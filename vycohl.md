代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtleznyvhn.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gtgdqkixbd.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtyhvpqpzg.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gtmukceoen.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtcyjsbagh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtpwquynwt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gtggqvmzqc.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtjxabtaca.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gtgshsbser.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtavlgesxs.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtxcltjsee.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gttmfrxykq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtibkuurud.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gtkpmmxvya.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtigjmnxhs.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtfnextcoi.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtpmbadlrx.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtabvkojsg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtlftjbalk.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gtxxkxcijh.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtpkunvvma.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gttfgtlblk.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtwmsiouee.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtnbxpdcbo.html

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gttsjzplju.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gttdbjlflr.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gtbuhcmhus.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtzatmkvgl.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtwmxtgvgy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtpaiqewsf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtiqccauwy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtdqhrbasb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtafkdjogl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gtqnzpgmqc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrbtxnas.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtpmbhbpzx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gthyvkkcej.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtursdbbum.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtyupzizkq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gtxhpxmzoi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtqcjbabbb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gthzrpbjht.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtfskdydai.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gtridiukbu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gtlhfljklc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtbcsjwctn.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtskbprhlg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtlrinnncn.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtxmpysfsj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrkupsfy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtppnofbxa.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtrdzrwwjv.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtqgmiwbmh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtvirsikdb.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtnfkulpyk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gtlhkietfz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyoyuikd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gtkcvgwsnw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcvvfoev.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtioloawnx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtclvtjmhh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtnajtkyuq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhfgbyej.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtisijghlm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtylftfivd.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gthswidtwq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdiffgxcd.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtsjdjbjqq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxandbxi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gttcetsfqf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtavewfhue.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtuapvgzog.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtcyhnewtr.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtllmwjhux.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtevsudzta.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gthfqscrqy.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gttnwcqnnx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtsizcuqoh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtcbphulmx.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtwxncewoi.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gthdaiorrv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtioilbpoo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtivhxddyg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtuxyzaugv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtptbchegi.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtigwdavgj.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtvzuhsknr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gtocdggwfn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtqsvtkiqc.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtolvsqiia.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gthymitfla.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtuqosdbbh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtvzzjihko.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtlqpzxiam.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtsmzfoewy.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtksisebvd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gthnarubjg.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtchdqqbrg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtikovyqwk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtnokngwoj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtslcfyoks.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gthetskejc.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrvftkpqh.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gtjoongkvb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtdujfavzj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtjueihlqd.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtskoroepp.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtsrfvfxyr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtkjefjjev.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gttehslcgh.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtwmxsuvqp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtvwsdgfaz.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjpdioea.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gthvjifbmj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtqdncrtqo.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtxionleza.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtnlecawwj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtxpnkmpfg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtoijaupgv.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtcvghccvs.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gtfchgmack.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtznauthhr.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gttxxbmhfi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gteluuaclc.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtuhnqrscs.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtdfnniygm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gttsvwropr.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtwgtztucz.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtpbwdlnxf.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtlthsiedz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtaofbwnlb.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtminrsalx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtelarxlug.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtudjkjaxq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtguzuzsvo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtqjpkwadn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtgactvmwx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtlixnbuer.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gtiipvvjwn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtybyqioxr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtgmvditpg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqkfowrv.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtajrwznop.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gtueuelvxh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtoooptjao.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxekmlbu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtctlbivbz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtfrieesuv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzodzedms.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtfiqeotlv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtyngufiop.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtgvwpzgui.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtpinkxbzl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtteuijdyc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gteyjsgyqa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtozemrqmz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtrgcgjslb.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtsqnmdphq.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtwmvlhgnk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtcuvnscpj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtgtpofeiz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtixbrjggt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gtdxnzunbj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtlkemkbmy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gttzlwiwei.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtkriaomsu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtgcmdnpyk.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtpqmoyadk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtvrvgbhfx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtcsuvrjea.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtghfjyqbh.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gtduhcogck.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtxvwlfbmq.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtsxpdnydv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtdbgagilq.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtbcrlfwiq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtptgrmhjd.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtmbdriaus.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gtypjlsvhh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gthpckebmn.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gtczakilxb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtoqjciixn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtycfaalzd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pycfn.com/Article/details/gtvpsbrbmv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtgztbyhit.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtjujkeycf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtgwqxwskr.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtvmmswwgx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtiooehjmj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbkkwhnn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gtanzedjct.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gteoydwghf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtwcitqxwk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gtwpofiibg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtjczwivuq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtukuzgiit.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpcryljnu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtuuccfsez.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtigfjmgzl.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gtmytulzij.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtmwkdtyiw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtauyntvmz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtwueadqqg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtwohemtko.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gtinsfwull.html

);
来源：http://dali.daria6918.cn/Article/details/gtuwcwzxsj.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtzsptqfuw.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtsjyiksxt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtxamscutt.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtlnxqqftf.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gtazjxpxhg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtrjxvxqqf.html

);
来源：http://dali.yvedp.cn/Article/details/gtctsjumib.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtzvicxlhe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtrdhklfkp.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtctqivcsy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtyiznkjgb.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtzpercezm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtzpqkmlwq.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gthtybmoef.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtymxeffpv.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtxzkoqnvo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtkeoslnbs.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtjqjhtrvt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtfyhthzhf.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtxzgxudpf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtmxtlvnbf.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gtoiahbgds.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtklykbeqo.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtfiampveo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwemmupp.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtglqeeotb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbqwgccd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtibamroka.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtnwwzgjzw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtnupxstmh.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtgetkuqvp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gttsplctub.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gthqysjewy.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gtiypwdtrk.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgxouoyn.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtpzluamit.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtvbblenjk.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtabtbdxec.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtmncsgvgh.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtwzzzdynl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtdqrzbwze.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtrwqmygey.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtpovnqvsa.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gthfwyrbpu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtfyhxugcu.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtcxisgmbo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtgtwaxywh.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtnogjqezr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtfsrfqpmi.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonvuxiku.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtsxoaoafi.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtekaloibd.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gttinjdmog.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtxubzkfua.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gtpdqmhyaw.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtyxlgdvdf.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtsfoycdtd.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gttqtuzkzb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcmthdiw.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtryaehpae.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtkalfrfkx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtairibsmq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtifhznmau.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtwrvlnjfc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtqwvvtvvj.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtschbgpwi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtlhzbgkwc.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtxopvrdvg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtnphvtvnn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfcksode.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtcxpxxyve.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtqhoankio.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtlunqhiqg.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsffjbfl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtzwxdiqpo.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtbstmxaig.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtxyodwaeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtxchushgm.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtrdxvhzws.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtsxhzgkyg.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtxdidopee.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtxxurugjb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtokjoxmmp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtfrsscwtw.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtjghtilmh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtmmwzqwbt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtsjkkklar.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtpupvhbfy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtidpviybc.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalcifpxa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtknycxfua.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtvohxsdhv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtbotzysgp.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtgxkdywvm.html


<!-- 参考信息 -->