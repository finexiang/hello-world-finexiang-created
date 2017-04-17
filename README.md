# hello-world-finexiang-created
for study purpose
hello friends,
Kate here!it is my first time get to know github.however i believe this step will lead me into a brand and grant new world!
#%RAML 1.0
Title: BMS local view threads API
baseUrl: http://3ms.huawei.com/hi/group/3106561/threads.html/rest/V1/threads 
list version: V 1
/threads:   
  desceiption:collection of available threads.      
  get:        
    description: get a list of threads based on the gid.       
    queryParameters:
      gid:
        description:the group ID of which threads were posted;
        required: true
        type:int
        example:gid=3106561  
    responses:
      200
        body:
          application/json:
            example:|
               "threads":[
                  {
                    "threadId":"6020889"
                    "threadTitle":"武汉代表处全员学习干部八条及十六条军规暨干部宣誓大会简讯"
    body:               
  application/json                
  example:                  {      
  queryParameters:         
  gid:            
  displayName:gid          
  type:int           
  descritpion: a group's ID           
  example: gid=3106561           
  required:true         
  ftype:           
  displayName:ftype           
  type:string           
  descritpion: thread categroy ID           
  example: fype=1416903           
  required:true         
  type:1:           
  displayName:type           
  type:string           
  descritpion: threads sort type:updateTime          
  example:            
  required:false         
  lang:           displayName:lang           type:string           descritpion: threads language           example: lange=all           required:false   
