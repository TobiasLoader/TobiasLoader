### 👋 Hey there

I'm Toby, a second-year Maths & CS undergrad @ Oxford.

Some info about me:
- Recently hooked on hackathons (like [Polygon x EasyA](https://www.easya.io/event/polygon-x-easya-hackathon), Oxhack and [ETHDenver](https://www.easya.io/event/polygon-x-easya-hackathon))
- Maintaining some fun projects in my spare time (plug [cylinderchess.com](https://cylinderchess.com))!
- Consuming too much coffee ☕️, climbing trees 🌳 and spending lots of time with my dog 🦮
- Working on [LensPy](https://github.com/TobiasLoader/LensPy), a py library for Lens Protocol (web3 social) – go check [Lens Protocol](https://www.lens.xyz) out

---

*Open source function to help you navigate Github profiles:*

```javascript

let me = new Visitor();

function viewProfile(profile){
  // determine if profile is worth viewing
  if (me.interested(profile) || profile.name === 'TobiasLoader'){
    // scroll down to view repos
    me.scrollDown();
    // choose top pinned repo
    let repo = profile.repos.topPinned;
    // a DFS traversal of repo to view every file
    me.viewProject(repo);
    // once completed – star the repo
    me.starProject(repo);
  }
  else me.skip();
}
```

If you want to read more about me, check out my [LinkedIn](https://www.linkedin.com/in/tobiasloader/).
