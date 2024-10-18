# f5-bd-openshift-virt-migration
Sample manifest files to facilitate migrations to OpenShift Virtualization for the DevCentral article  
https://community.f5.com/kb/technicalarticles/vmware-to-red-hat-openshift-virtualization-migration/334264

The VM optimization settings are are inspired by https://docs.openshift.com/container-platform/4.16/virt/vm_networking/virt-using-dpdk-with-sriov.html. Yet to try is the use of huge pages.

For platform optimization, I have used additional optimization settings in Kubelet besides the ones indicated in the link above. Yet to try is the use full-pcpus-only=true.
