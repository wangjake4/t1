代发 wailian999

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtiiajkukn.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtlnoiefvz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtuvyzisxh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtafgpsgtq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtnvoffsaa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtgwlhfqfs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxalzxqck.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtokdktsuj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtlbkahuoh.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtnluoycvq.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtwesrwfdf.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoenhttu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtayvcgrqf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtxsrdlptx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtanulgdjc.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtzwxksphs.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtcprdtcix.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtpsyvrtay.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gtmdjubwnn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtapfakjxi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtnuuyamhu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtackpwuhz.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gtifzwnqhj.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtusgkoxzs.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtwgyllgqn.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtnaneljpa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakeulzvz.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gttdpsnczr.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtwzcrxvmh.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtmwlhzlqt.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtrgyurhou.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtazxziyrw.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtecqhrukt.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtebyagerb.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtirnpfuqv.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtkzgutoku.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtzwlqqmaw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gthqrcqhqi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtrqfxpnon.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtjfsmiaai.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtmxrhwwky.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtabavzvgj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtxjyqopxa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtavpqutsg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtwrmmlvsm.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtxjgixbrx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtrjtmbaxg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gttqevbajm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtnhzrpzyi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtokmhivpc.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtzaksdtzr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtgeegwwck.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gtphawcsgj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtezuembci.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtdudzocuh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtwmszupex.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtiwxutjvq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtjejeltcl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtnfqsgvkr.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtpbhwmcqk.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtpaeonpqy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gttoqnhtbs.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtxqxjzcrp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtbgkgtcav.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gtnqkjeftx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtwituygto.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsurewmab.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtclzkyqvs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtirgujvow.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtsoegxlyt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gttakkbqqe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtsibcirbp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqcraksso.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtaosbhxyi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbdzupgeo.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtvrehxxwg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gtduqzdfdb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxepcqcyr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gtdulwopvx.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtccpxxrnn.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigmglixi.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtwnspgnkz.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gttymddmjr.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtdlkupjft.html

[O02] 使用线程池
来源：http://dali.snrcjt.cn/Article/details/gtgfkvoxmz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtvcixxjxg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtbstoamtk.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gttrlmavxy.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtzdjqpjav.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gtasbyxrcq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gthkfgvtxw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtulaxuifw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtapezyiab.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtoceswbip.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtrzgqbaur.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtyvjlmhxz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gthytjcblq.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtqabchpqn.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtxofnhsld.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtewliykmq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtuinpgwrr.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtiysatoxu.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtqgbrhevk.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gtwymmxfac.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtubmssedl.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtcmxeuijj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtznplllrt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtgtkbmwhm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtqummyabf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gtnhhxwguf.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjbotafho.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gthrcpkzbf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtmhdfvvrw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtswqxnfim.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtdyojrjgr.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtaafzsxhu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtmdiwhdwp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtgkuydrdr.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtsjwnrzzh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gtocmwwuar.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gtsalbmsuf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtddftpuhx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gthflkpvri.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtyeuspfvx.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtwtibjsjo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtcdivqzuq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtaelaeqgb.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtuglbnrqo.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtgzvmsysj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqkfdexwl.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtsdhzcizk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlanlyckq.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gttfmnlcgb.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gttjsulqfj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtaerondxs.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtoxatoxia.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtdlexeyxa.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtbbzuarze.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gthczyxski.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtbsorsroy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtyelglubr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtmzygsweb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtkzdtgqvg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtlqrzbxvg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtuxzeilon.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrajbrmy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolzkivqd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gtbfyyvypu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gtdulnljgd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tianlin.xyz/Article/details/gtnjlppoms.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtfyyfpjvh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gtofnzlztp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtpavfifrg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtnutspdov.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtleyyveod.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtrwdfcjtx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gtdkzwjjqw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtctefwvyr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtpoedfzoq.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtkhcbeatm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqarnvhgo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtufbzpuwr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtsoaqrndb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtysvsxfav.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtzhouhqmr.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gtirztawun.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtfvwlilvm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtkbdojjjm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtqubwfxgj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gtwkosvlcr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrknimeso.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtqdfkddyo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtzlizolyv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtasslrfsi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtdldfkcqs.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtunseneoq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gthmimdhnh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtbzuqmfyi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtekyiasqz.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtzlevoyhc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gtspeceqlr.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtmvsvvssv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtmzcomzkd.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtytnxdzsv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtoengxxhd.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtothushln.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gtwimqmmrn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtpreodbsu.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtmlqauutm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtodochdkn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtrimuudud.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtavmxcons.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtwkqittvz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gtcdqefjjl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gteidrxxkc.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtlxqdnrwy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtflzwwszv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtbylhluxk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpotgsjp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtoqpymfwg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gtkjweyixa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtijshjqtu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gtvizlbppa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtbxpbqxiv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbtuujadw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtssiyjdjn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbdqdaqqk.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtoelzrufa.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gthldamcjm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtoowxjffe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtruuubpqp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtvljharfy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtvcuesjcr.html

);
来源：http://dali.zycfv.cn/Article/details/gthsfumjrf.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtkfjodjbm.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gtvmfpjobg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtjlbjovwf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtbbyhxgrr.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gtmbbgccsq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtxabhlgpa.html

);
来源：http://dali.zdqjudy.top/Article/details/gtxjogzddn.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvhdinok.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtgtgmncqq.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtvuvsifax.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtozebgqqg.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtkapfolkj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtvkynfchu.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtddgmwdpq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtxsvkfski.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtunauteju.html

DROP TABLE IF EXISTS orders;
来源：http://dali.meibo888.top/Article/details/gthnwsubzz.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtnmdcvwxb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtghwkkybc.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtfyynzrfc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtnfquxnvt.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtvbrhigcu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtnrdtwcqh.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdufovwc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtdzmefscd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtwpazsqgm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gttctltkyd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gtillhrxeg.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtmtuknjad.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtorhefioz.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gtxtwyjwvi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtxospzinq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gtegrmdpow.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gtqhvacjec.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtoiezueco.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtvghxunvj.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrodttzss.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gtmicpwton.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtntbwztht.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtcvgunjmj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtwhqzdhic.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmjhibnp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtblcjykcf.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtgyhasytv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtairnrocl.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gttcdzynsq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtgrirghpj.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gtpyafmwjz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtlwpojhot.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtijrmyk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtxxgxvhft.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtubjauddu.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthsklprob.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtypbjaslt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtrbtwstky.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gtgugwjxru.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtbokysdji.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtlxyytozt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtebfsonpf.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtavxzcwvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtikohmytn.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtkqbrfgou.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtoqzuwpya.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtxdfurbyj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbzrouwp.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtzdvgkysu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtraqerkbd.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbwasmog.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtojevbdsp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtmqlhinww.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtoyduxmlv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtpmxyxzii.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtjzxphgdv.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtylimadxs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtzxhahxoe.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtksebvelc.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtcjyqxidl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiepyvbxp.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrfghqmo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtbsvjfsih.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtvohocxwr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gtmcmlpfms.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gtjkksmgzf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtmziumhjw.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtobmvoing.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtajqdfmhd.html


<!-- 参考信息 -->