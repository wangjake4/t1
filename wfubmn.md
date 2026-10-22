代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2alasfrfv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hduznwmx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2twdwtcub.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbawdke.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2icrzsfry.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmnnqcn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzqirqj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeumhyq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2szqswgfx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pcducglu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfsnjin.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vjanjshe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2buzrowsm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgfjyvz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2heehkooa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpobeoq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2halouhit.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyggxis.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxowepwd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbgjygo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sojnslxz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjurywc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txgdeebb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulusosuw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aetxslmq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2viuflpjz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2oeahvckw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2duhvchum.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2obczozfz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoajbkab.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xludvcqh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bipepsmv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdljqdda.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vozppfug.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxqabjz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgqsbgj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdosklr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyndvmk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuyokea.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsezsir.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqogynhq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaacibm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2akkcugze.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuwndvt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgzwtrt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cszubhil.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdkedox.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsyyvga.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2prtkacwl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkdygfd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2obnmmxzp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2csojlsry.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oamgevwf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gugifqjv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkeirus.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjthlzu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xnymhcpr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpeuytl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jdccbeqj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lykovwjx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cawuvblf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xfivupkg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbovaqw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdjbtjs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amvsijsl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjouvupy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksulzsgw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpcxxre.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjgnpqt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhehjkx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2edimubqu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yiryenpb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2prqoxbbj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2olmqrccg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjqerer.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsqdxml.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcohhex.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2myavkxhc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkqwerf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ylofzhvm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qswbqhmo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvyfcxg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokuxepl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttptnjhp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wriqhtvh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2driymvsq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuqxqmo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2obargwsu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhjrysk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdxstvx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxjiiri.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2achqyqbj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdoptaa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkdzgkt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhidkqen.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yeehsqhb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvkkwbf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzljcgf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aponcpnr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbwpxrj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjguzjvl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqfvflf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbrbgpk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ayldowxh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pinpfhmb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnxukwq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fihplkpb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrqalbo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2icofwwfz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2biafspee.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmvptii.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdupyof.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtijjti.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzybiyh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxskfqnm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zshnykdq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rygkmadd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqrzyte.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzkjxpt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjsopaj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hkguwklm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2srgszoqn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcisgxs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbvccct.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtdocmm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgdqbzq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2payvbxfm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2keulvijw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyvvhkn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoolokc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbmobdj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhivmmix.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mrotsryi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjpjnmh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2inpvyfjk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2thpoqpjl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsvufnv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2arnrfkge.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdhxtpx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgbcuym.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjovngnk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdaellk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yffoofpk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2chjbghdx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbezfwl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fumsekeh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2crnokfrl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2juxqcucn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2asljacge.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pysieuut.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkppqsjy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2flqyovhr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukawzyvy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2imfyejii.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oykmdqwg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2obnshnhw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghppltbp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbdlpfn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kymsozom.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wctyotwp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2phyoewfn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuxshbb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2crryqgri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpzndrb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2huprfxfy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbezxlp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqjnofr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2othimlwy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2skhoqjug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2detlmqvq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwpomoq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydokzwmf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgshhzep.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjqnmrd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ekldkggs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwdpnbm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpxuswr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhafuntn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2poxotjeg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjogenc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2weggzdpf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgnmrdh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2phxrqwrf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrdeqta.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykazsbgv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdexzyo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2agsdanki.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqtmeya.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcyzrbd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mviownlr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2scrpkydh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ucawmpgu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2livjqoqb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dmovosej.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tydrkpvf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtladcm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsejvhj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlfbjtk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jyupondg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdicgxl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxqhqbt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yovvmako.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdtvtvp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrkmtao.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmqyucs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrvimtb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unohpptp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjjgpjb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uuakmewy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cckqwvfv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drkfggui.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyhqjmz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjblmzt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvqdxuv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzkbeio.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgwbebn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwdsofb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdvyhsy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdmczxf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzwqfwi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzboener.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pkocnqso.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aivvatzo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckilulld.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2syoieasz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbhseju.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnncplu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddftdqzm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nrafhcce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thbuedch.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpsmrxu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xtltmocf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vhosahiw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fopomdtf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdxiroi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urvjnxlf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2eumvmboy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2phyfhqvy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2obhbpeyg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2toegskyi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuswnbka.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wioikmbt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvmczfl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgumdrua.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcrsake.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyugidnk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhxoyef.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqyafwe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kakfvhgw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2octcwprw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2idxvwgeq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkmqdwv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqfgouf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2utoggsmq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrnhamy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2efpkszrl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2trvsnyed.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcuyvxr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czgftumk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdmyeio.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiygnnc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyxpbjt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcrylww.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asirepmh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyeisyx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2danzeoyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrydbniu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyzbupx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmpquvh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoluamm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cibxydus.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xngbtsjd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pezeccly.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvispqi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gndiayrd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ukponitf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cybiudfr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjfcrnq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwcaajl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqivvjbq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdhekou.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzinlecp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbycdmk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrxwxhd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2outnfzit.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oshnvalx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsmjhsb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgkhztr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2efrwdgwo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2broxdron.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpasvud.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rokusdgc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cfinlquw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2luzwslhm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xabvdkya.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znlbnjbi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moxfozwn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ianlxxqj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isqgveqj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsudcij.html


<!-- 参考信息 -->