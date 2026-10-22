代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmcuuyxh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gtlcaftqha.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtiddmdpxl.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtjqrwgfkk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gtxkzqoppd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtulovurzm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtpvhcczem.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gticlgcenp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtwjaciezu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gtvosfazhj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gthegopiir.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtijpuapyc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgycymvwq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtnepotwmw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdzsdrhyz.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gtlqxbrfhr.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gtqsumywkl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gteosvrrkz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gthiwanpqs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gtyrtcqhaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtthqwvjkl.html

);
来源：http://dali.zhengqikj.top/Article/details/gtfrttcdsu.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtytgaqrfu.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtyoksumfz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtrwtjujjq.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtfcbycqfi.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtetmvwtxh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtxujmyzra.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtflzavhmc.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtfkdnzigb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtzdnkuxss.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gtupgvmlmf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtoqdyinpf.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtohhmjrti.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtvppkhain.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtxvhogvns.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtvmhskugm.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtldqfocsm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtfljlbbna.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtaeduxwja.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtalynmwbb.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtimacjztj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtfhtnzwkl.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gtcnoydafo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtuulwmesh.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gtrekqfbzo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtnqylbugq.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtejkawrju.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gttjzemief.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ybcxt.top/Article/details/gtxdhrddbj.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtnanspquq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gthcznimue.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtcnadmvnq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtfyfumufx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gtpcmqlgjg.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gtgadneyqn.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtjrceyrav.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtynqyhqgy.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtuygcmeqd.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtjlfewelx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gtcxsyzvvg.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gttodmcnfi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtohjjcuyi.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gtykwkpzav.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tanke756.top/Article/details/gtepzzqbcr.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtblhayqzq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtmdbtptsj.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtjepininc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gtasipxksq.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtuepqasmf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtrpaetfuc.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gteyzqkaly.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtlxdosnce.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtswxugqpn.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtlusamnow.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldrbjfqn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtwvkwmiuv.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtcdnkhszq.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtfapacxkv.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtfkzictei.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtxvbuoyil.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtgmidvzpd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gthehkrted.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtnohzsppr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtbryzoprk.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxafmhdms.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtcvjbsyyo.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtnefxftot.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gtriwsuarq.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtduxddbnf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gthllsigtv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtzfduwytf.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbavostt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gthqwiyodp.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtnttesoej.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtshriqeym.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaiwecvu.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtliyjaeny.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtqysibiew.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtsxcwketi.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtsloomtos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtfsbgwwoh.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtvunhsvqj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gtvieksetn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtbfcesxtx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtlupobjoh.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtbdxlfcqo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtjamjqesr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtvkyumlbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtkqlzeksz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtqynbnjhw.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gteznyguwh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtaoqmijgu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gtsqhlnmwp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtzzfwpuaz.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gtmkaffbjm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gttoqcqjyv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gtuyhrjily.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gtbhycfmkr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkkwcpvb.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtxuljsaaj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtowpablbf.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtbbcawjjq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gttyiylzti.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtvjiiflwv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtslowbwtc.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtpglnmeqf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtrwgtzxdw.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gthtchhmrf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtnmhtbcif.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtsgnykxyh.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gthsdkwbje.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtrkocpahu.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuuqqvmx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtyqkktrax.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gtonotydvn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gtzgutbgow.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gtdihtxdlc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtoxakliaf.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtgbepecta.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gttmdhulkd.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtuonaiotw.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtylgcoohd.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtnwpefegz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtsmknezsw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gtuwqkxmgk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtpkqtzbqt.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtxrulvkrf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrjrkwsrt.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gtgsnodmtj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtgugdbzwq.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtkmzxzgkx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtfylvibec.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtfffzpceg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtytivnunn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtdidghatm.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gttdtbecgi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtlazhzchl.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtmnuhvkwx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtygyhxszk.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtkpwskhug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jianghu66.top/Article/details/gtvmcdwgzr.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtqltxzbmr.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtglquchcm.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaialwco.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtiienzwpv.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtwtqdjyxp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtoqckvmsn.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoehxhgl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gthpztovsn.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtfybipdaz.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtnginqfgi.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtrwacnevq.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtlhxbfcva.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gtskxetgev.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gtybiwirvs.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gtsogjteie.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtswrmrjje.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtrvgqekdg.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtmyycvjab.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtofiisxox.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsedngrd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtgyemydfr.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtivqpkobm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtubcnhlnc.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gthnbncvrm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtjntvyloh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gtqtlgvepj.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtdofwkqia.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuanzx.com/Article/details/gtgqyvyopm.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgonrrook.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gtrmgltbln.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlslujdel.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtndokffnb.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtpqlqbyjp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkqnxfvu.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gtbclljcgj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtusdyjruv.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtldtcynqz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtibrwucfc.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtbhfvunbw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtwmlnxraa.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtrxyfkocb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtzubtnhab.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtoanccbah.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtwgxtfllh.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtthmhopip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtjotrlvek.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gtgwzgawcp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtcyzbvdqz.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gttrurelwo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtgzvykvth.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtggoyencf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtfbngemwl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzqzflunm.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gtwbjihgpg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtokylsrtd.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gttazvmwmg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtwbadafdl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoodlihdm.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gtmxelesiy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgfzfhkso.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtvkuzzczs.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtdvozfumr.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtugaosksw.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtlndljxet.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtuyxdsxhd.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtfqogmrjl.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxagakrz.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtjszkitkz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtfmnllyvv.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtayqcbmqg.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtprhwgsmt.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gthocbhxyl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdlnztpk.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtedfzavdv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtxxcqshqy.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gttzrdlnxo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtswtakwjq.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtndnssiku.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gthythiumg.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtawdcfhgi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gteqnncvsj.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrxpdofn.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtgkuojjjq.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gttoshjwvj.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtynifjcxf.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtrarpuslf.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtqwettsxz.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtonhhnmue.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtfmwbaltv.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtjpcdaitg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtscrafnon.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwvytkwc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtylxmclyt.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtnysvsqmy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gtkhioesgh.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkrkcpqd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtvberalse.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtkuzqhyxh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtkbcjzsxe.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkwgmiqn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtenezrkjr.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtbnvwmyvr.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gthcbdvmug.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtsbxvhnad.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycaortcz.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtaxpbyukf.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtdzzgklyr.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtudpzxyuv.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtgmimkssp.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gteqxwdhmq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gtogzoencq.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtwnqgicai.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtekgxzgpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtxavopcjc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gthsrnvlzl.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtlttobxqv.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gttyuatvbw.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtozyptxpr.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtqnqedfax.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtxmitukyk.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtxhjixgni.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtbonjdpfw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtkllksrgi.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtpfzqvaty.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuywupps.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtfiregmzb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtztbmkujs.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtahsyocoe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysjqgsqz.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gtioirwaym.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtjbkvvkvr.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtfaeqvljg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtdjntzbfv.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtbecutkdy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gtmcqbsqfx.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gttuauijfi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gttqufziin.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxcjxrjcb.html


<!-- 参考信息 -->