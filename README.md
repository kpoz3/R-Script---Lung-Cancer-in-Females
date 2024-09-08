# R-Script---Lung-Cancer-in-Females
> names(liver_cancer_data)
  [1] "CONDITION"                          "OUTCOME"                           
  [3] "Year"                               "Geography"                         
  [5] "GeoType"                            "GeoName"                           
  [7] "GeoID"                              "Region"                            
  [9] "District"                           "Total"                             
 [11] "TotalRate"                          "AARate"                            
 [13] "Age0_14"                            "Age0_14Rate"                       
 [15] "Age15_24"                           "Age15_24Rate"                      
 [17] "Age25_44"                           "Age25_44Rate"                      
 [19] "Age45_64"                           "Age45_64Rate"                      
 [21] "Age65Plus"                          "Age65PlusRate"                     
 [23] "Total_Male"                         "Total_MaleRate"                    
 [25] "AA_TotalMaleRate"                   "Age0_14_Male"                      
 [27] "Age0_14_MaleRate"                   "Age15_24_Male"                     
 [29] "Age15_24_MaleRate"                  "Age25_44_Male"                     
 [31] "Age25_44_MaleRate"                  "Age45_64_Male"                     
 [33] "Age45_64_MaleRate"                  "Age65Plus_Male"                    
 [35] "Age65Plus_MaleRate"                 "Total_Female"                      
 [37] "Total_FemaleRate"                   "AA_TotalFemaleRate"                
 [39] "Age0_14_Female"                     "Age0_14_FemaleRate"                
 [41] "Age15_24_Female"                    "Age15_24_FemaleRate"               
 [43] "Age25_44_Female"                    "Age25_44_FemaleRate"               
 [45] "Age45_64_Female"                    "Age45_64_FemaleRate"               
 [47] "Age45Plus_Female"                   "Age45Plus_FemaleRate"              
 [49] "Age65Plus_Female"                   "Age65Plus_FemaleRate"              
 [51] "White_Total"                        "White_TotalRate"                   
 [53] "White_Age0_14"                      "White_Age0_14Rate"                 
 [55] "White_Age15_24"                     "White_Age15_24Rate"                
 [57] "White_Age25_44"                     "White_Age25_44Rate"                
 [59] "White_Age45_64"                     "White_Age45_64Rate"                
 [61] "White_Age65Plus"                    "White_Age65PlusRate"               
 [63] "White_Total_Male"                   "White_Total_MaleRate"              
 [65] "White_Age0_14_Male"                 "White_Age0_14_MaleRate"            
 [67] "White_Age15_24_Male"                "White_Age15_24_MaleRate"           
 [69] "White_Age25_44_Male"                "White_Age25_44_MaleRate"           
 [71] "White_Age45_64_Male"                "White_Age45_64_MaleRate"           
 [73] "White_Age65Plus_Male"               "White_Age65Plus_MaleRate"          
 [75] "White_Total_Female"                 "White_Total_FemaleRate"            
 [77] "White_Age0_14_Female"               "White_Age0_14_FemaleRate"          
 [79] "White_Age15_24_Female"              "White_Age15_24_FemaleRate"         
 [81] "White_Age25_44_Female"              "White_Age25_44_FemaleRate"         
 [83] "White_Age45_64_Female"              "White_Age45_64_FemaleRate"         
 [85] "White_Age45Plus_Female"             "White_Age45Plus_FemaleRate"        
 [87] "White_Age65Plus_Female"             "White_Age65Plus_FemaleRate"        
 [89] "Black_Total"                        "Black_TotalRate"                   
 [91] "Black_Age0_14"                      "Black_Age0_14Rate"                 
 [93] "Black_Age15_24"                     "Black_Age15_24Rate"                
 [95] "Black_Age25_44"                     "Black_Age25_44Rate"                
 [97] "Black_Age45_64"                     "Black_Age45_64Rate"                
 [99] "Black_Age65Plus"                    "Black_Age65PlusRate"               
