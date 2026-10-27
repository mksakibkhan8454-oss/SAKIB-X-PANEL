SAKIB X PANEL Firebase package

Files are at the ZIP root: index.html and admin.html.

For Firebase Auth popup/reset flows, run with HTTP/HTTPS (e.g. VS Code Live Server or Firebase Hosting), not file://.
Firebase project: sakibxpanel-d47c2.

## Admin top-up history hide
- The Admin Panel Top Ups section now has a Hide button.
- Hide only removes that top-up from the Admin Panel view.
- The original `topupRequests` record is not deleted or changed.
- User/store top-up history remains untouched.
- `adminTopupHistory` is protected by admin-only Firebase rules.
