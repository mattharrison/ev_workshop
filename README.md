# ev_workshop
ev workshop

Book is available at [https://store.metasnake.com/effective-viz](https://store.metasnake.com/effective-viz)

<img src='https://store.metasnake.com/content-assets/public/eyJhbGciOiJIUzI1NiJ9.eyJvYmplY3Rfa2V5IjoicmxvMWR6bXhxcTZ3M2JzeWR2aTBsc3F4NmlieSIsImRvbWFpbiI6InN0b3JlLm1ldGFzbmFrZS5jb20ifQ.CIHxa_vjm4kGRXdi5BdDIbkOLIjvKQ1xhpvwKmWsNGs' width="50%">

## Installation

There are a few different options for installation:

### Use Codespaces:

 - Click on the green "Code" button. Then click on the "Codespaces" tab. Click the "+" button to create a codespace. 
 - Wait a minute or two for the Codespace to provision
 - Open the `viz-workshop.ipynb` notebook


### Local install with `uv`:

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

### Pip install. Install packages in `pyproject.toml`

## Note

I use the *Roboto Condensed* font. You will get warnings if you don't have 
it installed. (The Codespace automatically installs it.)

https://fonts.google.com/specimen/Roboto+Condensed

