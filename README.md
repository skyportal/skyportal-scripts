# SkyPortal Scripts

Scripts and notebooks to interact with the SkyPortal API.
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

Edit `.env`:
- Set `SKYPORTAL_URL` to your SkyPortal instance, e.g. `https://fritz.science/`, `https://skyportal-icare.ijclab.in2p3.fr/`, `https://orcusgate.org/`
- Set `SKYPORTAL_TOKEN` to your API token (found on the bottom of your SkyPortal /profile page)

## Usage

```bash
jupyter notebook fetch_candidates.ipynb
```

## Resources

- [SkyPortal](https://skyportal.io/)
- [API documentation](https://skyportal.io/docs/api.html)
