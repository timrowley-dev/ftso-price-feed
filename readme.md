**Video Tutorial:** https://youtu.be/fcC8DOaybbU

**EthersJs:** https://docs.ethers.io/v5/  
**CSS:** https://github.com/andybrewer/mvp/

**NodeJs Dependencies:**

- Express (https://expressjs.com/)

---

**Installation & Usage**

- Run `npm install` in project root directory
- Start Express server by running `node index.js` or `npm run server`
- Navigate to `http://localhost:3000`

**Considerations**

There are a few of ways to improve this code such as resolving all prices of symbols at the same time (using Promise.All). You can also be selective with which ABI items you import which could also mitigate issues such as the one with `getCurrentPrice` having two input parameters (by specifying only one option you will be able to call it as normal rather than by specifiyng the method name and input type).
