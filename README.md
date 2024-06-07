<div align="center">
  <img width=320  src="/assets/Subterfuge.png">
<h1>Subterfuge</h1>  
</div>

Learning TypeScript the Temu way!

# What's this?
This program's purpose is to restrict your TypeScript down to just console.log and functions. After completing "problems" (similar to LeetCode), you gain money. With money, you buy features. To complete the game, you need to solve all (10) problems.

![overview](https://github.com/face-hh/subterfuge/assets/69168154/1bbb5e93-30f6-440c-809c-d096a04e9f2b)

# Commands
```
Commands:
  - [filepath]     (Runs the given file against current problem. Example: main.ts)
  - shop           (Displays the shop with the available features to purchase)
  - current        (Displays information about your current problem)
  - peek           (Displays the problem list & where you're at)
  - battlepass     (Displays the battlepass)
  - claim [code]   (Claim a promo code for Premium. Example: claim AOPMGBAEP)
  - support [code] (Support a content creator that creates content on this game)
  - use [code]     (Claim a COUPON code. Example: claim OKEGAOP)
```

# How to run?
‼️ Please install [Bun](https://bun.sh/docs/installation) first! (JS/TS runtime)

1. Install Rust: https://www.rust-lang.org/tools/install
2. Run `cargo run` in this folder.
3. Create a `main.ts` in this folder.
4. You may now play the game, `cargo run main.ts`

ALTERNATIVELY

1. Run `cargo build --release`
2. Copy the path (`target/release/subterfuge`)
3. Add it to your PATH.

# Monetisation
What? Battle pass?? Ads?? Banner ads?????

You must buy features before using them.

![errordump](https://github.com/face-hh/subterfuge/assets/69168154/e0e41387-7512-40ea-851f-a4e3e78e671b)


You can get the Premium version of the Battle Pass by supporting me on [Patreon](https://patreon.com/facedevstuff). But if you don't want to, the code is available in plain sight in the source code. ;)

Banner ads are there to embrace the feeling of gamifying your learning.

![banner](https://github.com/face-hh/subterfuge/assets/69168154/37d3742e-15bf-434f-a106-d36327859df5)


While running your code, you have a 10% of being interrupted by a spinning wheel of coupons.

![wheel](https://github.com/face-hh/subterfuge/assets/69168154/cbd5ae71-11fa-4f6b-b7e9-6763e29e1c7b)

# Playthroughs
## Complete without buying!
1. [@mybearworld](https://github.com/mybearworld)! Code [here](https://github.com/face-hh/subterfuge/issues/4)
2. [@idkhow2type](https://github.com/idkhow2type)! Code [here](https://github.com/face-hh/subterfuge/issues/6)
3. [@BlockOG](https://github.com/BlockOG)! Code [here](https://github.com/face-hh/subterfuge/issues/9)
# FAQ
- Dude I'm stuck at...
  - The `tasks/` folder contains the solutions for each problem. Please peek at it only if you REALLY can't figure out the answers.
- Why did my `main.ts` get deleted??
  - Once your solution passes, it is moved to `history/{0..100000}main.ts`. The active file however get's rewritten with the boilerplate for the next problem.
- How do I get money?
  - The prices are designed to revolve around giving you exactly how much you need for the feature required in the next problem, and so on. If you've spent money on a feature you don't need, you can go in `/src/data/savedata.json` and modify the "money" property. It isn't recommended as it may alter your gaming experience. Otherwise, you can get money from *problems* and *battlepass*.
- How is the BP XP calculated?
  - problem money / 1.5
- How many problems are there?
  - 10
- Can I contribute?
  - The structure for adding problems is quite intuitive, so if you wish you can open a pull request with a new problem in `savedata.json`. Please also include the solution inside `tasks/`.

# Known bugs
1. The RegEx used to detect "regex" also matches comments like `/** */`.
1. Every RegEx still works in comments (i.e. `// { this is: true }`).
   
# Credits
- https://temu.com
- https://fortnite.com
- https://leetcode.com & everyone who posted solutions
- [Linker](https://github.com/Linker-123?tab=repositories) for the idea

Created with 🦀 by Face
