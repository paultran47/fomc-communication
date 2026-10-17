# beamer-template

[MIT licensed](https://github.com/paultran47/fomc-communication/blob/main/LICENCE.md).

<details>
  <summary>Table of contents</summary>
  <ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#current-communication-collected">Current Communication Collected</a></li>
  </ul>
</details>

---

## Overview

Single collection point for all text communication from members of the Federal Open Market Committee
(FOMC) or Federal Reserve System.

## Structure

Communication documents collected by me will be organised as follows: the "raw" communication document
will always be saved either an HTML or PDF file in the sub-directory "raw", which in turn has several
sub-sub-directories named by year. The raw document will have the naming format of "ddmmyyyy".

Cleaned communication documents are stripped of everything besides the communication text itself,
converted to UTF-8 encoding, and saved as a text file. Similar to their raw counterparts, cleaned
communication are saved in the sub-directory "clean", into the correct sub-sub-directory named by year,
and finally the communication document itself is named as "ddmmyyyy_clean".

All communication documents are then put into a single "master" csv file, which contains the date of
the communication, the time of release (in Central Chicago time), and the text themselves.

For all communication documents not collected by me and instead given to me (thank you Amy and Alex!!),
they are kept as their original file format (e.g., csv) in the appropriate directories for the time being.
Eventually, I will have a truly single "master" csv file that will organise and house all central bank
communication.

<p align="right">
  (<a href="#fomc-communication">back to top.</a>)
</p>

---

## Current Communication Collected

* FOMC official statements from May 1999 through Dec 2021 (scheduled and unscheduled).

* FOMC alternative statements cleaned and provided from Amy Handlan from Feb 2005 through Dec 2017.

* Fed Chair and Vice-Chair policy-relevant speeches from Feb 1996 through Nov 2019 (not public yet).

<p align="right">
  (<a href="#fomc-communication">back to top.</a>)
</p>

---
