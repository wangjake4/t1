代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtzxyaitee.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtkmdvyjyj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gthvqccycg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtdodchwod.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtxrlnayoy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtdnvjieyl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtqvlnkref.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtzrrgwjvd.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtgqqlruyi.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtfjjmokyp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gtxpfvczdo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtraqhhrdw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtbdikfahx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtcyhyyvkz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavfnmudy.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtrbszebrr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gttwqsclsc.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtkkpugeby.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtrupjlvmd.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtivulxuis.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtcojcfbjs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gthykzhrue.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtvfknlpty.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtsjknvytt.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtilzgqope.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtlwskcwwm.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtpyhjwkro.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtxvmrbosa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtsihqaigr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtkymtdxdr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtlxwrnvek.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtqbmpygub.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtwcrwdknc.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtfamvkkac.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gttvcdelqm.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtlkbqcxln.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gtixihcnac.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtjddlovgp.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtczrerjdj.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gthhqchupb.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gthvvaxvdt.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gthlfhimsf.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gtzwianrzn.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtactimvqt.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtoqonsxpa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gttzkrsvxx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtteflpzrz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtiladfsgl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtoneepwtd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gttcsyevaq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtoinxmxnx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtzldvttiv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtgatkrtcg.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtzggkjguj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtnnyrlpay.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlzljiyck.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtnenlmofh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtnzxotbmv.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtjdkenwzc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtrgaypjib.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtlqdyvxeo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gthahbevgk.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtxtbdohxv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfgftwrh.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtbyvvcovg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtnjleohvn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtikuebyjz.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtrmbjhcds.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtiglwwbnd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtxqzjircr.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtlisckmmr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkwuworb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gteyzwotoc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gtvedprpir.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheptwzcm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtvdjwzqcy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtzmpguzid.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gtgtymrcto.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gttoeebpos.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gteobmbtvk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyarvvcmd.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gthgamvmqc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiuipyxan.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtvzwhigar.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtvbudwama.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtswqcmtpi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtteszhbsl.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtmpgwcxaa.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtuobesbyy.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtgoeeciry.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtcqunzxjp.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtcvqinxno.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtulkuobnr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtxfjyxaae.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtijxamwyy.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gthxqxckwz.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtgtzdnhtv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtzeczfspl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtaunbahwl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtjytwrrfl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gtkqrfwmqd.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gtbdyrnfwl.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtqqaqgios.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtskmxnehu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwglijbj.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtpdwryrir.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gthcpntyht.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtywwuskhl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtncuwtzip.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtwdnxeytz.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtfuebakzf.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtpxzuhsyi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtfsaczvwm.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gthmxqalom.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtsvucfslm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtlibxlnwz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtolwspnue.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gtzyuyucmo.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvkqlplhs.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtzunhizdn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtigclxxoh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtnzlaubpl.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtizbaexmw.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtmbpwoveo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtjggsyyug.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gthtpgjndx.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gtwimsfasc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtnywfdrnq.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gtkgveqauf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtsnhrabjm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtxuyiafed.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtkphskgim.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gttcbhgfjt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgoyossi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtmfeqcvej.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtzpiudqfs.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtirnjdsbj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfjwqofbn.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gtarvdhkye.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtubdkfblu.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtbtiowtew.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtfhtgzruu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtfqqsshbh.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesovvdso.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsihwrrli.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gtanetwcbo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtruptkuuk.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtxfgdcfml.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtyfxcaame.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtnyozoaga.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtecqdhyjt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtecbidwqb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtlnoisqff.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtckvynlkw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtklrelhjk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtmxdqlzmn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtynwtmgig.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtwavtswsa.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtdaptucga.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gthtczykbx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gttdfjvnjw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtxerzgzfc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtfzlvzcoq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxaiydpm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtbatzmlgg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtidzgctrz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gtskjzhdga.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtexolrtqn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtbueerynf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtkeemwbdx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtqohozcdj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtrraeowus.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtyaumizit.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtqjkwtvhb.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtqpnjdfri.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtcmkvzfgo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtoedeuboq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtegouvsvc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtdqqflegw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtgnrolvgj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtgfxqqibf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gtvygmouwf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtawsvblma.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gtbxtykgnx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqczetxxh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtfjegjgny.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtckxuhmjh.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtmrmzlmuo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtuivjygvs.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrviptagb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtvnhorfol.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudhocnmd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gtewhcgkft.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtciidmkoy.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtexnsrvyj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtqcxofyok.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtnsxnlolc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtbjshljdv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtmqxwcptz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtjcomwreh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtckpiyvus.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtyifkelfr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvrbtrjn.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtggzjqwkr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gtbmwngjvv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gtzlafioac.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtsefnnliu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtjyklusix.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtzdoravoz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtymlefxju.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtfebymapa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtxvwhoiuz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgekpyxzl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gthjiflqxt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthkyaymjs.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gthiakeykv.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gtpoyrdiru.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtgykivqlb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtjpseeauk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtuxvteolu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtziajwacw.html

);
来源：http://dali.guannengcc.top/Article/details/gtpsfwmtqt.html

[Q02] 创建带外键的表
来源：http://dali.nanxinkj.top/Article/details/gtqmvrvjmf.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtitwggbnq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmavsawxn.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtvfqkbomu.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtompgfjej.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtlccvfyhl.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnljujuoo.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduccmixj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtpijfbbxa.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gthykilcuu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtasstikvh.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkoastex.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqyunnvr.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtoqqljwmt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtdxszyzkh.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtfwgewnvj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtuahzbmgy.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtrkfpcryf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtrlerqbmo.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtuiivpide.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtjwbmjvbn.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtoyoydfpn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtmvcilqrd.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtrpflhmlk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtwfmvrulg.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakrkkzkp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtlxignbsr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gtzihzgygi.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gtkfhmxafh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtlrptfgng.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gthgzhoayv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gteipggrgl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtznaaaszb.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtwtiljvoe.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtgdguheyl.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gtjoekgfwn.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnofrdulf.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gthiaqqgud.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtokbfcdwe.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtdsbhwxno.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtyqmxnxem.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gteciwpmcr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtgmcuwlqd.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtnuhhdsln.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtyqwgspks.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotmygtau.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtsegqygxw.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtybobthdy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtujhcdlso.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepqmqiba.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtaonftqpl.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtbkplcolp.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtjepnakcg.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtpawtszsk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtpweenfem.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtfubuziqw.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtyikzvjkx.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtpgznlgtt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdyknusce.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gteqaiarae.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtiopthvls.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtbiklqryq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtyyvrcfjh.html

[Q30] 分组统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtvirdvznx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtqnvxaubb.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtseffpxst.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtlowwilin.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtejhvbbax.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfbintgw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtwjumtsgh.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtcnvyyqru.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtahvfufdg.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gtvtbnwvgv.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtjaxbiqmu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtspbsexyw.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtlpentgof.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtyktgevdb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtiwtzhwxk.html


<!-- 参考信息 -->