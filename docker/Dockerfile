# Use the latest Python image as the base
FROM python:latest

# Set the working directory in the container
WORKDIR /workspace

# Copy only the requirements file first (helps with Docker layer caching)
COPY requirements.txt /workspace/

# Install the dependencies from requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Create VSCode settings for notebook customization
RUN mkdir -p /root/.vscode-server/data/Machine && \
    echo '{' > /root/.vscode-server/data/Machine/settings.json && \
    echo '    "editor.lineHeight": 17,' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    "breadcrumbs.enabled": false,' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    "notebook.insertToolbarLocation": "notebookToolbar",' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    "notebook.showCellStatusBar": "hidden",' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    "notebook.cellToolbarLocation": {' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '        "jupyter-notebook": "hidden"' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    },' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    "notebook.globalToolbar": false,' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    "notebook.experimental.outputScrolling": true,' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '    "notebook.consolidatedRunButton": true' >> /root/.vscode-server/data/Machine/settings.json && \
    echo '}' >> /root/.vscode-server/data/Machine/settings.json

# Copy all contents into the container (for the initial build only)
COPY . /workspace/

# Expose the Jupyter Notebook port
EXPOSE 8888

# Start Jupyter Notebook server by default
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--no-browser", "--allow-root"]

