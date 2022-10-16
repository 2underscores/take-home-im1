# Identity Management (IM) Service - BE
Given the increased scrutiny on cyber-security, and upcoming regulatory crackdown, we’d rather not leak our user’s data.

SME (small-medium enterprise) banking has business’ sign up for accounts (not just individuals). Depending on SME size they may need different levels of access control, such as:
* Small SMEs (e.g. sole traders) may just need one user
* Moderate size may need 2-5 users
* The largest may need features such as SSO, MFA, password policies, external identity provider, integration, etc.

Design and implement an IM system & API to manage users and their permissions. The system should allow a user to login and access some resource based on their permissions.

### What we Expect
The task is purposely left open-ended. You are **not** expected to built a fully functional IM service that caters for the variety of requirements in SME banking. Define your scope to best showcase your abilities whilst being completable in a weekend. Include this scope and reasoning behind it in your submission.

Below are some requirements and recommendations:
* The system **must** allow:
	* CRUD users
* The system **should** allow some of:
	* Restrict actions by permissions
	* Check if user can perform a given action
	* User login
	* CRUD permissions
* The API **should** be used by some form of UI. This could be:
	* Basic functional API documentation e.g. Swagger/Readme.io
	* Custom UI
* The solution **should** be readily accessed. This could be through either:
	* Containerisation for local deployment, with strong documentation on how to setup
	* Deployable to public cloud with instructions
	* Self hosted with a link included
* The solution **may** include a test suite
* The submissions **must** include a written summary as a `README`, that **should** cover
	* Instructions on how to deploy and run
	* Key decisions and tradeoffs you made in built
	* Areas of improvement in system

### Getting Started
To get started, please clone the repo at <LINK>

### Submitting
* Make your submission as a PR to the original repo
	* Under a new directory called `<dd-mm-yyyy>-<your-email>`
* Ensure you have included the written summary `README` that covers the above points