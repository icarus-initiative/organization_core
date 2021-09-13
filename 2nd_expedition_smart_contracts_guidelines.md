# Icarus Initiative - 1st Expedition Wallet Guidelines

Tags: #icarus #2ndexpedition #smartcontracts #guidelines

- Document version 1.0 (2021-09-11)

---

## Introduction

> The objective of the smart contract is to start working with the Solana SDK and smart contracts. We will work to make different types of smart contracts. The target one is to make a time delayed escrow transaction. After user A deposits a good and user B deposits currency, the program will release the items to the parties after a certain amount of time determined by the users (5 minutes, 1 hour, 1 day, etc).

---

## Briefing

- Some recommended readings before you engage.
- [Basic Solana Docs Summary](https://2501babe.github.io/posts/solana101.html)
- [Paulx Escrow Smart Contract Article](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/)

---

## Minimum User Stories

- [ ] Building a Smart Contract with time delayed escrow.
- [ ] User A can deposit a good (jpg or something else) into the escrow.
- [ ] User B can deposite lamports into the escrow.
- [ ] After a fixed duration determined by both parties, the items are released to opposite sides.

---

## Stretch User Stories

- [ ] Stretch goal:

---

## Recommended Approach

> Squadron captains should manage the squad details, decisions, and repos in the squadron's repo which will be provided by the admin.

- Much of the same steps from wallet guidelines. The new steps starts at number 7.

1. Talk to your squadron if you all are building this project together or separately.

- Working solo is recommended for the new beginner.

  - PRO: Learn every single bit of the build process and code.
  - PRO: Experienced developers can surgically target your pain points.
  - CON: Can remove the group dynamic if you don't get hooked into your squad or community.

- Working together is recommended for a squad with some development experience.
  - PRO: Leveling up together and sense of contribution.
  - PRO: Being able to build more user stories as a team.
  - CON: Lose out on building every single facet of the wallet.
  - CON: Added complexity of Github repository management.

2. Have a Github account to version control your code or make commits.

- If soloing, make your own repo to version control your project.
- If with the squad, a captain should contact an admin on discord to create a repo on the [organization](https://github.com/icarus-initiative).
- The captain should invite their squadmates and grant appropriate permissions.
- You can feel free to contribute to your squadron's core repository on the organization if you want. Just let your captain know. You can then fork and clone to work on your project. Helps keep your github green with PRs and commits!

3. Decide on the technologies to be used solo or with squad.

   - Recommended to use technologies already known.
   - A basic html, css, javascript wallet will be adequate for this expedition.
   - This project will revisit the SDK/API from Figment to interact with the blockchain backend hosted by DataHub.
   - Can add 1 new piece of technology if there's high ambitions.

4. Look at the core user stories and decided on any extra stretch user stories, either solo or as a squad.

   - The user stories might have changed and updated so you can revisit mid-expedition also.

5. Set up the file structure and dependencies.

   - Set up the file structure according convention decided by the squad or the coding language.
   - Make environmental variables file to store the DataHub endpoints and wallet keypairs.

6. Start on the user interface.

   - Create a multi-page or single page app.
   - Build a basic navigation bar with a wallet, send, and receive page.

7. The options going forward are up to you or your squad.

   - You can now tackle any stretch goals or tasks your squadron has decided.
   - The stretch goals may have changed so refer back to the [expeditions markdown](https://github.com/icarus-initiative/icarus_initiative/blob/main/expeditions.md).
   - Tackle your resources and recommended readings. Also in the expeditions file.
   - Log and share you progress on social media like Twitter or personal blog.
   - Connect on Twitter, LinkedIn, Github with all the pilots in your squadron.
   - Create a guide/blog/video article on how you created you wallet.

8. Tweet your progress with screenshots and hashtag `#icarussquadron`. `#icarusinitiative` was already "taken". lol

- Here's a template you can get started with! Go for it!

```text
Day 1
#icarussquadron @IcarusSquadron @squadmate1 @squadmate2 @squadmate3

✅Started a new repo for the Solana Smart Contracts Project.
✅Met with the squad to tackle this.
✅Started on the UI!
```

- **Good luck, pilots! 🛫**

---

## Support

> Don't forget that you are not alone in your learning. Take the initiative to make friends and ask questions and learn. No one is responsible for your learning. You get what you give in the world.

- Hit up the discord channel and ask your squadron's personal discord channel IE "1st-squadron" or in "technical-help" channel.
- Check with SOLHACK or Solana official discord channels to get more expert help.

---
