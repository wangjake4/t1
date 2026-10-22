代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypojmwtg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2szpicttj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbtgclx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhntqvmt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyxniow.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmluuwyr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwckfra.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjqyvrn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmtddbe.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gphqmgab.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mneyvmlx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdeqxsc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zljbigex.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bcswcmoz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgxcajm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkukdlm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfotvhbs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnopmbn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zctmqxzi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdxmgfq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgxwjno.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfufckdx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbifffu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkprsnzq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfpedzf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krgvhqew.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrlvoek.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwtalpw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2abbyseqj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfzffyq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kuskrdde.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uwehizle.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzbdddo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vgliusie.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnitpmvi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sygqgisf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsrvafi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hofieare.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uynleffx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oursabgf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbalnwix.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2edwsrdof.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbqvkhi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jevechwl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2saukomcu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jaydwsrb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvezpfn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rafgypzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mncnxqha.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnssrkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vugvxzvw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2obfdzlet.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpgkbcg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrynwde.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sumisndu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyrbcqd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fpboabuh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2frhvqhno.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjbbjsu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjfsygr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbybexvo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wiznvxwe.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2shqxumct.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwxehym.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkbpdaq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiaodfq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyiqgwy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxctfxg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oubvcqur.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwbumbi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqjnzfz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwyrpxi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2acudxjwp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2udqxrzhv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfcozif.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjexduc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2egevskkp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyecxek.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2btlnlgal.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2apzynqhy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxkdtln.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zavakjgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeivrom.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxkpdzy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnhkkci.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxctipm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfkbzph.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqdohpq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfxoqms.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2meyhehpo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgibczgn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aouoaxmr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhccsbik.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgmgigx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsfqnum.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoiwonl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqravks.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpphwfr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jssvggtz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrhzime.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmanwvp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsnmmhz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udmjcrqe.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtsephf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kntjhjes.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuetlls.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnmlyen.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yckalhzm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruofrxbw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdcjiui.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoemnuk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vutvlapg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xkshvmos.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2syluwgut.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjkhlgp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjpzepi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qugffmvf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzjvbit.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bslycltr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2roqnymxv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzdglwe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2czdkuqsf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpezzojm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2njszempj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgaymzx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2glxczkbb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyeirie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2utxqakyk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiegxdt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxpnmss.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2noxnnled.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2isfddcpx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2emcwrxty.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgogdemr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2plhnlzya.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhpxcja.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xbosdafr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmyggdw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ryorpdtk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxkjyex.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lblpvlsb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwdnwgn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjcndgs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmdfzxj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xenadmcd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoxfhdl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2atnnngvy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mqikigsk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mswepcda.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xabobnuv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxhzdul.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2htrieosn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fqksuadw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyqkbsh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vyitvyxc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2agxrknsi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpenyjc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbynytb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkevwnmw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeuhwtp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2knanrilj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pamgepoj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjspsqrt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2luwqhwzf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vemjzvtv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmwcjnt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rycrlcra.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2osvewuzr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cregvuya.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2glnvchqq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ujewmrle.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vskvuabv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qluulerc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2scverfhc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wptbzulp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2swhkrbld.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dogcwvkm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpupqmn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjiwmtu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqieeedo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmayanlb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbmisyp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2seoxazln.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qswpdvgo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfwohez.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xskpfexz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grhffqti.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiuzbos.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkamkwni.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxeslvk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqzosxr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwegxvux.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcjtfsp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfbztdw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeeoemz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeekvxkr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxbyzlt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bjomnjjn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2umocujdb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxryzrpm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ryujemkk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kctvuqfq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ntylzfmw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrmhtyo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2giwmicdo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dawphcaa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2reggppez.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2biebtifw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyhtaua.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2euujjssb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zujwfwur.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lefujxiv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbjnvgy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2aprslofg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yibbzfhe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lhocyebc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsvlebw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sadyonao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmpnbww.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2toxlmtsa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxipeceg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2numsvdfv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxfoxab.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsqoysp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rlktjohh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeabatwf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iifyjzof.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtmtutq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zylwqrig.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zaldqnmp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnxnjjw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dzigpbvh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dljjvxqa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tabvkavm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmedjeci.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhalrqq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxotzomj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrinbgm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsdddkz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyoupoi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hsylrzpt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ietoybpl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfcxwgh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eydgzjuk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vogsyvss.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ksorwfhg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdysxop.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fosuutbi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pktuvdns.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2axruvvpz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyixlie.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zdquzear.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fltoljvz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cariukhd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2inneradb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhjtjnt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rznlyqcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jynmzlti.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuxgloj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2auumwxff.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyvicwq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsbvsua.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iskcdwpi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aicggmro.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoaxyig.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqlxhli.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbllquxg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnqxhyx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiefnbw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfyjovw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xorvszmk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlgyrgt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2keikvwqz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzgvxtg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2akdgkypv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsqzigl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpeidom.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hzejswkb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qtopbgmk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2frhiiett.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcioyte.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rruokzdg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaczvtn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2owjmytcw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaxcsvq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kaljxmei.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpujrdu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yeecgzjh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeyvgfu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2keaaeiji.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xolnejxg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsalaqq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsplpjhx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmrbeze.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpvbsgr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiexdbiu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoqplob.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfchzlp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqoeoqn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzagwzx.html


<!-- 参考信息 -->