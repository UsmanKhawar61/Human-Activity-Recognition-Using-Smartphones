# Code Book for HARUS Project

## Step1:  
Importing the raw data and merging data into one large dataset.  
It contained the folowing variables:  

  [1] "V1"          "V2"          "V3"          "V4"          "V5"          "V6"         
  [7] "V7"          "V8"          "V9"          "V10"         "V11"         "V12"        
 [13] "V13"         "V14"         "V15"         "V16"         "V17"         "V18"        
 [19] "V19"         "V20"         "V21"         "V22"         "V23"         "V24"        
 [25] "V25"         "V26"         "V27"         "V28"         "V29"         "V30"        
 [31] "V31"         "V32"         "V33"         "V34"         "V35"         "V36"        
 [37] "V37"         "V38"         "V39"         "V40"         "V41"         "V42"        
 [43] "V43"         "V44"         "V45"         "V46"         "V47"         "V48"        
 [49] "V49"         "V50"         "V51"         "V52"         "V53"         "V54"        
 [55] "V55"         "V56"         "V57"         "V58"         "V59"         "V60"        
 [61] "V61"         "V62"         "V63"         "V64"         "V65"         "V66"        
 [67] "V67"         "V68"         "V69"         "V70"         "V71"         "V72"        
 [73] "V73"         "V74"         "V75"         "V76"         "V77"         "V78"        
 [79] "V79"         "V80"         "V81"         "V82"         "V83"         "V84"        
 [85] "V85"         "V86"         "V87"         "V88"         "V89"         "V90"        
 [91] "V91"         "V92"         "V93"         "V94"         "V95"         "V96"        
 [97] "V97"         "V98"         "V99"         "V100"        "V101"        "V102"       
