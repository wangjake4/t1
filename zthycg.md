代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bfliqptg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2khprxezx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtycbzy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcjfcxi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uefylfbq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiwsmni.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2njuxccfe.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdxirui.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmvymic.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmazlya.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcwfejs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esxgxzyg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmpzzlt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtqtcwd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlwkach.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmbgzaw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2elldqfmd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apzsuqsr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeyrmot.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxzlora.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxibksys.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zonvysnu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqftwsrb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jugigdga.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdpoigg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lkizwsus.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbjbjyh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwfkahg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqblyogn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jklvlrvi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcdgfcs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhedscs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxikpbhg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlxvwts.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2omncawjz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrmwmwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiurnck.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nygalthk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iawuupyg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2odembcnx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kpadjesv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cnacemto.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yibixsja.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2eryukkca.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ncunmure.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2egtagoig.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhsajcb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbllcpg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzdzzor.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjgfusy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxjvnqu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxoubck.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2risidlff.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdapjzx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdeblwu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcwxwsr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjslysls.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqyexic.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kymtnlgk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2itdepirn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwpjjoh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2coupignd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iapdmghg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwpydph.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqpghhl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fdieatjr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmajnjrd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yffieuwy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vvafmgqh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcjpkeq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2haoesssi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yecarudd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtyzbus.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2spwdjjgd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2usihgrqv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ydicrixj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oesfpsjd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqngxfb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mypbflej.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsytpih.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfusebj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrgvghe.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfwdhyy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhxpcdn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxljxzkq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaibcay.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vngubafb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ideijnkm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqvzxej.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jifbajzt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmbbcbn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wikssjtq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtugqac.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnieelv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvqekmk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdgqovw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtctyoa.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmcjpro.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjvewhy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aynkjwdq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ddquamyp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fklxwiii.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uezbbfzj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpakshbm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djbazttw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxthyw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpycrddn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eacojdjp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkamdkrt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeasbhh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2arlzetke.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2baaijumx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhuskxj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hniskvfk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrvumtd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kszkeyyh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2teunnork.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2udmlaqne.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkdfqjj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gceztzay.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2evirohce.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfygigtm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxpxwja.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhutetmn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wyddfmlq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcajrlv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tpppfdwf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhdgjcv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cijrqpbt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sumpnggk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2svrdiqor.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjztrqg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vydrvtxa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxkdhcx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjkddly.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgsimxg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiqmlaw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbkntjw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqowllha.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wiblpcbv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwjqxzv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2evdorjcn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2exkxhvea.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qitvbuqn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ongdnqkk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrsnflg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yxatnacm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2imknqcdl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2asbfuakh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dohekssm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdybugb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyidrahc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyyresw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuulxlj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sepkmxxn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtwinxi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjjmhex.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzupmur.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfjasqk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqndfjp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrogkugh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzagkdds.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aceeryjf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbecqxz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kehhyupd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkthotaw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxabfgo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhialwot.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtbeewa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zicupglq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhcebxo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rozalzet.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjluste.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvyviep.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrvpbch.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rorcpzbr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cebravvw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2muvsoflc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2aehblfzh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bquicqlb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhzrfoq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfqcmvj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xlomnsus.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhmbdxq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyzsneo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2auniprbz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yunmbgno.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhqmlfi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkiynjo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2upbzhlyx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mlntayux.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zblxcudi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iicnnqum.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwmkxul.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbezpmj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jieietxo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2invcthkh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2thtkssll.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sthzkvii.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwjgudf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsbrkmz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hbefhzlf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrsmdpq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyibidy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxhmqng.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjwdkij.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbdibtz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2damoznxw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbkwxvk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgheyoo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2satqvgsw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgrkkjm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vopfbryu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2roecwnrr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzkgspe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aadytllo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoydmqc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2avqlmquh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2szzcazag.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbolehl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vcudmjwh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khfqbhgn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfiuymg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrouguuu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdvcagw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sknptozn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejspktdj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyhjbsc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlxlawg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2besjvosk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoemsun.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyhirby.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqmtvlh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuolcod.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyubccmn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2soekmuis.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhjfoao.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcyaprj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzdilpy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzfqvss.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xsthrdyu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zevfsteb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwccgwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwrsmis.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2krdlcnva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhttliq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hieynzxp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yygudibx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhdjcsf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2msuoeshk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqjjjll.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2arnrhugb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjoknna.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzjqfct.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rywualwy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vruufypa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epmtigpi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyuujjf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohtocwh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zypafyuu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2puondhef.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcbmyzv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eseqsmsf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2csdqgjen.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrjwppp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvaktrq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpqdrct.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbnaxhr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtgzmnh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gguqzkim.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoptnbbb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzwkqq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmbmsxh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2daflhven.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qssaegxr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kwltzxjf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2arpplnlz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnebpdt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkflcqb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwxjnsu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gohwytwp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzfgmvq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuovuoq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeoxfqm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jusltevp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqwanyn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vaukuyqc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkwzsxr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hegxvvpr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjaevim.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnkbbsd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wligrpdz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bneeyjjp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnwguip.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgvnvje.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbhxwgc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfwrysn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjujhulj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwypfdc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ldluyovq.html


<!-- 参考信息 -->