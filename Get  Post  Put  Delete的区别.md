> 在spring boot中用了这么多

**组合注解(@RequestMapping的变形)**

- @GetMapping = @RequestMapping(method = RequestMethod.GET)
- @PostMapping = @RequestMapping(method = RequestMethod.POST)
- @PutMapping = @RequestMapping(method = RequestMethod.PUT)
- @DeleteMapping = @RequestMapping(method = RequestMethod.DELETE)

### GET

> GET请求会向数据库发索取数据的请求，从而来获取信息，该请求就像数据库的select操作一样，只是用来查询一下数据，不会修改、增加数据，不会影响资源的内容，即该请求不会产生副作用。无论进行多少次操作，结果都是一样的。

