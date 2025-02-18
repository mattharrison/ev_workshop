# ev_workshop
ev workshop


## Installation

There are two options for installation:

1. Use Codespaces (the video walks through this):

 - Click on the green "Code" button. Then click on the "Codespaces" tab. Click the "+" button to create a codespace. 
 - Wait a minute or two for the Codespace to provision
 - Open the `viz-workshop.ipynb` notebook


2. Install with `uv`:

 - Install `uv` as per https://docs.astral.sh/uv/getting-started/installation/
 - Check out this project:
   
   ```bash
   git clone git@github.com:mattharrison/ev_workshop.git
   
   ```

 - Change into the directory of the project:

   ```bash
   cd ev_workshop
   ```

 - Run `uv sync` to build the environment.

 - Launch Jupyter with:

  ```bash
  uv run jupyter lab
  ```

 - Open `viz-workshop.ipynb` notebook

