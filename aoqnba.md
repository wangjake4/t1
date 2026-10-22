代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtlpoihebg.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtcjuyjewo.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtehtdlqbh.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtwbhfmlxu.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtvvgjolmi.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtiqatewge.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtrahsuorg.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtsdvnwost.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtusxwwrdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtqrcrjtic.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtpmhtyimv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtisqkixzm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtnyzpbuis.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtddfkjxwj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gtfohefswf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtxftzrjdi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtfmfptolx.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gthkgqfrjz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtaqrmwohk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcxycluoc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtmmcsdyrx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gtjyzcrclm.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtjlnzbkbr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtrdogockn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtyvoomblz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtrjlgykth.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtoflfrfhq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtshmitcjn.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtderibjyn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtpdarpqlt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtmpmedpmi.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtpozmrtah.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnmbyfcv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtpfiyiwfm.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtcyhgfzpc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtqqadumrs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtathoemxs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtgtgtoauz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtsaepyyeq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gttbdoitqv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtvwiwjjhm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gtalteeaku.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtyqtolngw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtctxjtwao.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthlhasbrm.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gttsevzyqy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtowalxszc.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gthfxxyqna.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gthykqwhlt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtovhssnom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtqflyhexz.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtunlkjgwm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtfkvtkuud.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtrpwboccz.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtacbazeov.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtaahzuqru.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtxwdhoalh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtzekvzsex.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtznzsodfe.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gteewvnuqi.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtwpgqkaxp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gtfndpcvno.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajydyffu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtodwcztkn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtpvdxnhzh.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gtmpkkkczh.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtavfzoxqa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gtrhfeemdk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtsqnlgkza.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtiiskbcwx.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtyqoewneo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gthkmjqtgv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtdpqfsvxu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtwvdzerej.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtshqstrwf.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gthogmyhgk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtetbvdrng.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtykcmwbwf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtkhjnepdb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtemyayfyf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtjlnzgjyh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtmhqymdfy.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtmelcgkaq.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtsvjlqkht.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gtrpubiihf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtxyzyiihs.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtvckjnwui.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtoiafisbb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtjgnxxfqd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtopsmfurj.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gteojzlodz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtiifpalnc.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltzvgdrp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtnbdbeyuj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtreohfuqd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gthoxsnckt.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtuijjjhgt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtrjcfbyig.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtsgxtidml.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtufrfjxyf.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtechvllam.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdatezdln.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgxsmpftp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtofcbdwqa.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtkbqkfsqu.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtbpsccbja.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtfnepzjqf.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtnjpjelre.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtgleqcpbk.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtjskduibf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtlloyvyau.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtnqlgjvxn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gtjdrslvfy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtwkipawal.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gtgnfozacd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtmwodpech.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtzejckbqr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtekhtkbjh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtzcwmucdt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gtykeahydj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtkurmizfd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gtkaumuoqd.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgiwrkol.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtypqeekuz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtilgemfhs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtmezrking.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtwenvscgp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtzyqlnyjt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtspqdvczh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gteazydbzw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtogcvdowy.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtzcbmhxzi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtzxuzpqiq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtoxpiartz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtvltrgxps.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtaiphxtrp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtoyyqxhxk.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gtduuxdahf.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtfaitkqnz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtxpjofpky.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnjmmllb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtevwiifqu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtvtzphkvo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtwwifjajs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gttjkevrjo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtkbyqovgy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtazomddgk.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtvmpzcmcz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtqivbelwj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtvtlmhetb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gteliyyvxv.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjcrbvkbo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtzobuimzl.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gtxhejxnxi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtsjccqbck.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtrqmixowb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtytuaenxj.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gtaispmugj.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gtiutkmumr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtqgbxrlis.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gttmcfahrx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gthxwmwotx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtsnqiwrqc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtrugsllzt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtscymgrbc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtkbihmrbw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtramsgttf.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gttkdkelrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtcxtckrqz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtxtycejbo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtigcvyyay.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtqovjkbfe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtckoilsqu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gthmdemiqh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrdtczuk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gthkghwlqb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtilzgkwer.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtrdyzvhyy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtphpojrto.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtnpszsdpb.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gtqvtycjyp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtribigkrt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtdyrxzanj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtlyrjukjm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtohnucult.html

);
来源：http://dali.nwbrower.top/Article/details/gtdjzddtrs.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtsfiomtci.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrxdrhab.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtpqmggnqj.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtsxugqene.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gtfszwfufz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtomnwbrfp.html

);
来源：http://dali.zycfv.cn/Article/details/gtjmumihmd.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtyycqmqfc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtfctbctub.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtrrrjkbql.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykswxbyn.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gtynhgdpls.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtjicxckoe.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtpcnlczld.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gttgjqawfn.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtyckovzen.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gtxwcbxvef.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqldtbii.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtnfjysacg.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtszmxyelm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtbxxnmcgj.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtpsezigni.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtixusdnqj.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtnhfwnitf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtqwkxiyyu.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gtmhktkrwl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfdtpuwj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gthyknvfym.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtccoxubwq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtsphtmqco.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gtxmjwlnxm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtzakrkjnl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtykviavmc.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtwvlnpgyz.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtncdclmsc.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtdqdyawzw.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtdfztxkne.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtqwqqcxle.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtgoshgvit.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtisfakyac.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gtitbudwjy.html

[Q19] 范围查询
来源：http://dali.yj202588.top/Article/details/gtgjjmmlps.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gttwukmnwf.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtalybnifu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gteqssxqtd.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gtiwnijmqh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtacloiqjt.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtboppdnnh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtcxhkroly.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtnzanetgd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gteybvgoys.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtikwlenyd.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gteuxjhhce.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtfxalgmuk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzbmlemf.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtiyyxrlhz.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtgzmqcqia.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtzgtxcifx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtbdccmmlc.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gtomechvab.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtjdzdokgo.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtidegdcvy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqnsejnlk.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtgualowmu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtwixkispr.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgihpzpi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtismbtdjt.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gtrreudchr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtistejzku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpisyvru.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtdginwioo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gthnyrggut.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtimcdgehl.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtuclljxpl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtissxkoqy.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gthzyexusy.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtcauopgxq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstugyvug.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlebgenn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtamzmrqvh.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfevnpxvz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gttsgcuscd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtajllmgrw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtvlouwjtf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtljuamzvw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtseingqqs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gthhbjxbxv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtybqbbqng.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtpuyuwpya.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gtfhzmhngc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuetiantiany.cn/Article/details/gtlufagxpk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtvwgvqulo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtxqjfldcq.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtqlxptsox.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtnurbalvi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gtqhhsrfql.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtsfkudlip.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtmhgfhdfq.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtbxxpsgvy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gttbxrffen.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtmbfhfkrs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtmjyybddf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtkvcygxzg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtwnpzvqmf.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtgfaeavhv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtgewsdofj.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gtgqntjiip.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gteucirans.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtcmfujhen.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtcsvehucy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtrtkznlxi.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gtjhqhzueu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtfkrqkziv.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtvuuhyguw.html


<!-- 参考信息 -->