Why MongoDB?
  > - 与关系型数据库相比，面向文档的数据库不再有“行”（row）的概念，取而代之的是更为灵活的“文档”（document）模型。通过在文档中嵌入文档和数组，面向文档的方法能够仅使用一
条记录来表现复杂的层次关系，这与使用现代面向对象语言的开发者对数据的看法一致。    
  > - 另外，不再有预定义模式（predefined schema）：文档的键（key）和值（value）不再是固定的类型和大小。由于没有固定的模式，根据需要添加或删除字段变得更容易了.
  > - MongoDB的设计采用横向扩展。面向文档的数据模型使它能很容易地在多台服务器之间进行数据分割
  >- 可写javascript

Basics:
  > - 文档(Document)是MongoDB中数据的基本单元，非常类似于关系型数据库管理系统中的行，但更具表现力。每一个文档都有一个特殊的键"\_id"， 这个键在文档所属的集合中是唯一的。
        - 文档的键是字符串,区分大小写     
  > -集合（collection）可以看作是一个拥有动态模式（dynamic schema）的表。MongoDB的一个实例可以拥有多个相互独立的数据库（database），每一个数据库都拥
有自己的集合。   
       - 集合是动态的，甚至可以存放类型不同（一个是字符串，一个是整数），键也不同的文档   

Types:    
  1. null   
  2. Bool   
  3. float64    
  4. NumberInt("3")    
  5. string   
  6. Date     
  7. regex    
  8. list(可包含不同数据类型的元素)    
  9. 内嵌文档(document)    
  10. 对象id(是文档的唯一标识)    
  

