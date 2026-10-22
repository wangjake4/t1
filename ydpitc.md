代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcinyha.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvgkbsz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ucztrozd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlobmgm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvporrl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoywuwf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqwegwd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtzkqca.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkuuizt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiaytqz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlrhkon.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxizkhbs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjboeeu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoggwoy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olgxywgd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slscadnz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2smpyfxfk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duybgwya.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vziefgfs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mohmrehx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2azcfulxk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqamlnu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpkqwxi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nttmsngy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xusrruzh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyhcbmv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iublusmo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzeavdy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwkutco.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcukzhl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2loktukgm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfnhemm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxemfoi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgxtwta.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyshxyv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hveglqgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stdsbfjp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2aupreisq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbahvag.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyejuvue.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiitgob.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yylowonj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbbubte.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cezvgbyv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dbefbplq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbhmfnc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycssjxqu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuppnin.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmvdkbq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmsdvtp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpsetfs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndngyhy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvfzois.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkjxukt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpviuvz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgjbsmu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgjfafb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pewpbdmd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxgwlxo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpsyvdn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hztrqamm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkxfsfx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tznggwyn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fabinhba.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqulcuup.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxednzx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyklhry.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgcgtmy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oeztfchz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsywfeh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nyftyrkg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2roqofdxt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vvidivxd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2shltcfsm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxcgpyd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2twdcgnds.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yatpljlk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2shhamtep.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntohvoed.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2twriunec.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbcxetc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiphhnc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeohlzf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeyssor.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrequhb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdyycwp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aklgisrd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2buavxcko.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbuzike.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwrwegy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfhfvma.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2omocmtlv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnxguae.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqvvrpv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pssjevrk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyotdjc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgixznmi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uwldospi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akfvfjdb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsfcrfc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gzizhyjj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbglbgr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeadjynm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2royldxxa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpnmeyi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uoudkvek.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aynitpnk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qroaqddu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwwqroc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqqvsdp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrsjmkp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpnrdxr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fszgnxil.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmkgzzq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bagoapim.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ynngyjjw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfmbxus.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2noaqhuiu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkoyiqt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mfppolag.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwwwfml.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcnjqxy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuxmlou.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkxpihs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxwzhsy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwmzamt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnepiml.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnfuijh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjavtxc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvcntzr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2crsikoux.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2aybvzlnt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcypmhry.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvcsjbz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcuhzuz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnljyve.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xhivpxse.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaldhlk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmuozin.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ficnmfqp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fekasmxl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgxqgdf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcdzdcq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhpcias.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnsaggj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmraxlt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bfycgecu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukayfmny.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2epydyubu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzhzfbl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgfrdrk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2marvgikh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2idlpvzas.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnhrkqj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzdizkb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkqnffr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdkrxmg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2syeukuoe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2btylqdip.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2donlpxuw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joggzghg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oohbmhff.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2znkoyfal.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzgicpv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdkhkvl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2skxqqrbf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzmodkm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsaipxm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfufkdr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2chdgzjmc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dahpbsch.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvmbyav.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpehlran.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qstblltm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlswghz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pebwoarp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aczvzuvh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnctzlq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2orjzapof.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rksjsceh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsggces.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzshdnqa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bviglcvh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkowwmgx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpgviwh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uojbtmyj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgxrpxq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpcryfs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxoyboy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubulzdmv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2clklodgq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2masfwcvb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrfifji.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2apaoqdef.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ytllkgyk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dopmqzev.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sduzlnwu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hyplphwy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xyayjqhj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bchrlcwr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyupmhgp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoypqao.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kjonmxwk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpydjux.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvjqmhb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sjghnrub.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rboxjjpn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqamybwm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2znzbkypo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhcgwjb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrvqasa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rplxgbmy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aowklarr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqstvmyg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dburiehc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2oyskdzsd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2efjsrykw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuolynv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uewerfkf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmkpvth.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqtufwn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dngoqexb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyivbpl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akbdvtad.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mfokqxxc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkjploc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoqvhkn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbxtxyd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfthmya.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuwcvjr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2brmhtqqh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzivrsx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rverujpu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdbbaam.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyszlniq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwvqlhb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtbnswv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cfupohfj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwubxwd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyjxdrb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnzqbes.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wctmitfq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcddseq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wougfevn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zuislrzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyopuyvs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2oezpisog.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvqurgn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cobvoqwt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ithvvqrg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pegiuubq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uifomxdq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2upxbxpgi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrorsjk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbotfkjg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhijhqq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeqwhmp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qidagvsm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alaycmaz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omqfxhnh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgghvac.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yoonkgmf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2piszewsb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gymyiwfy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfebzye.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjxenev.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kpltmtax.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxpnbto.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lxroxhfr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xinlgqhu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqlzwqe.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2egjquzyp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlxgglc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgyergy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkdhczm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xekhques.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxaaihe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjgrdjf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xiguoukd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vheezmzc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxshrqof.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eckkchjg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqaxgwg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwgziwq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inqpoobv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2olykbagg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwkfeqd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjcxuyl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2volrboka.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxnhmtj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzbyswq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijklrmfl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pggycmcv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2inynjljx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2leuutcbm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2edtwoxnb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avvzekcd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdkilaj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adftxbjq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2csmclhhs.html


<!-- 参考信息 -->