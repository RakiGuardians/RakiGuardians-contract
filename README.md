# RakiGuardians / $REIKI Contract
- [`RakiGuardians.sol`](https://github.com/RakiGuardians/RakiGuardians-contract/blob/master/RakiGuardians.sol)

```

▒█▀▀█ █▀▀█ █░█ ░▀░ ▒█▀▀█ █░░█ █▀▀█ █▀▀█ █▀▀▄ ░▀░ █▀▀█ █▀▀▄ █▀▀
▒█▄▄▀ █▄▄█ █▀▄ ▀█▀ ▒█░▄▄ █░░█ █▄▄█ █▄▄▀ █░░█ ▀█▀ █▄▄█ █░░█ ▀▀█
▒█░▒█ ▀░░▀ ▀░▀ ▀▀▀ ▒█▄▄█ ░▀▀▀ ▀░░▀ ▀░▀▀ ▀▀▀░ ▀▀▀ ▀░░▀ ▀░░▀ ▀▀▀

Token: RakiGuardians
Ticker: RakiG
```

Features:
- 1,000,000,000 RakiG Supply with function to add progressive burn on every transaction in future
  - Function for users to burn tokens, in future makes it possible to have dApp/s which encourage burning
  - Burned tokens are instantly removed out of existence & Token Supply
- 10% max tax restriction in update functions
- 5% Taxes: 1% liquidity, 2.5% Dev United, 0.5% * 3 internal team, 0% burn (to have the option in future)
- Renouncable functions (_renounceFeeFunctions, _renounceMaxUpdateFunctions, _renounceWalletChanges) so that entire ownership doesn't need to be renounced (in case of CEX listing or etc)
- 0 maxSellTransaction Amount for first 2 minutes to prevent whale bot flips
- 1% max sell transaction restriction
- 2% max wallet restriction
- 180 second cooldown on sells after transactions to prevent bot flips

---

```

 ▅▅▅ ▅░░▅ ▅░░▅ ▅▅▅ ░▅▅▅ ▅▅░▅ ▅░░▅ ▅▅▅░ █▀▀█▒ ▅▅▅ ▅░▅ ▅░░▅ █▒░█▒
 █▅▅ █░░█ █▀▀█ ▅█▅ █░░█ ▅▀▀█ █▀▀█ █░░█ ▀▀░█▒ ▅█▅ ▀▅█ █▀▀█ ▅▀▀█▒
 ▅▅█ ▀▅▅█ █▅▅█ ░▅░ ▀▅▅█ █▅▅█ █▅▅█ █░░█ █▅▅█▒ ░▅░ █░█ █▅▅█ █▅▅█▒

```

```

______      _    _ _____                     _ _                 
| ___ \    | |  (_)  __ \                   | (_)                
| |_/ /__ _| | ___| |  \/_   _  __ _ _ __ __| |_  __ _ _ __  ___ 
|    // _` | |/ / | | __| | | |/ _` | '__/ _` | |/ _` | '_ \/ __|
| |\ \ (_| |   <| | |_\ \ |_| | (_| | | | (_| | | (_| | | | \__ \
\_| \_\__,_|_|\_\_|\____/\__,_|\__,_|_|  \__,_|_|\__,_|_| |_|___/
                                                                 
```

---

[This Repo is licensed under an MIT LICENSE](./LICENSE)
