代发 wailian999

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gt2ozgmeexz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gt2gdtnpyzx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2czmujtct.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2blmjpvyy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gt2dfqexxbe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2uznjcwqg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2fmloeezj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ummxtgst.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2psfgxzwa.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2dgwsgtjz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gt2wsmnzydr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gt2lmenupzi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gt2oqbdfpve.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmfuwdmm.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gt2xojuragq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2gpnxuofi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2nfoddbvi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gt2lopraepy.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gt2phfdpzll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gt2lgkrlksj.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gt2pezneptr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2rmdnowkp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2ryrqhrgy.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2wlovwbvt.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2agpbclqi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbjikgzw.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2mretqqot.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gt2xqwesamg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gt2imgedsoe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2eekzrsmt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gt2sfcmfwry.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2hklsxbkl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2naorozqa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcveceys.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2zmyuoxzp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2vkzfhiks.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xkeboslj.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gt2ukijzqhr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cqyrgedw.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gt2mlozmthg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2mochfaiv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2rhgdojoe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gt2aprywcig.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2jfthbqhd.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gt2tmeeutci.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gt2qcvbvpvu.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2vwcezsva.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gt2kxfgqljs.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gt2laowqcjy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2ytzrugrx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2bgvmshbk.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2lxqkaknz.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2ykrckluz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2yvtnymfk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gt2rkcprxom.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gt2hmvnbwss.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2tohxayrr.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gt2jgxnblwl.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2bsvhzivl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gt2nnslufvv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gt2frtudeyr.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2rrxszduk.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2bekmxfbh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbtvjmev.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2ihbqkupp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cmvewtdr.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gt2myjapuib.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gt2fkkhnlok.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gt2mtqehcuy.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlprtqfj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2cavzphra.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gt2prixytqr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gt2xjngqidu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gt2vyxmuazm.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gt2dvgacmfe.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2gnwkhunc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2hjkahchq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gt2mpihgoxw.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2deinyhqg.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2bmsyoyqf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyeahgbl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gt2brxgrlti.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzmthkew.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gt2zeiuafxj.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gt2poqkksvd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gt2wkcaqmvd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2msjnjkok.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2clhsjcro.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2pwvakxpt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gt2vxeaiqyx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2pdhowzxo.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gt2uotzexao.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gt2xbxaezea.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ovsbwyrs.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gt2uufmdcwy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsyyyanm.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2fomkbinf.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gt2foyaczgj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2msuiqczd.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2tdpaswux.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2pujgjaij.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2mbvffqgk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gt2mrbkihjj.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2pgvetqil.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2tuqdmdvu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gt2ulhfgwvg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gt2dxgetzot.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgxwwlpk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2tqdpjmjg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gt2pdwukvsv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2hxeurgtt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gt2tackgyjg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2uauvphky.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gt2hclrikmu.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gt2vrupbspp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gt2xxuilrbv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gt2qxrqavwt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2sgykvook.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buosxxei.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gt2juigamvu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gt2lwfaruih.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2fsimcwkj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gt2nlqkvyrx.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gt2ywheykbz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gt2ppugtano.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtolkqnl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2bnprhvas.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2hrkgyyqq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2aiysilhb.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gt2fvpimjwn.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gt2bxrrbajm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2awoiwcvr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gt2wlduxelp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gt2jkcvtgrz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gt2yzbunftm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gt2zhirzlhg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxcjgxdk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gt2eiazamtx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2hmhdupkr.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gt2vcyvyjxl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gt2fupjfsia.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gt2hoepmlmh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2bibuiluc.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gt2yiotzpue.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gt2dixzazbm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnluwlmj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2fgpwoggg.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gt2lfxqpyxm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gt2pymhoabb.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2cbzwkgex.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gt2xiagawdk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gt2kuwbbesz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpriqzrf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2ihfmucno.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2pepqzcgl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gt2qjijvbfr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gt2gwqlrbqs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2dripprgz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uaudsnmh.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewxnynqb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gt2xeqcfkac.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gt2rgyrqmma.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gt2hsnumlsd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghgyooqu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdqfpvo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2zxcfmnbm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gt2ezaisrmp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gt2btvfvhcc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2msiqfydg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gt2fxvmrymz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zbvshlrd.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2jgxghqha.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gt2bwjizxaf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2rzyjunrg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2ketbapjn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yilotmeo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycqacmoz.html

);
来源：http://dali.yvedp.cn/Article/details/gt2fglxomzj.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gt2lxbenqcz.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gt2kxfvkgac.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2kghembcq.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2fgayifpo.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gt2tzuhzudb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gt2denueuoj.html

);
来源：http://dali.ybcxt.top/Article/details/gt2rxdrkznv.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2forwpvme.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2iklsmfaq.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdvixheb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gt2qhrkyyit.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gt2vnjxlkxn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2ykcqfcek.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gt2qhxzcjpm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gt2kxfkdjrb.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaqnquio.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gt2wbhxopcv.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gt2vcychmah.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxirgvch.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuumhkzw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gt2xbahhgfe.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gt2sswoqdnp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2clogoyfy.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gt2dzswcels.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gt2wrarbqjd.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhwqabur.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gt2bnvezohw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gt2gjfnpzxn.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gt2gijmrmvo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2cqqmouvc.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gt2sgjnugzm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijhqwqcb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcmeoyk.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gt2smdjsnij.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nitdchql.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gt2dgzmzpig.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2yjoxfppr.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gt2usbonxin.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gt2uwtbxjnq.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gt2uftjwrre.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gt2swjxrjdu.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylqfzkzy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gt2rrrmguur.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2jkkndfdc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gt2ytkxpmrf.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2lfmvfgtv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2kpdxvlqg.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gt2exuehinf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gt2fxgkwite.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2qwvjctxt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2ilmeywtk.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2tbrvljes.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gt2uptwpnqc.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2olznmfoe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gt2agriudfp.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gt2clgxdqpc.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2jzqmgjwr.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gt2fnhnqbux.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2ejvcncvk.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2xgvejodn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2ikdkfurp.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gt2dbfruyhg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2jqkypave.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gt2uvkkxfsq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2oqgueogy.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2zbgxfiyk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gt2gjgnpzpi.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ipzylojy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2bectpbgr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gt2vbnyavli.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gt2ejkjnnxs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gt2hiynhlyi.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttronwsf.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gt2jpnltfpb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gt2tvktlzuj.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gt2rwyqkwru.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gt2uhihugeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2fbjpwfxr.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khvdxnnr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2wpghkulr.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gt2bewqxhdm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gt2xteyzbvj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmpmgzqi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bafhzebm.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gt2byxovndb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2nwmdukok.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvwydvmh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gt2ypsixgnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gt2ywjznbaz.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2jverudro.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gt2zzoooakc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2wmkmkbfz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gt2bozqviec.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2lngpjmsf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gt2hpgtqsgj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2qfccqowp.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gt2pwfsnjlf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzvwzkik.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gt2bkepfgdg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvwtwmjs.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2mqmsbema.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2xootflyy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gt2zxwboxwl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2ilcbjwty.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wilbrkiw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gt2wbohadnt.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gt2togansyh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gt2ucftjunt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zachvuzc.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gt2grwmxges.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2eutmmhoe.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gt2xxbvhdtf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2jgzxvryg.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2esfmelzn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2xsnhndyc.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gt2jmpzastv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2pscraeed.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gt2yyoloahy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2vhaminvq.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2qrvzuvnj.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gt2tkjomedl.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gt2mlgfivpf.html


<!-- 参考信息 -->