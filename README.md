# dbms_partition_wrangler
This project offers fully automated range partitioning for Oracle Database that follows best practices for handling data.

Mission Statement: To help custodians of data that concerns the general public to better manage that data.

Goals:
* Facilitate the uptake of best practices for handling bulk data in an Oracle Database.
* Facilitate the purging of that data when it is no longer of relevance and there is no justification for its retention by the data controller.
* Faciliate the reduction of online storage, archive storage, backup storage, compute, and electricity consumption that is incurred by hosting the data set.
* Facilitate performance improvements for the online processing of large data sets by reducing the size of the working set.
* Encourage the use of security controls such as encrpytion and auditing to protect data.

Intended Audience:
* Data processors and data controllers in retail, healthcare, telecommunications, utilities, transportation, hospitality, hotels, and financial services, among others, that more often than not store bulk personal data in an Oracle Database.

Why:
* Because there is no consistency in how data controllers and data processors handle bulk data. It is difficult to follow best practices and this project provides an easy way to adopt them.
* Entities may be out of compliance with data privacy legislation such as GDPR. Mass data leaks are occurring regularly and they often concern data that should not have have been retained once it is no longer of use.
* To reduce the energy footprint of storing and processing bulk data by avoiding unnecessary and excessive resource consumption. Data centers are large energy consumers and in many countries they are powered by fossil fuels.
* In 2018 it was claimed by one commentator that only 1% of the databases in the world are encrpyted.
* Why a wrangler? Because partitions need to be managed with care. Handling must be orchestrated by policy and fully automated to prevent human error.
* Why FOSS? This project is intended as a benefit to a society and so the code can be subject to scrutiny, testing, contributions, and adoption by the community.
