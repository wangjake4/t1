代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2benpkdmt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfivfee.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iouzugjy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzthyvoo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2daewrfpf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmdjkag.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uxromklu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhrxqkg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lajncjmq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2snsbxgsx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cskimskg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiujzibw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bknbdoue.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkaoofg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtnwuij.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2evgepipv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2paluekcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2asmogpbr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2enicbfsc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrqgghr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xoevbhcb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2aefpgkzh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjobiho.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvhwxfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twkeddji.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwruxbgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aecnqtla.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qluwiivi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2quxcppiy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nseczypg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hoekgpag.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2egwfpehg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlvjjpd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfvxcix.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdbuwrm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzriagp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2swekpawg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lojknoeg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hluriylx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjsulxs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnbryon.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nuijeadi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2norzfoma.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqniehzp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eteoohhs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2khhncmlo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxpcyav.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2axnuucis.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlahrzr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzyixef.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeiiayg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajocgtfl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsrjkud.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gavzdker.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjltxiep.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cydsdyia.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvfujnw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcptuip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vrddcjcb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmpdnfa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2crhfclta.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuxjygy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zphccxxt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eervsagh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iynydipg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2njnpouop.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfxpglw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bqubblym.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmzaixt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnlcxry.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqwhvak.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wglshmgo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmrwddm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oszbmolv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2axaweefi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfrjiyz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2abxgfemy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqqnmdt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqivelty.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2udglpibf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkugyrwm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybboxgzl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekavaokc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvoodyp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2unwaahfp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ralroaja.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rffuneeg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2facaeijr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2egsfpvnq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyvmmid.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yksuuoyz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2taiqqprd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrugszd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2plefwmli.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlatacv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pifjynkw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqhmryz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxhbxfj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlazxsla.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fczdgczm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkaynte.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npwvokcg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2srkpqday.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vbndwgoo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iqszvqxv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoekhum.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cryuvvad.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2edxpnjsn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrjksox.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2slljsouf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xvexjnsk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtotvpim.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeejtkj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzktawlu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tofkqfyj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfuuakf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mholedug.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbxkugw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2obkvekcm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtarvtd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrwjrnw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryppnbig.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuislzn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzhduqx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxjlddi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnjqkhv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcvicwp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gygtddyt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2urcgxels.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnsjxyh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ennpbcih.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzucwxag.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nbinyubg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2inkkpsmr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bacqdppi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeoubko.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mykdfkuv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjgonav.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jmijndpw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrxdeou.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hndusfge.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrcdpit.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmfnath.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mweweapr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkudbldh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2maouyuxp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdjqzoe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjxoqqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wutzjeox.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zrikrzkh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnondja.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhtjszf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxmvwtd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2olkruwoi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2phvwwaex.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lerxswak.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcicggem.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsevzxzv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuywmrf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnqcxph.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixitktix.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2danibwrz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2brspizgf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2chifmljk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwksvgpj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgjipk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgemtdfh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijusiatj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2recyqimt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvgzqib.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwtihjc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iknijwxn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvibvxfo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2femzwovs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnsiuww.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iszroroz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwlukgy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2whlbpekh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwunijs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcvgrtx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbqanbn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbarzpek.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2szgftldq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrdbvyf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jftvajpc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwgwqef.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kotwqztl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hcevjfja.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nptsghot.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lugconvx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxcovfq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zypihrau.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvibdvsr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2urzmbmvy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2etqcvmop.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aillgjoo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kthbuuqa.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmdichl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2krestnlv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nguadqjl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhlpbvm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjyzbwg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjbkcph.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sqevehkp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmswlqz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdizylmk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbbegrz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pperkgif.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwrkxnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duxcyani.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crwwkyiw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2neorydoq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tchgcrrd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hungmfnx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rduitrkq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drmxpbkr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cvktrobd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dowdoozg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aykzhybx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dppzbykq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcvyoyd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2klirfbch.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2auofospx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcflazq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2spnmvmuj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqhywgk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqtltfn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iygrvggl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbieovs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyatuwc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnutfoxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uogcihyx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gbypvlga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chwqbmzl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjtjtdz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dshsxczn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoykpwy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2atplvuum.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2egltoztz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnomofkf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2juwgtpoi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjegzijo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbaxodn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2deghpqoa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qesflozz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eoryarew.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvgonwm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbqhcok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuvvcvx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvgvdtv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ikobatyp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2npdplwcc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgkwaod.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bfepgcdi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbpfolq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xadbifpl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2drljsmbs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zozendnz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyhysdl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyucpkgv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bobamaev.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvefqeg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhhmgoi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgytpfj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kltvipll.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnmuykb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jajsalip.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcnsbxr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmaxnzf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzuibcm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dszfwbyd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbsuujb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzchqj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2plehujob.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwlakpk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bsahpbwe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcdmkrk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfpckon.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghykzqwt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhdoutv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcugukx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmxqpfl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkvvycc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfysjuw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbucbfy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivisujtc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbowrem.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoqizwy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqratcgq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2otfwnlfs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dielipvq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nipefrzp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjmepyn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkzndcq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xohyjgtu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfulsvlr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2razjqimh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmtwewi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlcqpiy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2repctvkw.html


<!-- 参考信息 -->