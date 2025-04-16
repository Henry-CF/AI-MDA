# liver_medical_data_dictionary：DB data dictionary

## Table 1. Hepatitis_B

- 各字段说明

| Column Name | Description | Value Range | Value Explanation | Type |
|-------------|-------------|-------------|-------------------|------|
| 狀態 | 病人狀態 | 轉出結案,追蹤中,轉出 |  | VARCHAR(255) |
| 編號 | 病人編號 | 由1開始 | VARCHAR(255) |
| Name | 病人姓名 | | | VARCHAR(255) |
| ChartNo | 病例編號 | | | VARCHAR(255) | 
| Dr. | 醫生姓名 | 人名 | | VARCHAR(255) | 
| Birthday | 生日 | | year/month/day or year/month.day | VARCHAR(255) | 
| Gender | 性別 | 男女 | Female  Male | VARCHAR(255) | 
| Age | 年齡 | 年齡 | | FLOAT 
| 收案日期 | 收案日期 | | | | VARCHAR(255) |
| EchoDay | 超音波日期 | | | VARCHAR(255) |
| Dignosis | 醫師診斷 | negative, no focal lesion,lesion could not be found,regeneration nodules,... liver biopsy(肝臟切片) | VARCHAR(255) |
| HBsAg | B 型肝炎表面抗原(HBsAg)「陽性」或「反應性」HBsAg 檢測結果表示此人已感染B 型肝炎病毒，可能是「急性」或「慢性」感染 | positive, negative, 缺 | positive(陽性), negative(陰性), 缺 | VARCHAR(255) |
| 檢驗日期 | 檢驗日期 | 月份 | | VARCHAR(255) |
| HBeAg | B肝e抗原(HBeAg)是pre-C/C基因的產物，當B肝病毒增殖時此種基因可以在肝細胞中發現 | positive, negative, 缺 | | VARCHAR(255) | 
| 檢驗日期.1 | HBeAg的檢驗日期 | 月份 | | VARCHAR(255) |
| real_age |實際年齡|||FLOAT|


## Table 2. Hepatitis_C

- 各字段说明

| Column Name | Description | Value Range | Value Explanation | Type |
|-------------|-------------|-------------|-------------------|------|
| 狀態 | 病人狀態 | 轉出結案,追蹤中,轉出 |  | VARCHAR(255) |
| 編號 | 病人編號 | 由1開始 | VARCHAR(255) |
| Name | 病人姓名 | | | VARCHAR(255) |
| ChartNo | 病例編號 | | | VARCHAR(255) | 
| Dr. | 醫生姓名 | 楒歆彤, 泓溫碧, 浚潔綉, 馭曦瑾, 巧琇嫻, 香靄晞, 淑翩芷, 揚墨醇, 琪翩嫣, 祐暄彤, 渝雲棻, 奕嫻淳, 瑾瑗儷, 綽卉卿, 瑜釧卿, 旻儷  涵, 巧琇嫻, 雅曦暄, 嘉勻寧, 庭雍淑, 卿凝華, 靈芷禎, 翩爽雲, 惻文涵, 承儷霓, 羽幃嫻, 奕嫻淳, 華芩儷, 晁采蓮, 逸凌雲, 儁瑾瀅, | | VARCHAR(255) | 
 Gender | 性別 | 男女 | Female  Male | VARCHAR(255) | 
| Birthday | 生日 | | year/month/day or year/month.day | VARCHAR(255) | 
| Age | 年齡 | 年齡 | | FLOAT 
| 收案日期 | 收案日期 | | | | VARCHAR(255) |
| EchoDay | 超音波日期 | | | VARCHAR(255) |
| Dignosis | 醫師診斷 | negative, no focal lesion,lesion could not be found,regeneration nodules,... liver biopsy(肝臟切片) | VARCHAR(255) |
| GOT | GOT的值| | | FLOAT |
| 檢驗日期 | GOT的檢驗日期 | 月份 | | VARCHAR(255) |
| GPT | GPT的值| | | FLOAT |
| 檢驗日期.1 | GPT的檢驗日期 | 月份 | | VARCHAR(255) |
| Anti-HCV | C型肝炎病毒抗體 | positive, negative, 缺 | VARCHAR(255) |
| 檢驗日期.2 | Anti-HCV檢驗日期 | | | VARCHAR(255) |
| 6MFollow1 | 六個月後追蹤的月份 | 月份 |VARCHAR(255) |
| OPDDay1 | 門診月份 | 月份 | | VARCHAR(255) | 
| EchoDay1 | 超音波月份 | 月份 | |VARCHAR(255) | 
| Dignosis1 | 醫師診斷 | 同Dignosis | 同Dignosis | VARCHAR(255) | 
| real_age | 實際年齡 |||FLOAT|



