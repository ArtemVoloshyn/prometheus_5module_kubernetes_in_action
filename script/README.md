Hi, this is script/plugin to see resource usage statistics from Kubernetes.

use this to start script with default parameters (top, pods, kube-system) 
```./kubeplugin ```
or you can add you desire parameters 

to execute script wih ```kubectl``` command make ```kubeplugin``` executable with ```sudo chmod +x ./kubeplugin``` and then use this ```sudo cp ./kubeplugin /usr/local/bin/kubectl-kubeplugin``` 