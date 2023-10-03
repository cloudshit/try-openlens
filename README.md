## install
https://github.com/MuhammedKalkan/OpenLens/releases

## intro
https://www.youtube.com/watch?v=eeDwdVXattc&ab_channel=k8slens-TheKubernetesIDE

## ssh tunneling for k8s
```
ssh -N -L 127.0.0.1:8080:<cluster_dns>:<cluster_port> ec2-user@<bastion_ip> -i <bastion_key>
```
