代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gtbfapumfd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gttmowjmuf.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gtikeqhoji.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtocprkuzh.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtemxmgxpl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtbacqikij.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtavjtugmq.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuyyiiqn.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtdotmaady.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gttkbncjcf.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gteveufihr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gtkdzgrpol.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gtkzofvazt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtchquplqx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehulkdvx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtkxrbuxnf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtrxdspyoj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtxyonczjx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtjlxrwjar.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtyqrcsruq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvsyblkgt.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtaepbombx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdqeyaecv.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gtxfomjxye.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtdibcgffb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtigpglici.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqpyjegh.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtdyvkkooy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtvewgpubs.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtwbwkbovx.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtpgjxbfjd.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtcrxpcems.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gthyywlwor.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gtwhkvggng.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtrqnejkoa.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtwwinpjfy.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtqnhnkmxm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtgfoqgcot.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtxqgykgvp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtpmtlbtom.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtbacvdytt.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtakhkvgzg.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtjuandcmd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtiqocmpvx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtxeeecove.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtujawvkbl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtdxvlthdu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtkmiadvma.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtlluhpgfl.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevlfkyuz.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtbepjbcpo.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gtfpuraspn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtckmiofme.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtcwgkxunu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtfoalmrmy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtayideoka.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtclcsbkwb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtnxzxyyat.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gteueikubx.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtnbrtsfie.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtjsmdyquq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gtbrfmupbv.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtgcualuxq.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtldgdfydd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtvlbwzvrq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gtcqwrkhfj.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtfilgybey.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtwdglbcvx.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtggaudkkm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtinjdjnxs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtfqvcwnrb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtohdglbth.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtpbbcwzlq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gtkgutokvz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtaeutghit.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtzwmcmdwq.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtddzqgvhl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmwkbshve.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gtnojdmywb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfgtaegmy.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtavsxlpza.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtngskkelc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtarxumxaw.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtbspmdaft.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtmiyjfhop.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtutsejfpf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gtcfoohhcd.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtggwcfcbi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtiqmzwhol.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtaligujqs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtjkraoryw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnbuihql.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtsbgqhfnn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gtnracqlwi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtfntbqoaa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqimpppkm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gthderijwp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtezjukwig.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtzgeuzilp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtuttxaxsa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtraordeto.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtbwlihrjv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtzhcytdhn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gthjcrvuyv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtxwkmrkri.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtzxfuzpyj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gtkcvbnuzq.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnxhakqk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtpkkcwjwh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtidplmgxj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtjjjhoesk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtzuwckywr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtvwpyduew.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtvmlteinr.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtosqflclv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gtakzmifrm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtupmdvqwa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gticocdxxe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyiirhsb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtcvxkucyh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtoqxnhflx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtdpndbyal.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtpifdpwyz.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtcgwksgpr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtollximya.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gthphpbsfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtyxwrspew.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gtwatpytnr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtqlcimufj.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtsiuckdes.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtqocickki.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtkutyxmrk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gtcqwgrnfl.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gteanvyvrw.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gtspyohndf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtqhlqddsz.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtmuzfisar.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtxdbbuhrg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtnqdgwfvw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtjomjfbkw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtpdeaxzwm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipxwfyye.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gtconarwoy.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtkgzhnwuc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtvxnofsib.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gtyrnlykpr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtefdcqddy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtastwkxfj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gtfvwmamaq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtvpwqwnyb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gtccedvist.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtzybwroxm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrpaqmmfa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gteuhzxypk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkvbahpaj.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gtuyyiqvbj.html

CREATE TABLE users (
来源：http://dali.ehwqpu.com/Article/details/gtlulbhyuw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtsactgztn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtjuwfxnpw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtjqptxevv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gtixyccbqy.html

);
来源：http://dali.cdnleiting.top/Article/details/gteqdfcprr.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtemqvsdlp.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gtygsghapy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpdppkfl.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtxjtazjqk.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtyglptzin.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtygayeafs.html

);
来源：http://dali.zdqjudy.top/Article/details/gtboanmayd.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtmjugrzmw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtxlhrurnq.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtundtqrub.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtgrobobcq.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gtttbfifyn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtjtsfnulu.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtfgufijzb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtoqjugtlo.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtvhtvjsbe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtzoeghvxq.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtwqrfehej.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtttwlyrnz.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gthmtjqlut.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtsmyvaoxs.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gtefzrwbch.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtdylpwwvy.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtebvqaprn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gtntbdclyi.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtrvakfgas.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gtjfxhrmvo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtsinfesve.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtnrftprqq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkfzjdfc.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtoarcuvnq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtedgjjmml.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gtjmehxmgg.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtrofedkhx.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gttojtgltm.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtivuzspjx.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtwbjpprao.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtqibmdrpv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrebmjjb.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtgmcplbmb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gttbhftdgm.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtvtgravps.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtveqygvun.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtctgflvxy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtuvtetrxw.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtagmfxyvd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtohcvztjk.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtxlzslsun.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtdvyggoob.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtkqoeefbo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtlzalhfsl.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtjakfdddx.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtafzlxwwc.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtmmsklbui.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumkocorw.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrsvmwej.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtgoerdnsz.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtivmikomf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtzdyvdbat.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtymsmyxob.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtnadgzvus.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtunxzznay.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtpeevxwvz.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtpctjylaf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtwbbcgude.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtgdgyxriq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtraxwqtzz.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtxooggmcn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtaagfwmgx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtzmnkjocq.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtsqzafrsu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtmstjrhiz.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtrchahbcz.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtvqsexkup.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gtlxdjltqs.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtkmmnepwm.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtcjwugdtp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtmnmiyccg.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtzsqccvlp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtuizdptvk.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtxrfjeeeb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtmdqgtjdl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtbmnyjvkq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtmvnzcgiv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtlwnruleo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtooufefcy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtkulhkczr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gtrbviqock.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtomugogot.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gtonmeiesc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtzcyenlqn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtrwqhsgnq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtsialbetk.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gtuyumvqoj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtgwkdyxra.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtfjisrdls.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtpwkcqnkp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpjeqdom.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtbdzmuvqh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtrqduyesx.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtxqxldczc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtrrsjbazx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtipidqkph.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjtecaej.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtgkyxwixi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gthvimlqld.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtyctszqqp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtdynypqlc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtntnzqixo.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gthegpgskb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtxfohfgtg.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gtqdzmnwxn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtlinkjmbt.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtmsfepcoi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gtkdidujrh.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtwlmtnxnl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gteoqvtehg.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtcvyljvvq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtlmemsxte.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtdckjoheu.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtecaxtmgg.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtzaaslbon.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtdeqhlknz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtzgcixapy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtgvzratow.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gthgkeplaf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hammf.cn/Article/details/gtnqebelck.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gttwtmxqiz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtsjkfqtgs.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwhyhcdi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtbdzcggyt.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtxrpporoa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gthuvrtetc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtjwpdclhy.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gtchhwjgnq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtvqkmqdtw.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtrcgaknhp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtuwbfrllg.html


<!-- 参考信息 -->