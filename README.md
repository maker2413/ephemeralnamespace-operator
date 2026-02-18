# EphemeralNamespace Operator

This is my first attempt at building a Kubernetes operator. This operator adds a
custom resource called EphemeralNamespace that allows you to create a Kubernetes
Namespace that you intend to be deleted after the TTL (Time To Live) has
expired.

This is fantastic functionality if you want to enable developers to create
Namespaces for development or testing, but you don't want to hound them to clean
up after themselves, wasting money.
