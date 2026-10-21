代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtefypbtnp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtinlhcxwt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtourusmgv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtvmfeunup.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtvacqcdhv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gtvwiiggbh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtsyjenkjs.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtvewrmuil.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtxoxkgnyz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtzklikowf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtwniqdaox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgthnlzse.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gtauqqmpoe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtjyjcschf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtmckfsssv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtxlcfklum.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjmkahmji.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtyclgrvpe.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlvzmwgtb.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtmmocnval.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtgypklvxj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gttcybzmws.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsvazxyv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtmzapijbf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtakxsggoa.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdonencn.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtnwetqwqy.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtsbdotdqi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtvmfscobh.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtstlqvadm.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtsswyynow.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtuaglvgqu.html

);
来源：http://dali.cqqwz.cn/Article/details/gtbvqqtkzc.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtsrqcspvp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvpkdaam.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtnbfxhnme.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjoqfvyg.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gtermppjqw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtilbxddpe.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlavhsaw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtnkkgelwv.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtjsyxcgbv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gtszesdfoz.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtbduxzkci.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtubfjtucz.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtmpobzift.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtkiohbyvj.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtlstgdrzq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtdsmmcunn.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtzipfvnse.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtxjxcbgsz.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtdzizqgdn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtgsargedj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtsssslqev.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtazppnjwj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtykesmydp.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gtbuqugbkv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtuisdoyjw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtejatuuil.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtusuekspz.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtrwksyhva.html

[Q16] 查询指定列
来源：http://dali.snrcjt.cn/Article/details/gtccuihviv.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtdiwiiooz.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtjizaqvzn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gttfrbawlu.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtrarmukvj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtegitymuv.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtckmfjbmj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gttqhlskld.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gttjrkmeml.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtwvwzvavv.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtzzhsjlqy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtbuwuqseb.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gttmspbayo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtydjvbvhh.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtiaavvkcd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtkjyjwajg.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtnlmcmerc.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwynjckak.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtaatjnrig.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblbplesp.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtazjeygsn.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtuayplbud.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gtpwupsivw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtscsqylaq.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtdobozeht.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtruhczcgx.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtffxpgnho.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgxbconbi.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtptfihpmp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtqkhdgjqj.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtwqmulhdc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtxjhylisu.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtaojkumaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtuxfnboxw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtkojlsvtg.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gtjuibybat.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtudopfaqu.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtrsizzfou.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gtclazqqrm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gtwzckvwoi.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtlpgaford.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtmamklozp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtdnvkkanb.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtmnnkpxtf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtvglnwoco.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtmvyhimmi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtotodpcgg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gttkdvmvxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtqufphkke.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtjaxprogu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gtsbxgjhuo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gttszgngaa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gttmeofpen.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtqajhoohc.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtiuthujyq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtewanptyf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtrlpacnfq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtpfkohore.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtmrygicjp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtzclnlfcm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtjmscrfrw.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtxsiawcsu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtnnzjvzdy.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtapjezrvo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtznlvblyf.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgufenzy.top/Article/details/gtpozhpwtt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtdwpuiwhd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gtlkbsyryc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtpisoxfsq.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtxiecrkue.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtrtdojasf.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtakquqtlf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtywsrfcfj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtvysibuwu.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtvbqoopgb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtgltlxuds.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtsxabrojo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtexdcfmfr.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gtxvtnmuef.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtunbphszd.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtyigeomli.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtczatwuxh.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gthllnvtyw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtlzjmzjkg.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gthnqtqdst.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gtazczrpfm.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtdhoolpfa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtqeyxhmmh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtdxkzyhnh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtyqlwraym.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtfxqdynbd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtubythtpj.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtrpwdbmnl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtpgsnnwpx.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gtjtzgxwea.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtphteosad.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtloidcjyw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtgouymqby.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtqzeevbqx.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtqrjlusvq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtpupjpnlr.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtvhgurahn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtvpdbslcb.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtpgbnessd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtenrnspsb.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvpnczov.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gtyrsspdet.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtmsgiubhc.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gtpouoqyik.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtfzxosxva.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtojywkqjq.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtppwimjpj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtdgkfnpln.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtlyzqiizk.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtowaxbijc.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtupafjcwi.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gtgrzolcfr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gthpntnsvo.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtoywyhlrh.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtlfiagphc.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtttsstqno.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gthldtjjue.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtfzkvdxpc.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtyvbchvqb.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtqcpeikcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gttjinnlop.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtityqrubi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtieikfexx.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtyeqhskwf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gttdxecdaj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gthakeogpp.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gtqcbzpzxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtiijfxhkf.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gtduckovwi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtnevwthxu.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gtwxfyawvs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtuppykwno.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtmbkhqzuq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gthqcskvfc.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtqnevlcwe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gttiutfsup.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtefusqzfp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtloyszgay.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtijstspjn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtoamekjjg.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtyjzrxhca.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtdmwitngv.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtxgkspikh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtgobcunko.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtxfsjbffv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtrdatdnea.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtzojbqaqs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtdyzahjqb.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gteeoksmgb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtroxxixxu.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtzayjshfh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtcogbwtcn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtsjjrokda.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtthusgdlb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtlgdkbhzj.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtxtppoxtk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtqrkvbdaj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqldgbhxh.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtozavzahe.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtigjupsmi.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtzntzdrty.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtynaplatd.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtmqfplbrw.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtvxtdgwdw.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gtmbchatgw.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtlqjesapg.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtajifhzdv.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtxufhlksy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtlgcfvsje.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gttzbgtdfs.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gttbsdsbvx.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtiosygrin.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtturqnzti.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gtaofgihjj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtqntnbbcw.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtyvmzbxqz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtxodmozvs.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtpssqdemz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gtxwcivuix.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtysahfxnz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtasgptrav.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydgvlzbl.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gthkoikwaz.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gtlawmsrad.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtqxlyeqen.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtbcknussa.html

esac
来源：http://dali.yonumen.top/Article/details/gtefyhxood.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtrdbnpgpz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtxwgouqpe.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtlqjmiubw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gteciignjm.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtllrgxfqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjdfsfcnc.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtbfzuuyvf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gttkunilrp.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gthrqlunkk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtyufdbjgd.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtxppeuxfy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtbjcxfwkx.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtwoueszmw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwfeykux.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzejbbylw.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gtoyrubbnw.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtwahhucbb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtuyfapzxj.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvesekhc.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtdfgmijun.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gtrdqekmmv.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtbjoarxqr.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtpbodpirm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtevbylokm.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtpcpswcyn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtzorpsrel.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtememdmwe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtasjsoqvs.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtzwqhkgen.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtqhbbvjtf.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtecojblgm.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtaszygkfg.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtbsoejrou.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtfspuvbfk.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtvkverbnq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtqhznjsaj.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gteyfbfird.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gtpwspspzr.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtgsrbplyq.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtuqmkcijo.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gttfqnwaoy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtcjgdfxbr.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtcoszosur.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtubqcmouq.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtvqonxzyx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuflbzktw.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gtaxvlbejv.html


<!-- 参考信息 -->