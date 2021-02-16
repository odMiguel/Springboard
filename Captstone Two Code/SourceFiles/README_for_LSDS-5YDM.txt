1. Description
The Lynn Sage Data Base (LSDB) contains information about patients who came to the Lynn Sage Comprehensive Breast Center at Northwestern Memorial Hospital for care. The Northwestern Medicine Enterprise Data Warehouse (NMEDW) is a joint initiative across the Northwestern University Feinberg School of Medicine and Northwestern Memorial HealthCare, which maintains comprehensive data obtain from EHRs.  Using the LSDB and the NMEDW, we curated a dataset named as the Lynn Sage Data Set with 5-year distant metastasis (LSDS-5YDM), which includes records on 6726 breast cancer patients including clinical features and distant metastasis. The records span 03/02/1990 to 07/28/2015.   

2. Number of Cases: 6726

3. Number of Attributes: the class attribute(metastasis) + 23 

4. Attribute Information:
Variable	Description	Values
Class Attribute: metastasis   Whether patient metastasized within 5 years	yes, no
1.age		age at diagnosis of the disease		0-49, 50-64, > 64
2.menopause	inferred menopausal status		pre, post
3.size		size of tumor in mm			0-38, 38-50.5, > 50.5
4.node_positive	number of positive lymph nodes		0, 1-3,  > 3
5.node_removed	number of lymph nodes removed		0-2, 3-5 > 5
6.node_status	patient had any positive lymph nodes	neg,pos
7.grade		grade of disease			1, 2, 3
8.invasive	whether tumor is invasive		yes,no
9.stage		composite of size and # positive nodes	0,1,2,3
10.histology	tumor histology				lobular, duct
11.ER		estrogen receptor expression		neg, pos
12.PR		progesterone receptor expression	neg, pos
13.HER2		HER2 expression	neg, pos
14.TNEG		patient ER, PR, and HER2 negative	yes, no
15.P53		whether P53 is mutated	neg, pos
16.surgical_margins	Whether there is a residual tumor after surgery	res. tumor, no res. tumor,no primary site surgery
17.surgery	type of surgery				conservation, mastectomy
18.chemo	whether patient had chemotherapy	yes, no
19.breast_chest_radi	whether patient had breast or chest radiation	yes, no
20.nodal_radi	whether patient had lymph node  radiation 	yes, no
21.antihormone	whether patient had hormone therapy	yes, no
22.HER2_Inhib	whether patient had a HER2 inhibitor	yes, no
23.neo		Whether patient had neoadjuvant therapy	yes, no