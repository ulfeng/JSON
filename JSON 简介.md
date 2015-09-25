#### 什么是JSON?
    JSON:JavaScript Object Notation(JavaScript对象方法)
    JSON是存储和交换文本信息的语法。类似XML.
    JSON比XML更快、更小、更易解析。
```json
{
"employees":[
{"firstName":"John", "lastName":"Doe"},
{"firstName":"Anna", "lastName":"Smith"},
{"firstName":"Peter", "lastName":"Jones"}
]
}
```
#### JSON - 转换为 JavaScript 对象
    JSON 文本格式在语法上创建JavaScript对象的代码相同。
    由于这种相似性，无需解析器，JavaScript程序能够使用内建的eval()函数，用JSON数据来生成原来的JavaScript对象。
```javascript
window.onload = function () {
            var JSONObject = {
                "Name": "SunLifeng",
                "Age": "22",
                "Address": "河南省唐河县大孙湾村97号",
                "Phone": "15603601222"
            }
            document.getElementById("jname").innerHTML = JSONObject.Name;
            document.getElementById("jage").innerHTML = JSONObject.Age;
            document.getElementById("jaddress").innerHTML = JSONObject.Address;
            document.getElementById("jphone").innerHTML = JSONObject.Phone;
        }
```
#### JSON与XML
###### 与 XML 相同之处
    JSON 是纯文本
    JSON 具有"自我描述性"(人类可读)
    JSON 可通过 JavaScript 进行解析
    JSON 具有层级结构(值中存在值)
    JSON 数据可使用 AJAX 进行传输
###### 与 XML 不同之处
    没有结束标签；
    更短；
    读写的速度更快；
    能够使用内建的 JavaScript eval()方法进行解析；
    使用数组；
    不使用保留字；
###### 为什么使用 JSON?
    对于AJAX 应用程序来说，JSON 比 XML 更快更易使用
    
    
    
    
    
    
    
    
    
    
    
    
