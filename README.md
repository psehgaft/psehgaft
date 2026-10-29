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

## 🌳 Tree of Life — The Sefirot

*Ten emanations, one single tree: the structure that sustains the universe — and good code.*

```mermaid
graph TD
    K["Keter · Purpose<br/>Build a meaningful life through architecture, knowledge, family, and growth"]
    C["Chokhmah · Vision<br/>Connect OpenShift, automation, AI, telecom, and new opportunities"]
    B["Binah · Structure<br/>Turn ideas into standards, plans, workshops, and well-grounded decisions"]
    D["Da'at · Integration<br/>Bring together technical experience, your thesis, mentorship, and shared learning"]
    H["Chesed · Generosity<br/>Guide, teach, and create room for others to grow"]
    G["Gevurah · Discipline and boundaries<br/>Set priorities, sustain habits, and protect your time, energy, and finances"]
    T["Tiferet · Center<br/>Be an architect, mentor, father, and whole person without reducing yourself to one role"]
    N["Netzach · Perseverance<br/>Keep advancing in your career, running, and moving forward through obstacles"]
    O["Hod · Communication<br/>Explain, document, and share through workshops, repositories, and community"]
    Y["Yesod · Foundation<br/>Weekly routines, health, rest, and tracking systems that support your goals"]
    M["Malkhut · Realization<br/>Visible results: published projects, professional growth, well-being, and presence with family"]

    K --> C
    K --> B
    C --- B

    C --> H
    B --> G
    H --- G

    H --> T
    G --> T
    C --> D
    B --> D
    D --> T

    T --> N
    T --> O
    N --- O

    N --> Y
    O --> Y
    T --> Y

    Y --> M

    classDef crown fill:#f4d35e,color:#222,stroke:#8a6d00,stroke-width:2px;
    classDef right fill:#ef476f,color:#fff,stroke:#8d1b35;
    classDef left fill:#118ab2,color:#fff,stroke:#07536b;
    classDef center fill:#7b2cbf,color:#fff,stroke:#3c096c,stroke-width:2px;
    classDef foundation fill:#06a77d,color:#fff,stroke:#045c46;
    classDef grounded fill:#333,color:#fff,stroke:#111,stroke-width:2px;

    class K crown;
    class C,H,N right;
    class B,G,O left;
    class D,T center;
    class Y foundation;
    class M grounded;
```

## ⚡ Fun fact

Always happy to help.

🎓 [Red Hat certification](https://rhtapps.redhat.com/verify?certId=170-241-434) · 🏅 [Credly badges](https://www.credly.com/users/psehgaft/badges) · ☕ [Buy me a coffee on Ko-fi](https://ko-fi.com/psehgaft)

[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/psehgaft/
