# virtlab

#setup

~~~~
oc new-project user1

oc process -f build-template.yaml -p NAME="bookbag" -p GIT_REPO="https://github.com/jeanchlopez/roadshow_ocpvirt_instructions.git" | oc apply -f -

oc start-build bookbag --follow

oc get route <- To get the URL to view the lab content
~~~~
# update your ssh keys
~~~~
Update your SSH keys
training RSA private key in ~/.ssh
training RSA public key in ~/.ssh to load in secret
Download virtctl on your laptop
Create Fedora based VM
Add SSH public key to secret
Start VM
virtctl -n mylab-bookbag ssh fedora@fedora01 --identity-file=~/.ssh/training
~~~~


SSH Private key
~~~~
-----BEGIN OPENSSH PRIVATE KEY-----
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
fy9jU4BcqzGlJceZhlS0jxc0TTw=
-----END OPENSSH PRIVATE KEY-----
~~~~

#SSH pubic Key
~~~~
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCjNsH6pfaKnus8/TmOkNOIw3z/5w4G1iyZ1km8jctWMxrsGfdaMvIH/m/gwto3wSC/7KVEDp2uGnJHmSKYnlFaL3Sg9RU/40sQLYuTV588MRrUBxFsf7eeVUiMp4WriEOmeM/SHWC8GdjhY9xCJifzf/+WAvu+ZabaZp+WQMgJpdgN+t5eUUWrFrlJmxWDEzRw4Ug/5kNqHlhyxe3AqVNmIbkeJjwCvjFTtULkczi0ZikRN7UzZjQsOe+EHb3pkBvCkOvj2jVaKCBfKc2Qe5f5dIXUB1su96iigxhGJbtELkWtvQvrQ+dZCeeqZaZe6tjfqvFududnhuBZSSTOKJmxgmqg33WYNdasdbILfAH46N4pYpJcmfqoA6ORgUHkulJrPMY6gzGKIoqwK/WPKfc92TEDMRd1ZvogJOAR+wHEkaqORziACZp5zqIMuBZSINB/5IAeq3XXYWo3EZ9iZVWTVcOrFosI7f0IlLThlF76Le8GFdzm0zHsRowv+H7OHDk= jcl@IMBP-13.local
~~~~

#URLs

#Fedora 39 QCOW2
- https://download.fedoraproject.org/pub/fedora/linux/releases/39/Cloud/x86_64/images/Fedora-Cloud-Base-39-1.5.x86_64.qcow2

#Bootable Images
- quay.io/containerdisks/centos-stream:8-latest
- quay.io/containerdisks/centos-stream:9-latest

#Windows 2019 Server
- https://go.microsoft.com/fwlink/p/?LinkID=2195167&clcid=0x409&culture=en-us&country=US


~~~~
1	https://console-openshift-console.apps.66075cbd33dadd001d8d80bc.cloud.techzone.ibm.com/	zHNNW-43bdn-TC3Yn-JehdH	xyzwxFjb	ssh admin@api.66075cbd33dadd001d8d80bc.cloud.techzone.ibm.com -p 40222
2	https://console-openshift-console.apps.66075d32698e33001e426c66.cloud.techzone.ibm.com/	gitDK-ga2hX-SSP4I-6LpTP	43PsPek8	ssh admin@api.66075d32698e33001e426c66.cloud.techzone.ibm.com -p 40222
3	https://console-openshift-console.apps.66075de0ba4d77001e72389e.cloud.techzone.ibm.com/	yYbhh-p2a9K-5o98s-S3eYY	gmkhDwUw	ssh admin@api.66075de0ba4d77001e72389e.cloud.techzone.ibm.com -p 40222
4	https://console-openshift-console.apps.660c79b5a2354c001edff36a.cloud.techzone.ibm.com/	LM9fx-qo3YF-cGhqK-MDgNu	TYsy27O3	ssh admin@api.660c79b5a2354c001edff36a.cloud.techzone.ibm.com -p 40222
5	https://console-openshift-console.apps.660c7a283abee4001ecaab73.cloud.techzone.ibm.com/	vgeYf-FJEmE-yEiZ8-PuETX	T8ZUv4KL	ssh admin@api.660c7a283abee4001ecaab73.cloud.techzone.ibm.com -p 40222
6	https://console-openshift-console.apps.660c7a957b1030001e66301c.cloud.techzone.ibm.com/	VUqq2-S39z6-D5fTn-P4Wr5	Uk5r397R	ssh admin@api.660c7a957b1030001e66301c.cloud.techzone.ibm.com -p 40222
7	https://console-openshift-console.apps.660ca750a2354c001edff37e.cloud.techzone.ibm.com/	8AN8m-TvWxG-DW6pi-a3nYY	hWRtNIeW	ssh admin@api.660ca750a2354c001edff37e.cloud.techzone.ibm.com -p 40222
8	https://console-openshift-console.apps.660ca7d0a2354c001edff37f.cloud.techzone.ibm.com/	WQBgE-uvYrm-Kqi4W-YPuID	iZB4nOeQ	ssh admin@api.660ca7d0a2354c001edff37f.cloud.techzone.ibm.com -p 40222
9	https://console-openshift-console.apps.660cae5f3abee4001ecaab91.cloud.techzone.ibm.com/	6dZSj-J6KrW-tJUAr-9yAQj	tCPRJ4b8	ssh admin@api.660cae5f3abee4001ecaab91.cloud.techzone.ibm.com -p 40222
10	https://console-openshift-console.apps.660cc8aa0a1be8001e6a990c.cloud.techzone.ibm.com/	tCpXQ-43ykW-sG2r3-bxNPx	iWrVtFOm	ssh admin@api.660cc8aa0a1be8001e6a990c.cloud.techzone.ibm.com -p 40222
11	https://console-openshift-console.apps.660cc940a2354c001edff39d.cloud.techzone.ibm.com/	vCoek-ndyoM-Xpcct-cicNH	dLGWKK45	ssh admin@api.660cc940a2354c001edff39d.cloud.techzone.ibm.com -p 40222
12	https://console-openshift-console.apps.660cd2d57b1030001e6630d8.cloud.techzone.ibm.com/	cMDY6-Fzvub-fsKCx-rvzsy	PzFUtDkf	ssh admin@api.660cd2d57b1030001e6630d8.cloud.techzone.ibm.com -p 40222
13	https://console-openshift-console.apps.660d7ee1d6d28a001e312a05.cloud.techzone.ibm.com/	Ex8F6-UBz2U-6VSIY-WhPhE	JCrofHmq	ssh admin@api.660d7ee1d6d28a001e312a05.cloud.techzone.ibm.com -p 40222
14	https://console-openshift-console.apps.660d7fa8d6d28a001e312a06.cloud.techzone.ibm.com/	5ZR3A-mf4Sp-SCbWM-R5BWP	LF0GcYWY	ssh admin@api.660d7fa8d6d28a001e312a06.cloud.techzone.ibm.com -p 40222
15	https://console-openshift-console.apps.660d800ba2354c001edff4d5.cloud.techzone.ibm.com/	m4URa-pwbzd-zFFma-33GBP	AwSIgSIz	ssh admin@api.660d800ba2354c001edff4d5.cloud.techzone.ibm.com -p 40222
16	https://console-openshift-console.apps.660f48eb28bcbb001e048990.cloud.techzone.ibm.com/	9YXZc-y5YLs-cxPzx-umTiR	u7m1E27S	ssh admin@api.660f48eb28bcbb001e048990.cloud.techzone.ibm.com -p 40222
~~~~
