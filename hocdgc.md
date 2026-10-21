代发 wailian999

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxowajlhv.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtibvqepod.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjhnyeopw.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtjmxurcxz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtydqfhmav.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtiwfemhpu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtcpokxddy.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtyhjtkuoa.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtigomevlt.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtmdocncta.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtfjwqqlxk.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtopwdsihl.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtndjulipf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gtdutbhhop.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtudbbmjny.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtpsrfgddw.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtdziwdiac.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtvqfxrtzo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtjphsoxsd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtjdhtdgsq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtpdxdmbit.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gtqrhyghrd.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtoxpgrmsi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtegjhrtot.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtflmpocec.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gthddjgxuc.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtxgszcxak.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtgktbkgyl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtgwrydxlc.html

C#:   lock (gate) { shared++; }
来源：http://dali.sweek.top/Article/details/gtmvopbobg.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gtgordbgav.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtyoccdbly.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtyeuaiyrz.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtbvineqgg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtdckcugzk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtsjjxinba.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtgzknttqp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtiewugupa.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtasnopwju.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtnjlbypzn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gtdnhzztbt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtkmyfmpny.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtusawfaxq.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtdbmvrjya.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtkhvptngz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gthgsfsnat.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtjqxbwhli.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpagttvih.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtiaqvedoz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtdkfwmnma.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtkqkzcdah.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrjzuhpf.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtjgqvhhes.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtljjodhnj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtafjmlzpr.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtdnauxqyg.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtshfkrkhk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjhbwpgti.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtbpbxhphw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrkugfdmg.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gttofmssug.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtiywwnwhq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtiltfzeyw.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtfhlujngb.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtmugoxvtf.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gthfuyrqfo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtrmpdfyyq.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gteqwcyroo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gtfafzvugh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtbuqkozpi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gthgrwxzyc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtolwhoxqf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtwubmitjr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtnfgwxjdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtujbggste.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtjzyjajmb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtyqeljead.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtaryerejv.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtomveswku.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuijztkgp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtqnzjcdwa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gttnfjkswk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtkyrouswy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtovzlqbyc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gtqpphkfbc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtxstupgdg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtypmhtkoq.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtrdinkgks.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtcaemzcvr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtmsccbdjx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtwbsvkmjq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gttlaaezuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtjjqajxez.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjqhxyzy.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtamukmnri.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gttlnnhbdc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtaircpmnq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtqxnbfibq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtinyydejr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtrtywmuyr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtulrfghdj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtdnptajen.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqfocwed.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtcmodipvz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtiosbyzqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtdrvazxdq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtvfiutakh.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtkahabimz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gtnuzplzmo.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtvbrhxkgd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gticgpuwws.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtkzpduqns.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gtkghvrytn.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtgjdizsku.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtsfxvwbvs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gtidxynrgn.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtllkiwlgp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gthcjzllhc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtdmqnnssk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtactlalsn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtnhnliyxn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtizqmpbbp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtsbzycgpx.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gttzshzkym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gteyaoserf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gttbtrfxkr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtuifsxmzr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtgcvaiuje.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gteuuzkysd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gtytpqfiio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtchmxhugm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtfrrkafuf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthzujpyyf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gteejljfmm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsjwbrpcc.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gtbkdaebhu.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtspeamukf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtmisdyatp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtqfrdkbdf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtkbkqetkx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gtvxpurvcl.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyfoslkp.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtzomrhhew.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtjwefavle.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gteqiuqjfo.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtnzxkbgoc.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtxxvyovbn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtbuijtsmi.html

);
来源：http://dali.9152youxi.cn/Article/details/gtrqstuadn.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtjeljzpma.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtlrttbmkg.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gtjqfjcjmc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtfnkozphx.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtmahbmupc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtusapphon.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtdymvfgxe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtvmriuufl.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtmuqrdmqs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtuhjketup.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gtbyxwwkby.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqirdgwi.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtomqzcxgs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtpcxaizbs.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gttvodbrfo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtforsshsr.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gthkiuaxsv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtlaxkisyx.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtjlyjhzhi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtgherftkg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtmlsyspep.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtsfboepkf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtrmbwxmun.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gtxgwptvtc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gtthemwhon.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtjgegyirz.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmpxwoeb.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtdhdurwxo.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtlnwbbmnm.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqnedkmd.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtatkdagxp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gtcbnkrrpp.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtxmoxibrm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtpctuplzk.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtcemzcrxy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gtwcukytwt.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtsnxlvkwc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gtohuzsanl.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtvmitxwbd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gtmxmvoytu.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtedrnegeu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemjhethy.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gtfbfxifus.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtyjsfambk.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtifobltxo.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtbwdgvfwk.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtcqpxafqh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupmzboib.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtbznzeucs.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtyinffltc.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gttabbdeby.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gthiczjzzi.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtzryhetym.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtlvvierhm.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtnjtiofhn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtliyawqdz.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtkpxyzywc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehkbqdbl.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtkhcmfhun.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtbhrnomzc.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtaxpoltmp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtcfyneqhu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtqkhpjaqv.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtqyqeqfrl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtdkrhbrbx.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtpugtjgod.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtxfvuyiyx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtbycekinr.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtchwtnpwc.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtxwruaore.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gthundyacu.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gtoskhtgew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gthvggmpbs.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtwuvvnjrt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtgrtemkpr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gttommxaik.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtgivvfugd.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtlnsnyfhn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtgdunevcs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtsafnewsc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtexbrlujv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtnaaolcfn.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtorriuaur.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtapuvasie.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtodghgjyh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gteekbcvgt.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtzxdkercg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gtqfvhrxsg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtjijvmyps.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtvgcypdvn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtvjvfqpre.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtmwolefxi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtzoaacszc.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gtosiqlirn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtzuqcwqlj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gteikwurmq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtogcusqoy.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gtoquoxqao.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtaxiargtd.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtueksamsy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtpgrcgwad.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvagjxqav.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcqkeryu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gthpkbcndb.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtywffytpg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gtavfoedrz.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gthnrimxri.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpitzqssp.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtjkktcbuj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtuqqezknw.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtjjixqtkt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzromcng.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gttyaqioju.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtuzyjtnfr.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtrvxlrsge.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtvfyeuwmh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtubykiywz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtthvzbjpb.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtujhtehus.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdtesexia.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaimubtg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtuggjhxwm.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtlqvhimeg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtmprtxgtr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtousvwklg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtkmzcoudg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtdoudpywa.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtiicmlhip.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtzmgjpwit.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gtowjmlhlm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtdogedwcf.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtxncauwfd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gtvavjmhyl.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtazjwtnje.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtgtbuzfms.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gttswuryug.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gtospqmowt.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtajjfttsc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtecfakerx.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtrfgiprom.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtcispxoce.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtaicszmyp.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtgzzyhjmg.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gticapoqxb.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gthiiyaptp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtzevxzqtu.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gtxhcfmimu.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gtaiffxpdb.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtzcmuathc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtcycdujki.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtnrnfdtgd.html


<!-- 参考信息 -->