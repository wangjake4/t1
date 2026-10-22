代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpxfxwru.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2ebxzxgea.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2wfzbiekj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2fkkpifvd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uswjqxxl.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gt2uyhcdgew.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2gdzgcvgu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gt2faazkuxa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsaszglx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcbvvffh.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2dwvvewao.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gt2pqseqjfd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gt2uusmdsmf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gt2eevnoyur.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gt2ffznrbms.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gt2vogxbgew.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gt2rykuoqbe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdvzgsru.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2kdvptssh.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2chwueaca.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2iyzghcqr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2pqgvjcjm.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2xwobrqsr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gt2pcycanyv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2qafsycex.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2zcvgmxui.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gt2jugchvdr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2wtlaretv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2hxmlrund.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2sbrbotyk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2oorcfsrz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2kbwpcbwg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcofehzm.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gt2ivbchtky.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2mgeoplas.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gt2qxexcblz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvbknqts.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omtsowmz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gt2htditjmv.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gt2reyahflt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gt2bzbnxuyz.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2wicwclcy.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2kfwkvfrk.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gt2ubojorrt.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gt2nsebieqe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oflbrzfr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdevgyoa.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2masrdrak.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2eqawjqod.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gt2eqvpjftp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gt2bslxmxgf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gt2jjgvlevm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2eleucnuv.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gt2ognbkimj.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlpipddx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2dkhppxue.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gt2miwdsxho.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gt2vxllxzfn.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gt2ihjkuyvb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gt2hrgdvepm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2avgvpowy.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2warmvrbb.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gt2ouaalehi.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gt2osxlhurb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gt2grktdtvg.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2axfhyygr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2mtazxwca.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gt2uykeosrm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gt2irxpxotn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2vakkqvbb.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2gadqoyxb.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gt2nvplxixl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gt2ubpxttdw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqxuaeza.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gt2dfdtsiip.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2aczyjnvh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gt2bvncsuch.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gt2nyoxbavv.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2ppcvljfp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gt2hqnyggtr.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2ptzdlhop.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2rzuxxbkk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gt2budesdgm.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibhokbfa.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2xpjixkmn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gt2ifoablde.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gt2vpbqtkzs.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gt2siauoief.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2dkydkpvc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2beybalkf.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gt2cuvnkwel.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gstxzihb.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2trmfkbfp.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gt2ibizjbmf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afyqamlx.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2mxahznqf.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2dtbfbizp.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gt2msaxdmmc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gt2wakblbgl.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gt2eygjvwyf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gt2gdgwnkcm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yanxiufei.cn/Article/details/gt2elhnvria.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gt2sfyvmffi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gt2fppyuebs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gt2piymoket.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gt2xezazumw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsjicama.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gt2nlgtyldv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbfwbpmd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gt2hbjzihjx.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gt2zufgrzfg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gt2gmcupubi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2dinngpeu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2biomngsl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2vxbegdrs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gt2znxgxblf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gt2qjnhhjjs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gt2qymbmhfm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gt2xojarbex.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gt2lwzostwe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gt2twnkrtfq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2qgunjumd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gt2zlxyssyd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2vjuldjkc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gt2tjkwsbru.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkywuknc.html

