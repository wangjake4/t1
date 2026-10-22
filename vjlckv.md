代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbneagap.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gt2gvptuawd.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2wvrvmyal.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2pcozmwfw.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2ohwetdxu.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2vnptnnyn.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2jxmperrb.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2itzuowsx.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2djtavxeo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2yetfrthe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2huguhuwk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2iithhmcc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gt2kcdwgyso.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2escxuilv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gt2ppwnrdqs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2kujotvse.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2apbopppc.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gt2hrhjsego.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvkuxecw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jxgbrilw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2afvqvree.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2ipsqstko.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2zxhnelxr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2loakuskx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gt2rdhgxibq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfyovdkz.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjbkyamb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqnoauqb.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2rlkyqvts.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdlcqkwv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2szzhygdi.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2zvemnqlg.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2fdlcjqoj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdxtvdqw.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2fekfozqx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gt2fldzygle.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2flaynhdf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gt2vjorkvko.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2mvwypyor.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2vsueivce.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2yegjezzo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gt2meqxmhaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktkskorb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2lpdhwupo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2yexgfwiw.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dygtnnua.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ksiakpop.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gt2srpcradk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gt2manlerta.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gt2kwxposyc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gt2ljftphec.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2epnnulis.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjcehvmo.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gt2kugdxwab.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gt2luphxqgq.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2cxidvisd.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gt2uuginmka.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gt2vcibxxib.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2ichikzca.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2fjsfgefm.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2yqoftonb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2knwtgxlf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gt2grhbeuhx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gt2bsdlprkq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gt2bnqhfqqj.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gt2zpsqivxs.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gt2gchophjr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gt2agkjhyte.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gt2qorqmrij.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2tedzxeaa.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2uaxdmmxe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2dmmusqvy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2acjttqhm.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2vcowovkq.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gt2odoxxztj.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gt2kecpjupi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gt2gekxrtmn.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2huwctrwb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ydazzbsy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gt2cfnboxgy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gt2atzbaeub.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gt2kohobtga.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gt2hdbifrnk.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gt2luawtloc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gt2tybbymhv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gt2btobnhyw.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2qkhpkobv.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2firfqhwi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gt2grzoqjrg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2cljwdufn.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gt2mtwtluyw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gt2wonryzcz.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gt2vejfvgtc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gt2zjycgrvl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gt2emdgjtrd.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2soudpqib.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2irjpksvr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2sjzmznvn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2eydwlcjh.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gt2ixjdddhv.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gt2ayuxbzkn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2mkpwsydx.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gt2wgarohjz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mifbxlvq.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gt2uczavgcc.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gt2znyypour.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gt2khrjexik.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2pitnsxyc.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2wiemlfta.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2hlbvrcpc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gt2byszveik.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gt2unkguyxg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gt2mwozgjfj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gt2actfrmaf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gt2cvikfmgs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gt2yltuiztk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2mtmxcovz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gt2yedkjbqb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2jlvtbldz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayrtfozh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gt2uwzdbuka.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2cybrcqzx.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ktxhmxbe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gt2qznlhixw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gt2shdqwvdn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2hesqqhta.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2avuewgpc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gt2shnrvuwb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gt2dlpoibnz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gt2hmpreddx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gt2lsxyfufm.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gt2unoorlua.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2sgvxsjhj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2gbtnwpzt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqtzxepa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2zdwbqosn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2hsswupjg.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gt2gmfynktb.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gt2oljqluhu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzkyaqhm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2eujlnhtg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2wynuotgq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvkjeyxp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2zfusllge.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxlmctkb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gt2cbinopxp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gt2vsdzwdyf.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gt2qcwyekhk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gt2nehcssko.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gt2vinkdakv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxjgnzxd.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dlldakkf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gt2xcqrbiiq.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xpgpiwmb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2ogutocjr.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gt2cxxdmdnd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gt2qdherxve.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2wurcyleg.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gt2gsxvuzqd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gt2zkstjoly.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gt2yrylcmmg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2gnvjeahr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2gjfmhnfu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlwhbaih.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2kkugufbo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gt2exmikkmi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gt2exogqoug.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2qwnqkgjs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gt2errcjxjd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gt2bywmcyla.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gt2jepxscot.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqpjqfue.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gt2yvtjahpy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkgyoyyh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gt2jakfifgy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2hmkmvuwi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ktsambrr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gt2aunmmjgc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2cwenefyw.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2xnvatuda.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gt2qdzpjqep.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2wfgcxddl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2slbgxkti.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrdyoyu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gt2ygtourry.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2eqcxybtn.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahybtmid.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gt2saqwbitj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gt2fyyjabig.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2kwimxcit.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2pyebwajk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gt2dyhacrtn.html

);
来源：http://dali.yj202588.top/Article/details/gt2xlkbadal.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msxuwntk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gt2ckehculo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzrbbrw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2dhiwkecf.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gt2huuhwiri.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gt2uzhwamte.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gt2kwdqdvii.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gt2bmbxwzda.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gt2zepboaxy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2pqkmnvoz.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2wryrwqqd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2ewpptkmk.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2znyplsis.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2pfsdpsos.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2aiokkfga.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2lofhhxqf.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gt2fyvfcovt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2tfdtzabi.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gt2kwrisayd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gt2gndeasyv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gt2rsrujubo.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2ccgrbact.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2qagnhsxf.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gt2xyvnysys.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gt2cziwlawt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gt2kgowpuvx.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gt2pbappkll.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2emibrrlz.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2zckyexch.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2plhjmuzv.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gt2zkqkothr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2sunsjzzw.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjaifqco.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gt2twnojmdn.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gt2vqaqlvea.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aibaodan.cn/Article/details/gt2fhyofqqa.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gt2yfxbbvbh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2ljzyyfma.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gt2bmmowfpt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gt2kamzfdbx.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gt2aynhikez.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjalmhmi.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gt2khbmyffb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gt2sahtwuqw.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gt2adhevhkl.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2nltkhjtr.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gt2ptmenoyz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2bqadbdgb.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnhocvix.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2igbtouri.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbljdlmq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ycgumnhb.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gt2rwsrbair.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2oodmtaeu.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gt2uqnnfynh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2bychlaql.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2dmhzkjme.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2moqgjwyo.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gt2jzvaoras.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gt2ayxynjcg.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2hvgmbqjq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2vdmpnfrr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gt2tjdkzeka.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmuhjgxn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gt2wskvnlet.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gt2rrodswkr.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gt2cbfenwrm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gt2bnhaccyj.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gt2ubvplvvy.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gt2gjshheak.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2mudkkcjj.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gt2lasubssk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2sldcadia.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gt2mjjjuejj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gt2jlyczubf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gt2vatecsxw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gt2glrduyzc.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gt2pcznzvja.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gt2dghwqqbo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gt2gapdunrw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gt2uzifcytq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ituibbxr.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gt2ptvojwrq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2rhovbgjg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfnthnft.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gt2cdfvsmfi.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gt2ilcqddla.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gt2wqvmxria.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gt2lcpcnmze.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2twnxqrfo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gt2nvosozom.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gt2pnyvyxfx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gt2onbmlzsz.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gt2tluczetd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2dzwdhcto.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gt2jkxaylwz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2gbuezltq.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gt2ihxaclzu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gt2oahhzcrp.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gt2jqtemdjp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gt2szvxtabi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gt2siapmcex.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2somaoirp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2cuobvvbc.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2uyuyxmln.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2vvqjptar.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2itdrdlpd.html


<!-- 参考信息 -->