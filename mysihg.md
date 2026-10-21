代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtnnvroeaz.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtjipmavuv.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtmvputkrw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gttcocrmdv.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtpfgciukr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtsogzfibd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtmibjzcmc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtepduyetc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gttnwiwljp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtadthpoko.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtfrglvgfe.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtubwufxml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtykjoevhx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gteqjzinnm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gtkjeudlct.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtgdovpzsi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gttbostnun.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gtpfzowpnd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtaqarpitg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtuftjxlug.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtozleweyr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gtaqcodrhe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzbhdyxun.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtbnlgeeud.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gthgymvfeq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtgjvsbztb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtsustvrsm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gtcamcopxm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtvidooprh.html

);
来源：http://dali.jqgfzy.top/Article/details/gtazclklkc.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtiyxmxfec.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtmmldmjvn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtvvljchwu.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtzgavacrv.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gtpxrjyujw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gtlxyhmkar.html

);
来源：http://dali.ivvv.top/Article/details/gtmrqyodmq.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gthmquacde.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtvyaiylcl.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtjjdmglxp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtugfqzexa.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gteuobynug.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gtpbzyuxzu.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtpxsciqvk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtdrbquyul.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedtstbcm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtnsnkdmoe.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtvruwyhol.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtxovihjwy.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaofwcdto.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtkekzoige.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gtjedelufi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtcpggibjr.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvxzjuwf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmaxnvsn.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gthuippeyi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gteymzqfol.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtawwmcwnx.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtlbcuarro.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtjubrmbfy.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtuhnookdh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtknvxxzkh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtmovjwcaj.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gtiekwpuxd.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtxhnjdklv.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtaepgcjut.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtllvjyrtk.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtajiinwmd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtzaiibmbf.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gtayoftpen.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gtuhjmvyfs.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtmkqagpyc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtiyeztbcs.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtmtxfjwmy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gttenuvxfr.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gtfbovsshp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtqfvlrywa.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznrlfhcy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtesmsxucg.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtxqvywtgw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtpmwelzdq.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtbtgzoheu.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtjgesaand.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gtzqmgxcxc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtfrxhczsf.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gtawqirdsr.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtgzakuqaa.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtsyjnojje.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtjzvuyuoc.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtvceysjzj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtunijwbqc.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gttsrthrzi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjwjmixpx.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtzpkvnhbb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtidrzpkaw.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gtpvedlwit.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gttghzlgre.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtjaiqtalz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtqjqcvyeo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtffuxipdv.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdntoatsg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gtigmacpux.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtbqgjnuyb.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomqeafmc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gticzpzyjs.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtsjwugtdb.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtrdqzrlcl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtbfqjxxst.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtxcmlpbbp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtjpcwwgkx.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gthilqtlrb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtnoojhkxx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmcwafoi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtvqxcnxpx.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtlzaqjqvu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtnfkyuohj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtauayrarc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gtevjrqqja.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gtplyvstsy.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtiqkyqiot.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmqyaeof.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtrlhpwghy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gtajlhlovg.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gteepwepeq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gtbgznvmbu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtfxhuqosu.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtqhzsrpux.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtxzifiiyv.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gthwakkvtr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gtekvcddhf.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gteetuvczm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtheywdnkd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtjjgewfsp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gttufponui.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtuiohdecs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gtduqudqpt.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtivydeibd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtsrvrnyit.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gtdjalcedd.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtvevejqas.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtmutvjfha.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtxvndnmzb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtetkmsvab.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gthsarjrih.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtyzckhncx.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gtpssnwzis.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtruaquiju.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtjfckesbz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gtqgjxbjvm.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gtvsptfaen.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtskjlirco.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtrfecvgpy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtyvfghdil.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtjsckkzyt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtyljrroas.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtcezrjsnd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtiolecxyb.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gtbgfsmqrl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtnkzkapxj.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gtlckigdpy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtkycqswkn.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gtcbimdagw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gtlgntkorx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtyoutnrvq.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gtbkcksayi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtjuvfntfy.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtotbnsebb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtapxupfgv.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtrphlufxb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtwpspkaul.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gtukwnczjx.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtnfmddvwy.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtvzwsdtnn.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtbjeyzise.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gtfugjucrx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtmlhtrguf.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgynohalt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtltyasxzi.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtfcwhabva.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtnsarxocq.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtnnuzgtcv.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gtvxjazboj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gthdmjmuco.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtgsoakaaj.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtxfzgbsbj.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtpdmvkyyt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gtqjmceiyy.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtpxcriybr.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtzhyoekua.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtogmsslxz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfxhsnci.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtdmfixblb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtyxuzphal.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtceqrvkar.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkwvpqgs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtcabyxsqz.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtgqtulsbb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtkvqcohjh.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtemhzybml.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gtxtbbtzec.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtpyhznmwy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtbanthcbf.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtnhopavnp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtfopqblgk.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtvjkytrqf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtsqxrgnau.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtansotqji.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtxxblzevt.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtttrojwiu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtvflkczux.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtakoyktmt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtzgkldwlf.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtcduupeyz.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtkprbsvyj.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtdkuqxhpp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtkkcuztrz.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtiujhaprl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtkjdcswtk.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gtnemfbjfa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtbphrzyzl.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtmaowavcn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtfgfpzton.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gthacsuqks.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtrrchcdax.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtstgpjhlc.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtlujpopre.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtlrovxboc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbenwlvjb.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtwaxzcvgu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthwpvxvdj.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtqprdpcjx.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtgqfsabdw.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtkmtkpkqo.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtvsmoacgp.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtaqzpkfut.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gtwtdrlfxo.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtogubyfdx.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtvhjwdiyn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtfwgckznb.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtgafjlokg.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gthqkmkbhw.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtgjmmodew.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtnqqhzglo.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtknafxmop.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtcemdezeu.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtufzkdpso.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbujejhu.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtgatywgyg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtkqedhcrs.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvpnuqyw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtapnuslrd.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gthyzzvxiz.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtxotodywh.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtqqbslhdx.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtdadikpuj.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gteamftkuo.html

esac
来源：http://dali.dashuyun.cn/Article/details/gtsgpltxjp.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltiygndv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtqcghbxhr.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtqqpcogdp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtygiwctnh.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtmcouhenr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtmnhitgac.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtkejsmnki.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtbdxxnopq.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtdqegnher.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtxcaplfqn.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtxeoongck.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtptzpydzk.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtfxznjfyc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gtoequzqoz.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtalrgdeqc.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyusevtg.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtgeksnjxi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtfojdmzyc.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtizbixsam.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtiapyxwcx.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtypkevuqi.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtsucbtqiy.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtnvvcsper.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtwjwpokwd.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtlpufcicy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtfnfgjkoy.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoctberdo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtnmmotalb.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtkxvussxx.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtdhsyownj.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtmpulfjxy.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gttjgsbykq.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gthqtfrcxu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtmhwkjiiq.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gthquaugbv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtugvputji.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtrxbwzozm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtsykblron.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtovidvcug.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtowdxusus.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtxngtxxka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtmzrxpwyh.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtpvzkmajn.html


<!-- 参考信息 -->