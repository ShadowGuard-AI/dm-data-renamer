![Banner](banner.png)

# dm-data-renamer
Rename columns or tables in a database or file to generic names (e.g., column1, table_a) while preserving relationships based on foreign keys or naming conventions. Useful for quickly anonymizing schema information. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

## Install
`git clone https://github.com/ShadowGuardAI/dm-data-renamer`

## Usage
`./dm-data-renamer [params]`

The run exits 1 when the input is not a readable database, when it holds no user tables, or when any table or column rename fails. In the failure case the changes are rolled back where the database allows it. The completed successfully line and exit 0 mean every table and column rename succeeded.

## Parameters
- `-h`: Show help message and exit
- `--prefix_table`: No description provided
- `--prefix_column`: No description provided
- `--dry_run`: Perform a dry run without applying changes.
- `--log_file`: No description provided

## License
Copyright (c) ShadowGuardAI
