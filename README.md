
Yesterday 5:33 PM

Take-Home Assignment Smart Staff Request (Owner Flow)(1).pdf
PDF
build a project on expo after give me the project in zip file

I've built the Smart Staff Request app using React Native and Expo based on your PDF assignment. The project includes the owner workflow, partner matching, request confirmation, documentation, and tests. 


📦 Download Your Project

What's included?
Feature	Status
React Native + Expo setup	✅
Plain-language staff requests	✅
Automatic request parsing	✅
Review and edit booking details	✅
20 sample staff partners	✅
Partner matching and ranking	✅
Score-based explanations	✅
Booking confirmation	✅
Request history	✅
README documentation	✅
Design note	✅
Two unit tests	✅
Important: This version uses a local, rule-based parser rather than a live LLM. The project runs without an API key. Real AI integration and a backend would require additional implementation.

How to Run the Project
Step 1: Extract the ZIP file

Extract Smart-Staff-Request-Expo.zip to a folder on your computer.

Step 2: Open the project in VS Code

Open the extracted smart-staff-request folder.

Step 3: Open the VS Code terminal

Run these commands one by one:

npm install
Then:

npx expo start
Step 4: Run the app

Android phone: Install Expo Go and scan the QR code.

Android emulator: Press a in the Expo terminal.

iOS: Press i if you have the appropriate Apple development environment.

Official setup guide: Expo documentation

Run the Tests
The project includes two unit tests, and both passed when I ran them.

To run them again:

npm test
One Important Note
The assignment also requests a four-minute screen recording demonstrating the app. 

 You will need to record that after running the project on your computer.

Start by downloading the ZIP and running npm install. If you encounter an error, send me a screenshot of the VS Code terminal, and I'll help you fix it.


1b3c60eb-dc5e-441d-af94-ae3a01c4b203.png

I'll explain step by step how to push your Smart Staff Request React Native + Expo project to GitHub using VS Code. Follow these steps in order.

Step 1: Create a GitHub repository
Open GitHub.

Log in to your account.

Click the + icon in the top-right corner.

Select New repository.

Enter the following details:

Repository name: Smart-Staff-Request-Expo

Description: Smart Staff Request app built using React Native and Expo.

Select Public (if you want recruiters to see it).

Leave Add a README file unchecked.

Click Create repository.

Keep the repository page open because you'll need its URL.

Step 2: Open your project in VS Code
Open the project folder:

C:\Users\Mohd Raiyan\Downloads\Smart-Staff-Request-Expo\smart-staff-request

Open the VS Code terminal using:

Terminal → New Terminal

Make sure the terminal is inside your project folder.

Step 3: Check whether Git is installed
Run:

git --version
If you see a version number, Git is installed.

If Git is not recognized, install it from Git for Windows and restart VS Code.

Step 4: Initialize Git
Run these commands one at a time:

git init
git branch -M main
Step 5: Create a .gitignore file
Before uploading, ensure you don't upload unnecessary files or secrets.

Create a file named .gitignore in your project root and add:

node_modules/
.expo/
dist/
web-build/
.env
.env.*
!.env.example
npm-debug.log*
.DS_Store
Important: Never upload API keys or passwords to GitHub.

Step 6: Add and commit your files
Run:

git add .
Then:

git commit -m "Initial commit: Smart Staff Request Expo app"
If Git asks you to configure your identity, run these commands with your own name and email:

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
Then repeat the commit command.

Step 7: Connect your GitHub repository
On the GitHub repository page, copy your repository URL. It will look like this:

https://github.com/YOUR-USERNAME/Smart-Staff-Request-Expo.git

Now run the following command, replacing the example URL with your actual URL:

git remote add origin https://github.com/YOUR-USERNAME/Smart-Staff-Request-Expo.git
Verify the connection:

git remote -v
Step 8: Push your project to GitHub
Run:

git push -u origin main
If prompted, sign in to GitHub through your browser and authorize the operation.

Once the command succeeds, refresh your GitHub repository page. Your project files should appear there.

All commands together
After creating the repository and .gitignore file, your main commands are:

git init
git branch -M main
git add .
git commit -m "Initial commit: Smart Staff Request Expo app"
git remote add origin https://github.com/YOUR-USERNAME/Smart-Staff-Request-Expo.git
git push -u origin main
Note: Run git remote add origin only once. If you've already configured the remote, skip that command.

If you get an error
Common errors include:

git is not recognized — Git isn't installed or isn't available in your PATH.

remote origin already exists — Check your existing remote using git remote -v.

Authentication failed — Sign in to GitHub and authorize Git.

rejected (fetch first) — The remote repository already contains commits that need to be reconciled.

My suggestion: Start with Step 1. If you encounter an error in VS Code, send me a screenshot of your terminal, and I'll tell you exactly which command to run next.



