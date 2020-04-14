# # API-newman-POC  🚀

This Project was created to as a [mvp] 🚀 for running **newman** _postman CLI_

# Parent Project 🎅
This repository is linked to its **Parent POC Project**, here is the link [Test-Automation-Project-POCs].

# How To Run 🏃
>	Its Simple! 

**Step 1:** checkout this repository ( `git clone https://github.com/eaccmk/API-newman-POC.git` )

**Step 2:** Go the path where you did checkout ☝️

**Step 3:** Install newman `npm install newman` ref [HowTo Install newman]

**Step 4:** Run on your terminal/cmd: `newman run api_collection.json -e environment.json -d test_data.csv`


# Some Details about project

- `api_collection.json`  : Test API Collection file ( Refer [How To Get This])

- `environment.json` : Test Environment file, enables to run ☝️ same collection on different envs.

- `test_data.csv` : Test data file (This may be optional in most of the cases) 


# Sample Result run on terminal

Look at this [wiki]

# Credits 🙏

Credit goes to [agify.io] for free API available to test.

## License 🔰

**API-newman-POC** was released under [MIT License](LICENSE)


[\\]: <> (This is a commented section and should not be visible in README file)

[mvp]: <https://g.co/kgs/PkxYkz>
[Test-Automation-Project-POCs]: <https://github.com/eaccmk/Test-Automation-Project-POCs>
[wiki]: <wiki/README.md>
[How To Get This]: <https://learning.postman.com/docs/postman/collection-runs/sharing-a-collection-run/>
[HowTo Install newman]: <https://www.npmjs.com/package/newman>
[agify.io]: <https://agify.io/>