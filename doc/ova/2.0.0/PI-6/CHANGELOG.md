This release notes includes new features, enhancements, and bug fixes added to the CORTX k8s OVA.


## Bug Fixes

- Restructure CSM-S3 integration code[CORTX-28035]
- [RGW] REST API to modify IAM user [CORTX-28042]
- Update CSM to work on Rocky Linux 8.2 [EOS-28018]
- Remove dependency on LDAP for user management [EOS-28020]
- Integrate Shutdown Signaling REST API with HA [EOS-25532]
- Manage user not able to edit self email id [EOS-26602]
- Support Bundle filter implementation [EOS-27251, EOS-28031]
- RGW sysconfig path needs changes [EOS-28564]
- populate CDF with rgw client details fetched from conf-store [EOS-27617]
- RGW: support multiple s3 motr client types in CDF [EOS-27808]
- RGW sysconfig path needs changes [EOS-28564]
- handle PVERF configuration object [CORTX-28926]
- nvec reply reports incorrect states for process tree [CORTX-25823]
- consul client agent status is not updated [CORTX-28823]
- hctl drive-state-set command does not work [EOS-28773]
- Motr endpoint ports are not configurable [EOS-23618]
- m0crate-io-conf util is broken [EOS-27636]
- Fix Hare cfgen tests [EOS-26855]
- device info accessed before saving [EOS-27016]
- find and fix all URLs in hare code [EOS-27301]
- hctl bootstrap is failing in latest hare main [EOS-27315]
- fix memleak in FDMI and its UT [EOS-28789]
- BE tool to dump CAS tree [EOS-27591]
- Motr QSG validation [EOS-27750]
- Motr Support Bundle generated by the script [EOS-27562]
- Detect max IOV limit from fabric attributes during run time [EOS-25947]
- CAS request should succeed even one put request is success [EOS-27288]
- fdmi UT fixes [EOS-27220]
- Update version for each component in bootstrap phase [EOS-28599]
- remove 3rd party mini provisioner calls [CORTX-28645]


## New Features

- Improvement in aux pool enable/disable implementation [EOS-25537]
- Improve http command for hctl status [EOS-27236]
- Optimize component bundle size - Motr [EOS-25683]
- MessageBus dynamic port from cluster conf file [EOS-27349]
- MessageBus as static instance [EOS-27346]
- IEM CLI integration with Event message [EOS-27255]
- Use noarch architecture for HA package [CORTX-27894]

