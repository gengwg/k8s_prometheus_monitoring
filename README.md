# k8s_prometheus_monitoring

## Logging

- data about the state or an event  of an application or service
- often long form providing details about the state change

## Metering

- data about rate of change
- time-series based


monitoring looks at countable elements, while logging looks at messages.

POD container is part of the networking service. Auto created.

cadvisor data is already captured but needs to be filtered to show pod state.

a sidecar application in k8s is a container that lives within a pod that provides additional service.
used to capture data from application that doesn't have built-in prometheus support.

prom can't automatically capture multi pod application data. one need to aggregate it oneself.


