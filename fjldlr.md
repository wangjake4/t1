代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gt2ttoepenl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2xdjhtioj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2yjfvntve.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gt2uydjrmhp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gt2coagfhnr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gt2jteuoimv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gt2grgvxupo.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gt2miqxtshn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2circhlus.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gt2mzbkddta.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gt2bzywkoov.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2vyilrwjg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gt2mxwizsdv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gt2mcrdcixq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gt2hvoglbwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gt2kwzlafoz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxxxrxnn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gt2koppbvdf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2lpoaadww.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gt2mskquvbn.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gt2ctmlvvvn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2uslrtdwa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gt2zuoilego.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gt2dwpyvfew.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gt2kmctsqtx.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2dqlpmoxz.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gt2qchbxhlz.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gt2ivecgthx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2lqbaltti.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfhewrde.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2zzzwtkeh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gt2bkddiesf.html

);
来源：http://dali.316326.xyz/Article/details/gt2tpbwwlko.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gt2jzlflqcy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiclougj.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gt2avgcgoul.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2elukyydr.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gt2hfqrjwca.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbzlesto.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gt2tirvasyc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gt2vpdiepro.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gt2bohjzcpk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dixjwojo.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gt2klubbkey.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2zzxjfncz.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gt2lcbjdpkm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2cnwxpgmw.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfxroflp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2nfngtoyf.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gt2yvhvytul.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gt2lzaxgqid.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2yurfaotd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gt2sjaxjjpq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gt2pbwqispv.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gt2cgwhkdeo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2qxugzfan.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gt2rholkxlw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gt2pobahlne.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmzknasl.html

[Q15] 查询全部
来源：http://dali.shuidangran.top/Article/details/gt2ndsivxpg.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gt2nfxoysux.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqrmcnpa.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gt2ermqjxag.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffeiskzu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2vafulwzv.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gt2jpyugfiw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gt2naamcuwv.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gt2pykpbesn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gt2tfnodkid.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gt2wrxoexyo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbzinjog.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouhlzgzy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gt2eaoykyrk.html

