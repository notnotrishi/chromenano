**Run Google Nano Locally on your desktop**

Step 1: Get Chrome Canary (nightly build for devs) and configure it with instructions below. Many thanks to https://kharms.ai/nano for the instructions:
> To try it out, you need to:
> be on Mac or Windows
> be on Chrome dev / canary (version >= 127)
> enable chrome://flags/#optimization-guide-on-device-model (set to Enabled BypassPerfRequirement)
> enable chrome://flags/#prompt-api-for-gemini-nano (set to Enabled)
> re-launch Chrome and revisit page
> if this fails, try chrome://components and look for On Device Model
> this should have a version which is not 0.0.0.0 -- you can bang on the update button if you'd like (don't bang too hard)
> eventually this will have the right value (after downloading the model), then you'll need to relaunch chrome and try again

Step 2: Down the code (index.html) from this repo and open it in Chrome Canary directly (not your regular Chrome)

Step 3: Enter a prompt and test it out. It should work without wifi/locally. Note that the reponses might be slow (local) and not be reliable (as expected with any LLM)

Note: This is just a demo and not meant for regular or commercial uses.
