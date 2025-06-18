# Skywalx Developer platform docs
All documentation regarding the Skywalx developer platform

## Roadmap 
**NOTE: Evolving content**

### Phase 1 - Playable platform with friends
1. Developers will create a fork of their gamemode that will create a fat image (itzg or any other that they prefer as long as we can run it on ECS without making changes to the setup). This way we still have some control over what gets deployed in production, it will however require a little bit of manual work. We could create a simple template to start from to make it as easy as possible.
- [x] ‎
2. Tag all resources for a developer their gamemode with a unique tag, so we can filter on it for billing (this will have to be a manual process every month).
- [x] ‎
3. Write down in all of the answers we get to questions asked by first onboarders and save it on GitHub wiki
- [ ] ‎
4. We provide the serversync plugin etc on a repo on codeartifact for developers to put into their fat image Manual for this phase?
- [ ] ‎

### Phase 2 - Start onboarding further aqcuintances/public trusted people and minimal marketing
1. Setup some form of image scanning and/or artifact scanning? Do we limit to our own images to tighten security?
- [ ] ‎

2. Forward ECS logs to somewhere the developer can see them for debugging, reporting purposes etc.
- [ ] ‎

3. Barebone legal stuff for 50% profit sharing agreement, license usage, onboarding/offboarding process with 1-3 month notice period, ..
- [ ] ‎

4. More in depth billing calculation, by database units used, custom API call model for internal and 3th party apis
- [ ] ‎

### Phase 3
1. Setup an ECR repo with user(s) that can authenticate to upload images. ﻿
For now we will provide a guide and help setup a template pipeline on each platform that will get the image uploaded to the ECR repo. The developers themselves are responsible for building the image to start with. 
- [ ] ‎