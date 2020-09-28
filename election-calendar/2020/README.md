# 2020

The DNC Technology Department has compiled various data relating to elections in 2018, which was forked and used as a basis for an updated 2020 version.  The following text enumerates 1) table-level descriptions and then 2) column-level descriptions.

* __p2020_federal__: **(ONLY UPDATED FOR LA)** this table contains all 2020 data associated with the primaries themselves, primarily the dates and types of primaries by political party. 
* __p2020_federal_vr__: **(ONLY UPDATED FOR LA)** this table contains all data associated with voter registration for the 2020 federal primary
* __p2020_federal_ev__: **(ONLY UPDATED FOR LA)** this table contains all data associated with voting prior to election day for the 2020 federal primary
* __p2020_federal_eday__: **(ONLY UPDATED FOR LA)** this table contains all election day-specific data regarding the 2020 federal primary
* __g2020_vr__: this table contains all the data associated with voter registration for the 2020 general election
* __g2020_ev__: this table contains all data associated with voting early / prior to election day for the 2020 general election
* __g2020_eday__: this table contains election day-specific data related to the 2020 general election

## p2020_federal

| column | description |
| :--- |:---|
| state_code | Two-letter abbreviation for state, territory, etc. |
| p2020_federal_election_date | date of the federal primary election |
| p2020_runoff_federal_election_date | date (if known) of the federal primary runoff election |
| p2020_federal_dem_election_type | the exact type of democratic primary to be conducted; allowed values: 'open', 'semi-open', 'semi-closed', 'closed', 'jungle' |
| p2020_federal_rep_election_type | the exact type of democratic primary to be conducted; allowed values: 'open', 'semi-open', 'semi-closed', 'closed', 'jungle' |
| notes | additional helpful information that further explains any of the columns contained within this particular dataset |

## p2020_federal_vr

| column | description |
| :--- |:---|
| state_code | Two-letter abbreviation for state, territory, etc. |
| p2020_federal_vr_deadline | the deadline by which voters in the state must register to vote in order to vote in the 2020 federal primary |
| p2020_federal_online_vr_deadline | the explicit deadline by which voters in the state must register to vote online in order to vote in the 2020 federal primary |
| p2020_federal_runoff_vr_deadline | the deadline by which voters in the state must register to vote in order to vote in the 2020 federal primary runoff |
| p2020_federal_runoff_online_vr_deadline | the explicit deadline by which voters in the state must register to vote online in order to vote in the 2020 federal primary runoff |
| notes | additional helpful information that further explains any of the columns contained within this particular dataset |


## p2020_federal_ev

| column | description |
| :--- |:---|
| state_code | Two-letter abbreviation for state, territory, etc. |
| p2020_federal_federal_evip_start_date | the date in which early voting in person begins in the state |
| p2020_federal_evip_close_date | the date that early voting in person ends in the state |
| p2020_federal_vbm_application_deadline | the date by which voters must return their applications applying to vote by mail for the 2020 federal primary |
| p2020_federal_ballot_return_date | the date by which voters must return their ballots for the 2020 federal primary |
| notes | additional helpful information that further explains any of the columns contained within this particular dataset |

## p2020_federal_eday

| column | description |
| :--- |:---|
| state_code | Two-letter abbreviation for state, territory, etc. |
| polls_open | time at which polls open |
| polls_close | time at which polls close |
| notes | additional helpful information that further explains any of the columns contained within this particular dataset |

## g2020_vr

| column | description |
| :--- |:---|
| state_code | Two-letter abbreviation for state, territory, etc. |
| g2020_vr_deadline | the deadline by which voters in the state must register to vote in order to vote in the 2020 general election |
| g2020_online_vr_deadline | the explicit deadline by which voters in the state must register to vote online in order to vote in the 2020 general election |
| g2020_runoff_vr_deadline | the deadline by which voters in the state must register to vote in order to vote in the 2020 general election runoff |
| g2020_runoff_online_vr_deadline | the explicit deadline by which voters in the state must register to vote online in order to vote in the 2020 general election runoff |
| notes | additional helpful information that further explains any of the columns contained within this particular dataset |

## g2020_ev

| column | description |
| :--- |:---|
| state_code | Two-letter abbreviation for state, territory, etc. |
| g2020_evip_start_date | the date in which early voting in person begins in the state |
| g2020_evip_close_date | the date that early voting in person ends in the state |
| g2020_vbm_application_deadline | the date by which voters must return their applications applying to vote by mail for the 2020 general election |
| g2020_ballot_return_date | the date by which voters must return their ballots for the 2020 general election |
| notes | additional helpful information that further explains any of the columns contained within this particular dataset |

## g2020_eday

| column | description |
| :--- |:---|
| state_code | Two-letter abbreviation for state, territory, etc. |
| polls_open | time at which polls open |
| polls_close | time at which polls close |
| notes | additional helpful information that further explains any of the columns contained within this particular dataset |
