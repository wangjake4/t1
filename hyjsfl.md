代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtdjfwbdya.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcjspmtgk.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtkafhxxci.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gtgvagvplp.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtifkgrhmn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtueuztqdq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtzwjkftwg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gteafixwax.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtcffstnha.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtbcipgecz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtusbginwe.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtihaoydot.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gthfeofbhv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtyusjtsgp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtubcxrxlf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtarrrydsv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtigxbvrop.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtkfywiftr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtidznhdbm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajkbgsdx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqfddzqxo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtnpvwdmja.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtatppgirz.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtlhigvepm.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtyfirnxlm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtskyvnwzz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtdcihuejr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gtyedjubha.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtfanqknmi.html

);
来源：http://dali.fzhhl.top/Article/details/gtoovekjhr.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtsldpwmje.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtulimmoyh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtubcnyrua.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtkbnoxkhr.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtnkpvorlf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gtfllyoovp.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtkjpzduqr.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtppipwsta.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gtmyhcqvfa.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtsqarwzhf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvhfbxic.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtsrpmjqmi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtizcxutwh.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtfmvqbdyn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtfzpexynk.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtmdevbynn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtsjrjnsnh.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtlvgvgzjw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtvwliwqfk.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtoprbsxkz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtxlbhatds.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkgopcfq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtaljgokfj.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gttyqesvbm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gtczvscufp.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gthlgiossc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gtbvrievjo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtcmbptkpp.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtkkvanndf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtdzdajfmm.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtzdplbptv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtjosxooxq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtnkkbmoep.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtkckbcddc.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjkuztlxl.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gtapdcncku.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtewrrbkce.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gtwexxozms.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtjfretsnk.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gthfgkteul.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtgyqpedmw.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtyxifsdom.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gtazngltgc.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtmerybesq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtuyuyvhur.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkifttwf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtlgjyhqby.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtomvdewvz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtrhqqrxdy.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtinmlnecx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtfttofclj.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtsynbtxkc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtspabpuan.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gtgjvowddc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtcvixwphi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtbvuibimu.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtqhsciezx.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtonvwepce.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtzzfcghcq.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtzsstpshn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtrnqqkrtl.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtimdhdlrv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtioqwnkzk.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gtwsgiioyq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtukxxaaqb.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtmpkkqacu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtxqmzpepc.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtofimnvtv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtbyzinwkf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtmhoaorqh.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtpgxpunox.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtriifojkn.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtpwtyrhzg.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gtuhmuwbkp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtksqtcgeg.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtuhpsbnet.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtbgqikuyw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtmmfilpmm.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gthkpcxfxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtybiwphii.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtakngueew.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gtjqvalntf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtwrckhien.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtjykoqaql.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtnwtrzueu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtqieqqbqg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtpvpsthbv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtdbwcdagw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gtsvcxxxzq.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtwreyivrm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtkppmkwet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtcegtxttw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtnrcniyjr.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtqwzonlsj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gthabgmymm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoqzlnon.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtheirfvkh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gthxcespul.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gtwmnswnhk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtkltndygk.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtdllmmabp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtabufkzqr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtzkbajwaj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtyiscvwze.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtvqzfhbcp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtmcbavzww.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gtkuzmtsjz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtqjtfucqy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtftwwaywf.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gttbywkhth.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtepebjkcr.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtguhcfiux.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtoylknkkd.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtvcziaqtv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtyiizvduw.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gttqkawcnq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtqjsrucys.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtsxkrwecz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtizqfqfgg.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtzdhqdege.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gtoowbmdpz.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtglfjdyuw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtnfmeweed.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gtutnvktyk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtfnoyhpik.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtnvkghwhc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtotmvloyl.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtxxzimigx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtwqmdcuna.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtldvmkkoh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtxiykrxhh.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupwfbtpl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtomubhypu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtkkwdxrhs.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gtdlzibzdf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtovmucbgu.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtmfjhhtiu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtfprcaffs.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gtgeqlmkkq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtpsrrjkrm.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtaobaeufp.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtlvvwkozq.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtfvoxnpvo.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtaoxnpvfb.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gthuoryncz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtudeszomb.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtrpduoyok.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtmurelcxv.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtnperogqo.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtxqlegttf.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtfgsyorzk.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtjtfpkcik.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gtpwxmnufk.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gtoyckgqva.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtfnuenqig.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gthltckgvf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtklwwcmjr.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbbbsjux.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gttjsoxbil.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtqtjhejum.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtasbxktaw.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtwdntwuuf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtgwsjwomr.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtjneombmx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtjqmhtiux.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtyvhejyxw.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtxqjksdgf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtlehfnljc.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtqpxpfdmd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtjkjindcw.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gtlhmsnfdp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtibugszlm.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtddczyjtk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtpkctzkbx.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gtkggwgsyl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtjsnrzjbl.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtafqtsnid.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtyvnztogd.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtravizxgj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtkcothluk.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtkkugyhgi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtlysdxeew.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtxhwvlunk.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtjiczyxfo.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtyqpumsuc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gtngygcsbb.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtfikthvsi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gtdtbpflbh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtqzwbjccm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtysqnwkav.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtlsrasouo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtacruvmti.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtosfaecsc.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtuhuleljr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtgmizqsec.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtawsowrvy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtbmtpyqyh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtntixqzfa.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtajdrizvh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgihhplto.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtgwocyqgq.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gttzswvsws.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gtzicoefxu.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtvjsinlum.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtlqsxpngb.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtqygukctf.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtfmlxnwfj.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtrvnylefq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gtgafyklyf.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gthbrryhxi.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtxlrptkot.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtsftergvx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtowfyfixe.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtugbsertb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtlufgrapz.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtihspkmfo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtvnksxaub.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtschicwqf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtvspzdvoj.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtooqopovz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtrddhawbo.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtsuqzqyap.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtcphrtlxo.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtlfffizyx.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpviusgj.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtlazurkjd.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtgdwxrsnc.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtimbyakva.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtkegkvavh.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtawpomoat.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtdrnylrai.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtkwtouawh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtrhimtqkm.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtijjikohc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtbyimbzwh.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtcoexpmha.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtbsvkrhfb.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtolvfkcge.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtffctlysr.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtmhrjmlmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtdrzlxxsg.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gteabhtazq.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtpmckiczx.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdojnamcf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gtqlcekgpf.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtqyzjtath.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtloydqdoh.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtrkitziok.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtibwhwt.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtkagxqfwb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gticinksfk.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtvqyobefz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtmwxbepal.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtfouddcyk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkwgdoqy.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtrancktko.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtuuiknisc.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtsruabfpv.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtmqvqcios.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtsgcrhjmf.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtkjkxxhyn.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtgbbaoybb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gtqoojmhcv.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtqcohdjsm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbbqvlrz.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtbxutdnim.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtvngomosm.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gtkjhfzbbu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukfsclpw.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtogpmpgbm.html


<!-- 参考信息 -->