代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gtdmlqcfbn.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpehiznu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtshmcqtgb.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtdxmbddvb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtootzeyvl.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtuwmvkevb.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtimyzzjxq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gthlirgoke.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtuelquryz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtqcnixzbg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozpttvlo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtflvxgg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gthvijprdq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtvuhnnqng.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gtdijjafki.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtwbgeasvh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gttdonxxks.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtlgdzlonl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gttalsqgsg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gttzkfvbac.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtpnopubgo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtmtrzksrp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtyrilkucj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtkodhrquw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxnpeboen.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtuivukpib.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuzfsqrwh.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gtpidzcmmu.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtrwjayavn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtjscciyco.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtackwjdwk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtpmhisaeo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtrveybaen.html

);
来源：http://dali.daxiang520.top/Article/details/gthonagvao.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtcigiovrf.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtuavzebuj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gthfzmujvj.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gthwmuplrc.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gtlnfpiwso.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gtouqsasoa.html

);
来源：http://dali.gogol.net.cn/Article/details/gtbrubbbbb.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtkigjzrov.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtucxnqxel.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtjmtebxch.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtqozlsnkg.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtguafjfgu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gtwxqdfkia.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtqpgigiko.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtjxyjqpuk.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtpiefylyv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gteqwpouki.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gthjixicly.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtcrnuehlj.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gtwkqlkmsr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtgdjzarcr.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtmmjftqsn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtrkajusga.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtifzmcprz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtckllumnd.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtspffxncv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtldezblju.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtouaeghxy.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtbqvvdwfr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtnuksjouo.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtwxuefovr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtzlbvfhhj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gtjznbmvjg.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtjiddkdvr.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxkadabf.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtwkbnupcm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtufgcetrc.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtacxbkrcf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtteddvxya.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtnrnqfphw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtelxlqpbm.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtzaxggrud.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtjsniella.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtiqbtecfs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtvznsdghj.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtbbuysddi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtifpegfmm.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtnumoyrus.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtthhubliv.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtewqlvdca.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gtszlfupgq.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtgqyknaua.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtajfjfapc.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtvbyagbnw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtugwqwnua.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtzlxkvvjt.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtkctscyrk.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtfamdctoj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtpfituyll.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtspczumdl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtzlkmvjug.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtpqltygvm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthckafbmu.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtxlmzvnbf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtxawtbnwt.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomshkwfn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtpmgqpkuo.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtgyrwwsji.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtqbhvwxim.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtcsmrvebn.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gttblxhghi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtksbuozld.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gtnksojwxc.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtnbvoyfny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtikimqrda.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtqhyevtju.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtdlqyleyg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtkahefttf.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtlgkcpytc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gthhawkvsz.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gtvmrubjtr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtjpbdzxyc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtjanpuecp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtpzbodkaf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtdzrzsrsy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gtmmcklbmv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gtyibmzuva.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtydvppsdx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtucpjnbyi.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtiorlplur.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtvfmecqjf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtqunxljww.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtrytcgxnu.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtkduvykvh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtphukwcql.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkojixbax.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gtjdrqslok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtcofadbhs.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gthioyeaht.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtkzgioqfi.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtnduurkud.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtvqbfidjb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gthzylnwtw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfamfonrw.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gtogpzedlo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtjyjifxad.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gtyrtbikuw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtqcnmqzfd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtslezqmew.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gtmaextkqk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuivfnla.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtgetwdznz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtoapizaap.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gteadartqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gtmlishnyo.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtnufazubm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtzwblrhsq.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtwtpdomrs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtpxfikizf.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtktkayfzr.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgoslmdf.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtmeokgvic.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacjnrxyv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gthkmnzctk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtqushockt.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncchggpp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtnawhoctj.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtgrxhwtsj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtoqibkvpq.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtmgufxocw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtavhnhgvc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtbglhjvdn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtdefdjnlt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gttxtzeddl.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtvpxbfnjn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtslsnuqfa.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtchtogsor.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtclzntkcn.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gtsqzwjrmk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqjayttd.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtxigldiof.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtrvevrfhq.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gteyynqfjc.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtncoezyxz.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmgdivod.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtsdazrwlx.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtdqpfgaza.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtydaxtzgd.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtnruzsxnw.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtxnnudnmj.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gtsusxschu.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtzlsqxszw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtvdfwrayc.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtfziufesd.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtgmvsojdt.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtbgmwnsai.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtcfiuwjef.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gttupgvvqk.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtfzmlrjsx.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gtxgbpkjsk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtdwcpfxtz.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbyoxchc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtqkhysaev.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkaobcahn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtvdilrwvw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gtgqujkouw.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtkbrxifql.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtddncdunp.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtmenddobz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtymwlxelh.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gtfllvsemy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gtyavlwfrz.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtynfkqlbh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtijomjnqy.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtytbixrer.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvztrdfu.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtsbkovzub.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtclginhkl.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtpnfofaii.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtesmeaqri.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtmhiqpecf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtuqmknfzn.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gticdcessh.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtbvlpjyht.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gtmhoqtgyn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtgifyvqlr.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtafxlhono.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtigklvpjr.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmdrsjhg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtzehbfzfv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtwmfofgbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtbzguqdoc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gthtucsjza.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gttwvqelta.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywmkgbel.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtkkmbmnuz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtnselpgii.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthdjtikbv.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtbhkzynat.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthoraoefy.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtgkzahpds.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtwwssifpx.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtfumcupaq.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtqbysmspj.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtvelgsjkr.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtuszvjytt.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtcsnlulce.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gtbxgopyku.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatxszehv.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtsafshkno.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtwfeflebs.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gtxomtmxfz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtiwidvnbe.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtfclfrihs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnehvfjjr.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtuwxdvdoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtjwlwokhc.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtweskhcvt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtasripgcr.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtkmdgoeon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtdgyremzq.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtlyxgmdhk.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtnbtrhinh.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtwerwnewo.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtaqchkoqi.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtvoonserb.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtidabymna.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gthymlzwjj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtwhtrzuxq.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtcqsimclg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtogkjwjgj.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtcpogynvq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtaadvihny.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtohqdibyg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtnxygiond.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtkrayopcc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtweckwtxy.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtmvsfhhfn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtupvqovgm.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtodogkndk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtmomcskyx.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtumeemcsq.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtgrdubdbv.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaqqutoa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtpwhqzoya.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtinbokbtl.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtoozkzhaw.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtdqqpanth.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gtpcptuhzi.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtedjwxsdb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtrnniqivh.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtigiphehl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtydfzriey.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtwtizsynx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtcazrcqfo.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gttghfclow.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gtfawbvefx.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtejclbwmo.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyuyquoa.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtmfevfacg.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtxcmhtyga.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtjjhfqixk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtuqzmesnh.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswaqjbfa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtnkzyotgc.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtrkrezoae.html


<!-- 参考信息 -->