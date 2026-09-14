<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0D10,50:12151A,100:0B0D10&height=160&section=header&text=Srestho&fontSize=62&fontColor=5EEAD4&fontAlignY=40&desc=agents%20%C2%B7%20edge%20vision%20%C2%B7%20systems%20that%20hold%20up&descAlignY=68&descSize=15&descColor=8B93A1" width="100%"/>
</div>

<p align="center">
  <a href="mailto:srestho1298@gmail.com">email</a> ·
  <a href="https://srestho.online">portfolio</a> ·
  <a href="https://www.linkedin.com/in/srestho">linkedin</a> ·
  <a href="https://x.com/Moon_Knight1298">x</a> ·
  <a href="https://github.com/Srestho0101">github</a>
</p>

---

I build AI systems that have to work under real limits — limited RAM, real user data, free-tier hosting, moving cameras. Most of the interesting work is not the model. It’s the boundary between the model and the rest of the system: tool contracts, quantization, auth, streaming, and the places where agents start making things up.

Currently open to internships in production AI (agents, edge inference, or anything that has to stay reliable when hardware or data is messy).

---

### selected work

**Pixagent** — [repo](https://github.com/Srestho0101/Pixagent)  
Laptop repair shop agent. Technicians log tickets; customers ask the assistant about status.  
The agent only answers through tool calls against live repair data. No free-form guessing. FastAPI + PostgreSQL/Supabase, JWT, streaming responses, explicit anti-hallucination constraints.

**Autonomous Desktop Agent** — [repo](https://github.com/Srestho0101/AI-computer-use)  
Multimodal agent that can see and control a Linux desktop on machines with ~4GB RAM.  
In-memory frame capture + kernel-level scancode injection on Wayland. Perception stays local and light; no heavy desktop automation stack.

**Real-Time Drone Vision** — [repo](https://github.com/Srestho0101/monster-vision)  
Live drone feed → Arch Linux box → YOLOv8n inference.  
Fine-tuned the nano model and applied dynamic quantization so detection stays usable while the drone is moving.

**Result Management System** *(contributor)* — [repo](https://github.com/Srestho0101/result-management-system)  
Added a Mistral tool-calling layer on top of a Flask school platform so teachers can ask natural-language questions over student data. Tools respect role-based access; the model never gets a raw database dump.

More context and write-ups: [srestho.online](https://srestho.online)

---

### what I optimize for

- **Grounded agents** — tool schemas and hard boundaries beat clever prompts when the cost of a wrong answer is high  
- **Edge & low-resource** — if it only works on a 24GB GPU or a generous cloud tier, it doesn’t count as finished  
- **Boring reliability** — auth, streaming, error paths, and “what happens when the model is wrong” get designed early  
- **Small surfaces** — prefer a few well-scoped tools over an agent that can do everything and therefore nothing safely  

Stack I actually reach for: Python, FastAPI, Flask, PyTorch, Mistral (tool calling), YOLOv8, PostgreSQL/Supabase, SQLAlchemy, SQLite, JWT, SSE, Linux (Arch), Wayland, Docker, Git.

---

### education

Pearson Edexcel A Levels (private candidate) — Physics, Mathematics, Further Mathematics · in progress

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Srestho0101&show_icons=true&theme=dark&bg_color=0B0D10&title_color=5EEAD4&icon_color=5EEAD4&text_color=E8EAED&border_color=22262E&hide_border=false&rank_icon=percentile" height="140"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Srestho0101&layout=compact&theme=dark&bg_color=0B0D10&title_color=5EEAD4&text_color=E8EAED&border_color=22262E&hide_border=false&langs_count=6" height="140"/>

<br/>

<sub>Mohammadpur, Dhaka · looking for teams that care about agents and edge systems that don’t fall over</sub>

</div>
