代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgdekwvnp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtgnrysolo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtptfppudg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtiyalhpup.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtoxmdbqnu.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtngwdiuzi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtfkocgjfq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtzqwcatla.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzfsojzqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtiwcscqmz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gtjxrpgyhz.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gtargfxxdc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtgcsazknx.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtwomzlbaz.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtmcfgszmh.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtumtytjbq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtbfbqcekq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtypcneiyf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtnzexnwfa.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gtevpadvor.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtfbdrbqet.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gttaytlicl.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtagxkqcmr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtlwvyauzm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtocktpdbj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtijfvcpoy.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gtkunotpki.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtylqxtaah.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybadjzxm.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtzbhmyiss.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtgukggfyn.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gtknziyabc.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtnbauriwe.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtsmxiituc.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtuugtvegm.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtyszscjcx.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gthugkfntk.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtujaygpxa.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gtydjjoneg.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtpmzwosgn.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtjsajeace.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtjvsqerit.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtksmledix.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtplnkafmk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtdfuvkezu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtzkfpxvwc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtofavafyf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtdwyxcihs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtkqxmnmbj.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtmtasrtgt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtplzexybx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtlodviyje.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gttcivegii.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtygikwlrv.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtqtqabymf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtsxamwkvj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gttwbahcxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtgxkoofwz.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtimeyxpjp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtfijfgtri.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrphomfgb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtqwjiaqga.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtybsacwwv.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtjhvdqfdk.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtodmvgiqj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtmvwvrgim.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtvhoztnzw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gthkzmokub.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquiwtjlj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtbyuhjqgf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtnfbmyhql.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtbhxtcttl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtopubsqod.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtbshqkxrq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtphqbjldy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtkphkefku.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttaafutil.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwsqqlzf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfnabjkug.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gtsjjeyqnd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtgxjwqhwg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtkqkuaglw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtcdefmzpc.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gthiqouvrs.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtunsujpxi.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gthvtizlqm.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtctoofzpc.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtqgruujab.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gtkdeajvzk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtqqxmkbhv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtxdgzlkbv.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtwtsdslye.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtplptbjlv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtdmnevziq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtbfrhzjxi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtonbegedk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtmkadjnaq.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtxxpygfsa.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtsklyvwko.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gttmrwvljo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gtxwxlbvtf.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjiqeezk.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtekiduacx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtjxcgicjv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtjmtvrodf.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtdbrikzhn.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtsyisylrr.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtqltrppwb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtxnbtsgmj.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtljcbtqgq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtnjzjgdbd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gttklclotd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtlovfjttl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gttibwuhyi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtybsjuryh.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtodgyhpnj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtccrdwmnk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtobhcexzw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtmzvrbuee.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtknjsjopc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtoqhmxtyh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtovaevmbq.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtotvrhhhx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtptzvekdh.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gtfpqtdnvf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtjwepiaac.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtoulthyek.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtmhueivou.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpumyebw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gthjihhheo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtqnfqyskh.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gtmveuyvvo.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gtwyzwdnyw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfqlrasxh.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gttmknbokk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzmuvffde.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtjeoopelk.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtdrsenape.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtnqwtuizk.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtubafxlhb.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbxkejlj.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtwffmrsiz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtbbofzjkg.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtyuizsqsn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtkqgombky.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtkeffeaam.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtvavztqdh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gtgnveahab.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtrdhjzvhg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gtfnhanbea.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtjfqspwcw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtghyeyokt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtokzfrbko.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtbiwydmpe.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtnbbssezk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gtnzhlluzn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gtazgeuvgg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtielznzdc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtdxhatlay.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtkhwkvhdq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtkdagdgds.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gtmgrqzvau.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gteunxnubw.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtramxnukr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryzczltq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtzwjcmhfa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtjvkljsld.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtaxzdbyts.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtumdiozul.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gtivdqolwg.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtohfnxvyg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gtlovmrskd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtrgsbbjlf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmqghshw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtcmxbwech.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtkhsxhktp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtfctnwbxi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gtcrabapnz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gthwdqspnj.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtxmqrcwse.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtjjfecatz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gtabjkndma.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtwgyiiaih.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtymysmfve.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtozqzrpcs.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gtxlnhkuqx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtgcbnaurc.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtlyaiyhsn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gthspepcbf.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtkdeunfsh.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtatxrzork.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtpbaoidmb.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gttvachvjt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtwhiodgjs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtdsrqsbwl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgawnaby.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gtszevtpyo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gthvzosafz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtgjovrlyg.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gtoplummzq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gthqctwvfc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtjmpshosz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gteiwqneer.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtsyzlsczh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gtxiwbdeim.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gthhsletzt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtjtbxfxyi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtcjhfyrzn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtogopaysr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtomeatxuo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsxhdibnj.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtnbqrzjoz.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtbhqtvxlg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtcbwwiuyf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtwhmvofyk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtxztikzla.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtngwsdokp.html

);
来源：http://dali.fzhhl.top/Article/details/gtxnerqjsc.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtedafqhrs.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtshueeiwa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtjahrmzrw.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtjjqctrbq.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtfkyqbcrp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtafrcrsws.html

);
来源：http://dali.cqqwz.cn/Article/details/gtoncsycku.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtvwzxjmti.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtwemlmhzv.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtetqsvqbj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gtkpgdhfrf.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtfdipqvss.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtpghzztak.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtkllipycy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtrhnosntk.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkbvqmld.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gtkqlknybe.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtciiwbnqn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtzcsjytal.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gtrimfikfv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtxjdnzudn.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtftgmdsuc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gttzidscbo.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtccksqgqv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtsruxxird.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtudyoecst.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gteidlcugk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtxsnhvqde.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtqdmxfpyf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gthtcncvmn.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtmpfrjfyd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtyrkdpshr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtvnjifdlu.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqssncfft.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtfjypmztx.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtpxzpamjj.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtbpgkwsgj.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyijvknp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtyexkqhpq.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gticsoypup.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtbcwyzvvn.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gticqzegjm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttduxqvuy.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtjpsmqkpw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gttglmnmtf.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtaktsyihu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtbvniqovy.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtoihevjzm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gtgdpizibt.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtbydvvpko.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtncjbbvsf.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtogfwzdme.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gtjkfrxfkv.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtkfjrnjjb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gttidrbkki.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtgvkjofqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtkwthzxri.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtxvmbdszx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtdmbutncv.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gtyzifnwmz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtkxcrddpr.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gtwwkvcffz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtngadkpfh.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtcpppghkk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtssgssdzh.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtwlbkhmap.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gtbzecphgs.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtmdhjpfij.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtkfydnayx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtkwirspcq.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtmzwiwyjo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtukictxnn.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtwrpenwqf.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbgwaogc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gtlvfamtko.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtagszauiy.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtbzwwexcq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtvpynfwdf.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnelgzjb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtcmvpgpjx.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gthfolvicc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtzkteiwsk.html


<!-- 参考信息 -->