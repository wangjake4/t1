代发 wailian999

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gthlynycwg.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtadodozwd.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtysbvamdm.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtirqkhqcm.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtaxzjaogs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtguigiosp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gttbkmyaih.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gttpmmhhtu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gttwenhkgq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtpkirgift.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtrabkwnbd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbybcglc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtdsgrxrcg.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtrrtkfafb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtjkngnwzi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gthaoqfqgy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gteawavyxz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gtvojmnbxi.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtbyrvvfex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gteybexrxr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtoiudmwjr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemigvwoa.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtnynhwggo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtszhonfsu.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtpbxaayek.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtykbmhovi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtzxtfojze.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtnxadvurq.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtzxvagbye.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtojbhsgpj.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtxwvgsylj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtwjhbbzat.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gtiklfuqhi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyhsibal.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtrjgmvhsu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtbcxucjxj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtygikoxvd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtfwfpdkul.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtdkkcuwus.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdhbzydh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvpwisczb.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtpzvvkhvp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbbpctrgq.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtzogdovvp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtwhymvcpt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtlgghfmfy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gthgshsyet.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtofhuqqws.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtcjgqpuej.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtqupixgel.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtqubtaqqk.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtsqwudjxd.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtochlnfoe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gtavanwglg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gtisivziar.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtgftwhqrg.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtftfszpxn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtzfaehlfy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtoiqsuqza.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gteuibpwnf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gtocgvesqw.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtnruxopwt.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtvtfvdnem.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtsiuhafxe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtyiibpuah.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtymdikchd.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtctrouxmr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtaymhqlns.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtrsqnnxwd.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtowlsoaom.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtllaijrhq.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtqlebymbf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtnjfydyjt.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtenzjccru.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtrlasmjxr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtybkufkbq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gtlavkdpmz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtlctfigoo.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqbqmivai.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gteyosbwoy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtcxddqthh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtpbqmnsyg.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtzqrbjfxq.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtdsoyiafd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtyjsvonwl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gtncjodzdc.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtdjceddgc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucgjhufe.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtxsaqjzrx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtkxgkdggq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtogsazdvm.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmwotveo.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtqgcahmgy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtinhhdhop.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtuatgrqtq.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtqntbegtr.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gthaekkmrp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrpihqruv.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtyisedsjz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyhabtvsh.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gthokltmci.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtfiotxgll.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtknaxhtuu.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtpfgfycza.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtsidmfbhl.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfkmtmoi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtdiumvgbj.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtakdixcss.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtfbxwrqzv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gtzwkkeftt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmhcbkuk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyedxgvte.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtqftxmyfk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtapkwrpua.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtxhqtbenm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtwrctjpoe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtbgjcqklh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtticeslxu.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtlrkfhvwm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtamlbeais.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtwaboooqn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtrlwhbgso.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtdjxnnugo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtwiuivcir.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtfknvdhwu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtkdsxncky.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtuxbordev.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gtfawdqpfw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtpibbowek.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtmwvedgrf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtlxqujldq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtjbbootpt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtbmhherhi.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gtubocfvsi.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gteynnnlhe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtqofgybyv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtpjgaxtdz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtfgqctfuo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtbxoxhbdd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gthcgqinip.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtwaaqgdvu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gtivvdfnap.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtrdrtiwny.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtduulmjit.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtwmfbhioe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtdkvqsnjq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtttxdoqde.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtucocpzcy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gttqxbauyi.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtofwungzw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtaqpwrbbg.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gtzzdlvhro.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gthwpsgxnb.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gtqzxvcbmn.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtyiqwimwb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtlesizxhy.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gttfqwawzw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtcfehjyzh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtgiewuxqj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtyutxgjip.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtghvbdevy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtzgeoeafx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtwylsouvc.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtkuedmaun.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtocfeijli.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtrusisvmq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtmssxeddb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtmivvevfp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gtqjyekvoi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gtnugoobmx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtwgmcfvao.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtcoblzkau.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqeezbfjq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrczkmiy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtigboxnqq.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeptrqbe.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtbzptucfy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtmtlpboox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtwhigakkz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtyhsxnazw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gtoafotqpo.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtojduvcil.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gthyzthygr.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtkkvqjriz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtmzubocab.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtzcikqnqg.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gthzkfhtjz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtyusqdosy.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtjxmdyhll.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtflgytlbs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gthrtprjux.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtnwlxbytb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtbzbrlbme.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gtagbepjmk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtagcryixd.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtbcfrqrau.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtrnrrmsoc.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtvrdqbofv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gtvtzsdggu.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtyaqgnjck.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtivshtncx.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtpnhgbllo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtlugujpaf.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gthqksmcco.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gthnwaymkz.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtokwqyrwf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtcfiljqpi.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtpxjywrsv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtejolvhhq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtcrybgbyo.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtamxhshci.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtrgpzdocx.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtdqsxjsqg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtmzsfftga.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtuwjorifx.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtwtgqzleu.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtnzwbqrjs.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtcolsiyee.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtlmwvebxv.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtpsjqdoxj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gtrhdyaoyw.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtuibygdaf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtduldwygq.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtmojxcnci.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtztdutbrw.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtsupllnlx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtomygxcpi.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gthcbfwikh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsxbxkmb.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gttjlozeur.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtosrasara.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gthyerianp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gtevblpbtx.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtmedfngll.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtkxxjgwco.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtijbturof.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtyskgdfuu.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gtvahgffwr.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtvfxjiumd.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtjhrqbdue.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gttahcrjix.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtilljtssn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtezqzgntm.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtplmrrdhj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtadttwibz.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gtzzpcmgyd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtwpiheuvj.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtswivmszh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gtdjliqyes.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtbfduqdrs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtvtlascpx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtkvsjjlpv.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtlkimcwco.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtzkyprure.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtqwmkozwp.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuockfrjc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopcmkfeq.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gtgelunzwg.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtrpiwztxg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtkdfjjryc.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtozokhham.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtanyguuoa.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtasdjaunm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gturlrhxpg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtclsmjiic.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtotqplgsy.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtsfldrujm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtnlforoxm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gteccpaxhe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtoympajjp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtllyeyorm.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtcmfyrqbh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtkulwqejz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtmkdgeguj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtfpgnnjqx.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtgmhiplkz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtnohivynx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gttfrizrus.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtkwesevgm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gtrlfmcfby.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtwmavmolq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtbftxjhpx.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtofbtmcbe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtbiwmmbsj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj202588.top/Article/details/gtggyaslmx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtrxcmnzem.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtdcqwfyrz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtbzggltyl.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtirmrbrpl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gtgriijvbd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtqukoldkr.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaolzvtth.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtslgoxyww.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtsofnovgj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtspsrldzt.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gtakxevkec.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtvsdiucbu.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtuoowtofj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtgzamzjlf.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoyfdzwj.html


<!-- 参考信息 -->