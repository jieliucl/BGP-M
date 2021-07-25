This folder contains 6 documents:
1. IPv4_1318_BGP-M_Cases.txt
2. IPv6_356_BGP-M_Cases.txt
3. AS6939_IPv4_12642_BGP-M_Cases.txt
4. AS6939_IPv4_Revisit.txt
5. AS6939_IPv6_Revisit.txt
6. README.txt

The first 5 documents list the BGP-M cases studied in this project from various aspects.
1. IPv4_1318_BGP-M_Cases.txt
	The document of IPv4_1318_BGP-M_Cases.txt lists the 1318 BGP-M cases deployed by 11 ASes on IPv4 Internet, inlcuding the 1,088 cases BGP-M deployed by Hurricane Electric (HE, AS6939).
	Each line is in the format of <NearAS, NearBR, FarAS, DstPrfx>|(FarIPs in IXP),(FarIPs not in IXP)
	For some cases the FarIPs not in IXP is empty, suggesting they are deployed via IXPs;
	For some cases the FarIPs in IXP is empty, suggesting they are deployed via direct links;
	For the other cases, both FarIPs in IXP and FarIPs not in IXP are not empty, suggesting they are deployed via hybrid links.

2. IPv4_356_BGP-M_Cases.txt
	The document of IPv4_356_BGP-M_Cases.txt lists the 356 BGP-M cases deployed by 6 ASes on IPv6 Internet, inlcuding the 300 BGP-M cases deployed by Hurricane Electric (HE, AS6939).
	Each line is in the format of <NearAS, NearBR, FarAS, DstPrfx>|(FarIPs in IXP),(FarIPs not in IXP)
	For some cases the FarIPs not in IXP is empty, suggesting they are deployed via IXPs;
	For some cases the FarIPs in IXP is empty, suggesting they are deployed via direct links;
	For the other cases, both FarIPs in IXP and FarIPs not in IXP are not empty, suggesting they are deployed via hybrid links.

3. AS6939_IPv4_12642_BGP-M_Cases.txt
	The document of AS6939_IPv4_12642_BGP-M_Cases.txt lists the 12,642 BGP-M cased deployed by AS6939, with queries to all the /24 prefixes in neighbour ASes.
	Each line is in the format of <NearAS, NearBR, FarAS, DstPrfx>|(FarIPs)
	The BGP-M cases in this document are not specifically studied in regarding IXPs.

4. AS6939_IPv4_Revisit.txt
	The document of AS6939_IPv4_Revisit.txt lists the 692 BGP-M cases that are deployed by AS6939 on IPv4 and still exist in July 2021.
	Each line is in the format of <NearAS, NearBR, FarAS, DstPrfx>|(FarIPs)
	The BGP-M cases in this document are not specifically studied in regarding IXPs.

5. AS6939_IPv6_Revisit.txt
	The document of AS6939_IPv6_Revisit.txt lists the 218 BGP-M cases that are deployed by AS6939 on IPv6 and still exist in July 2021.
	Each line is in the format of <NearAS, NearBR, FarAS, DstPrfx>|(FarIPs)
	The BGP-M cases in this document are not specifically studied in regarding IXPs.

6. README.txt
	The document of README.txt describes the documents contained in this folder.