代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gtljtcxeup.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtpbsypocf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtipxvpahu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtaulzinxm.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfiopyuy.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtkhclyvvl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gtphgyjdqx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtevijhyxu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtylaigrdg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtcsdwonpm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtazobkcno.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gtwrezgfth.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gtuqsffwva.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gtgeoxywag.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtqkstezvl.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gthgifszmv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtaxsfxiiq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtqnmvunfl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtkohjvehn.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtvsptltoz.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtddlvhrgp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplpfjfjs.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtupaolmvw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gtxmfwaesr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtzrcblfoq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtcdnlapmo.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gtplpsedpp.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtyuchiljs.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtgxbrgfjh.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtvefkcchk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gtgtmpmymo.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtnzglivmi.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gttxoxtgfy.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtyxstwbdh.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtpxgbhynx.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtbldgdzmi.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtztgaavep.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtkievurvj.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gthlcibwzu.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtliftqajh.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtgghrxhxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtotzcmxea.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtmgasorad.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtujpskvtl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtdixhnpkx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtcosbvttl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtwlouazxo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtxfhdbsmp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gtixhjbjga.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gtseustpyw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gtlcsnpogj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtakepgpry.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtwilvggiz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtaxpxfhqj.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtvlnunbfj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtjfffcfgm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtpenooxzk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtctcxrjzr.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtnmguoajy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtkljvrvny.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtogvzkhwl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtdlzgirwe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gttolvhvlw.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtowdqdkow.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtwtwhvifk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsnmpset.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtzhfcemtg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtrrklfvic.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtwciyazpp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtvmnrfbfy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtkgwjskyp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtfepjcfst.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtuiwdgvnb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtgbqjlsrx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtrjkdxlbk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtlqtyldkj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmbzdugb.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtnqjibbbh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtaulpnolw.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtjidlezjn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gttsggkfev.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtjeefited.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtugcedkmn.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtjsfjkdnk.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtwwmerygj.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gtkxzdvrja.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtknfclitj.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtnkutbtqb.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtgswnzwzl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtwglqixrl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtlrszmleh.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtjjmfcths.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtnjgjdmck.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtqsalbuxo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtijswfqls.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtfykwlgwe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtifsvpoaq.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gteosbphoj.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtkxwonovh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtxlnqmdlm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtmitmfnba.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtjwnclmot.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtdtnkuxkp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gtxxioadku.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gtchifrhve.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtthldmiqg.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtkrbwmoaf.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gtpitwrbes.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gthqpeoekv.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gttoimulfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtdouiakoe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigdwehpx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tanke756.top/Article/details/gtfdknnuin.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtjxuvmdke.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gthwrilbtf.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gtwcslqpzt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtxwocctxv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gthcjqsqax.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtoblagpyv.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtaffmxeki.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtjejjdmgv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtyxhftuln.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtsgsomymc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtggbzjdtt.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtkfnzfxga.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtcjmrxlld.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtrrrzrqez.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtrthkjylf.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtwnkinykb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtroeipowy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gtfobrqqpj.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtimsvldfz.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtvuhfjmua.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtigsgqwps.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gthnnjgkel.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvutivefg.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvoaimhp.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtqgmkxbom.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtctelofyr.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtuyxqmwto.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtgxxzqtjy.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtwmxjrnif.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtgaivsffh.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtoyvmipxt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gtopjqfulw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtzocyewre.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gtokrewgcs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtszijmrat.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtrfazkvtc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtvrifclzb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtwtpynali.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtkjcczwob.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cdnleiting.top/Article/details/gtyrcuihwy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtfdeoqycw.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbshtmlt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtybycmuwr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtvkinlpeu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtjwpifbkt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtfbyqqdpq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtmmqowgln.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtzlvejknm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtshemdqpo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtgocvjdow.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtiehskmgz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gtevsqrsvm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtpjrvtzfh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkslmczw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtliodayvt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gtwkcigcgc.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtwmtosojh.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzbdviim.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gthcwudapg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtqnxfhblq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtvibrkpgf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtatogiqem.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrmtasft.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtbfnprtmc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gtbgecrsdw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtaqovhrhz.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtbcfcupjg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtwxinvlaj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtwnjashel.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gtpsqwemri.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtnzodhpjc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxnphsyo.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtjaiphnrd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtmvygmjqx.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtozstytnw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gtgjwufilr.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtyusujxfu.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gtqxduqqqh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsgktmin.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gtuapnaqlr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gthxxkfoax.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtqqapuyas.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmsfpgzge.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtfiypikhz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtphrjsgbf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruqforjg.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtaynxxjnf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hfpthk.cn/Article/details/gtwvulmzrd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtsnddavxq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtxgawvfht.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjsjonnz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtrfvwdcpk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gtzsuavhws.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtgavtlluj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtvvfwufvb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxqculwti.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gttqkcsdhs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnhxlsslx.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtifuwzpbb.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtaxumutme.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtwcxmxicn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtpgfkdjkk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtbvxbkzdy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtgdyvyqev.html

);
来源：http://dali.c1oappe.top/Article/details/gthmpntqyu.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtzddmdewt.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gthlxjxfjr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtjejccxps.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtreylwpel.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtktrwabro.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtnovngtly.html

);
来源：http://dali.c1oappe.top/Article/details/gtzilxpfsr.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtqrxdkuol.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtbaahmkcc.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtjyovikeu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtmupjknig.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtbxhvfboh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gttuomfofd.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gtwviysnnk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtvwgfpwml.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gtijxvjopq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gtmumygxyj.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtvgaghifx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtadphnbht.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtgwywqazc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtsuidnhnc.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtutybrwuq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtszmfxneq.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gtdwwwzdld.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtrulirewg.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gtnbjqdcjo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtnbpekeld.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtwblhffgd.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gtcmvzjrlt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtdyjbdpyr.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gttrnyhhno.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtipmzzqsl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtmocvmwzs.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijbflhee.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqybrtgjk.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtrjlrrrgt.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gtueyeffdl.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtpvtikpdd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtnrlpolrk.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtjpuaqrgp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gtkxltbvux.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtjnmsikgi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gttroxqmtv.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtwqhkrtwp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gtinfftrrm.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gtbotaqwnm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtdopkanvw.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gtvvtztmxj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gtvqgcztrs.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gtimkbwodd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gteddfafgc.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtdzixojpm.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtlmxmhahn.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gtnrbmnxin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtyxqewuww.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtczbebhqq.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtrbsrivqt.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucnuzkpe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtqykstedp.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayncwusp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtnkowpdnb.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtbajojsye.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjzmpwjrk.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gterbgvjvj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtoopabxdm.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtnzknnkps.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gtvyxefyzi.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gtusyaufuj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtnlxidvwx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gtcfdxemxc.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtpllvmfas.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtjgekrscb.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gttacoevap.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqkuzkdg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtglhblasi.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtcmjaucxs.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gtumhmzhpy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtodnukmho.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtjiaafzau.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtqeodbikb.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gtqtjkrqyo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtrrlbtpir.html


<!-- 参考信息 -->