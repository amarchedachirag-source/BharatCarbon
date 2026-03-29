# BharatCarbon

National Supply Engine for India's 2026 Compliance Carbon Market.

**Vision**  
BharatCarbon is the "lungs" of India's carbon market — turning real-time sensor data from construction sites, EV fleets, MSME clusters, waste, and degraded forest land into verified, bankable tCO₂e credits.

**Key Features**
- Real-time IoT telemetry with monsoon-resilient edge processing
- Automated Digital MRV compliant with BEE CCTS 2026 and ISO 14064-2
- Direct mint-to-ICM Registry bridge with zero double-counting
- NEST-powered Market Terminal for T+0 trading and liquidity
- Sovereign Dashboard for DGF/MoEFCC oversight

**Tech Stack**
- Layer 1–4: Python (FastAPI, MQTT, scikit-learn, Web3.py)
- Layer 5: React + Tailwind + Recharts (Sovereign Dashboard, Developer Wallet, Market Terminal)
- Security: TEC-33010 aligned, TLS 1.2, HMAC-SHA256 signing
- Deployment: AWS Greengrass v2 for edge, MeitY-compliant cloud

**Current Status**
- Prototype with 3 screens ready (Sovereign, Wallet, Terminal)
- MRV engine and sensor component implemented
- Ready for first pilot in Mumbai (construction + EV fleets)

**Next Steps**
- Integrate live data from FastAPI MRV engine
- Add full Market Terminal with order book and risk alerts
- Run joint pilot with partners (Varaha, OmneNEST)

Built for Viksit Bharat 2047 and BEE CCTS compliance.
