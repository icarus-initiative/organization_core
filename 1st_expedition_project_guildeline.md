# Icarus Initiative - 1st Expedition Project Guideline

Tags: #icarus #1st_expedition_project_guildeline #1stexpedition #walletbuildling #guidelines

- Document version 1.0 (2021-8-28)

---

## Introduction

> The objective of the wallet is not to test your technical prowess. It's to learn how to build relationships with your squadmates, work with other developers in a collaborative environment, have a tangible project that you can showcase, get your hands on the keyboard, provide a welcome switch from consuming content into creating code, and devote time to learning the rust/solana ecosystem in preparation for the upcoming expeditions.

- The document contents are guidelines, not iron-clad.
- The wallet project assumes you have completed the Figment course on the [Solana protocol](https://learn.figment.io/protocols/solana).
- For the project minimum user stories, refer back to the [expeditions markdown](https://github.com/icarus-initiative/icarus_initiative/blob/main/expeditions.md).

- Assumes you have basic web 2.0 development skills.
- If you don't meet the minimum, you will have difficulties moving past the first expedition and beyond.
- You really should be taking basic web development courses instead of joining this initiative. There are many platforms such as FreeCodeCamp, Udemy, or other beginner courses.

- Minimum: HTML, CSS, JavaScript, basic understanding of software architecture, REST API, and some Github.
- Proficient: Front-end framework skills (React, Vue, Angular) and some back-end framework knowledge(Node, Python, C-based languages).

---

## Recommended Approach

> Squadron captains should manage the squad details, decisions, and repos in the squadron's repo which will be provided by the admin.

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

7. Interact with the DataHub backend.
    - You should already know how to do these things as you've worked through them on the Figment.io pathway. The challenge here is different since you have no provided solutions and you have to figure out how to achieve the same tasks in your app.
    - Connect with the Solana Devnet.
    - Create 2 KeyPairs and store the info in the env variables file.
    - One for your personal wallet and one is a target wallet to interact with.
    - Fund/airdrop the personal wallet with some SOL.

8. Wallet section.
    - After you have stored your public address and funded your wallet, you should try to read your lamport amount in your account balance.
    - Call the DataHub "blockchain" for this task.

9. Send section.
    - You should have 2 wallets because we created 2 KeyPairs and you've been good and stored them in the env variables file.
    - Now adapt the UI with a light form that you can send lamports from your personal wallet to the target wallet.
    - We don't need to read the target wallet, we trust you already know how to do that and can make the interface if needed.
    - Generate a link that users can click on to go to the transaction on the solana explorer blockchain.

10. Receive section.
    - Create a way that people can quickly copy your address or scan your QR to send you SOL.
    - The object is to get familiar with this because all wallets have a copy address feature and QR code feature.
    - The objective is not to make it actually functional but you can if you'd like.
    - This requires an interplay of other technologies that is not crucial to our wallet app at this very moment.
    - You can also try to implement and test with other squadmates to send SOL to each other if there's ambition.

11. The options going forward are up to you or your squad.
    - You can now tackle any stretch goals or tasks your squadron has decided.
    - The stretch goals may have changed so refer back to the [expeditions markdown](https://github.com/icarus-initiative/icarus_initiative/blob/main/expeditions.md).
    - Tackle your resources and recommended readings. Also in the expeditions file.
    - Log and share you progress on social media like Twitter or personal blog.
    - Connect on Twitter, LinkedIn, Github with all the pilots in your squadron.
    - Create a guide/blog/video article on how you created you wallet.

- **Good luck, pilots and squadrons! 🛫**
---

## Support

> Don't forget that you are not alone in your learning. Take the initiative to make friends and ask questions and learn. No one is responsible for your learning. You get what you give in the world.

- Hit up the discord channel and ask your squadron's personal discord channel IE "1st-squadron" or in "technical-help" channel.
- Check with SOLHACK or Solana official discord channels to get more expert help.

---
