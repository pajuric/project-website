---
role: daemon
artifact_id: opensearch
version: 2.19.0
platform: docker
architecture: arm64
slug: opensearch-2.19.0-docker-arm64
category: opensearch
type: docker
inline_instructions:
- label: "Docker Hub"
  code: docker pull opensearchproject/opensearch:2.19.0
  link:
    label: View on Docker Hub
    url: https://hub.docker.com/r/opensearchproject/opensearch/tags?page=1&ordering=last_updated&name=2.19.0
- label: "Amazon ECR"
  code: docker pull public.ecr.aws/opensearchproject/opensearch:2.19.0
  link:
    label: View on Amazon ECR
    url: https://gallery.ecr.aws/opensearchproject/opensearch
---