[103] "V103"        "V104"        "V105"        "V106"        "V107"        "V108"       
[109] "V109"        "V110"        "V111"        "V112"        "V113"        "V114"       
[115] "V115"        "V116"        "V117"        "V118"        "V119"        "V120"       
[121] "V121"        "V122"        "V123"        "V124"        "V125"        "V126"       
[127] "V127"        "V128"        "V129"        "V130"        "V131"        "V132"       
[133] "V133"        "V134"        "V135"        "V136"        "V137"        "V138"       
[139] "V139"        "V140"        "V141"        "V142"        "V143"        "V144"       
[145] "V145"        "V146"        "V147"        "V148"        "V149"        "V150"       
[151] "V151"        "V152"        "V153"        "V154"        "V155"        "V156"       
[157] "V157"        "V158"        "V159"        "V160"        "V161"        "V162"       
[163] "V163"        "V164"        "V165"        "V166"        "V167"        "V168"       
[169] "V169"        "V170"        "V171"        "V172"        "V173"        "V174"       
[175] "V175"        "V176"        "V177"        "V178"        "V179"        "V180"       
[181] "V181"        "V182"        "V183"        "V184"        "V185"        "V186"       
[187] "V187"        "V188"        "V189"        "V190"        "V191"        "V192"       
[193] "V193"        "V194"        "V195"        "V196"        "V197"        "V198"       
[199] "V199"        "V200"        "V201"        "V202"        "V203"        "V204"       
[205] "V205"        "V206"        "V207"        "V208"        "V209"        "V210"       
[211] "V211"        "V212"        "V213"        "V214"        "V215"        "V216"       
[217] "V217"        "V218"        "V219"        "V220"        "V221"        "V222"       
[223] "V223"        "V224"        "V225"        "V226"        "V227"        "V228"       
[229] "V229"        "V230"        "V231"        "V232"        "V233"        "V234"       
[235] "V235"        "V236"        "V237"        "V238"        "V239"        "V240"       
[241] "V241"        "V242"        "V243"        "V244"        "V245"        "V246"       
[247] "V247"        "V248"        "V249"        "V250"        "V251"        "V252"       
[253] "V253"        "V254"        "V255"        "V256"        "V257"        "V258"       
[259] "V259"        "V260"        "V261"        "V262"        "V263"        "V264"       
[265] "V265"        "V266"        "V267"        "V268"        "V269"        "V270"       
[271] "V271"        "V272"        "V273"        "V274"        "V275"        "V276"       
[277] "V277"        "V278"        "V279"        "V280"        "V281"        "V282"       
[283] "V283"        "V284"        "V285"        "V286"        "V287"        "V288"       
[289] "V289"        "V290"        "V291"        "V292"        "V293"        "V294"       
[295] "V295"        "V296"        "V297"        "V298"        "V299"        "V300"       
[301] "V301"        "V302"        "V303"        "V304"        "V305"        "V306"       
[307] "V307"        "V308"        "V309"        "V310"        "V311"        "V312"       
[313] "V313"        "V314"        "V315"        "V316"        "V317"        "V318"       
[319] "V319"        "V320"        "V321"        "V322"        "V323"        "V324"       
[325] "V325"        "V326"        "V327"        "V328"        "V329"        "V330"       
[331] "V331"        "V332"        "V333"        "V334"        "V335"        "V336"       
[337] "V337"        "V338"        "V339"        "V340"        "V341"        "V342"       
[343] "V343"        "V344"        "V345"        "V346"        "V347"        "V348"       
[349] "V349"        "V350"        "V351"        "V352"        "V353"        "V354"       
[355] "V355"        "V356"        "V357"        "V358"        "V359"        "V360"       
[361] "V361"        "V362"        "V363"        "V364"        "V365"        "V366"       
[367] "V367"        "V368"        "V369"        "V370"        "V371"        "V372"       
[373] "V373"        "V374"        "V375"        "V376"        "V377"        "V378"       
[379] "V379"        "V380"        "V381"        "V382"        "V383"        "V384"       
[385] "V385"        "V386"        "V387"        "V388"        "V389"        "V390"       
[391] "V391"        "V392"        "V393"        "V394"        "V395"        "V396"       
[397] "V397"        "V398"        "V399"        "V400"        "V401"        "V402"       
[403] "V403"        "V404"        "V405"        "V406"        "V407"        "V408"       
[409] "V409"        "V410"        "V411"        "V412"        "V413"        "V414"       
[415] "V415"        "V416"        "V417"        "V418"        "V419"        "V420"       
[421] "V421"        "V422"        "V423"        "V424"        "V425"        "V426"       
[427] "V427"        "V428"        "V429"        "V430"        "V431"        "V432"       
[433] "V433"        "V434"        "V435"        "V436"        "V437"        "V438"       
[439] "V439"        "V440"        "V441"        "V442"        "V443"        "V444"       
[445] "V445"        "V446"        "V447"        "V448"        "V449"        "V450"       
[451] "V451"        "V452"        "V453"        "V454"        "V455"        "V456"       
[457] "V457"        "V458"        "V459"        "V460"        "V461"        "V462"       
[463] "V463"        "V464"        "V465"        "V466"        "V467"        "V468"       
[469] "V469"        "V470"        "V471"        "V472"        "V473"        "V474"       
[475] "V475"        "V476"        "V477"        "V478"        "V479"        "V480"       
[481] "V481"        "V482"        "V483"        "V484"        "V485"        "V486"       
[487] "V487"        "V488"        "V489"        "V490"        "V491"        "V492"       
[493] "V493"        "V494"        "V495"        "V496"        "V497"        "V498"       
[499] "V499"        "V500"        "V501"        "V502"        "V503"        "V504"       
[505] "V505"        "V506"        "V507"        "V508"        "V509"        "V510"       
[511] "V511"        "V512"        "V513"        "V514"        "V515"        "V516"       
[517] "V517"        "V518"        "V519"        "V520"        "V521"        "V522"       
[523] "V523"        "V524"        "V525"        "V526"        "V527"        "V528"       
[529] "V529"        "V530"        "V531"        "V532"        "V533"        "V534"       
[535] "V535"        "V536"        "V537"        "V538"        "V539"        "V540"       
[541] "V541"        "V542"        "V543"        "V544"        "V545"        "V546"       
[547] "V547"        "V548"        "V549"        "V550"        "V551"        "V552"       
[553] "V553"        "V554"        "V555"        "V556"        "V557"        "V558"       
[559] "V559"        "V560"        "V561"        "Activity ID" "Subject ID" 

## Step 2:  
After cleaning and extracting only the mean and standard deviation measures, we got a relatively smaller dataset with the following variables:  
 [1] "Activity ID" "Subject ID"  "V1"          "V2"          "V3"          "V4"         
 [7] "V5"          "V6"          "V41"         "V42"         "V43"         "V44"        
