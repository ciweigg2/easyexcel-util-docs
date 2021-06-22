## EasyExcelReadUtil-easyexcel读取工具类

easyexcel读取工具类

### syncRead-同步无模型读（默认读取sheet0,从第2行开始读）

同步无模型读（默认读取sheet0,从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |





### syncRead-同步无模型读（默认表头占一行，从第2行开始读）

同步无模型读（默认表头占一行，从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |





### syncRead-同步无模型读（指定sheet和表头占的行数）

同步无模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | . | java.io.InputStream |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### syncRead-同步无模型读（指定sheet和表头占的行数）

同步无模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| file | . | java.io.File |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### syncRead-同步无模型读（指定sheet和表头占的行数）

同步无模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### syncReadModel-同步按模型读（默认读取sheet0,从第2行开始读）

同步按模型读（默认读取sheet0,从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |





### syncReadModel-同步按模型读（默认表头占一行，从第2行开始读）

同步按模型读（默认表头占一行，从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |





### syncReadModel-同步按模型读（指定sheet和表头占的行数）

同步按模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | . | java.io.InputStream |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### syncReadModel-同步按模型读（指定sheet和表头占的行数）

同步按模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| file | . | java.io.File |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### syncReadModel-同步按模型读（指定sheet和表头占的行数）

同步按模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### asyncRead-异步无模型读（默认读取sheet0,从第2行开始读）

异步无模型读（默认读取sheet0,从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 字符串 |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |





### asyncRead-异步无模型读（默认表头占一行，从第2行开始读）

异步无模型读（默认表头占一行，从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 字符串 |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |





### asyncRead-异步无模型读（指定sheet和表头占的行数）

异步无模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | . | java.io.InputStream |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### asyncRead-异步无模型读（指定sheet和表头占的行数）

异步无模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| file | . | java.io.File |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### asyncRead-异步无模型读（指定sheet和表头占的行数）

异步无模型读（指定sheet和表头占的行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### asyncReadModel-异步按模型读取（默认读取sheet0,从第2行开始读）

异步按模型读取（默认读取sheet0,从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |





### asyncReadModel-异步按模型读取（默认表头占一行，从第2行开始读）

异步按模型读取（默认表头占一行，从第2行开始读）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |





### asyncReadModel-异步按模型读取

异步按模型读取

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | . | java.io.InputStream |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### asyncReadModel-异步按模型读取

异步按模型读取

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| file | . | java.io.File |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### asyncReadModel-异步按模型读取

异步按模型读取

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| filePath | . | 字符串 |  |  |
| excelListener | 监听器，在监听器中可以处理行数据LinkedHashMap，表头数据，异常处理等 | com.alibaba.excel.event.AnalysisEventListener |  |  |
| clazz | 模型的类类型（excel数据会按该类型转换成对象） | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |
| headRowNum | 表头占的行数，从0开始（如果要连表头一起读出来则传0） | 整型 |  |  |





### excelHeadRead-读取Excel表头（默认读取第一行为表头）

读取Excel表头（默认读取第一行为表头）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | 输入流 | java.io.InputStream |  |  |





### excelHeadRead-读取Excel表头（自定义表头行数）

读取Excel表头（自定义表头行数）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | 输入流 | java.io.InputStream |  |  |
| headRowNum | 表头行数从多少开始 | 整型 |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |





### dataRead-读取数据（默认1000）

读取数据（默认1000）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | 文件流 | java.io.InputStream |  |  |
| baseProcessor | 自定义处理器 | BaseProcessor |  |  |
| clazz | 数据转换对象 | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |





### dataRead-读取数据（自定义读取数量）

读取数据（自定义读取数量）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | 文件流 | java.io.InputStream |  |  |
| baseProcessor | 处理器 | BaseProcessor |  |  |
| batchSize | 单批次处理数量 | 整型 |  |  |
| clazz | 数据转换对象 | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |





### dataReadValidate-读取数据（自定义读取数量并使用validation校验 只会校验batchSize长度设定的数据 如果在batchSize长度内有错误会直接抛出异常）

读取数据（自定义读取数量并使用validation校验 只会校验batchSize长度设定的数据 如果在batchSize长度内有错误会直接抛出异常）

#### 方法入参

| 字段 | 说明 | 字段类型 | 是否必填 | 备注 |
|:---|:---|:---|:---|:----|
| inputStream | 文件流 | java.io.InputStream |  |  |
| baseProcessor | 处理器 | BaseProcessor |  |  |
| batchSize | 单批次处理数量 | 整型 |  |  |
| clazz | 数据转换对象 | java.lang.Class |  |  |
| sheetNo | sheet页号，从0开始 | 整型 |  |  |