## Table 3. Hepatitis_BC

- 各字段说明

| Column Name | Description | Value Range | Value Explanation | Type |
|-------------|-------------|-------------|-------------------|------|
| 狀態 | 病人狀態 | 轉出結案,追蹤中,轉出 |  | VARCHAR(255) |
| 編號 | 病人編號 | 由1開始 | VARCHAR(255) |
| Name | 病人姓名 | | | VARCHAR(255) |
| ChartNo | 病例編號 | | | VARCHAR(255) | 
| Dr. | 醫生姓名 | 楒歆彤, 泓溫碧, 浚潔綉, 馭曦瑾, 巧琇嫻, 香靄晞, 淑翩芷, 揚墨醇, 琪翩嫣, 祐暄彤, 渝雲棻, 奕嫻淳, 瑾瑗儷, 綽卉卿, 瑜釧卿, 旻儷  涵, 巧琇嫻, 雅曦暄, 嘉勻寧, 庭雍淑, 卿凝華, 靈芷禎, 翩爽雲, 惻文涵, 承儷霓, 羽幃嫻, 奕嫻淳, 華芩儷, 晁采蓮, 逸凌雲, 儁瑾瀅, | | VARCHAR(255) | 
| Gender | 性別 | 男女 | Female  Male | VARCHAR(255) | 
| Birthday | 生日 | | year/month/day or year/month.day | VARCHAR(255) | 
| Age | 年齡 | 年齡 | | FLOAT 
| 收案日期 | 收案日期 | | | | VARCHAR(255) |
| EchoDay | 超音波日期 | | | VARCHAR(255) |
| Dignosis | 醫師診斷 | negative, no focal lesion,lesion could not be found,regeneration nodules,... liver biopsy(肝臟切片) | VARCHAR(255) |
| HBsAg | B 型肝炎表面抗原(HBsAg)「陽性」或「反應性」HBsAg 檢測結果表示此人已感染B 型肝炎病毒，可能是「急性」或「慢性」感染 | positive, negative, 缺 | positive(陽性), negative(陰性), 缺 | VARCHAR(255) |
| 檢驗日期 | 檢驗日期 | | | VARCHAR(255) |
| HBeAg | B肝e抗原(HBeAg)是pre-C/C基因的產物，當B肝病毒增殖時此種基因可以在肝細胞中發現 | positive, negative, 缺 | | VARCHAR(255) | 
| 檢驗日期.1 | HBeAg的檢驗日期 | | | VARCHAR(255) |
| GOT | GOT的全名為天門冬胺酸轉胺酶（Glutamic Oxaloacetic Transaminase，又稱ASpartate aminoTransferase（AST）| | | FLOAT |
| 檢驗日期.2 | GOT的檢驗日期 | | | VARCHAR(255) |
| GPT | GPT的全名為丙胺酸轉胺酶（Glutamic Pyruvic Transaminase），又稱ALanine aminoTransferase（ALT）| | | FLOAT |
| 檢驗日期.3 | GPT的檢驗日期 | | | VARCHAR(255) |
| Anti-HCV | C型肝炎病毒抗體 | positive, negative, 缺 | VARCHAR(255) |
| 檢驗日期.4 | Anti-HCV檢驗日期 | | | VARCHAR(255) |
| 6MFollow1 | 六個月後追蹤的月份 | 月份 |VARCHAR(255) |
| OPDDay1 | 門診月份 | 月份 | | VARCHAR(255) | 
| EchoDay1 | 超音波月份 | 月份 | |VARCHAR(255) | 
| Dignosis1 | 醫師診斷 | 同Dignosis | 同Dignosis | VARCHAR(255) | 
| real_age | 實際年齡 |||FLOAT|
  
