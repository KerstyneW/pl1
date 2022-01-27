# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?
origin=place_id:ChIJrRDzO2Boj1QRNCdIenv189M
&destination=place_id:ChIJvwNEBzMEj1QRgCfJl89AmXw
&avoid=highways
&departure_time=1662031800
&traffic_model=pessimistic
&waypoints=optimize:true
%7Cplace_id:ChIJ8eXQX-Vzj1QRW5LX2X9MTE4
%7Cplace_id:ChIJ2y_IbAUNj1QRuJsFm13ExgI
%7Cplace_id:ChIJswQ27UcNj1QRF0XmYCSzeS4
&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJrRDzO2Boj1QRNCdIenv189M",
         "types" : [ "airport", "establishment", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ8eXQX-Vzj1QRW5LX2X9MTE4",
         "types" : [ "premise" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJswQ27UcNj1QRF0XmYCSzeS4",
         "types" : [
            "establishment",
            "food",
            "meal_takeaway",
            "point_of_interest",
            "restaurant"
         ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ2y_IbAUNj1QRuJsFm13ExgI",
         "types" : [ "establishment", "gas_station", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJvwNEBzMEj1QRgCfJl89AmXw",
         "types" : [ "establishment", "point_of_interest" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 48.6402525,
               "lng" : -123.3315209
            },
            "southwest" : {
               "lat" : 48.3407024,
               "lng" : -123.7114569
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "26.2 km",
                  "value" : 26203
               },
               "duration" : {
                  "text" : "31 mins",
                  "value" : 1835
               },
               "end_address" : "1680 Poplar Ave, Victoria, BC V8P 4K7, Canada",
               "end_location" : {
                  "lat" : 48.4595991,
                  "lng" : -123.3315396
               },
               "start_address" : "Victoria International Airport (YYJ), 1640 Electra Blvd, Sidney, BC V8L 5V4, Canada",
               "start_location" : {
                  "lat" : 48.63753029999999,
                  "lng" : -123.4293467
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 144
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 48.6388094,
                        "lng" : -123.4290405
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e on \u003cb\u003eElectra Blvd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qozgHlhjpV_G}@"
                     },
                     "start_location" : {
                        "lat" : 48.63753029999999,
                        "lng" : -123.4293467
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 643
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 194
                     },
                     "end_location" : {
                        "lat" : 48.6378399,
                        "lng" : -123.4330695
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eElectra Blvd\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "qwzgHnfjpV_@Gm@KIA{@Mk@KC?EAC?A?C@C@C@EBCBCDCFELADCHATa@vHIdBGx@@N@F@F?D@D@DBD@B@B@BBB@@BBD@BBB?FBTBTD`@FTDNBNDPBD@HBHDLD@?LFPJJDFBJBrAt@HDhAn@TP"
                     },
                     "start_location" : {
                        "lat" : 48.6388094,
                        "lng" : -123.4290405
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1033
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 78
                     },
                     "end_location" : {
                        "lat" : 48.6351802,
                        "lng" : -123.4206103
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit onto \u003cb\u003eWillingdon Rd\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "oqzgHt_kpVDBBD@FBJ@H@@BDBBB@F@@?BA@?@A@?BA@A@C@A@C@A?C@A@C?C?C@C?C?C?C?CAC?C?C?Y@g@Dg@@}@?a@?a@?c@Aa@A[A_@A[?WAO@O?Q@KBWBK@I@IBGFQFQJSFOFIDOFUHa@`@mBTmARgAPgAPu@Z_BNs@P}@Li@He@RaAVoAVkAHe@Je@F_@Hg@Fa@Fi@Hk@Dg@Dg@BYB[Ba@@_@B_@@_@@Y?Y@c@?i@?YA[?_@@Y?Y?S?K?K@SBQ"
                     },
                     "start_location" : {
                        "lat" : 48.6378399,
                        "lng" : -123.4330695
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 460
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 34
                     },
                     "end_location" : {
                        "lat" : 48.63299319999999,
                        "lng" : -123.4157589
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit and stay on \u003cb\u003eWillingdon Rd\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "{`zgHxqhpV@??A@??A@??A@A@A@A@C?A@C?A@C?A?C?C@C?A?CAC?A?C?CAA?CAAAC?AAAACAMAI@K?I?K@I?I?E?KFq@BYD]D]F[Hc@DSDSJc@J_@J[L[HUBGDMXo@^m@j@w@\\a@Za@RWr@y@l@u@Z]"
                     },
                     "start_location" : {
                        "lat" : 48.6351802,
                        "lng" : -123.4206103
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 307
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 48.6308867,
                        "lng" : -123.4131816
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eCanora Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "esygHnsgpVhBmBbBkBNQHIJ?dAeALSJQJSHUDQ@CDWDUDMDKDGDCDEFG"
                     },
                     "start_location" : {
                        "lat" : 48.63299319999999,
                        "lng" : -123.4157589
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 419
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 48.6274396,
                        "lng" : -123.4115074
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit onto the \u003cb\u003eBC-17 S\u003c/b\u003e ramp to \u003cb\u003eVictoria\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "afygHjcgpV@?@?@?HIBC@ABE@ABE@CBG@UFIDEBEBCFEHGLQLMBCNILELEVCh@@X?B?b@?VAl@E~@Of@Ij@Qv@Yx@a@`@SRKNY"
                     },
                     "start_location" : {
                        "lat" : 48.6308867,
                        "lng" : -123.4131816
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "17.9 km",
                        "value" : 17917
                     },
                     "duration" : {
                        "text" : "14 mins",
                        "value" : 818
                     },
                     "end_location" : {
                        "lat" : 48.471512,
                        "lng" : -123.3827426
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eBC-17\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "opxgH|xfpVrB{@jAg@x@]HEbBs@@?hBu@|@_@`Aa@rD{AlDyAf@SbAe@z@]n@[x@c@jAo@r@g@h@]rAaAbBmAdBoAhBqAl@c@`BkAlCoBnA_A|@o@jAw@|C_CrDkCr@g@|BcBl@c@~L_J~EoDzBaBrF_EnBuAl@c@|@m@z@c@dAe@\\Kd@M^Ib@E^Ct@Bl@Al@?l@@j@@l@@fA@j@@R@n@@l@@V@R?@?l@@j@@fAB`ABp@@nBDl@@n@@j@@n@@h@@n@Bl@@l@@l@@j@BZ?R@j@DV@VDh@DVDVD@?j@L`AT`AXl@Tt@ZdAZ^NPFPJjDrAXJ^NPF~@^pB|@dAV`A^bA`@rHtChDpAD@pCfAlBl@f@L`@JPB\\Fn@H\\DPBXBV?TBF?N@Z?\\?`@?X?T?b@Cr@Ej@GZEPEZEj@M|@SzAc@rAa@lA_@RGz@Wn@SxBs@lBk@~E}AzC}@t@UrBo@rBo@b@MdCu@PGRGBAZKh@MTIVGTEPCPEXATAj@AZAT?XBh@DbALvAR~ATrARjBTt@B\\DZDn@NhBNXBtBTbALp@F|@Jh@Fp@Hj@F|@Hn@Bh@@j@@j@?j@Cd@C^Cl@GVC\\GDANCd@Kj@Kj@Mt@Yj@Wr@]\\Qb@Uz@k@XSj@_@`A[NIh@_@f@W|@e@n@a@`B}@lAo@JGz@c@|@c@n@[v@a@l@[j@YDC`@SVKTKt@[\\M^OVKh@UZKn@Sf@QRGDANEh@OJC^Ih@O^K`@KTGVETGj@Kl@Mj@Mh@Mn@Kj@Mn@MZG^Gn@MZG~@Ql@Kp@IlASf@GVCfAKvAOv@GJAp@Gj@EvAQ\\Ch@EPCVCVCxAMj@EXCf@GfAMj@IRCn@IZENCl@In@K^G^El@KZEPCl@Ih@Gl@I|@MDAdBUj@I\\Il@Kl@ORGZId@MVGPGZGPGVId@KZITGTGTGVGn@OPEVEj@KVEPC`@G`@E~@KF?tAKl@CbAGj@EVCpBOj@El@Gl@EVCVEn@Il@Eh@E@?bAKVAd@Et@Kx@It@Ml@If@Gl@KbAOTEp@MjBWrBYb@Gb@GPCZEdAQd@GXEh@IZEh@Gj@Gn@Ej@Cb@Cb@El@Gl@Ij@Ih@MzA_@dCm@ZIVGf@MXGj@On@OFA`@KXGHADA\\GREVETCTCTCXCRCTAV?JAJ?T?@?T?T?l@@Z@x@Bl@@\\?NAXARA`@Ab@EXCj@In@Kb@KTG`@GVGf@IbASl@Mj@K^INAPCZGFARCNAPCXEVEB?VEJAVCf@Gd@GbAMt@Ir@KdBQd@GVETCfAMrBWn@KbFq@bFq@`AMr@Gt@MRCx@MdDc@z@Mb@GTClAOhAMf@?nACZB`@@nAJbBRH@`BRb@DfCZh@FzARp@HnCZ^D@@fD^JB`@DtAPx@Hb@FlCZf@FlCZtAJtBHxAKbG[pAGt@EbAAR?B?l@?`ADZBTBl@Fl@JfARh@NdAVRFjCv@bAZPDxBp@F@~@Vr@Rr@Lh@Fl@Bb@?`@Ah@G@?h@K|@W^KBAlDkA`Cw@`Cy@fC{@rBq@d@Op@Qd@KRC`@G`@E`@Al@?t@D^B^F^JfAZdAb@lAj@vCxAtCtAvAp@l@X~@`@f@Rp@Pj@J\\Bj@BX@Z?l@Cx@MfAYdCs@fAYfA_@nE{AlAc@tKuDnDmAd@Q`@OpC_AvBu@vBq@rAa@pA_@nA]|Aa@"
                     },
                     "start_location" : {
                        "lat" : 48.6274396,
                        "lng" : -123.4115074
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 283
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 48.4689708,
                        "lng" : -123.3825749
                     },
                     "html_instructions" : "Take exit \u003cb\u003e7\u003c/b\u003e for \u003cb\u003eMcKenzie Ave\u003c/b\u003e toward \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-1\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eNanaimo\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-14\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSooke\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "}azfHbeapVTFlAIPAfAEfBIfACjAEXAf@A"
                     },
                     "start_location" : {
                        "lat" : 48.471512,
                        "lng" : -123.3827426
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 130
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 48.4678317,
                        "lng" : -123.3822249
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork, follow signs for \u003cb\u003eMcKenzie Ave E\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "aryfH`dapVLCXCJALCp@KFA`@KJCx@Y"
                     },
                     "start_location" : {
                        "lat" : 48.4689708,
                        "lng" : -123.3825749
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1884
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 233
                     },
                     "end_location" : {
                        "lat" : 48.47094209999999,
                        "lng" : -123.3573715
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMcKenzie Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}jyfHzaapV^MOeAK_AKcAKaAKeASyCQuCMeBC_@Is@Gu@Gs@KuAEg@Ic@Eq@Es@Gu@S_DEm@?GMiBKiBMkBCYg@_II}AGu@Es@G{@[aFKkBG}@Eq@Gw@ASAOEu@Gu@Cc@GeA@e@O}CCw@MqBMoBIwAKaBKyAI{AUeD?a@UkAGq@IsAIqAMmB_@sGQwA"
                     },
                     "start_location" : {
                        "lat" : 48.4678317,
                        "lng" : -123.3822249
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1788
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 184
                     },
                     "end_location" : {
                        "lat" : 48.4626572,
                        "lng" : -123.3370214
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCedar Hill Cross Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k~yfHpf|oV~@u@`@o@Xa@t@mBh@uATi@hCoG|@}B|@wBh@uAr@mBRm@b@aATm@jA_Dv@}Bv@kDV{@pA{Eb@}AlAgEVwAJq@ZcBN{@|@sCx@iC~A_Dx@wANc@FYDWDa@Bc@HoC@K@i@@]Ba@D_@D]BUF[HWLm@RqALm@Jo@~@wD"
                     },
                     "start_location" : {
                        "lat" : 48.47094209999999,
                        "lng" : -123.3573715
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 492
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 47
                     },
                     "end_location" : {
                        "lat" : 48.4584374,
                        "lng" : -123.3388477
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCedar Hill Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sjxfHjgxoVnCdB`BdAf@\\nDr@b@HnDp@b@JhCf@"
                     },
                     "start_location" : {
                        "lat" : 48.4626572,
                        "lng" : -123.3370214
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 535
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 82
                     },
                     "end_location" : {
                        "lat" : 48.4586151,
                        "lng" : -123.3316344
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003ePear St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gpwfHxrxoV?q@?{JAcD@cCCoGCwC@g@?eAAu@?KAe@Ge@Qi@"
                     },
                     "start_location" : {
                        "lat" : 48.4584374,
                        "lng" : -123.3388477
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "27 m",
                        "value" : 27
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 48.45876879999999,
                        "lng" : -123.3313427
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003ePoplar Ave\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "kqwfHtewoV]y@"
                     },
                     "start_location" : {
                        "lat" : 48.4586151,
                        "lng" : -123.3316344
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 141
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 48.4595991,
                        "lng" : -123.3315396
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "irwfHzcwoVYb@IjA{@?u@?IIE}@"
                     },
                     "start_location" : {
                        "lat" : 48.45876879999999,
                        "lng" : -123.3313427
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "18.0 km",
                  "value" : 18048
               },
               "duration" : {
                  "text" : "32 mins",
                  "value" : 1931
               },
               "end_address" : "2401Millstream Rd, Unit 101-B, Victoria, BC V9B 3R5, Canada",
               "end_location" : {
                  "lat" : 48.4636194,
                  "lng" : -123.497373
               },
               "start_address" : "1680 Poplar Ave, Victoria, BC V8P 4K7, Canada",
               "start_location" : {
                  "lat" : 48.4595991,
                  "lng" : -123.3315396
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 141
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 48.45876879999999,
                        "lng" : -123.3313427
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e toward \u003cb\u003ePear St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "owwfHbewoVD|@HHt@?z@?HkAXc@"
                     },
                     "start_location" : {
                        "lat" : 48.4595991,
                        "lng" : -123.3315396
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 563
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 128
                     },
                     "end_location" : {
                        "lat" : 48.4584374,
                        "lng" : -123.3388477
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePear St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "irwfHzcwoV\\x@Ph@Fd@@d@?J@t@?dAAf@BvCBnGAbC@bD?zJ?p@"
                     },
                     "start_location" : {
                        "lat" : 48.45876879999999,
                        "lng" : -123.3313427
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1163
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 132
                     },
                     "end_location" : {
                        "lat" : 48.4685839,
                        "lng" : -123.3353241
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCedar Hill Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gpwfHxrxoViCg@c@KoDq@c@IoDs@g@]aBeAoCeBo@USK_@Qc@MOGu@MC?yA[gAO{AUcBWaC[KC_Ca@qAUiBYqA[oAS"
                     },
                     "start_location" : {
                        "lat" : 48.4584374,
                        "lng" : -123.3388477
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.5 km",
                        "value" : 5462
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 523
                     },
                     "end_location" : {
                        "lat" : 48.461322,
                        "lng" : -123.4030912
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMcKenzie Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "soyfHv|woVSAHv@?fGAjB?v@AtA?vD?vB?n@AVAVAVCRCXCPGZGTI\\M\\MVMTg@r@Y^u@dAW\\{ArBaAtAgBdCMPIPINO\\O`@IZGVIZIb@Gb@E^Gb@I|@]vD]fDGf@C`@AZA`@A^@`@@x@Bd@D`ANnCRpDZzEN`CNnBLhBPpBNhBHr@Jz@V|AD\\DRDXFl@B`@LzAPvA^rGLlBHpAHrAFp@@nA@b@JdBLjADbAJbBH`BHfANjCXtEJbBJb@FdABb@Ft@Dt@@N@RFv@Dp@F|@JjBZ`FFz@Dr@Ft@H|Af@~HBXLjBJhBLhB?FDl@R~CFt@Dr@Dp@Ad@Dj@FdAHnBFrAB`@FrANpBDpAF|@Fv@Hv@Ft@TnBTjBTjBDZTfBLlA@Rb@pEJjBP~CRrDHxAHhAHhAP`C^fFNxCD|@Br@BrA@X?FDzBBdBBdADzBBfBJvA?FFd@Fh@NpAVtAPt@Pj@Vx@DLJVf@dAR\\`@t@v@tADF@Bn@hADHDHBBNVjArBrA|BPZT\\Z`@FHJHLZBBDFh@f@^\\lAhAPPf@b@j@j@j@t@^`@X\\@@"
                     },
                     "start_location" : {
                        "lat" : 48.4685839,
                        "lng" : -123.3353241
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
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 48.4592053,
                        "lng" : -123.406148
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eMcKenzie Ave\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "gbxfHhdepVLHFFLJJJ@BTVBDPRJJFF?@PXNV@BB@BFTd@^r@BFLVNZDLTd@@BFPPVFJHLFLHLFFRVFHPZBDBFFLL\\"
                     },
                     "start_location" : {
                        "lat" : 48.461322,
                        "lng" : -123.4030912
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1635
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 147
                     },
                     "end_location" : {
                        "lat" : 48.4513055,
                        "lng" : -123.4244691
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAdmirals Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "auwfHlwepVLd@Nn@BHFTJTPfAFp@@@Fp@@@PdBd@tCLv@XvAh@rCTl@Rj@HTFNBBd@`AHNl@pALVdAxBzA~Cv@vBDXTfBHp@J~@Ff@Jr@X~BBTBPJj@BLFTFRHXDJ@BFNHPJTJVNZ^z@l@pAzAfD`AvBP^v@fB\\r@l@rAb@`AXt@Vh@dAzBJRdAzBVf@Vh@R`@\\j@Xb@"
                     },
                     "start_location" : {
                        "lat" : 48.4592053,
                        "lng" : -123.406148
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.6 km",
                        "value" : 4609
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 426
                     },
                     "end_location" : {
                        "lat" : 48.445426,
                        "lng" : -123.4670051
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eIsland Hwy\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ucvfH|iipVBr@ATIz@W`@e@t@W`@SJABq@x@_@z@CJE\\Kr@Il@AJCt@UvGK`DCt@G|BAnA?V?N@F?D@`BBp@DdBJtBJlB?^?F?TCf@Gn@Q|@o@dCWz@K\\u@hCa@tAUz@_@dAUn@Uj@{@jB}@fB]p@e@r@w@`Ag@l@OVa@v@QXIPg@z@c@bAg@pAYn@O^EHKVIPWh@O\\EJA@UXW\\a@\\_@NQCM@a@NIBMHkAr@e@h@SVORW`@O\\]t@Wr@IREVC`@CHYlAK`@CTCb@?JAX@v@?b@@d@BvA@X@n@G|@Ef@Il@Ml@?BQn@UbA_@nCa@|CU~AKz@QdASfBCVOdBEz@Ct@Al@?j@j@`AZl@Vn@l@xA|@vBVVNb@\\z@DLHRLP@BFLh@v@LPHLRRZVRNJF\\R`Br@x@Zd@LRRd@J`@Nr@RNF\\LJLHLFDTPLF@?HFLLJN^r@Zj@Td@\\RJRn@hAd@r@l@t@t@x@bA|@DB~AfA^f@d@b@h@\\~A`A\\R|@h@v@b@NJ`Ah@t@^p@^D@Z?fD`BZPTJl@Vv@ZJDl@VhAd@h@RRHRHv@^z@X@@HV`Bp@`Bl@|@\\r@VPFp@Z"
                     },
                     "start_location" : {
                        "lat" : 48.4513055,
                        "lng" : -123.4244691
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 701
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 74
                     },
                     "end_location" : {
                        "lat" : 48.4442605,
                        "lng" : -123.4761941
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eNob Hill Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWale Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Wale Rd\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}~tfHxsqpVFTBRBPBRBTQj@?DADGVCLAJCTJfBLbBVbD?FD^BPDn@LnAlAtMV|CFt@V|C@JJ|ALrADT"
                     },
                     "start_location" : {
                        "lat" : 48.445426,
                        "lng" : -123.4670051
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1446
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 137
                     },
                     "end_location" : {
                        "lat" : 48.4472695,
                        "lng" : -123.495126
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGoldstream Ave\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "swtfHdmspVBl@W|C_BbHk@bC_@rE_@lEa@dFw@fIu@zH[~CMfBGbACr@?HAb@?@IxFMtEGhCCfAKlBE~@K|ACXCTIv@a@rCWnBSdAOz@"
                     },
                     "start_location" : {
                        "lat" : 48.4442605,
                        "lng" : -123.4761941
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1292
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 170
                     },
                     "end_location" : {
                        "lat" : 48.45850069999999,
                        "lng" : -123.4974688
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVeterans Memorial Pkwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-14 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow BC-14 E\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mjufHpcwpVG^KXGNUGqBg@_BQuBKSCeBDkBDgETqFCkDb@k@L_@HiAb@MBIDc@Tc@R_@PeAh@uAp@{Ar@SFWHiA\\{@VC@cANoB\\u@HYBw@@"
                     },
                     "start_location" : {
                        "lat" : 48.4472695,
                        "lng" : -123.495126
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 567
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 76
                     },
                     "end_location" : {
                        "lat" : 48.4633501,
                        "lng" : -123.4989738
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eMillstream Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "spwfHdrwpVS@O@QAC?eB[SEUA{@KoBC_ATg@Tc@Xk@^q@^c@Z]N}@d@QLULc@NEBaAZi@PIHINWL"
                     },
                     "start_location" : {
                        "lat" : 48.45850069999999,
                        "lng" : -123.4974688
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "63 m",
                        "value" : 63
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 48.46358009999999,
                        "lng" : -123.4981906
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}nxfHp{wpVOw@Oq@Mq@"
                     },
                     "start_location" : {
                        "lat" : 48.4633501,
                        "lng" : -123.4989738
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "22 m",
                        "value" : 22
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 48.4634079,
                        "lng" : -123.4980559
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kpxfHtvwpV`@Y"
                     },
                     "start_location" : {
                        "lat" : 48.46358009999999,
                        "lng" : -123.4981906
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "56 m",
                        "value" : 56
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 48.4636194,
                        "lng" : -123.497373
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ioxfHzuwpV]kBK]"
                     },
                     "start_location" : {
                        "lat" : 48.4634079,
                        "lng" : -123.4980559
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "3.5 km",
                  "value" : 3549
               },
               "duration" : {
                  "text" : "8 mins",
                  "value" : 490
               },
               "end_address" : "2978 Jacklin Rd, Victoria, BC V9B 0A3, Canada",
               "end_location" : {
                  "lat" : 48.4418219,
                  "lng" : -123.5108212
               },
               "start_address" : "2401Millstream Rd, Unit 101-B, Victoria, BC V9B 3R5, Canada",
               "start_location" : {
                  "lat" : 48.4636194,
                  "lng" : -123.497373
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "56 m",
                        "value" : 56
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 48.4634079,
                        "lng" : -123.4980559
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e",
                     "polyline" : {
                        "points" : "spxfHpqwpVJ\\\\jB"
                     },
                     "start_location" : {
                        "lat" : 48.4636194,
                        "lng" : -123.497373
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "22 m",
                        "value" : 22
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 48.46358009999999,
                        "lng" : -123.4981906
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eMillstream Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ioxfHzuwpVa@X"
                     },
                     "start_location" : {
                        "lat" : 48.4634079,
                        "lng" : -123.4980559
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "63 m",
                        "value" : 63
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 48.4633501,
                        "lng" : -123.4989738
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eMillstream Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kpxfHtvwpVLp@Np@Nv@"
                     },
                     "start_location" : {
                        "lat" : 48.46358009999999,
                        "lng" : -123.4981906
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 780
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 120
                     },
                     "end_location" : {
                        "lat" : 48.4565634,
                        "lng" : -123.497223
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMillstream Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}nxfHp{wpVVMNBFArAa@VKfAc@FE~A_ANK~@g@p@a@jAi@z@Ql@Cz@?`@Dl@JpAVb@BZ@`@?nACz@KB?~@SFAd@I^At@Ot@Q"
                     },
                     "start_location" : {
                        "lat" : 48.4633501,
                        "lng" : -123.4989738
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1851
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 187
                     },
                     "end_location" : {
                        "lat" : 48.44176179999999,
                        "lng" : -123.5018812
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eVeterans Memorial Pkwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-14 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "odwfHrpwpV|@[h@Sp@UZKl@Yb@Sb@UtAu@NIh@SnBu@hBi@pC[lAEzE@vCSp@ErCCTAbCLr@Pr@Lj@J|@TZJPFXJrAd@nCnAtBz@dBx@v@^r@d@n@j@x@~@Xd@RXd@bALZRh@Rl@j@fB^nA~@tC`AxB|@~A"
                     },
                     "start_location" : {
                        "lat" : 48.4565634,
                        "lng" : -123.497223
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 647
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 48.4429154,
                        "lng" : -123.5101984
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLangford Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_htfHvmxpVDr@?^AHCd@Qn@Ot@WvAo@lDSbAm@|DKr@?@e@tCYdBK|@C\\AJAJ?V?V@T@TBV@DDTNx@BR@LBd@?@Al@?FAfA?n@Ad@"
                     },
                     "start_location" : {
                        "lat" : 48.44176179999999,
                        "lng" : -123.5018812
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 130
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 48.4418219,
                        "lng" : -123.5108212
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eJacklin Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gotfHvazpVNJz@d@nAh@j@TRH"
                     },
                     "start_location" : {
                        "lat" : 48.4429154,
                        "lng" : -123.5101984
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "29.0 km",
                  "value" : 28996
               },
               "duration" : {
                  "text" : "35 mins",
                  "value" : 2101
               },
               "end_address" : "Juan de Fuca, BC V9Z 1L8, Canada",
               "end_location" : {
                  "lat" : 48.3407024,
                  "lng" : -123.708541
               },
               "start_address" : "2978 Jacklin Rd, Victoria, BC V9B 0A3, Canada",
               "start_location" : {
                  "lat" : 48.4418219,
                  "lng" : -123.5108212
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 934
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 114
                     },
                     "end_location" : {
                        "lat" : 48.433951,
                        "lng" : -123.51522
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eJacklin Rd\u003c/b\u003e toward \u003cb\u003eRex Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "khtfHrezpVl@Vb@Vj@PnDzA|BhA`FdCfD`BdAf@^Nd@Rf@Tb@RVLpB|@v@\\`Br@`@RXL`Af@dAf@`@PLF"
                     },
                     "start_location" : {
                        "lat" : 48.4418219,
                        "lng" : -123.5108212
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "12.2 km",
                        "value" : 12155
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 726
                     },
                     "end_location" : {
                        "lat" : 48.39357709999999,
                        "lng" : -123.6290527
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eJuan De Fuca Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSooke Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-14 W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ewrfHba{pVMnACV?VA\\@|@@R@PBP@HBLBNDPXr@PRj@hBH^@@Fb@P`BDj@D^@PDTXbBLp@v@fEBr@@N?H@b@?F?ZAnACxACz@CZI^Gr@ARMxBEb@i@hBQf@Yt@Un@]hAC^Cf@A`@?J@JBRBRDVFVRp@JJl@nBvA`Ff@jBz@hDjClKvAzFb@fBTr@X~@vApFFVh@tB@FFP@Ph@tBXxAHf@D\\@HJv@LhA@t@@t@@pA?jA?j@AbAAn@Ad@?VAH?d@?`@?J?D@^@N?BBTFh@BLHVFP?@JTJPNTVXn@h@LJr@b@vAr@lBhARFBBZVNP\\z@@BbAxDb@~ANl@p@fCDL@PPj@Vt@X`AjDrMPt@Pn@Nn@Pj@@F@DlC~Kl@fCBLJ`@FTFd@F\\@JLlA?XDzB?NKxAAJGb@EVENMn@CHCNITCHA@[dAq@|AEJM\\A@[t@O\\qBpEiAdC]v@c@fASh@Ur@_@lAc@lDKvB[tFIlCSnD?^MdD?z@Bp@Dr@Hx@@FJp@BF`@tAZ~@DJb@x@^j@R\\DFjApB@@Vb@r@jA?@Vb@@@nBpETh@Vj@Tf@@@j@pA?@Tf@@@lBjE@B`BvCVd@p@nAdBxC@BT`@BBbBxCT`@@?\\f@`@n@f@p@^b@NPLJBBZV`@^`Ax@fAdAl@p@^r@d@`AzA~CP\\r@zAh@fANZFJBHZn@^n@HJDHBDv@dATRf@d@t@f@z@d@z@\\NB`@Jx@R`@FRGTDrARj@Jp@J`@BtADR?vAFX?H@`DH`@Ab@CPA@ARCp@Q^Mb@O\\MDA`@M`@Kd@MbAYREf@Mn@WNGHEVOv@m@d@]TOHGTMJERKpAc@DA|@e@ZQBCNGr@[BC^I`@Mb@MxAa@NC`@Gb@Ib@EFAbAIbAGL?TA^CbA?F?z@B`@Dn@DL@lANzAR\\DZHFB`@NZPVRJJZ\\P\\DJHTNf@fCnMBTBVDr@@d@?\\C|C?rA?rADn@Bb@LdAVjAFPRn@LZXl@\\l@BBh@x@XZ~@`Af@h@TP\\VPFNDB@^FD@P@l@D@?J@TDNDRF@@zBdAfBx@D@JHRLJJPPDDP^R\\t@xATh@Vf@P`@BHL^BLPl@Pn@BHLd@`@|APn@j@tB@TZlADNTv@Lr@FTBVJ|A@|@@b@?X?ZAP@J@FARCJOrCCd@ANGjAA`BAjA?RCzAANM|B?j@ChACVALIh@IZM\\_@x@_@n@IN[b@k@t@UXY^Wf@ELENUv@a@pBQl@CFQ`@]j@CBq@n@EDa@T_@V]Rm@b@i@n@EDw@`Ac@h@QZWd@A@Up@Kl@Il@EpAGzAGv@Gf@ETYjAWfAMl@Mp@On@Gh@?JChAA`@At@AjAA~B?JAv@@r@?DBp@Df@N|@|@|FbArG`@hCTx@@@Tj@Vb@@@Z^r@z@b@r@Rb@Lf@?DDT@\\@b@Az@E`AEt@ATC\\Et@Gt@Er@AVAx@BXBVFXDNJ\\FPLXLVHNXb@?@VXDBZVdAf@LFRJ`@R|@b@`Ap@NLR^TXHPFPHZ@FF`@@FBf@ALAd@CL?FId@"
                     },
                     "start_location" : {
                        "lat" : 48.433951,
                        "lng" : -123.51522
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.6 km",
                        "value" : 5574
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 402
                     },
                     "end_location" : {
                        "lat" : 48.35418929999999,
                        "lng" : -123.6420413
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGillespie Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{zjfHphqqVPFJBHBDDBDDF@J@J?L?B?LAPCLADABIXEPAFERETAR?R?L?JBXBLHr@DPLt@Z~ATf@RR@@LJLDX@J?PCPGZOt@s@JI^Y\\[TQHG^W^Y@A^OFC\\E\\Bh@Db@D`@Db@DfAJb@Bb@DL@TBb@BV@J@b@BD@ZBb@FT@LDHBVJB@\\RRLJH\\XDDXTHHTNFDXF`@J`@J@@PBNB@?R?LC@?PKJMDEL[@GFSBY?E?S?a@AK?U@S?ABYBW?ALc@BGJONSBEHGNK@?`@O`@M`@ORILEdA]`@OHEVGPGPCPEZEfAOf@I`AQ`@KREHC^Qf@a@RMTOVIPCt@?X?hBB`@ALCTEJCz@Wj@S`@Q|@]DC`@Q^O@Ab@O`@Q`@OHEVIj@S\\IZCd@AP?P?F@V?B@RDNFBBNLFJBDFLFV?@BX@V?@ATE\\?@Mp@ENG`@EVAR?F?P@X@HBJFXBHRj@DLL^Pb@BFJTJPBDHLJL\\`@NRJJZ^HJRTRVDHT`@BDf@bA\\t@JXHPTh@@DHTDRFXDb@BND^FP@@FLFFDDD@NDHAF?JANEFC`@O^Q@?VQNQHMDMBIH_@@ENq@DOFODK@AFIHGFC@ALCNAD?T?L@X@H@RBN@HBVF@@VDHAF?NCJCFCVS@A\\YPOLEBCTAF@D?LHHFBBZ^@@Z\\HJPR\\\\HHRTZ\\BBXXZXBBNHLF@?H@T?JAFCRKJKBCNUHO`@u@Tc@@AT]Za@DCLIRIDAZC\\AD?NAPG@ALMJSBCRe@@EPWNSTKLCR?@?b@Dh@LZPRXBFLZFNFT`@p@JLRND@^TZHNDZD`@FPBN@d@@b@@b@?H?N@H@L@TD`@HzAVN@b@F`@Fb@Db@FRBN@b@FN@R@J@T@b@Bb@BtAFT?X@HAVCPERIf@]HGVKDCZEB?^?J@V@b@BjAHNFJJ@DNTHNVb@?BTj@?@b@xATv@Ld@b@|A@BLj@Nn@@FJj@Fb@BLHr@DTFZJp@Lr@BLd@zCZzBJ\\FNJNb@`@j@\\`@T~@j@FBx@h@^T`Al@@@\\X\\XPNJL\\^DHRZVd@JPLRVf@HN"
                     },
                     "start_location" : {
                        "lat" : 48.39357709999999,
                        "lng" : -123.6290527
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "9.6 km",
                        "value" : 9592
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 771
                     },
                     "end_location" : {
                        "lat" : 48.345814,
                        "lng" : -123.7106206
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eEast Sooke Road\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "udcfHvysqVg@rAABUh@EHSZQTi@b@C@]Ts@b@m@VOFSFcA\\c@LcA\\E@oAf@OFA@_@V_@V]Z]Z_@ZQNGHEHETCR?@CL?L?N@HN`AFr@@b@Ev@ALOdAc@dCMp@UnAKp@GXCVIf@?JGt@?DAn@?d@Jp@Jr@F^BPDRZjA@BL^DFZr@HNPRJH`@VTPFHFHFJHVBP@P?H?@AVANI\\KVO^GHYj@U^?@Yt@Md@AFMz@Cb@CZAVCt@Ct@?BCp@?B@f@Bf@`@pEZpD@ZAR?NCLCJGLKNC@y@j@EBaAn@]\\IHSRMPKPEHu@zBGRKXABS\\KRGJSROP]Va@RQDEBYHA?OFEFGH?@ELI`@CNK^GXGTQf@Yz@Mb@GPEJEDCDEDIh@?@ATA\\?F@z@@z@@`@?HEZCJETG\\CPEn@?f@?@@r@?NARANAFE\\G\\K`@Mn@A@[vAQn@Wp@Sj@IRIXGTGXADGd@ADId@Gf@GVEPIZIZ[p@EHi@|@]n@ADO\\O`@IXGNSdAAHETCZ?BAb@E`AA\\CZARIh@Mv@eAfFa@|AIVEVADCRATATA\\@F?NDTBJ@DLXDHNRJNNTd@dAPp@Bb@@??V?TAF?FERGRAHKXCHY~@Wt@WbAIX]pACNI`@Mp@AFKh@On@Op@]~AOp@On@Mp@o@pCEVGXI`@ANGh@Gr@AJGp@A@GPOTA@WRCBSJk@h@kAP]AC?[CCAm@IWGa@Ic@OMGg@IO?G?SF]Vc@^CBiAlAQX_@f@[b@u@bACBq@bAm@x@?@GLADEDYb@[b@SZEF[`@Yb@Y`@A@Yd@ILMXSf@A@Yd@GLQTYb@EF_@t@_@~@Uh@a@lAi@xASj@Sj@Sl@Sj@Sj@Sl@Uj@CJM`@Of@ADG\\ETALCr@BvA@DDr@?@HpA@VDt@?BFn@@DD\\Pv@@FRl@J^f@rAFPTj@Pf@@BThAHf@R|@Jb@Pl@BLHb@DRJr@AJ?XCXCd@AN?JIf@CRKp@CV?H?R?V@H@NFr@Hj@L^BDVf@FLHPLRJTBDLb@`@|BDd@Hr@Fr@Hr@Fr@Hz@Jj@DVFX@FL`@RZHJZ^\\^@?Z\\Z^z@|@Z^Z`@LJNJNJHDXDb@F`@FHBXDb@Fb@HhBXd@HbAT`@HfATD@ZFb@H@GBCH?f@AZCHCHERQ?A`AuANUXc@Xe@@?DKHa@@KBS@M@EBSDW@EDKFQDGBCR_@Zq@BENc@Pc@BIRk@Rk@Tk@?AJOLQPUHILWHQ@CHWDQBIJUHMFGPGB?D?ZH~@Tf@RTHJJLJJFD@D@L?LG`@Qv@]JE`@Q\\OBA`As@^QJGRKPINKTSHEZSPGRA@?T?JBb@JB@\\N`@P`@P`@PD@XPB@THH@L@VCr@C\\?V@?@LBLFDBhAt@NFFBLBb@Fh@FLBZFF@PFNBJBPJBBNLJN@?JZDPHd@@t@BZBt@@LBd@Hz@Dl@@F?^?L?FA^CLANKvANfBFx@LdBFr@B\\Hv@DPLn@BJHd@DRF^Lp@BNNZTh@DJRXVLNLJFD@FDJBFBRFF@VHHBJDTFHBTFB@NDPF@?\\HB?LBT@N@R?B?PABADC@ABEBIDMDOFQFU@CFQLY@EJSHO@ADEJMHGHIDEDGBG@ABGBGFQDGBIHOHM@ADELMFENKNE@AFAFARCD?RAF@@?NBPFHBNFFBFBH@PBb@BH@XBTBL@`@@@?ZCDALCPGBALGPQJMNQ@CRYBETYFEDGLKHEBAPGLC@?N?J@BBFBLLDLHPHXPh@@BLXFNLXHNN^BJN^BLDJHTPTLHBBHFLBHBVFJB\\FD@`@HHBXFb@HHBVD@?RJHHJNHV@BFNDJHHDHHDLJ`@T"
                     },
                     "start_location" : {
                        "lat" : 48.35418929999999,
                        "lng" : -123.6420413
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 574
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 48.3412889,
                        "lng" : -123.7106234
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSilver Spray Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ipafHjfarVXRDB^V^T~@l@@?^XB@XPTJN?B?PAJCBATMDGJKLY@?FWFUFSNm@J[?AR_@BENSLIHGTG@?TEL?L?RHb@N@@^NRFLFZJD@b@JD@ZL`@NFBZ@b@@V?"
                     },
                     "start_location" : {
                        "lat" : 48.345814,
                        "lng" : -123.7106206
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 167
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 48.3407024,
                        "lng" : -123.708541
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOcean Park Pl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "at`fHjfarVLq@Lo@Lq@Lq@Lq@Lq@Lq@RcA"
                     },
                     "start_location" : {
                        "lat" : 48.3412889,
                        "lng" : -123.7106234
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "qozgHlhjpViN{Au@nQjN|Fp@`@Hy@B_N~C}MlFsXr@uOX{EjBeOpRiUlBgEjAgBhLoBlb@_Rpd@_Zh`Agq@fT[tVd@lQ|Brg@rRzQzDxTsDfg@mOhSj@n\\hDlQyB`WeNt`@iNjm@wH|a@kHvf@iFnp@qJzK}B|KEn[oEze@eGtOiBpM|@~d@rFhWa@hIt@fN|DnJz@p_@}KrJzAzSnJzIU~c@cOvVyHrM_@dEi@tAqBo@kG}AiT}@}LuDwl@_Dwh@i@eIq@kJ`BeBnCoGnH{QtIqWpI_]zF}Ob@yIr@sDX}A~@wDnCdBhCbBrE|@rE|@hCICs\\C{H[aCw@UeAjA_AI~@HdAkApAdBBlDBrQ@~OiCHgL{BiI_FcImB{U{DcBUH~HCpLQnH{NvUqD`YnJvuAxItuApKp{AjBja@jH~OvV`[hJxRtGt[zHlSvA`LjIzRbOt\\iDtG{A`PJv^cMx`@eL~SwJvHcDlPyDp_@m@`Hd@pEjFtLfLxIlIfG|HxJpKtH`WfLjJfEhEhD^nRnDta@{Fpg@gF`~@wBlOkNa@uZzB}JxEeL|BaG_@sGZeDtByGrC{@OYiFCdCdAlCbIaDxFeCxDLbKErIuBpKyEx[iB|KnBtS|KtEnLdEbLW~BkEhWk@~Gf@jEC~BhAfCzPpH`R|IfNnG^hG`DtOlBdN_@xJ_DrND`EtUj|@|B~X^|JxMbLjNth@dFvT?hKsHhS_DnHeBfL}@z[vInSnPr]dNfS~K`QpCnFvHtFxIpAjMZ~EiAdN_GnOoFlTJ~DrBfExSTbPfDbIdJzEnHhDlDlGdGjUE~R[`PqBbGuI`QyGfGeB~JgChYzCzWxDrJlAxGg@bJt@~EpDjD|FdEh@fDh@nEUrGvBvFfEqBfD}BzHd@`JrA|GvCnAiFx@iCbDqAtOiEfPsCjKkC~Ar@LnCVxIjF|HpDtKtEyAjCmD`FCrBi@`ChCfCbCbBSvFeFvA}AhDg@~BtDtDhA`NrAbLPzCy@~DnA|EdRxBzMfGnEzEvD|@|AF~CoCdDwHvCkHrG{AxTBjH~ApFvBvB@lC}CrN`AhP{AhCkH|KiEfFiBlLi@`KuK`_@oDzUbCbKyJde@eApDqEbAyE}@qFvFkIvLqI`RkDzP`DlQxB|Oh@|KfDzRdJvJzPlCvDyBzAmDtCeIjDiH`E`AzC_@vIqEdUrFzApAh@nHt@dT|DnJ|ErAnC{AnBeDnCyBpFt@|EoCrAg@pAzBbDbGhGhBdGfFdCr@jAkBxAcDfBKlDjAjAb@dBm@fBmJ"
         },
         "summary" : "BC-17",
         "warnings" : [],
         "waypoint_order" : [ 0, 2, 1 ]
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
