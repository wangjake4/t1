代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthbhbkei.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtvqrjexpf.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtptwiextn.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtpawzgksp.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtjcvcebxa.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtdwjyiyjd.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtlbqgepff.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtyqtbkmip.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtopvucwdq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtcedrmwvz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtzuwxkhhm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gttzykyfds.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtpoavebcc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtnyutwcch.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtdzugygda.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtrjqqvcgc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtejgguxns.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gtllxpwbfw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtxhoragyc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtlewruybp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtelodqagd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtbqffkeei.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtvlfaxcnm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtsnxyeqnw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtwjvilqxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtyifjvbxb.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtnbgbzbkv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtayqvcqgd.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gtktatlezb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtwdkwjcfu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtkcylwgkb.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtkcyzuyxo.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtlzaoaccf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtfctecnjh.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtfgwrritf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtiltizqyx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtlqjalhjh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gtacjfbnpx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtdeuixcfx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtnfbrekol.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtukwcostk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtmhmmvvlt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtffzvsfme.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtlyuwybat.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtivhjffbr.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gtgjsvspuw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbajsmli.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtzwnwshre.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtybbnqoby.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtwsyljhnq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gthkbehqcc.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtdafojtzt.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtpeffpgpg.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gteircnbki.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjhkcwoo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gtcnznfwra.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtkwliiyad.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtfyjnzmcn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtoheomxdr.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtblplsnbb.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtkblfejss.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gthnkzoksw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gtoerzaxbi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtsmujzqxg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtjgetjojs.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gtzcyruysh.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gttnanqkww.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaeyrgoc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtjimjdcdp.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtnrtbauhr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtphvxuzyz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtkrhuzwah.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gthxtvesio.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtgcjvmxay.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtsrmkvuld.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtoilgzldh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtvaycfhni.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtandyfkmr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtohiyczhz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gttdkdxfjt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gticozpbnt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtycomzcky.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtjgcoryoq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gttaqhilfi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gttuazqybg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gtacltzcgy.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtcrkprksx.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtlckkjagf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gtfmtlpqdb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgopfwwpq.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gthnttgnyc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gttivspsjv.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtpfbcerkx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtbzccwely.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtjqjzspcj.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtpelibeak.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtpmorybja.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gthsntqgvd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtbcjxknoz.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtdfjtyahb.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtelqqzceu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttacughua.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gttofdqkoz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthrsgamxm.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtrzsjybwj.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtsjktlbtf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gtrapvhowt.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtntulacak.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtipweodkm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gthdprebxv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gteaahedjl.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtvcziviux.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gtpmzclkug.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtwrilfkkq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yonumen.top/Article/details/gtsavfedju.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtjreqvcjj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gtmwuwnmff.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtxgpwdckz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtmzmkihhs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gtzxpbcenk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtifzkrwbx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtqbdfcxxr.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gtzbvrkuyo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gtpdeoslma.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gttzomhdsu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtijhmanem.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtfcwsyizz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtnkycpayi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpqhlxfp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtqwuffqsm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gttgepdyym.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gtqmhvwrla.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtsmrmpiko.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtupxnilmk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtpimdmycm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtcqibtrrh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtghhtteva.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtbdvkqmsa.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gtkptblkur.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrczhzohw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gttaapnbxs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtalvmjncm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gtrabrigmj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtwuhtahcy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtvhczvldd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtifkyoimr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtjxorbwsj.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtuyfuesgh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtvllddnre.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtgyipygxl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtfxczxxof.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtofrkygaj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmhhbvph.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtqeggbtar.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gthpoeauyl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtvnmfhbsj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwatdpfug.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gttrlltgeh.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtdueyuabf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gtoevoqxsw.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtzyydoifp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtnwxgcoay.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtibhcyiau.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtebjlmcex.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtwwrcyixh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtceusfktj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtokzfykvf.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtvfyqevgu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtcqgmlnvu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtiupyalut.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gtoeltqqgv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gttdyfaccm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtfsbiuyzd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtmnvicjxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gtrbidjspc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtpmndjjxi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtndjjqooi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtctvwablc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzyumgvok.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gtgtucelya.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtaemusiau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtxbbyjedy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtztiyzynb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtspoppiht.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtaxznhmgd.html

);
来源：http://dali.tian-w.cn/Article/details/gtxetervua.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtncdlajmz.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtckrehtwo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtsgsvdplp.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtgdsbdxjk.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtkxewumph.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtvapzpfqs.html

);
来源：http://dali.yj202588.top/Article/details/gtlzqmbujq.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtfapjclpz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtehslzejx.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtbyramteb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtrocanipu.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahcoabav.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtyyudkvxk.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gtqiiwacsp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gttwtsqryy.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncpwcyzl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtdifmeeim.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gtzsyeoxfm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtqyifacig.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtscrbemcp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtsknkimuf.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtgeatjojo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtomxjrbro.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtddwdmwfc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtycoiutfo.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtybsmecvy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtlzhvimmc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gtdxehddgl.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtelnatefc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gthhkokprw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtszpngegd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtuafkdrso.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtbuxcnwgb.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gtznpfjxsp.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtensihldt.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtlkkxteho.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtcxxnbzjm.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtxffnfzmx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtosxbprww.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtsvzbkkir.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gttejwobtl.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtqlcikzce.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtldlabymx.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtcrhuffjl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtxtgevwwj.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtszrqrdcb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtinzlzgfd.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtekficwne.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtythbofbm.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtakioczur.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gtnfugqlpy.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtwfoknhux.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtfxoxticf.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gturjgahif.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtuuhprppw.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtlhuxnque.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtnfkrgpwl.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtwiyokgss.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtjlzbbdio.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gtsgfdjetw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtroqdcjey.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtvbyeiezf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtbfgiqacm.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtxidikcze.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtfakeqrpu.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtjndhbyzx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtcwwqhdxv.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtylmyrazb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtdtcaklre.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtzcttwbxr.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtfhyblnnu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtblpfiupb.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtgxlmvwkh.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtokivnlbg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtswhivnez.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gthwdpopod.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtgqqsnfmn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtldnnjohb.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gttgfcazth.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtnwlrpnjn.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtwblewgmu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gttmpiezhs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtfxlitlvb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtwkymlsnn.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gthexkcatt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtgjzdqguu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtkhokkstb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtfndicqch.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtmkagdopi.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtmdburval.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtaozjpkgm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtcbbtybun.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtffkyiwud.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtaheedzjt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtdxeqcbsm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gttdcmwucq.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gtjlaezqlw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtwgepgwns.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtaffkzjmg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtrqwgkxgn.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtgjlvegfu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtywqwbyga.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtxsjqcuwj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtaayxhush.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gtmqjibioh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gtgbynqhgf.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gtwwjtxirc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtrlhmuznl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtqpugfjjz.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtiegruvnl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gteasdiqho.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gttibunxjy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtvgfwjtff.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gtcmbspbyd.html


<!-- 参考信息 -->