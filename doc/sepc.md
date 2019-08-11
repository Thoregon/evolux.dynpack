dynpack
=======

* build dynamic packages depending on the terminal
    * browser only
    * with 'Ambur-Karbush'
    * with 'PULS'
* arranges layers and components for the target e.g.
    * local persitence
    * offline capabilities
    * remote processing
* uses rollup dynamically to transpile node only modules browser usable
 
##independent clients

run standalone, needs no 'backend' to communicate with. represents a full peer to sync with others.
is typically installed as app on the device.
 
##reliant clients

run in browser but retrives its content and packages from a service. the service may run on the same device/vm/container.
supports browser local data sync to mitigate unreachable services, but is not a full peer.
