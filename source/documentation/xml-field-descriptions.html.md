
<p class="auto-cursor-target"><br /></p>
<table class="wrapped relative-table"><colgroup><col style="width: 256.0px;" /><col style="width: 307.0px;" /><col style="width: 601.0px;" /></colgroup>
<tbody>
<tr>
<th>Field Name</th>
<th>Field ID</th>
<th>Description</th></tr>
<tr>
<td colspan="1">Message Sender</td>
<td colspan="1">MesSenMES3</td>
<td colspan="1">
<p>The&nbsp;<span class="il">message</span>&nbsp;<span class="il">sender</span>&nbsp;field is made up of the&nbsp;<span class="il">sender</span>&nbsp;EORI and branch. The branch is a 10 digit&nbsp;number.</p>
<p><span style="color: rgb(0,0,0);">An EORI is made up </span><span style="color: rgb(34,34,34);">a country code, to show where the organisation or individual is registered, and a unique code or&nbsp;</span>number<span style="color: rgb(34,34,34);">. <br /><br />For&nbsp;</span>UK<span style="color: rgb(34,34,34);">&nbsp;businesses the&nbsp;</span>number<span style="color: rgb(34,34,34);">&nbsp;is made up as follows (with a few minor exceptions): </span></p>
<ul>
<li><span style="color: rgb(34,34,34);">VAT registered businesses: GB + VRN (VAT&nbsp;</span>registration number<span style="color: rgb(34,34,34);">) + 000</span></li>
<li><span style="color: rgb(34,34,34);">Non-VAT registered businesses: GB + unique&nbsp;</span>number<span style="color: rgb(34,34,34);">&nbsp;issued by HMRC</span></li></ul></td></tr>
<tr>
<td>Reference Number</td>
<td>
<p>RefNumHEA4</p></td>
<td>
<p><span style="color: red;"><span style="color: rgb(0,0,0);">Local Reference number - </span></span><span style="color: rgb(0,0,0);">his field needs to be unique for each 'Person Lodging' and is validated using the 'Person Lodging' EORI for declarations which have been submitted </span></p></td></tr>
<tr>
<td>Transport Mode at Border</td>
<td>TraModAtBorHEA76</td>
<td>
<p>Transport Mode at border is a required field which must be one of the following values entered with no leading zeros:</p>
<ul>
<li>1 - Maritime</li>
<li>2 - Rail</li>
<li>3 - Road</li>
<li>4 - Air (including fly trucks)</li>
<li>8 - Inland water transport</li>
<li>10 - (NEW)&nbsp; RoRo &ndash; accompanied</li>
<li>11 - (NEW) RoRo &ndash; unaccompanied</li></ul></td></tr>
<tr>
<td>Identity of Means of Transport Crossing Border</td>
<td>IdeOfMeaOfTraCroHEA85</td>
<td><span>This field where appropriate contains the identity of the means of transport or, if containerised, the equipment identification number.</span></td></tr>
<tr>
<td>Nationality of Means of Transport Crossing Border</td>
<td>NatOfMeaOfTraCroHEA87</td>
<td>
<p>Nationality <span>of Means of Transport Crossing Border is to enter a </span>'Country Code' if transport mode at border is one of the following:</p>
<ul>
<li><span>3 - Road</span></li>
<li><span>10 - (NEW)&nbsp; RoRo &ndash; accompanied</span></li>
<li><span>11 - (NEW) RoRo &ndash; unaccompanied</span></li></ul></td></tr>
<tr>
<td>Total Number of Items</td>
<td>TotNumOfIteHEA305</td>
<td>
<p>This field is to enter the total number of items. It must equal the total number of goods items provided and must not have leading zeros.</p></td></tr>
<tr>
<td>Total Number of Packages</td>
<td>TotNumOfPacHEA306</td>
<td>
<p><span>Total Number of Packages is required when information on packages has been provided:</span></p>
<ul>
<li>this number must equal the sum of all 'Number of packages' +'Number of pieces' provided at goods item level + 1 for any declared as bulk</li>
<li>this number must not have leading zeros</li></ul></td></tr>
<tr>
<td>Total Gross Mass</td>
<td>TotGroMasHEA307</td>
<td>
<p>Total Gross Weight (mass) of goods including packaging. Excludes any specialist equipment the carrier may use.</p></td></tr>
<tr>
<td>Declaration Place</td>
<td>DecPlaHEA394</td>
<td>
<p>This is a free text field used to enter where the declaration was submitted. This should be specific for example EU 'Country Name' rather than just entering 'EU'.</p></td></tr>
<tr>
<td>Specific Circumstance Indicator</td>
<td>SpeCirIndHEA1</td>
<td>
<p><span>Specific </span>Circumstances Indicators field which will allow the following:</p>
<ul>
<li>the 'Specific circumstance indicator' with value 'E' (AEO) can be used only if the 'Person Lodging the ENS and all 'Consignees' declared in the ENS have a valid AEO certificate of type 'AEOF' or 'AEOS'</li>
<li>if the submission is an amendment submitted by a Representative, then the Representative is also required to have a valid AEO certificate of type 'AEOF' or 'AEOS'</li>
<li>declarant EORI must be GB and will always be provided. Consignee EORI will only be validated if GB</li>
<li>specific circumstances indicator can only take the values 'C', 'D' or 'E'</li></ul></td></tr>
<tr>
<td>Transport Charges Method of Payment</td>
<td>TraChaMetOfPayHEA1</td>
<td>
<p><span>This information is to be provided where available. </span>The following codes can be used:</p>
<ul>
<li>A - Payment in cash</li>
<li>B - Payment by credit card</li>
<li>C - Payment by cheque</li>
<li>D -Other (e.g. direct debit to cash account)</li>
<li>H - Electronic credit transfer</li>
<li>Y - Account holder with carrier</li>
<li>Z - Not pre-paid</li></ul></td></tr>
<tr>
<td>Commercial Reference Number</td>
<td>ComRefNumHEA</td>
<td>
<p>Commercial Reference Number needs to follow the WCO (<span style="">World Customs Organization) </span>recommended format:</p>
<ul>
<li><span>year (2 digits), EORI, another commercial ref (for example Invoice number or waybill number)</span></li>
<li><span><span>this is issued by industry in order to identify specific goods (a particular consignment) within a load of multiple consignments, and can be used by Border Force for identification of consignments </span><br /></span></li></ul>
<p>Note: this is not a required field but if entered the user will not need to provide <span>transport document numbers.</span></p></td></tr>
<tr>
<td>Conveyance Reference Number</td>
<td>ConRefNumHEA</td>
<td>
<p>'Conveyance Reference Number' is the identification of the journey of the means of transport (for example flight number, train number, voyage number, trip number):</p>
<ul>
<li>if 'Transport mode at border' = '4&rsquo; (Air) then format is Alpha-numeric 8, and must contain the carrier code (AN3), the flight number (N4) and an optional suffix (a1) without any separator between the two or three elements<br /><br /></li>
<li>if 'Transport mode at border' = '1' (Maritime) and the Conveyance reference number is used, and the first four digits consist of XFER in uppercase, then it must be followed by the lorry registration plate number, without any separator between&nbsp;&lsquo;XFER&rsquo; and the lorry plate. Otherwise XFER cannot be used in the first four digits of the Conveyance reference number</li></ul></td></tr>
<tr>
<td>Place of Loading</td>
<td>PlaLoaGOOITE334</td>
<td>
<p>Place of Loading is used for the identification of the seaport, airport, freight terminal, rail station or other place at which the goods are loaded onto the means of transport being used for their carriage, including the country where it is located.</p>
<ul>
<li>where available, coded information should be provided for the identification of the location: first 2 digits country code, followed by port code, but format validation limited to Alpha Numeric 35</li>
<li>this must be provided at either Header or Item level. If provided at Header level, it cannot be provided at item level. If provided at item level, it must be provided for every item.&nbsp;</li></ul></td></tr>
<tr>
<td>Place of Unloading</td>
<td>PlaUnlGOOITE334</td>
<td>
<p>Place of Unloading must be provided when the message is encoded in EDIFACT and the corresponding free text field is not in the UNOC character set:</p>
<ul>
<li>if provided it must contain the language code (of the language used) in the corresponding free text field<br /><br /></li></ul></td></tr>
<tr>
<td>Declaration Date and Time</td>
<td>DecDatTimHEA114</td>
<td>
<p>This is for the Date and time of the declaration submitted by the trader system and must by GMT (<span style="">Greenwich Mean Time).</span></p></td></tr>
<tr>
<td>---Consignor (Trader)</td>
<td>TRACONCO1</td>
<td>
<p>This section relates to the 'Consignor' which means:</p>
<ul>
<li>the party who is making the declaration</li></ul>
<p>or</p>
<ul>
<li>the party on whose behalf you are making the declaration</li></ul>
<p>The consignor is the owner of the goods or has similar right of disposal over them at the time the declaration is made.</p></td></tr>
<tr>
<td>Name</td>
<td>NamCO17</td>
<td>Consignor Name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrAndNumCO122</td>
<td>Consignor Street and Number</td></tr>
<tr>
<td>Postal Code</td>
<td>PosCodCO123</td>
<td>Consignor Postal Code</td></tr>
<tr>
<td>City</td>
<td>CitCO124</td>
<td>Consignor City</td></tr>
<tr>
<td>Country Code</td>
<td>CouCO125</td>
<td>
<p>Consignor Country Code</p></td></tr>
<tr>
<td>TIN</td>
<td>TINCO159</td>
<td>Consignor EORI</td></tr>
<tr>
<td>---Consignee (Trader)</td>
<td>TRACONCE1</td>
<td>
<p>This field relates to the 'Consignee' which means:</p>
<ul>
<li>the party to whom goods are actually consigned</li></ul></td></tr>
<tr>
<td>Name</td>
<td>NamCE17</td>
<td>Consignee Name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrAndNumCE122</td>
<td><span>Consignee Street and Number</span></td></tr>
<tr>
<td>Postal Code</td>
<td>PosCodCE123</td>
<td>Consignee Postal Code</td></tr>
<tr>
<td>City</td>
<td>CitCE124</td>
<td>Consignee City</td></tr>
<tr>
<td>Country Code</td>
<td>CouCE125</td>
<td>
<p>Consignee Country Code</p></td></tr>
<tr>
<td>TIN</td>
<td>TINCE159</td>
<td>
<p>Consignee EORI</p>
<ul>
<li><span style="color: rgb(0,0,0);">If the consignee has a GB EORI, this information is optional. If the consignee has an EU EORI, this information is mandatory</span></li></ul></td></tr>
<tr>
<td>---Notify Party</td>
<td>NOTPAR670</td>
<td>
<p>This section relates to the 'Notify Party' that is the party who needs to be notified of the arrival of the goods. This information needs to be provided if applicable.</p></td></tr>
<tr>
<td>Name</td>
<td>NamNOTPAR672</td>
<td>Notify Party name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrNumNOTPAR673</td>
<td>Notify Party Street and Number</td></tr>
<tr>
<td>Postal Code</td>
<td>PosCodNOTPAR676</td>
<td>Notify Party Postal Code</td></tr>
<tr>
<td>City</td>
<td>CitNOTPAR674</td>
<td>Notify Party City</td></tr>
<tr>
<td>Country Code</td>
<td>CouCodNOTPAR675</td>
<td>
<p>Notify Party Country Code</p></td></tr>
<tr>
<td>TIN</td>
<td>TINNOTPAR671</td>
<td>Notify Party EORI</td></tr>
<tr>
<td>---Goods Item</td>
<td>GOOITEGDS</td>
<td>This section is for the good items which are being sent</td></tr>
<tr>
<td>Item Number</td>
<td>IteNumGDS7</td>
<td>
<p><span>This holds the number of items being sent within the declaration:</span></p>
<ul>
<li>items will be numbered sequentially from '1' for the first item and incrementing the numbering by '1' for each following item</li>
<li>example
<ul>
<li><span>600 phones = 1 item </span></li>
<li><span>300 phones + 100 phone cases = 2 items</span>
<ul>
<li><span>300 phone = No 1</span></li>
<li><span>100 phones = No 2</span></li></ul></li></ul></li></ul></td></tr>
<tr>
<td>Goods Description</td>
<td>GooDesGDS23</td>
<td>
<p>This is a free text field to enter a description of the goods which are being sent. This is only used at goods item level, and only format validation, that is no prohibited descriptions.</p></td></tr>
<tr>
<td>Gross Mass</td>
<td>GroMasGDS46</td>
<td>
<p>Total Gross Weight (mass) of goods including packaging. This excludes any specialist equipment the carrier may use.</p></td></tr>
<tr>
<td>Transport Charges / Method of Payment</td>
<td>MetOfPayGDI12</td>
<td>
<p>Transport charges method of payment code - this information is only to br provider where available</p>
<p>The following codes can be used:</p>
<ul>
<li>A - Payment in cash</li>
<li>B - Payment by credit card</li>
<li>C - Payment by cheque</li>
<li>D -Other (e.g. direct debit to cash account)</li>
<li>H - Electronic credit transfer</li>
<li>Y - Account holder with carrier</li>
<li>Z - Not pre-paid</li></ul></td></tr>
<tr>
<td>Commercial Reference Number</td>
<td>ComRefNumGIM1</td>
<td>
<p>Commercial Reference Number needs to follow the WCO recommended format:</p>
<ul>
<li>year (2 digits), EORI no., another commercial ref (Invoice no.) / waybill no<br /><br /></li>
<li>this is issued by industry in order to identify specific goods (a particular consignment) within a load of multiple consignments, and can be used by BF for identification of consignments</li></ul>
<p>Note: This is not a required field but if entered the user will not need to provide transport document numbers.</p></td></tr>
<tr>
<td>UN Dangerous Goods Code</td>
<td>UNDanGooCodGDI1</td>
<td>This code is a unique serial number assigned by the UN. It must be provided where relevant.&nbsp;</td></tr>
<tr>
<td>Place of Loading</td>
<td>PlaLoaGOOITE333</td>
<td>
<p>Place of Loading is used to for the identification of the seaport, airport, freight terminal, rail station or other place at which the goods are loaded onto the means of transport being used for their carriage, including the country where it is located:</p>
<ul>
<li>where available, coded information should be provided for the identification of the location, that is the first 2 digits country code, followed by port code, but format validation limited to Alpha Numeric 35</li>
<li>this must be provided at either Header or Item level. If provided at Header level, it cannot be provided at item level. If provided at item level, it must be provided for every item</li></ul></td></tr>
<tr>
<td>Place of Unloading</td>
<td>PlaUnlGOOITE333</td>
<td>
<p>Place of Unloading must be provided when the message is encoded in EDIFACT and the corresponding free text field is not in the UNOC character set:</p>
<ul>
<li>if provided it must contain the language code (of the language used) in the corresponding free text field</li></ul></td></tr>
<tr>
<td>------Produced Documents / Certificates</td>
<td>PRODOCDC2</td>
<td>This section is to complete document reference numbers and is not required if a '<span>Commercial Reference Number' has been provided</span></td></tr>
<tr>
<td>Document Type</td>
<td>DocTypDC21</td>
<td>Specifies the document type</td></tr>
<tr>
<td>Document Reference</td>
<td>DocRefDC23</td>
<td>
<p>This is to provide the reference for the transport document that covers the transport of the goods into the UK</p>
<ul>
<li>where the person lodging the declaration is different from the carrier the transport document number of the carrier should also be provided if available</li></ul></td></tr>
<tr>
<td>------Special Mentions</td>
<td>SPEMENMT2</td>
<td>This is for additional information which is coded</td></tr>
<tr>
<td>Additional Information Coded</td>
<td>AddInfCodMT23</td>
<td>Enter Codes for Special Mentions 'Additional Information/Special Indication Code' to be sent across the Common Domain</td></tr>
<tr>
<td>------Consignor (Trader)</td>
<td>TRACONCO2</td>
<td>
<p>This section relates to the 'Consignor' which means:</p>
<ul>
<li>the party who is making the declaration</li></ul>
<p>or</p>
<ul>
<li>the party on whose behalf you are making the declaration</li></ul>
<p>This consignor is the owner of the goods or has similar right of disposal over them at the time the declaration is made</p></td></tr>
<tr>
<td>Name</td>
<td>NamCO27</td>
<td>Consignor Name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrAndNumCO222</td>
<td>Consignor Street and Number</td></tr>
<tr>
<td>Postal Code</td>
<td>PosCodCO223</td>
<td>Consignor Postal Code</td></tr>
<tr>
<td>City</td>
<td>CitCO224</td>
<td>Consignor City</td></tr>
<tr>
<td>Country Code</td>
<td>CouCO225</td>
<td>
<p>Consignor Country Code</p></td></tr>
<tr>
<td>TIN</td>
<td>TINCO259</td>
<td>Consigner EORI</td></tr>
<tr>
<td>------Code (Commodity)</td>
<td>COMCODGODITM</td>
<td>
<p>This section is to provide the Commodity Code</p>
<p><a href="https://www.trade-tariff.service.gov.uk/sections">https://www.trade-tariff.service.gov.uk/sections</a></p></td></tr>
<tr>
<td>Combined Nomenclature</td>
<td>ComNomCMD1</td>
<td>
<p>This field is to enter the commodity code</p>
<ul>
<li>For ENS, the first 4 digits may be used</li></ul></td></tr>
<tr>
<td>------Consignee (Trader)</td>
<td>TRACONCE2</td>
<td>
<p>This section relates to the 'Consignee' which means:</p>
<ul>
<li>The party to whom goods are actually consigned</li></ul></td></tr>
<tr>
<td>Name</td>
<td>NamCE27</td>
<td>Consignee Name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrAndNumCE222</td>
<td><span>Consignee Street and Number</span></td></tr>
<tr>
<td>Postal Code</td>
<td>PosCodCE223</td>
<td><span>Consignee Postal Code</span></td></tr>
<tr>
<td>City</td>
<td>CitCE224</td>
<td><span>Consignee City</span></td></tr>
<tr>
<td>Country Code</td>
<td>CouCE225</td>
<td>
<p><span>Consignee Country Code</span></p></td></tr>
<tr>
<td>TIN</td>
<td>TINCE259</td>
<td>Consignee EORI</td></tr>
<tr>
<td>------Containers</td>
<td>CONNR2</td>
<td>This section is for Container Information</td></tr>
<tr>
<td>Container Number</td>
<td>ConNumNR21</td>
<td>This field is to enter the container number</td></tr>
<tr>
<td>------Means of Transport at Border (Identity)</td>
<td>IDEMEATRAGI970Type</td>
<td><span>This section relates to Means of Transport at Border</span></td></tr>
<tr>
<td>Nationality</td>
<td>NatIDEMEATRAGI973</td>
<td>
<p>This field is to enter 'Nationality' of Means of Transport Crossing Border using a 'Country Code' if transport mode at border is one of the following:</p>
<ul>
<li>3 - Road</li>
<li>10 - (NEW)&nbsp; RoRo &ndash; accompanied</li>
<li>11 - (NEW) RoRo &ndash; unaccompanied</li></ul>
<p>This is not required if 'Identity of means of transport' is provided at the Header level.</p></td></tr>
<tr>
<td>Identity of Means of Transport Crossing Border</td>
<td>IdeMeaTraGIMEATRA971</td>
<td><span>This field where appropriate contains the identity of the means of transport or, if containerised, the equipment identification number</span></td></tr>
<tr>
<td>------Packages</td>
<td>PACGS2</td>
<td>This section relates to the packages in the declaration</td></tr>
<tr>
<td>Kind of Packages</td>
<td>KinOfPacGS23</td>
<td>Type of package to be specified from a list of package types</td></tr>
<tr>
<td>Number of Packages</td>
<td>NumOfPacGS24</td>
<td>
<p>This field holds the number of packages - based on number of packages which are packaged in such a way that they cannot be divided without undoing the package.</p>
<p>This is a required field if 'kind of packages' indicates anything other than 'unpacked' or 'bulk'.</p>
<p><br /></p></td></tr>
<tr>
<td>Number of Pieces</td>
<td>NumOfPieGS25</td>
<td>
<p>This field holds the number of pieces if the goods are 'unpackaged'</p>
<ul>
<li>if 'type of package' indicates bulk, number of pieces is not required</li>
<li>this field must not contain leading zeros</li></ul></td></tr>
<tr>
<td>Marks &amp; Numbers of Packages (Long)</td>
<td>MarNumOfPacGSL21</td>
<td>
<p>This field is used to enter any 'Shipping Marks'</p>
<ul>
<li>optional if 'Kind of packages' indicates 'bulk' or 'Unpacked', or if the 'specific circumstance indicator' has been used</li></ul></td></tr>
<tr>
<td>------Notify Party</td>
<td>PRTNOT640</td>
<td>
<p>This section relates to the 'Notify Party' which means:</p>
<ul>
<li>The party who needs to be notified of the arrival of the goods</li></ul>
<p>This information needs to be provided if applicable.</p></td></tr>
<tr>
<td>Name</td>
<td>NamPRTNOT642</td>
<td>Notify Party Name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrNumPRTNOT646</td>
<td>Notify Party Street and Number</td></tr>
<tr>
<td>Postal Code</td>
<td>PstCodPRTNOT644</td>
<td>Notify Party Postal Code</td></tr>
<tr>
<td>City</td>
<td>CtyPRTNOT643</td>
<td>Notify Party City</td></tr>
<tr>
<td>Country Code</td>
<td>CouCodGINOT647</td>
<td>
<p>Notify Party Country Code</p></td></tr>
<tr>
<td>TIN</td>
<td>TINPRTNOT641</td>
<td>Notify Party EORI</td></tr>
<tr>
<td>---Itinerary</td>
<td>INT</td>
<td>This section is required if goods are routed between the <span>country of original departure and final destination</span></td></tr>
<tr>
<td>Country of Routing Code</td>
<td>CouOfRouCodITI1</td>
<td>
<p>Entry Country Codes for all countries where goods are being routed between the country of original departure and final destination.</p></td></tr>
<tr>
<td>---Lodgement (Customs Office)</td>
<td>CUSOFFLON</td>
<td>This section should be present if different from the Country Office of first entry otherwise it should not be provided.&nbsp;</td></tr>
<tr>
<td>Reference Number</td>
<td>RefNumCOL1</td>
<td>Enter the Reference number for Customer Office</td></tr>
<tr>
<td>---(Representative) Trader</td>
<td>TRAREP</td>
<td>
<p>This section relates to the 'Representative Trader' which means the person the declarant has authorised to represent them.</p></td></tr>
<tr>
<td>Name</td>
<td>NamTRE1</td>
<td>Representative Trader Name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrAndNumTRE1</td>
<td>Representative Trader Street and Number</td></tr>
<tr>
<td>Postal Code</td>
<td>PosCodTRE1</td>
<td>Representative Trader Name</td></tr>
<tr>
<td>City</td>
<td>CitTRE1</td>
<td>Representative Trader City</td></tr>
<tr>
<td>Country Code</td>
<td>CouCodTRE1</td>
<td>
<p>Representative Trader Country Code</p></td></tr>
<tr>
<td>TIN</td>
<td>TINTRE1</td>
<td>Representative Trader EORI</td></tr>
<tr>
<td>---(Lodging Summary Declaration) Person</td>
<td>PERLODSUMDEC</td>
<td>
<p>This section relates to the identity of the person lodging the entry summary declaration</p></td></tr>
<tr>
<td>Name</td>
<td>NamPLD1</td>
<td>Lodging person Name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrAndNumPLD1</td>
<td><span>Lodging person Street and Number</span></td></tr>
<tr>
<td>Postal Code</td>
<td>PosCodPLD1</td>
<td><span>Lodging person Postal Code</span></td></tr>
<tr>
<td>City</td>
<td>CitPLD1</td>
<td><span>Lodging person City</span></td></tr>
<tr>
<td>Country Code</td>
<td>CouCodPLD1</td>
<td>
<p><span>Lodging person Country Code</span></p></td></tr>
<tr>
<td>TIN</td>
<td>TINPLD1</td>
<td>
<p><span>Lodging person EORI, t</span>he person lodging must have a GB EORI</p></td></tr>
<tr>
<td>Seals Identity</td>
<td>SeaIdSEAID530</td>
<td><span>Identification number of all seals affixed to the transport equipment</span></td></tr>
<tr>
<td>---(First Entry) Customs Office</td>
<td>CUSOFFFENT730</td>
<td>This section is for&nbsp;First Entry Customs Office</td></tr>
<tr>
<td>Reference Number</td>
<td>RefNumCUSOFFFENT731</td>
<td>Enter First Entry Customs Office Reference</td></tr>
<tr>
<td>Expected Date and Time of Arrival</td>
<td>ExpDatOfArrFIRENT733</td>
<td>
<p>The is for the scheduled date/date and time of arrival of the means of transport at the declared first Office of Entry</p>
<ul>
<li>must be provided in local time GMT/BST</li></ul></td></tr>
<tr>
<td>---(Subsequent Entry) Customs Office</td>
<td>CUSOFFSENT740</td>
<td><span>This section is for</span><span>&nbsp;Subsequent Entry Customs Office</span></td></tr>
<tr>
<td>Reference Number</td>
<td>RefNumSUBENR909</td>
<td>Reference number is required if some of the goods are destined to be transported to subsequent Offices of Entry</td></tr>
<tr>
<td>---(Entry Carrier) Trader</td>
<td>TRACARENT601</td>
<td>
<p>This section relates to the entry carrier which means:</p>
<ul>
<li>The party that transports the goods at entry into the customs territory</li></ul>
<p>This information shall be provided where it is different from the person lodging the summary declaration.</p>
<p>This information does not need to be provided where it can be deduced automatically and unambiguously from other data elements provided by the trader.</p></td></tr>
<tr>
<td>Name</td>
<td>NamTRACARENT604</td>
<td>Entry Carrier name</td></tr>
<tr>
<td>Street and Number</td>
<td>StrNumTRACARENT607</td>
<td>Entry Carrier Street Name and Number</td></tr>
<tr>
<td>Postal Code</td>
<td>PstCodTRACARENT606</td>
<td>Entry Carrier Postal Code</td></tr>
<tr>
<td>City</td>
<td>CtyTRACARENT603</td>
<td>Entry Carrier City</td></tr>
<tr>
<td>Country Code</td>
<td>CouCodTRACARENT605</td>
<td>
<p>Entry Carrier Country Code</p></td></tr>
<tr>
<td>TIN</td>
<td>TINTRACARENT602</td>
<td>
<p><span style="color: rgb(0,0,0);">The Trader Identification Number (TIN) for the Entry Carrier.</span></p>
<p><span style="color: rgb(0,0,0);">This is also known as the EORI <a href="https://www.gov.uk/eori">https://www.gov.uk/eori</a></span></p>
<p><span style="color: rgb(0,0,0);">An EORI is made up </span><span style="color: rgb(34,34,34);">a country code, to show where the organisation or individual is registered, and a unique code or&nbsp;</span>number<span style="color: rgb(34,34,34);">. <br /><br />For&nbsp;</span>UK<span style="color: rgb(34,34,34);">&nbsp;businesses the&nbsp;</span>number<span style="color: rgb(34,34,34);">&nbsp;is made up as follows (with a few minor exceptions): </span></p>
<ul>
<li><span style="color: rgb(34,34,34);">VAT registered businesses: GB + VRN (VAT&nbsp;</span>registration number<span style="color: rgb(34,34,34);">) + 000. </span></li>
<li><span style="color: rgb(34,34,34);">Non-VAT registered businesses: GB + unique&nbsp;</span>number<span style="color: rgb(34,34,34);">&nbsp;issued by HMRC.</span></li></ul></td></tr></tbody></table>
<div><span style="color: rgb(0,0,0);font-family: Arial;font-size: 13.0px;white-space: pre-wrap;"><br /><br /></span></div>