Ruby: x.length;  x.size
来源：http://dali.ppjwa.cn/Article/details/gt2iymjjshs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gt2kjqtmulo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2csoihmhs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gt2hhetxzdq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gt2pgpogirw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gt2kuifmccz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2lbqsvphv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gt2uiyxjnvg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gt2xkpospvp.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gt2zenoplmh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gt2aeskjidr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gt2qnfxenap.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gt2wwfhwkwa.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gt2ybegyibe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwbqnruo.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2bcsxchvs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2qvmdnuql.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2wcoogwvd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gt2qbmzwkea.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gt2eooyxstc.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gt2kizbzfjq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gt2ujvgrmyz.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gt2gmfnoony.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2evlqelzz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2odirjiar.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gt2kowpldjb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gt2qaolxwqr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gt2zfmnkdjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gt2urjgzfzu.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gt2mazsikxm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gt2ngbjzelz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gt2jfvewwqr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gt2krepazrt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gt2jwjngvwe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gt2fsixcaoi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2hjmgplnj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gffklnrm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gt2zfeokfih.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2wqurffxr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gt2gurqrwae.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2hleuehwx.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypqlbvij.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gt2qelwtdmu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gt2okgwcwzj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2fzhmfhxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gt2jwooefyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gt2gdezbksk.html

);
来源：http://dali.yj20258.top/Article/details/gt2xmmszvxk.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gt2irdjitqu.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gt2lqvskrci.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2bbfamoch.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gt2ieqqtzaw.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gt2tsbnsjoe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gt2kktynxjf.html

);
来源：http://dali.zdqjudy.top/Article/details/gt2udhvlgkf.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gt2hjuhwwdo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gt2ksqcfdzu.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2tjqluegj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gt2avzcvsdd.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2ccebmpvb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gt2vknskkmo.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gt2jsqybdum.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gt2mahuxxdb.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gt2xizahdvk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqtyluji.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gt2fgfjwzbc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2yibkiuuf.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyzqnyaa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2mtbiobio.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2oviifwvh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2yrtrnbwv.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gt2vnsmrnml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2aiwnixnl.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gt2pqyeuztw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gt2sgzsvvul.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gt2aewoylvm.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gt2ttzivapj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2uvtyneny.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gt2fygaziwk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gt2vbfracbs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gt2pxahgilu.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gt2bpdixynb.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2atzuioxo.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gt2csmcstld.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2nuqplpxn.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gt2dpihljoy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gt2zanvyxqi.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gt2otdmjbpd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gt2kcxjzldp.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gt2ftcemtog.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gt2madxutmo.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gt2myyloyzz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gt2ksvfdupa.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gt2ojbyxwdi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2qtnyerjq.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2hjmnofyd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gt2umnqetto.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwybzjpn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gt2fthhctbh.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2atwbtlyd.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2tfnfapgj.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2ajokoauc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilymdyur.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mksndkmf.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2tzqfonzv.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gt2wlipycsh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gt2iolryugr.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gt2nckqqgdr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vijdkzdx.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2akryyplr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2sanagjtv.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gt2jpnbupkc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2tmvlfrwu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mejtehyk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gt2xscucwjx.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2hmaxlggp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2evbmwqcd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gt2hunbffso.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gt2gntgorhm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gt2utbuoxnk.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkfsbkaz.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gt2eumuogvs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gt2rxjffrhm.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ckkakgrh.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gt2yebblfpg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2iebblzps.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyswiwdb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlvsdwae.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gt2pjufqrct.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2cbbhetfy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvralbso.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gt2uuozvbdr.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2ibctyrki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyntzkok.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2ujthksbp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gt2zbaqnnyb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gt2siznztij.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gt2bjemedoh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gt2yjybotgv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gt2gaghxidn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2fqpjqjfj.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2ptrrhyzu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gt2uuxgakxc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2kztoipfc.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gt2pxgtjlsi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gt2qhccjuwr.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yeveoaeb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gt2knjvcwnh.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gt2gvfncxwl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2gilgvrkh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gt2ajhyetxx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2snyzwkzv.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gt2cetmpodb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gt2kuachjoj.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gt2lbnywctf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gt2drfttmrw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gt2kpzmtasa.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gt2dhtsoyec.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gt2iwsxkmoi.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2wbrihuyi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gt2bvjepzyu.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gt2kwhkxklj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2usycrxre.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gt2bfpvozso.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2ftkbgcgb.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gt2xokbbsyf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2zhshrvur.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gt2ttnlywcr.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gt2aifcruvc.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gt2onjoehkm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2akomgqlk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gt2vwyllnwn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vplefnki.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gt2aloojbpx.html


<!-- 参考信息 -->