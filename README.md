# Cross-chain Rebase Token

1. A protocol that allows user to deposit into a vault and in return, receiver rebase tokens that represent their underlying balance.
2. Rebase token -> `balanceOf` function is dynamic to show the changing balance with time.
   - Balance increases linearly with time.
   - Mint tokens to users every time they perform an action.
3. Interest rate
   - Individually set an interest rate for each user based on some global interest rate of the protocol at the time the user deposits into the vault.
   - This global interest rate can only decrease to incentivise or reward early adopters.