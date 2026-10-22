代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ncprblpi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2iegwrcty.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwxpmjb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdwctky.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsxrqke.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkwejhj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mepmlpvk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vixrctlt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnkkuvm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2atipeonk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjtzmij.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxsrgey.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjvhpna.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyowsmy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxggngo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2shjrqjri.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yewhctrw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjopvey.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsiacvm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmhqict.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2snopysti.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyytglqe.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdgkvox.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ditvzpba.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pbljnewy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpymfhm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qhccituq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkzbowu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttctgzwa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxghqcs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoqiage.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmfiwpt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ytphoahg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwzutwm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvbixtj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfjpkpy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hpowwhbx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znoecrgr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skqymzoj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmzdrlo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qehiscuw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grsfpqmm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2smuzrwuo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sonxudpr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bvokvfwy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anbgjmxi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrcguqf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mueswyuc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpifhdr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xzapkljc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2utvcbbdb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdcxgil.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkwosmi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmjfyrj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2appwnwvd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgamimpf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrbmnnh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2guwqythj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfjkinl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vtplplff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsqpjvn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2umthsprm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaxjtta.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaplynn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wulozlpo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpeqzpy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvsbvlo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzprgjd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cbazomrt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmeturc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmuwmia.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mokwzkzb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmquixh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2akoykhab.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcfuzhy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqphyepo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxmqrah.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfyagqf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqehqois.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbceelm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfwrljl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kevidzdk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrrmlpc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyzzzjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgczcea.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gikzmsfc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaesmyfa.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdxgyhe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dijtfjrp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsndfmx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceumjkmj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2knecmveb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfvgxao.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqsisgb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsbbqta.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2opeshcvx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dosbhhpx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ogckuvgc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2trccjibh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pktalxaq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bygwvnrt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsjxisc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pneikwdl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfhmygb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdoltuf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2utpibzts.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuwtomd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzywgcco.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsywqar.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdrtvcp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoxdddd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2szrbtppj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcczyezi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsspwcgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfphaano.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwqaffe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyoqjvb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2faccoxfu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fawuojkx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwhykok.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eesqovyo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2shiaqola.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yilsdtca.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbvltuh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmydwpj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrucnst.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nclykmwg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqoaude.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdgieia.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2owicutgt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgpsivl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcyishl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itqqcmge.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gfidwtht.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcigkoj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxsieqs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbazigd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxjeqrt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsbcipk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2edizoney.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgblkie.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxaieag.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2atdlubdo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2suqfcdni.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ljglquid.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaokoyu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpelvvp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfbgiyp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hybjetke.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zimtpaug.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2silwitpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlkizyi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcyuiwk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlolwbff.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqclcalg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qophqpnb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrafnpjp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2whoawizc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2abjddeqo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eljxnsqb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ivualwva.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uhulkgvr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tggmddnu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fygrndgt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2axkiyhnk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwmrzam.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuubwcx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2egxjeaza.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxzywvs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2maewegtn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bpquztwc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cajqjxhw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mnckfxnt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iocpzfby.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxsytfw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfepotq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gakbwxmm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqsnkqe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibezmwio.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqzmzvz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nctoihmv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gocjfktk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gakbqpxe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhonyiu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsbbmck.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxkqfka.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjfqmmt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2atixxuqd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrjxoaj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yldtcruf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2osgsatvm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhsxucd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2svtlypqh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqqxkky.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhracel.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiuvrkz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcyqatq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iilvjzpe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xntbjkzd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiukcie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfahhts.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmbohnh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbxspya.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtflzmt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqgkafv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eprcdsbu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvwgrie.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhubyum.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqwzixh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ihayxers.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxjazcd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrclloob.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrikjyi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjpihqq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2weqppqft.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2evheeepn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2libvodut.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2victefzq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnplmgx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzllmyba.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkytwctm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqyxgaa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaudrxv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yxncaldo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avqillai.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kvikeddx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jycqwaei.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kvypbfgs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuhyxaq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdrghtb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjvtkkn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xovfswci.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uivezusi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aliszcgw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyehily.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2exoqlcbl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2chhbhbya.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hopwpeby.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvpryth.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmizmwq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbgwsrg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyijpmp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxzvphk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzlhzmv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2itvfjmwb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfbtwrs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2widkvgif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhldsslt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2chmqhnlw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcgahby.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2puzmnnly.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vidgapjw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uiufwvnk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgjoiqb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zhctfhwy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2luljwngu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpvrzwc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsnhpaw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpcszgh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwzfnpm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tagrikcr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hzownzyj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmuipih.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlskqdn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrclddg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfvrsdc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2asfcjfnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iklppqfs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uieggick.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztifbzdu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyeanps.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2onuxyqiq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzngvpy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfotpcb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkveleq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kubgwmmb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqdhtee.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpgjjjo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hywydfdx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckizjfub.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qalrdjuk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2quibnoge.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vivsajds.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xicfcndv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjrvpyj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwsysot.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vboyliee.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shzodipg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtlwwuw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbwhxbm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwtigat.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdcmocz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2essiiglm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwxsysm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odujksbi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qupklusm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iasdhoju.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpcgqre.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrfxwmq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bokmxxth.html


<!-- 参考信息 -->