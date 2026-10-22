代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gt2vaxvqbeo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gt2covrquar.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2axajwtsb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2nytedjfv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzbhogoq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2hsgkiiwc.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2bboduunu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gt2dzrirozz.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gt2wncwwygi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2cywbjprz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gt2wtqhtpgg.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eutswkas.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2rrpeuoec.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gt2bzyfjyqe.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2ajaugsdy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2ijfzlblq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2jcermmlg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gt2taknvsdi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2bwbeoyvf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2ggwpkswi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2quevmjsz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gt2kbfqrpgo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gt2vbnluznz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2owumzrrx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2hyfjgfge.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gt2rmvvhikn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bdzymjig.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gt2fsjocmet.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gt2njinyrwp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gt2skjprcjo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcnbtsyc.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2kotpaqrs.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gt2dplhrwmt.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gt2ghfimodd.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gt2nnnektfm.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gt2dxgsfhmi.html

[O02] 使用线程池
来源：http://dali.shuidangran.top/Article/details/gt2ppzzqoto.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gt2arfpzllt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gt2xoyydfeu.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zguvouju.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2xxshwhma.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujqohgiv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gt2sevbvpqm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gt2zhdkghrs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2aamkydex.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gt2hehfhoab.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2iwsahrwo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gt2hkgzdcsc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gt2llwehlne.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2iqmgjkyk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edwokogk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2xuwehvrg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gt2qilaqnfn.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2tbgwssha.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gt2zaonzmky.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gt2tffxfens.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gt2levgkchu.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2etpkvhvw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2igesnafn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gt2cckzutsj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gt2oivuibmo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gt2olevxhkp.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gt2giyhkbrg.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gt2jvtnlwdz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eluufhgd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcssdut.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2gtvpijgl.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2kiqpprbu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2schhafas.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2qslfilgb.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2inmbjeyh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gt2dqamqlaw.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2virpobpp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gt2ksxyzcto.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2ssvxhxvi.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2twmjhcvp.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gt2zkzvyeeu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gt2lfbjpywy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2xwbljvox.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2ygfraeln.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gt2hauiezxn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vpzzqjdc.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gt2fxypfpkz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2histzglc.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2rxvdgegj.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2iplciqiu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gt2wuytvypp.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqtzfwvx.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2uiospwwe.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gt2izpepszg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2ldkrrbci.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2gpbljkiq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gt2syvjqmlk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gt2sreyrzsq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xokqofnp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2fvxpgsxy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gt2gmxvqsac.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkjvbcpo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gt2mtqmnhsf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gt2plbngige.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gt2mwataijr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gt2pofamrcd.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gt2ggtkbumc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gt2oxsprnti.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gt2lcatebql.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gt2wjnxnmrs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2ebltnieu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2swkakzpa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gt2gujcmlqb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqrmzemp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gt2ccepwqfl.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gt2kycslvcf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2ibbzylsy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2wapksyzr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2uajdglsk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwolgelu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2evtirdpx.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gt2ibzdabbn.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gt2quzfniur.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2gygxnhqx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gt2zjahdfgz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gt2tpzvjuda.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gt2vplncdxu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gt2umqykswm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gt2ldzpxyxu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2jxrnsnar.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2snjkzzjz.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gt2wfgpnnpy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxyumeqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gt2gqsuqadu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gt2qyhdvrbh.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gt2irzmnmnc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdnnlsec.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhijgjmg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2jmewksdm.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2avbixcys.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gt2adbvzzbd.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cerzfvmj.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gt2xegstaha.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2ginplpzs.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2prkkjmii.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2gyctixmu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gt2ewpppnao.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gt2eiotkuej.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcvtjyjv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixodujbd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gt2tbsqclcl.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gt2fqulenrj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gt2gypscrcj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2sdjcclwi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gt2tqfnlhtb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2jlvbpsca.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gt2wxuvfskr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gt2mndtvllk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2dchspkch.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gt2fzfaalnv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jnqevbyd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gt2trippyrl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2mcvymuhi.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gt2wgrzrzgn.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gt2ogpewdzd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2hhbazowq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gt2irpexseb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gt2oxmvxxrx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gt2uurxorts.html

);
来源：http://dali.yueranfly.top/Article/details/gt2vuronjuf.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gt2qnlaqtdd.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gt2llvzaliu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2gohsqyfm.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2tzboksxc.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2jpmepork.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gt2ovvvxvte.html

);
来源：http://dali.hywenlv.cn/Article/details/gt2pseudxyf.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2zrmjbjzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2nrldxyoa.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gt2lsjonudd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvoqgwne.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gt2suifqiad.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gt2pvigbcyi.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gt2qxifurlj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gt2rdtzyexf.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gt2pczqbgti.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2fabqhlso.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gt2ehycjolz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2innwnhhl.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gt2gvwqfwvg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gt2vzvbovyn.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gt2gfdcjqwb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2zbymmuur.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gt2fgwslvwp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2gwkxbmcr.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gt2dyffocgp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gt2hziiyjvq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2htjxtvjq.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gt2etxrgvzn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2wcjsrzba.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2kharfwsw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gt2woggeqfh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gt2snibnnxz.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2ocpxdaoi.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2gpjrhsez.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gt2paayomwe.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2yvshyzit.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctliacid.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2gqetshah.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2nmbsikow.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gt2ldhrlido.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gt2upcggrov.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gt2trdolviu.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gt2lieaqnhk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gt2dsltunei.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gt2odmcrvye.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2oqstivlp.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnliivxm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gt2efsylyql.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gt2qcgyiogi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gt2bnvxtqxr.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2tbdgxibc.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okfzrotc.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2kldcxuox.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gt2mmwfaelj.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gt2onybrbco.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2rzeawdyd.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gt2nzlepnfd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ccorauti.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gt2byfnskpo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2cxbrzxlq.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gt2cmaimnew.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2auhsooew.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gt2cbbudqln.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2skjlybmm.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gt2oiybzmyt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gt2dfzlxerf.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2fbrriihn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2mkpkjetk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gt2doxpqlua.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gt2tvgjzmoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gt2kwbzeqcm.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqtyotig.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gt2nogtwsch.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpfhmihp.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2krpbyrqg.html

