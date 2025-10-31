# curso-docker-kubernetes-tareas
## Título: "Tareas - Curso Docker & Kubernetes"

# Nombre: Limber Juan Romero Condori

**[Enlace curso de i-Quattro](https://www.i-quattro.com/product-page/dok-kub-001)**


## Indice del Curso

### Temario (10 puntos)

1. Introducción a containers (contenedores) y Docker
2. Manejo de images (imágenes), containers (contenedores) y networks (redes)
3. Docker avanzado y Docker Compose
4. Seguridad en imágenes y escaneo de vulnerabilidades
5. Arquitectura de Kubernetes
6. Pods, Deployments y Services
7. ConfigMaps, Secrets y Probes
8. Escalado automático (HPA) e Ingress
9. Observabilidad (logs, métricas, Prometheus/Grafana)
10. Proyecto final integrador

---

### Bloque 1: Docker (Clases 1-5)

- **[Clase 1: Introducción a Containers y Docker](bloque-docker/clase1-introduccion/)**
  - Instalación y configuración
  - Primeros containers: hello-world, nginx, ubuntu
  - Docker Hub y exploración de images oficiales

- **[Clase 2: Dockerfiles y Fundamentos de Compose](bloque-docker/clase2-dockerfiles/)**
  - Anatomía de un Dockerfile y multi-stage builds
  - Buenas prácticas de seguridad (non-root users)
  - Fundamentos previos a Compose (volúmenes, redes y anatomía del yaml)

- **[Clase 3: Docker Compose - Redes y Volúmenes](bloque-docker/clase3-compose/)**
  - Orquestación multi-contenedor con Docker Compose
  - Redes personalizadas y segmentación de servicios
  - Volúmenes para persistencia de datos

- **[Clase 4: Microservicios y Seguridad Básica](bloque-docker/clase4-microservicios/)**
  - Aplicación multi-contenedor con cache (Redis) y API Gateway
  - Comunicación entre servicios y frontend
  - Introducción a scans con Trivy y hardening inicial

- **[Clase 5: Seguridad Avanzada y Puente a Kubernetes](bloque-docker/clase5-seguridad/)**
  - Escaneo de vulnerabilidades con Trivy y optimización de imágenes
  - Técnicas avanzadas (multi-stage builds, Alpine, non-root)
  - Preview de Kubernetes: componentes y flujo declarativo

### Bloque 2: Kubernetes (Clases 6-7)

- **[Clase 6: Fundamentos de Kubernetes](bloque-kubernetes/clase6-introduccion/)**
  - Arquitectura de Kubernetes (Control Plane y Worker Nodes)
  - Pods, Deployments y Services (ClusterIP, NodePort, LoadBalancer con MetalLB)
  - Herramientas clave: labels, selectors y namespaces

- **[Clase 7: Kubernetes Avanzado](bloque-kubernetes/clase7-configuracion-persistencia/)**
  - Namespaces, ConfigMaps, Secrets, StatefulSets y PVC
  - Ingress, health probes (liveness/readiness/startup) y HPA
  - Observabilidad como bonus: guía Prometheus + Grafana



