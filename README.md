# mb2g-mapstruct

This maven project uses Mapstruct to create a Mapper class (UserMapperImpl.java) from an interface with annotations on the target/ directory. The generated class will hold methods that will return both ways the classes User and UserCommand, which hold the same fields and methods. 

By using simple annotations provided by the mapstruct dependency, we can simplify greately the effort of coding the mapper!
