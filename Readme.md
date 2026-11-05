## Environment setup

## Windows
### Step 1: Install Python 
### Step 2: Install VS-code
### Step 3: Install uv
- download and install uv.exe:

`powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`

- check version : 

`uv --version`



## MAC & Linux
### Step 1: Install Python 
### Step 2: Install VS-code
### Step 3: Install uv
- download and install uv:

`curl -LsSf https://astral.sh/uv/install.sh | sh`

- check version : 

`uv --version`

## Common steps for MAC and python Starting a project in uv
-  Initialize a project inside a folder 
`uv init --bare`

- 