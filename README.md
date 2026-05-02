# Jupyter Notebook (jupyter-notebook)

Jupyter Notebook is the original open-source web application for creating and sharing computational documents that contain live code, equations, visualizations, and narrative text. The Jupyter Notebook server exposes a REST API for managing notebooks, files, kernels, sessions, and terminals, and uses the WebSocket-based Jupyter messaging protocol to communicate with kernels.

**APIs.yml:** [https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml)

## Tags

- Data Science
- Interactive Computing
- Jupyter
- Machine Learning
- Notebooks
- Python

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### Jupyter Notebook REST API

REST API for managing and interacting with Jupyter Notebook servers, including kernels, sessions, contents (notebooks and files), terminals, and kernel specifications.

**Human URL:** https://jupyter-notebook.readthedocs.io/

**Base URL:** http://localhost:8888/api

#### Tags

- Contents, Files, Kernels, Notebooks, REST API, Sessions

#### Properties

- [Documentation](https://jupyter-notebook.readthedocs.io/en/stable/rest_api.html)
- [Repository](https://github.com/jupyter/notebook)
- [OpenAPI](openapi/jupyter-notebook-rest-api-openapi.yml)
- [JSONSchema](json-schema/jupyter-notebook-document.json)
- [JSONSchema](json-schema/jupyter-contents-model.json)
- [JSONSchema](json-schema/jupyter-kernel-spec.json)
- [JSONLDContext](json-ld/jupyter-notebook-context.jsonld)

### Jupyter Kernel Gateway API

Web server that provides headless access to Jupyter kernels for remote execution of code, with kernel and notebook HTTP modes.

**Human URL:** https://jupyter-kernel-gateway.readthedocs.io/

**Base URL:** http://localhost:8888

#### Tags

- Execution, Gateway, Headless, Kernels

#### Properties

- [Documentation](https://jupyter-kernel-gateway.readthedocs.io/en/latest/)
- [Repository](https://github.com/jupyter-server/kernel_gateway)
- [OpenAPI](openapi/jupyter-kernel-gateway-api-openapi.yml)

### JupyterHub REST API

Multi-user server management API for spawning, managing, and proxying multiple instances of single-user Jupyter notebook servers.

**Human URL:** https://jupyterhub.readthedocs.io/

**Base URL:** http://localhost:8000/hub/api

#### Tags

- Authentication, Hub, Multi-User, REST API

#### Properties

- [Documentation](https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html)
- [Repository](https://github.com/jupyterhub/jupyterhub)
- [OpenAPI](openapi/jupyterhub-rest-api-openapi.yml)

### Jupyter Kernel Messaging Protocol

WebSocket-based messaging protocol for communication between Jupyter clients and computational kernels. Supports code execution, introspection, completion, and rich output over shell, IOPub, stdin, and control channels.

**Human URL:** https://jupyter-client.readthedocs.io/en/stable/messaging.html

**Base URL:** ws://localhost:8888

#### Tags

- Kernels, Messaging, Real-Time, WebSocket

#### Properties

- [Documentation](https://jupyter-client.readthedocs.io/en/stable/messaging.html)
- [Repository](https://github.com/jupyter/jupyter_client)
- [AsyncAPI](asyncapi/jupyter-kernel-messaging-asyncapi.yml)
- [JSONSchema](json-schema/jupyter-kernel-message.json)
- [JSONLDContext](json-ld/jupyter-notebook-context.jsonld)

## Common Properties

- [Website](https://jupyter.org)
- [Documentation](https://docs.jupyter.org/en/latest/)
- [Getting Started](https://docs.jupyter.org/en/latest/start/index.html)
- [Blog](https://blog.jupyter.org/)
- [GitHub Organization](https://github.com/jupyter)
- [Community](https://jupyter.org/community)
- [Support](https://discourse.jupyter.org/)
- [Security](https://jupyter.org/security)
- [YouTube](https://www.youtube.com/@ProjectJupyter)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/jupyter-notebook)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
