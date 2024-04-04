# virtlab

#setup

----
oc new-project user1

oc process -f build-template.yaml -p NAME="bookbag" -p GIT_REPO="https://github.com/jeanchlopez/roadshow_ocpvirt_instructions.git" | oc apply -f -
imagestream.image.openshift.io/bookbag created
buildconfig.build.openshift.io/bookbag created

oc start-build bookbag --follow

oc get route <- To get the URL to view the lab content
----

#URLs

#Fedora 39 QCOW2
- https://download.fedoraproject.org/pub/fedora/linux/releases/39/Cloud/x86_64/images/Fedora-Cloud-Base-39-1.5.x86_64.qcow2

#Bootable Images
- quay.io/containerdisks/centos-stream:8-latest
- quay.io/containerdisks/centos-stream:9-latest

#Windows 2019 Server
- https://go.microsoft.com/fwlink/p/?LinkID=2195167&clcid=0x409&culture=en-us&country=US
