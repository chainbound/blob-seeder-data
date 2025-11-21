## Installation

Tested with `python 3.13.7` and `jupyterlab 4.4.10`

Required `pip` packages:

```
python-dotenv      # To read credentials file
jupysql            # SQL support for Jupyter
clickhouse-connect # Recommended clickhouse driver
numpy              # To give you headaches
pandas             # To give you multi-dimensional headaches
matplotlib         # To make it all worth it
```


## Credentials setup

Run this command and fill the missing fields with database credentials:

```sh
cat > .ethpandas_xatu_credentials.env << EOF
XATU_USERNAME='TODO'
XATU_PASSWORD='TODO'
XATU_EXPERIMENTAL_USERNAME='TODO'
XATU_EXPERIMENTAL_PASSWORD='TODO'
EOF
```

The file `.ethpandas_xatu_credentials.env` is in `.gitignore` and MUST remain there.
