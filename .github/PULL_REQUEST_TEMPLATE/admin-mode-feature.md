Implement Admin Mode: restrict signup/unregister to teachers, add simple prompt-based login/logout UI

- Only teachers (admins) can sign up or unregister students for activities
- Added /admin/login and /admin/logout endpoints
- Teacher credentials stored in src/teachers.json
- Frontend: prompt-based login/logout, admin token stored in localStorage
- UI disables signup/unregister for non-admins
- No database or persistent sessions (in-memory only)
