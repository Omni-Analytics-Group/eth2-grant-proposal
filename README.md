# Ethereum 2.0 Validator Health Tier Tracking Research Proposal

Our grant proposal seeks to improve on our bronze place, award winning research into tracking the health of the Ethereum 2.0 mainnet through the analysis of validator behavior. By setting our previous work as the foundation, this set of new phases will formalize our methodology, improve its accessibility through the development of a visualization dashboard, and encourage community ownership by open sourcing the techniques and code. We believe our contributions will help aid potential validators understand how the network rewards positive behaviors, will give network stewards a way to attain a high level view of the health of the blockchain, and also serve as the initial ground work for more complex performance tracking tools. All funding for this grant will be used to help us push forward through our roadmap.

Phase 0:

1. Release our current dashboard script and dataset.
2. Document the current code base.
 
Phase 1:

1. Improve our data procurement processes and semi-automate data collection.
2. Create an RShiny (Javascript R Wrapper library) application to streamline dashboard development.
3. Reanalyze the most recent BeaconScan data for the ETH 2.0 mainnet and refit the validator clustering/tiering model learned from the Medalla testnet.
4. Document those results and invite community feedback.
 
Phase 2:

1. Create a scalable data backend.
2. Incorporate community feedback into the model implementation.
3. Improve the aesthetics of the dashboard.
 
Phase 3:

1. Add support for real time scoring.
2. Develop a REST API to make the validator scores easily accessible to other applications.
3. Revamp the dashboard to a more professional UI with interactive graphics.
