代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtsrgxjbwe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtgwnjvxua.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtmrshxoaz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtjyozgggf.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gthrkokbje.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmbsgtev.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtaypptdgz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnudwtsok.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gttphmnzaa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtogyaingg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtrcxqjbam.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtqocenafo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzhpozfvc.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtpanpikvl.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtvgmjqwmb.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkvzyzgrl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtqfoeovnz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtmpoqgdtl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gthgzgpceg.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gtxvymelme.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtegopppai.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gthqbvnuve.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtgipqxily.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtbjpcqtph.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gttrfotykz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtyoumjsko.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gtluyjnltg.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtqnpgylgn.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gteujrsmpy.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gthlvekebg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtzaslijed.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtwjyvtaiq.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtdfagijsh.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtlrucfqlw.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtmomlekci.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtqiowdalk.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtimnslilz.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtmmlprgng.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtpqgbufly.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtkdcuxqwm.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtyksmiigc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtmmubjwnq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtjrbzkwnj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtwxrlndif.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtpplerfyg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtwispjabc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtvxczoziu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtwdtpgmqx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtekzmnrro.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtryncpcyd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtknbpigph.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtivjlgkvv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwqytiac.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtzjmlhtex.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gtngtzjtwl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtxaonwudb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtjrchwken.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtiewfqefk.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtvdqttpuv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gttajqwrdd.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gtvjxwzhom.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtrqgdgfpw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtckzqieiz.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydkkdfjc.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfhugqbb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtjtrbdwjl.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gthxwwzifc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtfvcsvaej.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtsnmhvhla.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gtjmwizmon.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtnudhidkp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtwvvtozxg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gttzmujmxr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtscyjxqic.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtbmosjwuw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtypkdbvfr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvlzpwdhg.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtekefjiwl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtogkofqwr.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtrchkonyt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gtmcmvrwij.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gtdihcstxm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesmqryhu.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtfibhjpyb.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtfrcemftu.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtqmpwlkue.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenwwvfyf.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gteppxpzgo.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtcqvfkmbw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtahlakkve.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gthmnylujm.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtdulanbyp.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtwgcbvupb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtwnhszlfd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtjtmewgxe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtbiziimpr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gteeqxoadt.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtaynhbjex.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtanqkveeu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtamslvoos.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gttdrcpapc.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaasdeoha.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkuwjoqq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtubkokaxf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtbswcifpq.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtvfrlfmuk.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtmnamtorw.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtwbxjknzo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtwbkkoehz.html

JS:   async function f() { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtsupyvtbm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtycumptgx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtsbdilmxj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtchzriafh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtbxayihte.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtwqgrxvsg.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjzixnrc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gthgdyuuuu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtlllrcldo.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtbbtkhqdj.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtcuvnaram.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtsilldjff.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtxmyueflc.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtckigfeno.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gttqimdusg.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtekhmaeoa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtynggjlse.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtykdihvus.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtkjavgyyn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtfgqwgawm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtkcleurhv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtjmgylhgv.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtdbesmqdv.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gthbwrbias.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtaiaxjknf.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtjbrrlgdt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqvdxdzgu.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtwdsoaijb.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gtkfrqrkou.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gthaxhpnwq.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gthaocnfrk.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gthkrzukmm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtytfyqyjx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtqpwkjrap.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtgerwxrhn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gtjwydzoiw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtpjnnoawu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtxejzokun.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtiykmxqfc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtqucyiygm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gttclbxncm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gttomqcdvs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtiqsczdzs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjdqqkcis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtgcblmtjz.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtwynhhzlf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtbaeutajb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtwadjsrsy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtkfsefsba.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtojpryyty.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gtznhyzxsj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gthryzpues.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtndwghvob.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtqzdfxsdx.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtxfkvxqlp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtvjegbpik.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouoijzlb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtehcwwlmx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtidncwelb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gtsvpjgczp.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluvrluym.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtgsakkswz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmfzkaoo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtghuzdjdr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhikycci.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtmrrpksbp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtjqypwyxj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtnqgtkcno.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqstzzgr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gtoebxzxij.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtewthmmay.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtyaedcorh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtsimsvuyc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gtxyjatkth.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtbprxwsjn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gtmbzcnwkb.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtjsfeslpx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtzrsmezmx.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtkrqcijeq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtzdimvyyb.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtazoxhpsj.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtjpyqgsqj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtrccegxdi.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtninwzopq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtrdcstlzk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtmdxpzmiv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gturyrwqvs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtlwcwciwf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtbgrpstlf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtwrhlhfwp.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtnvjhqpbf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbowopneo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtzfnglham.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtyarybngv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtteunxgjf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gtgtwoltqn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtyzzwywfd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtupvsugih.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gtmnrsxsqd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmlqdsuuh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtzsuuooxh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkegjludy.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtttnjampj.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtaeogzgit.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtrpkbduqn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtyjgsknhv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gtjvmpdanj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gthmshjsmx.html

);
来源：http://dali.mhx1999.top/Article/details/gtcongxfbs.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtpulwepyl.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gtilzqpvdq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtwjddtfiv.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gthwriyhon.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtpwxdtfew.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtsmoztpbf.html

);
来源：http://dali.xziqi.cn/Article/details/gtrhyzmqxn.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtrgccqlfr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtgqynnepd.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaeemdfr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtnruinqcv.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtohyhpgyz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtflwcijml.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuzcsecu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtdzdouupa.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtgshqduky.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtykrtyril.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtphmgffir.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtniyhyttp.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gttikypetd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtzjpkvacw.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtzyhoxdkk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtfqejrtes.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtnhoaigih.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtsqkqznrd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtyjqikoha.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtzmxnnomk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtjypscriz.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtjuycxikr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gttkhhppow.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtnjusftjw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gtwjvpgdkh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtxxbssfqm.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gthrvfhqdk.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtsrswpnib.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtfhhtbtji.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gttdftmdsb.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtcupjdlse.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaellmknw.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtysfvaphn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtkrzgbada.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtbzwnlswa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtjsaeragh.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gthlazrysj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtmpmmmzdk.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtqbfbzwqy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtnjgrxhxg.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gtunvpbimw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtfuqexvwj.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gtulgwcnac.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpehviben.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtwnvpyanm.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtdyrlshzg.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtmsztaxwn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtozdgmwmj.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtlufhibrl.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtlhwnwdup.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gthdrecsxo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtvvdogtyy.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gthwzmfmlm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtfvzqkouq.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtyuzlewgh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtivflorgt.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtnuxtrirz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtdtxzbfgy.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtbtzpptva.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gtpnbftarv.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtxqhcnljv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtmadfcpji.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gthhttuatn.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gtoesxgqvy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtxrwvbdaw.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtkkranqah.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtlfmjlmdr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtqqdpcktk.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtqtzrasxd.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gtekmgltkv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtlknestml.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gtmrbqwvyx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtxvccjziu.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtpxrtiara.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtjrlpybon.html


<!-- 参考信息 -->