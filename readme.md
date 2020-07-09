
```
mkdir /etc/kubesphere
cd /etc/kubesphere
git clone https://github.com/zackzhangkai/ks-developer-config.git
mv ks-devoper-config/* .
TMPDIR=/etc/kubesphere/

go run cmd/controller-manager/controller-manager.go --logtostderr=true --v=4 --kubeconfig=/Users/hugo/.kube/config
```
