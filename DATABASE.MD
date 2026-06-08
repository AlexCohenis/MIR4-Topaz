# Database Structure

**Database Name**: `mir4_topaz`

### Main Tables
- `accounts` — User accounts
- `characters` — Player characters
- `inventory` — Items
- `guilds` — Guild system
- `darksteel_mines` — Mining data
- `server_settings` — Dynamic rates

**Backup Command:**
```bash
mysqldump -u root -p mir4_topaz > backup_$(date +%Y%m%d).sql
