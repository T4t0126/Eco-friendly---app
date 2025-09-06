# Security Notice

## ⚠️ IMPORTANT: This is a development project with default credentials

### Security Issues:
- Default admin credentials are included in the database
- Database file (`db.sqlite3`) contains real user data
- This should NEVER be used in production

### For New Installations:
1. Delete the existing `db.sqlite3` file
2. Run: `python setup_admin.py`
3. Create your own admin user
4. Never commit the database file to version control

### Production Deployment:
- Use environment variables for sensitive data
- Use a proper database (PostgreSQL, MySQL)
- Enable HTTPS
- Use strong passwords
- Implement proper authentication

### Default Credentials (CHANGE THESE):
- Username: `t4t`
- Password: (set during installation)

**DO NOT USE THESE CREDENTIALS IN PRODUCTION!**
