<p align="center">
  <img src="https://github.com/Easy-CAS/.github/assets/56296654/098c08c8-d3c1-4ac4-9f29-610ab86a292d" style="margin: 0 auto; height: 180px; width: 180px">
</p>

# Project EasyCAS (ECAS)
The project is about designing a Central Authentication Service (or CAS) as a module, that could be integrated into any other web (or not) project. It will be separated into several modules, with different purposes: one "back" module, that will take care of all the business work; and many "front" modules, that can be skipped because these won't have any logic within them, but are going to have possible integrations with many front-end frameworks such as Vue.js, Angular.js, and the list goes on.

For each module, there will be a cli tool to set it up correctly, and to edit the parameters if needed. Theoretically one wouldn't need to edit the code, so only a compiled version will be available. That way, if changes needs to be made, these will be done as PRs on the GitHub repository, and thus available for everyone afterwards.
