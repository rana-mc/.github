## RanaMC – FAQ

**Q: What is RanaMC?**

**A:** My pet project for finding, installing and control minecraft servers.
 
**Q: Free?**

**A:** Yep, opensource and can be on your machine.

**Q: Stage of project?**

**A:** Alpha now.

**Q: What is done?**

**A:** Finding Forge and Fabric cores, installing, accept EULA and stop / start server.
 
**Q: Whats next?**

**A:** Refactory, finding mods at Curseforge and installing. Check mods updates and etc.

**Q: Okay, how to install?**

**A:** Follow instruction:
1. At first, install nodejs, https://nodejs.org/en/
2. Then exec `npm install -g @rana-mc/api && npm install -g @rana-mc/web`
3. And now exec `ranamc-api start & ranamc-web start &` for starting RanaMC
4. Super! Go to http://localhost:3000/

**Q: Installed. Whats next?**

**A:** You should get API key [here](https://console.curseforge.com/?#/api-keys) and paste it on CurseForge page in RanaMC.

**Q: "Permissions denied"?**

**A:** Well, you can check [this](https://stackoverflow.com/questions/51923277/npm-install-permission-denied-error-using-root-user). If you use nvm, do not forget about different path to global node_modules.

**Q: Why rana-mc/rana-mc repo is not actual?**

**A:** That was bad idea, [probably](https://alexey-soshin.medium.com/monorepo-is-a-bad-idea-5e587e848a07).
