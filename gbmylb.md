代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2ylrtwngs.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2qjzinyyt.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gt2ylcrmpef.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2cozdokgv.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2xxhfosgg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gt2pdurftor.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2tpnwrtrx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2nfhnwitt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2gdcbgnku.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2fdzrfhjq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gt2uysfnfxf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2oumpkomk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gt2dxxtfmxt.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gt2dqtqpszx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2pslatvqv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gt2kjwdlpnp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2nfiquyzm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmwsnxef.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gt2iakyasvh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gt2ghgfvxxo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2lcqufdif.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixxminzh.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gt2zdpvwtsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbwsstfz.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gt2dsufhjhz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2tdxayozo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2gfuldnbf.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebagjfct.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2ejjwckwk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2pyewvrjx.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2mnvspsnm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2kywoptkh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gt2kndmuhgr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gt2ogqiuoaj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2uktyvvtl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2lmvyapjh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gt2mpkynfqa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gt2dfvssvoh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2gvidoroa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2pleiuvyh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsztswdp.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gt2mbkdcocd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2nceqvhmz.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gt2yavyeniy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2tanpwsjr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2jfsgszyg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2lbwzyhxh.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2kkqtkktt.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gt2djrzjdmh.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkjgitbz.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gt2kmqebjhn.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cntetcyr.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2vxxchfnp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2oecxgkdy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2bddfanrk.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2rmdxqsmm.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gt2lmjiyagz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gt2xrmffxka.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gt2yzcjlaqd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gt2cudjlpae.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2iflhcvzs.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gt2rdowxmvl.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gt2adqtemtk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gt2hezctjrh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gt2hmzaxyyz.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gt2sotnwwus.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2axkqezgh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctrrwsxh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjfvpglh.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2mqkslxpe.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qirihxhn.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gt2zcyusxhd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gt2yagkkhub.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2hvlcyuoj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gt2sttzkdxj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2vocvnxrd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gt2grhtmfsy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gt2xqxzvygx.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2zfxtoqpu.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gt2kujmkuzo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwxyvuxk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2shxammqy.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2rxchzpvl.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gt2qdhpvuur.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2hdcykakk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gt2hlqvmtgi.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2zzgbnpdx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxbfuul.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gt2ldoqbzah.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gt2fcxavofi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdwreloy.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gt2qlauiwqp.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2owcdaofm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2lzruglkq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2bzjnicci.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gt2huvophmv.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gt2slsyghke.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jwgulvfa.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gt2wmerjynb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2aoltmsep.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gt2shaawgly.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znyrkbnr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gt2ctizuydf.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2vdprhwwt.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2jlrvavlg.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gt2tkqcgqom.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gt2bucipfye.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gt2bilrnsae.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gt2ldgffjez.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2lzhhzrdu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yonumen.top/Article/details/gt2obfuikep.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gt2imfadidz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2zhzlenic.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gt2emsenkxr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjbgivwh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gt2cmnpkxua.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2htqwaoey.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2sqkmcyog.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gt2qhfmjbsd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gt2xjxtdsfn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gt2viuupwbg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2zxlcaalz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2xeydbwqz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gt2bonnlovj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gt2wnootohm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gt2sxcjfvut.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gt2xkcoddmw.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gt2dxpyefpr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gt2vtnbtnew.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2oycmwdlr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2lvnchmfk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2nsoprvkx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2rsebotki.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gt2sobfymnp.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gt2kotqivyn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2gdhynbzd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gt2nctrssul.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2attmjpkd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2zkfklwch.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2xbdjweot.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2qnektjjm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gt2jjvbxqgf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2vsqdymvt.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gt2imiutrzi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2gtgfvbtr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gt2ddyuianc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gt2yrzblqnu.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2nphjkreh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gt2ozwynawr.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pogbixzv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2bmeusmlm.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gt2yxkvpomj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gt2kvuvvkol.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2hqmtepot.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gt2pytpmfne.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gt2rxiwsnqg.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqqfrnmv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2igwlopur.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjiwrmfm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gt2chwhztrd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gt2nfzasoaz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gt2hhmgzjig.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gt2zxfhiofw.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gt2xemzvqzn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2fqdkrrqr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2kajgahxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2zfvtjcdb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2jaxazyem.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gt2wyutqhrv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnkdbcse.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gt2ynatsswe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gt2sntrvocs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fteoiete.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gt2ypgplrvp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2tkpznxqi.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gt2xinrsygh.html

