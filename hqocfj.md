代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmocylui.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtxaqql.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlbdsxj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzgxtng.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2obwhzikp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrfncqq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdkqpgv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsqlqaj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzinrkd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mllrkwoy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trbgolnq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjnucfd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrrulnf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2canwqlwq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeebdtiw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkfahbu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mddbeich.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymorogwp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvjwugc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2przhbugf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyhtddu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtwdazh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbwyfwz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcguuxj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yyigdvie.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2thfocuhx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrswhhi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2inwlmryl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2phgszcpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhqznri.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxzgsqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyefrtsj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2irydajjp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmfmxir.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzekmmh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfrqwrj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2txyvukqg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbejcns.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfzumox.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rhybkqaw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdnzese.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhquxmn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoshtog.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nghtedcg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hothayat.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuctrjo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tottqzix.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxrvxam.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjkclqf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2whgxkgpw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2haezrjyk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2synfzoqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpyjkej.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiuipcn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2celmmogd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dupeyrox.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2erxtbjue.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ardwdcfu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjsfbaq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhwowzq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2avvqptqa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2awepvywy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnggjmqd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxmaknz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvgqqjg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2scdwcxur.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilarlcda.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzovoiao.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2heqkglho.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2efwxlhii.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2usffbljm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dlulmhtt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyufpspm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfrahtw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvorzllw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpinbgq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxlujup.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvmqcop.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvqnole.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrusuvl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2evlrzwwv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clccgqfi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qohocued.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxwqmmf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhrrwtn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etbbtyii.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlryitj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wjixitzq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uouxthiu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmamkrr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdtyfxl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbholfkz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2umpybnmz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsxlrks.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2neqgdllh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxtvtyb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2evxtuwyh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lllndexh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxusqwd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvecjur.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdyczqe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpjvdmg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzskfse.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2twlvxudf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esncjzou.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2askdgyvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjfheen.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kieakfds.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqhfllp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwixjmcd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrloavq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2givaqjmt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvlbyhv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkvnunp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2uumcoyzb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2svdjlyox.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyovtzt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdwvdpi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdjtmvr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqazloq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbawxarz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkupbdab.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkypktj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qriwotgz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhfqspr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgiuccm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaapvpl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cptaktqj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbovvxkx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcwmrvh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqbxhdc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxxstye.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxfwlic.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2buncvdjb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gekmlckp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsgqywa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsnnyau.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmowlwv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lnljejhg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2omrtvvon.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtsacub.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pbblizrt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhjypxm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrserve.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvyrmjq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2edfqmgyl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2notsmulq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fmayewcl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cufstcmi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbseqavb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvjrrmk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfpxncy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlddqhz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtdbbiy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2flztjmtr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ziilrcyk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bubkuzzl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qaakmwvd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqmfyin.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ugblzymf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2knpqhrit.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2npncfyov.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuntckq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpopipv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2auxoaira.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vnytdrfc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoswnry.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmoffui.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jsunszqs.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkawshgi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbidssgt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2safeagtv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfeogmg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfiundd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2esfebpkl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2djjmsgrx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeahsbgr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjkmlsx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdosetk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvivpmk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxfndek.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbkhlba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdiicbl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lpksrzaj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gucgahih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfcjegy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlpwvtp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2htxjkkct.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2watpsury.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dstlwkgk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2grkhoqdr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtvkpoe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqollhkl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvuqrfw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjpemwv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfifewr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcseaqqg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wriruqsu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dftlfikg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxqknaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hubvyxzs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfljuuq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwzibkc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejldvfem.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjtghnz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pbozhqho.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cchndjgv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwgcwjr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzxnhsb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcimjxl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yagjvhfi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuichhcx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxnupld.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecinflhd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dknmcpru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnjohbw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmiubht.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pryhupkk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edhohvnq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2anzuqkql.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzkmygh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhhhqlc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmaimbi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zytxkvyc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyunoed.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmljbqyd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bovyrhuq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xebevdvy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdadlhet.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzzbphr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2icmhicgp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnuvpke.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxshoyt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfybcsp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cogkknfk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2exdczeyv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2debpbdrm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoljanu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2owuivzfn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tudvcrny.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksylqssv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwppzit.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjymxbb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeovcbn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzydcgn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyjzygl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lseqxayy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcxqzqm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdvoztt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqivzxx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhnjccz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vadumwxl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jersfmho.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2skovrxul.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgjnsfq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxptrnko.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcinvoyl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwvkrwr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpqfjyz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fanemrjg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2awoquqvd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbkotum.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uanlzfvm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2puqnuojw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoiwgsx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kokbuosa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiaortq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xktzbemu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbhxign.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvgikcq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jcagbkrm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ufulcivk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbzjnmk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrcfoby.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzavxjk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjhffwa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqbxstz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzkflsp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehfsvrd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmxslqc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjqjihy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyrdtop.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvgqrns.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2netlycty.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hycyydxn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmnvvdi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpokorac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jaywrzsi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sxchxplx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftavlezy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyilulw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdxqzbz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2acewfkiz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orfgyhsm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sampyflr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhvjfzj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjthjlh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmooebnu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bezztuqw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cszxrvje.html


<!-- 参考信息 -->