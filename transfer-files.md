
How to download your files from a vm instance on google cloud on youe local machine?

with google cloud sdk:

go to the instance
read this link:
https://cloud.google.com/compute/docs/instances/transfer-files

e.g.; I used this command :

gcloud compute scp --recurse deeplearning-2-vm:/home/jupyter/exBERT C:/Users/marman2/Pythoncodes/vmgcloudexbert