[101] "Black_Total_Male"                   "Black_Total_MaleRate"              
[103] "Black_Age0_14_Male"                 "Black_Age0_14_MaleRate"            
[105] "Black_Age15_24_Male"                "Black_Age15_24_MaleRate"           
[107] "Black_Age25_44_Male"                "Black_Age25_44_MaleRate"           
[109] "Black_Age45_64_Male"                "Black_Age45_64_MaleRate"           
[111] "Black_Age65Plus_Male"               "Black_Age65Plus_MaleRate"          
[113] "Black_Total_Female"                 "Black_Total_FemaleRate"            
[115] "Black_Age0_14_Female"               "Black_Age0_14_FemaleRate"          
[117] "Black_Age15_24_Female"              "Black_Age15_24_FemaleRate"         
[119] "Black_Age25_44_Female"              "Black_Age25_44_FemaleRate"         
[121] "Black_Age45_64_Female"              "Black_Age45_64_FemaleRate"         
[123] "Black_Age45Plus_Female"             "Black_Age45Plus_FemaleRate"        
[125] "Black_Age65Plus_Female"             "Black_Age65Plus_FemaleRate"        
[127] "Hispanic_Total"                     "Hispanic_TotalRate"                
[129] "Hispanic_Age0_14"                   "Hispanic_Age0_14Rate"              
[131] "Hispanic_Age15_24"                  "Hispanic_Age15_24Rate"             
[133] "Hispanic_Age25_44"                  "Hispanic_Age25_44Rate"             
[135] "Hispanic_Age45_64"                  "Hispanic_Age45_64Rate"             
[137] "Hispanic_Age65Plus"                 "Hispanic_Age65PlusRate"            
[139] "Hispanic_Total_Male"                "Hispanic_Total_MaleRate"           
[141] "Hispanic_Age0_14_Male"              "Hispanic_Age0_14_MaleRate"         
[143] "Hispanic_Age15_24_Male"             "Hispanic_Age15_24_MaleRate"        
[145] "Hispanic_Age25_44_Male"             "Hispanic_Age25_44_MaleRate"        
[147] "Hispanic_Age45_64_Male"             "Hispanic_Age45_64_MaleRate"        
[149] "Hispanic_Age65Plus_Male"            "Hispanic_Age65Plus_MaleRate"       
[151] "Hispanic_Total_Female"              "Hispanic_Total_FemaleRate"         
[153] "Hispanic_Age0_14_Female"            "Hispanic_Age0_14_FemaleRate"       
[155] "Hispanic_Age15_24_Female"           "Hispanic_Age15_24_FemaleRate"      
[157] "Hispanic_Age25_44_Female"           "Hispanic_Age25_44_FemaleRate"      
[159] "Hispanic_Age45_64_Female"           "Hispanic_Age45_64_FemaleRate"      
[161] "Hispanic_Age45Plus_Female"          "Hispanic_Age45Plus_FemaleRate"     
[163] "Hispanic_Age65Plus_Female"          "Hispanic_Age65Plus_FemaleRate"     
[165] "API_Total"                          "API_TotalRate"                     
[167] "API_Age0_14"                        "API_Age0_14Rate"                   
[169] "API_Age15_24"                       "API_Age15_24Rate"                  
[171] "API_Age25_44"                       "API_Age25_44Rate"                  
[173] "API_Age45_64"                       "API_Age45_64Rate"                  
[175] "API_Age65Plus"                      "API_Age65PlusRate"                 
[177] "API_Total_Male"                     "API_Total_MaleRate"                
[179] "API_Age0_14_Male"                   "API_Age0_14_MaleRate"              
[181] "API_Age15_24_Male"                  "API_Age15_24_MaleRate"             
[183] "API_Age25_44_Male"                  "API_Age25_44_MaleRate"             
[185] "API_Age45_64_Male"                  "API_Age45_64_MaleRate"             
[187] "API_Age65Plus_Male"                 "API_Age65Plus_MaleRate"            
[189] "API_Total_Female"                   "API_Total_FemaleRate"              
[191] "API_Age0_14_Female"                 "API_Age0_14_FemaleRate"            
[193] "API_Age15_24_Female"                "API_Age15_24_FemaleRate"           
[195] "API_Age25_44_Female"                "API_Age25_44_FemaleRate"           
[197] "API_Age45_64_Female"                "API_Age45_64_FemaleRate"           
[199] "API_Age45Plus_Female"               "API_Age45Plus_FemaleRate"          
[201] "API_Age65Plus_Female"               "API_Age65Plus_FemaleRate"          
[203] "AIAN_Total"                         "AIAN_TotalRate"                    
[205] "AIAN_Age0_14"                       "AIAN_Age0_14Rate"                  
[207] "AIAN_Age15_24"                      "AIAN_Age15_24Rate"                 
[209] "AIAN_Age25_44"                      "AIAN_Age25_44Rate"                 
[211] "AIAN_Age45_64"                      "AIAN_Age45_64Rate"                 
[213] "AIAN_Age65Plus"                     "AIAN_Age65PlusRate"                
[215] "AIAN_Total_Male"                    "AIAN_Total_MaleRate"               
[217] "AIAN_Age0_14_Male"                  "AIAN_Age0_14_MaleRate"             
[219] "AIAN_Age15_24_Male"                 "AIAN_Age15_24_MaleRate"            
[221] "AIAN_Age25_44_Male"                 "AIAN_Age25_44_MaleRate"            
[223] "AIAN_Age45_64_Male"                 "AIAN_Age45_64_MaleRate"            
[225] "AIAN_Age65Plus_Male"                "AIAN_Age65Plus_MaleRate"           
[227] "AIAN_Total_Female"                  "AIAN_Total_FemaleRate"             
[229] "AIAN_Age0_14_Female"                "AIAN_Age0_14_FemaleRate"           
[231] "AIAN_Age15_24_Female"               "AIAN_Age15_24_FemaleRate"          
[233] "AIAN_Age25_44_Female"               "AIAN_Age25_44_FemaleRate"          
[235] "AIAN_Age45_64_Female"               "AIAN_Age45_64_FemaleRate"          
[237] "AIAN_Age45Plus_Female"              "AIAN_Age45Plus_FemaleRate"         
[239] "AIAN_Age65Plus_Female"              "AIAN_Age65Plus_FemaleRate"         
[241] "Other_notAIAN_Total"                "Other_notAIAN_TotalRate"           
[243] "Other_notAIAN_Age0_14"              "Other_notAIAN_Age0_14Rate"         
[245] "Other_notAIAN_Age15_24"             "Other_notAIAN_Age15_24Rate"        
[247] "Other_notAIAN_Age25_44"             "Other_notAIAN_Age25_44Rate"        
[249] "Other_notAIAN_Age45_64"             "Other_notAIAN_Age45_64Rate"        
[251] "Other_notAIAN_Age65Plus"            "Other_notAIAN_Age65PlusRate"       
[253] "Other_notAIAN_Total_Male"           "Other_notAIAN_Total_MaleRate"      
[255] "Other_notAIAN_Age0_14_Male"         "Other_notAIAN_Age0_14_MaleRate"    
[257] "Other_notAIAN_Age15_24_Male"        "Other_notAIAN_Age15_24_MaleRate"   
[259] "Other_notAIAN_Age25_44_Male"        "Other_notAIAN_Age25_44_MaleRate"   
[261] "Other_notAIAN_Age45_64_Male"        "Other_notAIAN_Age45_64_MaleRate"   
[263] "Other_notAIAN_Age65Plus_Male"       "Other_notAIAN_Age65Plus_MaleRate"  
[265] "Other_notAIAN_Total_Female"         "Other_notAIAN_Total_FemaleRate"    
[267] "Other_notAIAN_Age0_14_Female"       "Other_notAIAN_Age0_14_FemaleRate"  
[269] "Other_notAIAN_Age15_24_Female"      "Other_notAIAN_Age15_24_FemaleRate" 
[271] "Other_notAIAN_Age25_44_Female"      "Other_notAIAN_Age25_44_FemaleRate" 
[273] "Other_notAIAN_Age45_64_Female"      "Other_notAIAN_Age45_64_FemaleRate" 
[275] "Other_notAIAN_Age45Plus_Female"     "Other_notAIAN_Age45Plus_FemaleRate"
[277] "Other_notAIAN_Age65Plus_Female"     "Other_notAIAN_Age65Plus_FemaleRate"
> max_geography <- aggregate(liver_cancer_data[, c("Total_MaleRate","Total_FemaleRate")], by=list(Geography = liver_cancer_data$Geography), FUN=max, na.rm=TRUE)
There were 50 or more warnings (use warnings() to see the first 50)
> print(max_geography)
                  Geography Total_MaleRate Total_FemaleRate
