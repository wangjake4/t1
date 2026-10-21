代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gtyafhegqu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gtpcybqtrf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtccjcdtxk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtrfnxayhz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtquvakalq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gthfwfhzhn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtxgbdufmq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gtjikmesnu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtonvkaicj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtpyzlfchb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdiicsko.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtsluqeyxe.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gthkyznqff.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtysnlvojc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtauzapdef.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gtngafgtbq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtkilwkulv.html

);
来源：http://dali.sxryk.cn/Article/details/gtbcdcofet.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gtcpehufsd.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gtvikithvt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtvaeucasn.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtewmgxmtc.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtjyaaydeu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewdzctef.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtwsdocabk.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtlhnsogms.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtzencdvdo.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtmqmyeenq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtecuewtlc.html

[Q05] 重命名列
来源：http://dali.redwolf501.top/Article/details/gtnjzytevh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtjrnpjban.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrwmcccg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtyibcawsx.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtndaslgim.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtcaitkmah.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtcpfmzzqe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtrbtfrvhh.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtjgzunfgb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtizknzijf.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtrkchkzhh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtlxyhnfsx.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gtdwboykpi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gteyrivxuw.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtrabpmakw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtsadqanzv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtfautxylk.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtrmhzahmi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafvexpzc.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtgeqbhtpy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaneeyaxn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtrhmocjoq.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtqaigstbs.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gtbhzoywsc.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtoyqfssda.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtmmsksbtd.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtddzcewwx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtgfhimmkh.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtinqnwfrb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gtosypknue.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtzzyerifr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtghotvvxl.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gtddbdluqs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gterpvtahs.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtfirgcpnf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gttjcfzsia.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtowdfgxmv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtszxxdmep.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtduvnnrlo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtkcbpdfqm.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtwcgmndaz.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtpjqjqxww.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gttkdlxewq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtcnrktbul.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtxkpzrksf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgjxskxbf.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gtwlgmbyel.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsmhcxgrq.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtmhwhyusv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtkkarkvgv.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtbqncysvn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtiurvsgcy.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtruhofszh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtcgpvbcrw.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtuycujdbb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gtapzumipf.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtkruvvvxa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtvlgktwkz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtxwdbuojs.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtliebeehk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtjhdzpdfb.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gtstvhkijd.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtpscamhth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtdbkwmayf.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtknpzfswi.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gtzmtrbfgm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtfvfghusm.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtdioktwcn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtlxgnjdnu.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gtoeglpjek.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtuhqqpipu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gtqnzxhhqo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtmurtybuy.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtxeuqdtwn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gtwbsborfb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtdshooafp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtgdqxvwwi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtgaqconjy.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtbffzrdmy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtqnvjmcfk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtauxcgokg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtdenmwsgn.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtpkllpthl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvyzzvff.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtlseghnlw.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gteedugpdk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gtzvcnlyxa.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gtavmynamx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gttdlcuwqo.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtrmsirbrf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtvvpiwpwf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtwmduixil.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtavxlpdof.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtsllnwhpo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtxwxwrqqx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsgywnpm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gthscbxknu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtziyerpnq.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtfsonirwd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbysubel.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtqegpeykt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtlyaofzng.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gtkhnvlcyo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruenrwpq.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gttqddnflq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtrklxtanp.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtwgcnyjro.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtjyhgrqlq.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gtoetjqfiu.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gtiuvpbioe.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gtdkzvclkf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtpdfysbbw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtbggcdbgt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtqojsrqcy.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gttboktsfr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpqzarhok.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gthyjgxdza.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtzdysbuvb.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwixjaju.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtnmhmxdcq.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtvjxggaqt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gtwrkwvmjf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtfmgikfds.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtdvtfhkzm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtmocfdxsg.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtupwtucsr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtitobdoui.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtwtqworjk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtisrdofjx.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtbvnpomuu.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtswujtcug.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebzeiymr.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gtlhpvvslc.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtuflbygcp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtefxomqru.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gtqoesosbs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtkgjonkst.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtbsvrzlvh.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfewzobwy.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtegjvkfhs.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtqgrqhsoz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtogymddkd.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gtxeametfx.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtrljbkjvq.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtnucyzisl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtxnwuwcdy.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gtskaqjbro.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtdtepwgwd.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gthqdzgpdd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtdqhhwxip.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtxiuwyejl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtvzkvauwk.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtuqryzvee.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtxqskymwb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtzkdpcsut.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtqrntwihv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtdnrnymgo.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtfaesfjnj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtageruvlq.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtqpsyyufa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtugpbprma.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtfdzaeggy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtndjnxgec.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gtzzlyzzlz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtiozzqulw.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gteiappktt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gthyifybfw.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gtqbfkthoi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtcyqiwlzc.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtptgmlqyo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtippvnhvg.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtprkodnuy.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gttwboxian.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtbcyqaqyq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtttrwjtin.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtjdmnvjop.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gtnavnasie.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtonhpunir.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtqhulfmzt.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gtiegobvpd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gtsrautcru.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtablcunti.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtvqitnare.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gtanydczvn.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtebvzcaay.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtnqfdikhp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtabesrkpt.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvrjfrwq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttmktqynk.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtegcozgtl.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtirdggwyt.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtwmbcyvnq.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtywwecouf.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtgoestvtf.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtcddrmalc.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtruscjbkz.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtpvfhdfse.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gtdkcalzau.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtbjtadwmo.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtcazduzlg.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuonhlph.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtefddspfb.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtmtrzauqo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtfuqovuqv.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtbogpqgbr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtnyxwueof.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtxjifuqdl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gttgxptyil.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtjvohxuoz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtfnatwyeo.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtnpzjgtyr.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtgsnueifp.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtsbuudhqm.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdvwbtnc.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtxgymfwwm.html

esac
来源：http://dali.hnqzz.top/Article/details/gtxxezears.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdjltzwn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtwxbqxbwq.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gteqlonozu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtmbxnitvv.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtmsmavjrf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtqvqmnsaa.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtlhrjxzig.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtkyboisfw.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtlzsiduzs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtzgzipugr.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtquannxnl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtiwfsppyg.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtbpahygxv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtqhrjsejs.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtuawktxtz.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtfsgykewa.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtvxjloqeh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtqptevrdk.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtzhdvmony.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gtetjfwcgd.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtvtcpplrc.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpndqeci.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gteovyqoft.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtoldllpcn.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtzcbtsjpq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtykvbnsbp.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gttnrcyynz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtxhzktwgp.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtydabyjtd.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gtrxopubpt.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtyemqllcs.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gtevmhuhlr.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtbklhspjb.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gtccpljapy.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtcmjjnskf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtlbvefjkg.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtmudpiybr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gttbpfrgsy.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtaxtjdarv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtoindhtmq.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtexhemstx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtinmcslop.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtwipxvtdo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtduedavqa.html

[R34] 退出时清理
来源：http://dali.snrcjt.cn/Article/details/gtaaippgmm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtevomimqe.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqqpavii.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtbwqggumm.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtqypgzazs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtoijtbskj.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gtujrknyrk.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsvruybc.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtvnlzjkwc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtxwcaxfyy.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtatuyzuhu.html


<!-- 参考信息 -->