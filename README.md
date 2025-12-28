# Sujal Shah

Full-stack developer building financial trading platforms and prediction markets.

**Email:** sujalshah888@gmail.com  
**Live Project:** [www.nepolymarket.com](https://www.nepolymarket.com)

---

## Projects

### Nepolymarket

A prediction market platform where users can trade binary options on real-world events. Built with Next.js, FastAPI, and PostgreSQL.

**Repository:** [github.com/sujalshh/mgi](https://github.com/sujalshh/mgi)  
**Live Site:** [www.nepolymarket.com](https://www.nepolymarket.com)

**Technical highlights:**
- Atomic transaction system using PostgreSQL SERIALIZABLE isolation to prevent race conditions
- Dynamic pricing algorithm that adjusts share prices (₹50-₹75) based on supply and demand
- Row-Level Security with 115+ database policies for access control
- Real-time trading with sub-100ms execution time
- Optimistic UI updates for instant user feedback

**Stack:** Next.js 14, TypeScript, React, FastAPI, Python, PostgreSQL, Supabase

The system handles concurrent trades with full data consistency. All critical operations use atomic database functions to ensure no double-spending, negative balances, or data corruption.

---

### Sports Betting Arbitrage Detection

Real-time system that scrapes odds from multiple sportsbooks and identifies arbitrage opportunities.

**Key features:**
- Scrapes odds from Pinnacle, 1xBet, BetUS, and MarathonBet
- 3-way arbitrage detection calculating optimal stake distribution
- Event matching across different bookmakers using fuzzy string matching
- Real-time WebSocket updates for live opportunity notifications
- Processes 100+ events per scan cycle

**Stack:** Python, FastAPI, Next.js, PostgreSQL, WebSockets

Identifies profitable opportunities with profit margins ranging from 0.5% to 5% by comparing odds across different bookmakers.

---

## Tech Stack

**Frontend:** Next.js, React, TypeScript, Tailwind CSS  
**Backend:** FastAPI, Python, Node.js  
**Database:** PostgreSQL, Supabase  
**Infrastructure:** Vercel, Docker

---

## Current Work

Building production-grade financial platforms with focus on:
- Data integrity and transaction consistency
- Real-time systems with low latency
- Database optimization and query performance
- Full-stack development from database to UI

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sujalshh&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sujalshh&layout=compact&theme=dark&hide_border=true&bg_color=0D1117)

</div>

---

**Contact:** sujalshah888@gmail.com
