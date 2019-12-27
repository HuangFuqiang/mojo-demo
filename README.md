运行
```
mvn install
```

在使用的项目中引入：

```
<plugin>
   <groupId>com.code</groupId>
   <artifactId>mojo-demo</artifactId>
        <version>1.0-SNAPSHOT</version>
        <executions>
            <execution>
               <phase>compile</phase>
                  <goals>
                     <goal>hello</goal>
                 </goals>
            </execution>
       </executions>
</plugin>
```
