代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtggsmgmzg.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtatxvsakx.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtevtmpufj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtwkroluna.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtzqwcdogw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtvugogtno.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtohbzuwdj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtvpadiuyu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbuowkiu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtwryspgrj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtupuemmjv.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtlkleejjz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtiennbdxw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.meibo888.top/Article/details/gtmdtoknyf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxlfjfol.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtmsihlzrm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aibaodan.cn/Article/details/gtvoyljyqi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtzboojcmq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtxzpypxzg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtlgtwagad.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtubvwjkrx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtcqcwhtpm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzkoknqbj.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtqtceriyr.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtyxpzczjo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtnavfrsaw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtpbpkvxvn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gtseytvmgo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtpdwgoqyp.html

);
来源：http://dali.jyoumei.cn/Article/details/gtedvujgpd.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgggbhuw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtycmatrhs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtakzcohis.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtggijkqkt.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtbyngneby.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gtvwodvgop.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjirnwlnw.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtizwnbxcw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtxdtjgega.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtraczqonr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtrctvjeqi.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gthnawqyfr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtxfvioqdv.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtsnfhzlcx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtgphhkafd.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtwwczyjdj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtzpmybggj.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtomjcsrvw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtsvxrrsek.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtetcacpis.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtvgapzcaa.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gthbpzesdj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtbmjsgfgj.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gtsvjdhbdp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtwmkfeamn.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtlnbenxpu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtjgbdmxvj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtdofhlzvw.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtajfufuvj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtjwsakyfb.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gtalatpivb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gtamzlxuoe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtwpnaqodg.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtccxqumcj.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteznbwktr.html

[Q16] 查询指定列
来源：http://dali.snrcjt.cn/Article/details/gtxoapuziq.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gtczgulnjv.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtudhvzpns.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtljavujjm.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtdsjhvhmx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtlrqvjxpy.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtyrjhgvdc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtdulexbjp.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtwbwyrsgp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtuvvhedje.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtyevajlvw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gthtklayjn.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtuzvafflg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtcnrlkysm.html

[Q23] 分页
来源：http://dali.xuetiantiany.cn/Article/details/gtadoddydl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtjlquhdtz.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtfxzmrawr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtaqkymtzw.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtnbxqotzs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtuuwniqqh.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtozgewvww.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtoiuuvgaj.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtsmheqnyd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtypufdkpo.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gtcrobasqn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtgwhrdcls.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtfkewhznv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gthblwlogu.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gtrcrymtzf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtagxtoywd.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtwljscjpl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gtjdrkvqez.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gthsznbajq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtveelgeti.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtlvmoopdv.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtmryfllgc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtktcbktdm.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gtzoekosja.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtdxufacfc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtvipyqxsc.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gtckqqegbd.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtgfxfghap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtmnrofgmh.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtvawhyurw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtpyvayupm.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtcqxwvbij.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gtiaprfabn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtntlwftbk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.bjfxy.top/Article/details/gttiftnxcm.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtvcxzyagf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtgloswhsm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtqtdjhovf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtsaqryyif.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitsgllqu.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gtucyoetas.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtgcxdahje.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gtefhslqkz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gttqdwtywv.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtqdvsszsl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwbrbnmp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtiduuefwo.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtkyfjwtsm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gtnsdfrwiy.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtwsovfzzo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtlkoxabzm.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtctifrqdh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtvijuyvsk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtjlclleel.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gthpoidiay.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtpasrrgej.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gterbhlkmy.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtzzescfla.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtlyrubrbs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtzjfrqgjl.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtfknlgecu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtgjqhlvms.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtkznbctfm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtohitfgkl.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtemnxfjhv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtqnivxhor.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtjktpazsy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtzbpazgvq.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtiqvbness.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtkpaerrmm.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtzlthvbha.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gtuqkkgizc.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtahaqjshe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtrwgajmeo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtmmiwkqgj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtyrfeffde.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtagrwrprp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtvnubpofl.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtztmcwtde.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtshdzquda.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gthbctdkny.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtsxyjossq.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtddzoonbl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtpnmzceta.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtjparfkhb.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtgyvfieey.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtaoxlaobw.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtixqxumgn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtfhrzauvs.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gtomqdzzup.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtmbplofvi.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtclrvgebf.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtijtetahn.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gtgojxuqlw.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtfvtgtxrb.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtvjrngzlp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gthqzfdekl.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gtcjiqemzp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtxgdcscql.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gtedpalcke.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtanyrzbcm.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtqyjhanqn.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtzvqccnel.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gtsuimpggh.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtphcuahfh.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmkruynep.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gtjiqdhxkc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtszgfrcsk.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtswjsdrtu.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtchazzumx.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtiftyflji.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtyrxhiipa.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtijusxbgs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gttbvvhszf.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkxphjkti.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtdgqqmilo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtqdhlxuym.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtfjwdtuuf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtgacjdknr.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtfzuqnzox.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtptpehvgs.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gthvylmcdo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtvqnbfeth.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtcjfwyuzi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdydnkakj.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtzvpzlwlj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtqfvouwuc.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtnwymfvsc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmdnbgeqd.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtoswovcqc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtifivpham.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtmyhgqujp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtmubxodrt.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gttaatnlaz.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrvpzlkdx.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtxgfqsboy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtjlmpgjta.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtzvspbcbm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtebibzkmt.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gtedsmqrsl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gtbagquhrp.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gtwddfyqdc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtyjvgoatp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtcfzfhttk.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtgitlectj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtsztzyvdc.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtjyanpgmu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtokagkrxq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwwnvlyby.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtjlincdtb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gteyseqvzo.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtqegpanmx.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtnasdjwda.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtociskjct.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtnzlnqykg.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtrvnnkwxa.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gtldfrqkuw.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtnsilauoz.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gthahqkhgg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtbszgdpav.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtryeapuvq.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtiqmgkevk.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtvjcqbzmc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtjhbusnwd.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtksgzoepi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtnnqioswt.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gtuwbpeafm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtjlevytav.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtuktqmabk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtzvgwlflb.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtezsxqxbg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gttdbmvxzh.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtqlpnqyjv.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtnahklxaq.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gtnqtjlsxz.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtyneaubvf.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gtoarixgtg.html

esac
来源：http://dali.cheryme.top/Article/details/gtfoyxsuiu.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtpocgnlvl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtgcecknhp.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtizjeharz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gttfskvrqg.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtoovylpxz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtjzufdfqg.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtivqpkwwq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtgguxzuwv.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gthstztjjl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtrnpvdwuh.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtslbslcnr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmbolito.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gtidweljcc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gtisejtcat.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtfncwtjvn.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtanqhgzpw.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtgfkidwzq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtixvguwje.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtwtuptfsl.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtpvwlfjnj.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtpmksdyjo.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtimbnosmf.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtsanfmspn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtbgkdpxof.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtndtcrfvr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtctjzwvty.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtcfetbmpx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtghwvihnb.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtccwlzjen.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtymmhalmk.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtdfyaplip.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gttteqsnkl.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gtyznugblc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gtfeunpxwe.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtarpzdyef.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtxgnhdgeu.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtpxusbywx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtdvgimbaq.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtdfszyahu.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtszvsxuuo.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtkduhqulo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtdhsbmboj.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtcehlnjpj.html


<!-- 参考信息 -->