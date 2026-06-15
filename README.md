# Jupyter Notebook (jupyter-notebook)

Jupyter Notebook is the original open-source web application for creating and sharing computational documents that contain live code, equations, visualizations, and narrative text. The Jupyter Notebook server exposes a REST API for managing notebooks, files, kernels, sessions, and terminals, and uses the WebSocket-based Jupyter messaging protocol to communicate with kernels.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Data Science
- Interactive Computing
- Jupyter
- Machine Learning
- Notebooks
- Python

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Jupyter Notebook REST API

REST API for managing and interacting with Jupyter Notebook servers, including kernels, sessions, contents (notebooks and files), terminals, and kernel specifications.

- **Human URL:** [https://jupyter-notebook.readthedocs.io/](https://jupyter-notebook.readthedocs.io/)
- **Base URL:** `http://localhost:8888/api`

#### Tags

- Contents
- Files
- Kernels
- Notebooks
- REST API
- Sessions

#### Properties

- [Documentation](https://jupyter-notebook.readthedocs.io/en/stable/rest_api.html)
- [Repository](https://github.com/jupyter/notebook)
- [OpenAPI](openapi/jupyter-notebook-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jupyter-notebook-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyter-notebook-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/jupyter-notebook-document.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jupyter-contents-model.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jupyter-kernel-spec.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/jupyter-notebook-context.jsonld)

### Jupyter Kernel Gateway API

Web server that provides headless access to Jupyter kernels for remote execution of code, with kernel and notebook HTTP modes.

- **Human URL:** [https://jupyter-kernel-gateway.readthedocs.io/](https://jupyter-kernel-gateway.readthedocs.io/)
- **Base URL:** `http://localhost:8888`

#### Tags

- Execution
- Gateway
- Headless
- Kernels

#### Properties

- [Documentation](https://jupyter-kernel-gateway.readthedocs.io/en/latest/)
- [Repository](https://github.com/jupyter-server/kernel_gateway)
- [OpenAPI](openapi/jupyter-kernel-gateway-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jupyter-kernel-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyter-kernel-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### JupyterHub REST API

Multi-user server management API for spawning, managing, and proxying multiple instances of single-user Jupyter notebook servers.

- **Human URL:** [https://jupyterhub.readthedocs.io/](https://jupyterhub.readthedocs.io/)
- **Base URL:** `http://localhost:8000/hub/api`

#### Tags

- Authentication
- Hub
- Multi-User
- REST API

#### Properties

- [Documentation](https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html)
- [Repository](https://github.com/jupyterhub/jupyterhub)
- [OpenAPI](openapi/jupyterhub-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jupyterhub-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyterhub-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jupyter Kernel Messaging Protocol

WebSocket-based messaging protocol for communication between Jupyter clients and computational kernels. Supports code execution, introspection, completion, and rich output over shell, IOPub, stdin, and control channels.

- **Human URL:** [https://jupyter-client.readthedocs.io/en/stable/messaging.html](https://jupyter-client.readthedocs.io/en/stable/messaging.html)
- **Base URL:** `ws://localhost:8888`

#### Tags

- Kernels
- Messaging
- Real-Time
- WebSocket

#### Properties

- [Documentation](https://jupyter-client.readthedocs.io/en/stable/messaging.html)
- [Repository](https://github.com/jupyter/jupyter_client)
- [AsyncAPI](asyncapi/jupyter-kernel-messaging-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/jupyter-kernel-message.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/jupyter-notebook-context.jsonld)
- [Postman Collection](collections/jupyter-kernel-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyter-kernel-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/jupyter-notebook-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyter-notebook-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/jupyterhub-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyterhub-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/project-jupyter)
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
**URL:** https://apievangelist.com
