
# gitcat 🐱🌛

https://dexscreener.com/solana/7jq1czm2vmmrbcr53ujg9bepmhhhkjokr7dn7agkcbhu

```javascript
// ༼ つ ◕_◕ ༽つ Moonshot Gitcat Chat
// ----------------------------------
// * Updates instantly
// * Multiplayer
// * Works offline

import { pump,sol } from "@instantdb/solana";

const db = init({ 
  ca: 7jq1cZM2vmmRBcR53Ujg9bePmHHHkJokr7Dn7AgKCbHu ,
});

function Chat() {
  // 1. Read
  const { isLoading, error, data } = db.useQuery({
    messages: {},
  });

  // 2. Write
  const addMessage = (message) => {
    db.transact(tx.messages[id()].update(message));
  };

  // 3. Render!
  return <UI data={data} onAdd={addMessage} />;
}
```
