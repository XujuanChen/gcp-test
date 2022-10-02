# gcp-test
Google Cloud Platform deploy practice:

https://apptest20220925.ue.r.appspot.com/

open google cloud shell

git clone https://github.com/XujuanChen/gcp-test.git

ls

cd gcp-test

ls

gcloud app delpoy app.yaml

it will take about 10 minutes to deloy, when it's done

go to APP ENGINE -> Services -> click default to open the url

### How to remvove non-empty foder
remove folder on cloud shell:  rm -rf folder_name


# Use Cloud SDK to deploy

run python3 -V

Use the python3 interpreter on your path

run export CLOUDSDK_PYTHON=python3 

download Cloud SDK

run ./google-cloud-sdk/install.sh

run ./google-cloud-sdk/bin/gcloud init

choose a number for a project to connect

go to VScode -> setteing -> commad pallette -> Python: Create Terminal

run gcloud app deploy

expample: https://sdk-deploy-364316.ue.r.appspot.com
