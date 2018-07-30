## Running the tests
```
oc create -f domain-curator-secret.yml
```
oc get secrets
```
oc get secrets es-curator-secret -o yaml
```
oc create -f domain-elastic-curator-pod.yml
```
oc get events
```
oc rsh domain-elastic-curator-pod
```
oc logs domain-elastic-curator-pod
```
