# OPNFV-ODL-SFC
This is a repository for development on resource-aware VNFFG (or IFG) Construction Algorithm based on OpenStack Tacker and OPNFV SFC projects. 
Currently, VNFFG Manager in Tacker determines VNF instances to be included in the VNFFG instance in a random manner. The proposed resource-aware VNFFG Construction Algorithm will construct VNFFG instance with the consideration of resource status on running VNF instances.

The 'Working History' table shows the events related to the VNFFG Construction Algorithm.

> ### Working History
| Date    | Target Project               | Contents                                                                                                                                                                                                              | Remarks                            |
|---------|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------|
| 2016/10 | OpenStack Tacker / OPNFV SFC | Offline meeting with OpenStack Tacker developer to discuss on the VNFFG Construction Algorithm                                                                                                                        | OpenDaylight Summit 2016 (Seattle) |
| 2017/03 | OpenStack Tacker / OPNFV SFC | Studies on existing Tacker specs and features                                                                                                                                                                         |                                    |
| 2017/04 | OpenStack Tacker / OPNFV SFC | Code analysis on Tacker VNFFG Manager and test existing VNFFG construction method                                                                                                                                     |                                    |
| 2017/05 | OpenStack Tacker / OPNFV SFC | Offline meeting with OpenStack Tacker PTL to discuss on the VNFFG Construction Algorithm. One of the main concerns is that the current Tacker does not support resource related metrics on the running VNF instances. | OpenStack Summit 2017 (Boston)     |
