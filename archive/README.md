# Kestrel Field Archive

Internal archive of field case studies.

- `index.json` - catalogue used to find records (id, title, keywords, publication date).
- `records/<id>.json` - authoritative archive record: title, ordered contributor list
  (each with an `equal_contribution` flag), venue, year, publication date and canonical links.
- `briefs/<id>.pdf` - one-page brief; page 1 repeats the contributor order printed in the record.

The record JSON is authoritative for the contributor order and the equal-contribution
flags. The catalogue is only a finding aid and does not repeat the contributor list.
