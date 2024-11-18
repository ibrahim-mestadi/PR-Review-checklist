# PR-Review-Checklist  

### **General Preparation**  
- [ ] Clone the branch locally.  
- [ ] Run the build and ensure there are no build errors.  
- [ ] Execute all automated tests (unit, integration, or end-to-end) if available.  
- [ ] Manually test features related to the newly added or modified code for functionality.  

- [ ] Test all impacted features to ensure there are no regressions.  
- [ ] Confirm that the PR fulfills the requirements stated in the issue/task.  

---

### **Code Quality**  

- [ ] Ensure all changes align with the intended functionality.  
- [ ] Confirm no unused functions/methods (dead code) are introduced.  
- [ ] Verify code is non-redundant and DRY (Don’t Repeat Yourself).  
- [ ] Code is clear and readable without requiring extensive comments or documentation.  
- [ ] Check for potential crash scenarios or bugs in edge cases.  
- [ ] Ensure proper handling of error scenarios and exceptions.  

- [ ] Verify that responsibilities are clearly separated between modules or classes.  
- [ ] Check adherence to project architecture and conventions (naming, folder structure, etc.).  

---

### **Technical Aspects**  

- [ ] Ensure the code is optimized for performance and doesn’t introduce unnecessary overhead.  
- [ ] Validate that database queries, loops, or heavy computations are efficient.  

- [ ] Ensure the code is modular and reusable wherever applicable.  
- [ ] Validate that new files, functions, and methods are logically placed and named.  

- [ ] Confirm that any complex logic is documented (if not self-explanatory).  
- [ ] Verify any new APIs, endpoints, or configurations are documented (e.g., in README, Swagger, etc.).  

---

### **Collaboration and Standards**  

- [ ] Ensure proper git hygiene:  
  - [ ] Meaningful and concise commit messages.  
  - [ ] Avoid unnecessary merge commits (use rebases if applicable).  

- [ ] Check that adequate test cases are added for new features or changes (unit, integration, or functional tests).  
- [ ] Confirm all tests are passing in CI/CD pipelines.  

- [ ] Verify adherence to coding standards and linters configured for the project.  
- [ ] Ensure compatibility with existing systems and no disruption to production workflows.  

---

### **Approval Decision**  

- [ ] If all tests pass and the PR meets all quality and functionality criteria, approve and merge the PR.  
- [ ] Provide constructive feedback if any changes are required, and request updates.  

---

### **Final Note**  

Feel free to adjust this checklist to meet your specific project or team requirements. It serves as a flexible framework to ensure a thorough and structured review process, helping maintain quality, functionality, and collaboration.
