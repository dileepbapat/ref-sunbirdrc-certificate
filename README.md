# ref-sunbirdrc-certificate
Reference sample of certificate registry using Sunbird RC

Prerequesite:
* docker
* docker-compose
* git (or download the zip)

1. run `git clone https://github.com/dileepbapat/ref-sunbirdrc-certificate.git`
2. cd ref-sunbirdrc-certificate
3. run `docker-compose up -d`

API sample is available in jupyter notebook, needs additional dependency of python and jupyter. 
check certificate-api.ipynb

## Troubleshooting
run `docker-compose logs -f registry` and check logs
