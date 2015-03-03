## Progress updates

Much of the early work will involve collecting and evaluating data, before the first line of code is written.  This log will record that progress, because it wouldn't be apparent otherwise.

### 2015-03-03
* Resuming work.  Should have a resolution for the issue from 2015-01-01

### 2015-01-01
* Function to download files.  ACS URL generation complete.  Issues encountered with download.file(); exploring RCurl

### 2014-12-28
* Updated table with reference file numbers
* Writing function to download files from the U.S. Census ftp server, based on user-defined state and survey info

To do:
* Work on program to download / unzip files
* Evaluate geography file for relevant fields
* Identify initial geographic summary regions of interest (city, congressional district, etc).

Functions (W = write, L = Locate):
* W: Download sequence files, based on sequence number, publication year, sample duration, and state(s)
* W: Convert data to one file per state, only columns needed for the project
* L/W: Recalculate margin of error, from 90% to 95% (for ACS)
* L/W: Statistical significance, confidence intervals
* L/W: Standard error (for DCensus)
* W: Relative position indicator

### 2014-12-26

Completed:
* Downloaded technical documentation for the American Community Survey (2006-2010)
* Downloaded geography files for all states (ACS)
* Created table with table numbers for educational attainment, poverty status, and mean income (from thesis)
 
To do:
* Identify file name for the relevant tables (ACS and DCensus). Download files for each state.
* Evaluate geography file for relevant fields (from SF3, Figure 2-5).
* Identify initial geographic summary regions of interest (city, congressional district, etc).
* Explore whether PUMS data is more appropriate than summary data (was not for TIF project, but may be here)

Functions (W = write, L = Locate):
* W: Convert data to one file per state, only columns needed for the project
* L/W: Recalculate margin of error, from 90% to 95% (for ACS)
* L/W: Statistical significance, confidence intervals
* L/W: Standard error (for DCensus)
* W: Relative position indicator

### 2014-11-28

Completed:
* Downloaded technical documentation for the Decennial Census (SF3)
* Downloaded standard design error factors for all states (Table C) - for calculating standard error
* Downloaded geography files for all states (DCensus)

To do:
* Identify tables for educational attainment, poverty status, population (P4), and income (from SF3, Ch. 3)
* Identify file name for the relevant tables (from SF3, Figure 2-2).  Download files for each state.
* Evaluate geography file for relevant fields (from SF3, Figure 2-5).
* Identify initial geographic summary regions of interest (city, congressional district, etc).
* Explore whether PUMS data is more appropriate than summary data (was not for TIF project, but may be here)
