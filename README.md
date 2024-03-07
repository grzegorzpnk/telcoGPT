# TelcoGPT

**Problem to be solved using this project**

TelcoGPT is a system designed to simplify comprehensively orchestrate and manage mobile networks on a cloud infrastructure.

**Why it is challanging today?**

To effectively manage 5G networks and its underlay cloud infrastructure you need to be fluent in tons of technologies. Starting from infra management, (e.g. ClusterAPI, Terraform, kubeadm), through 5G Network deployment (kpt, helm -> nephio) and observability (*OpenTelemetry*) compleet on continuum life-cycle management and cloosed loops (kubernetes). 
All of these tools ( provided list is not finalized and new technologies still appears!) requires knowledge of CLIs, rules, good-practices and so on.

**What is the challange?**

TelcoGPT offers high-level user interface in the form of human-level intents for all mentioned technologies. Please specify your intent( simple text format) and let LLM to interprete it 

**How to achieve?**

TelcoGPT relies on LLMs such as GPT, LLama, Falcon that seems to be not only good content creators, but as well interpreter of human intents.

**What is gained?**

TelcoGPT provides transparency layer between OSS intents/bussines persons/administrator ane underlying technologies to manage 5G. 
Once customized LLM allow to manage your network (or hundrets of different private network) for non-technical persons.
Even if new technology will appear, no need to administrator to learn it, it will be hidden in technological part.
