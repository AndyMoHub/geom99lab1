# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json
?avoid=toll
&depature_time=1674183600
&origin=place_id:ChIJ7TrIIsXRKogR4hDB14vKuJ4
&waypoints=place_id:ChIJl9dHxBUvK4gRyjDLRoGLlM4
&destination=place_id:ChIJmzrzi9Y0K4gRgXUc3sTY7RU
&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE

```

## Next paste the full JSON response to this query here:

```JSON

{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ7TrIIsXRKogR4hDB14vKuJ4",
         "types" : [ "premise" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJl9dHxBUvK4gRyjDLRoGLlM4",
         "types" : [ "establishment", "point_of_interest", "shopping_mall" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJmzrzi9Y0K4gRgXUc3sTY7RU",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 44.0560811,
               "lng" : -79.38665709999999
            },
            "southwest" : {
               "lat" : 43.6134507,
               "lng" : -79.59678770000001
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "33.5 km",
                  "value" : 33483
               },
               "duration" : {
                  "text" : "27 mins",
                  "value" : 1593
               },
               "end_address" : "1 Bass Pro Mills Dr, Vaughan, ON L4K 5W4, Canada",
               "end_location" : {
                  "lat" : 43.8263781,
                  "lng" : -79.53913799999999
               },
               "start_address" : "221 Woodspring Ave, Newmarket, ON L3X 3J1, Canada",
               "start_location" : {
                  "lat" : 44.056011,
                  "lng" : -79.5020329
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 473
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 44.0547446,
                        "lng" : -79.5075138
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eWoodspring Ave\u003c/b\u003e toward \u003cb\u003eRay Snow Blvd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "au{kGtvfdNI~AAHAP?V?T?Z@`@Dl@Lv@Np@Tp@DNd@rA~@jCDLVr@FXLl@Ht@H|@F`@?LRvB"
                     },
                     "start_location" : {
                        "lat" : 44.056011,
                        "lng" : -79.5020329
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 637
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 44.0491826,
                        "lng" : -79.50630149999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBathurst St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 38\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cm{kG|xgdN@XnE}@tBa@TMpAUFAj@Kb@GdAOd@Ip@Iv@IXCp@I`ACjFq@"
                     },
                     "start_location" : {
                        "lat" : 44.0547446,
                        "lng" : -79.5075138
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "7.3 km",
                        "value" : 7315
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 343
                     },
                     "end_location" : {
                        "lat" : 44.0297805,
                        "lng" : -79.59313969999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDavis Dr W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 31\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Davis Dr W\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kjzkGjqgdNR~AFj@`@nCL|@R~ATbBDTFb@dA|HR~AHb@j@|DRpABN\\bCT~AJn@@Hp@lCJXPj@@Dd@lAPd@LVHPj@nATd@^~@HPRf@t@fBHRN\\BHdAhDXfAFTb@dBN~@z@`F\\tDJr@j@lFz@vIFn@`@bEFl@TtC@J@b@DdA?|A?h@?JChAEbCGxBAb@A~A?l@?F?p@?DBhA@j@@ZFfA?DDj@Fz@Hh@Hp@VzAh@vC\\jBFZZfBl@fDnAbHhAdH`@dC@HT|Ab@tCHh@\\pBD^@?l@`EdA|G@HjAdJBV?@f@nENrAl@nGFh@VjCZvCf@bFN|@`@rC\\jBfA|Hh@xCJp@b@jCZfBX|APdAN~@ZfBFv@L|@XdBv@zEJn@V|AV|AJn@`@fCb@lCJ`AHb@t@hFRl@h@xDLv@NjALz@Jp@BNFh@F^^lCT~AHn@Hn@T~AHn@T|AJn@Hn@h@~Db@dCBTHd@@LXlBPpA\\~BL|@p@~EXlB`@fD@Fr@pFl@lEF\\n@tEF^@Ff@tDDVVrBDZZlCRbB@NNlA^hDRhBNzAXpCBVN~A\\bDC\\@XD^BVX~BD`@L~@Fn@Fl@DXD\\"
                     },
                     "start_location" : {
                        "lat" : 44.0491826,
                        "lng" : -79.50630149999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 197
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 44.0292618,
                        "lng" : -79.5954955
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-9 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cqvkGbpxdNNrAj@fEL~@\\zB"
                     },
                     "start_location" : {
                        "lat" : 44.0297805,
                        "lng" : -79.59313969999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "22.6 km",
                        "value" : 22629
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 785
                     },
                     "end_location" : {
                        "lat" : 43.8332714,
                        "lng" : -79.54694979999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eON-400 S\u003c/b\u003e via the ramp to \u003cb\u003eToronto\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{mvkGz~xdNAn@@\\?J?DAZCPEPERABINGJCDKJOJOHQBOBO@Q?OCSGQKUSKMOWKUGWEWE[?IAO@S?C@O@U@EBK?AFOFOJOLOHITKrAc@`@M@ANINIf@WVOn@IZEhBYRCPCLC\\EpB[l@Ix@MdC_@HCb@G@AFA@ARQdBWh@I~AWJAhAS^I`BY|AYhB]lB_@HCdCe@|Dw@tAUpAO`AU`Cc@tAU~@QhB[bAM|@S~@Qt@Kp@Mj@Kx@Kr@Q`Ca@|A[tBg@tBc@hBa@~Bi@dBa@|LqCr@QNCdAWnA[|@WhCm@bHiB@?pEgATG`@IjAWfAUjBe@xA]|EgAbAW|A]@?jA]x@ShAWb@KVGFCD?BAXIj@MnCq@XId@Kx@QDCPO@?x@S\\IdBc@FAj@MZGPC`@IFCf@ITEHA^Gh@K\\EbAONCdAQPCRCh@Ip@KnASd@Gv@MNC|@M`AOj@I|@Oj@IPChFw@hBWx@MTCXEhAQdC_@nAQVErASl@ItAS~@Oj@I`C]bC_@h@I~@O`AOj@IvAUhBWp@Kz@OZE|B_@tASn@K~@OTCv@MFAh@IPCbAOHAv@MTCj@Kj@I@?~@MREb@G\\EVEh@I^GHAj@IFAb@Ij@Ij@IDAb@Gj@If@IB?h@Kl@Ih@I\\GLA~@OFAlAQbAQD?nAS~@OhBWn@KhAQVEl@IdAOl@Kb@Gt@MZEZEp@KRCbAOz@OXEh@I~@MVETEj@IhBYTChAQJAv@MZGz@MLCp@K^Gt@MRCh@ITEl@If@Ij@I@?|@Oj@Ij@IZEJC`AO\\Eb@I~@MTEDAb@Gj@I`AOZGxASHAj@ITEf@I@?f@I@?TETEj@Ij@IRCTERC`AOh@I@?rASTETETE~@MXEd@GTEh@IVETEh@GTERE`AM~@OTETCj@Ih@I`@I^EREXEPCRE@?RCTEFAb@Gj@IRCh@IRE@?j@I~@Oj@ITCNCZGRCPEB?f@ITC@?REVE@?d@Ih@IB?h@I~@MTEb@GFATEf@IB?z@MB?REh@G@?b@Ih@G@Ab@Gl@K`@GTCREh@IHApASPCr@KJAt@M\\GVEB?vB[~@O`@GnAQ|@Od@GVEdBWrASj@IPC|@Oj@Ir@K^Gv@MZEf@Ib@G`AOt@M`@GxB[jAQ|@Ot@KFAh@Ih@IVEf@Ih@IJAr@Kf@IjAQ`AO~@MtAU@?hAOVEn@ITCjAQLA`AKNCrAODAXCtAQDALCvAQ`AMHChAObAOvAU|@Md@ITCfAOp@MFAdBW@?l@IZGPC^GFAVETC`@GFAz@MTELCTC\\G|@MHCd@GLC^GTCj@Kj@IDAb@Gf@Gb@In@I|AULCTE`AOlAQ^EbAQf@G@A~@Mh@IbAOJABA`AOlDi@FAxB[bBWdC_@nBYjBY`BUDAdDg@^GVCdB[|@QPCrAUz@MfAQ|Ey@nBc@DAnDg@pC_@xAUnFw@vJ{AzAUvB]|Eu@^ErHy@x@KxFw@~Dm@tCa@ZGzAUVCVG@ABAB?fBYrCa@zB]hBWbAQhLcBz@MlBYrB[`C_@bBU|J{AxAUzO_C~HiA~AW`@Gb@GbBWvIqARCXEhAQVE~@OPC|AU~@MtDk@|AUdDg@lBYnZoEpCc@p@I|B]vB]|HiArEq@lCa@~@OzAUtEq@hC_@pASjDg@bK}A`C]bDg@tFy@TKFAHCjBYbHcAjG_Ab@GvFy@vCe@fAOfHeAxEs@|Dk@j@KjC_@zGcAhCa@zB]nC_@bAGVEh@G\\CLC~AM^E~@IRAj@Ej@ETAlAE`AEx@GvDQh@APApAGdCKXAn@EVAVAXCXAj@Cx@EbAETALAZAnEShAEHA|BKjAGhDO"
                     },
                     "start_location" : {
                        "lat" : 44.0292618,
                        "lng" : -79.5954955
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 641
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 43.8278135,
                        "lng" : -79.54817079999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e33\u003c/b\u003e for \u003cb\u003eRegional Rd 73\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRutherford Road\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "}dpjGloodN\\V@@ZA`AAd@?tBAx@AjA?j@?`@@N@H?D@LBTBVFLBB@RFPHNFRNRNTRnAhAh@h@f@^PHJDPDNBH?F?FANCNE\\Ix@_@"
                     },
                     "start_location" : {
                        "lat" : 43.8332714,
                        "lng" : -79.54694979999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 593
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 69
                     },
                     "end_location" : {
                        "lat" : 43.8288767,
                        "lng" : -79.5410787
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRutherford Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 73\u003c/b\u003e (signs for \u003cb\u003eRutherford Road\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRegional Rd 73 E\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ybojG`wodNTMSaAM}@CKKs@Iq@AIYaDWaDQsCe@eHC_@YoCUaCOoA"
                     },
                     "start_location" : {
                        "lat" : 43.8278135,
                        "lng" : -79.54817079999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 202
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 43.82715229999999,
                        "lng" : -79.5406378
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oiojGvjndNPUFKDETOd@K\\IdAWz@L`ABZC"
                     },
                     "start_location" : {
                        "lat" : 43.8288767,
                        "lng" : -79.5410787
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 328
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 43.8261773,
                        "lng" : -79.5442984
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFishermens Way\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "u~njG~gndN@Z?L@j@?j@?H?b@?j@@l@?PB`@Dh@Ff@@JH`@Lh@Ph@Tj@BDRb@Zp@@@h@v@FF"
                     },
                     "start_location" : {
                        "lat" : 43.82715229999999,
                        "lng" : -79.5406378
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "79 m",
                        "value" : 79
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 43.8257315,
                        "lng" : -79.5435301
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sxnjGz~ndNVc@l@gARm@"
                     },
                     "start_location" : {
                        "lat" : 43.8261773,
                        "lng" : -79.5442984
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 389
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 43.8263781,
                        "lng" : -79.53913799999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yunjG`zndNE{@?GIg@?EWc@CC]i@U[KO_@i@AAKY?KA[?MAMB[@CL_@BKBK?E?E@U?AAk@Ck@Ak@Ak@?m@Aa@@IBU@W@]?O?I?G"
                     },
                     "start_location" : {
                        "lat" : 43.8257315,
                        "lng" : -79.5435301
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "42.4 km",
                  "value" : 42412
               },
               "duration" : {
                  "text" : "34 mins",
                  "value" : 2042
               },
               "end_address" : "290 Bremner Blvd, Toronto, ON M5V 3L9, Canada",
               "end_location" : {
                  "lat" : 43.641677,
                  "lng" : -79.38665709999999
               },
               "start_address" : "1 Bass Pro Mills Dr, Vaughan, ON L4K 5W4, Canada",
               "start_location" : {
                  "lat" : 43.8263781,
                  "lng" : -79.53913799999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 468
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 103
                     },
                     "end_location" : {
                        "lat" : 43.8261773,
                        "lng" : -79.5442984
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{ynjGr~mdN?F?H?NA\\AVCTAH@`@?l@@j@@j@Bj@@j@?@AT?D?DCJCJM^ABCZ@L?L@Z?JJX@@^h@JNTZ\\h@BBVb@?DHf@?FDz@Sl@m@fAWb@"
                     },
                     "start_location" : {
                        "lat" : 43.8263781,
                        "lng" : -79.53913799999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 604
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 43.8209778,
                        "lng" : -79.54424229999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFishermens Way\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sxnjGz~ndNZXXX\\TVPHBn@ZJDbADNAp@Bp@Cx@KHA`@CL?J@JAB?LABAXCJFT?ZAz@Bn@CF?\\AVG\\O^Sj@a@NKLGNGj@QDATCF?H?ND"
                     },
                     "start_location" : {
                        "lat" : 43.8261773,
                        "lng" : -79.5442984
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 825
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 43.8198786,
                        "lng" : -79.54566899999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBass Pro Mills Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cxmjGn~ndNHn@P~ABTPrAD\\@LD\\@DFh@RdBHn@Hn@D\\B`@?P?NADAFAFCDEJEFIFUJuBXqAPE@C?ECCAECCEAECGCQGi@Ea@Im@Ea@AU?OAQ@SBQFSBMFMFIDE@ABEHEFCJEJERE\\EPCh@I\\E^GJA`@Ex@K^C@AXe@"
                     },
                     "start_location" : {
                        "lat" : 43.8209778,
                        "lng" : -79.54424229999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.1 km",
                        "value" : 11090
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 372
                     },
                     "end_location" : {
                        "lat" : 43.7215822,
                        "lng" : -79.52268269999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eON-400 S\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "gqmjGlgodNbAE^ChBIJAB?lBIvAG`AEj@Cl@El@CRAl@EvAKxAKRCtAObAKVEh@GHAZEVErASj@I~@MRCvAUtAS`AO|@Mh@I`AOtCc@~B]tCc@@?hFw@tEq@j@IBAnAQj@I~@O~@O~@MjBYjDi@j@I~B]`Em@tAS|@OvAStASh@INCn@KtAS`C]tAURCj@I~@OtCc@TCj@Kh@I`AMNCl@Kl@If@INCXEl@I~@ORCVE~@Oh@IfAO`@GjBYtASTE~B]TEh@Ij@Gh@I~@Mj@I|@MdC]f@Gj@IPClBWbC]RCHA^G`@GHAnBYpCc@D?pC_@d@Id@G\\EX@b@ARCPCTEt@KTE\\ETEVEXEz@MlASb@GXGlAS\\GREd@IxAUXGh@INCZGf@Ih@Kj@K|@Oj@Kj@Il@Kz@Oj@If@Il@Kh@If@I^G^G`AMVEZE^Gl@K`AOvAS~@OTCj@IdAQLAjBYl@KbBUl@KbAOpAQhBYTEj@ItASl@IJCRCr@KVEVE^Gt@K`@Gl@K|@M`AONC\\Ej@IRETEj@Ih@Ij@Ih@Ih@ITCj@Kj@Ih@Ih@ITCLC\\G~@Mj@ITE~@OTCRERCVERCVEj@If@ITCTEHA`@GRETC~@OTCREVE~@MTEh@I`AORC~@Ol@Ih@If@I@?`AOZELCXEx@Mj@Ij@IRCTEd@Gn@Kj@ITERCTETEh@Ij@IhAQv@MNCB?TEj@ITEh@I\\ELCh@Id@IXEf@Gj@IFA`@Gh@Ij@If@IxASTERCTETCTEh@I~@MTE~@M@Ah@Ij@Ih@Ih@Ij@I~@OTCj@KjAQHAj@IPCVERCRCVETERETCTETCn@KDAHATCBANCTETCTEh@ITCTERCTETCVERCVERERCTETCDANCTCTERE@?RCTERCTETCj@Ih@ITETETCRC@ARCTERCTEB?PCTETCREl@ITERCTERCVERCTETERCTETCTEVEPCTCVE~@OTCRERC@?REVCREHA`@GRCZGNCTCTEh@IRCVETE^Gt@K@?PCj@KHAJARCTETETCREHAPCnAQTETC^G^G`AORCJC^ETEREVCRED?PERCRCFAv@Mj@ILCr@KRCTE@?RCREVERCTETCDANCh@Ij@Ij@IRE\\Ej@IDANCJC`AMREj@IJAHA~@OTE^EJCj@ITERCTERCTCVE|@OXERCTETCRETCTERCTETCTETERCTETCTERCTETCTETCTETE~@Ml@K|Du@~@OdAOf@ItAU~@Sh@O|@[h@STId@Ud@U"
                     },
                     "start_location" : {
                        "lat" : 43.8198786,
                        "lng" : -79.54566899999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 358
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 43.7187039,
                        "lng" : -79.5206986
                     },
                     "html_instructions" : "Take the \u003cb\u003eOntario 401 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOntario 401 W\u003c/b\u003e exit on the \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "{jziGvwjdNpHoEjCaB`CyA"
                     },
                     "start_location" : {
                        "lat" : 43.7215822,
                        "lng" : -79.52268269999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.4 km",
                        "value" : 6447
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 282
                     },
                     "end_location" : {
                        "lat" : 43.6825647,
                        "lng" : -79.57494969999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork, follow signs for \u003cb\u003eOntario 401 O\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-401 W\u003c/b\u003e and merge onto \u003cb\u003eON-401 W\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "{xyiGjkjdNPC@?VOLIf@ULE^Md@GB?T?RDH@VF^PNJPPBB@@DDJNNXJR?BFPHT?BFVFT@BD\\BNBLFb@Df@H`A@@N^XxGN`CJxALbADb@JhAFf@Jt@BTBV|@pGVhB@D`@pCFl@Jl@JlAXpBDVRzADNBJ\\bCZxBt@hFFb@Jp@F`@`@dCZtBr@bFl@zD^dCBPZtBRpAPlAHj@Fb@Fb@Jx@DZHz@DZJbA@HDb@B\\BZB\\DZFz@BZB^JrAFt@Dd@DZD\\D\\DZD\\DZF\\Jv@F\\H`@DTFTNt@Jb@l@hCXjANl@DPBLLh@Nj@BNR|@Ln@Jf@Lr@Ln@Lt@Lt@BPJr@Lx@DTF`@Jt@FZF^Nt@FZ@Dj@zBDRNb@Vt@L\\Rj@Xn@Xn@JRNX\\j@\\l@^h@JNRVJLTXLNPPLNTVNNPPPPPPPNNJTTd@^VRJHd@^BB`@ZJHXTPNPNr@h@@@@?b@C|@v@l@f@VT^Zb@^b@^b@^f@b@JHb@`@JHZVb@^RP`@\\b@^`@\\TRb@^^\\@??@N\\f@`@XTFDb@^RPRPb@^dA|@b@\\d@`@b@\\d@`@BBv@p@NLvAlAHFz@t@BBzApAb@^PNlAbA|AtApAdAbA|@hA`A~DjD`Ax@p@l@v@p@bBvA`Ax@XRJHd@^v@j@f@\\d@\\RL\\Tl@`@TNh@Xx@f@z@d@h@V|@d@~@d@tBbAZPXLNHJFz@b@d@Th@Xz@d@h@VbBz@fAh@p@\\PHz@b@B@b@T|@b@z@`@vBfAxBdAf@VPHz@`@TJp@Zx@^^NbBt@"
                     },
                     "start_location" : {
                        "lat" : 43.7187039,
                        "lng" : -79.5206986
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1778
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 43.6685205,
                        "lng" : -79.57414279999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e352\u003c/b\u003e for \u003cb\u003eON-427 S\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "_wriGl~tdNZ`@@@lAl@z@b@NH`@TPH`@Tb@Vz@d@r@`@x@b@tAz@nAr@xCdBTL\\RZRRJb@VRLPJ@?d@Z\\RpAv@LHj@ZRHf@TPFTHPDTHRDRDTDRD`@DbAHn@@rBSTETEPCFALCTGZI`@ORKRIPIRKPMRKPMRMNOPMPOPQNOPQNSNQNQ^i@NUNSNSDIT[b@o@d@m@Ze@V_@DENUPWJM^i@\\a@Z_@PQPSPQPQPQPOPQPOPOPMPOTQPM`@YPA"
                     },
                     "start_location" : {
                        "lat" : 43.6825647,
                        "lng" : -79.57494969999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.9 km",
                        "value" : 5892
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 206
                     },
                     "end_location" : {
                        "lat" : 43.617943,
                        "lng" : -79.55246439999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-427 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "g_piGjytdN`@Yn@]|Au@HEj@Uf@QTIVKNEBAv@Wl@S`@MrBo@v@WhM{Dn@SlC{@nBm@jA]~@[pBm@^MRGTIRGRITGRIp@UrBs@r@WxAg@BARITIRIRITIRIx@[~@]TKZMJETIz@_@RIRINGDA\\Ot@[RI|Ao@HCRI`Aa@b@Q@Ax@]fBs@HCfAc@pAk@f@Sd@QXKd@SNGDCRIDANGRIVK\\MXMj@URGTKRIRGPGh@URGRKRGRIRId@QTINGTIRGd@QRITIjAc@~@[NGh@Q^OBARGRIPGRGRIRGRI@?d@Od@QTIPG@?RIbBi@d@Q@?hAa@r@UJCt@WXKh@QFALERGh@Q@ArAa@PGHCJETGRGj@SlA]XKLEXITGj@QRGRGTGrAa@TGTGRGTGBALEl@Qh@MRG@ARE`@KFC~@UHC^Kt@QHATGRGVGh@MjDw@f@Mj@MRGhBc@h@M`AUh@ONEn@Oh@MjBc@rA]rA]tA_@rA]TGfAYdD}@nBi@h@ORGHC`@KhDcArAa@j@OhA]lEsAz@Y~@Yh@QpAc@RGh@QTIRGfBk@RIzBu@|@[RI|Bu@p@Up@W~@[xDsAp@UlC_A^M~@[h@Qh@SPGh@QHC^MVIHCPE^M^Kh@Oh@Q"
                     },
                     "start_location" : {
                        "lat" : 43.6685205,
                        "lng" : -79.57414279999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1317
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 43.6150447,
                        "lng" : -79.5405066
                     },
                     "html_instructions" : "Take the \u003cb\u003eGardiner Expressway\u003c/b\u003e exit on the \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eToronto\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "ccfiGzqpdNHK|@WVGhA[jA[\\If@MVG^KLEREd@MRERETGNC\\KRGx@_@\\QLKZYXYJMLQJMHONW@CDIDGFQHQHUDOFSLi@DQDUBSDS@SBW@QBU?O@Y?i@?k@A]AYCm@Em@CWAIAMCWEWMaAKo@Km@Kk@QiAc@kCc@mC[uBYyBWaCEYEa@QqBU{C?AOS"
                     },
                     "start_location" : {
                        "lat" : 43.617943,
                        "lng" : -79.55246439999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "12.3 km",
                        "value" : 12308
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 526
                     },
                     "end_location" : {
                        "lat" : 43.6378208,
                        "lng" : -79.39862909999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eGardiner Expy E\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "_qeiGdgndNKwAUcCI_AYqCIo@Gu@Q}AQ{AUqBCW[iC}@yHCYE]s@aGOsAo@uFMgAMeA[kCm@eFaAwIg@gEq@cGuIuu@Ky@Iy@mAmKa@kDg@iEk@cF}@{Ha@kDOuAQuAIy@Kw@Ky@Ky@Iw@Kw@Iq@Ky@Kw@Ky@Ky@Kw@Ky@E[E[_@kCQuAE[WqBG[E[E]Kw@Mw@E[E[G]Ig@Ik@Mw@QoAi@mDO{@e@cDa@iCMw@SsAYmBg@gD[qB{@wFE[Mu@cB}KKo@Ks@Im@SmAu@_FOcAQeAU{AqAsIE[G]E[E[G[E[G[G]E[G[G[G[I[GYG[I[Us@IYK[IWKYKWMWWm@O[MUOUMUOUMUOUOSOSOUOSOSOSOSOUOS]e@AC_@g@OSc@m@a@k@Y_@OS_@i@OSOSOS_@i@OSOSOSMSA?OUOSOU{@uA]k@MUOUEKMUMUMWKQACMWKUKUMYKUc@aAWm@Sg@A?KWKWKWKWMWKWMYYm@OWYo@MUMUMWMWMUMUMWKQa@y@w@wAc@y@i@eAm@uAq@eBAE_@gAoAyDo@iBI[c@sA[cAUy@Ww@[kACI_@wA]wAOo@Kc@Ki@UgAOw@Ig@EQMw@Ks@Gc@Kq@Kq@Iw@Ku@Ee@Ge@KeAKcAGu@CWEk@Gq@Ci@Ew@CSCo@Cs@Ci@A_@A]AYA[Ak@Am@?GAo@?Q?a@?o@?[?Y@_A?[@m@?o@B_A?k@DsABcA@KFcBDaABs@Do@Bs@Fu@FgADc@Bg@Fk@HcAH}@Dc@De@P{AB]Fe@Js@D_@L_AF_@XmBDW@ERkA@E@IJg@Fc@Lk@TgAJe@DS@EBK?C@CDQFUDSBIDOH[@GBG@GFWHYTu@Po@@CHWTu@r@uB~@uCz@oCr@wBFQFQPi@Ne@L_@Ro@Ne@HUHWDOFSHSPi@Nc@Nc@La@j@gBh@aBr@wBHU@E\\cADMJ]FQFODQNe@JWRq@@GFQBKBIFYFSBMPy@He@DSBSF[D_@Fa@B[BUDc@Bg@B[@Y@_@@S@S@]?U?Q@M?O?W?WAGAoAAWCu@C[?GCU?AAUIy@E_@MiAMq@Ic@Gc@q@qDUoAoAcHe@eCEUKk@_@sBUoAUiAUqA[eBYwA_@qB[gBg@kCsAqHCQKk@Ki@Ow@G]COq@qDKi@Ms@Ko@EUSeA[eBUmAg@qCQ{@UmAGc@Gc@E[Kw@E]Ee@Ea@C]C_@C]C]?SAUAa@Ce@?i@Ak@?g@?}@?{@?{A?yAAy@Aw@C{A?SC}@Ai@G}AG_BMmCKuBCc@IiBE{@Co@EgAE_AEy@A_@?[Ai@Ag@?O?I?y@?s@?K?K@u@@k@@g@@M@iA@Y@_@@k@@o@BuABkA"
                     },
                     "start_location" : {
                        "lat" : 43.6150447,
                        "lng" : -79.5405066
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 518
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 43.6385577,
                        "lng" : -79.39236409999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e153\u003c/b\u003e toward \u003cb\u003eSpadina Ave\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "k_jiGlprcNJW@A?QDqB?Y?c@Ai@Ce@AYC_@MuAOuAGq@?EGi@CUCYGo@Ee@AIE]ASEa@I{@Go@?CAKAICWAGAWAICSCUCWE]AOIm@Ig@"
                     },
                     "start_location" : {
                        "lat" : 43.6378208,
                        "lng" : -79.39862909999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 242
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 73
                     },
                     "end_location" : {
                        "lat" : 43.6405651,
                        "lng" : -79.3928444
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSpadina Ave.\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_djiGfiqcNE[CK}@Zi@NUHm@NA?_@HC@k@LK@E?G?y@TSDa@H"
                     },
                     "start_location" : {
                        "lat" : 43.6385577,
                        "lng" : -79.39236409999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 565
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 140
                     },
                     "end_location" : {
                        "lat" : 43.641677,
                        "lng" : -79.38665709999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBremner Blvd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qpjiGflqcNG]EWAKEWKy@AU?I?I?G?I@K?I@SHY@MJgAJsAJqADc@Da@De@BS?G?E@G@M?K?E?O@K?EAM?E?CAM?SCSE]COAEAEAGAEAGAGEMGUCEAGCEEKCICGGKEIAECCGGe@m@c@g@CEAACCA?C?A?MOS[MQIKIMEICC"
                     },
                     "start_location" : {
                        "lat" : 43.6405651,
                        "lng" : -79.3928444
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "au{kGtvfdNMrCF`Cx@jDbC`HfA|JlLcC|Ce@hDa@rBMjFq@R~Ah@zD`@|ChBzM`DvTxCnJhE|JrBxGvB|KxEff@HrEIbGGtLl@xIvMtw@nFx`@rEfb@fL|s@fIzh@bGtb@xKdx@rCrV~A`RlAnKfBvM?~AQrAWd@}@d@aA@gAu@i@}A?yBRm@x@u@fC}@~B{@vJwAxF_AxBi@hCa@vEy@jX_FdSqDvQiDl_@qIfYeHx^sItIuBjBm@tD{@lEw@xHiAl^mFl}@{MdqAsRztB_[to@sJ~i@sHl_B{UdMsBbOgCrYiEpMoBfXkDfIoAfzAuThl@wIheBgW|a@qGff@iHb]yEvIs@d[uA`Nm@hEShDO\\V\\?fBAfHC`ADbCn@pFpEv@Nn@KvAi@TMSaAQiAUeBeAaNyAwQOoAPULQ~C}@|BPZC@Z@x@?t@@nCR~B~@`Dt@|Ap@~@dAkBLiBIo@y@wAcAwAMoAPmABsC@_F@w@?XGdDFrEWz@?rAl@pAbAxA`@xAMhBeAjBrAhA|Av@vDBrBQhB?nCArBm@xA}@nAWXDZnC\\tC`ArIUpAgF~@OAe@wBQuBJkAp@}@bEs@fCWZg@dNm@nKq@lJkArl@wIph@{Hju@}KfZaElOwBbBG~B]|IwA`HkArUuDjq@}Jla@cGdbA}Ndt@qKb`B_VxIqAnRcDfDiAhO}IpFsC~AUtA`@tAfBh@~BThBt@|JrA`OjI~l@fInj@dB`Sv@bGbCzK~DxSbA`GxAhFtAhDbDfFlCvC~IlHd@CjB~A~BpBzEbEbEnDxAzAnBbBdH`G`KtIhT`RvJvH~HtE`KdF|[bPtCrAxAn@~BvAzC|AxBlA|ObJ~D`C`GtCrAZhDVxF{@fDcBjCcCjCqDpDeFrDgErC_CxGeD`h@ePbS{Gdd@uQbX_K|[sK~YqI~VcGbe@cMl^iLl]oLxDqAhIwBtD}@hCeAnAmAhAoB~@qDRqCSkGoAsI}BiOu@oHe@qDeAmLiDmZyX_cC}Igv@_EoZ_Kyp@gK{q@{@aFyAoFyBuE}BgDoIkLiH_L}EyKsHcOmD{HaDqJwDsM{BoKuAgK}@eK[qHCaO`@iNt@}KtCcUxBeKlRcm@fEwM`A_Fd@uFHkDMyF{@gHwFe[yKam@yCoPuAiJYgFEsM]gO}@eSK{GHmHFuCT{DAkHaBmQcAmJaAN_AXsAZeANmAZa@HG]Gc@QqAAq@f@wFd@}Ho@cEe@cAaBiBoAeB"
         },
         "summary" : "ON-400 S",
         "warnings" : [],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}

```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
