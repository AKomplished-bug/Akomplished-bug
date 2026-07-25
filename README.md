<p align="center">
  <img src="./hero.svg" alt="Athul Krishna — Voice AI Engineer" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/athul-krishna-a-826146238/">
    <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=2DD4BF&labelColor=0D1117" alt="LinkedIn"/>
  </a>
  <a href="mailto:athulkrishna8781@gmail.com">
    <img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=2DD4BF&labelColor=0D1117" alt="Email"/>
  </a>
  <a href="https://github.com/AKomplished-bug">
    <img src="https://komarev.com/ghpvc/?username=AKomplished-bug&style=flat-square&color=2DD4BF&labelColor=0D1117&label=views" alt="views"/>
  </a>
</p>

<br/>

I build **real-time voice AI** — the streaming STT → LLM → TTS pipelines behind phone agents that answer, understand, and talk back in under a second. Right now that means telephony for regulated **BFSI** and **healthcare**, on [LiveKit](https://livekit.io) + SIP.

```text
now      Voice AI Engineer @ Ignosis AI     BFSI voice platform · sub-700ms · LiveKit SIP
before   Voice AI Engineer @ Core Cognitics multi-tenant voice AI · 10k+ calls/day
```

<br/>

<h3>&nbsp;What I'm doing</h3>

**`~/ignosis`** &nbsp;— A real-time voice platform for BFSI (debt-collection) telephony on LiveKit SIP (Exotel/Vobiz trunks). Targeting **sub-700 ms** end-to-end latency with full barge-in, per-provider STT/LLM/TTS failover, and an offline eval harness (WER + LLM-as-judge) that replays production calls to catch regressions before users do.

**`~/core-cognitics`** &nbsp;— Co-led a multi-tenant voice AI platform on the LiveKit Agents SDK handling **10k+ calls/day** across healthcare & automotive. Multilingual (Arabic / Indic / European) with mid-call provider switching, a multi-layer guardrail system, MCP tool servers, and a RAG stack on Qdrant.

**`~/open-source`** &nbsp;— Found and reported a bug in the [LiveKit Agents SDK (#5665)](https://github.com/livekit/agents/issues/5665) — STT errors closing the session without the tolerance counter LLM/TTS errors get.

<br/>

<h3>&nbsp;Toolkit</h3>

<table>
<tr>
<td><b>Voice&nbsp;AI</b></td>
<td>
<img src="https://img.shields.io/badge/LiveKit-0D1117?style=flat-square&logoColor=2DD4BF&labelColor=161B22" />
<img src="https://img.shields.io/badge/Pipecat-0D1117?style=flat-square&labelColor=161B22" />
<img src="https://img.shields.io/badge/Deepgram-0D1117?style=flat-square&labelColor=161B22" />
<img src="https://img.shields.io/badge/ElevenLabs-0D1117?style=flat-square&labelColor=161B22" />
<img src="https://img.shields.io/badge/OpenAI_Realtime-0D1117?style=flat-square&logo=openai&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/Gemini_Live-0D1117?style=flat-square&logo=googlegemini&logoColor=white&labelColor=161B22" />
</td>
</tr>
<tr>
<td><b>LLM&nbsp;&&nbsp;Agents</b></td>
<td>
<img src="https://img.shields.io/badge/Claude-0D1117?style=flat-square&logo=anthropic&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/OpenAI-0D1117?style=flat-square&logo=openai&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/LangGraph-0D1117?style=flat-square&labelColor=161B22" />
<img src="https://img.shields.io/badge/MCP-0D1117?style=flat-square&labelColor=161B22" />
<img src="https://img.shields.io/badge/RAG-0D1117?style=flat-square&labelColor=161B22" />
<img src="https://img.shields.io/badge/Qdrant-0D1117?style=flat-square&labelColor=161B22" />
</td>
</tr>
<tr>
<td><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/Java-0D1117?style=flat-square&logo=openjdk&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/SQL-0D1117?style=flat-square&logo=postgresql&logoColor=white&labelColor=161B22" />
</td>
</tr>
<tr>
<td><b>Infra&nbsp;&&nbsp;Obs</b></td>
<td>
<img src="https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/Kubernetes-0D1117?style=flat-square&logo=kubernetes&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/AWS-0D1117?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/Kafka-0D1117?style=flat-square&logo=apachekafka&logoColor=white&labelColor=161B22" />
<img src="https://img.shields.io/badge/Grafana-0D1117?style=flat-square&logo=grafana&logoColor=white&labelColor=161B22" />
</td>
</tr>
</table>

<br/>

<h3>&nbsp;Selected projects</h3>

<table>
<tr>
<td width="50%" valign="top">

**[oneNote_AI](https://github.com/AKomplished-bug/oneNote_AI)**
<br/>Multi-agent model for academic note generation.
<br/><sub>Python</sub>

</td>
<td width="50%" valign="top">

**[AI-Call-Operator](https://github.com/AKomplished-bug/AI-Call-Operator)**
<br/>Multilingual voice call-center for disaster response — Sarvam TTS · Google STT · Llama 3.
<br/><sub>Python</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[edulex](https://github.com/AKomplished-bug/edulex)** · **[teacher](https://github.com/AKomplished-bug/edulex-teacher)**
<br/>AR adaptive-learning assistant for dyslexic students, voice-driven via Gemini Realtime. 🏆 ₹1L @ Spark Venture 2024.
<br/><sub>TypeScript</sub>

</td>
<td width="50%" valign="top">

**[Medical-chatbot](https://github.com/AKomplished-bug/Medical-chatbot-)**
<br/>RAG-powered medical assistant.
<br/><sub>Python</sub>

</td>
</tr>
</table>

<br/>

<h3>&nbsp;Stats</h3>

<p align="center">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=AKomplished-bug&show_icons=true&hide_border=true&title_color=2DD4BF&icon_color=2DD4BF&text_color=8B949E&bg_color=0D1117&count_private=true" />
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AKomplished-bug&layout=compact&hide_border=true&title_color=2DD4BF&text_color=8B949E&bg_color=0D1117&langs_count=8" />
</p>

<p align="center"><sub>Obsessed with latency budgets. Occasionally finishes side projects. 🎙️</sub></p>
