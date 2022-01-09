# Fair DAO voting mechanism

- everyone stakes any amount they want to the available options
- option with most tokens wins vote
- winners' stake is sent to losers, pro-rated by how much they staked
- e.g.
    - A votes 80 tokens for option 1
    - B votes 20 tokens for option 1
    - C votes 60 tokens for option 2
    - D votes 90 tokens for option 2
    - option 2 wins with 150 vs 100 tokens
    - A gets 200 tokens: 120 consolation (150 * 80/100) + 80 back
    - B gets 50 tokens: 30 consolation (150 * 20/100) + 20 back
    - C gets 40% (60/150) credit/blame for option 2
    - D gets 60% (90/150) credit/blame for option 2
    - A and B lose this vote but gain more tokens to influence next vote 
