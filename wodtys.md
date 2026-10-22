代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnktwmh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rchhvmuv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqffwrk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzicxtm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvhkrnt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ummaalzf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obiwnmek.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnicweh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hekomgfy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wugzoqyn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2joeibtgd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqdczht.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nyydkjez.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwebcmy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shyywvou.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uorqccgz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuessav.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hotxczla.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykggwcaz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzbrpte.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgguhrc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qayatedr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhenixbh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mumboiha.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hawvljzq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjzydod.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtautef.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymyieml.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aocncyyf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqixzavc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpkozvc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2thtsarus.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2imdudykq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bksncmtk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2svvnitda.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wrymwrgp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2niwdrmrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nufnoyxx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isjkgjsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnliytyq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2skjytkpi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtdkocy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqqcblx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbmquoy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmxhwen.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfssxcz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkyxhtd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqkbpfs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2joqcvsvu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmpepqc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ravcbpdt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2anvpvznu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xzazowtc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhfrxtt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfplgfs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqdshbl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohxetyc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2efqhwscc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvcvnys.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mittyocg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbbwbqt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqhlukg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qklofpda.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wppzivrm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkyvsac.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbjibrr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvnetcq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2twzuyxsy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbgxsur.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2srhisjyg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yinwwpxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hggxjlhi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvmsxyr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrmgzdh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mzigjzog.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqlqror.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2klnasvds.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jywkbmmz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhyiakx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2woxgpjpc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymrjuvj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nljnqvxo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvhejwb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgschxq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2upzzgmni.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjcljdk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ohonmxqq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzoqghf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxyuhpp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beynxdag.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wscfqubb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgztkxb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyuvoqi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmzrmfe.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2faacoxtf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vesotgvo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rttqpmji.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2orkshjos.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeuxpkh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mudqlaxv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtconrp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2izrdnluo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfapzsr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmvmqkp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcvvqlq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rapslzxo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eithcftu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gphhpqft.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoupmjr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vshvsrsg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2aebvzumf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlpgaxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khtmagmf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoneilg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arxncyjs.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwijyrpd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhjwhbn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxcbxpm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgoiapw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqmwxct.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pigbseug.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zffoleht.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxzmbnf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fqesceey.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkadgfj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhacgmyj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xblxolzd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rywjbqdc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmdnlwk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqypboo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nirivipp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfosrme.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmyoudy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntefnnmy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2faakyfac.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2liftrtym.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ineaeypd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2brcgjnsx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrniadpv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yqujdekl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrvmkry.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2thadpwzp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjonbggu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mphotkud.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzlrakg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pygoutvf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuecbwm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rztminek.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uemjtdjq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mfilcpbj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2orcsgbwj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2teqepfuo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dndjkjbw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvasmkl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvnwjms.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhslawv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvmesmi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ethtrmog.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhfcfrc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwcilhj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onndkoqe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2baibuqcr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dauonsfp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2arlcfumk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrohpos.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2efcidyit.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjlpyxm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gfljfqii.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxxqvz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnztyfos.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbsiiqg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2teutxhoh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2giooyzqk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzuarmh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvcmfjj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nwutypep.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkfonwd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgkhzzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdyfeho.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlcpidl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quueiavq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lovqbauc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzkfezs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2irppcjah.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbvfcpq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mcelwesn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2smgrgnpa.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cdohhwlh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoabrhyn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssryvmel.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2futczlye.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2beczjrym.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfktobt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxelnsl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxdxmrc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2udodbezn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrmuuvo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxwywiv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pykeolks.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkggapcx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2axdzezhs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iieyqjmt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzbxcea.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqficlzl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtbbnha.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xecsrzra.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsjblvi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpqkntq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlrkuhv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2turuxcly.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbiwcfg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxmkrjb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rwykynpa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdgsldx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdleluz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsmawsb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wybokjcs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcywaei.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kljjqote.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvguwrw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kujkmvcc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2chnjzixq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cckrfuzz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2detildex.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgdhgwb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmlzzcx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzwpbyn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2izpockrd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrqdlsa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsjsteo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2odfhzgzj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aqavgcdu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmedpna.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2unnoxadb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cukbhvxt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrrfuut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2crixvrxp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dyixwifo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2adigpugr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rvacugqe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbhrtpw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pztulstv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgjvxeb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lygpepcj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvulkawp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iypjltfs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgrosii.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fojwwmuj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwenjvqh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ekixgquc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2blzeadzt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbwndty.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eigqglcj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdorgev.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjxzqzk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdjbiox.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2drzydjfe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmcfmbe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xafjoley.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhauqzs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uztjgywl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnscsis.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlrxlhv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwbxool.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbhzbll.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2znexujkq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkskeqy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2focdjfeo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtxuoox.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrhixnn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2msqkoejl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oynicghl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbcoebf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yccfrawb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvymtham.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eeldcrer.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykagpaxe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wkquzdiz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2beeheklo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mitltgdf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlfrhgn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvohmsb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2volyjhqi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsvuotk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rloaoqea.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2azabymdd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokkclfg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ioddligj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2loorwkta.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnpdlqt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfxjihl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2otxgzmmj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hlutjlul.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjfjcfu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhbbkay.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqqqtye.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2afblqryy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hamxltnm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fazuwqnn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udyqbspa.html


<!-- 参考信息 -->