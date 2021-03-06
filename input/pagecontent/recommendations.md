\< provides a list of synthetic and clear information and
recommendations\>

1.  **FAIRness** is a **goal** not a status, therefore a **continuous
    improvement incremental approach** should be followed.
    
    1.  Do not pretend to implement everything from the beginning.
        
        1.  in terms of principles to be realized
        
        2.  in terms of maturity level
        
        3.  in terms of coverage across communities. For example, a
            solution applicable within a well-defined community may not
            be fit for purpose for a wider target (e.g. global search)
    
    2.  You need to be able to know where you are ("as is" assessment)
        and what you want to achieve.
    
    3.  Measurements, such as RDA indicators, are essential for
        evaluating achieved improvements.
    
    4.  \<…\>

2.  The **HL7 FHIR** standard is a widely recognized and used standard
    in the health space providing **value** in
    the **implementation** of **FAIR health data and services**
    
    1.  Even if HL7 FHIR can provide support to data FAIRification,
        implementing HL7 FHIR is not a sufficient requirement for being
        FAIR. This guides provides suggestions on how to use FHIR to
        improve FAIRness.
    
    2.  The HL7 FHIR standard provides its highest value in
        realizing **Interoperability** and Reusability principles.
        Hybrid solutions, i.e by using combined FHIR and non-FHIR
        technologies, can be used to realize the other FAIR principles.
    
    3.  This would not exclude the possibility to realize also
        Findability and Accessibility principles by using FHIR. However,
        a cost benefit evaluation, considering the level of adoption by
        that community, should be accomplished.

3.  As with the FAIR principles in general, the FHIR implementation of
    the FAIR principles should follow an **incremental approach.**
    
    1.  in this sense, depending on the usage context, including the
        standards adopted by the community, the cost-effectiveness
        evaluation and the community goals, an architectural migration
        path with a consistent set of intermediate objectives should be
        defined. Objectives might be related to:
        
        1.  a set of RDA indicators to be realized. *\<add example\>*
        
        2.  their realization maturity levels. *\<add example\>*
        
        3.  the HL7 FHIR implementation. *\<add example\>*

4.  FAIR / FHIR by design (future shape of success): hard to make data
    FAIR when data are poor (even if potentially findable and
    accessible...) or not designed for that.
    
    1.  converting data in FHIR may be complex or not sufficient if data
        have not been designed from the beginning for that purpose
    
    2.  the specification/adoption of FHIR profiles against which to
        assess the data content may help on this;
    
    3.  the availability of natively conformant FHIR data is an added
        value.

### Findability

Findability covers a wide range of different expectations and users: not
of all of them need to be realized by using HL7 FHIR based technologies.
For example, a human being makes a web search to find generically
available data about COVID; a researcher knows that the XYZ repository
makes available Traumatic Brain Injury Research data and consults that
site to search data set with specific characteristics.  
Consider a **multi-layered** and **hybrid approach**: that is,
combination of FHIR and non-FHIR based technologies, enabling computable
and human findability. For example, \<….\>  
If a search mechanism is adopted and accepted solution this will be
used, even if not FHIR (for example Google style web search)  
Describe how to handle the search when data are no longer available.  
Cases where you cannot get data (e.g. for privacy reason) proprietary
patient data (but a summary or a description of the data can be
available). Machine can work  
FAIR is 90% metadata  
Depending on the access rights FHIR server can return only partial
information

### Accessibility

\<…\>

### Interoperability

For subject level data objects reuse where applicable existing FHIR
implementation guides

### Reusability

FAIR Implementation Profile enable to compare the way a community
implement FAIR (evaluate if  
One of the community standards mentioned could be FHIR

A clear license and consent is important for reusability    
\<…\>
