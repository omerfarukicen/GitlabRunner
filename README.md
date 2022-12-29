# GitlabRunner

## Register
 gitlab-runner register --tls-ca-file /home/maya/hmb.gov.tr.pem
gitlab-runner register

## Unregister
sudo gitlab-runner verify --delete
sudo gitlab-runner unregister -t 3b4cfc1dc4ef8fd7a25fcda8846e8a http://maya.muhasebat.gov.tr:81/
