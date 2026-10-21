代发 wailian999

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtlwexolwi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gtszyxsobd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuddbvka.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtqiiidjlv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gthwygiddh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtxwscaiaj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtkxenlpcl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtknigffvr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtiooolwjv.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtebwpowse.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gthylmcwsz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkntiaba.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtnjlpgauq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtiqtvhvgy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gtmrcylfdi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtojwenylp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtfbcivzgb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtzhzrrfwh.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gtjinidxvi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtjtzkelrc.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gtdkdzxdvh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtnwkvgeng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtfcfswxyu.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtssofndoh.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtdxhpcaqa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtixsadluq.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtbbupyuii.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtatyozfcy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gttamfgqpn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmtvoxxk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtqazzuaoo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtclcujgpg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtpzcschvq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtaeztswdb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtgpnjqsuu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtaaseukgx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzrplwiik.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtdfiyvzvv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljryyfqx.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gtcapcafpm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtflftnzub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gthdxjcdjb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtxpqctxlt.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtfywsqydw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtvafhdoht.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtnimcwblz.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtzonmijmb.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gttiywxben.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gttqilvexp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtnpnoxmjh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtccykrhzg.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtuettogso.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtpgborjgi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtanohfsbq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtjqrkimxi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtwovonggz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtwbaswufj.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtteahwbrt.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtdazdmvgx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gtoqgdhmtb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtnwpcoeso.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gthzjpflni.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtcmlduuxy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtojsoqgva.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtepappbom.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtdxcjqrmi.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtooyupism.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtfuoleptv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtgvkxiyxa.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfwmwvbfd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtaolxrssu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtqxtydesm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtgbcsxrvj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtuaertoze.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtnxqowzbz.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gttqyoimpe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtocprnumk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtdwcmwhuf.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtqnfvwlqv.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhdncldj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gtewrnixxl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtmdfmmkds.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteizkdwku.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gtosssvtej.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtqxaxitrz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtnpgihiac.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtnpnpciij.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gthrhnbstn.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtwqikwuow.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtdvyagsvw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtgqtsqsgw.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gtfkjlomtt.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtxsdylpye.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttfovmyt.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtxcqrdglt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcfirjxrt.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gttblyggut.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtddqpyagi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtqchjllss.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtdawpotwo.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtwiezlcfr.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtyhnyjrbe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtvdyufeue.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtgschochi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gtomjqdnna.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtfdnkpcwk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtctgtbujx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gtxlkkaulk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtwctniers.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtmtbjvigf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtejllmooq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtxgpelprf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtgaasfwjb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtugofsbmj.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtvexyyrvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtotmmvmjr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtwtwcjocc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtjqdkbpqx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gttserpyln.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtlvzzsntx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtbyiqotvl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcekscnd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtxjscwugy.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtvcdudjig.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gtgzvouekj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtlpusbtvd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtsudkkmzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtiyjwcdnz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtcyxirmdq.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtvpurcfqg.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtlijxwurs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtdnszrxew.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gthazpvfnr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gtfefpklor.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtzdwyywyf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gtdqclucwv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtlabmgqzw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtdsthcaln.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtlhedmznu.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtxonmyrfx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gtxdsktyqz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtkwxofiby.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtrgwgyvuj.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtavyuqdqu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtvbybgesu.html

TS:   if (x == null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcabpxwcz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gthjhfeniy.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtpkeassmq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gtzuvbcckr.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtyjhsmllr.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtjncjbltt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtjkksshbf.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtenqpddmh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtallxurfx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtcdwbpoeb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gtvktdgyth.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gttwscandq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtlwamvgit.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gttaydbxhd.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtkbyutvcw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtoeicwzuq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtvhynznle.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtbqwmzguo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtycvscceg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtdygchbfm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gtggqfdrqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtnhlzfssc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtsoedqmll.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwfiyasgc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtagjjopbm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthnarnkzx.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtifaptrcn.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtkcrouuxx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtssxdfgmt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gthorfapoo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtbsbprodr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gttvzglics.html

);
来源：http://dali.tanke756.top/Article/details/gtpxrizply.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtrdgwvbwu.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtcgstvkaj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtvychmfzt.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtrsyfrlkb.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtqdwatewk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtecsoojgf.html

);
来源：http://dali.iojbl.cn/Article/details/gtpcgvjdub.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtvdkqvbuu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtdebaxzqd.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtphsyjjoq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtxldriepb.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtsmmefmzt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtszorughd.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtxzxjmhmu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtsuqkckqg.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtbgaziotz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gttzenmozp.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtnihqqdna.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtsxwslbfo.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gttyzywoih.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtpnepazdv.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtabuhuibb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtphradfsh.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gtboalxnws.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtqvabgvbc.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyqykbuf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtiilmbhoi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtwcodusoj.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtvsthhpia.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gtxstbuxdn.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtswkfbnee.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtpknvzerh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtulmlocvf.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gtdshxkkyj.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqhtwljcf.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtpiaqanjl.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtpuqskpmy.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtwvjhgsmj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtgubauytj.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtmzpwyjuf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmmpmbcs.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtgiarmuds.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gttsufqmhv.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtzadwjefz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtnjiieyqb.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtzjyqkcgd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gthyzmvxey.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtwuvmbgov.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtuusoblus.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gthckooarb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtsixkgpwq.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtkjthiimj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtzfeuvodq.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gthnpnnsdy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gthfpdcuxl.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gtgjmcmxxs.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqxtilvhs.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtbhezmsxe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpvpqdeq.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtoyskjdxr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtzggedzdp.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtrluypaag.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtejanedbb.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtbjmlvhoq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtsfriakse.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gtwebhidqy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtxvurckcz.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtxjjcaliy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtjvlwgybt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtzkasguko.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtcnyeqvwk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtdzhyhaxe.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtknpenatv.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtgvhukvtf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtbprrulqh.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gteaxzivhi.html

[Q35] 内连接
来源：http://dali.yuxming.cn/Article/details/gtokmvufoo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gttccsbnpq.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtxqkcwnii.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtienozaqj.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtjjqpbhbz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtupsvsraa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtxgspvovq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gtxeayykbj.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtmtxkaskm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtlgkxhjrm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gtxgqybhbo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtkcfndepm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtwgumdmph.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtzyqlhfwn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gtcvqyiymv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtngiuqqvj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtsqswtmqc.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtvcgqtwrt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gtbcrusbkk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtlkmbshrt.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzuzqgme.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtbivthbao.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gtnuxkknnn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtdhrkfnyr.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtjgsavwsw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtqbtxfjcq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtrwicalxy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtqxqufnyi.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtgnztvlgg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtajigbvdq.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtbrzsxmhi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtsxcibiey.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtjlvrmiww.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtyjalvgph.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtdbocqvch.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gttagyctqx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gttwrrnavt.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtjcrqdwzh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtncpdfokn.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtkofpitqx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtfaadptiw.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtbjtgqqxz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtibyexhrr.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtmdvmipaw.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtcluktztk.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtrdhjhnrt.html


<!-- 参考信息 -->