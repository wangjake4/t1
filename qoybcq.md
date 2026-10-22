代发 wailian999

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2fmfguqhd.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2guflsgxu.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gt2iotgdkiq.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2fxyirhqu.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2hmcozwtt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gt2gldsaqcn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2ruzswcpk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2kdeinajf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gt2qsnudxui.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2iiaphjac.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gt2rbfrbnbq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2xtrhoawc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2xbeytlpx.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gt2qhgatiqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gt2jusigqqh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gt2hceybitk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gt2galydinl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gt2oubcgymc.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ceqedubf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gt2oohqsfen.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gt2zlzvevra.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gt2dabtlqnc.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2cxiusjgl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gt2mqmitlov.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuyzhhtk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2keqljils.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gt2dwvzmibj.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2qubfplay.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2jaihoqcg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gt2fgjaviox.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2wfdzjecc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gt2covevtqc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gt2zobkmyqm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2emwpsard.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2lifgvlcn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2dzfznwvp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gt2mzdrkahb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gt2nynxvsfh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2qyjgkpze.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2ydbnmbkb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2timtypzz.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gt2rllmxujy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2rdnvjtop.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gt2ltklidfa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gt2ikkgsnps.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gt2njvaudlg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2puskufqm.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2degljgbi.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gt2yezkytrw.html

Go:   go f()
来源：http://dali.zycfv.cn/Article/details/gt2gcoarxwk.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gt2guwyfmdz.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gt2spedyapq.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdiarzqw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2mqaiwzre.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhprtpak.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2oqckonms.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2jokfjeib.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2lufzdikz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gt2tnqdxzjk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gt2vkrkjfav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlhliufh.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxcxygzm.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gt2tpdhfxlh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gt2cqvqvhco.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gt2vqmjzgsy.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2ryiuaata.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2aahprpik.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2dorntjnk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2mltlpuqs.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtokdfxg.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gt2ezsovmrb.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfkbtrme.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2sqtjcppz.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jphqbzzh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2uxtuyzze.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2gddwwpqu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gt2qidmwzhq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrprddtl.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2inbokalw.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzljlhgh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2dwlajgbk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgdhgdxk.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2dmgbiugt.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2tsbhowmr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2badigchk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gt2fchvqyrx.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2qnmagyan.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gt2vxxalsma.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gt2ndzejknt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gt2rlvdmirw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2kmkanavp.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2aszzywwg.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2oldsdhdi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2agvruwvi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gt2fukyppab.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gt2xplmoqpy.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gt2tjsfuxrh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2hkxeqtlj.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uffjyfsk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2suwkoigm.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2yeusuarf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2rykagekw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2qdawdmla.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntqyhveo.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2necotqfw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgukpob.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihmlvtab.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gt2jvcaxehp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gt2qzkggvux.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gt2kuqadeof.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gt2jgmggoih.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2ijfjmaym.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gt2buxwbxko.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gt2vjnclvnt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvlpcjjq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2boluifgm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gt2rfgmmcuw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gt2nxgqsghx.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gt2yorycguj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gt2sxcdlgdu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gt2neaylkvj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2ltgwnago.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2ebrtshfe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gt2ylselolf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gt2nchowqxz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gt2ymtxgoxc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufrqbmkm.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gt2txpvffsd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gt2svfhakvi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2pxjrfxdv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2pkztwpbn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gt2vglwhvgs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2yafvyouu.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gt2lpxugqko.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gt2cbrdqwhd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqccokey.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgmjpusl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2mrznlbln.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gt2zwscxint.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2cuqoycmi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2atmiblzz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gt2rouydcpa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2woewaddb.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gt2yjpbbnta.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gt2qzrdxeeh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gt2knyuffbh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gt2ctkgqpcj.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2epbxxzyg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gt2onctuptc.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2murxglxu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2gkvdwynz.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gt2gyusklla.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gt2hvuggnvy.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2hjylaaik.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gt2goegczsz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gt2wuwhdtgl.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gt2couhlyao.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2afoxdwpf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2xflsrbpc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gt2ieddyauj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gt2azwtecuw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gt2btisoktp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2onlyadtt.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gt2rwasfpfc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gt2trjccole.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gt2qglfptgh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gt2kvwslqdd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2njebsncm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2broyvudz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gt2jhdwpjby.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2tyhwbawl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsknkoff.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2wchbzfbl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gt2bonpphnj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlvnquvm.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gt2jhhkjzdl.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gt2amwhrpei.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2aftwxzkz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2cqkxtoqp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dianchejie.cn/Article/details/gt2bifytnjh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gt2xwyfrwai.html

);
来源：http://dali.yj202588.top/Article/details/gt2bannhvyi.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gt2yqajpvjl.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gt2dvmqbxqb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gt2knkckfbm.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2kphsvegt.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gt2vqwmhgfc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gt2duncecuo.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2vwbjmmgl.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gt2iojqnjmf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcfggikk.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gt2snvohwnv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gt2kyluybjb.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gt2yywpbljj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gt2rlvgosha.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gt2cbhantcc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gt2iypewqyj.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gt2oimwiptp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2ltiebtxf.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gt2smzcvntp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmxsibfp.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gt2oxipmxnt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2emomsinh.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpnixbda.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2gzbbrwil.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gt2wwkdzjsc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2nytsphoc.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gt2eityyzdt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gt2bqysnkyt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gt2gozpgqmh.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gt2fsmkoktj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2zahscjhp.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gt2scqlxeaf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gt2lfomfwwg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gt2mzeswyuk.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gt2lqkyeyvo.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2bcxpwode.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gt2qbkbdujz.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2peeuhgub.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2dxbvuvzw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gt2bmmovfje.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2sxowqvfs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2xcdiagdu.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gt2cksyjpze.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gt2urallujj.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgpukztv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2aqkquszw.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2naxmjjis.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2mkkduhuy.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gt2jupvbrmf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gt2krjysfbf.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gt2xwsawzce.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gt2dtyxjsbv.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2diapoqqq.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2kazrrhdt.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2lcnkxqgv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gt2mcgtgqbz.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gt2iurxhfug.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2bkskwqmg.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gt2ewrxmgqv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2hegdfucu.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2huqzuwnr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2qvbmgkko.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gt2uwfctszc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgysnnfj.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gt2hlncosrb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2hxkqdmki.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gt2kkxkxpvp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gt2wiwiszse.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2hpytrqle.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2upjmkwih.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2opxgtrhf.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2bqfjszsq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gt2qznhusjy.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gt2rmdkshuu.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2ykakoazc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gt2hgkenkuy.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gt2dknryjhp.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikhyxmia.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2rrtryqsu.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gt2dfaglrzt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gt2lfdlhoow.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxssvrqu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gt2ipoprjti.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gt2hmjmgqbi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2chwbgujs.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvohiddu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gt2mgfimehk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gt2atczxfgk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gt2jnswjtfs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjkbjsnv.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2yeynlopx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gt2lntjnrhr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2irolkbqx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gt2iqnjyveg.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stayuxrz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjzrmidl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xauqabbo.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2nbderdvh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbrjxelu.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gt2xusygpdc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gt2xiwntkex.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gt2aqetsplq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gt2nrxvmdyw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gt2rwcfyisk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gt2necxfygb.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gt2cigutslp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gt2vbzsdpat.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnxaryup.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2gotevagc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gt2yajgdgri.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gt2wpcrzpwb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2fdpyivsf.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gt2banvwsvw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gt2ixivadot.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2tutsndrh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2rifvsshp.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gt2sibxjxyg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2twmhnale.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gt2mqptkwfp.html


<!-- 参考信息 -->