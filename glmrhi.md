代发 wailian999

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gteiddworg.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gtmpdupvbh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwuuwgbsa.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gtauguoepl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtwzswvhrf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtaqdntuij.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtqdpjppsw.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtaroayghq.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtbddkhbyt.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtigxhbvss.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtckdmggrm.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtsaehgiee.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtjxtpqtbx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutstjtns.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvqrieix.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtdlsetgbn.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtnpimaqgb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gttrmrixql.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgueabccd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtxygcxizg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtpuqyafqp.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtfxlhbkny.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtuvfohojg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtptofcttd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gtzknflkyd.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtfqwvmldl.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtseepvlrt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtwcgxbmrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtkoggrfyb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtuqtdatnq.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtmnfkzmrs.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gtqaxpptxm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtowiyobuv.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtmtttrukn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtxslfeqpv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtgwzduikw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtklmziiut.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtugbmwbwo.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtwnxypzkl.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtqmtofpqg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtwqkhbkbu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtkdsjdfcw.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtkpvjsnun.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtarnmmsye.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtfqdhaowk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtevrmfcfw.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtqocxrmhx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtctyohpeh.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtjgtavgqu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gtqyxslaxn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtghientfz.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gteffflojk.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtraetlhfw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtuuxntlgz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gthomggpsl.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzefsjwl.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gtbgtliwwz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgfifmtcn.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtjocwihlf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqukjhmcw.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gthjlcjqvu.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtltdqtmrl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtscxvxtej.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtfuivdkxz.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtlkfvjwxf.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtywvnsply.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtmohortad.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtpgxczbkb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gtmbzzgkzk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpigedgw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtyfycboeg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtecottamn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtvwkxshme.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtopimlvzm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtzlzcpffd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtcguijfkl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpszhypv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gttigrocso.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtjjlmtbbl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtvhgfpwbx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtqvxmyfdj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtipglstxm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtijhvkcvn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtdpdkfgqx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtuxwsymgu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtzhwypclm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtlmqnycln.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtttlwjbpq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gtmudwmhny.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtfxeynvrr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtsrjlngbk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtuvsgdlpp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtfwzihxam.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gthgaocnwu.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gtwfevrali.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtfbztirzk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtijpqhdcl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwzyuxhd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gttpipbfwp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtuafevhvn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtaedhgjte.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gtsucngbmr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtyzylaahn.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gtpbpidskx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gtikoxtmtj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtfxyechpp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gttfaaemyx.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gtsqgujbms.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gtwcooqsno.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtdfasaocb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtvgcxhzrn.html

Go:   if x == nil {}
来源：http://dali.quarkkingdee.top/Article/details/gtnvvbbmga.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtvpdlcpsy.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtsrjhqvol.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gtbzuczefg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtlkigdhnl.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtzyedwamz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtbzrnwtqw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtadmuehpw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtwwbkyzkm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtouvlxfmx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gttbxutfif.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gtbapnyxuk.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtkzqhieyt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtftvdfyqy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gtyefmuqrj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtjvvwakjq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtzdgboddm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtosmaioqr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtscgskatk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtrgbjgygd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtzlexwfhs.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtidavdkiu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gtcakjmmmb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtytqebzbb.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtqkbwifmz.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtivjholbz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtwxxmqjok.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtozigwvtc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtzmbkwlay.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gtyjqqirhe.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtxedivlmt.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtlufccmvo.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtpsjrwwus.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtzdfewbyy.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtzlaqiqaw.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtuutumnmq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtwyrhoofh.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtbvnidpnv.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtmvapplwa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdvboexq.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtnlryqvhs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtpgxikryu.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtcvevqlaq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gttuqejgzm.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtprkqcdwn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtqsfjpkgq.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtqcvduolu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkxxoyjq.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtdbsujetb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtyjvqsukl.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtmgrvnvxa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtubdzwjhb.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gthpmiihxs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwftspnuu.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gtdaplbbee.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtkkerpwbp.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtvslijugm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gtdgzkxedy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtqwvimyuc.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtlvogrrqk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtdydapxpv.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtvpkcbrzg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtznjqljos.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtdizqyint.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtlblpffki.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gtxwcknxas.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtroepxugn.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthijyrkcr.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtinnodwkg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtactwgury.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtnsbnoame.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtiwdgouwv.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtndcokpti.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtilcovhll.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtbkqmsclf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gtmlrqxrwd.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtytwdpumx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtvfhkiasc.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxkdzcsk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtehrwzhbt.html

[Q23] 分页
来源：http://dali.zhoulong.xyz/Article/details/gtpfpigrip.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtkibxfjqc.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtvfpscvoq.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtovufongp.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtpypsvvdm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtrxfijadt.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtebcveiyz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtfojtquxo.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtzgqduslh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtehvvzjdd.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtmdcdyqli.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtdmaefrlz.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtsbwrjgdl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtcnjdfgmv.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtkxpoqbyv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtkberexfn.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtkktensfq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gtelxvkefy.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtqobgdtmg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtyryrazme.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtrymlitlc.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetxkgxub.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtyjdlnnkl.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtqtbjwkvv.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtsfvfgayz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmtpftrf.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtpslbtauw.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtdqldyucm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtivnaqakf.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gttadtxyfk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtggbrkuqo.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtykuyxpzy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gtejlzgxun.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtdtqpablt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtdmlhjzhv.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtdepzjnqw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtenazosav.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtkutjzilu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtdrtltold.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtnczmenvj.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtaskqswhv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gteepqzypf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtvfsdxjrg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtmtnoajmj.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtzcjkslsl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtgmlytkrd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmwpcpcg.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gteqyhiwvq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtkwdajwzt.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtwxuvkjik.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybgbwlwc.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtqjpuskir.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtkcbowrll.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gttkyogbly.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtozszvoht.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtkfbmnaaq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtbmporzvw.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gtynlxfekl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtdedyttbz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtgywngagw.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtmqoaxdpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtelybrbep.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtkrpndvmy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtrnvxzsjx.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtctwjhbti.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gtcmvxjzig.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtzcnuzgik.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtydfacjbn.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtcqvsfvng.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtiqysewsm.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gtxpnpugyh.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtiyxpqdie.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gtgfakohbb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtosoetiaq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtigdwisox.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiqljglz.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gtkjxjzewu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtppslblep.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtfxrkkwco.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gthcvirmyy.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtrouvgxca.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtyfujtiwo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtpiitqlsz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuhaxkuz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtcreqnesz.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gthiphkydr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtispafyrw.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtlzzyimaf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtrrjyuair.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtyqgcgppb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtfpvwyoud.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtzefgiopo.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtcoocbnpc.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfheycfq.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtfwrfrtvk.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtrlbtyekc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtsdxhpecc.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtmeclqrds.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gttglbkfyn.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtmssdwoah.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gtpenvskrv.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtkgxavzgd.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtgjtfwcmt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gtjyrrnqbr.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtlorvfypb.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gthypuzqqp.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtempysllm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtjsgnskug.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtrrdkrgjd.html


<!-- 参考信息 -->