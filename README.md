<!-- PROFILE HEADER -->


<p align="center">
  <img src="https://readme-typed-effects.vercel.app?font=Poppins&pause=1200&center=true&vCenter=true&random=false&width=600&lines=Hi%2C+I'm+Na+%28%EB%82%98%ED%98%84%EA%B7%9C%29+%F0%9F%91%8B;Entrepreneur+%F0%9F%92%BC+%7C+Full‑stack+Builder+%F0%9F%9B%A0%EF%B8%8F;AI+%26+EdTech+maker+from+Korea+%F0%9F%87%B0%F0%9F%87%B7" alt="typing intro"/>
</p>


<p align="center">
  <a href="#">English</a> · <a href="#ko">한국어</a>
</p>



⸻


<!-- QUICK BADGES -->


<p align="center">
  <img src="https://img.shields.io/badge/Java-17+-blue"/>
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-brightgreen"/>
  <img src="https://img.shields.io/badge/React-18-61DAFB"/>
  <img src="https://img.shields.io/badge/React_Native-0.76-61DAFB"/>
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6"/>
  <img src="https://img.shields.io/badge/MySQL-8.x-005C84"/>
  <img src="https://img.shields.io/badge/Oracle-11g-E95420"/>
  <img src="https://img.shields.io/badge/AWS-Builder-FF9900"/>
  <img src="https://img.shields.io/badge/Ollama-LLM-black"/>
</p>



⸻

🌟 About Me
	•	CEO-minded maker building SaaS for education & hospitality.
	•	Shipping with Spring (Legacy/MVC & Boot) + React/React Native, MySQL/Oracle.
	•	Exploring local LLMs (Ollama), RAG, and automation agents.
	•	Moving to Australia and crafting global products.

“Build the system that builds more systems.”

⸻

🚀 Featured Projects

StayFolio (Spring MVC + Oracle) — Hotel/room booking platform with admin modules
	•	Reservation, reviews, bookmarks, room management
	•	ERD + MyBatis mappers, JSP/Thymeleaf templates
	•	Demo: [link] · Docs: [link]

EM — Easy Marketing (Next.js + AI) — Automated marketing content & Google Business optimization
	•	Content pipelines, prompts, Notion integration
	•	Demo: [link] · Docs: [link]

Crushy (React Native + Expo) — MBTI‑based AI chat companion
	•	Neon UI, persona engine, avatar components
	•	Demo: [link] · Docs: [link]

Want your repo here? Pin it on your profile and update links above.

⸻

🧰 Tech Toolbox

Back‑end: Java 17, Spring Boot 3.x, Spring MVC, JPA, MyBatis, Gradle

Front‑end: React 18, Next.js, React Native (Expo), Tailwind, shadcn/ui

Data: MySQL, Oracle XE, Redis (cache), Prisma/JPA, QueryDSL

DevOps: Docker, GitHub Actions, Vercel, AWS (EC2/S3/RDS), Nginx

AI: Ollama, OpenAI API, Embeddings/RAG, Vector DB (Qdrant/FAISS)

⸻

📊 GitHub Stats (auto)

Replace USERNAME with your GitHub ID.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&hide_title=true" height="160"/>
  <img src="https://streak-stats.demolab.com?user=USERNAME&hide_longest_streak=true" height="160"/>
</p>


<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=USERNAME&bg_color=ffffff&color=000000&line=000000&point=000000&area=true&hide_border=true"/>
</p>


Optional: https://github-profile-trophy.vercel.app/?username=USERNAME&theme=flat

⸻

🗓️ What I’m Building Now
	•	📚 Academy Admin: attendance & SMS automation (Android‑first)
	•	🧠 Prompt libraries for marketing & education
	•	🧩 UI kits for React/React Native (glass/neon styles)

⸻

📝 Latest Posts (auto‑update)

Add a GitHub Action to fetch and render your latest blog/Notion posts.

# .github/workflows/feed-to-readme.yml
name: Update README with latest posts
on:
  schedule: [{cron: '0 */12 * * *'}]
  workflow_dispatch: {}
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Generate section
        run: |
          echo "<!-- posts:start -->" > posts.md
          echo "- [Sample Post A](https://example.com) — 2025-09-01" >> posts.md
          echo "- [Sample Post B](https://example.com) — 2025-08-20" >> posts.md
          echo "<!-- posts:end -->" >> posts.md
      - name: Inject into README
        run: |
          awk 'BEGIN{p=1} /<!-- posts:start -->/{p=0} {if(p)print} /<!-- posts:end -->/{system("cat posts.md"); p=1}' README.md > README.new.md
          mv README.new.md README.md
      - name: Commit changes
        run: |
          git config user.name "readme-bot"
          git config user.email "actions@github.com"
          git add -A
          git commit -m "chore: update posts section" || echo "no changes"
          git push

<!-- posts:start -->


(Auto‑inserted by Action)

<!-- posts:end -->



⸻

🧑‍🏫 Speaking & Teaching
	•	✍️ English learning & IELTS prep
	•	🧪 Elementary science content & creative education (books → drawings)
	•	🧩 Project‑based learning with coding + design

⸻

🤝 Connect

<p>
<a href="mailto:hello@example.com"><img src="https://img.shields.io/badge/Email-hello%40example.com-informational"/></a>
<a href="https://www.linkedin.com/in/USERNAME"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue"/></a>
<a href="https://nahyeongyu.dev"><img src="https://img.shields.io/badge/Portfolio-visit-9cf"/></a>
</p>



⸻

🇰🇷 한국어 소개 

안녕하세요, 나현규(Na) 입니다. 교육·호스피탈리티 분야의 SaaS, AI 자동화, 로컬 LLM을 활용한 제품을 만들고 있어요. Spring과 React/React Native를 중심으로 빠르게 아이디어 → 프로토타입 → 제품을 실행합니다.
	•	주요 프로젝트: StayFolio, EM(Easy Marketing), Crushy
	•	스택: Java/Spring, React/React Native, MySQL/Oracle, Docker/AWS
	•	앞으로: 호주에서 글로벌 서비스로 확장 🚀

문의: hello@example.com

⸻

⚙️ How to Use This Template
	1.	GitHub에서 사용자명과 동일한 이름의 공개 저장소를 만듭니다. (예: NaHyeongyu/NaHyeongyu)
	2.	이 파일을 README.md로 저장합니다.
	3.	위의 USERNAME, 링크, 이메일을 본인 정보로 바꿉니다.
	4.	원한다면 통계/그래프 카드 이미지 URL을 본인 취향으로 커스터마이즈하세요.
	5.	자동 업데이트(블로그/노션 등)를 원하면 workflows 파일을 활성화하세요.

Tip: 섹션은 3–6개로 유지하고, 스크롤을 유발하는 이미지는 최소화하면 가독성이 좋아집니다.

⸻


<p align="center">
  Made with ❤️ by Na · Inspired by makers & teachers
</p>
