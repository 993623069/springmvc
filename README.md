//RequestMapping注解类的属性，
//分别由 value, method, consumes, produces, params, headers
//vaule的用法有两种分别是，value是请求的路径
// （1）@RequestMapping(value="index")
//（2）@RequestMapping("index")
//method属性是用于请求的method的类型
//分别是，GET、POST、PUT、DELETE等
//用法 
//（1）@RequestMapping(value="login",method=RequestMethod.POST)
//（2）@RequestMapping(value="login",method=RequestMethod.PUT)
//（3）@RequestMapping(value="login",method=RequestMethod.GET)
