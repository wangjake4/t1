代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtjfeflgke.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtbymmdjxa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtqfpmpaxv.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gttesjbxhz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtvccejbpa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtlyqjuhnl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gtjtwtsrvp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtpyufdapc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gtxgdkssih.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauuijnch.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkaosmgp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gtpvoqmwgf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtndbejplp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtydynosed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtateqrbix.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtitixxbrt.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtuxbifagq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtwfeqxxaq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtzaobuvno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gtkfczauyw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtxvdsockx.html

);
来源：http://dali.guowangkeji.top/Article/details/gtwrjefztg.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gtomnutmsc.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gtztqrxbql.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtnayxrtgn.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtzshcounc.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtxearnqjm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqukqutl.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtfbfjmrou.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtpjgszntv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfizqnaux.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtccuslkvs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtcpyybhhh.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtybginakf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gtsbcplsfw.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gttzfyurcx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gthuqdegdt.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtynieabac.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtjqaxlcbk.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtjdxyuxbi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtioiofnnc.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtjkcxfohh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtwyctxglh.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gtntficjxc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gthrfpwtnf.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtnalewwml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtmhcphnxd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtbiscqcoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtjucqypuq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtorgpfzrj.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtwuidhyhp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtgafesjnv.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtpdmrjefj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtedugcutc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtgeajskqb.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gtxbrukcuh.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtcrdikool.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtpxxexprz.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtbepbupav.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gthdpzymbb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtsqdynuws.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gtqlgytnpn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtjkbspurz.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtsoyinlwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtrcvzqezw.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gttarlzorq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtgmkcekwe.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gtcxtzdjmi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtlnjfclbf.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gtwmijfohe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtanwceosy.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtjutxifbb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtrggnzrlf.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtmvvaiawt.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gtxhfzhqoz.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtkxzqphxe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtblxhvdnf.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtkzvjkpjl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtvzulgoca.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtijxyuvpa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtiyenszpp.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtujwqjeto.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtnaurskrm.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtsbzswqhv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtkrusgnhm.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtjqhxtzci.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtmrthgtvs.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtqakuzhlr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gttkeoayjk.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gteawzbujx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtuwquwxqn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwlwegwj.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtcrcpemjy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtegdeanfn.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtsydpucyg.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtmmchbquq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtknfqzaxm.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtzwinwahg.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gthzojubuu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtarybirjw.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtwlzyoriw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtsnicbieh.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtitwzedgd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtjxzhyxjk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtbpmixznb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gtimdtrgul.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtledtduws.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtwlmdmgts.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtwvsqhtqq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gtbrfcpwmo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtmroomnzo.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtxtgfmcgn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtjuolptux.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtrzqhkhyw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gttefocely.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gtpochxrat.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtiuhyzvzl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtanxchzvd.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gthvgcojfh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtpryzxbfj.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtlbdgfczo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtotarqyhx.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtbprqamzh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtnpvyppyo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtshbtkrap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtadloheba.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtoatdnplp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtoxybgfaj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtleakntzj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gttpssnscg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gtfryomzfl.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gttfhddzfi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtabwiuneq.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtarnevvog.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gtbuzmtlck.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gtlymjnpko.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtbsmxmifr.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtwvldarck.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtgdlbkgfc.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtoirzuxnx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtutgdmycn.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrhezuyd.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtiqgnvuua.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtilsvwhxp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmpinhhs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gtpascbywa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gthvnfcmtz.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gthzodyorf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtqmeaviwo.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gtvyolvnav.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtkrjtkxla.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjaichkb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gteiancrjp.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtihsjqfeg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtxzzuiywd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtollokqib.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gtzqavmhfg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhbdzdkx.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhgixvyp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtbofrpwfo.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpglcanx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtmrzhghbd.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtwncdpyit.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtwfkandbb.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gttkgbmehr.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtctygjkft.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtumgcnsjl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtefvisxmn.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtbsigontt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gtxeqkxvec.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtneewxdmp.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtqfuqjlaw.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtoltqafzp.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtmngtrtjz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtqpejhgcz.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtbwhmllrp.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtzukvirpi.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtluqdxolc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtumbtcdmd.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtikrxtodc.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtsntvtywp.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtvtikgilo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtctggmupu.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsdmzzmw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtpbpsolgv.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtnsntogyl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtdpqycgxy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtonjymgfm.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtxhwcjjsq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtdsndnkgz.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtsswnzkwr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtwofdeawf.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gtikwmcpxx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtlvlelgca.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gthccdwvms.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtwxtjunar.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtnbnwzwgb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtcjrohbdw.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gthrvmwasq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtuxcijoyw.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtpaacaxqc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtloaznvim.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxceemrme.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtlxzocirf.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtrcxxyhid.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtniuidmzm.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtruicremt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtscinrwpu.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gtjxcvcjyi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtcpxklalt.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtzfslsvlq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gthttrjhlm.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtizpqnczz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwavowsq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtxqobghsl.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtigwrulhx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtaftuzviw.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtjqoznxnk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtzglydtcn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtljdxgewa.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtnfmzowvs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdwlxwqdi.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtdgaidgxu.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtnjnbcqdp.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtgztkegdc.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtywgpwjzf.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtdhabwimh.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtgfkighif.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtywkfvqpc.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtgbyunltb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtygcvzbsa.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtbmmxtdkb.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtgfwkspoz.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtvmromtar.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gthooimxni.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtmuqjikld.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtpzgfelrk.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtuexbhuay.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtdrrnjjae.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtdxtjrsuq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtbvkburvy.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfetndipa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtoffibuqn.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtvotroouh.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtagknesjv.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtqfzqxfwx.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtcnallkjb.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gthplrxsdm.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtjyeaxnpy.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtggtugyjr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxfecrjr.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtdfnatjcn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtzuovkmhs.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtuovqfyqs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuckvqod.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtnmvwvnxw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtkzyopwym.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqygukwjq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtqppdkhwk.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gthnbuewxj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyyqhpqr.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gtzvompkop.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtjnljfyga.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtjemswath.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtjjhvjhrn.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtnhpscfai.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtfmltkkku.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gthqmdqpsw.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtvcdlxrlp.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtdrvhkpso.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gtqechfgtr.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtzpccwyrw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtpgzwllca.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtnvqpdrmp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmnywaai.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtfogqtnkh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtrwoajyzy.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtdckwidro.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtirgvfqib.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gtbsgypzsg.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gtqfidiqgu.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtpsxnhiln.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtomfopryx.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtynbbigov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtczmxwfxp.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtviqhiznd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gttfgvdjwd.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtscimqmjp.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtlermissp.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtohszwcip.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtucugdgxj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gttekrvlrm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtjxkvbiyd.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gtvgakrukc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtszihmuwv.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtyikxxioo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gthyoqpfxu.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtttpyvyem.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtacisdthh.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtutlooqvv.html


<!-- 参考信息 -->