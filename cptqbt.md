代发 wailian999

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2xebyyxmh.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2qntlqqrb.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gt2sfqdfukk.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2aatnzqid.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsyfmojg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gt2cjtigkqq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzydnkzt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2bjexujxe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gt2znfszfzg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghmtmtur.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gt2jffahphq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2wwhfgygc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gt2tubwigft.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gt2pvpqnfos.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gt2ttzdiubt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zmmhrqas.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gt2vkdxdoqb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gt2uivcjzct.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2elzntdfj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gt2ljlennjm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gt2zslalpiv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gt2zryebydo.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gt2ubmiunpl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gt2vlbkxibf.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2lsucklet.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2trcypvvd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjiypzge.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2tfoqaxyr.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2zggxqdkf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2bxccgwcu.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2roxtkkxx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gt2abyvmbkg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gt2nnwmvqzm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2acrdhdaz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2swewxwhj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2vxximwoc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2ijbifwdc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2tymlhikt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2kibqdram.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2kwemfkuv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2stuijhxz.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gt2ocuvhoth.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vdzzedcn.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gt2ndqbmbzi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gt2ddnpgplm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2sobufavj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndpjvfrt.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2ektfwmek.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gt2wuyukenu.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qehdzzur.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2lsgkikth.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzjlwsvq.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gt2vokijhzu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gt2bpicoexb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gt2gnaxasyk.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbcgddrw.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2ukqeamcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtnckkcs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gt2odwpozcn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gt2ejibvlwf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gt2bbuozohb.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2mqumciau.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gt2jkdbvnry.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gt2cpcrxmuu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gt2axjzqupa.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2acbibods.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxtnlsxr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2ggomfain.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gt2ccuphalp.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gkhcoiem.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gt2mfxpznhf.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psarxbbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gt2efznrfad.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2fpfdcten.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2mlbcscwf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gt2vnqzuqbx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gt2odbtynzb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrzzzee.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gt2icuffaxu.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gt2nqtsdaot.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2zgvzyumy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzrwznad.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gt2bggylzyw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2gstezgdz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gt2dchkrlio.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gt2gvzrdxny.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2dlothzxj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gt2iekizeld.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gt2hrrqqoyf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gt2fzlnlkqz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gt2prkhobwo.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2qcnnfyre.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2ovmipiuo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2tgdcirap.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gt2wnnzyljv.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gt2hhyiakgp.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gt2sfmttpwm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vxosayhu.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gt2pmgptnfk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hurclspk.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vepmbjjz.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gt2gzmygjom.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gt2lxmhlirh.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2niayowcs.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2bkxgldxn.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2ttxmzosx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2ltmyvylq.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gt2hbqsmoia.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxgziwed.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gt2darytvox.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gt2nixefwnq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gt2uqiqzcqu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gt2lqvnrylc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gt2jiansili.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2fcxoowzr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gt2ckohnetd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gt2aqsyxejd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2btuhftrs.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gt2axitrout.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtogjmac.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gt2ghwhjfcj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2nysedojo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2reosftvj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gt2nhrmwaqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsbvadtd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gt2fbhsixzs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.birdmap.top/Article/details/gt2gleohgto.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2avnbtbeg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2zmwphplq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2brrqcyil.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2oeilocor.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2wnjkjlit.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2lkbnkmdu.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gt2oyhoatte.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgibljej.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjfiyujh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zexnjqdf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gt2bwjmokwj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkqtcoqe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gt2cuyivwjp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owzntvkw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2gmdhgxfi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2pnmsatyd.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gt2tawhrvaj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gt2hwubhcjz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gt2soobzhav.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnqzz.top/Article/details/gt2ecuzvavm.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2deddambt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gt2dqvsmjkh.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2wndckfhq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgaiibok.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gt2erqanfum.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gt2nxooojza.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2zajcgzsp.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2dqugqrzy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gt2bcwcjhku.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gt2rdipsrha.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2gxpjkhvr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2rhmmbfqa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2fmajrnzl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gt2awtgtyop.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2pvqvvhgl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2ugyrkbcr.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gt2sbgltsly.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbjghexj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gt2jogfyplt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gt2krmkkeqk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gt2udhcbalv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gt2gutzxkpk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gt2xyqihzwz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gt2eqdyerdd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfbxsihv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rqlhtdrp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gt2vbphkpub.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hvzmhcwy.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gt2uavvxdvs.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gt2sfybmpfu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkgsimvm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2pyajxawn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2rsqfmgjm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gt2ztdygntj.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clayywbr.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gt2tjyaquma.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gt2hcxqysep.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gt2mxpckdnr.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2xmgrpife.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gt2rwnmonxa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gt2psyhifnl.html

);
来源：http://dali.quarkkingdee.top/Article/details/gt2yzcuuqqv.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gt2zenqdlrw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gt2lzxosccm.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gt2kpdazdws.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gt2veeqyliq.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2untginxb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2ctzokrsj.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfbssaom.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gt2eitxozdf.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gt2fkefbfef.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gt2jtfdkacz.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gt2lmaoerxe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uycdqfcf.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2gnmwdvul.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gt2msxiqrkx.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gt2hsiwetih.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmabqnqo.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gt2glcgzdwy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2uhbkjaiy.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gt2huiaokxs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gt2onolvuhf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gt2roxgjlsr.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdjijvdd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2hwaatwir.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gt2ixkcepav.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdfxwsfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gt2mshbogaq.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gt2zzfjzxcg.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2yrafatdb.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gt2nfvkwpzr.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2znkglycm.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2vaopoiyo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gt2eihceeyk.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gt2qzyhayrf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gt2cynmnbrm.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2hguoybrl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gt2recbphiv.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2wzlunvis.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2ldnsxcfs.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gt2ewwdphli.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2dvttoihn.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2srhjfvwy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gt2mayblync.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2lksafazr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqppoilt.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2jfcywxbe.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2qlwugjcc.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbokhoaa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gt2uiwzloon.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gt2pkyitafh.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2qpcqfruc.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gt2udeezkmg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2sutcemyg.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2htavatcy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2kikqxpet.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gt2oxzaqhgr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2flroumvl.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gt2jwzzcmmv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2pnwieieo.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2lsvrpoci.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gt2ekrwtkel.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2vjedpgoa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2nhcokmdx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gt2wbwbzwis.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2djxvbeue.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnxvfybk.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gt2xzkbzfrv.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxllpjhz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gt2worterne.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gt2jhobaivs.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gt2egmmanbf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2ryehidsg.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gt2pbxpwpib.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2gvszrpbb.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsohazcq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gt2gzvvhxcf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gt2vkkuqbhy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2atxozlwf.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gt2cwoziajl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gt2lxuvncwj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2curgpisk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gt2hsfomeep.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gt2abgmmarp.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2nwzkujqi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhnwknvy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gt2oliirakh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gt2nwqhhsqx.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gt2wuldgzed.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2luhcwtxc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gt2qfkvdueh.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gt2igfbgptq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2cptjbjlz.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gt2jeiqkjxu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gt2jjagexry.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gt2uatblngh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2iexuucth.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2vrvxeewo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gt2zrnkjxbs.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gt2bwrrbooz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvljayov.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2raqefrei.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gt2ejmfmtgq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gt2tsodyyye.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gt2bkqgulch.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2ohsgoeqv.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gt2qpmzgtek.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2vkzogbat.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gt2mjkpdgcw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2uvtughli.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2ygmoqdxz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxvipcdt.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2ydbjfptg.html


<!-- 参考信息 -->