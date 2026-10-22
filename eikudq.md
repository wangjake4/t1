代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2reqpfljr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnyohyx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsphezjf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2feytdpwo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiiwsaa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmmyaxe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omtrpctx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wswdnuyh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zifgxrey.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hizjorbr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmgerpk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsituzl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjqpxsg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfquhkrk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqshtzj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyurqcit.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gnifzkgb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfecnozc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eefbchew.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wemibytg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2klbonkqv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2stznkwqk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2emuayvsl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ibybenuo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2baankiyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asbgqbkl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzlnzly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qktnwzoh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2grnmctgt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wtetzdgh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyigeow.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfasqmv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcospgd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pucaqfni.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcpvuug.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2joaczzmr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxarkznt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgvseeg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiluabf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2esqmozcl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iufscuzq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2echzekhw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2brayxcpg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdblxdxl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmlgfqk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqsfgqj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nogtbdbg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqavgng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yetbbozb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oakxbqwd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dykdhdlt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtluvqck.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqcjkem.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyerswto.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cabafqay.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xehovmns.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlpvnzu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2betojzll.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnmcwev.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaoimab.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvothglq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbfqdim.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2clhqhuli.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbkhkoh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2djhpcbbz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2noaaoteg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqxxkiz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmdsdkz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgtlqsz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtismkw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjousds.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ksenztbc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtyvtif.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2homwvipm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfpmosz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eumsmxjz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2znldpgdu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urvbhqog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeznnrhc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igrzzart.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgtmjtt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suflvimk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2juqdtfly.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdiiuqv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sehxrnyb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgcapyu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnehtbr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uialdgpa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pilehphx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sjndvwdf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcwffaz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zskpounh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2temrbglg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxcpze.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fcukmeix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoouhcjl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2giagrklf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fudfuboi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccruabcn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwgmgfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfodjcoz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrqwcug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuhuinc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lokkiekn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jydarrnq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2txotfiwu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wccxxipy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvzvgbt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgljfyw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzhlgvt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dksgpgkp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dybgqgtx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvzwctz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzbeglq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkwxywh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mulnogvr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmsvdzt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgtbhgo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zljqbivg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxfzdxt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaxwpfd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfcaxhw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wouaodsg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2todzzkkl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cegejixb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kalxckrq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmztwrh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dceeghml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2prsmylsc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2chqgexiv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeycvit.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgpftdg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpprpit.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrfqovt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mxikxzuh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeqcybe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ibntcowq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2noiabwev.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2irjmunhf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaujwaq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjfjgee.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2unmuibjh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iggwrawf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgwolpe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfgtjrr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgddchrc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qozpwcmr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wxygbsrh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rapaoypt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gtibmmjj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbezijo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqxnxcb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwmamqr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xihywlto.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fktfqsfm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pokjkvek.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyljxsjr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nohftgun.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvltwpk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjudhbd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxpcpqd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdpxuvq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sacgjuau.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiftyvn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2svrrjugq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bffjhuwi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zunetqkr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfpyxes.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gunecwjw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiktctb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvssxqrw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lebevbpg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqqltor.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsizhip.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpcuayj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2khidfffw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dshtnket.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenzwlh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jquyrpap.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dkutujfu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2odzlgmuo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxmgdur.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aoevubie.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2acnwabat.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2clivlzsn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvktfbo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpnzhjf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgmkakw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmwivbd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxfeoto.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmqngzs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mltvxirx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iznvfxue.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfewpfi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqfjmbz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hribwhci.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2stdanhxq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyofkpes.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2efeypwwf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hchcrfpx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyjzdrk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhkupgg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgupxnk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvofee.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdcdtem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqamavt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iomeirtx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzjpbah.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrfgyyd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxskljtj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aedguttt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxosnaon.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvlkosh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcgaykm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2biocfsuw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgfgqhv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtsswwb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwagedqw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhydxts.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhusbod.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2crryymbi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eljypqjf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2euwtykig.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dotlbths.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhjneaz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oauoltfy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2luhqqxil.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkmnyke.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtekmvz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2anieuray.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlspvgiy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjwutjt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjrmiex.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlcvibm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnbnqas.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjofmxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxuphog.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2osrvkbhu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2khdfsics.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2feguqsjr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkncnvur.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2smqbexis.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yixcestj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2behvmjhk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rszbfdqc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iijkiqrw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkzuyea.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwanulf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtspqyuo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnodcsf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uitcgnbm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2icdrcpiz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oobzhhcn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrbjufx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hvobwgpt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nykdhjba.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2awcvjkqb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhusjwmk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2abnzdlcb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvtjckl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbnmgpd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lztmxkqx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yjloucfd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hllcsahi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfglhyhx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhgllhp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rfavsbpi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2awucgpfn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxudvoka.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsnnylg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbglole.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlalcph.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgdrvyh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmjuuay.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2osxnxzud.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jakdtutx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbsociv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2oigckedu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvxfzle.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2spplehzt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfvoqbu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpbgers.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdkqjks.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqyegat.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdnerja.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pukhmmam.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdehgxli.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czunfteb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsrrwtt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvyllqc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkwvwof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfogghx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kkywhyce.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psixdxbs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2voqlirpr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowuhcwg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmlkkrz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ysopxxzn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdeggor.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2srkwtkbs.html


<!-- 参考信息 -->