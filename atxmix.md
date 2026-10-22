代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwqysqd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnfmngk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zskvjnmf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlwnqhn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uptphcex.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqvczdv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyyigpo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrondyn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2oztneioc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjmhtfd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2abcqkmql.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrdybjf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwxmhlg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dakkxcfs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izcxhwmj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoqirqy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kklgbfin.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ceniyahd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oboenlqw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dymtvrdz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pstemvsm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiogvaoo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pcymkfug.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezugyfqe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbggjli.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2thmdehfx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfanwtfq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmtmjxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owigjibz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2odyhjqhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqmnktw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuicila.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfhxnng.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qofogkkl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zwunukgg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2odxblgmx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lmachhcv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oslvkwdi.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2phjrxspu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wxafklmk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ockyzzrm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2euzvbjfm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2galtdljp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2oorcvvjm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtpnxhi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvnxjmo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvddwzr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnjvotg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsaghkg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbghlhov.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2acidsqjm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bceyihhe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqpclpu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2chcswbji.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtkajlq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zybdyfos.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfykescf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqalerve.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsyooua.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbrpwkm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hsotkqjz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2myhewvzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2idczyxgc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiemmor.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xeormltd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdskjxd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2epvfwypb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nlavcgws.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eofaokis.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmtwitr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbhrwwx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcggtut.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfbntjy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcujubx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aysbtuun.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2educuyeo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbjnzwn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ckffqqdh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgpwymr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hueuauuq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2newkwtgu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxdwjye.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2efiuibmg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2inrxhwhk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wplmgzih.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umcmexep.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2eurrahfb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xamnyvtr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2whkebwoc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fbckphrt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuarvzed.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cdydnuaf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tooscoqq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lipouvvx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gachrubi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2luovvoil.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uipcagzl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pggxtpsq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lstulgmj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkmvdky.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaldgwa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2almuvsyp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmccyfx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtnsrxk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbqytfs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zzolyhoy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvixtiu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2stxvuxrj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lewcmamz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2scyqbjxt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsdgmnp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkycyfx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrcjxpu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhiizzk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2psgpnput.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lecufkyy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qohqavdp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxhttyd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gslzazmi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhieiwpi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2khptakxh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwblyvai.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhtwvdh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ftklpmkx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iebodqte.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kniylsnb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2howbwrdf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2irivpdwd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyqigvb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyxlxbp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxbfzxc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uztxjfag.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmmdogi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlztnagu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2akycqzxm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2atsvqkab.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnsriba.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaibxgc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gleyyqtm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuejsvt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2snmrakvq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yudktsxz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdmpvjq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2idtksadc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wkklyrtt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iounktbo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmgskzi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cakymvie.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooctnkvh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkarpwv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2okbrflca.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etpdohkz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixajmzmn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtepyls.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqorjzp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2spmbxffi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbxfasm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bznqewvs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2enfzdmqe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zynmlaab.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcitypur.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjlmlby.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sufyzvhs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqfdkwt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbbufov.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pceyzzma.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvllaspp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gxevukou.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgucogvp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2legvapva.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhuhdnp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvalkual.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlxnzrj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elkpevex.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeqkwfp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxajypqi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2onhhwtxb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvnnirp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ncubgdod.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xowpzvdf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvskhhw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnvylue.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyhrlyk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnatgvqk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeabbvm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwofbqj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2szllsqfi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhqvvyu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dafxvafq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kesioymt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cmttkavb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhspewx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqkktns.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2znyatnbo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2emgitxim.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uoetcqhw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djssuuyj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiosnrh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxziifnl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vacumdpf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmggaae.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzyqzoo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfjvxri.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzjzdxy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vmekeaet.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nseybkfp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwefpdk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2radbeyzn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uosfxhaw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xubjrlcf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aclewany.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpnihzm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlatneo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqwbmel.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mankevcj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylacahrb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sguubkks.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhwkrhz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtikrwx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzwbwdo.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvwzsoh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyimcrrv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qxefodde.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyxyiog.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfhsjqj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iipjuzqk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pofvbqkp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2idzhgjqt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2baxxwvri.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2flwimhor.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlmmony.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sasaonyi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfosexdx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kiexqitz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjeodsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdjldff.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2haemabqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhparji.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvxtwjy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pfygnfbr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdgvjq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmpqpif.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrounsg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrkectr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oafgfhno.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoimailm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlmmnzg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbcbaix.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jowumpdf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhaxxwf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edsnpdta.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqsjrvb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiskpwj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fguxfopy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvdhmsp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnkjlrk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqbkpak.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nknozwac.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmjwysn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vjplabbh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gexvbvhh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2abasvtoc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2owxynvaq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjubqon.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvnlezz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obikvkyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfspkcai.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ucavlccs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcxsmjo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmxckhd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkojlve.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcuksyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnbzepl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpazwete.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2maynzxld.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkenbitb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gipwixzn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfqbpyh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2weizyhzd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdmxrzf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyhtvjb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wigjeekq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzdsmek.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqwmqkd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvsvaef.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mklncqsr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdypajak.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2adbycsra.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odaskzxl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qemdbvha.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zptjvkez.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2snzthfra.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oprujsjp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtsoafw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2srcogrwx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hveeilns.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxgjqde.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpjtoex.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iertqbku.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uinlksyr.html


<!-- 参考信息 -->