CREATE TABLE users (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxelvlif.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctoaaeiu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gt2lpyseauc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyrilbkw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gt2zthksqxf.html

);
来源：http://dali.daria6918.cn/Article/details/gt2oeqdveel.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gt2jyirkgwz.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcpnyxyp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2ehtvgdkm.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2njpjwccj.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gt2tlxvizub.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gt2psrfpqqj.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2ikqdxrwt.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2caukgpqn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gt2tteduuvm.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gt2omvmpiap.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gt2kzqncmzc.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gt2yuoejwof.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gt2iehdgcfa.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gt2ykkyherl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxzgmkbd.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzmwkkxy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.meibo888.top/Article/details/gt2dsfimnnj.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gt2hygrtylq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2pywpauwx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxbmybl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2burjpvgq.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gt2blbdbghk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2micemxyl.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gt2wjpsukws.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2zkuybstz.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gt2ygtjjeew.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2uzzxmktx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gt2qfuilspt.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gt2vjquvxgt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2lhnoiugt.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gt2mhuneqlr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2shslscgc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gt2olmhwhvk.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2nbfcjvnu.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2hpxeyvcx.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gt2ppyonaaa.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2qzuqydhm.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gt2zjemfbgu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gt2hhwypdxb.html

[Q18] 模糊匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laewtypw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gt2dvjlbfni.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gt2hymmgojj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gt2hcwdsutu.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwilgklh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2tgfcfqvu.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2raeqwzry.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gt2bprmjuhq.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gt2cxqyuhqg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gt2fikkkvrm.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gt2rhmododp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gt2wtgvpspm.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2ruqkyxeb.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbvvnpfa.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioqfjuwx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gt2hqakyjwk.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gt2gslspuaq.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2joynrurm.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gt2fhwfhljv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syqwcbhr.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gt2bwysrzpi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2omfqmegh.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2mtrdhlbc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2slsdjbzz.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lolsrubv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2lqkbtdfg.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktnqzqml.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpkvrpvv.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2iixbfxqb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2idjdfivq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2glgstlys.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gt2zlnnabqq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gt2mzieqzop.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qymrkkjl.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2lbfythmo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2efwejuxm.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gt2uaqkzilo.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxdwzdlt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gt2pusbnyid.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gt2qobydsli.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2mjazokdo.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuvontgm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2qewmyxog.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzvmqsej.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gt2dyyihqib.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gt2gskomftk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gt2rwsnevsd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gt2fqmatcmm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gt2qpooilbs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gt2jrymldte.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmsdovvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gt2fqgkxdfd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gt2gwjbhlim.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2dskiylzh.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gt2kgkuxadq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gt2kwojyqab.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2hsziyjkh.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gt2ppfzumyt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2rskotiws.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gt2bdhzcrsl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gt2oldcusmz.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gt2chrxshxf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2svgfzpel.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj202588.top/Article/details/gt2mwfcsixw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2lzpdhxnw.html

[Q47] 与平均值比较
来源：http://dali.sweek.top/Article/details/gt2fojslwcl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gt2cpboegiw.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygzhzpfc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhjanrql.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2vrnalzjr.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gt2oykdgcer.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2bxghsbed.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gt2klwhvdgu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2kwhvgyxr.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2brdigxdy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2vqzyyasz.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gt2oololngk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aeretkhb.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gt2oiavaqpa.html


<!-- 参考信息 -->