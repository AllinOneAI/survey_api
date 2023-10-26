# survey_api
python -m venv survey_api
cd survey_api
source bin/activate
python -m pip install pip-tools
pip-compile
pip-sync
