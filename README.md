注意事项：  
    1.这是一个用于自动生成MVC三层结构模型的文件，Controller，Service，ServiceImpl，以及实体类Entity。  
    2.那么对于DAO层的Mapper文件，建议使用mybatis-generator来生成。  
    3.建议生成步骤先使用mybatis-generator，再使用/src/test下的测试入口，这样模板生成的实体会覆盖mybatis-generator生成的实体。  
    4.可以修改模板来满足自己想要的效果，当然也可以添加模板，添加mapper的java文件和xml文件来生成全套的代码，就可以不在使用mybatis-generator。  
    5.使用者可以在本项目中生成文件，再移到自己的项目中。在本项目中生成的文件都在com/march/coderobot/out目录下，包括mybatis-generator生成的。不太建议，因为包名需要修改。  
    6.也可以将com/march/coderobot/util目录下的Robot和TableMapper，以及generator.properties文件移到自己的项目，然后修改生成文件的路径，就可以直接在自己项目中的对应位置生成文件。建议使用这一个。  
    7.因为每个人的开发习惯和所在公司的代码规范不同，我认为修改模板来达到自己的要求是必要的。我的模板只是满足我一个人的需求，以提供参考。  
    8.代码都很简单，欢迎使用。