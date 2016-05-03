# mybatis-generator-limit-plugin
A MyBatis Generator plugin for MySQL pagination use limit.

```
<generatorConfiguration>
    <context id="mysqlgenerator" targetRuntime="MyBatis3">
    	<plugin type="com.xxg.mybatis.plugins.MySQLLimitPlugin"></plugin>
    	...
    </context>
</generatorConfiguration>
```