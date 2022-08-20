### NPM地址
[l-multiple](https://www.npmjs.com/package/l-multiple)
### 安装方法
````bash
npm i l-multiple
````
````bash
yarn add l-multiple
````
### 使用方法
````js
import multiple from "l-multiple"
/**
 * @param {number} value 			        进行判断的值
 * @param {number} [multiple = 10]	        指定的倍数
 * @param {number} [min = 0] 	 	        限制最小值
 * @param {number} [max = Number.MAX_VALUE]	限制最大值
 */
const data = multiple(100,20,10,10000)
````
### data 返回值解释
````js
find: true  param1是param4的倍数
typeErr: 0  param1类型有没有错误，必须是number类型
intErr:  0  param1是不是小数或者param1不是param4的倍数
minErr:  0  param1有没有小于param2
maxErr:  0  param1有没有大于param3
````