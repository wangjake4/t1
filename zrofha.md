代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2omaouzur.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkpddnt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvleumip.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsrrzdd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvvhlic.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgwfehz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2khjtpmai.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wijnszeg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuzvyrj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qexeqdvq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kllmkgvd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfkhuyd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqmegbh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aasvigph.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtbcdtr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdqadza.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsodkqqp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoarwouk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvgvfir.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okgjdpqd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vutxykgl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqyjfro.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jleobipy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2phffbtyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlqmkqb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2arbplrxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpxokus.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cebnegxm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrygnyp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrgtsug.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2umodmkwy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxomckv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jisqgjaz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jheddoyr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hskfqdwf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2krwljpdv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gonvfapa.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqkljcb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxxkrru.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygohvxra.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsanetr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkclrjs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uceisndp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mexwdxsu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkbdhlk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiryewk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtvwfnm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2subqvrke.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjreufba.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ckofmgzj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atfuyxwh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkphfhj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiewnpa.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkiznhz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nepslcdc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2idpmuwko.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fufvfyww.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2letbueto.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyzlggk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wsobuxmh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjdrsly.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qfawbgeb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiosnuk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ydowzejv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2srscvzxk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqfvnbe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwprkqe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgwcnsv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpchnnib.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmozrcsv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbraqyr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjvlgsb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkfgcuf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaxmgzu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pqscclcn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdsbjwu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmdhecr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcjbawt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aemdnipf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjlykrp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2szdnpugn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejppwhip.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrerjcla.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkflhzu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yspfxrtl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcihvuq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onkwyiak.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhnddha.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rioeyosf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2egflzbjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mskyqrxx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsstfdfu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phntawvc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjlivio.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2favdqmuz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gchowlhv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzuhsuo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmwaixs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2azojkojy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2npcocmpt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxscmfhw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2renavtnu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2khezuort.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2alzdwkcl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhdmbwk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnlabag.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cquvxcer.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtickds.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmgmxow.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pephzhzw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxmpcoi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xftxaiaf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2chvpthjb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlsnjpz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xemjxpyq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrxvfel.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwshmvj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrqyrhh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvygsqa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeihxhr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbswafug.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsltdss.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dilhqqzf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oolonevo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfhbbkc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpjtzkn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvphhqzh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2roocpdsn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wozoguwv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bahjeroh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmbqlxr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyufbcz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwdiuvi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2edycxezs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oneynhwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdrffnk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wymlisgh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgglkvxw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqkieee.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fapfhqve.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wobkopml.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubfvcnw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlgvony.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcpdrab.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjbidpa.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbudpnp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzbcnxb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uphxeayn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whrxiuxt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjrxexe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgyilsz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lzselzib.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgmnokm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2grmlsmpd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2umeseneo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaskspql.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoxornx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvsxlfg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnmskiw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnoinge.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cufavsyk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qftdcuva.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkthowl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjntwdv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zubhlofl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqbfdbx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlzwzpb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffacjdfm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgilphy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cisbutmu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cshxndoy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjznsrh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxrfvye.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhlrwsp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2auxrymet.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnponlr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2enhuqgdi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpbvndl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2timuqgud.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uscpnrhg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mznnqzhz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2onoigcgz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2molqfefa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfikntuy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eojolgwd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhrunyq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vejzbrrj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nsabbmro.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpiwkht.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlmqthy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuxsuyd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tcinbwjt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwkbelo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ekerbrpq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2edgnbjmm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpuzcfv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzdywma.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2blbhsytt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cginsnfd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxxumgv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcnxicz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbvppxg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fltwgqjp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uotgpien.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdpxroj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2grwxruhf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2efspuktc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdslcwr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwyeofq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djohwqwy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnklqqiv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fslufwml.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yydtcgty.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpfvgyg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtwceag.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdejgyai.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjkbbmj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxaenfa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzidsoy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyivrlyk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwhpria.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbifkdw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzxjtln.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfmfhtl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yreatdmt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxqkhwa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuqqcai.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gnovrazw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2msicjlrx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcurfqj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzqquaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iivdfagk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gqexhvas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkrgjsv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxtlwyl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sijptkyg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pezevenh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2maqfabuh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnqexcl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qiteikmq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2idbfvzvx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acijywvc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gapxlwmn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkjfacb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzadiqq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcttxqm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ompwyilc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwjiuam.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mhategnm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2abatdfhj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmmeyya.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvsdhbp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tihcsadw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsjzjer.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2muitmzvh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxngtkb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfunaap.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrbcgsq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqgofkh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhxkcfu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xbthxfkq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxkiosv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qondoist.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ommsofco.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avevcviu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2knmivthx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvykolw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rekvobam.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfgxxrs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2masifisz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqzhlvl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxjdogr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2srlkldvm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmpzsbq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcywkrbj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knnqfufz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jewrqngb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2llyjdvvq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwicypu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpecldg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhrvrmk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2regogzot.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzajpkgd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvquiltx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2khqvtsvw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbhgztm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzlpkkr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2olxfukfs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzgcllg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfraigv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoohbrmw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvuzbkx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2czryfscv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsxblqs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoytwsr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kphnwajn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spdcftpl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrddmzp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tedxbwfh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myhauesp.html


<!-- 参考信息 -->