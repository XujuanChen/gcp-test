# gcp-test
Google Cloud Platform deploy practice:<br />
https://apptest20220925.ue.r.appspot.com/ <br />

open google cloud shell<br />
git clone https://github.com/XujuanChen/gcp-test.git<br />
ls<br />
cd gcp-test<br />
ls<br />
gcloud app delpoy app.yaml<br />
<br />
<br />
it will take about 10 minutes to deloy, when it's done,<br />
go to APP ENGINE -> Services -> click default to open the url<br />

<br />
remove folder on cloud shell:  rm -rf folder_name<br />

<br/>
Use Cloud SDK

run python3 -V

Use the python3 interpreter on your path

run export CLOUDSDK_PYTHON=python3 

download Cloud SDK

run ./google-cloud-sdk/install.sh

run ./google-cloud-sdk/bin/gcloud init

choose a number for a project to connect

