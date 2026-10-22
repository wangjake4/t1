代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rihliwdw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgdhjpt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjdijos.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxywhqqj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjuzmvd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2axqtwgsu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqntjyr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ihawsdiz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qqckwmaw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyisbve.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jeabohmj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoguoti.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wpargggt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tikccexh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbrgqhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ausqwnut.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcmkfcp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yewdhxgf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrxbyih.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mddzgpvz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypezwmzo.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyukfgyg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xorqgxmj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyfmmgs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dclbclcg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gobpmcdm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwtscby.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2auqmkcde.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yswehguj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2grgnyjzb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwouylrm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkrsfxh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iautmrue.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2brqtyein.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcrnslz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ditcytly.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwqmtbr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sywzhflg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtfefou.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeacphf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2coiinupd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujraidbn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wryejvra.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcupuec.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2viptubke.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrtasch.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pkimlobi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2biyqfgxl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqarxlvh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2oldpctcz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnuereg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tifijmxa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bnakfexg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vzubttto.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrnclps.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2znzgeauc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axcmmhyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2umhzyzur.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdrcauc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2iykoyybi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2spnfrxag.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbthvzkw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqpuifl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcwqwrt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kudfjjtn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpicdqc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyuskjv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieraevrf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpzhalj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhubgck.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kgofnxik.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyohunb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cazhkmpr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eryzmmhe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cssstfkk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiqsacj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ljweoobg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sprjgmll.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2daaijevx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcnzxud.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2olkdtzvb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mocmspuh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nckyzubi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdatnmfj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyogtfkw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqiouzs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhfidqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2swccibuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wivuysru.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkisgkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xueiteyq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpqfbfj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2keuweihz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kjypxbsu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjibskov.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkvqfta.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlhqwjf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlanvyua.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqxennk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2odluietn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fctvbeji.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbxcfoo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ticnwpwr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mclhaqzy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqcgeun.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfoekqj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxitlpt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lchmshnd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qczwgwbs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfpopse.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbyqiqu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjnlngz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjjkqnz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qksazbpx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzmnrkh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjeqtvq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eufbgvlp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dabgqvrx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiogoaeo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2odwmotrv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tumpzrpz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqrvqkx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjfyohi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pooyeutw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhriwxm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjwltio.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2btvwukuo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjmrtrq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlhlwhp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcubuju.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2czkwoiws.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2whgoymlk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2biboiaqt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdpakyo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxbskjm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ddutoumi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwysduuy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2weqyvupf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2azodzsqy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2itekrvqs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwalpuv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bflezfup.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpukihck.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvznnhom.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhqpwcy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsxswsz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwemjqw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zknpwera.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2exezrbbk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbygluj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiqrzgz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2odpgkops.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2duebqjtr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnajtzh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mivpkbku.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwyzevk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqlhovy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2elfvcnuo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gheaxkme.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oscdzlef.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2demedukd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwmvmxx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldurdfek.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ipljbcma.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfbemnr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vucpemrj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2estnnygg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoqldxq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uuavwnin.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gucbslxa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxizluv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxpovzv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcjumss.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgxxqoh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqoqrnm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgrtmhq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhctanyk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqbnjpp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2keumwutt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzholxj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2udwabqge.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqufsck.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mihtvwpj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zlywmzsm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvcpnyn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxfnsdn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcpuncb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfdhfys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kboiisso.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2irrjwjjl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2crdxeksi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gtztutsh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cexwinzb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oywrzvlf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvymawd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yforjins.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqalhun.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpvaqqv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2enddqckb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjunfph.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qehscmxv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhgqltb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efviogrc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2exfwevfj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlsawxl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycelssyr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzijwrj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rknvybuj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdywsmwj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2stozaojs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xucsryph.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xejwmdei.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmmcpur.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wadljtkb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiufyilc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2opqjgotc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gicvmrgk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbtjnxq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpltgfyl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2umqowntw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eepqzxnc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcisskc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuneqoy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbicjxg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeuerph.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfdqcit.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcawgwzc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tvirmfjl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmlsywk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qsftudqz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgtqlqp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzkbewh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tzguxzqg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nofioxep.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwcxkmk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclnplek.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aptpytum.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nznniede.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2otalywao.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcswepih.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2shohybiw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfirozq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tshmwrja.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbagvgvg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uwstlbsl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqimptuh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2glcqiszi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjkjpsh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ootegewr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uscnnqtv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kptxywfi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzrbisp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iymcdkld.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpclkuv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqnaunc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mbivwqgf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gotmtgcq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lctgxjzs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cihrxeis.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ohddapor.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgpxlvn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2swowdztg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsublqjt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2urrotuyl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgacrlz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmtsjhl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2thgbcmha.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2heyqboah.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2afbwpmka.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmsiouo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2geuitpzc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2csxpnpvb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wolofupb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkgiwyt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtwzxrz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mosqetcy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqhxmvw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpmdwgz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2womacnxj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brslbeoe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uovqopld.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtcwccf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdppeps.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbpntjz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2adjlysjp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpzfpur.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmenheuz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2thcfpgjx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnaimih.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjtnxvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gngayujp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2unccnypq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgznkpc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmrraob.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnabqviq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbdsxja.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kffvvhie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbotvish.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbgxbbk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkjdzce.html


<!-- 参考信息 -->