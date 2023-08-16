### 👋 Hey there

I'm Toby, a second-year Maths & CS undergrad @ Oxford Uni.

Some info about me:
- Recently hooked on hackathons (like [Polygon x EasyA](https://www.easya.io/event/polygon-x-easya-hackathon), Oxhack, [ETHDenver](https://www.easya.io/event/polygon-x-easya-hackathon), [ETHGlobal Waterloo](https://ethglobal.com/showcase/tokenbound-titans-5w6oq), ETHGlobal Paris)
- Maintaining some fun projects in my spare time (plug: [cylinderchess.com](https://cylinderchess.com))
- Consuming too much coffee ☕️, climbing trees 🌳 and spending lots of time with my dog 🦮
- Working on [LensPy](https://github.com/TobiasLoader/LensPy), a Python library for Lens Protocol (web3 social) – go check [Lens Protocol](https://www.lens.xyz) out

---

*Open source function to aid navigation of GitHub profiles:*

```javascript

let you = new Visitor();

function viewProfile(profile){
  // determine if profile is worth viewing
  if (you.interested(profile) || profile.name === 'TobiasLoader'){
    // scroll down to view repos
    you.scrollDown();
    // choose top pinned repo
    let repo = profile.repos.topPinned;
    // a DFS traversal of repo to view every file
    you.viewProject(repo);
    // once completed – star the repo
    you.starProject(repo);
  }
  else you.skip();
}
```

If you want to read more about me, check out my [LinkedIn](https://www.linkedin.com/in/tobiasloader/).
