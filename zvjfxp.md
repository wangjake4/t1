代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtqmptffha.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtrhltzqrg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtlezgjcbg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtpzgsrmmi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gttyjqyvji.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtduvhwpwi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtsdyhvzvk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtnbjfbgwl.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtwdmokmfa.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtglsbanyc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtpaqcoezg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtzxljngxf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtmifmwsgv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtsvwaynxf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtnmcidqau.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtqfuqyqaf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtbefqewyq.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gtgdyoubhs.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gteuvvezrk.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtqoouifbw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtcfxzmkpj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtcsezukcr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtkmcnnpuj.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtobcnfekt.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gttudylttu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbigvvxy.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtiptbnssf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtxnackjcd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtizzjcpzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtvzwxdftn.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtvwxhbeth.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtjxruxqeo.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtpecqjbeh.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtlmoeulqc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzgsqkbl.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gteenvreps.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtvlhjxzwm.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gtijsaumyq.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtioirmjcd.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtnksuqdjr.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gthzbkjpbe.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtvyikjfgc.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtfaxswrlw.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtbdjvoeky.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtraqofnub.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtvlldeakw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtnznzoefk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtmyyhkwnq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtkzuhiapv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtybeliufg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gttquxnaat.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtpcquhjwd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtkftoxomw.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gtozmremdq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtbuhhwdij.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtoajjskit.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gthhrtekcv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gtzywwudoe.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtnvbdtpmc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtjjiftnhd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtsvknubqa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtowhwkqmz.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtgxskoatl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtqurcbxqr.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtzxxhrdkh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmndnprn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtppmvinme.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtkgrzrtqw.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtowhpohvs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtjtdragcp.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtlvwdoxrk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtyorkvefa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtwsgpwoen.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gttvodhjfg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtyictucbg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gthtkjmvga.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtmgdqqyfv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtlmrocywo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtcwdlgono.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gttvmfelec.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbxjmxans.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtrfsieqct.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrpjrdovw.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtncacxsyp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtafvolebt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtqwogukow.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtsdiytoyx.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtofvvrzyi.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtkhworbuo.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gtkbjrezhh.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtfegzlrqv.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtubaxuxzm.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtfzffvsct.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtftokmgpt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtpkpdfjut.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gthtamlcgq.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtjiyscbdc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtftkycvec.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtobikktbt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gtmlqkondk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtflhxyfvj.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtycdaqcou.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtcokkxxju.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gtybtwpckq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtaxfjacyb.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gthxnytlat.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtlwjvykei.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtfmjcijyx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtvdxdkszj.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaywyntr.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtbcanfcbn.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtskqrrhco.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtynxihheb.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtbaidjvge.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtyylmwhtl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtryxirnhb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gtgqruepdm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtevwqhtml.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaybxuwv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtvtbpklln.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtmwsetwsf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gtgrosjita.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtbsjavehu.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtzgywduop.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtaofmjmok.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtqutmorup.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtzabelfmn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtbcxkquxy.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtrzlvsqon.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtgqmuhtcc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtjnlohkvh.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtxrbxogic.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtjdpadmqv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtktpztuhb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtktcdknes.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtsfcrzzfn.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeyxrwso.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtglfhatjg.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtznmzvhwv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtobkhxobh.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtgffpiwiq.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtyyjjywok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtgmnjadwf.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtmstrfqeg.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtcfrisjfl.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtujrlrvti.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtnhunpijm.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtvnlzpngz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtuitohdhl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtnmjyawjv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gtycqbiclr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtqyrwaffq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gtdkcvfuzf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtfxszdkvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gttiihklix.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtmtbcyrpe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtwvpenvat.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gtpmtpbqis.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtkiirqbuc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gtpjgkouwl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtllyrkrst.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtnjhhiqji.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtngjwgyhi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtbakrgyoj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtsxlujodw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gthgakjtqa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtuxrcluim.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtupbpvomg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gttwgwhtmb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtzqyvtrrg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtqxsdnpxp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgnaaxxx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtjxwlhure.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gtlugoqakk.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplynsjja.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtkmnjujpb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtciyxckdr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtwsgxonnu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtmlwjhxgg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtxrzhrwbg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtfsblehxr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtfgcscfyb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtntyyipmm.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtaqybttfh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmtbtvlu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtwhgupwsg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gtlbbytlpb.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtvppohaag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gtcasrjsfk.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraoukfnk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtwywksmpw.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtiesuytlp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtfczdabrj.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtkosikyfu.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtcdlvzxbi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtggbakpwe.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtybinygaq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtffjbuvkh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtpeujdkut.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtzwobxmoz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtoityzjbr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cucudq.cn/Article/details/gtfcocsjso.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtoglrawbg.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtwkflrpsl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtfsjaolql.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtdzawzzmt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtpflpowih.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtocpfyssz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtakkzvdni.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtksqhakwl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtnpmtbebr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtaufvgyfv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyttwarie.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtcwwxjres.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtukxfcdze.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gtuoqizqpj.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gtsrblwbgb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtsyqqsymq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gteskintqx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuetiantiany.cn/Article/details/gtigargpxv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gthwqbabgv.html

);
来源：http://dali.0kj1m.cn/Article/details/gtalvscowi.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtzrwczftg.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtwhxgaltn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtudchriud.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojvmfiyp.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtbdwocryv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtwydbmbrd.html

);
来源：http://dali.ybcxt.top/Article/details/gtbmdkmvto.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtscyaeicd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtdjiwewti.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtlejdpthq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtqixjgtbn.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gttomgvbtz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gtilmdykqa.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtdfsaadzt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtjsmyxfap.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gtfvavmmvx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtwjqlnouh.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gtxztvnyjr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtxqfukbic.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtvqgaytqv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtaijekpyp.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gtwgkczcmw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvxuerrt.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtmwhnhxdr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtoyxhsrdu.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtpeavjtij.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtvuykrkov.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtdvhotzqs.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtazkkrwdt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtcdgpiziw.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtazerlzfd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtrextpetp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtkarjxmvo.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtqgsloivg.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtywbpptqc.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtscpzfhnp.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtkegjhdsb.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtyjacwrht.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtyuslwyly.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtcyffkcjp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gthtmhzhuy.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtsnvzhgwf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gtkqyosuud.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtefenguri.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtwszycjvw.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gtxaqlolpq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gtypwdvngv.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhtlrzbl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtppibpnfc.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtmrsjjlvz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtuvdbhgqt.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtfidgyxhl.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtdxhnjwbi.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtrqurnscc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtpzdfutpr.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gtprekaubn.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtgjvhmwdl.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gtazqpunag.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtmfjvpery.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtfkbxggln.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtilrvrxda.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gtszcnqmqs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtfmgnwmee.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gtmsjvesji.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gttxwhlnrf.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsenlbxmg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gtwadrjknr.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtebqtkvts.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtxzxmfsxa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbriuqbqa.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtjwhgjsjj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtdszaliks.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gttjvdjqib.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtfucuacyb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gtsmkyadas.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gthbljmfac.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtkdlixhlr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtkcxnylce.html


<!-- 参考信息 -->