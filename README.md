# zetra-godot
Welcome to Zetra! Your sweet new companion for Godot. Zetra seamlessly bridges your design workflow into the engine, helping you create stunning, smooth UI interfaces with absolute ease. Think of it as a cozy toolkit built to make your game look gorgeous without the stress. Let's create something beautiful together! 

# Zetra Blue for Godot

**An all-in-one Godot 4.7.2 plugin featuring avatar tools, a visual novel builder, and built-in editors for photos, vectors, video, documents, and spreadsheets and more**

* **Supported Engine:** Godot **4.7.2** *(other versions are not supported)*
* **Included Terrain System:** **Terrain3D** *(bundled under its own MIT License)*
* **One-Click Setup:** Enable the plugin once to activate all editor tabs automatically
* **Website / Download:** [zetra-7oh.pages.dev](https://zetra-7oh.pages.dev/)

For a complete breakdown of the included editor tabs, avatar utilities, installation steps, and legal disclaimers, please visit the official [Zetra Blue for Godot](https://zetra-7oh.pages.dev/) website.

================================================================================

PROJECT PHILOSOPHY & FAQ

================================================================================

1. WHY THIS TOOL EXISTS (THE GABE NEWELL SERVICE PHILOSOPHY)
Most avatar and 3D workflows force creators to pay for separate utilities, 
juggle multiple programs, or boot up heavy software just to handle basic tasks 
like texture painting. This project brings those core tools together into one 
place—without paywalls, subscriptions, or corporate lock-in.

As Valve co-founder Gabe Newell famously put it: "Piracy is almost always a 
service problem and not a pricing problem." When software is buried behind 
paywalls, invasive logins, and clunky workflows, users get frustrated. If a 
workflow is broken, the goal isn't to charge people for a workaround—it's to 
provide a faster, cleaner, safer service that anyone can use right out of the 
box.

2. HOW IT WAS BUILT & CONTINUOUS QUALITY CHECKS
* Solo Development Under a Protective Studio Banner: This entire tool is built 
  and maintained by one developer. There is no corporate team, no outside 
  funding, and no investors behind it. The studio name exists solely as a 
  protective legal banner to shield the project's identity and ensure the tool 
  remains fairly accessible to everyone.
* Clean-Room & Hand-Coded: Standard algorithms (like noise generation, 
  timelines, and brush systems) were broken down into core mathematical and 
  logical steps and written by hand from scratch—zero copied source code. 
  Where AI was used to map out logic skeletons early on, every subsystem went 
  through months of manual rewriting, debugging, and rebuilding until it 
  worked reliably.
* Fix vs. Rebuild Triage: Every part of the codebase is evaluated on simple 
  math: what can be fixed cleanly vs. what cannot. If a system cannot be fixed 
  cleanly, it gets torn down and rebuilt rather than patched over with fragile 
  band-aids.
* Automated Regression Testing: Past broken builds, busted UI states, and 
  failed tool snapshots are kept as permanent test benchmarks. Automated 
  regression suites run continuously against those old failures so previously 
  fixed UI or tool bugs never sneak back into a new release.

3. ZERO BACKGROUND TRACKING (LOCAL SELF-DIAGNOSTICS ONLY)
* Zero Spyware or Telemetry: This tool does not harvest your personal data, 
  monitor your projects, or silently phone home to external servers.
* Local Safety Checks: The only monitoring built into the software is a local 
  self-diagnostic and integrity check running strictly on your own machine. 
  Its sole job is to alert you immediately if a module is broken or corrupted 
  so you don't accidentally open a faulty tool or expose your files to risk.

4. RUNTIME TRANSPARENCY & CRYPTOGRAPHIC BUILD VERIFICATION
* Clean Directory Layout: All configuration assets, manifests, and working 
  directories are kept in a clean, readable structure. Nothing is buried in 
  hidden registry keys or obscured background folders.
* Pre-Release Network & Dependency Audits: Every release build is verified 
  using network packet monitors (like Wireshark) and process/file monitors to 
  confirm zero stray network calls, zero third-party tracking dependencies, 
  and zero leftover debug artifacts.
* Verify Runtime Behavior & Integrity Yourself: While the application ships as 
  a closed-source binary, you never have to take my word on what it does on 
  your machine or whether a download has been tampered with. Every official 
  release publishes SHA-256 checksums so you can cryptographically verify that 
  your executable is clean and unmodified, and you are encouraged to run your 
  own packet captures and file monitors against the process to confirm it 
  makes zero unauthorized connections.

5. OPT-IN DIAGNOSTIC PACKAGES & DIRECT SUPPORT
* You Stay in Control: Instead of collecting crash logs behind your back, the 
  tool generates a clean diagnostic package locally when something goes wrong. 
  You decide whether to send that package directly to me.
* Direct Fixes, No Support Runaround: When you send a failure package, I inspect 
  it personally to pinpoint the exact bug and hand you back a clean, working 
  build—no chatbots, no ticket queues, and no corporate runaround.

6. PUBLIC FIX RELEASES, PLANNED UPDATE API & SANDBOXED TESTING
* Fixes Shared With Everyone: Whenever a reported issue is diagnosed and 
  repaired, that clean build is made public so anyone else experiencing the 
  same issue can upgrade right away.
* Upcoming One-Click Update API: I am building a dedicated update API that 
  will let users click a single button to submit an opt-in diagnostic package 
  and pull down cryptographically signed, verified updates seamlessly.
* Sandboxed Testing & Badged Review: Every single build—even early, unstable 
  builds—is tested inside an isolated environment before release. Nothing 
  ships until it passes automated regression checks and manual vetting by 
  badged community testers.
* Strict Malware Screening for Uploads: To protect the support pipeline from 
  malicious payloads, every user-submitted diagnostic package is isolated and 
  detonated for malware screening inside a locked-down virtual machine before 
  ever being opened for review.

7. CREATOR PROTECTION & TERMS OF SERVICE
* Your Work Stays Yours: The Terms of Service and EULA are written to protect 
  creators by default. No company—including this project—claims rights over 
  what you build, nor will your work be scraped or harvested.
* Built-In Authorship Signatures: Files created with this tool carry a custom 
  signature to help verify origin and protect creator ownership.

8. CLOSED-SOURCE SCOPE, SECURITY RESEARCH & MODDING
* Why This Tool Is Closed-Source (Anti-Abuse, Not Secrecy): Normally, closed-
  source software is used to hide tracking or lock users into subscriptions. 
  Here, the sole reason for shipping a closed-source binary with basic asset 
  and signature guards is to stop bad actors from cloning the project, 
  stripping out the built-in authorship signatures that protect creators' 
  work, bundling trojans into fake forks, or slapping paywalls onto a tool 
  meant to stay free. Closed-source here protects the ecosystem—it is never 
  used as security-through-obscurity or a substitute for verifiable safety.
* Verifiable Trust Without Source Access: You don't have to blindly trust a 
  closed-source executable. Between published SHA-256 build hashes, clean-room 
  architecture, local-only diagnostics, and open encouragement to audit the 
  process with Wireshark and file monitors, every runtime behavior can be 
  independently verified on your own machine.
* Good-Faith Security Research & Modding Welcome: Security researchers, 
  reverse engineers, and community modders are welcome to inspect the binary, 
  audit its runtime behavior, and report vulnerabilities in good faith without 
  fear of legal retaliation. If you find a security issue, want to coordinate a 
  disclosure, or want to build an official plugin or integration, contact me 
  directly via encrypted Proton Mail at [INSERT YOUR PROTON EMAIL HERE] (a 
  dedicated, tracker-free channel protected against spam and bad-faith 
  noise).

9. SUPPLY-CHAIN SAFETY, ARCHIVES & TORRENTS
* Why Pre-Release Builds Aren't Archived: Holding back early builds isn't about 
  gatekeeping—it's about quality control. Unfinished builds have broken 
  features that can corrupt user projects, which is why pre-release testing 
  stays restricted to our test environment and badged testers. An official 
  release stamp means the build has survived full scrutiny and is stable.
* No Torrents or Third-Party Repacks (Payload Protection): Distribution isn't 
  about chasing money—I don't care about piracy. As Gabe Newell noted, the 
  easiest way to beat piracy is simply to offer a better, more convenient 
  service than the pirates. Because this tool is already free and available 
  directly without lock-in, torrents are completely unnecessary. Please do NOT 
  upload builds to torrents or third-party mirrors: once a binary enters a 
  torrent swarm, broken builds cannot be recalled, and attackers routinely 
  bundle trojans and malicious payloads into unverified repacks under popular 
  project names. Always download from the official source and check the 
  SHA-256 hash so you know no one slipped a payload into your build.

10. PRIVACY-FIRST MODERATION, ENFORCEMENT & TOS CLARIFICATIONS
* Strict Privacy Protection for Everyone: Any moderation review, rule 
  enforcement, or formal takedown process—including DMCA notices—is handled 
  strictly in private. No personal details, account records, or identifying 
  information will ever be published online or used to publicly shame anyone.
* Living Terms & Good-Faith Clarifications: The Terms of Service and EULA are 
  actively maintained to remain clear, fair, and free of loopholes. When users 
  or community members point out edge cases or grey areas in the rules, the 
  Terms are updated transparently to close those gaps rather than relying on 
  gotcha enforcement.
* Accountability Without Public Spectacle: Rule violations and unauthorized 
  redistribution are addressed directly through formal, private channels 
  rather than public callouts or community drama.

11. FOCUS ON THE WORK
* Constructive Feedback Welcome: This project is built to give creators safe, 
  fast, reliable software. If you have constructive feedback, bug reports, or 
  ideas on how to improve a feature, reach out anytime—I'm here to build.
  
================================================================================
