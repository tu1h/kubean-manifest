# :ledger: kubean-manifest
Managing manifest information about different releases of components within kubespray.


### How to use

``` bash
# download manifest file
$ wget https://raw.githubusercontent.com/kubean-io/kubean-manifest/main/manifests/manifest-${spray_release_num}-${short_commit_hash}.yml
# apply manifest file
$ kubectl apply -f manifests/manifest-${release_num}-${shot_commit_hash}.yml

# e.g:
$ wget https://raw.githubusercontent.com/kubean-io/kubean-manifest/main/manifests/manifest-2.23-10679eb.yml
$ kubectl apply -f manifests/manifest-2.23-10679eb.yml
```
