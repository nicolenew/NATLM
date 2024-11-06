# NATLM
NATLM is a tool designed to detect four common types of vulnerabilities in NFT smart contracts: ERC-721 Reentrancy, Public Burn, Risky Mutable Proxy, and Unlimited Minting.
# Experiments
pip install solc-select
solc-select install 0.8.16
solc-select use 0.8.16
An example of running the training are as follows:
python main_detection.py --directory ./data/NFTcontracts/test/ --output ./audit_report
