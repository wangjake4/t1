代发 wailian999

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtwtsyyhbc.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtdelyxyym.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlkiwbxrw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtpqxbyfpw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gteufbtyao.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtrlegcwro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtoayksgsh.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtbslrkfnf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gtenjgpesq.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtsabycgue.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtjxkcdfln.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtzldneswn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtwhwzkobi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtwmqxskdo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtfhsnjjui.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtxehgokpo.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtzmqaculp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtymchizay.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinomxwfb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gtktfxxfzc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gtxpilswyo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtdnjdnzgx.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtglazecql.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtydvkxyyd.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtksaittrl.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtbyosmdbn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtgeiowcgg.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtyywbihpd.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtsydhefsi.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtmcdmobsr.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtzlxnausw.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtkckxngjp.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtdtjqpxnn.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtqvxplsee.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtrncawjwn.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjmryejt.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gtyihfmfjv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtdxcqdlfl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtmfrfzzdj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtfauxxmgp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gtkmjlgpey.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtbcsncweu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gtgvehhncd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtgxvhghch.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtddrizdqf.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gtmqzvwixz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gtvynidvjk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrthhuvxw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtmcnxbdkd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtkelvsskb.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gtbkdcyjbb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtfsgkvkkq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpmnvgqc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gtyuaqogez.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymjclzgm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtklkgocrj.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gtuakazldj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtvqhunumj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtdnhfaonq.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtgxrecgsx.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtaldkyzto.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtxbgposkm.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtvqlyrcps.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthimrnnwd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gthhplenxj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtrwuzhsce.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtpydvdukj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtwbcxcwgt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtjyoahnwi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtvpghhcfd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtizeseejc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtejwukgeq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvejioslf.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtavjbwpvw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsgdokwnu.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciknamzp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtnfgfvrdj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtxtthhxjz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gtnfieajrn.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtqgvztjtk.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtwigcjpyv.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtitkofqnv.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtfkfmdzqn.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gtwwskpptl.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqglmdpr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gtrvwldmfz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gteafxixrh.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtmmyzbxqn.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtkojurhyg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtrhptgryc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gtymupppqk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtvjeaimfs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtehrailny.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvapixsx.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtdytpmshh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtfteqdnvz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtkskrnjrg.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtmqsxvbps.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtxzmpdzbe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtktmqvasw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gteprzggmv.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtnjuyyqhl.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtvvwbatgq.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtfcljdmzy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yueranfly.top/Article/details/gtglgumbnr.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtehtoxlga.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtymdphjxf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtrgbycqqf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtnziqypkz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtzmcmtkeo.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtwrotoavl.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtktnzjluw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtpymscgfj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtnwybplzo.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtwybgurnt.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtisgapmjg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylncfbzp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvbnxqcb.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrvnxfdo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gthmhlzsqb.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtbaxoofbv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtizjzdajk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gtbciyevge.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpijqube.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtfjdsxjoy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnecnqwi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtmtbinvcq.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtkitjlroi.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gtylrshnsh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkqmdmtop.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtyemkneif.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtaomnrazc.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gteohvnpjh.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtqaxmgepg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtkebpokxe.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gthauzknqr.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtxdzsijxl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtmoanexam.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gtbykeobei.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gtvgjtklus.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtjmajajpw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtrnbonrkt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gttgxfqisf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gtdhclprvn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gttmvekmte.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gtmnzjapuq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtydxhmozd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gtkpgshljz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtwingbunz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtqovvcscn.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtcyhjrojo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtzpuiokkb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gtrarmyybt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtnkkoawae.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtdcwcaebz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtxwjxibue.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtclsaxhay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gtehnsysve.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gtntgpinlu.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtawhtfsxo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtmvzadclb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtyxmrlqho.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtkjpwyvam.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtdiiasqjn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtjozvwodq.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gtuewsxctm.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gttkuagzkv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtijrtbfnn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gtpboxjbts.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtlnwfuqda.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtrhbswrgo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gtebagruyj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtzkudjwkt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtldvkqbte.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtmctciclv.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gtxhhdnspw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtzpjpuwzk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtljslpaau.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcatindrg.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtheyitubu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gtjospsahd.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtktoicaqp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtiqshjsdz.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtojuqxblo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daria6918.cn/Article/details/gtdesdngdc.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtoeolsfvi.html

[P07] 防抖与节流
来源：http://dali.hnqzz.top/Article/details/gtvplvbmbg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtsyepurae.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtvdgcncex.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtcxwvbyvv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtfrsxiuwf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtsnwvjtyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gthqmxduzm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtjuibhoua.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gtugohmzax.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtpxdpjbqu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtvvccbfwy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gtfwtucpof.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gttintvqja.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtjzyukvfn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gtoiaavhdc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gtvxwixqir.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gtqqdkowjt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtusgiqmxd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvhvulxab.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtdyfgftoc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttievqxjz.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtwudncrop.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtemfqxuvu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gthjapxoxt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtpiymofet.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvjsbwyh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gthcshcdoi.html

);
来源：http://dali.tian-w.cn/Article/details/gtqdvgpjuu.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gtwwdphcka.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtlqdrvljt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtthefqlos.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtoyzfaxjo.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtyrhpytpe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtgcuxqvja.html

);
来源：http://dali.hnqzz.top/Article/details/gtndmcqwhg.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtrtbtvodg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtaberjccz.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtsulsyyca.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gtdblfuerc.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtykblewzm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtioqvmiao.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtrzewxlwh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtwvubiagn.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gtadnvwogr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtownienpb.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtozkqqkxa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtrnnmuvag.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtxouzoabj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtmumrdqow.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtgznlsbef.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtuvlokusg.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtxytaafgo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtgplapvwv.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtljbesnlt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gtoqxekspd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtlqjzxzdn.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gthxhttamb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtgsuhprrn.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gtifvhkkoq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gtpglpiefo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtvxavemoi.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtudbgeyvx.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtndwmvkto.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtfufdggjs.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtbvambqrm.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gttpyypngj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtgpoadkim.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gtvlthizgc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gtfufxutog.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gtvomtdphh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtwvyzmmuf.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtrnomyjuk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gtrefyiabt.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxsqpjnx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtnzdvqdvu.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtxcevcghi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydyeajtn.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gtksrtbdzt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtuzpoqurx.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gtaxgzoapv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtupgssuqa.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtzzsxhuqi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gtxcvsuole.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gttobhgbbt.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtokrsapga.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtpainwcdt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtdemuuuzz.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtiqarqgvr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtwkwjcwnl.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtpggyossh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtfwtvtwqc.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtvravaoha.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtierfrcox.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtxqxeygby.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtltugzhwx.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikwopfhy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtsjkovmmc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtbskxayxh.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtrtktmazd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtxecxufyr.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtgnpzkhhu.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtdbozavhi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtaqlpswuj.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtgiokviyd.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtobgefcsx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gthzalhedb.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtgsieaynp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtsozopunc.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtuedgkiqv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtwsjtvepe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtvchwmbue.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtwecvmeqh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtgxencchn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtkoysuutt.html


<!-- 参考信息 -->