# 🚀 Awesome Kubernetes

Repositório com exemplos práticos e organizados de objetos Kubernetes, reunindo arquivos YAML prontos para facilitar o aprendizado e a implementação de recursos essenciais no cluster.

## 🎯 Objetivo

Este repositório tem como objetivo servir como um guia prático para quem está começando ou deseja consultar rapidamente exemplos de configuração no Kubernetes. Todos os arquivos estão em formato YAML e seguem uma estrutura didática para facilitar a compreensão.

## 📁 Estrutura do Repositório

O repositório está dividido por tipo de recurso:

- `autoscaler/`: Exemplos de escalonamento automático de pods.
- `cert-manager/`: Configurações para gerenciamento automático de certificados TLS.
- `configMap/`: Modelos de uso do ConfigMap para configuração desacoplada.
- `daemonset/`: Deployments que rodam em todos os nós do cluster.
- `deployment/`: Diversos exemplos de Deployments.
- `ingress/`: Exemplos de regras de Ingress para exposição de serviços.
- `job/`: Exemplos de Jobs e CronJobs.
- `namespace/`: Definição de Namespaces.
- `networkpolicy/`: Políticas de rede para isolamento de comunicação.
- `pod/`: Configuração básica de pods.
- `probes/`: Exemplos de liveness e readiness probes.
- `replicaset/`: Definição de ReplicaSets.
- `secret/`: Manejo de informações sensíveis.
- `security/`: Configurações relacionadas à segurança (como PodSecurityPolicy).
- `service/`: Exposição de serviços dentro e fora do cluster.
- `statefulset/`: Modelos para aplicações com estado.
- `volumes/`: Exemplos de volumes e montagens de dados.

## 📚 Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Anselming/awesome-kubernetes.git
   ```
2. Escolha a pasta correspondente ao recurso que deseja estudar.
3. Aplique o YAML com o `kubectl`:
   ```bash
   kubectl apply -f <arquivo>.yaml
   ```

## ✅ Requisitos

- Ter um cluster Kubernetes configurado (Minikube, Kind, GKE, EKS, etc.)
- `kubectl` instalado e configurado

## 🙌 Contribuições

Contribuições são bem-vindas! Caso tenha sugestões ou novos exemplos, fique à vontade para abrir um *pull request* ou uma *issue*.

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

> Feito com dedicação por [@Anselming](https://github.com/Anselming) 🧑‍💻
