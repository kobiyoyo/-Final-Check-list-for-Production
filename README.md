# Final-Check-list-for-Production

- [ ] Linter is properly configured. 

- [ ] The project have several small methods / functions each with one single responsability .

- [ ] Only RESTFUL routes are defined in the app.Only routes that are used are defined

- [ ] All operations that require working on collections of items (filtering, sorting, counting) are handled by SQL queries - ActiveRecord methods or plain SQL encapsulated in descriptive scopes that can be joined if needed

- [ ] File not related to the projects should not be commited.

- [ ] No commented code 

- [ ] Use correctly private methods and accessors.

- [ ] The project structure is correct : several files
 - correct naming of classes,files and DIR structure
 - all logic operations should be encapsulated in models/services -
 - if not an api project move view related logic to helpers

- [ ] Methods / functions should have meaningful names and follow conventions: snake_case, ? suffix when returning a boolean

- [ ] User input is validated to make sure that none with bad intentions can destroy your app.

- [ ] User input is passed to controller in a safe way

- [ ] n+1 problem is addressed properly

- [ ] Please make sure no errors from linter
