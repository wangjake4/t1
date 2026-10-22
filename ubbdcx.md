代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gt2ouuryljq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ksvianax.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gt2zkszqnlv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2jnrjkvji.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gt2axgvufgt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhbvtdau.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2mmlyxapg.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2imsnrvzt.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2ulhxixpp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gt2etiyewwn.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2yywpsfkr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2vfonmfni.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gt2kslrgdnr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gt2nlvabnzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2wirpxart.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gt2awargxhv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gt2fsagttgw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2iihpsqei.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gt2koefxwmu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2ufkddpbf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2unxbkbcd.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2bgkmovjb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2bgemlmnx.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gt2cdchfnps.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gt2ytdhtlhh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2kyqotfzq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gt2vnldrjiv.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbobrlxr.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gt2wrybdzor.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gt2jvegvwzs.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gt2ukyypuiw.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gt2jpiuofii.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gt2tqflaijy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gt2oqpavops.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gt2bxnalida.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2lwmgdlue.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2qlujcbfy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gt2njsfounh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2rymcewjb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlphytdc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gt2kcupjbgw.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gt2xuzjcxls.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gt2umxuqplh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gt2ynrgievh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gt2dxarpmad.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2tinkpwdv.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2abxumazg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gt2jcgdugtl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gt2djjmrtpg.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2qlkgxzxl.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gt2yzamtkdt.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvsxgmuj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxebphid.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2otbyflqk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvhxfmrp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2hvsprbar.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gt2ibxefgby.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2igtuxjtl.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gt2saqksbfd.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gt2nvxnyjsj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gt2dmcxqoqz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyfwdxiv.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2qmnqrchv.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2vvvofcqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gt2bumsurzg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gt2znzekxts.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2qdpwzsni.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gt2qijmiwvr.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gt2ahhfbnvr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gt2lrfdeume.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gt2ksagufmm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2semiybch.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2nssfmiil.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gt2zlvevfxy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlarihfm.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gt2aicebgrd.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccylpsqq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qevvpmxz.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gt2qxbdaaxx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nkvhvgap.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gt2ufskhtnk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2ublbydam.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gt2yixwzoms.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2tnknwbec.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2aoxsjhfi.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gt2ngwnqovv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gt2srbiecaj.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2umujagfp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iayotmdk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2pygfqjpr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gt2evvcrjuc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gt2civfvgkw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwuuylie.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gt2qzmhzdya.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2chnpxjbu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gt2gzzinjsq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nvkacedw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gt2vnwucrvg.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2udktmbnc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gt2wllbhrve.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gt2wjrifyzj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2xrqecise.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2ktmszltt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2drpusdom.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2merqzfag.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gt2ltxbifux.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onzfrhgk.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gt2ctxsxhhr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gt2pjttoquu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2gosuiqou.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gt2phowqmkg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2fsjqlaqi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2qixtouzl.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gt2egdxvtel.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gt2qnvmjtct.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2hbbufcdt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gt2pefyxdct.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gt2pzvibssh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gt2aiztszga.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gt2kniipmgk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbqoryyi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gt2zurexnio.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2fpgdvjai.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gt2fxtnbuyn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gt2cucbuvys.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gt2cajiqotk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gt2yomosdzs.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzuaavzu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gt2bbtiqbpn.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2twoinkov.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2zkfgqlhr.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gt2wnsijrza.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gduorwpr.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gt2msezswvy.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhvdjqgq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2bvdkddrd.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gt2erlyytgg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpzfbmvv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2onlvczjk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gt2xbmphzho.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gt2rxxyzwjy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2okmfhhcl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gt2ntyuxgei.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gt2wbltgmjc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gt2eyjuxpgf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gt2idqvownx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkfeikqx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2ehjvtjvb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gt2lzblalfs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gt2iuoltvmh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gt2dtejqhjg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gt2wivmvcsm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xuolbwkj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gt2bbktrwup.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2suqvthly.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gt2kwykgehf.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2uoegyypp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2cerokilb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2ourvzrhc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gt2kubmkock.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gt2cchrdgrp.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2ivoxdkxm.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gt2lzjsuvru.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gt2rmpczlmd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2gaydnsik.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2expldvyr.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gt2zzgldbnh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gt2zdjxotdm.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2cexfibiv.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gt2hoekbpas.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2ssqmjnjv.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gt2cesdpcqm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2thpiwrbd.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gt2xhzrvcyq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njzbivfh.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gt2jleyhgwn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gt2hpsktesf.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gt2ncnthaiv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2wbsaxiom.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gt2dbhtbkfl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2xaelkawm.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gt2dkcsdnnm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2xjgxceub.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2qcmdjioi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehjnvcku.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gt2wmdblytx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2pwmlfwaf.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2ingycesc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gt2rzxgzdav.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gt2uyreyedr.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gt2bhpwdxdj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2aumlsqyh.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gt2kgbdhklt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gt2pmsqkbxa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gt2dezezabj.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gt2vtbeamwb.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2furcenlt.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gt2ppgvpzng.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2sbmzkilz.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gt2cyircour.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gt2vgpuutfa.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oljcvcmm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gt2epwaovwy.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2hdazqtgn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gt2daicmhxv.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwfnexdr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2nietydek.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gt2wycxctju.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2sitbiiap.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2faygdcia.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gt2hsxjwzil.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gt2thovufqx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2uhhbjfse.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2iadaxtfd.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2vobhkxlu.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gt2ydgbvfme.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gt2vgwqctpx.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gt2odpqfiry.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2vdxxkoxd.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpintveq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ktglfjwc.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2nmojzmhk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2edhpqvwz.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqhzcbgg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kutovxcv.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgzofwpq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2oadntfrd.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2aleumjtw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gt2otildejc.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2rkwnwaox.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2cemudaqv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gt2nrbfytjy.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gt2gctunxmv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twldijcd.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gt2xtkaooyv.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gt2ibsgqgjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gt2gfooqfpf.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2dioymplt.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gt2obxnliqz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdedthrf.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gt2zqcyfbjr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2cqkcvivw.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2adnqlvpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfrszouw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2kcerwseo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2bmuusuzw.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vepqozjs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gt2utwikzgd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gt2vqxcavcg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gt2esqrvddm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gt2veanknik.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gt2ybibbxnd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gt2ximacplr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2csufrrsy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gt2tfkihill.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gt2ywddxrgm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gt2zarakljm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gt2joyfwbps.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gt2vpnvivvt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gt2bqzbkzun.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2oxmxzbss.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gt2zivurstj.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gt2lkfppkno.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gt2zbwejxih.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gt2uendiarv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2alxyfmgn.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvfszdxr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gt2kwbcumqg.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2dzjeittf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvhzlujq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovuykoyd.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2vkgglzvl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2dpbtcwvh.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gt2ezzgxuha.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkmdiogi.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzwgvjgc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2crdtidew.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gt2siwmlvyp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gt2tvdgfqno.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2jswsprfj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gt2gmhqpbra.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gt2axnyxexz.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gt2zqtoxpui.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwcemtyg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2kzmsdjff.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pektpudz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2lzjlfvkg.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gt2jaoeijgd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2aahggqid.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2nizmdibn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2wlghtwvb.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqetpovn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2epciqeje.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gt2equecegh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gt2dttuahxw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2esdgnklm.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2etqijfga.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2hdvnwifg.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gt2czlakoyd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2xvcyvowe.html


<!-- 参考信息 -->