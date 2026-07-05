# EVIDENCE SOURCES — official links and verification log

Every file in this folder traces to a government source. This page records the exact
links and the dates each was pulled/re-verified, so anyone (a regulator, an attorney,
a court) can reproduce the lookup themselves.

---

## 1. DBPR statewide mobile home park extract (`DBPR_mhpark_extract_zephyr_and_surujbali_rows_2026-07-02.csv`)

- **Official live file (DBPR's own published data extract):**
  <https://www2.myfloridalicense.com/sto/file_download/extracts/mhmailing.csv>
  Published by the Fla. Dept. of Business & Professional Regulation, Division of
  Florida Condominiums, Timeshares, and Mobile Homes.
- **The Zephyr row, verbatim from the live file:**
  `"PRMZ001210",8896,"ZEPHYR MOBILE HOME PARK","Pasco","3950 DIXON ST","ZEPHYRHILLS","FL","33542",82,12/20/1985 12:00:00AM,"Approved","Delinquent","DE00014756","CHANG, HYE SUK","C/O SUK CHANG","20019 PAINTING NATURE LANE","TAMPA","FL","33647"`
- **Field-by-field reading of that row** (the file publishes no header row; labels are
  inferred from the data — for sworn use, have DBPR confirm in writing):
  field 9 = **82 lots** · field 10 = **prospectus approved 12/20/1985** · field 11 =
  **Approved** · field 12 = **fee status: DELINQUENT** (annual per-lot fees,
  § 723.007, Fla. Stat.) · field 14 = **owner of record: CHANG, HYE SUK**.
- **Statewide context (from the same live file, July 5, 2026):** 2,295 parks in the
  file; 483 marked Delinquent; 14 of those in Pasco County, Zephyr among them. Of
  Surujbali's ten personally-registered parks, one other (Pine Lake MHP, Lakeland,
  PRMZ001802) is also Delinquent.
- **Verification log:**
  - Downloaded and rows preserved: **July 2, 2026**
  - Re-pulled live and row confirmed unchanged (owner of record still CHANG, HYE SUK;
    fee status still Delinquent): **July 5, 2026**
- **Human-readable official lookup (no stable permalink exists):**
  DBPR Online Services "Verify a License" — <https://www.myfloridalicense.com/wl11.asp>
  → choose **Search by License Number** → enter **PRMZ001210** → the record
  "ZEPHYR MOBILE HOME PARK — Mobile Home Project" opens. The detail page's URL is
  session-generated (`LicenseDetail.asp?id=…` changes each visit), so cite the license
  number + the search path, or the CSV extract above, not a saved detail URL.
- Division contact: (850) 488-1122 · 2601 Blair Stone Rd., Tallahassee, FL 32399.

## 2. Pasco Property Appraiser parcel record (`PascoPA_parcel_23-26-21-0020-00500-0010_2026-07-02.md`)

- **Official lookup:** <https://search.pascopa.com> (Pasco County Property Appraiser)
  → search Parcel ID **23-26-21-0020-00500-0010**.
- Retrieved by Brandi Rodgers July 2, 2026. The June 2020 $2,000,000 warranty deed is
  independently reproducible at the Pasco Clerk's Official Records site
  (OR Book 10134 / Page 3753).

## Why the two sources together matter

The state registry (source 1) still names **Chang, Hye Suk** as Zephyr's park owner of
record with fees **delinquent**; the county deed records (source 2) show **Desmond
Surujbali personally** bought the park land in June 2020 for $2,000,000. Sweet Living,
Inc. — the corporation that sued as the park's "owner" — appears in neither.
