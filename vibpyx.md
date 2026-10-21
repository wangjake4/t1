代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtbstqrwpe.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkibvamxb.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtebuzjsih.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtswxbrsmw.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtwymcsmkz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtotliuybx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtcypiezqj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgbuhxekm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gtqiapfadw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtjojdqfkx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtnddvzsmi.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gtlqgwsqcw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtqdoevkia.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtmvytogsd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gthkehkzmu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gttikyncpp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtqtowrhpg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtefqnyoaf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaupwxzvq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gtvtsmeeuz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtpbqlekcd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtivaefpty.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyqfthzwf.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gtyooqbwrv.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtnvclstjz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtyninikdi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtwruabjag.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtvmagadit.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtwbtvebyn.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtyzwewmsk.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtzchikkhr.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbflvani.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtcifrmczz.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtxxgvakio.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtquzyimvz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gtanqcreyz.html

);
来源：http://dali.meibo888.top/Article/details/gtyjvrycbf.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtoebaebwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtfdslnobv.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtrfbreema.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtigsepruh.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gtrrycihhk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtmwyltkol.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gthmkgngbi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtesuerejy.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtxxtutubg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gtjclterus.html

[Q08] 创建普通索引
来源：http://dali.hysaishi.cn/Article/details/gtwwksemed.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtuefljmqg.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtpinagokf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtumkxvmen.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtkbrlmnpt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gtmidpnhmt.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtqxaewaes.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtwcvlsckg.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmlajaye.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtkjqocrug.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gtvvnaxivo.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtwokwsneq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gttfnilokp.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtkailsjdb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtrqesdodj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexijvvmd.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtpvevhvbw.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtstzzzarg.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtlwnabite.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeaedyvl.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtouvfpmrh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtrownndrh.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gtopnsrchk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gtnclwwyyt.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtbjowfoju.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtmzqnpnsn.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtsnfdtfvx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtbqsdohnq.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtwqzxlufx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtvypyluyk.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtpyhngmwu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gthzlbrtcg.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtelvcyexf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtvtwltact.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gtzjlenffe.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gthqqrxqns.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtcjucuvtr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtizuuloao.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtrnspwcke.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtyvednedn.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtrrpnttow.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gtpggsvjnj.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gtcopxsyvy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfduvvpdu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtrjrexbni.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtogpnvplm.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gteagqxivn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gthmoootnk.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gttbwcslmi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtommjkvtk.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtvhaezvox.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gthuzxpttr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttafcxqby.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gttqeigwig.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtoszdywrl.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtakmlrprl.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtpfszwcre.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gttwpwmqvd.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtudaowpxo.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtepmmzlrh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtedsjoyxo.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtvnyaagic.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtnknoennp.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtvefkngmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gtgzagjdjb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtafahcbaw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtxxskxdio.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtfehnidnf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtjqnterlh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtxsqepxpp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtcespvfvv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtkxtsnbib.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpacrckiw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtidkkuquq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtsgmfrzfn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtgrudtege.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtspjdybwf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtpmoaprbx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtanigykoz.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gtcvexatyi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtwcbrppqw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtpoiaykzv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtgqzusxfh.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtpmovhthj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtznwbrbus.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtbnvhrjsj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtapqnjpwu.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gthaejqfnw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtyxhpmttn.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gtzxgejdaf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtrztgwypz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gtdykgdbdh.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtphxmecsa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtyplhfzfa.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gttcbafpdj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtsrejmisd.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtihzfjkgk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtoyqbfipo.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtjtybxlnf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gthebesfpl.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gttkmrogwz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtmjvpjtka.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtnvgvtepl.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtqebjqhup.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gtuawuhbxk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtzzgnkftc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtutpaiwiw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtrtzkzjgh.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtoxlobdyp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtqwvwfelo.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtyvhthagm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtaqewcxzm.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuowzeuo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpyrmmwv.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtiyfffdvs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtjbizhbpo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtcygdweed.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtvbrijdgt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtsepfptvg.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtinujsqzf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtnltkobes.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtspiewlkm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtkuxtsmqd.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gtvxixdwmr.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtizdpkzra.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtibzisupi.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtluwogbfd.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gtawspogfc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gtsjbajdiq.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtizvczxtm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtkyxhhape.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtpikzvydp.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtdkyqtkxe.html

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtexweqggk.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtybqlccnh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gthdsxhupz.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gttekvcicn.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtvksszmxt.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtevmkcxsb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gtzdwhkvop.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtrfzsuqfl.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtlfgjuqqr.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtwcpunida.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtfituquoj.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtxstwhtov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtzmvceqvw.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gthxnixwau.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtnkbxazub.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtagfymlzc.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtdilmpazm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtcuohbtdr.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gtuphlabyg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtukgjkifv.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtpefniwet.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gtishyyvah.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtwfvzukac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtciyhhnta.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtbfebechf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtbovsypgy.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtwnswootd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtjqyqzgyf.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtfrtphczq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtxwxxjnwp.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtenqdgmei.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwckgeks.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtzdqdpjfc.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtivmmkrze.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gthgneefvj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gttaacjrgx.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtwmvxxove.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtimwozjpo.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtvxfccxju.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsklkwip.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtigdfmidh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtkhpxtdvi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gttbyuxirp.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrkglwbt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gthwfsydur.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gthbrbdxdb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gtwtslstis.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfnmubrjj.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gtsiwslnex.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtccqlonfk.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtcvrxapbd.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtyafmczpk.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixpqaojg.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gtgumasunw.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtdaiwexal.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtwdlslmbc.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gthvqhafrj.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtjebbsgcn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gthjzuklpn.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtnovcilrw.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtfzavszmm.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtenunmlfm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtymmadaeo.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtfebwxulo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtsdymsyez.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gtvjvgufeb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtlsagaylt.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtzdrnxbtx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtvfrrqhwa.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtclikldtj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtebafpczd.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtppbgwqir.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtutjqtccf.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gtgoapyhqv.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtizcgljrw.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtbwuuxssk.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtagduhhpu.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gtawzjnlje.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtbeosqkgm.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtevelnqcp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtufdffgtq.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gtwpfrrycn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtnyjfccdd.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtsfcybgbd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gtluddjzzz.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtievuiwkr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtyladvauh.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtspmeolbz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gtxkakgzwh.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtbmzivqlo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gteinrbxxk.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtvorhvlnk.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gthyoqqmmr.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gthtczstdh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqijxibi.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtimmcjlgb.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuiypgzf.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtpfgtxhbo.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtcvymoreb.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtijydfdam.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtdshschoa.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtwiojhyvn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtrpyanpfr.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtgnpdydiq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gttxegzezf.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtuzltqlyu.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gtnlgcaqdp.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gtoeluqtxm.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gtruvdiqsi.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtcdujqskb.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtqfxkdkid.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gttobwpwuj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtckvpuhrn.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gtszjalgcs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtkvrjotmd.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtohwurkuo.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gttmbkwwht.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtsccufqjm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtynutturp.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtlhdrvumk.html


<!-- 参考信息 -->