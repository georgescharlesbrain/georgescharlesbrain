<!--
Notes:
This is the repo from which the github profile is generated.

Fork the github profile repos and copy the interesting parts.

Inspiration for GitHub Profiles:
https://github.com/ForrestKnight/ForrestKnight


-->
# 🏄‍♂️ Georges-Charles Brain

**`Digital Craftsman (Sui Move Developer / Proprietary Crypto Market Maker)`**

I'm an indie backend and web3 developer. All coding projects are built from the ground up, from planning and designing all the way to solving real-life problems with code. 


---

### 🧰 Languages and Tools

<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
<img align="left" alt="TypeScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-plain.svg" />
<img align="left" alt="NodeJS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" />
<img align="left" alt="ExpressJS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />

<!--
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
<img align="left" alt="React" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
<img align="left" alt="Bash" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
<img align="left" alt="Java" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>
<img align="left" alt="Spring" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" />
-->
 
<br />


#
<!-- 
<details>
  <summary><h3>👨‍💻 Georges-Charles's Coding Journey </h3></summary>
    I started my coding journey as a Qlik Data Vizualization consultant.
</details>
 -->

<details>
  <summary><h3> Projects I'm working on: </h3></summary>
  Custodial USSD wallet for the Sui Network  
 
  [Curabolist](https://curabolist.com) - Curate, collaborate, and monetize online research about any topic.  
  Grid trading (custom gsheet model)

</details>

<details>
  <summary><h3> Projects I worked on: </h3></summary>
    MoveToEarn / Stepn - a team of 9 East-Africans Employees walked 90 phones daily for 6 months, totaling 16200km
    Reality Mining - community-sourced street-level imagery and map data, 2 employees mapped a city neigborhood using RealityMaps (shut down) which wasn't mapped by Google Streetview since 7 years
    - Algorithmic cash & carry - perpetual funding rate arbitrage
    - Hedged Yield Farming on Ethereum and Solana (APY.vision, tulip.garden, custom gsheet model)
    - [Solana Ecosystem Database](https://ufahamu.notion.site/f8cf55a53ac34d118aae18b906aff319?v=2420b81d89f24442a4ff7e89c5fe38ad&pvs=4) - Community maintained, includes pre-token and pre-mainnet projects, sorting of projects by category, dev stage and other properties
    - Quant hedge fund investing
    - uncollateralized lending (TrueFi, notes.finance)
    - A proprietary cross-exchange triangular arbitrage market-making trading engine written in Python (see detailed project description below)
    - Manual triangular arbitrage vs Fiat on CEXs

</details>

<details>
  <summary><h3> Languages and Tools </h3></summary>
    - Python
  
    - Javascript
  
    - Tools:
    Linux, Zsh, render.com
    Qlik, Notion, Asana, gsheets

    - AWS:

    - web3: duneanalytics, thegraph, 

</details>

<details>
  <summary><h3> Crypto / DeFi / web3 </h3></summary>
    I've been near full-time exploring the crypto / defi / web3 world since the end of 2017.
    Sui: SNS

    Solana:
      protocols: MNGO, SNY, TULIP, GMT/GST(Stepn), HXRO, MEAN, IVN, PRT, ATLAS/POLIS(Star Atlas), FIDA, GRAPE, RAY, PEOPLE, SBR, MAPS, OXY, SRM

    Ethereum: 
      protocols: UMA, SNX, SUSHI, 1INCH, TRIBE/FEI, TRU, AMPL, BAND, ITGR, MLN, Augur, BAL, GLM

    Others L1s: Celo

    Other protocols: RealityCoin, Hivemapper
    
</details>

<details>
 <summary><h3> Detailed description of projects: </h3></summary>
 
 Built a proprietary cross-exchange triangular arbitrage market-making trading engine
 Built using:
  Python: CCXT, threading, logging, SQLAlchemy, Redis, boto3, Pandas, Numpy, Dask, Altair, concurrent  
  AWS: EC2, RDS, CloudWatch, IAM, SageMaker, Parameter Store, S3  
  Tools: Redis, MySQL, Linux, git, Atom+hydrogen, Jupyter Lab, Asana, HeidiSQL, P3X Redis Client, 
  ConEmu, bitbucket, VPN, QlikView, TradingView  
 Features:
 - CCXT exchange APIs integration and requests wrapper
 - CCXT exchange API unit tests evaluation script
 - Oanda Forex API integration
 - A universal bot for parameterized market making in any market vs reference markets
 - An order placement optimizer, dependent on the order book and tunable parameters per market
 - Monitoring:
   - Email alerts
   - Market maker checker (removes all the orders of the books in a self-detected emergency) (python script)
   - Balance overview on request (console)
   - Open orders on request (console)
   - Bot state on request (Redis viewer)
   - Detailed bot logs (Cloudwatch)
 - A current market state which fetches order books and tickers from all relevant CCXT exchange
 - A balance state which regularly fetches the balances of exchange accounts
 - Total balance over multiple exchange accounts and currencies with time comparison and a backup position re-balancer
 - A parameterized capital management script to auto-transfer crypto assets across multiple exchanges based on balance targets and accompanying thresholds
 - A public trades fetcher for all relevant CCXT exchanges and markets
 - A public trades processor to convert all prices to EUR and add reference bids or asks
 - Market profitability analyzer based on the processed public trades
    
</details>

#

### 📊 Stats

![Georges-Charles's GitHub stats](https://github-readme-stats.vercel.app/api?username=georgescharlesbrain&show_icons=true&theme=gruvbox) 
<!-- ![GitHub Streak](https://streak-stats.demolab.com?user=georgescharlesbrain&theme=gruvbox&border_radius=4.5) -->

