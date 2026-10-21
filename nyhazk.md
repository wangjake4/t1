代发 wailian999

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtdwbhtivy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtnexfrryt.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtghazvdvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtfrnzojvl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfagqjmc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtlhcrzjxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtkgauhirf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtkubdfnnu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtfwfznsll.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gttndwvnow.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtgutrgwax.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtvygeriid.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnmidpwdb.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtilxoapum.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtryuoileq.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtjljvohbq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtoijkckmu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtxwgcgovo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtupcklnhy.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gthzzaleju.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gttdkbsoma.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtrvkcvjly.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gteoeqvtkh.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmfhzfjc.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtfjjlbhvt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtgokepflk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gttdiaylpt.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtaecctepk.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtgchwocnu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtjvlmdoyd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gttsyduosg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtejkshpph.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtyonmnmae.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtnzvnsgug.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyjzoufe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtacytmrma.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gtkzgagzkk.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtbbzpdklq.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtwbcaipid.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtjlngcyrj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gtyldnqwzl.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtwxajdswu.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtpbltceyq.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtnnxcvmjw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gthikihrtg.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfxihcfg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtykippqpx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtnhzitwrs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtgvqcuivp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gtgspsetaz.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtrgzxbeyc.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqeosrkk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtdnhqtttz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyfqiksa.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtfguitpae.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtqyzcqcja.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtdjjjdjwl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtmtsswmvi.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtjgzqnebb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtkcqwfokw.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtkoejpsnc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gtxitjoios.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtnijjvbyu.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtawzbmwhi.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtxrqxgjhe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtvpuzvtgr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtrovtsilx.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobiaqccd.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gthmtnnyad.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcpdbrhzu.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtitjzaxdt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtigkrioau.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtuhqpdkbn.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtbbzlofvl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtkashctey.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtnhqbctrv.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtfhimrkmn.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gthhimnwmr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtcfxvtfql.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtwpqdsqia.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtnlalryna.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gteptoopoz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtlzmwodap.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gtbjxidauh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtmryknfhk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtlwqugrak.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtzsuvgxqg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtgefwflpf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gtxjckfqhx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtvoqypfec.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtecxlsvhg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtsmaqclmp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtfualqhgk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtwgkpnhuq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtgrpkhkqw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtdhuycbtv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtbokbksgp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtknmjsaym.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gtvnfdifbd.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtbrpxzkvy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtvnjfgdyt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtxepfbvni.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtijoopivl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtrutlrhtm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtpcyeljpy.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtnvnzgtbf.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtukddqgkw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtjwhpabmj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gtnngdtnds.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtggrjkvbg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pengpengdd.cyou/Article/details/gtrvgqrapz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gtvhjabwzr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtdlmokmmc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gtlomkjpfq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtlhblgfht.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfvwyjgd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtbrkmvsge.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtrmipyexf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtetiastvg.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtouagoucs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gteyiklwhs.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtuwwdjugq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtbcvpapby.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gtfrhasogf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtupkizhmo.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtiluaekbx.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtdwoafnal.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtvlbovkaw.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtlrvkmror.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gthewxydtr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnrxkreq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtvcjrggik.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtgzujkvwb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtxyklciqi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtnlluflxl.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtyvrdyuxk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gtnnhvsfbg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtrgveukhs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtakblvpzl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gthmlovwzy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtunvbdteg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtytdzjdcu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gtjhcuchxo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtprjdggdi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcyawjiys.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtsjpljqsm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtldlpyppr.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtchhkgzub.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtfzlubrio.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtuorynkru.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtfjvvgstm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtzdlaudbn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtlmljwoab.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtbemioqua.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtubgyschh.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtgiewkycp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtapnhsavi.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtgcsjrdqk.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtcmeyvguv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtyyjulcej.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfxtykwk.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtybweaxuo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtmaelukmj.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gthlxbqynh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtdgbkeeob.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gtjqfrmgvk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtzioxbquu.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtdceujowl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtounhmhdc.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gtpjxiwrxs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gttqmbounp.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtbfmqzpdq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtpourgqja.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtvxvvujop.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtaqywcivm.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtopkdjtqf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtaikwegsg.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gtytnzaynm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtkmevgqkn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndykalzk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtrvcoterf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfbroozr.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtxogafgki.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtrdcxtinn.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtekxzjyfo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtyhezipdj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtfkoznqlc.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtmirqvsmt.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtyrkhnmwg.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtkaoujpls.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgvzjiugp.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gtktvnoxei.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawgkwbkh.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gttcsnkizm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gttsndiyos.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwpahpnp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gtyuziyofm.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gtatxiugoe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtqybakcsz.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylorfrlf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtaaapiwpq.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtijumocvi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtshxymmpn.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtpeagkscf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtcicfbfca.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtijziyqmo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtujlqcjvg.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gtuemzrarl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtcrueylpb.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gtrvxwwiia.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcjoknikn.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gttknsfikk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gttalpfedr.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtolxdjepz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtwlqdfeig.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtyfioaayi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyftljtuk.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gtnycamhoa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtosnsabug.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtseljkisz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtwyeegfwv.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtevvlccvg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtfcxjjyye.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtayjfxtqm.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtiumpanqz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtkydjrocm.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtzejtywbg.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gthepkqahb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gtgwtlqkog.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwmscdwm.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gterqejber.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtbxcstujq.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtxufnjkcp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtwiacxdpi.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtagngighy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtpmleeqhu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gtcldulciu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtaqpydaij.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtfwxpcyzh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtvggexhqf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtckkzgbaf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtmnbkzyfv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrokeicf.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtqftifqdc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtqmnynuyj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtifkcgjpp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtjvkccwdp.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtyedbquvb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvmhocks.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gthldbzxrg.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtxjkvzujb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtbcmnjxze.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtrhhzwszx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtnjuptwcu.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gttrqhblhd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtyoglqfcv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gtivftltqf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtcjaiibpw.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gtxpyknoll.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gtuhfyfbtk.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtnkydakqb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtbpwoaujn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtuyzzilwu.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtpppnfknt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtcejqxofc.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gthdzzhcco.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gtfgurfyut.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtuqhhzxep.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gtvxegeaok.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gttkdhgpxm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtcjwlmwun.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtfryesrxj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gtqcwrbwpm.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdxdwrzd.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtqrfqdtok.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtqxngomxe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtjzftlcoo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtvbgbzlhb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gtcarpxtnx.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtcbowkboz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgeicyhgz.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtaoxfomtl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtornaboag.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtubqrckdc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtdomzkols.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtpyfrpqou.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtqnrrdcjf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtqxtfgoke.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtqhrzxtep.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtnajiupdt.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtzatrqxau.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtezrydazc.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gtshuwncnm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkppfojit.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtdaeazbti.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtogjvflcu.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtbwhwfbhk.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtwdtbowfx.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtiyzcwrwc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtmgnmkpaf.html


<!-- 参考信息 -->