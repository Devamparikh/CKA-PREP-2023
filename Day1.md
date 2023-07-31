Cluster Architecture

- Master Node
- Worker Nodes
- ETCD Cluster (store key value pair)
- kube-scheduler
- kube controller manager
- container runtime engine
- to interact with master node there is Kube-apiserver
- to interact with worker nodes there is kubelet
- kube-proxy (communication between services)


Any container technology such as Docker can be run on kubernetes with the help of container runtime interface (CRI). This CRI use Open Container Initiative (OCI) as to validate images from imagespec and its development from runtimespec.

CRI CTL Tools
- nerdctl
- crictl (only for debugging as kubelet is not aware of it).

ETCD
It is a distributed reliable key-value store that is simple, secure and fast.

key-value store
document and files.
simple to install - download binary, extract and run service. (PORT: 2379)
export ETCD_API=3 to use that version.

Kube-apiserver




