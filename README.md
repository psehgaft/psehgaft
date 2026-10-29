![psehgaft banner](assets/banner.jpg)

# Hi there 👋, I'm Heber Romero Téllez — `psehgaft`

**Architect @ Red Hat** · OpenShift · Kubernetes · DevSecOps · FaaS · Open Source

[![LinkedIn][linkedin-shield]][linkedin-url]

- 😄 Pronouns: he / him
- 📫 How to reach me: **@psehgaft** — [psehgaft.org](https://psehgaft.org)

## ⚡ Me, as a serverless function

```yaml
apiVersion: serving.knative.dev/v1
kind: Service
metadata:
  name: psehgaft
  labels:
    role: architect
    company: Red Hat
    since: "2016"
spec:
  template:
    metadata:
      annotations:
        autoscaling.knative.dev/min-scale: "1"   # always on, always learning
    spec:
      containers:
        - image: psehgaft/architect:latest
          env:
            - name: EXPERTISE
              value: "OpenShift | Kubernetes | DevSecOps | Hybrid Cloud"
            - name: PASSION
              value: "containers, cloud and open-source adoption"
            - name: PRIORITY
              value: "never stop learning"
          resources:
            requests:
              coffee: "1 cup"
              curiosity: "unbounded"
```

## 🔭 I'm currently working on ...

```yaml
currentlyWorkingOn:
  - Red Hat
  - Containerizing Applications
  - FaaS
  - DevSecOps
  - App Dev CNDF
```

## 🌱 I'm currently learning ...

```console
psehgaft@redhat:~$ cat currently_learning.txt
Computer systems
Dev Apps
Cloud and Hybrid cloud
psehgaft@redhat:~$ uptime
 10 years @ Red Hat, load average: curiosity 100%, boredom 0.00
psehgaft@redhat:~$ sudo make knowledge --target=all
[sudo] password for psehgaft: ••••••••
Compiling... done. Learning never stops.
```

## 🛠️ Skills on the prompt

```bash
skills=(
  "Podman + Docker + OpenShift + Kubernetes ☸️"
  "Ansible + Terraform"
  "Java + Spring Boot + Quarkus"
  "JavaScript + Node + React + Vue + Angular"
  "Python + Flask"
  "C# + .NET + ASP MVC"
  "Kotlin + Android"
)
for s in "${skills[@]}"; do echo "✅ $s"; done
```

## 👯 I'm looking to collaborate on ...

OpenShift / FaaS / Open Source

## 🤔 I'm looking for help with

OpenShift / FaaS / Open Source

## 💬 Ask me about

OpenShift / FaaS / Open Source

## ⭐️ Notable Projects and Contributions

- 🌐 **[Open Ecosystem Services](https://github.com/Open-Industries/open-ecosystem-services)** — serverless interoperability reference architectures, with the Open Industries community
- 🐴 **[KubeVirt Migration — Solution Pattern](https://github.com/psehgaft/solution-pattern-kubevirt-migration)** — Red Hat solution pattern for migrating VMs to OpenShift Virtualization · [live site](https://psehgaft.github.io/solution-pattern-kubevirt-migration/)
- 🎤 **[KubeVirt Without Fear — TXLF 2026](https://github.com/JoeRH-OCP/unify-KubernetesKubevit-workflows-TXLF2026)** — hands-on KubeVirt workshop built for Texas Linux Festival 2026
- 🏛️ **[Architect Diagrams](https://github.com/psehgaft/architect-diagrams)** — reference architecture diagrams: AWS, Azure Red Hat OpenShift, OpenStack and OpenShift Virtualization
- 🏠 **[psehgaft.org](https://psehgaft.org)** — my personal site: repository catalog, open-world map and more · [source](https://github.com/psehgaft/psehgaft.github.io)

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=psehgaft&show_icons=true&theme=github_dark_dimmed&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage)

![](https://streak-stats.demolab.com?user=psehgaft&theme=dark)

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=psehgaft&theme=nord_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=psehgaft&theme=nord_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=psehgaft&theme=nord_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=psehgaft&theme=nord_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=psehgaft&theme=nord_dark)

## 🌳 Árbol de la Vida — The Sefirot

*Diez emanaciones, un solo árbol: la estructura con la que el universo — y el buen código — se sostiene.*

```mermaid
graph TD
    subgraph Right["Pilar de la Misericordia"]
        CH["Chokhmah · Sabiduría"]
        CE["Chesed · Misericordia"]
        NE["Netzach · Victoria"]
    end
    subgraph Middle["Pilar del Equilibrio"]
        KE["Keter · Corona"]
        TI["Tiferet · Belleza"]
        YE["Yesod · Fundamento"]
        MA["Malkuth · Reino"]
    end
    subgraph Left["Pilar de la Severidad"]
        BI["Binah · Entendimiento"]
        GE["Gevurah · Juicio"]
        HO["Hod · Esplendor"]
    end
    KE --- CH
    KE --- BI
    KE --- TI
    CH --- BI
    CH --- CE
    CH --- TI
    BI --- GE
    BI --- TI
    CE --- GE
    CE --- TI
    CE --- NE
    GE --- TI
    GE --- HO
    TI --- NE
    TI --- HO
    TI --- YE
    NE --- HO
    NE --- YE
    NE --- MA
    HO --- YE
    HO --- MA
    YE --- MA
    classDef crown fill:#2b1055,stroke:#ffd700,stroke-width:2px,color:#ffffff
    classDef right fill:#123a6d,stroke:#4da3ff,color:#ffffff
    classDef left fill:#6d1220,stroke:#ff4d5e,color:#ffffff
    classDef middle fill:#14532d,stroke:#4dff88,color:#ffffff
    class KE crown
    class CH,CE,NE right
    class BI,GE,HO left
    class TI,YE,MA middle
```

## ⚡ Fun fact

Always happy to help.

🎓 [Red Hat certification](https://rhtapps.redhat.com/verify?certId=170-241-434) · 🏅 [Credly badges](https://www.credly.com/users/psehgaft/badges) · ☕ [Buy me a coffee on Ko-fi](https://ko-fi.com/psehgaft)

[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/psehgaft/
