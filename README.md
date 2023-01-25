# grlc-queries

A repository for the [grlc queries](https://grlc.io) that will be used for the EJP-RD Virtual Platform integration of the World Duchenne Organization.

# Queries explained

- _count_ : The Virtual Platform's first use case was to retrieve a count of the number of disease-code-matching patients within participating repositories. This is the query that should provide this answer for all VP participants.

- _phenotype-frequencies_ : This query retrieves a count of the number of patients within participating repositories that have had a phenotype code at any time.

- _kpi-ttd_ : This query measures the key performance indicator of the time between symptom onset and diagnosis.  The results for each disease code (Orpha code) are aggregated by year of diagnosis, and the time offset is measured in days.
