# utl_System_RASPFS_Reliability_Availability_Serviciability_Performance_Functionality_Security
System RASPFS Reliability Availability Serviciability Performance Functionality Security.  Keywords: sas sql join merge big data analytics macros oracle teradata mysql sas communities stackoverflow statistics artificial inteligence AI Python R Java Javascript WPS Matlab SPSS Scala Perl C C# Excel MS Access JSON graphics maps NLP natural language processing machine learning igraph DOSUBL DOW loop stackoverflow SAS community.

    System RASPFS Reliability Availability Serviciability Performance Functionality Security

    github
    https://tinyurl.com/y7eh56nb
    https://github.com/rogerjdeangelis/utl_System_RASPFS_Reliability_Availability_Serviciability_Performance_Functionality_Security

    How to detemine if a SAS local power workstation would benefit you
    as a SAS programmer with/without an EG server.

    The first question to ask is how often do you need to access a database schema where one
    or more tables are over 1TB. I define big data as computing problems where most
    of a users programming involves tables over 1TB. The other place for larger servers is
    "big computation" for instancemassive simulations or parallelism over 64 concurrent jobs.
    Workstations are available with 64 cores.

    Should I use just the server or a sever plus workstation(or power laptop) for my SAS programming.
    Systems like Tableau, Oracle, Teradata, Midas and the IDR do not run well on a workstation.

    This is how IBM used to measure overall mainframe usability.

      1. Reliability      - Do you get the answer you expect.
      2. Availability.
      3. Serviciability
      4. Performance
      5. Functionality
      6. Security

    I use either excel or SAS running on both platforms for comparisons.

      1. Reliability.
          There was a bug in SAS 9.3 where 'proc distinct' gave the wrong answer for very high
          carinality.
             Workstation: I downloaded the fix from SAS and installed it on my workstation in 30 minutes
             Server:      Reported it a couple of months ago and it is still not fixed

      2. Availability.
          Workstation: 99.9%
          Server:      75% (Mostly due to the fact that you need an internet connection and scheduled
          and non scheduled availability

      3. Serviceability:
          Workstation: I added a second esata III SSD to my laptop in 2 minutes
          Server: Generally mot possible

      4. Performance
          Workstation: Much more ram,RAID 0 SSD drives and 100% of the XEONs. Very fast response time
                       not like a server dial-up connection
          Server: Little Ram, SAN spinning raid 5 drives

      5. Functionality
          Workstation: You have an operating system, R, Python, Ghostscript, Perl, C, Java...
                       ODBC(excel access...), more disk space(Try getting 5TB ob the server)...
          Server:      Generally locked down most of the above not available.

      6.  Security
            Workstation: Only have a subset of data. Local and disk encryption.
            Server: Has the jewels so obviously a better targer for hackers.
            The ultimate security is to separate the workstation from the internet and
            set up a very secure transfer protocol to communicate with the 'insecure' server.




