## Ranking companies by eps forecasting error
In the `forecasting_accuracy.Rmd` workbook, we use annual company guidance data from 2006-2016 to compute an average forecasting error for each company in the S&P500.  We then rank the companies by forecasting accuracy within their industry classification.  The results are contained in the `analysis_results.xlsx` workbook and also pasted below:

| sector                 | ticker | name                                   | avg_comp_fcst_err | fcst_rank_sector |
|:-----------------------|:-------|:---------------------------------------|------------------:|-----------------:|
| Consumer Discretionary | MAT    | Mattel Inc.                            |         0.0014799 |                1 |
| Consumer Discretionary | HAS    | Hasbro Inc.                            |         0.0042762 |                2 |
| Consumer Discretionary | GPC    | Genuine Parts                          |         0.0162282 |                3 |
| Consumer Discretionary | YUM    | Yum! Brands Inc                        |         0.0236348 |                4 |
| Consumer Discretionary | TPR    | Tapestry, Inc.                         |         0.0382740 |                5 |
| Consumer Discretionary | LKQ    | LKQ Corporation                        |         0.0419822 |                6 |
| Consumer Discretionary | GPS    | Gap Inc.                               |         0.0434087 |                7 |
| Consumer Discretionary | AAP    | Advance Auto Parts                     |         0.0435696 |                8 |
| Consumer Discretionary | TIF    | Tiffany & Co.                          |         0.0466208 |                9 |
| Consumer Discretionary | GM     | General Motors                         |         0.0533333 |               10 |
| Consumer Discretionary | TSCO   | Tractor Supply Company                 |         0.0608030 |               11 |
| Consumer Discretionary | DG     | Dollar General                         |         0.0632807 |               12 |
| Consumer Discretionary | ROST   | Ross Stores                            |         0.0682353 |               13 |
| Consumer Discretionary | FL     | Foot Locker Inc                        |         0.0687500 |               14 |
| Consumer Discretionary | VFC    | V.F. Corp.                             |         0.0714686 |               15 |
| Consumer Discretionary | RL     | Polo Ralph Lauren Corp.                |         0.0722236 |               16 |
| Consumer Discretionary | ORLY   | O'Reilly Automotive                    |         0.0806673 |               17 |
| Consumer Discretionary | TJX    | TJX Companies Inc.                     |         0.0818807 |               18 |
| Consumer Discretionary | LOW    | Lowe's Cos.                            |         0.1005542 |               19 |
| Consumer Discretionary | HD     | Home Depot                             |         0.1033725 |               20 |
| Consumer Discretionary | TWX    | Time Warner Inc.                       |         0.1066667 |               21 |
| Consumer Discretionary | RCL    | Royal Caribbean Cruises Ltd            |         0.1068900 |               22 |
| Consumer Discretionary | LB     | L Brands Inc.                          |         0.1255952 |               23 |
| Consumer Discretionary | KMX    | Carmax Inc                             |         0.1323836 |               24 |
| Consumer Discretionary | MAR    | Marriott Int'l.                        |         0.1326372 |               25 |
| Consumer Discretionary | HBI    | Hanesbrands Inc                        |         0.1371149 |               26 |
| Consumer Discretionary | KORS   | Michael Kors Holdings                  |         0.1538462 |               27 |
| Consumer Discretionary | BWA    | BorgWarner                             |         0.1743259 |               28 |
| Consumer Discretionary | SWK    | Stanley Black & Decker                 |         0.1749288 |               29 |
| Consumer Discretionary | GRMN   | Garmin Ltd.                            |         0.1784972 |               30 |
| Consumer Discretionary | JWN    | Nordstrom                              |         0.1896359 |               31 |
| Consumer Discretionary | DRI    | Darden Restaurants                     |         0.2238603 |               32 |
| Consumer Discretionary | DLTR   | Dollar Tree                            |         0.2370624 |               33 |
| Consumer Discretionary | CCL    | Carnival Corp.                         |         0.2396694 |               34 |
| Consumer Discretionary | WHR    | Whirlpool Corp.                        |         0.3049543 |               35 |
| Consumer Discretionary | BKNG   | Booking Holdings Inc                   |         0.3280952 |               36 |
| Consumer Discretionary | M      | Macy's Inc.                            |         0.3398504 |               37 |
| Consumer Discretionary | PVH    | PVH Corp.                              |         0.5704745 |               38 |
| Consumer Discretionary | NWL    | Newell Brands                          |         0.8926696 |               39 |
| Consumer Discretionary | TGT    | Target Corp.                           |         0.8998800 |               40 |
| Consumer Discretionary | BBY    | Best Buy Co. Inc.                      |         1.0566964 |               41 |
| Consumer Discretionary | HLT    | Hilton Worldwide Holdings Inc          |         1.1613682 |               42 |
| Consumer Discretionary | LEG    | Leggett & Platt                        |         4.4595559 |               43 |
| Consumer Discretionary | SBUX   | Starbucks Corp.                        |        44.3963336 |               44 |
| Consumer Staples       | TSN    | Tyson Foods                            |         0.0029411 |                1 |
| Consumer Staples       | SJM    | JM Smucker                             |         0.0225694 |                2 |
| Consumer Staples       | COST   | Costco Wholesale Corp.                 |         0.0239130 |                3 |
| Consumer Staples       | GIS    | General Mills                          |         0.0244922 |                4 |
| Consumer Staples       | PEP    | PepsiCo Inc.                           |         0.0278584 |                5 |
| Consumer Staples       | CLX    | The Clorox Company                     |         0.0364213 |                6 |
| Consumer Staples       | CVS    | CVS Health                             |         0.0380778 |                7 |
| Consumer Staples       | PM     | Philip Morris International            |         0.0438846 |                8 |
| Consumer Staples       | MKC    | McCormick & Co.                        |         0.0534000 |                9 |
| Consumer Staples       | WMT    | Wal-Mart Stores                        |         0.0598296 |               10 |
| Consumer Staples       | CHD    | Church & Dwight                        |         0.0668952 |               11 |
| Consumer Staples       | MO     | Altria Group Inc                       |         0.0813207 |               12 |
| Consumer Staples       | CAG    | Conagra Brands                         |         0.0941489 |               13 |
| Consumer Staples       | MDLZ   | Mondelez International                 |         0.1026884 |               14 |
| Consumer Staples       | PG     | Procter & Gamble                       |         0.1221480 |               15 |
| Consumer Staples       | KMB    | Kimberly-Clark                         |         0.1298294 |               16 |
| Consumer Staples       | CPB    | Campbell Soup                          |         0.1378378 |               17 |
| Consumer Staples       | EL     | Estee Lauder Cos.                      |         0.1561901 |               18 |
| Consumer Staples       | K      | Kellogg Co.                            |         0.1948590 |               19 |
| Consumer Staples       | HSY    | The Hershey Company                    |         0.2380305 |               20 |
| Consumer Staples       | STZ    | Constellation Brands                   |         0.4841488 |               21 |
| Consumer Staples       | DPS    | Dr Pepper Snapple Group                |         0.6521861 |               22 |
| Energy                 | VLO    | Valero Energy                          |         0.0108696 |                1 |
| Energy                 | OKE    | ONEOK                                  |         0.0709086 |                2 |
| Energy                 | ANDV   | Andeavor                               |         0.0837438 |                3 |
| Energy                 | FTI    | TechnipFMC                             |         0.4162437 |                4 |
| Energy                 | WMB    | Williams Cos.                          |         0.4303936 |                5 |
| Financials             | RE     | Everest Re Group Ltd.                  |         0.0018954 |                1 |
| Financials             | STT    | State Street Corp.                     |         0.0043478 |                2 |
| Financials             | AFL    | AFLAC Inc                              |         0.0516851 |                3 |
| Financials             | AXP    | American Express Co                    |         0.0548673 |                4 |
| Financials             | FITB   | Fifth Third Bancorp                    |         0.0657572 |                5 |
| Financials             | PFG    | Principal Financial Group              |         0.1357601 |                6 |
| Financials             | WLTW   | Willis Towers Watson                   |         0.1513158 |                7 |
| Financials             | BLK    | BlackRock                              |         0.1567065 |                8 |
| Financials             | PRU    | Prudential Financial                   |         0.2145999 |                9 |
| Financials             | MET    | MetLife Inc.                           |         0.2254404 |               10 |
| Financials             | HRB    | Block H&R                              |         0.2584270 |               11 |
| Financials             | NDAQ   | Nasdaq, Inc.                           |         0.4105263 |               12 |
| Financials             | COF    | Capital One Financial                  |         0.4584912 |               13 |
| Financials             | MCO    | Moody's Corp                           |         0.5200014 |               14 |
| Financials             | ETFC   | E*Trade                                |         0.7936070 |               15 |
| Financials             | HBAN   | Huntington Bancshares                  |         3.7540972 |               16 |
| Health Care            | AET    | Aetna Inc                              |         0.0046802 |                1 |
| Health Care            | WAT    | Waters Corporation                     |         0.0046948 |                2 |
| Health Care            | LH     | Laboratory Corp. of America Holding    |         0.0123457 |                3 |
| Health Care            | CERN   | Cerner                                 |         0.0171985 |                4 |
| Health Care            | EVHC   | Envision Healthcare                    |         0.0233807 |                5 |
| Health Care            | BAX    | Baxter International Inc.              |         0.0377433 |                6 |
| Health Care            | UNH    | United Health Group Inc.               |         0.0570818 |                7 |
| Health Care            | MDT    | Medtronic plc                          |         0.0618528 |                8 |
| Health Care            | IDXX   | IDEXX Laboratories                     |         0.0702880 |                9 |
| Health Care            | JNJ    | Johnson & Johnson                      |         0.0757576 |               10 |
| Health Care            | VAR    | Varian Medical Systems                 |         0.0800952 |               11 |
| Health Care            | BIIB   | Biogen Inc.                            |         0.0872108 |               12 |
| Health Care            | ABC    | AmerisourceBergen Corp                 |         0.0873087 |               13 |
| Health Care            | HSIC   | Henry Schein                           |         0.1014445 |               14 |
| Health Care            | ALXN   | Alexion Pharmaceuticals                |         0.1022727 |               15 |
| Health Care            | MYL    | Mylan N.V.                             |         0.1044664 |               16 |
| Health Care            | SYK    | Stryker Corp.                          |         0.1084501 |               17 |
| Health Care            | ANTM   | Anthem Inc.                            |         0.1256853 |               18 |
| Health Care            | XRAY   | Dentsply Sirona                        |         0.1294118 |               19 |
| Health Care            | MTD    | Mettler Toledo                         |         0.1523336 |               20 |
| Health Care            | AMGN   | Amgen Inc.                             |         0.1591103 |               21 |
| Health Care            | DHR    | Danaher Corp.                          |         0.1631614 |               22 |
| Health Care            | DGX    | Quest Diagnostics                      |         0.1888131 |               23 |
| Health Care            | BDX    | Becton Dickinson                       |         0.2055180 |               24 |
| Health Care            | UHS    | Universal Health Services, Inc.        |         0.2138121 |               25 |
| Health Care            | HUM    | Humana Inc.                            |         0.2200860 |               26 |
| Health Care            | ZBH    | Zimmer Biomet Holdings                 |         0.2628858 |               27 |
| Health Care            | PFE    | Pfizer Inc.                            |         0.2664073 |               28 |
| Health Care            | ZTS    | Zoetis                                 |         0.2872800 |               29 |
| Health Care            | BMY    | Bristol-Myers Squibb                   |         0.3603905 |               30 |
| Health Care            | ESRX   | Express Scripts                        |         0.3620699 |               31 |
| Health Care            | PRGO   | Perrigo                                |         0.3714593 |               32 |
| Health Care            | ILMN   | Illumina Inc                           |         0.3794519 |               33 |
| Health Care            | LLY    | Lilly (Eli) & Co.                      |         0.3809697 |               34 |
| Health Care            | CELG   | Celgene Corp.                          |         0.4046383 |               35 |
| Health Care            | ABT    | Abbott Laboratories                    |         0.4425406 |               36 |
| Health Care            | A      | Agilent Technologies Inc               |         0.4678571 |               37 |
| Health Care            | ABBV   | AbbVie Inc.                            |         0.5137775 |               38 |
| Health Care            | MRK    | Merck & Co.                            |         0.5949437 |               39 |
| Health Care            | AGN    | Allergan, Plc                          |         0.6414304 |               40 |
| Health Care            | ALGN   | Align Technology                       |         0.8049153 |               41 |
| Health Care            | IQV    | IQVIA Holdings Inc.                    |         0.9949860 |               42 |
| Health Care            | HOLX   | Hologic                                |         1.5815210 |               43 |
| Health Care            | PKI    | PerkinElmer                            |         1.7759901 |               44 |
| Health Care            | COO    | The Cooper Companies                   |         2.5027775 |               45 |
| Health Care            | BSX    | Boston Scientific                      |         2.5793234 |               46 |
| Health Care            | CNC    | Centene Corporation                    |         5.6691887 |               47 |
| Industrials            | UPS    | United Parcel Service                  |         0.0000000 |                1 |
| Industrials            | ROK    | Rockwell Automation Inc.               |         0.0053957 |                2 |
| Industrials            | EFX    | Equifax Inc.                           |         0.0099010 |                3 |
| Industrials            | SRCL   | Stericycle Inc                         |         0.0219626 |                4 |
| Industrials            | FLS    | Flowserve Corporation                  |         0.0254450 |                5 |
| Industrials            | GE     | General Electric                       |         0.0296190 |                6 |
| Industrials            | ROP    | Roper Technologies                     |         0.0344176 |                7 |
| Industrials            | NLSN   | Nielsen Holdings                       |         0.0359712 |                8 |
| Industrials            | AME    | AMETEK Inc.                            |         0.0396290 |                9 |
| Industrials            | COL    | Rockwell Collins                       |         0.0409674 |               10 |
| Industrials            | MMM    | 3M Company                             |         0.0499919 |               11 |
| Industrials            | CTAS   | Cintas Corporation                     |         0.0547195 |               12 |
| Industrials            | UTX    | United Technologies                    |         0.0589970 |               13 |
| Industrials            | FBHS   | Fortune Brands Home & Security         |         0.0597015 |               14 |
| Industrials            | JCI    | Johnson Controls International         |         0.0731401 |               15 |
| Industrials            | GWW    | Grainger (W.W.) Inc.                   |         0.0810185 |               16 |
| Industrials            | XYL    | Xylem Inc.                             |         0.0819543 |               17 |
| Industrials            | PH     | Parker-Hannifin                        |         0.0977993 |               18 |
| Industrials            | ITW    | Illinois Tool Works                    |         0.0982044 |               19 |
| Industrials            | FDX    | FedEx Corporation                      |         0.1004712 |               20 |
| Industrials            | AOS    | A.O. Smith Corp                        |         0.1005273 |               21 |
| Industrials            | NOC    | Northrop Grumman Corp.                 |         0.1122841 |               22 |
| Industrials            | EMR    | Emerson Electric Company               |         0.1140274 |               23 |
| Industrials            | RSG    | Republic Services Inc                  |         0.1277058 |               24 |
| Industrials            | JEC    | Jacobs Engineering Group               |         0.1283595 |               25 |
| Industrials            | DOV    | Dover Corp.                            |         0.1353130 |               26 |
| Industrials            | URI    | United Rentals, Inc.                   |         0.1426811 |               27 |
| Industrials            | RTN    | Raytheon Co.                           |         0.1649590 |               28 |
| Industrials            | ETN    | Eaton Corporation                      |         0.2242878 |               29 |
| Industrials            | PWR    | Quanta Services Inc.                   |         0.2779454 |               30 |
| Industrials            | HON    | Honeywell Int'l Inc.                   |         0.2818533 |               31 |
| Industrials            | TDG    | TransDigm Group                        |         0.3845645 |               32 |
| Industrials            | IR     | Ingersoll-Rand PLC                     |         0.3932287 |               33 |
| Industrials            | ALLE   | Allegion                               |         0.3963212 |               34 |
| Industrials            | BA     | Boeing Company                         |         0.4307322 |               35 |
| Industrials            | TXT    | Textron Inc.                           |         0.9587220 |               36 |
| Industrials            | MAS    | Masco Corp.                            |         1.0945618 |               37 |
| Industrials            | LLL    | L-3 Communications Holdings            |         1.1817057 |               38 |
| Industrials            | PNR    | Pentair Ltd.                           |         4.6413886 |               39 |
| Industrials            | CAT    | Caterpillar Inc.                       |         5.6828240 |               40 |
| Information Technology | ADP    | Automatic Data Processing              |         0.0043077 |                1 |
| Information Technology | ORCL   | Oracle Corp.                           |         0.0091743 |                2 |
| Information Technology | CSCO   | Cisco Systems                          |         0.0100671 |                3 |
| Information Technology | RHT    | Red Hat Inc.                           |         0.0186916 |                4 |
| Information Technology | FFIV   | F5 Networks                            |         0.0236486 |                5 |
| Information Technology | TSS    | Total System Services                  |         0.0301674 |                6 |
| Information Technology | FIS    | Fidelity National Information Services |         0.0328467 |                7 |
| Information Technology | PYPL   | PayPal                                 |         0.0352174 |                8 |
| Information Technology | APH    | Amphenol Corp                          |         0.0443241 |                9 |
| Information Technology | FLIR   | FLIR Systems                           |         0.0539993 |               10 |
| Information Technology | ACN    | Accenture plc                          |         0.0552845 |               11 |
| Information Technology | IT     | Gartner Inc                            |         0.0830183 |               12 |
| Information Technology | CTSH   | Cognizant Technology Solutions         |         0.0896666 |               13 |
| Information Technology | IBM    | International Business Machines        |         0.1034379 |               14 |
| Information Technology | CTXS   | Citrix Systems                         |         0.1042481 |               15 |
| Information Technology | ADS    | Alliance Data Systems                  |         0.1096957 |               16 |
| Information Technology | INTU   | Intuit Inc.                            |         0.1107069 |               17 |
| Information Technology | GPN    | Global Payments Inc.                   |         0.1131064 |               18 |
| Information Technology | NTAP   | NetApp                                 |         0.1271279 |               19 |
| Information Technology | SNPS   | Synopsys Inc.                          |         0.1295585 |               20 |
| Information Technology | NFLX   | Netflix Inc.                           |         0.1645055 |               21 |
| Information Technology | TEL    | TE Connectivity Ltd.                   |         0.1715849 |               22 |
| Information Technology | ADBE   | Adobe Systems Inc                      |         0.1956489 |               23 |
| Information Technology | XRX    | Xerox Corp.                            |         0.2148074 |               24 |
| Information Technology | CA     | CA, Inc.                               |         0.2265007 |               25 |
| Information Technology | QCOM   | QUALCOMM Inc.                          |         0.2268707 |               26 |
| Information Technology | STX    | Seagate Technology                     |         0.2626979 |               27 |
| Information Technology | WU     | Western Union Co                       |         0.2670666 |               28 |
| Information Technology | SYMC   | Symantec Corp.                         |         0.2829632 |               29 |
| Information Technology | HPQ    | HP Inc.                                |         0.2969715 |               30 |
| Information Technology | ANSS   | ANSYS                                  |         0.3393329 |               31 |
| Information Technology | ADSK   | Autodesk Inc.                          |         0.3454481 |               32 |
| Information Technology | CDNS   | Cadence Design Systems                 |         0.5138666 |               33 |
| Information Technology | ATVI   | Activision Blizzard                    |         0.5185514 |               34 |
| Information Technology | HPE    | Hewlett Packard Enterprise             |         0.5604396 |               35 |
| Information Technology | TTWO   | Take-Two Interactive                   |         1.7443652 |               36 |
| Information Technology | EA     | Electronic Arts                        |         3.6643050 |               37 |
| Information Technology | HRS    | Harris Corporation                     |         4.6614116 |               38 |
| Information Technology | EBAY   | eBay Inc.                              |         6.8410159 |               39 |
| Information Technology | CRM    | Salesforce.com                         |               Inf |               40 |
| Materials              | MLM    | Martin Marietta Materials              |         0.0406427 |                1 |
| Materials              | SHW    | Sherwin-Williams                       |         0.0453841 |                2 |
| Materials              | PX     | Praxair Inc.                           |         0.0658314 |                3 |
| Materials              | APD    | Air Products & Chemicals Inc           |         0.1118001 |                4 |
| Materials              | AVY    | Avery Dennison Corp                    |         0.1590106 |                5 |
| Materials              | SEE    | Sealed Air                             |         0.1643573 |                6 |
| Materials              | MON    | Monsanto Co.                           |         0.1785088 |                7 |
| Materials              | ECL    | Ecolab Inc.                            |         0.1832461 |                8 |
| Materials              | VMC    | Vulcan Materials                       |         0.3458340 |                9 |
| Real Estate            | SPG    | Simon Property Group Inc               |         0.0221465 |                1 |
| Real Estate            | IRM    | Iron Mountain Incorporated             |         0.1135467 |                2 |
| Real Estate            | FRT    | Federal Realty Investment Trust        |         0.1150792 |                3 |
| Real Estate            | O      | Realty Income Corporation              |         0.1293527 |                4 |
| Real Estate            | CCI    | Crown Castle International Corp.       |         0.1328125 |                5 |
| Real Estate            | VTR    | Ventas Inc                             |         0.1701258 |                6 |
| Real Estate            | EQR    | Equity Residential                     |         0.1884762 |                7 |
| Real Estate            | AVB    | AvalonBay Communities, Inc.            |         0.1919787 |                8 |
| Real Estate            | DLR    | Digital Realty Trust Inc               |         0.2023248 |                9 |
| Real Estate            | EXR    | Extra Space Storage                    |         0.2203643 |               10 |
| Real Estate            | DRE    | Duke Realty Corp                       |         0.2272727 |               11 |
| Real Estate            | ESS    | Essex Property Trust, Inc.             |         0.2693726 |               12 |
| Real Estate            | SLG    | SL Green Realty                        |         0.3151350 |               13 |
| Real Estate            | HST    | Host Hotels & Resorts                  |         0.3330602 |               14 |
| Real Estate            | ARE    | Alexandria Real Estate Equities Inc    |         0.4010431 |               15 |
| Real Estate            | MAC    | Macerich                               |         0.4447182 |               16 |
| Real Estate            | WELL   | Welltower Inc.                         |         0.6357548 |               17 |
| Real Estate            | GGP    | General Growth Properties Inc.         |         0.6709264 |               18 |
| Real Estate            | AIV    | Apartment Investment & Management      |         1.0906690 |               19 |
| Real Estate            | KIM    | Kimco Realty                           |         1.3389903 |               20 |
| Real Estate            | PLD    | Prologis                               |         1.3594672 |               21 |
| Real Estate            | HCP    | HCP Inc.                               |         1.3977427 |               22 |
| Real Estate            | REG    | Regency Centers Corporation            |         1.6695521 |               23 |
| Real Estate            | UDR    | UDR Inc                                |         2.5105648 |               24 |
| Utilities              | AWK    | American Water Works Company Inc       |         0.0019084 |                1 |
| Utilities              | ES     | Eversource Energy                      |         0.0138430 |                2 |
| Utilities              | SO     | Southern Co.                           |         0.0214077 |                3 |
| Utilities              | XEL    | Xcel Energy Inc                        |         0.0329764 |                4 |
| Utilities              | SCG    | SCANA Corp                             |         0.0646659 |                5 |
| Utilities              | SRE    | Sempra Energy                          |         0.0700441 |                6 |
| Utilities              | ETR    | Entergy Corp.                          |         0.1119263 |                7 |
| Utilities              | EXC    | Exelon Corp.                           |         0.1555916 |                8 |
| Utilities              | AEP    | American Electric Power                |         0.1854839 |                9 |
| Utilities              | PCG    | PG&E Corp.                             |         0.1972936 |               10 |
| Utilities              | CNP    | CenterPoint Energy                     |         0.2077465 |               11 |
| Utilities              | PPL    | PPL Corp.                              |         0.2091968 |               12 |
| Utilities              | LNT    | Alliant Energy Corp                    |         0.3680297 |               13 |
| Utilities              | AEE    | Ameren Corp                            |         0.7149827 |               14 |
| Utilities              | FE     | FirstEnergy Corp                       |         0.7419994 |               15 |
| Utilities              | NI     | NiSource Inc.                          |         0.9895985 |               16 |
| Utilities              | AES    | AES Corp                               |         2.1507773 |               17 |
| Utilities              | EIX    | Edison Int'l                           |         3.0196691 |               18 |
| NA                     | BHI    | NA                                     |         0.0116919 |                1 |
| NA                     | BF     | NA                                     |         0.1117419 |                2 |
