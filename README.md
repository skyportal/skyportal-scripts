# SkyPortal Scripts

Scripts and notebooks to interact with the SkyPortal API ([orcusgate.org](https://orcusgate.org/)).
See the [SkyPortal](https://skyportal.io) and [API](https://skyportal.io/docs/api.html) documentation for more details on available endpoints and usage.

## Installation

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Configuration

Copy the environment template and fill in your API token:

```bash
cp .env.default .env
```

Edit `.env` and replace `your_api_token_here` with your token (found on the bottom of your SkyPortal /profile page).

## Usage

```bash
jupyter notebook fetch_candidates.ipynb
```

## Resources

- [SkyPortal](https://skyportal.io/)
- [API documentation](https://skyportal.io/docs/api.html)
