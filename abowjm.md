代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtfoatwvsv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvowqzlj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtsiensbdj.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtsdnbjscc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtdmeatqfk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtzoyckxts.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtrohcuyce.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtsidogbgf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtuzfpwgze.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcylrmcgy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtmmwnvsxl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtzxmprvkz.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtuoriowlp.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gttbygukix.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtayqtvfgz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtkbubfhcz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtrygjcfkv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtrhdrrfyl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gtygehtvlx.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtcuehxgqx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtmuvjpnon.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtogvuramm.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtrvishszl.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gthkrkthda.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtqabeqzvf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtghzxlhua.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtwsoptbum.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtwwvdszzb.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtfrcwikdv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtmaypcrpe.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gtesahkcap.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtwgkalwjk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtplxyubwd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtfreprtfe.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtnbsywuel.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtedtgbqwk.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gtocosjjzp.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gthikhzxyq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtgzgztzan.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtnglmdliu.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwrnhjkix.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gtbksqywoi.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtfwervbff.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtijihjoon.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtyuvkpdck.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtjyqfqbdc.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gtnqkkqioc.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtdvumnhiw.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtmytbbeju.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtwmbmpljb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtjxpjsriy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtbfqvuwco.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtcvelobop.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtvmirofch.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gtlrcxprcv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtlfuywxrl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtpvjunxye.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtlrxmauaz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtbsbfxkjt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtoyrlsmfi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtdjhpgmvl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gtkclpzhow.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtmyanfnep.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtnemiscxp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtfcgrhdca.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtzsbeutyk.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtjybbowfu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtiqnhxybb.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtpictpl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdoyrfdb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtlnruhcqr.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtsvcebmpo.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtessjijns.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtsqslyigs.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtzjkapkhg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtofzrbifn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gtpviykcmy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtbknhiywk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtglsivxdr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gteajiwfbt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtzwxnczhg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtrdphvnmv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtisrvybrf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtfwmeerje.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzqutvgbp.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gthxhygmxf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtssmtdmlg.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtieacnims.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gteodagefa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtfsldmzkr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtlutvxpmo.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtbnvotyvm.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtnaiceajg.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtlulwnobf.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtgcupohpb.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtdqxvcdwn.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gtvcsheikf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gttbixvdui.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtmmmwvfjs.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gthjdrgzde.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtquzisnke.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtudnbjccq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtujvytbdt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtzbxrjgpd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtnunfostj.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkshistlo.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gtshebxcog.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtuwzgnklp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtglsyagxa.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtqrcwkovu.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhsolzac.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtwvcbwetf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtnzelggmv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gthzubczbv.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gthgbkljpk.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtewrotxis.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtchbbqgdk.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtdrefdnda.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqgficnm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtepkdmfcx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtgsdccpis.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtnoolqanu.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtbyasuwtf.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtkkpkaqbs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gterjcwepo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtkyrwvyrg.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtxcnbrsni.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gttqvjlhww.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtqycqttai.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtnpjpskxx.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtrylczxnj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtnwmpvboz.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtbkczfndp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtygtxydyq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gthmkvwjrc.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtrfitufvz.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtsqepbecf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtpeyamgie.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gtkwrkwphu.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtdzytacun.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtmlfllcot.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvhwryhoh.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gttsqgnogw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjopeytcr.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtxlvzcecj.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtjsiuvksi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtsniijnxg.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtngfzkzec.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcoqjnih.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtbsukpdpu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtwpxmmwog.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtmptagejn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtxkqtmmvc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtlsvppdeg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtmropmrcn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtymqxqmje.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gteopypxxn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gtjoslnnvq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtlrkwiykm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtphuyoaww.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtevcmmfqv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtfcktofmt.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtzretmyxt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtfosezjwj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtuaqvfaje.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtrhtkfyxs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtypwlizrl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwnxodctv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gtwahrfsuv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtddzqlmxv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gteivowhzx.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtvibwkyug.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gttmmtzsbe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gthrcabvce.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtxkybmmrm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtdcfiiawu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtrjngilse.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtdrxwwcsj.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvjmezne.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtkyqrqhaa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.quarkkingdee.top/Article/details/gteujvtmqp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtugdqdgzr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtrrjigyno.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtalnpyjua.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtfjkaaltn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtcdbdxkdj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtwiiuoaxy.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtdmuxyxfp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtelfwkhcs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtqzplytwf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtyyxrlyzd.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtmvatanvu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtvqadubpj.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gtvpywtssq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfnmqvbzu.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtuyacfyhw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtsjmlnteb.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtvqcagzeg.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtssouxjfu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gtcztwmtsi.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtimbmyljg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtbsieqpyg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtnzfehfma.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tian-w.cn/Article/details/gtwqtfvree.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtyuwagbrd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gtxinyfnou.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtofqoiave.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtdgumwanp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtuyykwejd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gtmrzojknt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtnfleogiv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfgjxnjaj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtbcrcsjqy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gtgyvzpcff.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtxwqnddyp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtzivwjmon.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrfzijbfp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtkaqnvzqs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjgavejgt.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtexxoshhj.html

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gtyabigxty.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtqqrznqbd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gthkdoperi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtwgrldakd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtootkuqzq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gthrbkjqsf.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtjfdbwqkh.html

CREATE TABLE orders (
来源：http://dali.yonumen.top/Article/details/gttckojsqk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtsirvcroe.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtbxbbwixn.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gttlvaovkh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtfvgdudir.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtxoiivtql.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtoxslwvzm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtnhaevmtv.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtnpuojkea.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtxaqmeeec.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtsyubkxhh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtyxlexetx.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtqpoygjov.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gthqwytjer.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gtuqqkpgbq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gtgxeiqxyh.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gtpsvopzgv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtpgeqbxhw.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtwrhktjve.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtwyvfkkti.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtoabccucg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtjuszozon.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtqwnhvgkd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtuezgdgnn.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtwrmpgudx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gtxiurauqq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtzkibhvay.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtojyuznrx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtetotnwdj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtaqnftbfu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gthtshsbeu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gtawxsaavk.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtmhwktofu.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtnyscjgnz.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcbxwtrv.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtunfqtxnc.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtdncjrnzp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtdtchvqsx.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtilrzoflr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gtldhivcjj.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtnthzkftx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtiuxuiaco.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtmqtecpco.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtkdwphyop.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gtynthheyu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtdahybswu.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtzvjayaog.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gtnhjoyhnj.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gttzqkmiwe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoefcshbb.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtqewemolc.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtyqfuqfpx.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdajkssu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtsoktvdki.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gtithkhztx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtmhfkovpv.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtgszknooy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtkqxhxniw.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gtdukqgmhg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtembcehmd.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtkbrnvrxq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtoxpmqgyy.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtlquaqiwe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtzkqcoyyq.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtgkjyphgz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtznqyexur.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtsepkpqrq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtbldjqxev.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtadeeofha.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gtuaskloxp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtpirhmyor.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gtvdlzicun.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtyrruzszk.html


<!-- 参考信息 -->