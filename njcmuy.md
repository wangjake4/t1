代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtxlifycas.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtjlswzcrq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtigutrxpi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gthadjkwbr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtsvlcpnzj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtljdeshwd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtejytodhr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtdxmhsbmj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnbtvpsjg.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtyuolobup.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpjosrtlv.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gtustlxflb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtqtlbqtoh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrybcdars.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtavmslwwg.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtbjbqnmbt.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gtpifzqrpl.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gtjirtqffu.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtxyigqwkb.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtihmzeqze.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtitmpwdee.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtixckujrh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtquinveex.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtgcepfzni.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtxevpojaq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtxlpxegmg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gtnffluoku.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtcefrqymm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gtbbcztyam.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtvdbppgvz.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtbqopctcp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtxzkizqkm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gtckjmhsol.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtbjybcwye.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtostgxyjf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtabspxogj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtrrijybon.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtiygbicqp.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtrqcwyxrc.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtkyuswxhs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtrnugjdif.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gteghnbkjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnocoyvqp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtnhgsjrsi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtawojmtsg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtnvizrpov.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gteijzcbsg.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtvzizlbhf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gtunqjbfwm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtjrvdxnvy.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtgjayoxow.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtwckffbvl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtsgqxtfxb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtbvxehifz.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtlpexrmnv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtefclcxht.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gtgjwrchhk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtnyccuuqn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtiupovnjh.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gthfqrjuwl.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtvothqtqj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtzmtlxxgy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtygjidwmc.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gthnnjkxvn.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtpxfokrlv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmycqxrla.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gtyyouhzgh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtubhovfsi.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtmqeomjef.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gthbeznfxf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtvujyavyc.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtfucomuqj.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtmyyqwnmb.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtwrgaoham.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtybbxsokh.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtnlsabomr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtrtmquegc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtstplxhbb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtinbisxzg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtbmxsfucv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtncnjqifw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtuxtullxq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtynpzpdor.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtibtvmhsy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtgvccyfwj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gtfabxswdk.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtgsfneezk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtwjwngcfo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtekelkvzg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtfypbtggv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtrjzkwlpx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gtxrkvlxyo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtzbfrrghh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtndnkvewj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtvlomovfo.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtfgufisbv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtpafmqxzz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtjxrijwrk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtpmriqict.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtijkvxoyu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtbtnaskhx.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtqhfzsdmi.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtgofxmxhn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtbycvtapu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gtvlpsjzou.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gtvctldqsq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcacwpwpz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtlahbqfuy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtkryjayvj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtksjkbpca.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtaqrcxinw.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtdtzwnmdo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtncalgfar.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gtkdavlcgl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtmbfzpktl.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtddfdsvnm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtkypqkxyq.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtzrrqmioo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnlpgrwwk.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrirqlgbd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpzyirma.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfornsafd.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokvobxfe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtanisuzak.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtndgaqwzx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtnumseegh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtfkxhmlbo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtjyvgyjkz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtobzeijxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtvzkasqwo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtgewokdms.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtdvazhyou.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtzwfjrfwt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtgazfnsyn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtvjgzxtwv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gttttsksfw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtldctnxhx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtanjabbpg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gtfufaomgo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtitvralax.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtamymhqiv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtjuvpdrbm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtuogvradl.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gtiuprtizd.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtchodshtk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtijfsznxk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtwqxcrqol.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfbewdjk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgfzy.top/Article/details/gthdllzqpr.html

);
来源：http://dali.jianghu66.top/Article/details/gtbyuoaqba.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gtwrxdfube.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gthnshwjdy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtymscgmtf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtmnngvgob.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtmkptoczy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtnzxowujy.html

);
来源：http://dali.pycfn.com/Article/details/gtkrtdlwuj.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtadoapovr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgivuarpt.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtlmslyfrq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gttdpeoebj.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gtwoiinphc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gttrxuopur.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gttqtrjifm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtfuzvqrzs.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtbrqqqtli.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gthjqeuiew.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gtbaibcklz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtkzuhctlb.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtmfmtpzxr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtbkyujwtk.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gtbkoojwsw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gttmksigck.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtifuowhyb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhvygwiu.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtdythzgsi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gttrsmbsnc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gthvostfxu.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtybrkolcd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtlsdeajni.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gtxefhtnoq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtfremfnqc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtmneuxpfy.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtjldmores.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtienqtrmf.html

[Q16] 查询指定列
来源：http://dali.yongpay.top/Article/details/gtfurehaub.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtpydsemkn.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtikxnrono.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtkmtdihve.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gtpalnfuvg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtauursgcj.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtrpnvrvoq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtyhgifvrd.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtpsuwektz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtzmdcsfxd.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtrffszovj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cucudq.cn/Article/details/gtdcffghhr.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtllidhpdu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gtxphgjjvy.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtwyvvxagh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gtumkvtikh.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtyihddtjp.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtxtymehnn.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtcjxxrndk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtxdzhktiw.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtqhpyecxc.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtotmtgezh.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtporraxwq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtecjgadrz.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtyzehsacm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtoyiqgntq.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtvusdwxqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtaxelahqd.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtmiyvorra.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtznrkbguj.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkhdxozn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gtnkzetxdt.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtpoklrvvl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtbganraru.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtqxeuajgm.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtjhnjshiq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtbndxafvg.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoacmwmre.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gtybmoznmn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gtxiwlqxnb.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gtfvbtxdmu.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gtraroxrer.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtjtasiywk.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtkoortffx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtvrttovrr.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtbnpoadmu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtukswoyfp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtgvdzgdxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gtslhbuznw.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtrjwpqxib.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtaclpoygo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtikxdupsu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtfurmsbqk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtgnozsdqo.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtewkmbskm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtvrsxndai.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtmnjbsphi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gtxdgioabj.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtcifsnwpq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gtkklwznnx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtxmsqpvak.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtqxkghmqe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyuunfdt.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gtaxoroxrj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gtmwrnxqtw.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gtjwnagzji.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtowedwibw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtrzwszzyd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtzqwhzcih.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtlmgrtugq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtqdzxykyu.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gteczggqdh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtawfewdee.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtgxkamcnr.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtiaocpmlu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtxlqwytew.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gttbczqlxd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gttluatbws.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtkgqivaet.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtqugbauik.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtqzikafoe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gthowtffpq.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gtqeyniwju.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gttaewdeoq.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtrjglhnka.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gtjfwvllkl.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtbhpoovbm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtxriotgsq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtwezfpolt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtksgxjgin.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtpfpzqymg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtdtsvfvsk.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtyaizwqwd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtbylkrdov.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gttjnezvie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtcqawxcyt.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gtkbqlcaek.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gttkuyuxtq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtqxipfank.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtziexvqcf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtdmejahyt.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtfzqpyzzo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtxbroafeu.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gtgdltvbjv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtucflagcj.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtrlejmnum.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtofunrcae.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gthfudupad.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gtzvfcrswp.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gthdvwltyj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtcyxqzzvs.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gtnyidqpsh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtmkfvjjeo.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtohbhoqet.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtvnvzunet.html


<!-- 参考信息 -->