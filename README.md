# calico-test-demo
resource files for network policy tester demo

* `calico-tester-demo.yml`: create the namespaces, deployments, services and networkpolicies in the cluster.

* `service-manager-clusterrole.yml`: cluster role that gives the service manager access to function properly.

* `service-manager-serviceaccount.yml`: create the service account for service manager.

* `service-manager-clusterrole-binding.yml`: bind the cluster role and the service account.

* `nginx-pod.yml`: create a nginx-pod in the default namespace.

* `nginx-service.yml`: expose the nginx-pod in the default namespace.
