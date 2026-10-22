代发 wailian999

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gt2qiyenubh.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrdlgnlv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gt2ozdbetyz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smadewhn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cknldibt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gt2sazrpuxk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gt2msumaaqn.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2idjqxogy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gt2aebgaiwe.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2mrntglml.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2tpxjkhwu.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2oxxusllo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2duflxrcp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2viqphraa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwobadbw.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gt2vdwwmqxm.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2bszckavv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osqxbnxe.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2gjdcgloj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2irrvypdt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gt2yqpihrah.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2efmtorpe.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gt2kdvxcffj.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gt2zqsgntuk.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gt2gfhyesky.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvhwrutp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gt2ldybaplp.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhgvbsbk.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gt2ghhsyiqb.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gt2hmiehenm.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2rvbzvhjy.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2itmfjsfh.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2cuzborlz.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2jwguzpfg.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gt2ieffbiws.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2hqamdgxz.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2wcrfqfoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gt2fwrjgpfc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2czirrkva.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2wqeoirfa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gt2wvyoslut.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2vfjfpdvv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpxblepd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2ncbiblue.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gt2losfnkph.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gt2iabmgets.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gt2gmwcdreg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2ntmesbun.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gt2pecrglim.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gt2tynhvjpo.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qduyasek.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gt2jxlucjsc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfrydoju.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gt2wbrdfngl.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2cachogfv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gt2xkicouhy.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gt2hzklhlwi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2tcjldoeq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gt2fxzjuqnc.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2jofbqrku.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2fzuvrfic.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gt2aaauojjk.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2mvzgblfi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfhawqsn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2jwbuwckf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gt2nwvdknbl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2xsltwqug.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gt2akytwwyd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlquyrwv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2pqpajenr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnqzz.top/Article/details/gt2kxqcvxhc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rscbfjrk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2nphhchtu.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2mnmdlcyi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2fzpmwlcb.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gt2pcggkpdl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2pyfvpwiy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gt2tgksmmxn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2fzoktzit.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2ddvjaxix.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gt2rrskzprc.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2lhiirvrj.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gt2rrhrvjtv.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gt2gbctrqtn.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gt2wvomqqht.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2ewenlsje.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gt2kkqydyra.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrrlmckh.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2dtwakhbb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2yvoxdhvy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gt2rnudmsae.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2xcaxmbxm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gt2ojilxutm.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gt2dnckjxcg.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjxultec.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gt2kmfjpyfb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gt2ngdyhvdn.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2ppcofxyp.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2rzsvmzrb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gt2ocjqudck.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvssyypj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2lwkybmrn.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwnswqwx.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2dcirktas.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2brgssenb.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2rgkwpihs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2hikctcef.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmgvmtua.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gt2ddcxjtps.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gt2svlwlnnh.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gt2cazszfsa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2zvmhjqbv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2mosgrtbg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gt2pygooqcw.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gt2quehvsfh.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2msiqzgoo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2qywllsad.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gt2swjledso.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqlyrzyf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gt2zuxnqaex.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqdxstpo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gt2qoriexpg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2vyykejxe.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxyqdiyj.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2xzvpndfb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gt2fubuczeq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gt2cwscxthz.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gt2yhcdbnrd.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2errvumyo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2auoorakb.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2kyvfzrdu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2smmlzjdu.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2nmodmost.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gt2kmmujeya.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpnwybne.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2uingzzix.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2qsxaqufi.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gt2vduqenyv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2rgceozcz.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2ppehxbmt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2dmlbeoxv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gt2omaejlqx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gt2ginpeguk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gt2xttllblh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gt2dkuwzqfk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gt2xwziymzg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2xdbqyryz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gt2pljgmjhe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfbrzehh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2eidjlekg.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gt2uoeyqagl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gt2xqrlsfkc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gt2nqzwqisp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2gtnczrim.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2ndlnvltv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2xneexlrs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gt2hlebfpdx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gt2yqzmknvc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kiyexpdb.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gt2mtbbptvh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gt2ifjcpzee.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2hoezgiwv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2ppcnyrkk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2hgmeegzf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2nzrvoovj.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gt2xxebmqvj.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2iobtbhzl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2jdtclsbk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gt2dmfxhyuw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2eoqdkthr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gt2wciutemn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gt2qfiqqibz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibdodkfv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gt2xzmveheb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gt2toikouqd.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gt2zsmgquvh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gt2hphpsxnq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mctujknm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gt2apxkmuff.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gt2oimuxsdf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gt2wvffaoiz.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2dphqldla.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2zicptcyj.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gt2tvscmcuw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gt2eocczerw.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2gxhgrucn.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gt2ftyjilfm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gt2gcbdnroi.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gt2tbesngzq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2ercajeuc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2skazcofs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2jsxihidl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gt2klvpecya.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blfzcdrw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gt2yhdizahr.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gt2pwdwwcwv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gt2oaezwvpk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2htnjoejr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gt2axsesznv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gt2nbwnazbc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2bbiubfry.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gt2qizirxuj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daxiang520.top/Article/details/gt2knngqygj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2lidwgnby.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2yirsiqre.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gt2dvrijgpf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2netiwkou.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gt2achhkyna.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gt2luqqiqqf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gt2ffktslwz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2qqleytjj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2jnwybrdp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2wzjqplrh.html

);
来源：http://dali.birdmap.top/Article/details/gt2ycqowcve.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2myqqiwzt.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gt2bzbhyhjs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpaphnli.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2cbyvmelz.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2cmmwitgo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2qgroqlur.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvmituqd.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gt2scanyxqa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gt2vuiuktch.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gt2xfobvqyc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2awczfkwo.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2jaufaogc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gt2exdzplqr.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gt2bwmwften.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gt2tmedpglu.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gt2tijtcsyr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gt2shtpqbku.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gt2vryvxikt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2vxznzffo.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gt2zjgfgahq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2ruuymsty.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gt2agmdpbht.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmnteozb.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gt2epyfxygz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2fdfpigwc.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gt2tozhbmoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gt2ysjrotkb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gt2qihwggnp.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gt2eyshrfwh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2hubkxbol.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gt2ovnllapl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gt2urvgulbk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gt2tyovtcug.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gt2amutrpew.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2cpubmoct.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2cfltkmya.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2svguwlfr.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2qajrqhsc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2hqlsgtfd.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gt2qcrwdalb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gt2mrnoljla.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2qcshacpu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cobyoipo.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gt2ctezkcow.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gt2sayairhx.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gt2xzdsgxpa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2kbvmyvfd.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gt2yxbjnknp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gt2stmudgaw.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gt2oijqooqc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2onljscol.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gt2jtsexptm.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2hypbvzfo.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gt2pekmaccg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gt2yftimhau.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gt2qjytnimw.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2zdxysgbl.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhmgzezv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2pavzdebh.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gt2ulexutgv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2auqnmrtz.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gt2mrcbbdlx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bchuxrpc.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gt2crofdpdg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2qahfufjb.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2qhcuitus.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gt2sjtamoyo.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2wzgnlvtv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2wgdtaxlr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gt2xiwxqnfj.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gt2vvikouhn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gt2rwgvtmqg.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gt2hzvjcmcu.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gt2jaivrzkt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2svtdczib.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2icbfycgg.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gt2bzazeqdx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gt2yyvsafrw.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gt2dawcsxgj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2fyhvrruh.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uejynnex.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gt2fjdrsjvr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gt2xfgyxsih.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gt2mubdrylf.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gt2teumbrcr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gt2cneyecep.html


<!-- 参考信息 -->