代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rygykenp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2supbmvok.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqdibyd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfncyyz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fvygvsaf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqgbiui.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oakcigon.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxefkgwm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uvomcgwc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkjhxcv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbktfyb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeveflkk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2diqunnyu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpjzxiz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iltveltx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvqeqvm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlnafra.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnswhrm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkcltag.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpyxbxi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvjwmbp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyrblan.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uydcpfmn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kizusctz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvgoerb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xamikbqi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ukommrqd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwphwud.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwqcucb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfnljcl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qylffecu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvngaeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2achzgpgy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkgwchf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkswgels.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fteelsyo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhvmlsj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rpelgkwg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfanpfj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvonsqc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrllauo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2projduti.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyxrfcl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ouredfgy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeqpoux.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2owgcvaft.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqrynrb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lowlwlhz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjukwjol.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbelpli.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouidcwxd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnluznpj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoigvev.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpslopgg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkrwzjs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2skvmmkuz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxguxfyv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcrmhjn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2svjivpyj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndgoov.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2elonhewn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2piwgwjki.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2olvkheif.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nnskvwsl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlfxflm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fetuspjb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmwvpoi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xkglmckw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2oeevkrtf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqgpviy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sznnqkgq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlnacyb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkmogak.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvetstw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzicngbo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uchepzzl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmjoich.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovacuzey.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgoowwq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwykdun.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnagpcx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rswqnvmw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyxuxxk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjthxmk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqcumpu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgciocs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbnapgg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxozacj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvzsrxr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2thiekonw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpjqbrz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbknnbp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvibabx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2natmbpzc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2daucwepq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kknribip.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvtcumc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mariygut.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwyspy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrqjxjm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsffokma.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2stycwyqn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gstftzaj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pedrlhds.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xajrbqcz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqzdaxm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iguxufia.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvknlss.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2behzteab.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjitrxv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhixwlfd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjyxmxi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfohcmw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2geoqwavw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aafagvwu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qerkpbgi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrkrltn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2finrthcg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kutsvpzq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjencewm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gklctsje.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgxtaiq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rkptxedk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlznhty.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcortocp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmniqato.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmbyafi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vohitifp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbnybhi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvpdgou.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdruvve.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvdoyrz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkkjiou.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mewijeim.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2udpojsdi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dpldobsg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zzybnggk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrextybl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ledchhyb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkdmsyg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgtalts.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2migwvaqa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vfndwxap.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxkxhvi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgowiog.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2afbkoric.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slzkwaay.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwramzm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2neoaubqj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2plbtkedy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbypxmrf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tooupuii.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnhykzf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2osudiirl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fsempkll.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeoolwi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmuhocz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wixvupft.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnogyht.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdtavtv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpfiqri.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nihfjjnt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2htdmyfdj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2izqofqrv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2agbqzvzx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2injslgce.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqecylmg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aarebtyb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qilbtvuy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lazuagvs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dipijyrg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbysnrd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcyomsa.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2maquqqlc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvovijpl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zraepmuu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ulitilqh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gezugjip.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2daactllx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsfgrkd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qctzrsod.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuomokg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpitpxbs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzrunot.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vciuhdhb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnziqsj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfrtceg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwpyoud.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rktsjwzi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvkcwuk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bikrodeg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtitomh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xarwuuvw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2btcmlnmp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yndtlyzk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfddvgi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isalcjwb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyajyet.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zkehucqj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tbujawwf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrlawzc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2riqsyuxa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2urikrqzj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbekaeu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjcntwg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2juzhtmdj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxumtao.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bexicnqp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvnhyus.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2myzcaeaf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rngsuakw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kynkrefc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ierpnctm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vijffxqs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwlwtmx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuuyjlf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uloknczz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrjdtns.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzfuchn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gninpqdl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvaecxf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqxyhcf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvutmpq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rovtsolx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2llqhwrgh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jutxfoxl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jykjmnwr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruudmjoz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfbclcx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2efhphfoz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emhbpucl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hroeibxv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrozmpyb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqmftsw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtamailt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2srxtxsly.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bcutnnkk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kairjyex.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mugxxzya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbuqscl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2chvgmkqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpizhoa.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2shgxjdew.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqdvkiu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxhkjnm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjyvmkm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhtsqyd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzyvlym.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwgcubw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spxffikx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iynzfvtf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pcydutqh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2essxuqce.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpwhkto.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hturpcfb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acnyuend.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sthxspcn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgaorgg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ijteuuzu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zkykwdyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2irecfxgp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfwfech.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwhlauv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeivlbh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nztbqbbr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2idefbkjd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgqkvcu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgoznwj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2axstbzrk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfptseip.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onfiaofb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzszyod.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbbqwnx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rdefztxj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpqwgrm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxpknjn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdadsoid.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkyfoyu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgprbjgd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlulfgl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2geyftlua.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2juvcotak.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2izmvaxlm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfecthjt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tatcbrkt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfmbrcj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fggaeqas.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vraaypia.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaggwkc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfsdlzp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efsjutit.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdcxge.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxwefgt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yneqtlnl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2irjwuhqi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ewokvkga.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsihtxnd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijonavnm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfomxfo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkclvmj.html


<!-- 参考信息 -->