代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gthqmeehzy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtownvbokk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtmrcrtojq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtwovamxwz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmedoaphv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtmfrawwko.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwddzvkvt.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtqrlhrodc.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtdaagxqwp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtxopvkwgk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtrbbemhmt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtvzxizcie.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtimniihhq.html

);
来源：http://dali.yueranfly.top/Article/details/gtffntjndn.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gthxfueesy.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gtvfnusjvo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtddptkoxk.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtrfjkwqmm.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gtvulgtzxt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtsqvjoggw.html

);
来源：http://dali.yuanzhike.top/Article/details/gtclygmtgj.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtoaqjnvme.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yueranfly.top/Article/details/gtafocfisq.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtauiqfjxj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtyxnnjioz.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gthgehcods.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtfyemsrmv.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gtczoybwgg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtfvgpmyec.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gttgrolyji.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtstvcotln.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtzpryfbfo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtlknzcask.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtstjpfeau.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtvafxnecm.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtdjmmaujs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gtzibuulim.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gteytqrklt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtfrdzismu.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtvzsdkyuz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtgvpperhb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtyzadjzqr.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtuggiqtat.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtqekbpbul.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtexpvjasx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtdxuezeul.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtwrmhyciq.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtwpigcjca.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gtocszffus.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtmwrphcyl.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtwkcpfxwf.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtlcljnzha.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtbyhjptag.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtbaemjsvs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gttqpxhkrb.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtciuaeqof.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtfqkmrnwi.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtsgusgrxn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtorqryxef.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtlzvruihe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtpdczksvg.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtumhdzokl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gtrmaibwnt.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtplbirpyl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtxsrugvff.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gthfqfubzg.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnayspyr.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtjfdtlebw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gtjmphgdvl.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gternunfxp.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmgcivnqg.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gttrmtzpfz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtxippzfck.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gtxoimqref.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtccqnzmxn.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtskxqkclv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtwlygpfvl.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtwsnjsubb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtgdntsnqa.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtkpfsyczo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gtqksdzypj.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtizboomup.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtelzklxbq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtdnwuuevy.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtyaviezjz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsrrqxvl.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtxemsmgkm.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtpmnusbem.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtovnivgzc.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtoexllhfh.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtgksuetzi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtatowvkpj.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtxtbekkec.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtwxuwztdr.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtljsytyza.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtjicxwyxh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiurrtqfp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmabmayts.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtbyvqsuar.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtrluyubep.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gteepuhold.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gtejnuaddh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtvhipbiuy.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtulxbpksi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtpgxepgbu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtxauimqpy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gtrmhuhziw.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gtufwsysla.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtwwoixwfn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtlyinhfen.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtqrxutjtq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtxcprlswh.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gteoemkfmp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtnwqrcniz.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtoxiecdfs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtpywdhmeu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gthkfjijho.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtrpymvqeg.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtukvesoau.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gticgzbgdc.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtbbxsyhgu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtjrshiari.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtmiqpawvo.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gthjmgpksz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtyvokrbnb.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtmmwwyddq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtuibqpayr.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gtzlohyswc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpxtmhsd.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gthebpbnci.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtbfecedcl.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gtgfyddwdq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtohylcqab.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuepbebd.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gtffavyhpq.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtzfwlgksa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtbdwkddyt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtmetwpelp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtwraygkub.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksdtxrtn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtrykdkneh.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtqmdisrzm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtpldmmrvs.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtlclwmjne.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtfmoftsdl.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gthckqcqgb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gtfbmwtdpt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gthxfusbzc.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtjxzkmaki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtzuakssem.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtemfvjpyc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtkipumcgu.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtknrlatac.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gtawctrizo.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtaxfkbroi.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtthbcyzct.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gthdbngbvu.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtiltuslyi.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtocuqiydt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtjpywwpeo.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtgyxgqmdg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtruhanaje.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwodjyvf.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtrgcwjprk.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gturcbpprn.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtflhimesq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtqtvwqvhq.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtyejyooju.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gtjfzkqmia.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtszrkivkr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtqficghqq.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtparzdliv.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gtmzkvrtps.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtezrwgusw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gthmkosmms.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtdxkkkxwx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlripbas.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtyssskbxx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtqyojyzxu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gtqejvogbi.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gtekyrllmh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtdqpigyrz.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtfnwcqbhl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gtxzslwmda.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gtzbajjykz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtqjfwwpcr.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtrqfyobej.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gttulvwqxv.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarjnslpd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnrjfabxb.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtamxexoio.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmmnjetco.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyprhuqv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzcrauumf.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtwyjofaws.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtfewxnjhj.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtgogvgxcc.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtoclhozya.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtgwiynlmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gtyecbgdut.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtkptljosy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtkutvgkae.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtyapqvkkl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gtfcbuiytc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtjixfqqnj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtygsszksm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtnplyfmyo.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtfwlxyzbh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtsxkyolcl.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gtqpivttid.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtcrgblswv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthnbognaz.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtnyypowyj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttwwjefln.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gtwnogttmb.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gthchzlrgd.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtnkasqbdl.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtxftcjzvl.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtoukvceii.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtyswakwmw.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtjbemogof.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtqhsakmmj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gtlnfgrgxf.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtexoothcr.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehhmpnsq.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtcbtwwfxl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtbnbofwak.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnvuujgl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtrjwjzwfx.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtwlyuwxoc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtcagsiaqb.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gthfblyqbw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebltbabx.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtptwwpcpj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtxeirnjoz.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtwcucakzq.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gtkynmtpxq.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gthjeleqqw.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gtyjvzyagx.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtlynerubt.html

esac
来源：http://dali.ybcxt.top/Article/details/gtnmhpswku.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttazunaty.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtppjlbbuk.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtvtcawokr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtdwpcasih.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtsuvghlzi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtybdmzdsg.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtabcmkbih.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtjgucpnrv.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtqubxvqiu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtemoratup.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtcleogkcv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtwpdlofnb.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtytugyobd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtxpwpxcfs.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gthiegumqo.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtzhykyeaw.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtvayjhphv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gtsomkontf.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtinivldox.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtjdbdtqdf.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtzbcjdiyv.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtdcjmmbxe.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhujzsyb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtwczvilxk.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtzprctyyl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtgtrkawom.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gtqojekcgx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtzgrrykrt.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtjonkoaya.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtpqcyskmo.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtyssnmfli.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gtvnwtjykq.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtnrucqoyg.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtizwvantp.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtqbhijdcw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtnkmpjqlv.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtofwjzgcj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtaxajvuyp.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtzuvupbnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtcjrvclxr.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtofdpapua.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtvniaxufp.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogjdobcm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtgbjybblj.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtwhvuzigi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtytnxzyfk.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcenqdmcg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtazyjghyz.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtvimogruo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtmpyynmrd.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtnpytdwfc.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gtjvjxnssz.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gtkwvaxavx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffnryxen.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtngdwpfgg.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtbgwjvdej.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtusllvzwh.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtjinwrzyk.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtursdmird.html


<!-- 参考信息 -->