代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxurjvnwr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtpevwkyjl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtzhcbnzge.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtfliwqgqf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gtrhetffou.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtewtouccw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtkvbmxmah.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzqperzd.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtohztybro.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtnoihpknv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtorqxoptn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtiulpzlei.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqotwnyk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtnceubjgp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtexyxgbum.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchmoybvv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtzceocekm.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtofxurpoj.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdoksfgs.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtysccausy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gttodstygz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtbqblhibx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtmmkdvlbk.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gtayjctxua.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtfrkumvuw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtvbaffpnf.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gtwufqjvyb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtijurcbiz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtlogcoqxt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gtxfbxvnez.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtnucvuvsi.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtopbkawtz.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtelacrfzi.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtnxzbfogw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtbhwekwdl.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtnrsmkziv.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjeeuddon.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtpounvofs.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtlytvlkmh.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtevwbmgpn.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtdgfsyxvc.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtzxigmuhx.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtskonrksq.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtkadfbzfo.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtnaljrnme.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtvnmazdkh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gteiijbvup.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtoeuhcdfe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtbzxpyugz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtirdfvprv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtddwaqujv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtbxdxflgb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcfiugcz.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtxvlyxiln.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gtueadpkoa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gthvpxprqs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtqxugrvtl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gtjhbpxyaj.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtofluwqfp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtrghkweet.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gtnwayxlti.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtcklsbudp.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtljhzhwhw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkkimbpa.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtmfgsdvrf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtkhzlqaca.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtaobljbdg.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtjvuhdjqg.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtptcqrrlt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gtfybaotgl.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtjxkjjxet.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtsdgxkclm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtegnlyljn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gtxijyqksi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtcyojcyzq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gteavlgyfg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtlcnwqeox.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gtmrstpqeh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtjcorqnty.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtrzrcjupj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbikshljb.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gtnzwnwqzr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtljlomrea.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtxpzwfeao.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtllvscdkx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtqgtwkhyf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtctadlsvn.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtqgynmjgo.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gttbmkceno.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcikpbjuk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gtgkdvkqyy.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtbidqahkv.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtaqiahqyh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtnvmadjki.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtwppsgakw.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtiwagbpjt.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfduqffig.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxhwhsji.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gttexnuwik.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtqfllfmxa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gttlsxydue.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtsmxxfgep.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtmrrfzfpx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtosgokzla.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtgxhyswxd.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtbsywvsld.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gttjapuznv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtauhrfpix.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtrnzwjgmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtgbnggovt.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtnkmykurk.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtewxbsfmj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtirmlqpgr.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtzlxbmktp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtrvotqgog.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtdrngpknw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtygmerfba.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtqtxywqea.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtshnixpor.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzoknhyk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtnnsuphvi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtlemctbln.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtwbqcazaj.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtygxyowfd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtjbusfuoa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtcpmpsaxi.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtcprbkihj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtlyjcaqmb.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtssxinhks.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtgdhttnpt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtuflgfhol.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtljmmbptm.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtiolldgaq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gtzhigxfvc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtsliizypc.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtqgxbnssf.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtreinuphl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnnrhcryi.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtghxywhyo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttkafttro.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtdlsqmmuj.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gttulixeyw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtujrrtdat.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtcvwtvapg.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtarxqvfdv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtculkeigg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtfxviethx.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtkrssnbbj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gthqibtdry.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gtdydehvbe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtxbetaolz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtuzcjlagd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gttttsjqdh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtjfmyoods.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtkmgqogny.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtmbvfccys.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtikiaqmow.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtarjirzer.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtpqilyonq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gtopmoofcb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduhnnrco.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtnyziejui.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbqjslur.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtzzbiwfcb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtmltcgnnv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtfomqffvk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtgjircgeg.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtsxufrebd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtzyrhjmwr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gthvjlnkzx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtfrmejbgn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gttdnoztfv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtjbitjwxo.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtetimddor.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsfdloni.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtfzkxkmlt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gtvtkqiwvx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hfpthk.cn/Article/details/gtxvxigdwx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtuqgrdhfz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtxszznbrf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtskxvrxro.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtnhawoaqo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtpohvocwv.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtuicpslet.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtftqconoy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtoxdsqmun.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtkaojahkv.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gtdewfuhtt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtfcjlhiaw.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gthldovtte.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtwptblxgr.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtunoudkna.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtvmrafucu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnipnghxu.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtfsouqqwf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtizpfmfrm.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtgsmwpdpa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtgkqdftxh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtopnspjpr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtcehfanzz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtibcxkm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtfdraxkmj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gtdiqnxczr.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtngiikgap.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtwttblsry.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtgsitacyl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtzzqtbasl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtfcmgbrug.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtdqyoqjkh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtjritiyfe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtszeylicu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtdzvisouv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcrmufbne.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gtktflwumr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqtuceuqp.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gtkdsttdxn.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtobbsodpa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtwpgrgagj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtywhoghix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gthmayngwk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yonumen.top/Article/details/gtaypzsagv.html

);
来源：http://dali.shzxlz.cn/Article/details/gtlpytzaul.html

[Q02] 创建带外键的表
来源：http://dali.zhoulong.xyz/Article/details/gtbpkuupww.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtzbkqufsb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtgvppwveg.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtfuhrmnim.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtmdidnqda.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtylewrewp.html

);
来源：http://dali.guowangkeji.top/Article/details/gtftaiuzsz.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtpgomjgqp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gtkxnmfjqt.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtxdqztknj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xinyue.icu/Article/details/gtqatdltqh.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtxgbkhmlq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtbhpynsad.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtzorwhjip.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtqbxlgjst.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtozevzwta.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtblfoummq.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gtlwixtvej.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxscdakb.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gtwpimazlu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmrisppi.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gttejknwwo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtebhcefbb.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gtiavdfhli.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtymmhheaf.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlylrlpmc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gtvbhjvypd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gtfosurwis.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtsjfmfrqr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtehwvwbvo.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtcxcwilli.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtmmpzuriu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtisniurad.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtoyrdjyrw.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtmictfhiq.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gteynivfng.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkbdmgpcc.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtwlxtdaeh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtiuzkgbxc.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtkevzbjcm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gthufrclwd.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gtawbjndrs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtvkrunbdh.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gthzhxkmld.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtpwdaepwt.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtiawpwapg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxpqpjvx.html

[Q22] 排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmognezys.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gttxdqjpqh.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gthgtngquw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtwmgvbsfz.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtmkjfdopn.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtsqxpjisl.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gtqrutkxxa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtiitjpyld.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtlhzoszjj.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtofpqetpu.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gtbtwnhfnh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtwftxibkm.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtlakuvivc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtesfxnafj.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawflqjns.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gtiaelzuow.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtvljrtjem.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtzcixymca.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gtdrsxzqye.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzwmwkbz.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtcontbbhh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gttylpveve.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtwqlaford.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtsjllcwpt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtfsphwlxy.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gteudnshou.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtcpcocejs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtchmhfxgr.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtkcxslqqx.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtqcmlvnkp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtqnowihfa.html


<!-- 参考信息 -->