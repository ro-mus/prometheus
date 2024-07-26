## Kubernetes Plugin Script
This script fetches CPU and memory usage metrics for a specified resource type in a given namespace.

### Usage

* Rename as kubectl-{script-name}
* Move to your $PATH
* Make script executable _chmod +x kubectl-{script-name}_
* Run the plugin _kubectl {script-name} <resource_type> <namespace>_
    * <resource_type>: Type of resource (e.g., pods, nodes).
    * \<namespace>: Namespace containing the resources.
