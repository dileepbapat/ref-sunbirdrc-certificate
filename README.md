## ref-sunbirdrc-certificate
Reference sample of certificate registry using Sunbird RC

# Run your own certificate registry in 5 minutes 


Prerequesite:
* docker
* docker-compose
* git (or download the zip)

1. run `git clone https://github.com/dileepbapat/ref-sunbirdrc-certificate.git`
2. cd ref-sunbirdrc-certificate
3. run `docker-compose pull`
4. run `docker-compose up -d --force-recreate`

API sample is available in jupyter notebook, needs additional dependency of python and jupyter. 
check certificate-api.ipynb

## Troubleshooting
run `docker-compose logs -f registry` and check logs
