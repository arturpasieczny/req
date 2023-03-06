# Adding a view
## Functional requirements
1. System must allow the user to add a new view in Deal List page.
2. Adding a view should be available only, when user has already added no more than number of views as defined in req-345234 'User must be able use up to 50 views'.
3. User should be able to choose:
   - add already existing view chosen from the list of views:
     - predefined (standard)
     - created by users (if he has access, see pt TODO)
   - create a new view
4. List mentioned in pt 3 should be grouped by views:
   - predefined (standard)
   - created by other users
   - created by team members
   - created by user
5. List mentioned in pt 3 should be searchable in any part of view name
6. New views must allow to specify following access policies:
   - 'Private', accessible only for user who creates the view
   - 'My Team', accessible for users who belong to at least one group, where creator is a memeber as well
   - 'Everyone', accessible for users, who belong to the same system client
7. New view's name must be unique in the scope of the system client and predefined views
8. New view is created with following setup:
   - no filters applied
   - default sorting
   - default columns (see req xyz)
9. Upon selection of existing view or entering details of new view, user should be redirected to Deal List page,
with the new view opened.

## Interface requirements
1. Searching for a view should be case insensitive
2. Searching for a view should search for any part of the view name
3. Search should have a button to clear the search phrase 
4. List of available existing views should be presented in a scrollable dropdown, no bigger than 5 items