Pasted markdown.md
File

Pasted markdown (2).md
File
write clear readme.md files and show command very visible

I've created a clean, professional README.md for your StaffUp: Smart Staff Request (React Native + Expo) project. I've also made the commands easy to find and copy.

📥 Download Your Files
1. Clean README.md


2. Complete project ZIP with the updated README


🚀 Most Important Commands
Open your project folder in VS Code and run these commands in the terminal, one at a time.

Step 1 — Install dependencies

npm install --legacy-peer-deps
Step 2 — Start the Expo app

npx expo start
Step 3 — Run the tests

npm test
Step 4 — Check TypeScript

npm run typecheck
Step 5 — Test all ten sample requests

npm run smoke
📤 Push Your Project to GitHub
After opening the project folder in VS Code, run:

git add .
git commit -m "Update README documentation"
git push
These last three commands assume Git is already initialized and your GitHub repository is connected.

Important: Review the README and run the app before submitting the project to a recruiter. The README documents the app's features, setup, tests, ten sample requests, project structure, and known limitations. 



remove unneccasary line

I've removed unnecessary lines and made your README shorter, cleaner, and easier to read.

📥 Download Updated Files


🚀 Main Commands
1. Install dependencies

npm install --legacy-peer-deps
2. Start the Expo app

npx expo start
3. Run tests

npm test
4. Push changes to GitHub

git add .
git commit -m "Clean up README"
git push
The updated README keeps the essential setup instructions, features, test results, project structure, and limitations while removing unnecessary explanations. 



give me short readme.md note only necessary thing are there

Here is a short README.md containing only the essential information for your GitHub project.

📥 

StaffUp — Smart Staff Request
A React Native + Expo app for creating staff requests, reviewing details, matching partners, and confirming bookings.

Run the App
Install dependencies:

npm install --legacy-peer-deps
Start the app:

npx expo start
Scan the QR code with Expo Go, or press a to open an Android emulator.

Tests
npm test
npm run typecheck
npm run smoke
Tech Stack
React Native and Expo

TypeScript and Expo Router

React Context + reducer

Rule-based parser with optional Claude adapter

Notes
Uses sample partner data.

No backend or persistent storage.

Never upload .env or API keys to GitHub.

See DESIGN_NOTE.md and AI_USAGE.md for more details.

To use it: Rename README-short.md to README.md and replace the existing README in your project folder. 



Library
/
README.md



StaffUp: Smart Staff Request (Owner Flow)
React Native + Expo take-home project
A restaurant owner describes a staffing need in plain language. The
app turns it into a structured request, lets the owner review and
correct the details, ranks matching partners, and confirms the
booking.

🚀 QUICK START --- RUN THESE COMMANDS
Open a terminal in the project root (the folder containing
package.json).

1. Install dependencies
npm install --legacy-peer-deps
2. Start Expo
npx expo start
3. Open the app
Android phone: Scan the QR code with Expo Go.

Android emulator: Press a in the Expo terminal.

iOS simulator: Press i on a Mac with the required Apple
development tools.

--legacy-peer-deps is used because this project has a
peer-dependency conflict involving Expo Router's web dependencies. If
installation fails, check package.json before manually changing
package versions.

🧰 OTHER USEFUL COMMANDS
Run these from the project root:

Purpose Command

Run the two unit tests npm test
TypeScript type check npm run typecheck
Parse all ten assignment requests npm run smoke
Verify README ranking results npx tsx scripts/verify-readme.ts
Start Expo and clear cache npx expo start -c

What the App Does
The owner workflow has five stages:

Request: The owner types a staffing request in plain language.
The ten assignment examples are available as quick-select chips.

Parse: A built-in rule parser, or the optional Claude adapter,
extracts staffing details.

Review and correct: The owner reviews a summary and edits
fields. Missing or uncertain details are highlighted. Required
questions must be answered before continuing.

Match: Partners are ranked by skill fit, availability, distance,
and reliability. Explanations are generated from actual score
components.

Confirm: The owner chooses a partner and confirms the booking. A
request list and mock notification toast complete the flow.

Tech Stack
Expo and React Native

TypeScript and Expo Router

React Context + reducer for state

Reanimated

Rule-based parser with optional Claude API adapter

Two focused unit tests: validator and matching scorer

This is a frontend-only demo. It does not include a real backend,
authentication, payments, or persistent storage.

Optional Environment Variables
The app works without configuration using the built-in rule-based
parser.

To use the optional Claude adapter:

Copy .env.example to .env.

Set these variables:

Variable Purpose

EXPO_PUBLIC_LLM_API_KEY Anthropic API key

