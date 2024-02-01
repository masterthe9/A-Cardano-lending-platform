
{
  "platform": "Cardano-based Lending and Staking",
  "tokens": {
    "mainToken": {
      "description": "Primary utility and governance token, earned by staking initial CNFTs.",
      "useCases": ["Staking rewards", "Governance voting", "Platform utility"]
    },
    "treasuryBackedToken": {
      "description": "Represents a share of the platform's treasury, earned by staking CNFTs minted from defaulted loans.",
      "useCases": ["Staking rewards", "Treasury share representation"]
    }
  },
  "loanMechanics": {
    "currency": "ADA",
    "collateralType": "CNFT",
    "loanToValueRatio": "33.3%",
    "interestRate": "1% per week",
    "defaultAction": "Mint new CNFT for staking"
  },
  "stakingRewards": {
    "initialCNFTs": {
      "rewardToken": "Main Token",
      "pool": "Initial CNFT Staking Pool"
    },
    "defaultedCNFTs": {
      "rewardToken": "Treasury-Backed Token",
      "pool": "Defaulted CNFT Staking Pool"
    }
  },
  "governance": {
    "voting": "Token holder based",
    "keyDecisions": ["Platform updates", "Interest rates", "Treasury usage"]
  },
  "marketDynamics": {
    "valuationMethod": "Market offers and oracle services",
    "collateralValuation": "Accurate and fair market value"
  },
  "technicalImplementation": {
    "blockchain": "Cardano",
    "security": ["Smart contract audits", "Regular testing"]
  }
}
