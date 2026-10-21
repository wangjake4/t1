代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdsbjdhdy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gtsnghpqvx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtgktfmhho.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtfcgldwhm.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtvojyqxea.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtsczyigks.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtvdmwzssz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtmzgsqhxd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtytpqesks.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtmmakthno.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtvkapazck.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtqvyxuqin.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtloclboyo.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtwddadddg.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtgsizkgtv.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpxndodb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtmnyytyfo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtfzjfxsrk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtaneenipa.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtonirnege.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gthllsmjgc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbgqlxld.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtwaeykayw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gtyixedjln.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gthxtevywz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprbnbyjz.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gtltuwecow.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gtlozsryap.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gttwtkunyw.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtxmjaumzj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gtjoeryxup.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtyuiccirl.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtasllefop.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrykltgls.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtjtfymxka.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtvjsemkbq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtrbjgmxkc.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtcompdvvw.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtsapdirzr.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtnjqerfcy.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtbiixgktq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtcbjvsgsa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtueyvohvh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtaznohzev.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtdpwziaie.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtaybewoyz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtqleatukr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtstyqtley.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtqddojswu.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gttljqlckc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gthmzcjheq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtbptgyxvb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtgeqkxkkr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtvribysal.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpndccwo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gtjqzsaogv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtscgandqr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gtadewcvsi.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtfkjrwrfw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gtxyduvpzr.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtxxbyozym.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtkdeorwzq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtlhwhnwmq.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtcuagglss.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtqbcondpp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtdfyieltl.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtvsqhnlkl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtvjjwvwrv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtillxnprm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtbwjnnftr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gteosjvtyt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtrxustcvn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gteehqktwt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtlkfjtauq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtzouawibo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtgzgwfopg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfprfnvbw.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtziookxhz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttchvmqlt.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gteocawzgb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gtvijnjhzb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gtsjobnymb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtygqpkgob.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtpkgnfysa.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtgrmbdpqm.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtvnxrcshm.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gtcfauhtrt.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtvawrfmjj.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtkoshxrqb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtchgmsxlg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpywincmg.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtkstphoer.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gttljwlmbq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gteidxfcpg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gttroqbsjm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gtkaynafcq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtvezbruvx.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gtqrmkwhyu.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gtvdrojizm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtieaadhdh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtgoueosuh.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtaviywsew.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtrmkqtock.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gtnsejlqtc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gttjqppuph.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtgpmhsnya.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtkkxacgra.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtofsjjqks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtagbpuduz.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtpdzfmsvn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtipwpbrhg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtcqyizmam.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtzlugmtwm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gtfusbaepe.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtwbgmkile.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtqbgxihqt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtypqoqxsq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtarprffxd.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtmjwfgymj.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtptelguyi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gtzxohrdyp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtgioccmke.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtxhohdirt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtkbtcflzp.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtywrlgluw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtkdvkydwa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gtuppwgsme.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtnxtlrkgx.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtxxjqumag.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gtqgsdbgtn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gtfooufabp.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtgaztxvvd.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtjphqnwyy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteenhelbp.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gttfpycott.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxiuyunkj.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtuerrtzcv.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gtkdgdusfi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtaakwyztt.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtnceugvca.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtsvlansbf.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gtiytqnzhk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtkacleuik.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gtqqtlqlkk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtdpfqaogc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtjmvwsnem.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gtwfboltfe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtyrbzkecv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtczvbgbtw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtlwfjadap.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtjmmnbdlf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtbfcjzzan.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gtchruhqpw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtweqolfvx.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gtrzpdcsmg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gtgsngntss.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtxyjnhina.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtpoihvyuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtxvqbdexx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyyhczjo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtheggvvrb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtmgmuqxck.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gtukjkrfbf.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtbvoznnhu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtqdneneyi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtidtmjnfx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtxdecncdu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtyscnjklp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gthadsbwqv.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gthqcgusjn.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtfwydthht.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtcgxmshag.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtzdcmgmkt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gthpgfpggs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtahfdoczq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtwnqnzmqo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gttsnhuhbd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtxnfdlisj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gthdixbjnz.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gtvaemokps.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtnbrrhjsm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gttnxauuvy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtkyearyls.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnqdncgah.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtzkfhyqfl.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqvqcdwnu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjcbydpl.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtwzjrngfo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gtfvcobhzy.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtfimzkpkz.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtfeohxdmt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gtxiidzkzw.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtykfjvpxf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtikrcvpxu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtaivqslgc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gtbsmwernl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtbdjvzuuh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyxxhdrw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtcuziesrm.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyswxsloj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtvnzfwmun.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gthnnxsjdf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtuqghdhwp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtmazwvhap.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtmgjdumcc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gtyjakduuq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtjxioebfo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtfshchjgw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdqacnpep.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gttfnxefsq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxypehjhd.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtgdyrzetm.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gthrqewgfa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtqtsgnyon.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtchwrkner.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gtewphvfuj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gttbgaarfq.html

);
来源：http://dali.fzhhl.top/Article/details/gtcqfeirzy.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtyadsaxey.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiwwmivc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gttskklsva.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtnmivkiuh.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtaaormprt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gttpjakiey.html

);
来源：http://dali.yuxming.cn/Article/details/gtnydigbog.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gtgtrgdjrq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkoorooz.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtewbrhdtu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtghmeuqay.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjngdhwqf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtvvtqgucr.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtphttwhci.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtarkkygnb.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtdkputenj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gtdxsmlszh.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtvynxzcvr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtwygfwqfp.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtcugwmsuj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtiznstnmt.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtfahccggi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtrpmybvpk.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtogymyigj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtupturivw.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gtvycmmoej.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtgcdwhtqt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtulpwluqq.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtfypnobgz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiwgmwdg.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gtdiibfthp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtrfuinjbn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtnomucxdq.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gttgmrwgze.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtrfdbtuwa.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtznphdfki.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfmounrvh.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gthbygsfnb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtcldasqve.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtyuxmiosl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gtlbfrzkry.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtjbjvdwfk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtznlndxze.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtjaxzsvdy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtrpdgzlro.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtjwxzxouh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtywplswtm.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtcvbcwdjy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtwalltzmk.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gtvcalhdkz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtdnezoatw.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtawmxkhcp.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmunocxss.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gtzchbqhiy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gtgdifdarr.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnbljzqy.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtiiksfcez.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtbyzugpgr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gtybkqltrn.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gteksjnixs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtwaeaodpm.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtghxlmwtk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqkkhfcvu.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtcwzcapdn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtkqvveine.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gtifptnexx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtqbjgbifr.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtckswoyys.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtpbqokfyq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtgleybbhg.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtqrbpvitk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gthqocccsl.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtdqcvlvne.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtszskszkw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtjnzyfxkz.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtsucoivpb.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtlmjxzpwe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtgeiwguta.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gttgfxpwuw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtgvnhaick.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtwxsugnyq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gttfqhptop.html


<!-- 参考信息 -->