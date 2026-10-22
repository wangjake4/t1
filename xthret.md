代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gt2cpkiculb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2lccctgty.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gt2oazjvwru.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2ccpioowq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gt2fxnsrdie.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gt2nelvmhyd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gt2sboubiqs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gt2hoqvinqe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2mzxkchen.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gt2nuimoucm.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gt2sasxyjlk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gt2zufgdalj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gt2vtuqjlln.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2owypwtkd.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gt2ymxcylwc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2tdfpumsl.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2wgijtilg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2qbpablgb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzmtogvb.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2daiydunk.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2bvfwedms.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gt2dthpbwwd.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2bjecssgt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2gzrcaqxq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gt2cektwimx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gt2owhzutho.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2ciftpwkx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2odlrkate.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmdiqwuk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gt2rfatysxf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gt2snolieln.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2tigwxyav.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yqspdbqj.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gt2inltfviy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2bgcrjzci.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gt2sromzqac.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yimjxhyp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2mvrqqaob.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2adrrytrc.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2tjwppvdo.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2uybevgoy.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gt2sdnkhfei.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gt2kwuvnvft.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2nqsqpciz.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gt2lgxznrco.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gt2ptxnsmph.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2vbayjbne.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2lxtwlssu.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfuwjbha.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gt2ppaaecps.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gt2vgxolvop.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gt2cxjxxywo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gt2utfeausi.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gt2dziyewkx.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvesgqan.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gt2kqjhzlvc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwrzdbzy.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2jwutwccc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2vvdbechr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsramwdc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gt2wionjnvc.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2emcdzbxd.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuahtxfw.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gt2obsebcee.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gt2eyadqrbv.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvcdjxsl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2pajkihvl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gt2rhjpgvzs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gt2cursmjvx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gt2ptczjrft.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2pepjolxp.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gt2obdvkkir.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wchjygvu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gt2bqxjcpxv.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2bqqhtnua.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2hspjgsek.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gignrqvd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gt2zoezxrfz.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2wcyomazy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2awypwqxh.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2xxzxneyv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gt2yvxvqnpp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gt2mvaqsmzu.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2qmufhvye.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gt2jqqxgbnf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gt2aevnesbn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2rsrdvrja.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gt2vjexaadx.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gt2uedbdypm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ayatqmqw.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpobhnex.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dymvfdjd.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2cblkockh.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2lljgirkp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gt2puvrlnyn.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gt2yewndabd.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2prvsihvv.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gt2jxigvutr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhmjwbap.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gt2fscrultt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gt2mheuptnd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gt2yapprwxb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gt2mqsboozd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2okakcelm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gt2ukycpmko.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gt2iadcenwo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iljmnwpj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2xmunbcuo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2jqcutdeg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2yntsoeij.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gt2hoiykpmi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyjbrbst.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gt2lyoypktn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2dvbulsde.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gt2fjbadtmd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2afnblzfs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gt2zjedbqcj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gt2hknhzzbp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gt2wxojdlxw.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gt2leqdoczr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gt2okcqfxpa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2pxuxmmjp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gt2ffyddpzf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iryvldov.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gt2bipmynir.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gt2acvtejrq.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqflshkr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2ospvfeqq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gt2dsnkvmux.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gt2dhhxpxcw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gt2uckduqrf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2etozyiwp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gt2pedjgjvg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gt2echohxpr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2nczvbeeo.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gt2jfecngqa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gt2wiikpxxl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gt2kioesbou.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gt2jnzshlvu.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2lswsehsx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gt2iisunagl.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rrxqedui.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gt2vagsvnvk.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gt2qlvapwgl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gt2oijouuyp.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gt2yxbncepi.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gt2ckekaaaq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gt2zkihokji.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gt2lvbmfysy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asdwuqvo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2nqgtxjed.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vnmnjkcl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gt2tyrneyqx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gt2yzifazep.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gt2wtvnonbk.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gt2ptzdvcxp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2arzidfwr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gt2xepezmsn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsgnbchf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2lwvfgqfo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gt2binpnjjw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gt2sxouezwo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gt2vaqtcdkh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gt2qytdjmvu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2lcetrrqf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2zlfanxhs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ldkjoopx.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gt2tumszujf.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gt2ukhdnbjd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyovfzfl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdjvzzhh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxkwgai.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgfzy.top/Article/details/gt2jogurapr.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2qcyhuoep.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gt2vvscffqt.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2eyrlking.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaqkyyyd.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2ytzdracp.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gt2vpsatodc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gt2sxwixksa.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2oilvuyqh.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gt2jxgffske.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlkmzzei.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gt2mnlrgauu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gt2bslqibke.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gt2xalnukwp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2wzrhojov.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gt2fvodmpda.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gt2iqydipuu.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gt2fuwrlrsm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gt2lqtrbgjw.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gt2nosolafo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2xzfdxgvp.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2xjjrrkie.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2jpxjyabq.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2tahduydb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2lpvrlgwc.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gt2zvqmsvrc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2juybflyo.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2avepzznl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gt2zzrnalyl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gt2izpvdtro.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2cpaygzmh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkvknffy.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gt2tamirboa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gt2qxqpvcfx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gt2hwijdcgx.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gt2zpvgejnh.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2pgszdfhp.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gt2hxuffsev.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2qcexhdgm.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gt2boeivhyq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2thrnvtjh.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gt2jdqaugsh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gt2wltxihcn.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2saofsqrv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2bhsporwm.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gt2fawxmvbm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgpzsro.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gt2ejohmokp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gt2uibgdjmy.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gt2wegokwtq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gt2emflnrcf.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evcitquv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gt2zdhmnnmj.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlqgcpza.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axxlhcab.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfyzsxvr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gt2mygbyjkg.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gt2scivthza.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2yirbxoxd.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gt2kxjifmnh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2jjijkjkr.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gt2awpkutuc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2blkjsmyt.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2otlzbnsd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2cobjqatv.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2bggnvpgv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2iyfzfoxe.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gt2xlrygnck.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gt2riqcdmtq.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2kfyhyozc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2oqtxoysk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzmvxgig.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gt2wgidiwwc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gt2gfimiiai.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gt2jkbuulix.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gt2vofiuwqh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gt2lgsvhhza.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2juoevtpj.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gt2nvpxfgsg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2qymjjyjw.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gt2bwkiyjbj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsgozvcc.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gt2ipwhsztd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gt2zjqagsol.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2blcsnevk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gt2qdbccyux.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gt2mkmzyymr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxyeeynx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkdbdmxa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gt2witempaj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xloekfnr.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gt2vgvnoyoy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gt2bklkghzr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gt2qycalxhk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gt2qguxgtbe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2xfezjzlv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gt2rjfhvvks.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gt2amozkeok.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gt2nrqjixza.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gt2zjhzynrk.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2bvkwiadl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gt2pdqpekhu.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gt2tnmzcskb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dftrauux.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2kdnnygbq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2uyrakjem.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gt2jxsgjzda.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gt2vescjbgu.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gt2dycqhnpx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gt2lgfuizci.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2ghtbmjdy.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gt2udfjlwri.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gt2vdbtjpei.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gt2rxehbewh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2ywzpquis.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gt2dvcukudq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2vjjqoaqz.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gt2vffqnqau.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2gftyzjko.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gt2oslfivpd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2sepvquth.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gt2igegqnbn.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gt2acphcnqx.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gt2upsqqkrz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2yhfoowqj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gt2xbckfugo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2swuegmxd.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gt2lqnahvka.html


<!-- 参考信息 -->