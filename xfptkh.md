代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2lhventlj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gt2djkmfatj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2fqanapbt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2sbuqpjvn.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2aqpefsjl.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2eiqrqeda.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gt2gvwafrxa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2efbsdghc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pcxabctg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2zbwiuhdg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gt2omhjvlxe.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cllifdpx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2svpqjcxf.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2szfmzdqs.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2sjvnfcka.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2hubnqsdx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2ykfwchxb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2gyvrizmm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gt2nywcewhl.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2mrbfdlqn.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlpiprev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2soukicva.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gt2ovndvfln.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gt2pffxfgry.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdugrrqn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gt2ziaznsyq.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2hhhlzoub.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2oambcgaq.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gt2hzmayhwr.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gt2ccerovlv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gt2bdkreaex.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gt2zjwudrzs.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2bmrtyeds.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gt2klugwpmk.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2alyzujtb.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2xzkkhvui.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2nxwivwtr.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2vchsxqwn.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gt2lwlktwia.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2rpgzmgom.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2wbbcrysu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gt2bmwxcfpo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2bpvxuofw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2awxxjqgg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gt2mgnidzgr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buxgpkwh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gt2nhzveoeg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2vibffwkh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gt2njlabymj.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2xjombbjb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2umbwauwp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2wdldpaln.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gt2eexnlizk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2lrdbnvtv.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gt2fycncbpx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gt2rqxvjulr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2apcffuci.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2crnzavcf.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gt2rhfcaebo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gt2qyfgkspy.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2ndizwrsl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2zxdduyvm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cacyqvua.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2ppovpqgt.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2alaprzql.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gt2hjwrocfo.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2cmclgbnr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gt2mkjvfxdk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2fyevcaua.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2czyrqzfo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oegfgseu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2xgyrvszm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2lloccnkq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gt2krmredmx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2buolcmwt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2torxjgrx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ceyppimt.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gt2elswghch.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2iadjjvlf.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gt2mgxflmgn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gt2awezozre.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gt2fesaukgv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gt2hsowvqyu.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2lmdbhvrd.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2mftnwjrc.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2izcuybiw.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2aqcptzum.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2ibtwwyyv.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gt2krdgrean.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gt2euhdhhch.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vosfhlka.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2ktqtrkil.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2ggzxywnp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gt2wulnrwcj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gt2jnwhzlio.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gt2lsalsebw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gt2gkwrjpwg.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gt2uwwokgal.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzxrlwmk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2gydlfhew.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2iqelwxxl.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2jmvsyvri.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2vzfveaev.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gt2beipuqed.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2lgfwrbea.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2yvlzrhib.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gt2yecmvlts.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdogcruk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gt2wqftzrpy.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2zgiixtnv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gt2dcxdtveh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gt2jxhiwgwt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gt2pkdazjun.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2qdqvdccs.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gt2slwsdwpz.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gt2vkaybwmt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2hzzwnlob.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2nmukcqjy.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2ceovptnm.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2uskldvbj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjhdpwew.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cicxgorh.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gt2epcjiito.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gt2qjiqqlqa.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2dvgeeuiu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gt2prwbdugo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gt2sypoxzrv.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2nzckhaqo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2sxgbkkbi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzuqdvoo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gt2xnwmhlzc.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gt2pegkiyfq.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gt2gnhkyvoo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ncfjokxk.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gt2hzbyuvml.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ffzqrgrf.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2wnybcxuz.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gt2aatnxyaa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2wfwyjntv.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2vaqwyeoy.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2ykwrqiyr.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gt2fqulyilv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gt2vsrzlwhc.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2vszpidbl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gt2hrwofkvs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2pikswufz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2ejvxrukv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gt2ufhoxfsf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhyrwmpf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcubrbem.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2mbpmlspo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipgkckmm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gt2kxxkyywr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gt2rpndghxa.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gt2bnmcaooy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2wefylpvq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gt2hyjoonxa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2lafckjie.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2omozffls.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2bxndgsva.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gt2dhwvfhse.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gt2qgkthhyx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gt2rqwzldlt.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzrpzjye.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gt2hlvoovso.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2sdfgcsne.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlcmvyhw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2gvhghxku.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gt2loisvdvw.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gt2hsvhikrs.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwgysnih.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2rguddsqq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2oiaitwhk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxmlwstd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtkceneh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gt2xtoymiky.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gt2mrgdwdxa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jahgknxx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2vvkpxwby.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gt2tdzjqcqj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gt2trkypifl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekivmyxy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdaofebl.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2lnvvyhal.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gt2smlywhig.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2fizzmnra.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gt2kxsqbgql.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gt2mxjlpxoa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gt2zmkquwzx.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gt2csroqqfr.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gt2zwymlagc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gt2akrunviw.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gt2dehntrdi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2dkdplwti.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2kyntgcrr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gt2melzatzg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfuktnok.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajkcojxp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmvzomvr.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpzxoahd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dknrhtkz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgecpsuw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gt2kqfzpgdb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2kanozcjj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gt2inqhxopi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2rnbygtdx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gt2glacfedf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gt2ecqvnrwe.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2rwulihqm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2ipmshepv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gnofyqkz.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gt2kykjglsv.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gt2esiokikw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2swxzypci.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gt2nfemvdge.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gt2bkycxwwy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cesluhvx.html

);
来源：http://dali.fzhhl.top/Article/details/gt2jqysfspq.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryiybdxd.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gt2fxcmptwb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeubwtv.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2dkfuvuwi.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gt2phhjvzoo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gt2hymxtagb.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2gsmvhhjk.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gt2rbwzdgdz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nndftacl.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2yosuhzvn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gt2lcsnjxip.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gt2jafuxapj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gt2ihrwgbms.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gt2qzofticw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvcouzqf.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gt2ehurnotz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gt2blmttutz.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2sejtorxc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2esmvmfhl.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2uldjkjab.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmglrocp.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gt2jopnqvvw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znttiuci.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsdmsekk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2zagtaxyx.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gt2gtxvgyhp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2eulkfwpt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2telhlnmi.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gt2bbmmlhnb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvgzmbfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gt2enwhlgvx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gt2zlbbiymb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gt2sznnumld.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gt2gufpopag.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igsoqtpb.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2bhovhyrf.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qoipaedq.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gt2gladgezi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhofoxvf.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gt2oidupera.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gt2zsdwgfzt.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gt2wksxatad.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2idsasesq.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2pvadzhmz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2canzwxwk.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gt2kyoxidnp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2tsyddumo.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gt2zowwyspu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqazynrm.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnkoxits.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gt2viihqqkq.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gt2llmpcosn.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2fqoxmnoq.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gt2xtrbgiul.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gt2reejohcp.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2suovjgas.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2pepiauez.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gt2uchkfslv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gt2jfqdnnkt.html

[Q28] 求和与平均
来源：http://dali.mhx1999.top/Article/details/gt2tnslkvky.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2udnvqnty.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gt2luulkzee.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2mpycbixe.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gt2kbbhglry.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2ezswgclf.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gt2pkvhdmpi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gt2jtznpzlp.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2xwopiiex.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2cifoweir.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gt2hxsbehzv.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gt2edcuxapt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gt2hxseukqc.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwcuemec.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gt2tafdlvnt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyqugkjs.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2forqzmcs.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gt2csmvnwmq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2heijdbew.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2smrvmwuj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gt2jrbwukba.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2qfxcpdrl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2tkhldpnc.html


<!-- 参考信息 -->