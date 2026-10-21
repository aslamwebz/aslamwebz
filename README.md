# Mohamed Aslam

**Software engineer · Laravel backends & AI applications**

I build the backend systems behind business applications and the controls around AI workflows. I've worked professionally with PHP/Laravel since 2021, following an earlier career in IT infrastructure.

The repositories below are independent builds: a desktop AI assistant, an AI-assisted job application platform and a business workspace.

[LinkedIn](https://www.linkedin.com/in/aslamwebz/) · [Email](mailto:aslam4webz@gmail.com)  
**Open to fully remote employment in backend or AI application engineering.**

## Start with the code

| Project | What to explore |
| :--- | :--- |
| **[Freya-v1](https://github.com/aslamwebz/Freya-v1)**<br>Desktop AI assistant<br>Electron · React | How model calls are coordinated and cancelled in the [model gateway](https://github.com/aslamwebz/Freya-v1/blob/main/core/model/gateway.ts), with persistent events and explicit failure handling. This is the public v1 work sample, developed with AI coding agents. |
| **[HireAI](https://github.com/aslamwebz/HireAI)**<br>Job application tools<br>PHP · Laravel · Livewire · Prism | LLM provider integration in the [AI service](https://github.com/aslamwebz/HireAI/blob/main/app/Services/AiService.php), structured resume extraction, streamed generation and [restorable resume versions](https://github.com/aslamwebz/HireAI/blob/main/app/Models/ResumeVersion.php). |
| **[TeamBoard](https://github.com/aslamwebz/TeamBoard)**<br>Projects, time & billing<br>PHP · Laravel · Livewire | [Database-per-tenant configuration](https://github.com/aslamwebz/TeamBoard/blob/main/config/tenancy.php), [invoice-payment creation](https://github.com/aslamwebz/TeamBoard/blob/main/app/Livewire/Payments/PaymentCreate.php) with row locking and balance checks, and [task permissions](https://github.com/aslamwebz/TeamBoard/blob/main/app/Policies/TaskPolicy.php). |

## The engineering behind the interface

My professional work includes framework upgrades, database query refactoring, employee and manager permissions, transactional checkout and device/server synchronisation. Employer code stays private.

Across my own projects, I focus on questions such as: what happens when a model call fails, a user stops an agent, two requests arrive together, or one workspace tries to access another's data?

## How I work with AI

I use Claude Code, Codex and OpenCode for implementation and review. In my desktop projects, coding agents handle much of the implementation while I focus on workflow design, integration decisions and review. I inspect the changes and investigate failures through source, tests and logs.

## Core stack

**Backend** · PHP, Laravel, MySQL, Eloquent, REST APIs, queues  
**Interfaces** · Livewire, Vue, Inertia, Tailwind CSS  
**AI integration** · LLM APIs, Prism  
**Verification** · PHPUnit, Pest, PHPStan/Larastan, GitHub Actions