1                    Alpine           -Inf             -Inf
2      Anza-Borrego Springs           -Inf             -Inf
3                  Carlsbad          11.46             7.57
4            Central Region          16.80            11.08
5         Central San Diego          18.91            14.82
6               Chula Vista          17.28            12.56
7          City of Carlsbad          11.24             -Inf
8       City of Chula Vista          17.42             9.94
9          City of Coronado           -Inf             -Inf
10          City of Del Mar           -Inf             -Inf
11         City of El Cajon          17.21            11.34
12        City of Encinitas          17.85             -Inf
13        City of Escondido          13.56             7.03
14   City of Imperial Beach           -Inf             -Inf
15          City of La Mesa          17.21             -Inf
16      City of Lemon Grove          52.78             -Inf
17    City of National City          24.48            16.96
18        City of Oceanside          17.38            14.62
19            City of Poway          24.17             -Inf
20        City of San Diego          12.62             7.54
21       City of San Marcos          13.96             -Inf
22           City of Santee           -Inf            17.11
23     City of Solana Beach           -Inf             -Inf
24            City of Vista          15.20             9.55
25                  Coastal          15.10             -Inf
26                 Coronado           -Inf             -Inf
27        Del Mar-Mira Mesa          13.96             9.63
28              East Region          14.68             7.79
29                 El Cajon          15.79            10.30
30           Elliott-Navajo          15.66             -Inf
31                Escondido          12.56             6.51
32                Fallbrook          22.55             -Inf
33           Harbison Crest           -Inf             -Inf
34  Harbison Crest-El Cajon          14.95             9.49
35                    Jamul           -Inf             -Inf
36              Kearny Mesa          21.08             7.95
37                  La Mesa          17.27             -Inf
38       Laguna-Pine Valley           -Inf             -Inf
39                 Lakeside          24.02             -Inf
40              Lemon Grove          47.19             -Inf
41                 Mid-City          18.76            12.73
42                  Miramar           -Inf             -Inf
43          Mountain Empire           -Inf             -Inf
44            National City          24.61            16.90
45     North Central Region          10.85             7.61
46     North Coastal Region          11.69             6.31
47      North Inland Region          13.01             7.16
48          North San Diego           9.21            12.13
49                Oceanside          17.47            13.52
50           Palomar-Julian           -Inf             -Inf
51                    Pauma           -Inf             -Inf
52                Pendleton           -Inf             -Inf
53                Peninsula          22.61            18.40
54                    Poway          15.86            10.71
55                   Ramona          26.67             -Inf
56         San Diego County          11.58             6.67
57             San Dieguito          15.75             -Inf
58               San Marcos          13.11             -Inf
59                   Santee           -Inf            16.67
60                South Bay          23.80            14.84
61             South Region          15.61             8.56
62   Southeastern San Diego          19.31            15.44
63            Spring Valley          20.26             -Inf
64 Supervisorial District 1          15.44             9.59
65 Supervisorial District 2          14.61             7.19
66 Supervisorial District 3          10.56             7.21
67 Supervisorial District 4          16.77             8.24
68 Supervisorial District 5          10.50             6.31
69               Sweetwater          17.81             9.63
70           Unincorporated          13.81             5.73
71               University          14.68             -Inf
72            Valley Center          43.22             -Inf
73                    Vista          15.65             -Inf

> ggplot(max_geography, aes(max_geography$Geography,max_geography$Total_FemaleRate)) + geom_bar(stat="identity") +
+     ggtitle("Geography of Liver Cancer in Females")+
+     ylab("Mean of Total_FemalRate") +
+     xlab("Geography of Liver Cancer") +
+     theme(legend.position="right") +
+     theme(axis.text.x = element_text(angle=70, vjust=1, hjust=1))+ list()
