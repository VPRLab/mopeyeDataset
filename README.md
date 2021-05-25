# MopEyeDataset
**MopEye: Opportunistic Monitoring of Per-app Mobile Network Performance**
* Homepage: https://mopeye.github.io/
* App link: https://play.google.com/store/apps/details?id=com.mopeye (will re-upload soon)
* Paper link: https://www.usenix.org/conference/atc17/technical-sessions/presentation/wu

MopEye was published in USENIX ATC'17, and the following is the bib information:
```
@INPROCEEDINGS{MopEye17,
  AUTHOR =       {Daoyuan Wu and Rocky K. C. Chang and Weichao Li and Eric K. T. Cheng and Debin Gao},
  TITLE =        {{MopEye}: Opportunistic Monitoring of Per-app Mobile Network Performance},
  BOOKTITLE =    {Proc. USENIX Annual Technical Conference (ATC)},
  PAGES =        {445--457},
  YEAR =         {2017},
}
```
**We are periodically releasing the datasets of MopEye for benefiting networking research.**

## Access Policy
We **request** that applicants:
* Do not redistribute the dataset without our consent;
* Do not make a commercial usage of the dataset;
* Get a faculty, or someone in a permanent position, to agree and commit to the policy.

To access the following database files, please send an application email (with the corresponding email subject) to **dywu(at)ie.cuhk.edu.hk** stating the name of your research institution and the name of the person requesting access. Make sure to send your application from your university (or research institution) email account.

## 170103MopEyeDataset
* Peroid: From 16 May 2016 to 3 January 2017 approximately;
* Five million measurements from 6,266 Android apps on 2,351 smartphones;
* Used in our ATC'17 paper: https://daoyuan14.github.io/papers/ATC17_MopEye.pdf;
* DB file: https://www.dropbox.com/s/4d5mw9yqle6ka29/170103MopEyeDataset.db?dl=0;
* Email subject: "Requesting the 170103 MopEye dataset from XXX", where XXX is the abbreviation of your institution.

## 180708MopEyeDataset
* Peroid: From 16 May 2016 to 8 July 2018 approximately;
* 20 million RTT measurements from 12.5K users in 653 ISPs and 173 countries;
* Used in our IWQoS'19 paper: https://daoyuan14.github.io/papers/IWQoS19_MopEyeDatasetAnalysis.pdf;
* DB file: will be generated upon the first applicant;
* Email subject: "Requesting the 180708 MopEye dataset from XXX", where XXX is the abbreviation of your institution.

## How to Use the DB
* You can access the dataset db file using the SQLite Browser.
* Then make SQL query according to your need.

## The Database Structure
For the meaning of database structure, please refer to **Table 1** in https://daoyuan14.github.io/papers/IWQoS19_MopEyeDatasetAnalysis.pdf

![MopEyeDBTables.png](https://raw.githubusercontent.com/daoyuan14/mopeyeDataset/master/MopEyeDBTables.png)
