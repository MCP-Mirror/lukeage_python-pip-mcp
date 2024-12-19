# python-pip-mcp

Minimal Example Implementation of an Anthropic MCP Server and Client in Python and Pip. 

The goal was to have easy accessable debug functionality in VSCode and Windows for the server and client in the same session.

## Installation

```powershell
# create venv
python -m venv myenv
myenv\Scripts\activate

# install requirements
pip install -r requirements.txt

# create a .env file and set your anthropic api key
cp .env.sample .env

# run mcp_client.py script
python mcp_client.py

# ask for current time
```

