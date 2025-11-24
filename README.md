# N Cost

A precise, no-nonsense CLT salary and company cost calculator for Brazil.

Enter a gross salary, weekly hours, and any monthly benefits. N Cost instantly shows:

- monthly and annual take-home pay after INSS and IRRF  
- true hourly rate  
- full annual cost to the employer (including employer social security contributions, 13th salary, and 1/3 vacation bonus)

Everything uses the official 2025 INSS and IRRF tables and follows standard Brazilian payroll rules. No approximations, no hidden fees, no registration.

## Features

- Accurate net salary calculation (INSS + IRRF 2025 tables)  
- Realistic hourly rate based on 30 h, 40 h or 44 h weekly schedules  
- Complete employer cost breakdown (payroll taxes, 13th, vacation + 1/3)  
- Brazilian-standard currency formatting (R$ 1.234,56)  
- Single-page, zero dependencies, works offline  

## Tech stack

- Pug (HTML) + Stylus (CSS)
- Logic written in CoffeeScript (JS)
- No frameworks, no build step required beyond Stylus compilation  

## How to use

1. Open https://ncost.netlify.app in the browser (or clone the repository and run index.html locally)  
2. Fill in gross salary, weekly hours, and total monthly benefits  
3. Click Calculate  
4. Read the report  

## Accuracy notes

- INSS and IRRF rates are current as of 2025  
- Benefits are treated as taxable unless explicitly non-taxable (user responsibility)  
- Vacation calculation assumes standard 30-day entitlement  
- No provisions for FGTS withdrawal options, overtime, or regional variations are included – this tool models the common nationwide CLT regime