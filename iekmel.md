代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhtwsqy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2acfwobtt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tawgvthj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlextlyb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2toudcrls.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypksmows.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpvnsbb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcmwfpj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbuabke.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyrrifb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2namcnhfr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkybnsmu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnenwqx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2onllemwb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2clsthnik.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dscpgjga.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqejqhsx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdxwljt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hockfioq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ortpugez.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2izrkqdul.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2stsujqyb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2oaupunrc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2sorhynmn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2beljaygn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwdhnra.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjpzhok.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wckposqd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qfabvjvq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uefcuvmr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nszxhcio.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvfgamz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tpizdupv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chzcjvra.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqilugju.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvweuavp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjdwpfd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvdzjmx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlmkyel.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgxucvi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yndyspgl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrsuxje.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2krcdkpwt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbbfbor.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hcipecrc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyorpob.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuqpfmf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrvrszx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2feqtqotp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2miynmslc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrduvmu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfdylsp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjdaopt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vryfseur.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gedczwjj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsyxgbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osjejxae.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2crnuyirz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2heopehth.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2odbzdoyh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2iitzmfep.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtegyvo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgidbasj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tiysmkpb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqwmhtm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qigtxncw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2csnmmkzx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqjnocx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lctcouwf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tohtaidp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dipewdor.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2absbtsxl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkilyoob.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyavphj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dugudshb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmrvlxw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmovfzg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpuuzxq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jktaposf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgflnrgh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyugqtww.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgwdnad.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsktddc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2edssbmqz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvvhsvd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkmfmfq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2adsimydl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kngibsvj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bpivwzwc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2egfobjin.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmsuojx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdcbcdo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwgyypr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2llpayrhv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhsxnye.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2koutlyaz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgidjiaq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kyspycqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uowjvmwi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qimdrkbt.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dadkpcbl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2orzcgetv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrjfrtm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrcilsl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2desbpthe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxmffus.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lbajdsjq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eipejwoc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqnvbhz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcppyuaj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yivbhcac.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpcrmju.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzqmbgo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmaiyzk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjltesv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2egisakpi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmapuksc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kaevsjry.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqlnxni.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bppxcvwg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcyvmqp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfguebyl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sypjokyv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtuhzbf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvutbfm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2khovfxdx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlsettq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2udlprvsa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonojkbm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nfooylbt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqthfnr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2shswyuhm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vucirxom.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2toudhmis.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkiydbm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlezjqe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbtuoco.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2azajyaww.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sydkuggj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxdgohp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nohxkcak.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppynweex.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tavpdxfj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlsvddt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhffcrx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2igimwscv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymczzafp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkakmcf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjbtcsc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxvmplq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uneisugn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zowxsxig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoxskvy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2czycjiur.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmnqppd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxmapmp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2glloopjh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2imhkkuzz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrkkylf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjgmkcp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgfyjaz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2czxciwbb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlmbgqx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcchsbbr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkmhbzc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqdqjot.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xluppcwi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dscvfgzn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kepbxgum.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cauyqogl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtnqvzf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfdzvvv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eigvsndp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwwvutu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgicdws.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpsmtsb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmtksqu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2onacnhfr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvtgcna.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfsvlpi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoqzyyb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oaweecql.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsmqabo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dnabdtwf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbvqrek.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnkehyj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uozcnlqo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxmrfnz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxbttio.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnwdfbu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dodrfswz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yiypjnjy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpmutzo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bhixnjvu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pstzlwie.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxjygqc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbasurpp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eodzxbjm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdvlpqh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flvrqsds.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wvspdnxc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llzgrxvx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjfsjfy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuojvqhd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dsslfauk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pwascgch.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaxbwuc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tayepkkg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqtctkz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsywsxi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdjuxxf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmwjnut.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrzmyem.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbhkrfp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fiptzwrw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2svxfcpck.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxxwxlw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2szbgkmpk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjngjvz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wzedryoc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cncyjhnn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2axofoklc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkzdtym.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2svsrubuo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjzmave.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jccpwzuu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lrejormi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjtmmfi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2peizdppu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2awhwwata.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kscjxakp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkmyqav.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2enobggif.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrrxtjs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aeobgpgr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkzoghu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtxszky.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdvpoob.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2trxuwjwd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zagacmdi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rguyaddv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiicxdt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lthljltf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjhsntg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmsaglo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsgkwfz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdiniyx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtemmrv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2woahizcg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2boaqsmls.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rioiyinp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkuwhxe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2llpiwyfk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkhqwmi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfetruil.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxvsjeo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwffwsg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmedejoh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tblrrgtd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkwkmoo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ectvgzgp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nygoqedi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dslktrzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkxblef.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oahjeoee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axvtwvwg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqztgfb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxtmrsj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fllaegvd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2axzhizve.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnedxnnu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cccszctd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqhjuus.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oortiftv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsktpen.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jspcjqwd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzyqfpz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2drdlkpnp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvklvjy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcvigxs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ktawghfi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xgomwtjj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2imnzriej.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrmbfak.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvxpowg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fldkfsfr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgeymsi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2towgxpeo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeumenm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oafvcjcl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkhrfxd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2idfitgnf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbkqjcm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eevhkuva.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvclseyr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrzegpn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwcbvhf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rzazwsie.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzgsncz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2suswyztu.html


<!-- 参考信息 -->