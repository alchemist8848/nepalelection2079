# NepalElection2079

This repository contains a CSV dataset of candidates for Nepal's House of Representatives Election 2079 BS (2022 AD), sourced from the Nepal Election Commission's public API. The dataset is designed for analysis in tools like Excel, Google Sheets, or Python/R.

## Purpose
The dataset (`nepal_house_election_candidates_2079.csv`) provides detailed information about candidates in the 2079 BS House of Representatives election, including their names, political parties, vote counts, and election outcomes. It is intended for researchers, analysts, and enthusiasts studying Nepal's electoral data.

## Dataset Source
- **Source**: Nepal Election Commission  
- **URL**: [https://result.election.gov.np/JSONFiles/ElectionResultCentral2079.txt](https://result.election.gov.np/JSONFiles/ElectionResultCentral2079.txt)  
- **Date Generated**: October 25, 2025  
- **License**: Data is sourced from a public API. Check the Nepal Election Commission's terms for usage restrictions.

## Dataset Details
- **File**: `nepal_houserepresentatives _election_results_2079`  
- **Format**: CSV (UTF-8 with BOM for Excel compatibility)  
- **Encoding**: UTF-8 with BOM to support Nepali text rendering in spreadsheet software  


## Dataset Fields
The CSV contains the following columns:

| Column Name         | Description                                           | Data Type | Notes                              |
|---------------------|-------------------------------------------------------|-----------|------------------------------------|
| SerialNo            | Serial number of the candidate                         | Integer   |                                    |
| CandidateName       | Full name of the candidate                            | String    | May contain Nepali text            |
| Gender              | Gender of the candidate (e.g., Male, Female)          | String    |                                    |
| Age                 | Age of the candidate                                  | Integer   |                                    |
| PoliticalPartyName  | Name of the candidate's political party               | String    | May contain Nepali text            |
| SymbolName          | Name of the election symbol                           | String    | May contain Nepali text            |
| SymbolID            | Unique ID for the election symbol                     | String    |                                    |
| DistrictName        | Name of the district                                  | String    | May contain Nepali text            |
| DistrictCd          | District code                                         | String    |                                    |
| StateName           | Name of the province/state                            | String    | May contain Nepali text            |
| State               | State/province code                                   | String    |                                    |
| SCConstID           | State constituency ID                                 | String    |                                    |
| CenterConstID       | Central constituency ID                               | String    |                                    |
| TotalVoteReceived   | Total votes received by the candidate                 | Integer   |                                    |
| Rank                | Rank of the candidate based on votes                  | Integer   |                                    |
| Remarks             | Election status (e.g., "Elected")                     | String    |                                    |
| DOB                 | Date of birth of the candidate                        | String    | Format may vary                    |
| CTZDIST             | Citizenship district                                  | String    | May contain Nepali text            |
| FATHER_NAME         | Name of the candidate's father                        | String    | May contain Nepali text            |
| SPOUSE_NAME         | Name of the candidate's spouse                        | String    | May contain Nepali text            |
| QUALIFICATION       | Educational qualification                             | String    | May contain Nepali text            |
| EXPERIENCE          | Professional or political experience                  | String    | May contain Nepali text            |
| NAMEOFINST          | Name of institution (e.g., educational)               | String    | May contain Nepali text            |
| ADDRESS             | Address of the candidate                              | String    | May contain Nepali text            |
| OTHERDETAILS        | Additional details about the candidate                | String    | May contain Nepali text            |
| CandidateID         | Unique ID for the candidate                           | String    |                                    |
| PartyID             | Unique ID for the political party                     | String    |                                    |
| ElectionPost        | Post contested (e.g., House of Representatives)       | String    |                                    |
| CastedVote          | Number of votes cast in the constituency              | Integer   |                                    |
| TotalVoters         | Total registered voters in the constituency           | Integer   |                                    |
| Samudaya            | Community or social group (if applicable)             | String    | May contain Nepali text            |

## Usage
The dataset can be used for:
- Analyzing candidate demographics (e.g., gender, age, qualifications).  
- Studying election outcomes by district or province.  
- Visualizing vote distribution and party performance.  
- Researching political representation in Nepal's 2079 BS election.  
