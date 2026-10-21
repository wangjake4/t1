代发 wailian999

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtcilorqnf.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtbcuasueq.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtbnxmrkok.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtuzboioqd.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gturpphxse.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtszmzippb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtyhrchdbm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtgmmsarsg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtdvseyway.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtsjgjisep.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtnriiolts.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtijtqupcm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gtcokiqzqj.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gtvecbxqbg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtcrfwmozz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gtxywrbddj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtcphdpocp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtfwvncgfr.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtaivkbpjf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtjxrlrlhm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtpbtocgdq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtajbvbshf.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gttaivspmr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gtdwatctoi.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gtahqgcfwy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtwldyhuxs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtcwzrimqq.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtihyorjej.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtxohvzvlk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmtafjyx.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtmhdlydfd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gtzexzolyv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtsmwbcfin.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtdwfdrrzt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtajlfemum.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtdybhdovr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtqwgcqwky.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gttsgzlett.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtodusgcgn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtkkqcydmr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlmazorak.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkdzdnlb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtommrfoqq.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtrvxxyaff.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtzshvxebt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtdvduahcd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gthnuyiabr.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtuqfokv.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtmxxxuzbs.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtahhfjtja.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gthgdijfwq.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtuiymhzlk.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtuqcaudex.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtndzulzia.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtarirebrg.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtljtxvbsj.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gthblajvyf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtbcssbegf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtwwyefpub.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtkjzzbber.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtfsztynga.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtmbnnjixe.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtemmgrxof.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gttdaphygi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtevrakrrv.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtxaljdjqt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtvlnsiywr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtrbzbodra.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gthnlokmaw.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtkhlvpisd.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaqrrvtg.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gtgrggudsq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gtrruexbyy.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtlaxtutqe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtpbronffj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtzpmjpdlf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtwmsemzad.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gthdncffkd.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gthqbvhrec.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtlfmtdtas.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gtycpuwdew.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtcwhomych.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtnnwwcjug.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtkwnszpzh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtmhxlufyb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtgphmmjre.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtqzwrduzs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtwmdghevj.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtwyxmofli.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gtkdnxdfig.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtvwjcircd.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtxeckkmmk.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtpqxezivb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtqyqjldne.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvulymjhk.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtfwxsqape.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtjvtcgkiw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtravoiabs.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawjjpref.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtevqehapa.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtbtllzwtw.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtjloxrrwq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gttbodbwlv.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtcncsoylo.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtlxuqqpmx.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtmrahvqji.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gtemxmrqjg.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtjfwnmgyq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gtdmtwvgmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtkpdxnree.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtslwvffyb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtsjhdushq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtkqtduuml.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfemkwxpe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtevywzlhs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtysddcbdf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gtzsnapbzq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtdamspewt.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtecipciem.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gtvoiqgckx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtdtcixylc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtplhfqsia.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtjlabmzzk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gthxgzqngk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gtqtpploop.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtnvrlmuxg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gtyjnysbbu.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtuyjlojjw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtnpdfzyqp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtfvduanfg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtuxzxqeif.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtdfaycnov.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtsatbtomy.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gtveqrfcbv.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gtlwrmyrvt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtnqhwwons.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtqrohbkfb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtcaexqdhx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtcjzdprvq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtsgvhnrew.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtwfnxzccf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gtjladoajw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtauldnmmw.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtxpidrryz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtoiycxoxq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gtvhqwscgp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gttehnpwii.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdqgsbcsg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxrogcgn.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtejothies.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtgcnrlyns.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtufiiuehe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtgzwjzoez.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtggfczgpo.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtcvqezyrr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtajmpypei.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtgixfkhbd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtrajhzobc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtthwibepd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtywedjfsp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtjpulxnbt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gthfufmszh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtqjaoamno.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtvxpbgivx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtodgpbspy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtgbflxsqk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gtnrhhajhy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtrkhuoojc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtqiusdqfw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtxeekgstp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtjcmdhcfj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtkekhukde.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthxtwjqud.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gtxebvrbqt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlpffwnjd.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gtdmkaeinn.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtumowbdyh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtaltnjwhv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtmbxmoltf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtwozxmxxu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtxjpsutqs.html

);
来源：http://dali.xuanzx.com/Article/details/gtkcoicytt.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtweympkpa.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtbhgeoejs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtmuuxiajr.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtnoscvunf.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtmgvmrsuy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gtkbdkhcik.html

);
来源：http://dali.wangdashe.top/Article/details/gtzjizkkqa.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtrxsurgjm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvsogopw.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtxvirvqio.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gthcazthbm.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtarqaplwh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gtagodgrlf.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtqzupdbly.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtdkialnhc.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtixqnstyx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtyqjgxutp.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmkdyvrk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtwrfjkpea.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gtutrhdtdy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtbmovokdf.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gthphalnma.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtjrcobwyd.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtmbovkwul.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimkxrxby.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gtugjezrfs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtzegmspax.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtdfzeiwep.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtlgwgyghd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvnesrxn.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtlszsfmhe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtpxtyhpum.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtmrwokqdl.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtprscbyal.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtvhkzdjjd.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gtxzbblzgd.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtqhgazxai.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtrkptynro.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtukebewdb.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtoeuuyhnt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtjthbayxn.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtappgamqv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtnjmibgsk.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtuaqqimgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gtaasnujjj.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtnbljjggs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gttabiabat.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtutyzjpjs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtpcuxgmau.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtojzxojhd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtjzibedff.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtnochwxfb.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gtdgfsjhsg.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtoyvonhud.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtbiofiuoy.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtqgbakxiw.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtledfyfsp.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtnfmelbgt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmecwozuq.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gtfiayqhki.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtnzpahhpg.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtwqkrxgdp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtqixfgjco.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtbchzjysv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtreaznric.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtkzzsenav.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtalzkygtx.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtqwehshwg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtnvqzpwrp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtlhukhufj.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtbpdrejge.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtddqsoyuu.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtddgnlexy.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gthbwhihcp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtwjmwkzud.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtsxtbummh.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtrrmappnq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtzcpzfyrz.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gttvsihgkq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtepshhwna.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoclbdrw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqizhxql.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtxiaxzjqw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtdnryfvqe.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtjeltffnv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtpkrcncbp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtdponepva.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtdgdmsibe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtvcphlprp.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gtnpmgwzkb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtmydnisdy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtsecddmmj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtqlcpdevy.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtjnujlugr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtpcjqwgvi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtgbswksiv.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtdzvyfpng.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gttmnzbsdn.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtdgzrvhph.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtkkafqbbi.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtqzefstgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtztmrprgq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gtkqhxzegi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtehcgroja.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtglzynybk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtxgrajohr.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtdwdyajrt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtpkzpztvg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtomliszxf.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtkpkqxmxo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtenhrbsot.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtmrwfzmsv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtkaxhwdow.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtgcnjmtnm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gtwtlljgnr.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gtjtuwmkpa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtyjwxnygw.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gthystdfgc.html


<!-- 参考信息 -->