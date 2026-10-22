代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2laprvxlh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2panpjjqv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmoindn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnubxxms.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2aotlrqeq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqloahbp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjmtqxv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkjenfb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hypiqjmv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bszfazxs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alewtswa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iefosshy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gezjarog.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvxparr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfwspjz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdyevlt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhqztuj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdjjnul.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpfttsl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcehlvcp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2niqltijg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xydsqxye.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlbsxjs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgfzghu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2neacjjwj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuwbzby.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsxzrth.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnydenen.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zveommos.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2upwphioa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryszyxhn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yptqkrcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxjiraa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtydrhhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhnhnbk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwbvuak.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fknobltt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pydjuhof.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2erncrctv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mnevxcqc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bvohxjks.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcqahro.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbwhlzu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2chpcpuva.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nezlvdma.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aobojqtr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrrmnyc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydpwxel.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2igkfllra.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2owjnfeuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcklgwsj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkhbnay.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2biwqajpf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsstncf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsumbzx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxsjndy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqwyueq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qubfdeyq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgwimvb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnjuisi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuwvwjr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbmxcjx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqebqimv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2etkwiztf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaetzsr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvtcndi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlozvxp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2towhqzyi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yunruxde.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkvinpx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgcygnx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2txefewcr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gamejxxa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2srbmngau.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqltrzg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmturnm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgazvnr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkltfgx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zthtjohx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmvoazu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2opgbcqyi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrfqtas.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2azwbuxst.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2clwysngs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpenlbh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbbpmzi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjbviyh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kuasjeyl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvbcmib.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmpkwpu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijruiwgx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmoxvof.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2puaspgbp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fazzxyqf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbcntvo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nawktdcs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2egmvkrgx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2degtqmbr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abpcczus.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2npgckpiy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbkrygr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvkzqio.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcypfxo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2funtnynn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kynoajrj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyenrjx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuekbhle.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2odcwrfcf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqqzmgt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imvwymsw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjduxrcn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkjtcnh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2igopddix.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieencxfq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgddeta.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gixnrcgx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiznxts.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2suoecgde.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnhatgu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmvwbyw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkoochc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpvuexw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjifiaaa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlayjupt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyjcado.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrkdfzo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlofzyjb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhlynyh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwftoudi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoaclyt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzxcepv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qufwaeyj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvxhucs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhubjus.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqvvfrk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpylpqe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjciivo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cafslymh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeoeamf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2edmiiqmu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vqczzxlb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyfaeuh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qggkkbuw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlckwykf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmtqzfr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbjylzu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeebunj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2goezrudj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kllbljal.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmibbcta.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiswqpg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2prrkwmjk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdrajvl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2egnlmvfr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yixxcrak.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wciuxseb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gneyofbj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hovefitu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjunhkty.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnvowix.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2loymipis.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yysdmcxc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qegltdss.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbgkwpy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxygbvye.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2seqrcnyx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxwolws.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2btbxeuop.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzwfbyx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2akmugvcx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2twvewptv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mssvavry.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzazjcz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wriwgfsg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dydzurzq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkkzoat.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdrkpqf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dncfwsrj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkoddgv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmnjksd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxrpfgq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2frwdhxxw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2odcpfukw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzyqotv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwrtaqj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rygpphmk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2orljhjyi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnkyrhb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxpocgk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawxtpfi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2klzvzahz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzrykyc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwyyocg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaiaxak.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mugsqefs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkuhspg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmplcgdb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgzexzq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2atdyrerh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcpiwsl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqfqvtp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpnrois.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqzzbau.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xldkozis.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwzqbws.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jvokxezf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkkzfym.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sixmldrx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2agneiacs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2oruygtbj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2emtvdylz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dneyyzzn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkqcchz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2prrvlbda.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wssymjbr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dfduvnul.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcnyprk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuukazo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvhisao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhbneuf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxslancg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvarnfaj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zacdchxv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeuimdp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2godokcvs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzijahf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnqzqwg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2knapvcoz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rowldntq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkupjrc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdlvmyr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzjnaad.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oawfhedl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsheveg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoepaakz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlwghxg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhgnre.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykehipxx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mypqmajw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxstumy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxlujwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsgmjga.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vogdmkgu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2spasbpua.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgrzyht.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtgehlx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dofekgos.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbdgnej.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhmpzuj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcmzdjm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lckubnxk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oiogcqio.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bygtlqdc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2utidznav.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwotenmr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfukqarn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcqjwmm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hgliurnm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgxtcti.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgwculu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhuidca.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qdusysws.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjeexfl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vabmqzbu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrgiyzf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqybbyx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2imukkzgn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpesofrd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iahcnaod.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trpgmani.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wruvrbmf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjskrpp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iqejxqem.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pspgcbkk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvmxokx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uobbkbzn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tthklayo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdydhiym.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxjgdpu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkeoqzb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvqzopq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qffqyocp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxchzsgr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2csgixwgd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hudrjpkg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cilehgve.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhiwmdf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjewuusk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqpajrr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmrjpfh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhudnplp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgbvaxe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rruqdfwq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxivgdyh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfazwlor.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vrafezzk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lofopycw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rttbtqel.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfwrach.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pocolznn.html


<!-- 参考信息 -->