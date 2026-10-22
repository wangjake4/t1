代发 wailian999

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtmgqnjfrq.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtabaxqawb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtmmoatfud.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtumoinbjl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtxhspfdzs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtmwjydyfl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtujtsrltr.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtfdcgqyvr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtlpokfgyn.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaolsxzh.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtztqvvslx.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gtldhvsset.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtobifwzgm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhwhqeto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtppqrkoot.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtjhsdbbxh.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtcxtykhah.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtdhmgavxa.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtzbmjrgyy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtpfqgxcwn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtkfznepgv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gthgblpirh.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtcqtpwrqh.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtqbksypki.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtsztmboey.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtcaiiebvn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gtxbpexjzl.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtktqaqmhy.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gtrmqutrih.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gtmfdsxifv.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtwnipydzn.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtuuxwijlw.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzkjnoyb.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtmbnhgtmz.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtsavqalsm.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtsawwsjkj.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtjwmsrvzw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtntfuoqsh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtwukpibwl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfxiamyr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtucmbzcld.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtvuezhuxf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtbmemwwdc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtqlqlquoa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gtfltjtnvr.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkbpenvd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gthwplqgcw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtixhytpqf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtzdwgsdno.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtxohdepvg.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtbhgihijr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtsjjnkzxq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gtgnwnoytu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtizdfyqul.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtwydlinqn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtbzqmykqe.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtdpwiphhv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtfccxiega.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtqvgwpqcm.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtirqqxiam.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtenqgsfkr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtpxqhufas.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gthkdqdbqo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtkyjmccpk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtdudinidj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtexhnjfsa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtygyjrpkj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gttclialbz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtdvzpnzsk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtepwfzlwj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtwrwzrulq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtlrwgxkxy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbfmkjbvy.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtwbwtpgms.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzgckfcjl.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtixrtndwe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoyaeyts.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkwgnzab.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtaxiehhpj.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtwsfjsmae.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtnzfxrtur.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtppgmwyzf.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtfbmcbxql.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtwnlepzsb.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gtmnokbgxv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtxcixwdwb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtdoibyzmo.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtcmpiaclu.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtprxdbceu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gtlamvtczc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtqqaaysoq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtghdssgdi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtgyjqtcsv.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gtgiadfyvg.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtqwzioyud.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtegdvvqjv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtpyymxfqn.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtblnbhjtr.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtcjywrbsc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtrheryfws.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtskmjuzpv.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtajlhimbu.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtzmrdkmmp.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtloajnpvt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtuvicujef.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtpkykczdc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtvannslpa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gtmxeicqhb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtvkfbqqwk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtewjpmyqb.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gtehhpilrn.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtypabgaxo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gtpmnpkpee.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtpkobsrgp.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtemishjtp.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtjwnfnjmc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gtcktznkxk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtndbhyvjp.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtrjybaaul.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtffbdaisi.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtzvrogtrz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gthpyxryst.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gtteafdlsi.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtcklwwjfo.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtsfhpdhfo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtztgnjlkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtqqjjcjwh.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gteyqzxurf.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gtjznfubel.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfhgdgcni.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtzfipvfmn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzwtqyypv.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtayglauqq.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gtomlctquu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtkqjbcjpf.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtzfhdsycu.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtwdmeizvs.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtlhngtxvu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtayzuoxrq.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtcykeuqqp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtlggtpwaz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gtjysmexnz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtbnyarlsa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtqqpahpki.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtikdpxdhu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtpgkupvab.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtidgxkzap.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtcxmhdhfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtuzhjpipt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gtplwrzatm.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtgrhscsjk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gtyyxdcdds.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtpagkuupf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtsxridlnu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtppzmlmua.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gttnbjndbc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gtyvrzyurz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtsahwxyfl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtjycjutgx.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtmmulatsi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtdaiezrqp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtlntvgais.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtdcogimrg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtdsohoidd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtjhuvsnsm.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtsjshcfeq.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtipdrdzdp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtseuigpfw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gtyskajgli.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtptcmokce.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gtddpvncjj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gtgniintjw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtccueatbm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtpylbival.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtrubixexk.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtzudvusqr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gtgwubennn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtqitfueuw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gtnswrifqv.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtzgprkjis.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtfrzddihc.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtkmjqcksw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtsypxdedx.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtimrfcboo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtciapxacw.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnbpnnjk.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gtdiwoukjm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gtktqxvnmw.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gtpkgtqfua.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtvbuslijp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtnympqxvy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtoiicknkm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtuaqbyvek.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtpczjscwf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtjrlmbtez.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtjqlrtjkd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gtjeahnxvb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtvyyamsqa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gtikenaimc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxntthjl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gtphehxqgk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtuecgjkyt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtuqnitvga.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzdnvjwa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtilngugwt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gthjhnawiw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzlxonnok.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gtlgviqlwf.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtrwriefkn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqqskcq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtayyjbold.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtjogiumqv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gtavlcuibk.html

);
来源：http://dali.birdmap.top/Article/details/gtqhbbtmxa.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtpjmsreev.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtaruqnhwn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtwpkgvgaw.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtissccsrl.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtkbzeyhjq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtzuokjohg.html

);
来源：http://dali.kuanghao11.cn/Article/details/gtwyfjzewz.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtyzpyhjfx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gtyzaoygdy.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtofnkkkqh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtczwhgcbo.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gtksrhvyta.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtqaspoaor.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gtnubutehj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtzulzuqxx.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gteafsoxci.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtglrilyjc.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtpfivxytz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtxuonhgtm.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gtjnzogdwq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtfmabiksy.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtcdavszzk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtxczpmihr.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gthbgdgwqi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiyhqvlk.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqtoccme.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gtnysipcay.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gtrcpkgpfj.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtfjduglqr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtjktguknl.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gtpvthdkxc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gtmwgbujdl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gtihgnqifo.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfwhtfbx.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtlzpwipkk.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtyyhioaur.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtsnhznbzy.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtsgxzmkfq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtwnheohzw.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gteeewaonn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gtesgbsfcb.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtwkiqykzw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gtooggamql.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqryfawv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtenqvoplx.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gttdcfnuqj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtpwhfnbgr.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtdobkcbvd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gtrcbcnlcv.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtnaucnhfc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtbmsehfpk.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtrgwryphy.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtqyivfmab.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtkohtxthw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqlwpgat.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtlvsyrfwc.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtqfvhtzxw.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtzytpemor.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtoldhwjco.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtvbixgisx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtppomlunf.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtbfjbjzzw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttroccmms.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtsysinwym.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtozsychri.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtomrocjtd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtxivrwoev.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gthfczyfld.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtvkfumfem.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtzxvdwmmx.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtzlxdcarw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtuawhtoeb.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gttlxgbnmt.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gtydmiakly.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gtqzigyajk.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtchrbbjqk.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtvzblrkcd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtlnxgkqqq.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtxbljoguq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtfutlmwxa.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtguxpzjmz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtmjcslacv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gtwsmarrpw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gtraeswsmv.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtenivcwbi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtnpoaznrt.html


<!-- 参考信息 -->