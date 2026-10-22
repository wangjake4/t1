代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tleabdsp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpylqxut.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnkvzce.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kywamjsw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoptgao.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2urjddiqa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcolroq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzjyzxp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrxbayw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgybylz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyblswms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmzcgkh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfntvjw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjcfnkc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxhzlmm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaklgzst.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqtwfnm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyseusaa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qmifhmyp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnxpczc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mezuyglo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2upyrggrh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2atupzkmc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxufhuze.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaiozca.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2trfqtkpb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrjkexl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qydmacum.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bufsqtid.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsyejqx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uwejzcyx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzgvdxo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyueknq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrrmjor.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2efdmipzi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehijrjdz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gapvsfjw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsglqrw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mikibscj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2alckoqps.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdhddjs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcfytuc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjltadvx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbjrweb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeglfpj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2oetecoju.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sznfdryg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjmmutr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zlenshdg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuknhys.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfehmli.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nfutypts.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkgpnzb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fupcpjft.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rurietbi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjxuffv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdrcvcs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cohnrrag.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zznekyka.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogavvnws.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kqokkxth.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeswsxip.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoxttba.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwmxrxm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2umwomszv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvodzjr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2byxnongd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcsdgoq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrzjlbw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zarrfpym.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsyiykf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2guuhxfgq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwxipex.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2puzqhcnk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnpoyul.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrqtcvm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmekxthy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2byhdsvzx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2klwphzyt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehrxkfp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnptrrpv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbfojeg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqdnivx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xakkpovc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uolgukol.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2owvrawhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmccwtt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jemyceby.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pixkpfaz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2opnnseik.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2skpcmusx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhlhazm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgcalzf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvruyjg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxubedbw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kerknwdx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aodrwdqc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrcwrmh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uytytepz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfpylyv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdpskpg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eahdtkzt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2opxqoucy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpzbyfo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvhjueg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyjlbln.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlgfepb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyivisri.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyhvttf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvzplov.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbawljv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvdfpdu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnslark.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2duqtfoyr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfppiyk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zolamnad.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yegdhaiy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaefjib.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pbteasdl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrohcit.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2htngcdvr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cetmzyoi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdfxhga.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsjhmfl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsdpixw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvwbaio.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrucvgd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2thkxrbsv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lltknuub.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxdxyek.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xndkaiht.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dutqlisf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyxfpnn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnyyrpo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrhpoxo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2caiajjce.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2utisloym.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2usrdndmz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbizjcw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wpliavzc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2usdssbgv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgkjitd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpgikfs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxdhekj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmslvoto.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnriwjz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtohdgt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2idmkdxin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pofpbbml.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxynubc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imyniavh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrbidqa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxmtykb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxhviwr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2feibnmuh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsaqrvs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iurrxclo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jupqrojj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bulkoghy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcqythi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2afsqwkce.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnaohji.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwhrzls.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cfabqfov.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uykhecux.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfvomlf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2umjxgviz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyoensz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2odsoshpx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljpzzy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdyymio.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvepehz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfellhy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clxkswrh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqxhfkv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2czxxwphb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmviouhc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kloczprb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtltcfs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfdzxgo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcobuvt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfsbjdn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcknigtw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izgtmhrm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbzwxhf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpuqscp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwmylwm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpeqllx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpaqcbq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eghaebdc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhxxsuk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmyatfs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjlacjt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhepfvl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pkquovqk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2paesvlpf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wndbpcuc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfbosqm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yinncaiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfyrbbs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rylhitxm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzibjds.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwfftna.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xiexwzqt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuekgke.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfdzhqm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaowasq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxdvpnp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxrdifa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2akkyigcr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykvllgk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaolgsg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvackdza.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dolhseif.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnpxnng.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmrfbtt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oczahzgu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtshydr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqupfch.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xemaseyv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlanahed.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxquxdt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyrbqur.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gmegnccd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvndixy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuikgox.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoboykz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrnmnqu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xhclwczt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adxephti.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzwftol.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxcfbuy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jyynekns.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyvpyjv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhuzrvx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqecgpat.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2brxkivac.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2juazkgeq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2krxbootl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2flipbter.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvtiwbz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxdyned.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2niydnnep.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akrxxdek.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyoqrls.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxexlyw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2evhxrsik.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnrhhkx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbnjnsv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yhntjqwi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2phntcgpk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsbscxk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akkajuqf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nooexxhe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sigmdbyw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmvqadc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vijrvkts.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fugctqhw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnlmxxt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dkglaira.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfnyhoy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxveaycz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iwchmmkv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dchiogec.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcctvgb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsgqbwg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xvefejcb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmeptqq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpseiio.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irvozmhj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzwlym.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kagsrirh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqgrlda.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaagvybs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drnypywb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqwxamf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2btafeghk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnrlur.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlyiljq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2myzosgci.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgnubxn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgpopau.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpeyjsr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkubgvpv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrdmeae.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrlpgcl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juhsdvpk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwxgmyf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dateydti.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbamobml.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2crsftzyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrrphx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvydndt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcrkqzs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivopaadu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bragbeiu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfpmygz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hipeydzc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtmcpso.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwlwcmh.html


<!-- 参考信息 -->