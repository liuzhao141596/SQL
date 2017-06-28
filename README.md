# SQL
SQL 使用相关

DECLARE  @d DATETIME
SET @d=GETDATE()
 
--do something 
--for example
SELECT TOP  10000 * FROM   dbo.Fct_Order  WITH(NOLOCK)  

SELECT [语句执行花费时间(毫秒)]=DATEDIFF(ms,@d,getdate())

--datepart	缩写
--年 	yy, yyyy
--季度 	qq, q
--月 	mm, m
--年中的日 	dy, y
--日 	dd, d
--周 	wk, ww
--星期 	dw, w
--小时 	hh
--分钟 	mi, n
--秒 	ss, s
--毫秒 	ms
--微妙 	mcs
--纳秒 	ns
