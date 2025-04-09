Role Name
=========

This role will install kuberay for researchers

Requirements
------------

TBD

Role Variables
--------------

|| Variable || Default || Notes ||
| KUBERAY_OPERATOR_CHART_VERSION | 1.3.0 | chart version of the kuberay operator |
| KUBERAY_OPERATOR_NAMESPACE | "kuberay | namespace to install kuberay operator |
| RAY_CLUSTER_CHART_VERSION | 1.3.0 | chart version of the ray cluster |
| RAY_CLUSTER_NAMESPACE | "default" | namespace to install ray cluster |


Dependencies
------------

TBD

Example Playbook
----------------

See `example-playbook.yaml`. To execute, you can do something like `ansible-playbook -i hosts.yaml example-playbook.yaml`

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
