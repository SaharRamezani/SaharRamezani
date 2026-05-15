<p align="center">
  <img alt="intro" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3500&pause=800&color=4A90A4&center=true&vCenter=true&width=620&height=50&lines=verifying+things%2C+one+trace+at+a+time;currently+breaking+DPOR+in+interesting+ways;i+write+proofs+and+sometimes+they+compile;stateless+model+checking%2C+stateful+coffee+habit" />
</p>

CS master's student in Genoa, research intern at MPI-SWS. I look for races in concurrent programs, and for proofs that there are none. Sometimes both at once.

---

### `// currently`

```text
$ whoami
> sahar ramezani. cs master's @ unige, research intern @ mpi-sws
$ currently_doing
> extending DPOR with timestamps in TraceForge
$ also
> teaching Coq to admit when it does not know
$ uptime
> 3 espressos, 1 admitted lemma, 0 races on purpose
```

---

### `// what I work on`

```mermaid
graph LR
    A[model checking] --> B[DPOR / Must]
    A --> D[Coq / Rocq proofs]
    B --> C[TraceForge]
    B --> E[distributed protocols]
    D --> F[concurrency semantics]
```

At MPI-SWS I work with Prof. Rupak Majumdar and Prof. Arnaud Sangnier on DPOR and the Must algorithm. The tool is **TraceForge**, a Rust engine for stateless model checking of distributed systems. The phrase "stateless model checking" sounds harder to explain at parties than it actually is. Short version: run a concurrent program over enough interleavings to be confident the bug is not there, without running all of them. A preprint lives on [arXiv](https://arxiv.org/abs/2504.18953).

---

### `// shipped, outside academia`

- Tender Offer System for the oil sector
- Grant Request System for a Ministry of Science
- Oracle Forms and PL/SQL modules across several internal tools
- A project management platform that ended up being sold to a company

---

### `// the stack`

**languages**  
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat&logo=solidity&logoColor=white)

**verification & theory**  
![Coq](https://img.shields.io/badge/Coq-8B5A2B?style=flat&logo=coq&logoColor=white)
![Rocq](https://img.shields.io/badge/Rocq-8B5A2B?style=flat&logo=coq&logoColor=white)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=flat&logo=ocaml&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)

**infra & tools**  
![Linux](https://img.shields.io/badge/Linux-1A1A1A?style=flat&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

### `// one theorem, mostly admitted`

```coq
Theorem sahar_likes_concurrency : forall p, concurrent p -> exists b, found_by_DPOR b p.
Proof.
  intros p Hc.
  induction Hc.
  - (* base case: trivially fine *)
  - (* inductive case: probably fine, it is 2 a.m. *)
Admitted.
```

---

### `// the numbers, lightly`

<p>
  <a href="https://github.com/SaharRamezani">
    <img height="155" src="https://github-readme-stats.vercel.app/api?username=SaharRamezani&show_icons=true&hide_border=true&bg_color=00000000&title_color=4A90A4&text_color=808080&icon_color=4A90A4" />
    <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SaharRamezani&layout=compact&hide_border=true&bg_color=00000000&title_color=4A90A4&text_color=808080" />
  </a>
</p>

---

### `// elsewhere`

<p>
  <a href="https://github.com/SaharRamezani">
    <img src="https://img.icons8.com/fluency/48/github.png" height="40" alt="github" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/sahar-ramezani-jolfaei/">
    <img src="https://img.icons8.com/color/48/linkedin.png" height="40" alt="linkedin" />
  </a>
  &nbsp;
  <a href="https://scholar.google.com/citations?user=5M3m52EAAAAJ&hl=en">
    <img src="https://img.icons8.com/color/48/google-scholar.png" height="40" alt="google scholar" />
  </a>
  &nbsp;
  <a href="mailto:6709190@studenti.unige.it">
    <img src="https://img.icons8.com/color/48/gmail-new.png" height="40" alt="email" />
  </a>
  &nbsp;
  <a href="https://arxiv.org/abs/2504.18953">
    <img src="https://img.icons8.com/color/48/literature.png" height="40" alt="arxiv" />
  </a>
</p>

<sub>based in Italy. English C1, Italian B1, German A1. international students' representative at UniGe.</sub>
