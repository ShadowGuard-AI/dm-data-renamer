![Introduction banner: one loose gold leaf sheet where the window light lands first, lifted corners visible, cushion and gilder knife below it, bookplates and ribbons in the middle distance, oak shelving and sealing wax farther off, no writing anywhere](intro-banner.png)

# dm-data-renamer

Catalogue entry, author first: dm-data-renamer, entered this day at the gilder bench. The name above is set in Candal in iron gall ink, with a small dated stamp graphic at the left of this title block and the gold leaf sheet drawn small beside this first heading only.

<img src="logo.png" alt="Logo: one gold leaf sheet alone, flat from above, uneven edges, bright centre, lifted corners, one sealing wax fleck" width="180">

![Banner](banner.png)

![Animated scene in three rows: shelves with motes drifting down the sunbeam, a hand flipping one loose bookplate in its tray, and a hand ferrying gold leaf on a knife onto the cushion](scene.svg)

![Heavy separator: a mustard rule with a gold leaf and a gliding ribbon marker](sep-heavy.svg)

# dm-data-renamer
Rename columns or tables in a database or file to generic names (e.g., column1, table_a) while preserving relationships based on foreign keys or naming conventions. Useful for quickly anonymizing schema information. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

A table keeps its rows. A column keeps its values. Foreign keys keep pointing at the partners they pointed at before, because the relationships are the gesso shape under the surface. What changes is the name a stranger reads.

> Guard heading: Keys Keep Pointing True.

![Heavy separator: a mustard rule with a gold leaf and a gliding ribbon marker](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowGuardAI/dm-data-renamer`

> Catalogue entry: the README fetch line writes the organisation lacking its hyphen. The fault stays readable inside this record. The correction stands on the website, labelled as a correction.

![Light separator: a short centred mustard rule with a small gold leaf](sep-light.svg)

## Usage
`./dm-data-renamer [params]`

The run exits 1 when the input is not a readable database, when it holds no user tables, or when any table or column rename fails. In the failure case the changes are rolled back where the database allows it. The completed successfully line and exit 0 mean every table and column rename succeeded.

> Catalogue entry: a database that cannot be read finishes at exit 1.

> Catalogue entry: a database holding no user tables finishes at exit 1.

> Catalogue entry: an unsuccessful rename unwinds wherever the database permits.

Main button: Lay the New Names. Dry run toggle label: Rehearse Without Laying. Breathe before you commit, and rehearse on a dry run when the page matters.

![Light separator: a short centred mustard rule with a small gold leaf](sep-light.svg)

## Parameters
- `-h`: Show help message and exit
- `--prefix_table`: No description provided
- `--prefix_column`: No description provided
- `--dry_run`: Perform a dry run without applying changes.
- `--log_file`: No description provided

Three controls stand in this list with no description provided: both prefix flags and the log file flag. This page assigns none of them any behaviour past their names. Rollback is promised where the database allows it, and no permitting database is named. How ties kept through naming conventions get recognised once a rename changes the convention is not explained in the source.

> Failure heading: When a Rename Fails.

![Light separator: a short centred mustard rule with a small gold leaf](sep-light.svg)

## License
Copyright (c) ShadowGuardAI

![Heavy separator: a mustard rule with a gold leaf and a gliding ribbon marker](sep-heavy.svg)

## Filed at the gilder bench

The finished page: leaf laid, leaf burnished, bench at rest, edition complete, press quiet in the next room. Buttons here are pressed paper over board, cut to the gold leaf sheet with its lifted corner, rimmed with bookplates in vellum. A card reporting a rolled back run carries a small unlaid leaf in its top corner, corners still lifted. No other card carries that leaf.
