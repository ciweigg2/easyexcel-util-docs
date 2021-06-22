## EasyExcelWriteUtil-easyexcel写入工具类

easyexcel写入工具类

### write-无模板写文件

无模板写文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| head | 表头数据 | 列表 |  |  |
| data | 表内容数据 | 列表 |  |  |





### write-无模板写文件

无模板写文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| head | 表头数据 | 列表 |  |  |
| data | 表内容数据 | 列表 |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| sheetName | sheet名称 | 字符串 |  |  |





### writeTemplate-根据excel模板文件写入文件

根据excel模板文件写入文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| templateFileName | 模板文件名称 | 字符串 |  |  |
| headClazz | 表头模板 | java.lang.Class |  |  |
| data | 数据 | 列表 |  |  |





### writeTemplate-根据excel模板文件写入文件

根据excel模板文件写入文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| templateFileName | . | 字符串 |  |  |
| data | 数据 | 列表 |  |  |





### write-按模板写文件

按模板写文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| headClazz | 表头模板 | java.lang.Class |  |  |
| data | 数据 | 列表 |  |  |





### write-按模板写文件

按模板写文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| headClazz | 表头模板 | java.lang.Class |  |  |
| data | 数据 | 列表 |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| sheetName | sheet名称 | 字符串 |  |  |





### write-按模板写文件

按模板写文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| headClazz | 表头模板 | java.lang.Class |  |  |
| data | 数据 | 列表 |  |  |
| writeHandler | 自定义的处理器，比如设置table样式，设置超链接、单元格下拉框等等功能都可以通过这个实现（需要注册多个则自己通过链式去调用） | com.alibaba.excel.write.handler.WriteHandler |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| sheetName | sheet名称 | 字符串 |  |  |





### write-按模板写文件

按模板写文件

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| outputStream | . | java.io.OutputStream |  |  |
| headClazz | 表头模板 | java.lang.Class |  |  |
| data | 数据 | 列表 |  |  |
| writeHandler | 自定义的处理器，比如设置table样式，设置超链接、单元格下拉框等等功能都可以通过这个实现（需要注册多个则自己通过链式去调用） | com.alibaba.excel.write.handler.WriteHandler |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| sheetName | sheet名称 | 字符串 |  |  |





### writeInclude-按模板写文件（包含某些字段）

按模板写文件（包含某些字段）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| headClazz | 表头模板 | java.lang.Class |  |  |
| data | 数据 | 列表 |  |  |
| includeCols | 过滤包含的字段，根据字段名称过滤 | java.util.Set |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| sheetName | sheet名称 | 字符串 |  |  |





### writeExclude-按模板写文件（排除某些字段）

按模板写文件（排除某些字段）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| headClazz | 表头模板 | java.lang.Class |  |  |
| data | 数据 | 列表 |  |  |
| excludeCols | 过滤排除的字段，根据字段名称过滤 | java.util.Set |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| sheetName | sheet名称 | 字符串 |  |  |





### writeWithSheets-多个sheet页的数据链式写入
ExcelUtil.writeWithSheets(outputStream)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

多个sheet页的数据链式写入
ExcelUtil.writeWithSheets(outputStream)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| outputStream | . | java.io.OutputStream |  |  |





### writeWithSheets-多个sheet页的数据链式写入
ExcelUtil.writeWithSheets(file)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

多个sheet页的数据链式写入
ExcelUtil.writeWithSheets(file)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| file | . | java.io.File |  |  |





### writeWithSheets-多个sheet页的数据链式写入
ExcelUtil.writeWithSheets(filePath)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

多个sheet页的数据链式写入
ExcelUtil.writeWithSheets(filePath)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |





### writeWithSheetsWeb-多个sheet页的数据链式写入（失败了会返回一个有部分数据的Excel）
ExcelUtil.writeWithSheets(response, exportFileName)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

多个sheet页的数据链式写入（失败了会返回一个有部分数据的Excel）
ExcelUtil.writeWithSheets(response, exportFileName)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| response | . | javax.servlet.http.HttpServletResponse |  |  |
| exportFileName | 导出的文件名称 | 字符串 |  |  |





### writeWithSheetsWeb-多个sheet页的数据链式写入（失败了会返回一个有部分数据的Excel）
ExcelUtil.writeWithSheets(response, exportFileName)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

多个sheet页的数据链式写入（失败了会返回一个有部分数据的Excel）
ExcelUtil.writeWithSheets(response, exportFileName)
.writeModel(ExcelModel.class, excelModelList, "sheetName1")
.write(headData, data,"sheetName2")
.finish();

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| response | . | javax.servlet.http.HttpServletResponse |  |  |
| exportFileName | 导出的文件名称 | 字符串 |  |  |
| writeHandler | . | com.alibaba.excel.write.handler.SheetWriteHandler |  |  |



