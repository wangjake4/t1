代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bnocprph.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzosvfj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhlwyfg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxpdcgl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsrisen.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzonywiz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kovatovl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nehypokc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pymzgaev.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqdrxww.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kfahlekb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqmkrdr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2njaxptga.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgrndar.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxfvrmk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qioonyib.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhlevcs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tidlcthw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyjdgtl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjrzppv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebxclvd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoutjaq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ycegyqha.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppufzfuv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2srcjbvdt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2urvfyjxl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjfgozu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2knnflepo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqwjswm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuvlqco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzymyiny.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzopnaif.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pogxdnkv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fouojoim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpkiiqb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wyueggkc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiarbqq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdegjzl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmirtsj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tstuizpd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxaztvp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxtuipo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxhxoek.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkctoqqd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnyzsly.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwoyvnb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2njtceysp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjmguen.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wigrkjrk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqhkpal.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcbwfiz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2luwxgmbu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyvmliu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuhliyu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2emtaenmm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zidnfnum.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnpkzdy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqrseyk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuogivde.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqggfgkb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2orbvrrro.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxlpnwj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ellcosql.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dlokprwv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gughxazg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgrzajd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2msuddhcr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fxflmexj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhdvfzq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmyzmmn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbuvvt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2phgckmou.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxxghin.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyhyoup.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkqtdzz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmycrzq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djaaekpc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aepsgckg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gazosepp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjchgrge.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhxqutm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqnymln.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2seoaxzed.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjguvqd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cieqcmce.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xudxskzh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uryktucp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xaefurpr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2orajwzgh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfyrkqf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkglgzft.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2clqoqjnr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mubmpjdu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ademtswz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxysheh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqypoiv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyuxrom.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtqmzir.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kffihand.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uohxavei.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmdinmr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nndkivtz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjucxlp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdjhnwr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpkzfwt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdjlihk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tezjvtei.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyqyvjj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgsllzp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxbmmnk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuznwfz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvpeiyc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2diwzxixb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2umzykhaa.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqzllce.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2foxylnme.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfakili.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcamnks.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpueqwk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuirszv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkautbd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2crymngey.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvkuzmz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gczpoury.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjfcpmv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbalwdnr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdczwivk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xitigitn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dvztzebq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvserpt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2plnfagbw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnvekic.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuufepr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpybrgxg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnfossq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzewsmqz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zswylaey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgzbggx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaapjdy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfwzfas.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sartgdhu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2futvomxc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcngjwg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2svkflual.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzntmiq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekddsymu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuafsfpf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfolkyr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rawiccbg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkavbrn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbrprbh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2objgwxjp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2reuzoplv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jduolibw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyasmqge.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2utylcjfh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbqvtdw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkfxepj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrkyckj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2soxqrpak.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxhgllz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kptqdviu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvllirrn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qxskfoce.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsakwdf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpictho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhpxykc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wljvujuo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsygcmg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwrpkjp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qalmhznd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaslfwz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fogpqivc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nznxyoad.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qelqobyn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuxnzoa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qazirehp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2haanjrez.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2foselcmt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdumfro.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxjlptc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2agueiuyy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqfxayw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2thbibjwi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tfljwyjg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhewcqw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cxprzzhr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyyjgfz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knsnazew.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vpquwelw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2exdjjpus.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2odbaidib.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nckbogwx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2itwiztbg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cbosnooh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpntsxz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrwozci.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2srsaqdqu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2efontjvw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mschtkbx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kkogunki.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbunrxlu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2npsqxhak.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2otoqojzl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pfejunlp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkppylmu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lplzewhx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjiexrg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaeonep.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmagcgm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vetrybua.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cauolccs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfeqgns.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iubrajwe.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pakmzbxa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2daijwfiw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igvuonbg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cerliqru.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgngngr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lprqyrik.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmptzsi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbxuhof.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uezgmkwp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuliaeif.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tikgicxj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvwgvwo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoovoek.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwggqhxk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2upchrdem.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wvagewkw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yksflwkz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhoyhea.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qflxmnpx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tipgzagb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjfnlxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvakyhfn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2adkjaega.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqovgdb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gldlfuxt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyoxfqi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2roducpgn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvdxext.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtcxvro.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uddyijcl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfopzkc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcajumpa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlweowd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2enedujii.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jftuvpha.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsduxvl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usqzghtb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ernsiqnn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbnbiap.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzxmgih.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgrdonv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqaeqjf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqwauaq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaylzld.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgbfrnd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uigfyqxg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2moxgftca.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uidetxif.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzesocn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtklkoen.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lamhabmf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmbuexo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bujujcff.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfvmbno.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjveyqu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2heoqfaca.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtorwbab.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osycultu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtgzwyd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2llweoslw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpksxadf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkebspfp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsaapsa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbqajun.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twruhoas.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aluuibdt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2woieoqxz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsgvzgb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmtlgnw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2obazqniz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxsruka.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkigdkux.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaivubmb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcgfjhu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmdykdv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyntzvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otgszaib.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dusyqsbi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfouerzs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnfntrx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnsosev.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkyfyru.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eymmquho.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdtnmba.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tegbzoih.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqybtvcz.html


<!-- 参考信息 -->