[13] "V45"         "V46"         "V81"         "V82"         "V83"         "V84"        
[19] "V85"         "V86"         "V121"        "V122"        "V123"        "V124"       
[25] "V125"        "V126"        "V161"        "V162"        "V163"        "V164"       
[31] "V165"        "V166"        "V201"        "V202"        "V214"        "V215"       
[37] "V227"        "V228"        "V240"        "V241"        "V253"        "V254"       
[43] "V266"        "V267"        "V268"        "V269"        "V270"        "V271"       
[49] "V345"        "V346"        "V347"        "V348"        "V349"        "V350"       
[55] "V424"        "V425"        "V426"        "V427"        "V428"        "V429"       
[61] "V503"        "V504"        "V516"        "V517"        "V529"        "V530"       
[67] "V542"        "V543"       

## Step3:  
After renaming the data variables, we got the following:  
 [1] "Activity ID"              "Subject ID"               "tBodyAcc_mX"             
 [4] "tBodyAcc_mY"              "tBodyAcc_mZ"              "tBodyAcc_stdX"           
 [7] "tBodyAcc_stdY"            "tBodyAcc_stdZ"            "tGravityAcc_mX"          
[10] "tGravityAcc_mY"           "tGravityAcc_mZ"           "tGravityAcc_stdX"        
[13] "tGravityAcc_stdY"         "tGravityAcc_stdZ"         "tBodyAccJerk_mX"         
[16] "tBodyAccJerk_mY"          "tBodyAccJerk_mZ"          "tBodyAccJerk_stdX"       
[19] "tBodyAccJerk_stdY"        "tBodyAccJerk_stdZ"        "tBodyGyro_mX"            
[22] "tBodyGyro_mY"             "tBodyGyro_mZ"             "tBodyGyro_stdX"          
[25] "tBodyGyro_stdY"           "tBodyGyro_stdZ"           "tBodyGyroJerk_mX"        
[28] "tBodyGyroJerk_mY"         "tBodyGyroJerk_mZ"         "tBodyGyroJerk_stdX"      
[31] "tBodyGyroJerk_stdY"       "tBodyGyroJerk_stdZ"       "tBodyAccMag_m"           
[34] "tBodyAccMag_std"          "tGravityAccMag_m"         "tGravityAccMag_std"      
[37] "tBodyAccJerkMag_m"        "tBodyAccJerkMag_std"      "tBodyGyroMag_m"          
[40] "tBodyGyroMag_std"         "tBodyGyroJerkMag_m"       "tBodyGyroJerkMag_std"    
[43] "fBodyAcc_mX"              "fBodyAcc_mY"              "fBodyAcc_mZ"             
[46] "fBodyAcc_stdX"            "fBodyAcc_stdY"            "fBodyAcc_stdZ"           
[49] "fBodyAccJerk_mX"          "fBodyAccJerk_mY"          "fBodyAccJerk_mZ"         
[52] "fBodyAccJerk_stdX"        "fBodyAccJerk_stdY"        "fBodyAccJerk_stdZ"       
[55] "fBodyGyro_mX"             "fBodyGyro_mY"             "fBodyGyro_mZ"            
[58] "fBodyGyro_stdX"           "fBodyGyro_stdY"           "fBodyGyro_stdZ"          
[61] "fBodyAccMag_m"            "fBodyAccMag_std"          "fBodyBodyAccJerkMag_m"   
[64] "fBodyBodyAccJerkMag_std"  "fBodyBodyGyroMag_m"       "fBodyBodyGyroMag_std"    
[67] "fBodyBodyGyroJerkMag_m"   "fBodyBodyGyroJerkMag_std"


## Step 4:
Now we grouped the data by variables Activity ID and Subject ID, after that, summarise() function was used to determine average of each variable. The new tidy dataset had the following variables:  
 [1] "Subject ID"                     "Activity ID"                   
 [3] "mean(tBodyAcc_mX)"              "mean(tBodyAcc_mY)"             
 [5] "mean(tBodyAcc_mZ)"              "mean(tGravityAcc_mX)"          
 [7] "mean(tGravityAcc_mY)"           "mean(tGravityAcc_mZ)"          
 [9] "mean(tBodyAccJerk_mX)"          "mean(tBodyAccJerk_mY)"         
