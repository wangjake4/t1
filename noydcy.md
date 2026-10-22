代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jadlfedl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpjnzjq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2okfxrfjp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkncmms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lilwmlkg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubtodke.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdnzufg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eecvvqus.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsshvrq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2madgrhav.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdswfwr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxgxfhg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2retknrnb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2clcdxoei.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2milagxal.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiowgdp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2iudnptwy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpwuqgs.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2izfswyai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnwurou.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2asiyikeq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiadqbc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvedjxf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkfgjth.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoatowu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrijexo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2azljdoez.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzblsvf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2miapasif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omflpmmp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2feycowog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yicdjvlh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnupqhg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxfsuwo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yscdlwki.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcnhihd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxgpnii.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xekgnoja.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfzwbxe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2esdsjacs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnowhlda.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2djipntlo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpytrsc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppttkwxg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsksyht.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzzbtyy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqoeyqj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpasohj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhwekaj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2aebdheap.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spfoljly.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiclmsng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhflvqiv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjleqpch.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vltowpnh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlccpshj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxilianc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2quwojluy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zppvfhsz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eifzqzrl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bowfqmub.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtmqzm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2imcjuoab.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lknhlxdd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2heyygosk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbdpolu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2incdeggf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2btkvsukm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uojygszw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nylughqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqmajj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmvzvli.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvuheol.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdgpqt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2imgrcsny.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttowanky.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuoxzqw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aibtvgpu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwmuuej.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xucywwqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jinwwixn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tppumiqi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hypbxrvr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aifeskwa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyulgzl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdopwai.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeopgai.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2edvsrsyf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2haxairjo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2frdlofxx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaunmeg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcflfrjg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jixooejg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvkdkbl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mclpzzgj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmhduqn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cocsugpc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkblrsqx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2phmrsokd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgnupve.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjqarke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwyvcta.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjungxgp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cexoetyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vutbqjoy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbxgjfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuduytiy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxrhemf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kpexlkgs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cljfmtny.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sczhdqgn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vztitoca.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfnkdxu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxuimqw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2invzvcff.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2evvfwpmk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqcojjy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyatdbk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkdggcp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgkyxho.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wosdwlxy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgszhsxd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncahacom.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqjkwby.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpnsxjs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqynvjb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dldxupvr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ervhrahw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtidzufg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujddoxki.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwgubdt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lawvlvqa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaztxya.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hiskaqam.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioawwhsn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gklavaod.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tofsteyq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vedynkta.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ossvzxsu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sgedvtpo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpugkct.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdtqnkb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bprndktf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nuauhyit.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrmxgof.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlqpvtw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbwwcgt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoavcgy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epfzwopw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2edgvgeae.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpzffuk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvygjpf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyelqdo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdnqhoq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtrpegi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tyswahzn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrkympd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpzfzjy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2azxupoqq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yqakmoyf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjyfqqi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wedunojq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2thfrnuji.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yftugotc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlslmrj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnytpba.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpmyqlc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zedyzclo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhydgjn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2esigfuqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nilyveke.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoqzrap.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tizavjii.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2udixgvhi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcjuggk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwjavhl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rderkxsj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xufvafxj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrklrmrd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zboykdpz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bttauika.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqugdmm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2saayowku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpicuoj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kbejzglt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uarpdvmw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eloekdqh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpbydwc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsaoikq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzikezy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgratlnw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwpipop.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrxswat.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shppzcyc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsjximf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdqevxt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcpamnb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aznrqxkc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rysyisdv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zypxiann.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2teqmnxxq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rygiloxt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nksfpdbd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxfohtg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2imrhfubq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dxghfmqb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtgjzll.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fddcfwun.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ediigtvx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oymbkjxp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tnumbgoe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwavwwii.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uiukvpkm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ordcikgr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zkczpvia.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmpxvro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpujjkr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsctlfoo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeglfgc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmefhazj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgqlcdv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cchcjqci.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijewpuvv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2djgewbxf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2besbccnp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zbntrgvb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpocrlk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdqygfl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwltjgxg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2itcseezz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmtyodx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjwkclg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzshlts.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgelcts.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2luskvwxd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeoqzen.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkulzkvp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmbhets.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuccflw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnvbexv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duixwgsr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjjyqnd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2megevkib.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsgrvfr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elpfygnm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2drslovil.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzziyvx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsniinl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bsctxgue.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwfmntl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sspjglhz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjtyzkj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wapkpnkp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ewztkchm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2alrylomk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtngpxk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiqalnw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qchqzywk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwcjwjm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2afaxwujp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dirvpfzd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2httcsrcw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oysgwxae.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sulluahd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjivfvc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoyhsjr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kntmnwuw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2frrgdrkg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmfvork.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkqyhxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmpkjyj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zukylngz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khcvifzv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fhninriv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpihoat.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnmddwj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzzalne.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wycagnus.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdroudo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uuciinex.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2enfndckc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhetdbr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2loraoqtv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2utlzhowg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2whhtampc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdvmmyo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcahaub.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fugltyao.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ufziemkr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgpggxi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvnzike.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2necppocj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbenycs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcliehyn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlrsyjr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjwofei.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzczatz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcsisdz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rofvfuwp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsrinor.html


<!-- 参考信息 -->