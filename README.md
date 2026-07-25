<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:5BCDEC&height=200&section=header&text=Farhan%20Kayani&fontSize=50&fontColor=ffffff&fontAlignY=35&desc=Backend%20Architect%20%7C%20Systems%20Engineer&descAlignY=55&descSize=18&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=5BCDEC&center=true&vCenter=true&width=600&lines=Backend+Architect+%26+Full-Stack+Engineer;Decoupled+%7C+Event-Driven+%7C+Real-Time;Service-Repository+%7C+Custom+Auth+%7C+ACL;Building+NexUs+%F0%9F%9A%80)](https://git.io/typing-svg)

</div>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Mrkiyani001-%23121011?style=flat-square&logo=github)](https://github.com/Mrkiyani001)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Farhan_Kayani-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/farhan-kayani-89a514373)
[![Instagram](https://img.shields.io/badge/Instagram-mr__kiyani001-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/mr_kiyani001/)
[![Profile Views](https://komarev.com/ghpvc/?username=Mrkiyani001&style=flat-square&color=5BCDEC&label=Profile+Views)](https://github.com/Mrkiyani001)

</div>

---

## `> whoami`

```yaml
name:         Farhan Kayani
alias:        Mr. Kayani
location:     Gujranwala, Punjab, Pakistan 🇵🇰
university:   University of Gujarat — BSIT (Expected 2028)
role:         Backend Architect · Full-Stack Engineer
status:       🔨 Actively building NexUs

core_belief:  "Frameworks are tools. Architecture is the discipline."
approach:     No scaffolding shortcuts — business logic in services,
              not controllers. Security by design, not by default.
```

I build backend systems from first principles — custom auth guards, clean service-repository layers, raw SQL optimization, and event-driven architectures that decouple heavy logic from the request lifecycle. I don't use starter kits. I understand what's under the hood because I built it.

---

## `> cat tech_stack.yml`

<table>
  <tr>
    <td valign="top" width="33%">

**⚙️ Core**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)

    </td>
    <td valign="top" width="33%">

**🔌 Real-Time & Events**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Laravel Reverb](https://img.shields.io/badge/Reverb-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

    </td>
    <td valign="top" width="33%">

**🗄️ Data & Infra**

![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

    </td>
  </tr>
</table>

---

## `> ls -la projects/`

### 🔷 NexUs — Real-Time Social Ecosystem
> *First project. The flagship. Still shipping.*

A full-scale social platform engineered ground-up — **not** cloned from a tutorial. NexUs runs a decoupled React.js frontend over a clean Laravel API, with live messaging powered by **Laravel Reverb**, media on **AWS S3**, and the whole stack containerized with **Docker**.

**What makes it real:**
- Dual-mode auth: **JWT + HttpOnly Secure Cookies** — no localStorage token exposure
- **RBAC** with Spatie — Super Admin, Moderator, and custom permission sets
- **Glassmorphic UI** with Tailwind + custom CSS HSL variables
- TikTok-style vertical **Reels**, threaded comments, emoji reactions
- **Admin Command Center** — moderation queue, analytics, live user management
- Content **Moderation Pipeline** — all posts pass `Pending` state before going public
- AI integration roadmap: Gemini/Prism for automated content flagging

`Laravel 11` `React.js` `Vanilla JS` `MySQL` `JWT` `RBAC` `Laravel Reverb` `AWS S3` `Docker` `Tailwind`

[![NexUs Repo](https://img.shields.io/badge/View_Repository-NexUs-5BCDEC?style=flat-square&logo=github)](https://github.com/Mrkiyani001/NexUs)

---

### 🔷 E-Commerce Engine — Layered Backend Architecture
> *Multi-vendor. Heavy-duty. Zero framework shortcuts.*

A backend-only commerce system built on strict **Service-Repository patterns**. Complex multi-vendor inventory mapping, commission logic, and integrated Stripe payment/billing flows. Every layer knows its responsibility — models hold no business logic, controllers hold no computation.

**What's under the hood:**
- Custom **Service layer** handling all transaction logic
- **Repository pattern** abstracting all data access
- Multi-vendor **inventory state management** with concurrency handling
- Stripe **webhook** processing for real billing lifecycle events
- Granular **ACL** for vendor vs buyer vs admin permission sets

`Laravel` `MySQL` `Redis` `Stripe` `Service-Repository` `ACL` `Custom Guards`

---

### 🔷 Secure API Framework — Built From Scratch
> *Security by design. No starter kits.*

A standalone API framework built entirely without framework auth scaffolding. Custom token lifecycle management, chained verification middleware, and a permission layer that controls exactly what every client can touch.

`PHP` `Custom Auth Guards` `ACL` `Middleware Chains` `Token Management`

---

## `> cat architecture_principles.md`

```
┌─────────────────────────────────────────────────────────────┐
│  REQUEST                                                      │
│     │                                                         │
│     ▼                                                         │
│  Controller ──────► validates input only                     │
│     │                                                         │
│     ▼                                                         │
│  Service Layer ────► all business logic lives here           │
│     │                                                         │
│     ▼                                                         │
│  Repository ───────► all data access abstracted here         │
│     │                                                         │
│     ▼                                                         │
│  Model ────────────► schema mapping only, no logic           │
│                                                               │
│  ─────────────────────────────────────────────────────────  │
│                                                               │
│  Auth:     Custom guards — no Breeze, no Jetstream           │
│  Queue:    RabbitMQ for async heavy jobs                     │
│  Cache:    Redis for stampede prevention                     │
│  Events:   Decoupled, routed via message broker              │
└─────────────────────────────────────────────────────────────┘
```

---

## `> git log --stat`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mrkiyani001&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5BCDEC&icon_color=5BCDEC&text_color=ffffff&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mrkiyani001&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5BCDEC&text_color=ffffff)

</div>

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Mrkiyani001&bg_color=0D1117&color=5BCDEC&line=5BCDEC&point=FFFFFF&hide_border=true&radius=6&area=true&area_color=5BCDEC)

</div>

---

## `> echo $CURRENT_STATUS`

```diff
+ NexUs backend — Real-time messaging module (Laravel Reverb)
+ NexUs frontend — Reels feed & stories pipeline
~ E-Commerce Engine — Stripe webhook hardening
! BSIT @ University of Gujarat — Year 2 of 4
```

---

<div align="center">

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

**Open to collaborations on complex backend systems, real-time architectures, and anything that breaks at scale.**

*Let's build something that actually holds.*

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5BCDEC,100:0d1117&height=100&section=footer" width="100%"/>
</div>