[Q22] 排序
来源：http://dali.sysykeji.top/Article/details/gt2tqhaddgw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2tfrijfcz.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gt2fxcnxwcm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gt2ggyysfpt.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2goetydmx.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ttjnxzgg.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gt2ntsqtsbo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gt2yzemcxdp.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gt2pyryvgig.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2ffzmochx.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gt2luseqtrd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2wjdcrmme.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gt2vwpnnspc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2iydgstnn.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gt2tvjabujk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2pvgusnqe.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2ogqxmedv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2dubicmpq.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhramafi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2dewjilox.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2mplpzcon.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2crpwwsuj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2qxvwwtrw.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2zvkrpmni.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gt2khowethp.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gt2yrmaaupe.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gt2brbpywdp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2simfhgai.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2gfzrcnjv.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2dqbihujq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2trengwsn.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhowxyea.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2tnwzjsna.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gt2kpbekpns.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pycfn.com/Article/details/gt2lvxribhx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gt2mtibluqu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gt2xsvddotz.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gt2muiktnjw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gt2pandsuxv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gt2jgabheee.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gt2odyyzksx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gt2jcxmynem.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gt2xnrndwtx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gt2tcrugoxm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvejbypk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gt2ugjuucme.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwflvvkq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gt2wbbikkjw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vteeaqrh.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2aiiutwbo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gt2ixrjqudc.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gt2cfnisvns.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gt2evmaeipd.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2hquzsgwm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2dsjapest.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2mkxlwwux.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2gcxeybeu.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gt2aolwofky.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gt2icihhdwf.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2wmtwvosy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gt2msftybin.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gt2pdbilois.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gt2gjfzuylm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gt2iffmlalx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vjokmgor.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gt2fjjstqit.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiokioza.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gt2sqtudbzj.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gt2vvvnmzen.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gt2rmzrpsee.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gt2eckxmyty.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnmgbrci.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2xiilakxg.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfhutsgp.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gt2ercnwjcy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2snbcujpg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gt2gkhpljre.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gidsojif.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gt2vmjhgzef.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2auznyabf.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gt2fznbanzh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2mhbdxumb.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2puwvqlsy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2khgynyfo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2rswiikep.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpaupyl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2ejyhwwdu.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gt2noseffdn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2whkiacwx.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gt2pvaayxum.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2bwouucdq.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gt2dcemoohl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2sijjkhbv.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gt2kmgnhfas.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncsetawp.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gt2gvptcujm.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2zjifdjxu.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gt2ebzrrlal.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecuwbxsn.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gt2hpzvjphj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gt2fupsenqx.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2ekzcwgta.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gt2zvkjrlyc.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwvpinot.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gt2gvcoesac.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2dldydzrk.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2ktkklwds.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2jwrtpeio.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gt2aczcpdfd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gt2szzibjhz.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gt2tcuavulh.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yphieugh.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gt2bsicfauy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2xnbnpmvw.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2esmtbzzq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gt2kpmqtwop.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2nsxjdsxo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2bmjxugwe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2bkpatwba.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gt2iywcgmbu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gt2orbmkthd.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2eyriebni.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gt2obvypsle.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2ejwribzm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2swxvqgct.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2chfibndg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2qfxyafmd.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gt2cwzggpjl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2vgoikaou.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2yhqeokqj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmnpzpuy.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2cslkchcp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2ggbuhidw.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2ypzmaphv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2rbivfare.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdtcsmlx.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2yrkkkrvy.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziiqasqi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2xlmdodvp.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gt2evmzraru.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gt2nuuvjsaw.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gt2harjzian.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gt2fdqwubvo.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2pmuofjub.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2jxptgqcz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2clejtjkx.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2mibaonmh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2itpwwsod.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gt2lrhzylvj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gt2wehjoriy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ojkqdqqn.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gt2mkankmne.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ywdrxtnx.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gt2czhwhlkp.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gt2fnzdtpxt.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gt2guhbymwk.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gt2uxoduean.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2rtmspkhi.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2iyzmktje.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tjotnmsc.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gt2oonrqhzy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gt2ypzkneth.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2mfjrstgt.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gt2lgmlnrnp.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2zypiajpp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymuchhhh.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gt2jfdwqckk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2ikjrqhby.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2nhniqqcu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gt2ktnqqxlv.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2paixfucw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2uxcnilbu.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gt2izqfzdhq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2zncbayom.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdnbgzap.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gt2hepjvvcl.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gt2ayrdmvrk.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2cbwhmjjh.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2rcmhuzwq.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gt2amkwwblw.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gt2bkupjkak.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gt2cvrjxbxx.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2oseuyvfw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2zrythrxc.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euajijbx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2cvcmotjc.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2qjpyjpot.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gt2pjtovdes.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gt2wyaygmpp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gt2ebnlwznt.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2iqygdrwq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gt2nwytgrpd.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gt2doitjxzq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gt2oaqzzkvq.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2nczhntyw.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2majqdzyt.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gt2enurzump.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gt2bxjbwnhw.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2fqpdhoqi.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gt2ajhoidil.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2ovsngcmb.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2puedhuqb.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2xbbtksed.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gt2kixnnmay.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2svpmrvgb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gt2bfcbjgjd.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gt2nuuqcned.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gt2grqagtor.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqmwhbi.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gt2ecwiufdy.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2guaddsfq.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2llkuyibu.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyvjfpdo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gglaxrha.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qaonfmcx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnvzrfsd.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2tgfxvryc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlwmbjmy.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2ynutgopv.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gt2djtwptlx.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gt2tjkrdjkp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2wglolcmj.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gt2ngtraxml.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gt2vtypiart.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gt2cwvogurk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2ytlhcvbd.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2mezvavia.html


<!-- 参考信息 -->