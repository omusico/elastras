Elastras is a research project to design an Elastic Transactional Data Store for a Cloud Computing environment.

Refer to the following papers for a high level overview.

Sudipto Das, Divyakant Agrawal, Amr El Abbadi, **["ElasTraS: An Elastic Transactional Data Store in the Cloud"](http://www.usenix.org/events/hotcloud09/tech/full_papers/das.pdf)**, In USENIX Workshop on Hot Topics in Cloud Computing (HotCloud '09), in conjunction with USENIX Annual Technical Conference '09.

And to the following paper for a detailed system design.

Sudipto Das, Shashank Agarwal, Divyakant Agrawal, Amr El Abbadi, **["ElasTraS: An Elastic, Scalable, and Self Managing Transactional Database for the Cloud"](http://www.cs.ucsb.edu/~sudipto/tech_reports/2010-04.html)**, In UCSB Computer Science Technical Report (CS-2010-04), March 2010.

Live Database migration is an important operation to ensure that elastic scaling has minimal service interruption and impact on performance. ElasTraS uses a custom live database technique, Albatross, that is cognizant of the internals of the database to allow efficient and lightweight migration. The following paper provides the details of Albatross and its implementation in ElasTraS.

Sudipto Das, Shoji Nishimura, Divyakant Agrawal, Amr El Abbadi, **["Albatross: Lightweight Elasticity in Shared Storage Databases for the Cloud using Live Data Migration"](http://www.cs.ucsb.edu/~sudipto/papers/albatross.pdf)**, in Proc. of VLDB Endow., Vol 4, No. 8, 2011.

Coming Soon....