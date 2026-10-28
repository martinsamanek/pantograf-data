# Pantograf region data

Public, read-only timetable packs for the Pantograf transit quiz.
Application source code and player data are not hosted here.

`regions/<region-id>.json` points to a fully published, verified release.
Release assets contain a versioned SQLite database and its `manifest.json`.
The application verifies checksums, schema, region and service dates before use.
Older packs are timetable snapshots, not live service information.

The source, authors, license and modification notice are retained in each
manifest and database. Brno timetable data is licensed under CC BY 4.0:
KORDIS JMK, a.s.; DPMB; Statutární město Brno.
Modified: filtered and converted to a Pantograf region pack.
Source: https://datahub.brno.cz/content/379d2e9a7907460c8ca7fda1f3e84328
License: https://creativecommons.org/licenses/by/4.0/

Publication is automatic once a week. Failed builds do not replace published
data. The files contain transport data only, with no accounts, profiles,
player identifiers, analytics or credentials.
