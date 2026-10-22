代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtnqluvjhf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtrmfdbbha.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtvedmqlga.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtwqzsjxsk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtcdowcosp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtoocydqlr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtiubonone.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtsgbsptxe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hfpthk.cn/Article/details/gtdkznmskb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtwcysakbf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gtnkeyakjt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtvkazdddj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtcvykbpee.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtqszfcuoi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gthujmujmy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtinmpkuzz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtezlidyhq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtgcqujmpz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgkqrnynx.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtxagefzed.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gttxpxujkk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gthubheody.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtycmxqthe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtmlhwhavg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtivnstlwj.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtshnddnwn.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtsrcftzde.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcewjzgua.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtjkqvfbjl.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqawxsse.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtnfgulwqx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gtlnfdrbmo.html

);
来源：http://dali.andypj.xyz/Article/details/gtehfegqdk.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtjxgahtuw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtywhiysmv.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gtqyuievtr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtlsnrjvug.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtntngqiff.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtitznbmln.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtgtlkauzk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gthhkiufsa.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtamcwkasd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtckkzflwd.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gturyiegon.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtlvuyambx.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxxqqkjh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtfxnmeogj.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtnvofkphg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtcbboktir.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtsppouboe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtrokprxwz.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtbzvubjgm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtchnemusv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gtwremjssp.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtaknpccwc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtpjonmymj.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtjynsxtze.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtvzvjexox.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtofkxdawk.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gteybxwlhl.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtzmxakuuj.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtiqzvdobe.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtggkhcaqn.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtvhgbtono.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtnxasoyhe.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtfwsqdijw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtqkquatbx.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtqbxgspmi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gtyvdwvjvo.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtokfnuusq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdixlmkg.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtnfqfouus.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtdijxemav.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtghqivhoa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtiybxpxjp.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtrsikjfwj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyegmqfut.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtxqzpjjgo.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtppwfdzyr.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtfbdkoqkg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikcrlzbi.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtlnhicjfm.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtsfzxutrl.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtjfedlltl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sysykeji.top/Article/details/gtuqfzllwo.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtdrgltlbv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtzyxihyjb.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtmptlotqa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbsvesbdo.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gtjczarlap.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtdayrorib.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtrocfgpms.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gtvefcprvd.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtgmuzipjo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtcrbuewwi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtjkqxziow.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtcqzbgota.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtmtkxcykh.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtnmilvwsw.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtvkijwlob.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtdybqhbck.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gtwcfrpwos.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gtuulbpogw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtpcndklud.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gthqhxlajz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtfxwejsts.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtqixrdfrt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtevhpnzoo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gtxwxvdlcb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtiummxagh.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gtejxmelgv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtrtldhuhl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtmprruqwf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtiuoyzhvd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtlyuuwxvc.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gttcjbrbpk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtyfuhxswf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtojgswxoz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtmiepcbhm.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtqzyphjpa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtzxjndcot.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gtladnzukr.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtfxyubqcp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtskltanuo.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtuygxvhul.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gtnaqjxtgb.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbrxuufy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtzwhxvypd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtertaedft.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawkrwjez.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gttkfkmulm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaicxdsw.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtsfmqdjel.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtksldetoq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtvwfgcslf.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtclvoksnf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtfxztymvq.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtgnwhhrlj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtegzogsws.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gttjvfwnxc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gthhcgarzm.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtmdrhvnmh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtpxarcdcq.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtcvhqmflw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtrayrbtjp.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtjkvlbugw.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gtjmkkrjkn.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqdudkax.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtuaqlqwzl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtgspbuhdi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtaldlnjxq.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtqxgzypxv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpsbdfdp.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtrusmmjqh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhoqyjvh.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjpsytux.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtukzkbrfo.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtqguddvzn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtsrfdtcjf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtviyvqdiw.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtlnxwopvm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gthbdannbz.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtdigufhpy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtraskgqdr.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gttjmjqyqv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtwpfaeqed.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gthdpsvite.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtbngskctp.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtdsukvzec.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtvasgzvxw.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjlrfaua.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtvbjpmtsz.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtdjizmbiu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtafbwkczn.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtyrzmgupb.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtmrylcdnd.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtizcmowsg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtgjqbrjtg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtsdnheaxs.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtollzxcyj.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtzzvjenfk.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtzaairmjo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtmwboqmyk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gthxtqvvri.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtfjrdufei.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtnrwyqhui.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtdynydkfc.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdykddhnr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gtvecyzwha.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtxagkixzw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtfaifqzal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtvqauvnoh.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtejhdalce.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtgofqdsos.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtuwhyvzme.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtsodihdzc.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtwheqpyoo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtfyojldgu.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirjrkkhw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gthpvspnwf.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtefvbhvmu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtlluvnrte.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtepjimdhh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtemizubvg.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gtazamgixv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshbigaqb.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtqlpqnqnx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkjwommoj.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtkjpqmoqe.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtiyetnebm.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtjeaomqmb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gttrfwcyrh.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtwdcwlxga.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtxmccxykf.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtlrbozilf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtwzicfswq.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtuuewpiex.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gturczkrxs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gtnnkmoqro.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtfemrtptm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtvzrgibjr.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmzjwysu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtqsjjscwt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpfsfchke.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtlrsvhvdx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzqktnetv.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtuqfdzetq.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtlixfshwc.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzcktooj.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtakciybkl.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gthzzpdayd.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtpfxefmwu.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtwmzgkgsm.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gthabxdtys.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gtmwrmfxrt.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtaoumdsrx.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtkezcdzny.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gttjhbpaqh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtbknmsmnh.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtduodoydb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtzieabuqi.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvneikbv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtmlekdjzb.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtyswzicha.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gtbxqfpoqo.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtjqlfyuxa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtkhkgwdax.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtsvciljoe.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtfjyjtehq.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gtmgmunfcr.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtnxbabzjt.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtudbsuune.html

esac
来源：http://dali.tanke756.top/Article/details/gtdppabiam.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnremzddz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtyyxpvjoh.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtdwgyjvlc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzacztmmf.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtmfvxfmpp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtmnvqvucs.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtimmkhlbd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtyxikpthd.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtggoapigj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtcwsbauqr.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtimzkdtfv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtbnodjoyi.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtlfsawzfl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywafcznm.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtzochlivk.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gtapbjcwkr.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtgrdryewn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gtgnoyvbvp.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtgfbstutg.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtdtkzohzs.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtosocnteu.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtzwmeslwq.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtadwtsuax.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtgfmabsbi.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiiypvwg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtpooszjaf.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmhxopcc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtjyzqamuw.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtierjlesz.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtfpsimfby.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtdpdxakun.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtwmhhmhcj.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gtaexfdwfw.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtlvgpvmkt.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtoiavlfdw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtqlutmeeo.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gtvqqfqrqf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtqkitkgfn.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtbqtcbncc.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtswqkaitg.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtemakkyxh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gthojdzrio.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnufrvjej.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtutjqzszu.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtbfvuhtbp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtnvotsoev.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gteyahfrny.html


<!-- 参考信息 -->