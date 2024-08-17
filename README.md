# TEALS Python Environment
Quick portable Python environment with python CLI preinstalled + easy VSCode debugging

## Launching
1. Ensure you have Docker Desktop & VSCode installed
1. Clone this repo
1. Open in VSCode, and use the "Dev Containers: Open Folder in Container" command to pick this folder.
1. You should now have a CLI with `python` preinstalled, and a debug action "Debug File" which will launch the VSCode debugger for an active `.py` file.

## Running Python code
1. Use the VSCode integrated CLI with the `python` executable - e.g. `python src/printing/main.py`

## Debugging Python code
1. Set the active file in VSCode to the file you wish to debug. Set breakpoints if needed.
1. Launch the "Debug File" debug action in VSCode.