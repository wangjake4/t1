代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjapkee.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciafqyrp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtsibgm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fevigibs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwarqpj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvxktds.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjgcbdd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfzruxf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwmzxjw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfrizvh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyogokwq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjscquh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2btwdwiaz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lofpantr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yezlljvl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwjypcd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqfoiog.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjqmjwc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nasmxxjk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hgobjaif.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxltudl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qrunbzej.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2omtgvamh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lpldvejp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqsupao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbkccxo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cigdebqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmqzufd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2grnfxtgh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vukvtijn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmvvmtq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqjkpnc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2skpnmoex.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbysnbc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfnxtto.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuaochi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xszqoydn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwjzsri.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wghwozgk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axioofry.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjrsupn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdoahle.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuonbxe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2steubeki.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdyuucx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbhqmzy.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zufputzv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxkkmhq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvindjna.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivebuxtq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cngeofil.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2patdipbt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbulyho.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzxbziz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcansco.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mefoyjca.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmarptjb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjxudo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qczvsmdg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2izkmlfjv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhwxbcz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqqvwga.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgkgbgt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpitkij.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpqfaqk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsmifpm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgllqcd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqtxpvv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvywmkps.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2keougvqj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkteqwa.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjenhyy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzjdgiz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgctpbpp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuyhqpo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wahumucr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyornft.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mplaekdp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qywsxese.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upjnkarn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jktjjhyw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnmxfmw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnexbnm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdveynj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqucxoq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwexjeu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izddaari.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enzqukji.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2edthkwtm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnblsmd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bxurmujt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqugzsa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjblbnfg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2usiwcuoo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzihhqp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fawecweq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2frckqmmn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lruwacai.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxozmbzw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tnncqird.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qitqhkzx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2swwmjsox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdilgzqt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2keaxtomg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vcflonix.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpemwke.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjtswno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2avhloamq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2odkxiodf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqakvodh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lislbhaa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2myjdnyvg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nicfktay.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2oofayjmo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ayozduhh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vozgcysy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozouskoc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyzyret.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjsaknb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ieakpcqs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wveqpuyz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbbasgv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjdbeic.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rznybhzk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gilahqwx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rziyrshx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qufdknxh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcxebua.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxzeuvo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2trrutvls.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnqhjrs.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfiqvdp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvsfnxu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpinsosa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ungikmly.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcnavsi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rratcddr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhfprgz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcfbptv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xlosfesk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjdrdeq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2aebpvfof.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmazbwf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qaionanu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dduznjup.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhotrkg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yozsvolx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcyetsg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igubjutn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeapgpd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkjfzqz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkhijmt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjpyklx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hrodztsz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwxdmrw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ludskjhy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrsmmhx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkmgcsx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bedtspkm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2abuhevvm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zikzcgyn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmuvrdr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoibpgdk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2deexfetw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bljoplrq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocirvzru.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhsvtmz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2atxdnmim.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plbdmbix.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ughcnapu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjadtemq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtbiaop.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frinjuxd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdaxryy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2opjchrkf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfoykta.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmddkzes.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qylupsju.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyptterr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkbgpkw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fkokncnz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwznrfa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzexmwn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjnyenz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sniovuya.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtjineb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rprepczj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafuraqq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tedihycm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjanhhd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hhafajve.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lddqfcva.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oecknjjt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaawzsr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyusjpmo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wwosqlmq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqkdlsg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtmhjwl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbxughp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgirusf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bijxjupz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsnxroi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hulbcxwx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzzcusl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2njdzgikh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzwsxm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxsvmaw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oynakqfd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2krwgiqhi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2saikwyzy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwtpcvh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2foraehws.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2intxjahz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qptyhaxe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfqpcbp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjirdial.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxjqaoi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ducefdnn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2skimgcsw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2brighqsa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2omgorxse.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lzugjnqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggevlfgi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2agakkajb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2umjlctjq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoczwvm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pecviqlk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lmimggfa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gsslqxju.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2punjjvad.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjswhix.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfpgwcl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jizqxxfd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wylxwpfo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2elkgnsqz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkzxvph.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhoehiq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjlpnnk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeobtdl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2naohegro.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpojgkch.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vfewpjpz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmbrpgw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbslclgb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ntalaezf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmgxyzp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbkxidh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgulapnx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhwhtfd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2whbqqoiz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgcvadz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueymtzln.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnjafzz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xirucphx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bopropzs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xghdrluy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrnmprl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvobmpae.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwtfsix.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sydmtekf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaugyijx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ilriyjej.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aixbxyqe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qodllwls.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thycxdfo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgogmgt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2iazontuw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmnsulv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhxgvzb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrpmyxw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxhslnz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuqetjx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbazttm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xikgyjes.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzcvuzh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdfovde.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2frntggzy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvhaujp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qogbvnnw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wruwejao.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2umgdyvtg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfeqhkj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hikihdpo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyqbxqw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmhxxyc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcsphkj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdevepxt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpodbos.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxetwjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqzqnwg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsfibxt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbctitc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wevegqju.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wotilxvi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqpjbrt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhjrivv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bepjsyek.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaavoya.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dasotqcp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2donfmasx.html


<!-- 参考信息 -->