Security: Never commit a real API key. Keep .env out of Git.
Variables prefixed with EXPO_PUBLIC_ are bundled into the client app
and are not secret-safe for production. A real deployment should call
the LLM through a backend.

Results for the Ten Assignment Requests
These are the recorded rule-parser results from 27 October 2026. Run
npm run smoke to reproduce parser output. Missing details are
intentionally sent to review instead of being silently guessed.

# Request Parsed result / outcome

1 Need 2 Chinese chefs Parsed as 2 Chinese
and 1 helper for chefs + 1 kitchen
Saturday 6 PM to 11 PM, helper, Saturday 31
Connaught Place area. October, 6--11 PM,
Connaught Place. No
blocking questions.
Recorded top chef
match: Dorjee Lama (1.4
km, score 97); Pema
Bhutia is unavailable
that date.

2 1 tandoor chef, 25th Parsed as 1 tandoor
October, 11am--4pm, chef, 11 AM--4 PM,
Rajouri Garden. Rajouri Garden. The
requested date has
passed, so the owner
must choose a future
date.

3 Deep cleaning crew of 3 Parsed as 3 deep
for Sunday morning, cleaners, Sunday 1
Pitampura outlet. November, Pitampura.
"Morning" is
interpreted as 8 AM--12
PM with medium
confidence. Only 2 deep
cleaners exist in seed
data, so the app
reports a shortfall.

4 Waiter, 3 din ke liye, Parsed as 1 waiter,
28 se 30 October, shaam 28--30 October, from 6
6 baje se, Karol Bagh. PM, Karol Bagh. End
time is uncertain and
must be reviewed.

5 Need someone for Parsed as one person of
tomorrow evening. unknown type, 28
October, 6--10 PM, with
no area. The owner must
choose a staff type and
area.

6 2 chefs, Chinese, CP, Parsed as 2 Chinese
Sat chefs, Saturday 31
October, Connaught
Place. Start and end
times are missing and
must be supplied.

7 Chef for party next Parsed as one chef with
week cuisine unknown and
note "For a party."
Date, time, and area
need clarification.

8 Need a cook, budget max Parsed as one chef,
1500 per day, Lajpat ₹1,500/day budget,
Nagar, this weekend Lajpat Nagar, with
Saturday 31 October
suggested and Sunday as
an alternative. Some
staff/time fields need
review. A top-ranked
partner may still
exceed budget; see
limitations.

9 Need 2 chefs Saturday Split into two
and 1 cleaner Sunday, bookings: 2 chefs
both at Saket. Saturday and 1 deep
cleaner Sunday, both in
Saket. They are
confirmed one at a
time.

Honest assessment: These results describe the recorded test run;
they do not mean the parser understands every possible request. The
weakest cases are those that omit several required fields and those
where an end time has to be suggested.

Matching and Ranking
The matching scorer considers:

Skill/subcategory fit

Availability

Distance

Reliability

The one-line explanation is generated from the numeric score components,
not written by an LLM. If fewer partners are available than requested,
the app reports the shortfall.

Project Structure
src/
  app/          Expo Router screens: request, review, matches, done, requests
  components/   Reusable UI components
  lib/
    parse.ts    Rule-based parser
    llm.ts      Optional Claude adapter with rule-parser fallback
    validate.ts Validation, confidence, blockers, summary
    score.ts    Partner scoring, ranking, explanations
  data/         Seed partners, locations, and bookings
  state/        React Context + reducer
  __tests__/    Validator and scorer tests
scripts/
  smoke.ts      Runs the ten sample requests
DESIGN_NOTE.md  Design decisions and trade-offs
AI_USAGE.md    AI usage and rejected suggestion
Known Limitations
The rule parser is not a full language model. Unrecognised wording
may result in missing fields and clarification questions.

"Next Saturday" can be ambiguous; the parser uses a best-effort
interpretation and suggests an alternative.

Availability for multi-day bookings is averaged across days.

Confirmed bookings do not persistently mark partners as busy for
future bookings, so the same partner could be selected again.

Distances use area centroids rather than the exact restaurant
address. If the area is missing, central Delhi is used as a
fallback.

The optional client-side EXPO_PUBLIC_ API key is visible in the
app bundle. Use a backend proxy in production.

Bookings reset when the app restarts.

Android and iOS are the intended targets; web is not the target
platform.

Tests
The assignment asks for two focused tests:

Parse-output validator

Matching scorer

Run:

npm test
Additional checks:

npm run typecheck
npm run smoke
Before Submitting
Run the app on your target device.

Run npm test, npm run typecheck, and npm run smoke.

Confirm .env and API keys are not committed.

Review DESIGN_NOTE.md and AI_USAGE.md.

Record the four-minute demo: request 1 end-to-end, ambiguous
request 5, and one corrected field.

Push the project to GitHub.

