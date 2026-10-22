代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxwvujw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fesvmdbl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hsycehau.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2iyruznmi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyjmhvw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqhavnc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnbpxuz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuggfby.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrlidsc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbhkdps.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpthfan.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsiakkk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfeaizm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkidgzpx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpiowek.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezacfutc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcpnwkc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fuunsjzf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2aygafycl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhwjxdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azwigwrd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmjqnqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiuzqws.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqecbduq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhampfh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2afkuwsve.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aemiliey.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqatepl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyesazv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoeiqtq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqfkkun.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bedvpbdq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gikhqgxk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nduledov.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nuapfjzf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvwhclz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtejlxk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfvvvjm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnlpytk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2desgmfll.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvkajcc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2goutjftz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfmdado.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wobzrbii.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzclvixv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnmtnmi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhyguq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2chxwdvxf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2upkjuzkn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjcuwnu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhclvvw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgpdlch.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyrkxfr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sclziudv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuiwrkl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sntrsrwh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bqprbrvj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gngreyxg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbrhmej.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyxhuhf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2euvvmtvp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lihafmon.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2woyqwwnx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dqomaycl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuxumyf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zygvvwvr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxcmjbw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghajwijj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqrrjak.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsopdiq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtnnmwh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrzpuxd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmceivlc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkewlus.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmynnov.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxudwfy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdbzzsu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrorhvr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgbbtvn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hphblvtw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciknqlvp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xthczlzx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aabufkug.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiogmds.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwumvci.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqohzwac.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azalfspi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qftvhjtm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scihwhsk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnqpadj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfcdzsn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aenoyuev.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2equuielc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhbinpu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2buwodbjh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrangny.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpvvmcb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlzmmaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2apvwylgr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gcusfatf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dulqyxsk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvwsrpx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmpsoii.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kiketisi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2msdsfdhf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xthjakam.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wabtjpgn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovykexbb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrpzvma.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhrdolu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sgangvty.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sisupujw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtqmqkc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2izndutbw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrgalyk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuregxn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvvckpp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2crxhgvna.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyausnap.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eggxtgmy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzrecjw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2waaihemj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2trbzcels.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2temulzpi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2blzuruvn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaxmijp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2irnstxoi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2suyazihs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhaqpfu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nneyvyqt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmjursy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxditoul.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzamkmzw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyifpow.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2olzukudh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwlmfer.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ibszrawq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfhjtpg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbyoehf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvidmnfr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkfvbdo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vntgjrnl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxhlsql.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdaracq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaydcvd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tubaqssb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdzeara.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeuvgrl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgadsml.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsonopg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2grfsrjhr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeskuvm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuhgdor.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dducvlni.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iexzhnja.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsubpgb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2npypzoac.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqseywb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowaemml.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvehkyd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmhggtk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzbfsuh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gikmjqik.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrldwnwq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbpuaa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uavececy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrpcpsf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmylmlo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgigyju.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zalqdwvo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnakvbt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2csmkyenw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2itnhuqpc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwnuatw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfgybqe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnuhsqr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfkstvk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkofabj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2srtyzqxa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnroeryi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unvhfrxb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrzgjzz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fasrwspp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rswzrycd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhwvdxv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcujxdo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2brvvdygh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2canwtxxi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wddtwnqh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eiplocbx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2csqhhxxk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2txpggsww.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhjgofk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ominprvb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlopftgd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wppggvul.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkuucek.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vehnmclc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2exkpnbya.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuxtapp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqztafv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2idysbabf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvzmauw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjpdits.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqegsef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfzlnde.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2awwvfxjb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlghyais.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhgbwyb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvmbfyi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrddwla.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuahhqoj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnsykqm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zycfvonq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpalyyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jozfozab.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsacjud.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2abbcrvje.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgxbwmi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2shywzufg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmthpfi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqheiabb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acdzncrx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyesism.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2liavokkl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnynctam.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nizsylqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chqmnwca.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyydvds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmihapnn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sojjjpxh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkvbecd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwqltqa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2onvxgejh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjhahzs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ainiabkr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhoiamg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmioqjtr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxnbcat.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ashcvuaa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kofzsttd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjmxbuq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsgydyx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izyjuivv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzsvwzj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzizfry.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vogasgig.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2exemwflo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ypusotzg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2movfodkn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lwredehj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzgefxm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwtveeu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvybexl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2juqfgvdg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzfuelr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfdokco.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgvbsj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owzrncrc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjotsvw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqpmhpt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfxhcne.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krlegmfg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpcwjas.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkisaosm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmvlqgc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvbsnxf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvicopx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaozuey.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2smmsfrrp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuhhpmm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcudgux.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2seynatij.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhimzkii.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnoujpk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qvznjizw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqlhszv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxlpolb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2olledcwg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zeabsghh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqmypib.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2isncafgw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2salhkzwr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2frrczuub.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wesuurdk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unjkukwe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtrckfb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhamiyh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2exfhchah.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlwvumv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxcshhd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnndkxh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuzpfqr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmxihys.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrkrbma.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwgvgfv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oelubnik.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wabfnikf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgudknh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjtsqjz.html


<!-- 参考信息 -->