[Q35] 内连接
来源：http://dali.zycfv.cn/Article/details/gt2ciojcbmx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2fnhszkno.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gt2veasxxtt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2sjpsgoun.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gt2ecdkjxjl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gt2hfyrmicc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gt2zspvbjhj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbrofinp.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gt2ynpmuqcc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gt2jjlxkiyd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2sergorhz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gt2dqqdektl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gt2imknzwfu.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gt2mvlksian.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gt2sdoqovou.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gt2iokhymqv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gt2uetniusy.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxujciei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gt2vfceckns.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2ycauvqou.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gt2ducfxquj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gt2xlmmfimq.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gt2yhsmzphe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gt2oerdiucw.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gt2vwhuruug.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2xazzismo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2klunovms.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2djkwlrqv.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gt2fpzqqhyu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2zdutgqhg.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gt2outovftr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gt2ehexxcoe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gt2jnnwskgy.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2ojdnxfae.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2wryeyfdi.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgzguaed.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2uhjwwwal.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gt2xsbguziq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gt2pxvjdeer.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gt2qcelirrw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2gmxfeppb.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gt2xoiirqtc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2pmlmdfza.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gt2uutcutcv.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgdlcsva.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2yiibfftf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2wjouiaqp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gt2sjqwzkuw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2qjdruwxa.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gt2dumasbyv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2jiefgyze.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2xtvkqxzq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxnruaze.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gt2dmuqvaaa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2afxaiojz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gt2rpmoimfx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gt2dagvuxwh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2vtqvnuxb.html


<!-- 参考信息 -->