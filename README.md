# visualization_scripts
US Map User Activity Visualization

Running 'visualizations_api.py' script will launch the API (by default on Port 5001, but configurable in main). Before running the script, make sure to change the DB login credentials near the top of the script.

The API endpoint is GET /get-state-counts, which returns a JSON object mapping all state abbreviations to counts of letters mailed in that state from the DB.

The front-end uses the DataMaps interface (http://datamaps.github.io) and fetches data from the API via AJAX.