[11] "mean(tBodyAccJerk_mZ)"          "mean(tBodyGyro_mX)"            
[13] "mean(tBodyGyro_mY)"             "mean(tBodyGyro_mZ)"            
[15] "mean(tBodyGyroJerk_mX)"         "mean(tBodyGyroJerk_mY)"        
[17] "mean(tBodyGyroJerk_mZ)"         "mean(tBodyAccMag_m)"           
[19] "mean(tGravityAccMag_m)"         "mean(tBodyAccJerkMag_m)"       
[21] "mean(tBodyGyroMag_m)"           "mean(tBodyGyroJerkMag_m)"      
[23] "mean(fBodyAcc_mX)"              "mean(fBodyAcc_mY)"             
[25] "mean(fBodyAcc_mZ)"              "mean(fBodyAccJerk_mX)"         
[27] "mean(fBodyAccJerk_mY)"          "mean(fBodyAccJerk_mZ)"         
[29] "mean(fBodyGyro_mX)"             "mean(fBodyGyro_mY)"            
[31] "mean(fBodyGyro_mZ)"             "mean(fBodyAccMag_m)"           
[33] "mean(fBodyBodyAccJerkMag_m)"    "mean(fBodyBodyGyroMag_m)"      
[35] "mean(fBodyBodyGyroJerkMag_m)"   "mean(tBodyAcc_stdX)"           
[37] "mean(tBodyAcc_stdY)"            "mean(tBodyAcc_stdZ)"           
[39] "mean(tGravityAcc_stdX)"         "mean(tGravityAcc_stdY)"        
[41] "mean(tGravityAcc_stdZ)"         "mean(tBodyAccJerk_stdX)"       
[43] "mean(tBodyAccJerk_stdY)"        "mean(tBodyAccJerk_stdZ)"       
[45] "mean(tBodyGyro_stdX)"           "mean(tBodyGyro_stdY)"          
[47] "mean(tBodyGyro_stdZ)"           "mean(tBodyGyroJerk_stdX)"      
[49] "mean(tBodyGyroJerk_stdY)"       "mean(tBodyGyroJerk_stdZ)"      
[51] "mean(tBodyAccMag_std)"          "mean(tGravityAccMag_std)"      
[53] "mean(tBodyAccJerkMag_std)"      "mean(tBodyGyroMag_std)"        
[55] "mean(tBodyGyroJerkMag_std)"     "mean(fBodyAcc_stdX)"           
[57] "mean(fBodyAcc_stdY)"            "mean(fBodyAcc_stdZ)"           
[59] "mean(fBodyAccJerk_stdX)"        "mean(fBodyAccJerk_stdY)"       
[61] "mean(fBodyAccJerk_stdZ)"        "mean(fBodyGyro_stdX)"          
[63] "mean(fBodyGyro_stdY)"           "mean(fBodyGyro_stdZ)"          
[65] "mean(fBodyAccMag_std)"          "mean(fBodyBodyAccJerkMag_std)" 
[67] "mean(fBodyBodyGyroMag_std)"     "mean(fBodyBodyGyroJerkMag_std)"

## Variables of the TIDY DATASET:  

*1. Subject ID*  
Integer variable ranging from 1 to 30. Each number represents an individual partaking in the experiment.   

*2. Activity ID:*  
A factor variable with 6 levels.  
LAYING-->1, SITTING --> 2, STANDING--> 3, WALKING--> 4, WALKING_DOWNSTAIRS--> 5, WALKING_UPSTAIRS -->6  

*For all variables 3:68:*  
mean("name")--> Reperesents average of the feature "name"  
All variables are numeric and normalized on as scale -1 to 1.  
The "names" represent features of wide variety that are calculated of either mean or standard deviation.  
_m --> Mean of the feature  
_std --> Standard Deviation of the feature  
_m without either X,Y or Z means it's a standalone measurement.  
_mX --> X-axis  
_mY --> Y-axis  
_mZ --> Z-axis  

Feature names starting with "t" means they are measured in the time domain.  
Feature names starting with "f" means they are measured in the frequency domain.  

All above rules also apply to the "_std" similarly.  
