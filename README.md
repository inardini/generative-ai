# Generative AI

> NOTE: [Gemini 2.5 Pro](https://cloud.google.com/vertex-ai/generative-ai/docs/gemini-v2) has been released!
>
> Here are the latest notebooks and demos using the new models:
>
> - [Intro to Gemini 2.5 Pro](gemini/getting-started/intro_gemini_2_5_pro.ipynb)

<!-- markdownlint-disable MD033 -->

This repository contains notebooks, code samples, sample apps, and other resources that demonstrate how to use, develop and manage generative AI workflows using [Generative AI on Google Cloud](https://cloud.google.com/ai/generative-ai) with [Vertex AI](https://cloud.google.com/vertex-ai).

## Using this repository

[![Applied AI Summit: The cloud toolkit for generative AI](https://img.youtube.com/vi/xT7WW2SKLfE/hqdefault.jpg)](https://www.youtube.com/watch?v=xT7WW2SKLfE)

<table>
  <tr>
    <th></th>
    <th style="text-align: center;">Description</th>
  </tr>
  <tr>
    <td>
      <img src="https://storage.googleapis.com/github-repo/img/gemini/Spark__Gradient_Alpha_100px.gif" width="45px" alt="Gemini">
      <br>
      <a href="gemini/"><code>gemini/</code></a>
    </td>
    <td>
      Discover Gemini through starter notebooks, use cases, function calling, sample apps, and more.
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://www.gstatic.com/images/branding/gcpiconscolors/service_discovery/v1/24px.svg" width="40px" alt="Search">
      <br>
      <a href="search/"><code>search/</code></a>
    </td>
    <td>Use this folder if you're interested in using <a href="https://cloud.google.com/enterprise-search">Vertex AI Search</a>, a Google-managed solution to help you rapidly build search engines for websites and across enterprise data. (Formerly known as Enterprise Search on Generative AI App Builder).</td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/nature_people/default/40px.svg" alt="RAG Grounding">
      <br>
      <a href="rag-grounding/"><code>rag-grounding/</code></a>
    </td>
    <td>Use this folder for information on Retrieval Augmented Generation (RAG) and Grounding with Vertex AI. This is an index of notebooks and samples across other directories focused on this topic.</td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/image/default/40px.svg" alt="Vision">
      <br>
      <a href="vision/"><code>vision/</code></a>
    </td>
    <td>
      Use this folder if you're interested in building your own solutions from scratch using features from Imagen on Vertex AI (Vertex AI Imagen API).
      These are the features that Imagen on Vertex AI offers:
      <ul>
        <li>Image generation</li>
        <li>Image editing</li>
        <li>Visual captioning</li>
        <li>Visual question answering</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/mic/default/40px.svg" alt="Speech">
      <br>
      <a href="audio/"><code>audio/</code></a>
    </td>
    <td>
      Use this folder if you're interested in building your own solutions from scratch using features from Chirp, a version of Google's Universal Speech Model (USM) on Vertex AI (Vertex AI Chirp API).
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/build/default/40px.svg" alt="Setup Env">
      <br>
      <a href="setup-env/"><code>setup-env/</code></a>
    </td>
    <td>Instructions on how to set up Google Cloud, the Vertex AI Python SDK, and notebook environments on Google Colab and Vertex AI Workbench.</td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/media_link/default/40px.svg" alt="Resources">
      <br>
      <a href="RESOURCES.md"><code>RESOURCES.md</code></a>
    </td>
    <td>Learning resources (e.g. blogs, YouTube playlists) about Generative AI on Google Cloud.</td>
  </tr>
</table>
<!-- markdownlint-enable MD033 -->

## Related Repositories

- ✨ [Agent Development Kit (ADK) Samples](https://github.com/google/adk-samples): This repository provides ready-to-use agents built on top of the Agent Development Kit, designed to accelerate your development process. These agents cover a range of common use cases and complexities, from simple conversational bots to complex multi-agent workflows.
- [🚀 Agent Starter Pack](https://github.com/GoogleCloudPlatform/agent-starter-pack)
  - A collection of production-ready Generative AI Agent templates built for Google Cloud.
  - It accelerates development by providing a holistic, production-ready solution, addressing common challenges (Deployment & Operations, Evaluation, Customization, Observability) in building and deploying Gen AI agents.
- [Gemini Cookbook](https://github.com/google-gemini/cookbook/)
- [Google Cloud Applied AI Engineering](https://github.com/GoogleCloudPlatform/applied-ai-engineering-samples)
- [Generative AI for Marketing using Google Cloud](https://github.com/GoogleCloudPlatform/genai-for-marketing)
- [Generative AI for Developer Productivity](https://github.com/GoogleCloudPlatform/genai-for-developers)
- Vertex AI Core
  - [Vertex AI Samples](https://github.com/GoogleCloudPlatform/vertex-ai-samples)
  - [MLOps with Vertex AI](https://github.com/GoogleCloudPlatform/mlops-with-vertex-ai)
  - [Developing NLP solutions with T5X and Vertex AI](https://github.com/GoogleCloudPlatform/t5x-on-vertex-ai)
  - [AlphaFold batch inference with Vertex AI Pipelines](https://github.com/GoogleCloudPlatform/vertex-ai-alphafold-inference-pipeline)
  - [Serving Spark ML models using Vertex AI](https://github.com/GoogleCloudPlatform/vertex-ai-spark-ml-serving)
  - [Sensitive Data Protection (Cloud DLP) for Vertex AI Generative Models (PaLM2)](https://github.com/GoogleCloudPlatform/Sensitive-Data-Protection-for-Vertex-AI-PaLM2)
- Conversational AI
  - [Contact Center AI Samples](https://github.com/GoogleCloudPlatform/contact-center-ai-samples)
  - [Reimagining Customer Experience 360](https://github.com/GoogleCloudPlatform/dialogflow-ccai-omnichannel)
- Document AI
  - [Document AI Samples](https://github.com/GoogleCloudPlatform/document-ai-samples)
- Gemini in Google Cloud
  - [Cymbal Superstore](https://github.com/GoogleCloudPlatform/cymbal-superstore)
- Cloud Databases
  - [Gen AI Databases Retrieval App](https://github.com/GoogleCloudPlatform/genai-databases-retrieval-app)
- Other
  - [ai-on-gke](https://github.com/GoogleCloudPlatform/ai-on-gke)
  - [ai-infra-cluster-provisioning](https://github.com/GoogleCloudPlatform/ai-infra-cluster-provisioning)
  - [solutions-genai-llm-workshop](https://github.com/GoogleCloudPlatform/solutions-genai-llm-workshop)
  - [terraform-genai-doc-summarization](https://github.com/GoogleCloudPlatform/terraform-genai-doc-summarization)
  - [terraform-genai-knowledge-base](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base)
  - [genai-product-catalog](https://github.com/GoogleCloudPlatform/genai-product-catalog)
  - [solutionbuilder-terraform-genai-doc-summarization](https://github.com/GoogleCloudPlatform/solutionbuilder-terraform-genai-doc-summarization)
  - [solutions-viai-edge-provisioning-configuration](https://github.com/GoogleCloudPlatform/solutions-viai-edge-provisioning-configuration)
  - [mis-ai-accelerator](https://github.com/GoogleCloudPlatform/mis-ai-accelerator)
  - [dataflow-opinion-analysis](https://github.com/GoogleCloudPlatform/dataflow-opinion-analysis)
  - [genai-beyond-basics](https://github.com/meteatamel/genai-beyond-basics)
  - [Gemini by Example](https://geminibyexample.com)

## Contributing

Contributions welcome! See the [Contributing Guide](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/CONTRIBUTING.md).

## Getting help

Please use the [issues page](https://github.com/GoogleCloudPlatform/generative-ai/issues) to provide suggestions, feedback or submit a bug report.

## Disclaimer

This repository itself is not an officially supported Google product. The code in this repository is for demonstrative purposes only.
