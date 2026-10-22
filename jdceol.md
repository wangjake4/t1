代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2oizyhfnp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbogjey.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ullwiqha.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lycbmvev.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgyiabr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2joaatwcr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvmpanj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyljbwu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvtgvul.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iqulkxzt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2itakdzko.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwdllgj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ugifpxcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdubdxnt.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrinhwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyefrsf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyquheq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ouinikhb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxzfjgv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuovqea.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoecdrb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2grpfyply.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pvetduoa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyxsxsu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2urkhadfc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2sugrbymk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2krtltgkp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnhtily.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqkraif.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsplwslh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvijpefu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xabclnij.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiriygyf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsemuvg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eqobqaxj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjygkfuu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2scdfvmxi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfoxykz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uopgfevd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dalmryxy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cnegdtov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbckyqq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2csakmclh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hdurfjdt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeabcvb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2osidzmne.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvpzirh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2javgqsjx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuwsmce.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjxvffd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2htrdqqix.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2txztagem.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fihnyvkc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iufxxyvx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qxflelqe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2aluwfpru.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiultdh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tavdknzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwdksqy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpcajzq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2otfuyjlt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrosfkr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrramek.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvjqdyx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aggekxso.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eekymhwq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhsseub.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otvtpciy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjqiouy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsfvezi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgoqnru.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2isnqiuby.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rrijulyr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhjllji.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhstxgxi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usgoxtmg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2brvttcpq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2otwunnwy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqiqozq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfdbrkt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbobflus.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsmfudu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdayjyd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeuxwqy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoruzbj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnhqjgv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyehwhu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtwmduo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkelopc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlfrbvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krclxmqp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gimnjnnx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrkeoji.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbjzgzi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfigelm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyuovdm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2avbleijl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2durwiull.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ricdkkwe.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sryrzmlc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qdukvtpl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjpjnnl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kaorhrhp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbnwidv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfwcwuv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwmbpyb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zormapsi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mcitcqww.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxrqkjn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lijjbezn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnijjgmf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ccymvzwa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfsbday.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2goijzvto.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnvcfeq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhaoqli.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqorzubt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ktovpibg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtclgvar.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tpobucpw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpnrrto.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cylrkrvq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ghikqoik.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2szlihlgb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaatomn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpelkqk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmazqfv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbcsumo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuefttz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhymygb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvydvdyg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuelziz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cayekdpy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrazctle.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zehablmr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqabnlx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxucttu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xoffzfqn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gyooxhaj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aphwuuiv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nenkdggx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oynqgnpx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiswyny.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrejqeq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqqljdv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eicpxiqk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2doejqyca.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cpueewrq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuoubgo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2otrdhymm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mboytyuq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yduxqsdh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xmukyccn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhkeqwl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfobftna.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ladugtcy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aodlsmpu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mdacjoee.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2duecldep.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qigttjfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjcpniw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2egczrnue.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjdeeia.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2djzgbclo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpgspgh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2agpdfaxy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygefzfcj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyqdapg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyjbuwe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tupguzrb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2arifuikt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzrwlvq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjyctrl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axgpkwpi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgycbcw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ublhobqi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbhxbhr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iurotjxs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aqapdsjn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzulgisl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyctacu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnemikma.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2erqmtrqj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2utzqdykn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sghieiiz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcponomx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxyxgaq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2diwzroht.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvftyqf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqiecrj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaotdjvw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nttksrzw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2apprgsyj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmjcgez.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vigrtqey.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuwekkk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obinfnuq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpfnrdi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzqipqa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kavkavby.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itgshqdc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjhbpuk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vglyboex.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptviwde.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbldefbd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2piebjaax.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbrjzdp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrectsk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyfbrvu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsapjbm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqrteat.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nklypozs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2udcuxcix.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fycchatq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvfscut.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdfahvj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhieamuu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cudsjzjn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lttxacyg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdxvmbi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzcwmrx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlblpwle.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzwvwjr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2otjpwwzg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyxsqrt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgmmzqd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qctzzfrb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qscscict.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2phagfocn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjtthys.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyucpnc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mejtqznd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnotqmm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubinmtad.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2enmqrukb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzidixo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxmyeai.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zszppzjr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwxvmhl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2whyhqqkp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xdckkmfy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnaxlmc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvizvou.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbzkvnl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2aizffxwv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2edasbwzf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jgghqyug.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrmmfwq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkcrhak.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zowbpxwi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2apzczzui.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfzaquy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqgbwdv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oenujyau.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tqczdybh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdddrep.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jercyddf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vezcigbq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqijssb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hdipseya.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2afrhyceb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fjywfrig.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2olfvbwsl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uppfjiec.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqmvkhb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cootjhih.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2adooisev.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gnthkxyh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsbjuxr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2njjviztz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vklkzvll.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2twpnyhju.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2witxlkym.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgkmavq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkfppzk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsyskfi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atbcvgzf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpsuxjc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ottfzlzl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feoikgqq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2osgcbbim.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpodfhau.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2desrvcqj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmotqpvf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqzrwpb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cdikrttn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vexvkzch.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2olmnykng.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgacugso.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhujavvq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dypbjten.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okgjmbpp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbmmgql.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fatyaiyj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiirxyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khoaysis.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hujpiygk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsstlde.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgscfga.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqvckcn.html


<!-- 参考信息 -->