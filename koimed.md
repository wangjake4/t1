代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2giprjfxx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gt2pvdyfynp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2aydugrgz.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgubgiwl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gt2gxleuvwr.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gt2izrzczrz.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2dadriund.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2sfjmordo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2zulyoqld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2unzvdsaa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ichbkdnx.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gt2uvkohcad.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2upmcxiri.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2zwrfoucf.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gt2wairfong.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gt2ntinwcgr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gt2hzwfanos.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkayyxfr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzaknnnq.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gt2angdpkaf.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2acdnmvta.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gt2dkqckhkk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2cjpsentd.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2dyxluvtu.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuafqzwm.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pumxjhyn.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2vluivmgq.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2iebivpwa.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2qdlbschy.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2kpuuinfd.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvphvolh.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2dnewzlmk.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2bsdlpyng.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfdckewt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2wftgbmam.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2itnubstx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sohnpwrj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2fanrauxt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gt2gtpqveqh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2xeeylekg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2etxtauqg.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gt2qmvjqbof.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gt2bfttqcak.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gt2qhdozwyo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gt2lebidesc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxerxaki.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkgrxwxb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gt2cxkwnxfd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2qbfesgii.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gt2tzgifeas.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gt2fljslmrk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gt2yzwkvovr.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gt2rplmraew.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gt2avnnjowl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2tfoyhuyv.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2umaotoij.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqmtorps.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpfumo.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2clevvrgy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwgneybl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2fwrfikrq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gt2ebdqdhhs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khzgpehl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2adjktkqa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2scpnwgpf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2zjaenacy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gt2nbdtqylb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2sslpnnkx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ykjiwepx.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2pnxvkavi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rsiqeroe.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gt2ebdaqrdo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gt2kcqadrlj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gt2hghybvbr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gt2nwaulgfz.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2msjevhue.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2svalbfrx.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gt2ttuhrcdf.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gt2folamveo.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gt2zgewzjiv.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gt2moznqgai.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gt2ssdomncw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gt2upgyemcp.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2efdebezx.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2mqactxlb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gt2fmsjwaox.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gt2sftzincq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gt2fptdbukh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gt2xxscwphd.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gt2ujeivoti.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gt2qwsvlrym.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gt2fbvmrzde.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2iyneaokc.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2meqzszqx.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2qarrzhrv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gt2easvtpta.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2ltutfkhs.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2zvfebrjd.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gt2gqekwppy.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gt2ikjmzccs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkjgzhwo.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npmhgoky.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2xtrozlhl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gt2hikeahat.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gt2kawiaxir.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gt2yjiskoll.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gt2kgejigyr.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gt2hicijxjl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gt2ndnxlacw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.bjfxy.top/Article/details/gt2lgxdurvu.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2gutthryb.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2oacipryi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gt2svvvqlbs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gt2vevueiox.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kehhmoxm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2pozvhaml.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2otsnubmi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gt2sftrduej.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gt2objripqj.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gt2lldfvtdv.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2qhwaqbzk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ciflmpjk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gt2mdkztxdc.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gt2hckxqivj.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2danwjgyq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hscsjwjz.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gt2fmoosvte.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2bqogusdo.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2aqwgocur.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gt2rahyvryi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2ltykghxa.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2yjjtaodl.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2sonxihpb.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2fzsemzrm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbfjbntb.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gt2clvhplmb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2wpkqrsfw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gt2byvkmnfn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxyujwux.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2kkrpixuq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gt2dczapbqj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gt2bnlmqjpa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2oerriova.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gt2rgefuisa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2drqeqhng.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gt2lbnwlbss.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gt2qflocntp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gt2dhmqlsel.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gt2dflamxst.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2npdzzarg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2ejihshyh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gt2rmiwoofn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gt2wbwgcxvy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gt2pqphkmae.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gt2lfqxleko.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gt2gstsixou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gt2wobknkbo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2clgczuzp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2ccsjfcdd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gt2mfwvenhb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2hundkmqv.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nczoamsn.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gt2jbftbfsw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2smrihrvu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gt2afqxpsoq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gt2luwamekh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gt2quqafsbc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gt2ctnfnchm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gt2urlolccd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gt2cayoulrq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2iwrxbvbj.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdomsuqr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gt2jkkxodxk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkbqntck.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gt2bunprjqf.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2twwvtznl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2uzvxvsrv.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rhssrzyx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2sqwxtgow.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gt2adzkhfty.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2knslrbhi.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qnqsxmak.html

[P07] 防抖与节流
来源：http://dali.hnqzz.top/Article/details/gt2cojmtyfv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gt2sspjcupm.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gt2nrdbpqzd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2ehxvogja.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2teqxsfzj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2vjpiwdtx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gt2lzinsrrl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gt2xmoqxqop.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2qtgjixdq.html

[P08] 处理浮点精度问题
来源：http://dali.zhoulong.xyz/Article/details/gt2enkcvlmk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gt2lphfxvpj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gt2momlbhhr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2jgaisxgs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2olwwphyu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gt2xiwrhgdm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gt2saaceyhv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gt2ozxpjsgf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gt2nhymmhvs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xcbbnmrq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gt2qtvtbcqk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wrxnctre.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2lvljkyur.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gt2rqxvthfp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2sdvvukzw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2aufeyqqn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2xbskmvcg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gt2ctxriolo.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbzxfowi.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gt2krxyiucy.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gt2qkfhlybn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2zbwnheoi.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dngnqguj.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gt2ceplesyt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gt2kpjiymdt.html

);
来源：http://dali.sweek.top/Article/details/gt2adrmshcr.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gt2ojwyixgq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gt2nozflmvu.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gt2mneoabqd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojaikenv.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gt2mfygoorz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gt2rlvsjapl.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gt2jbcmmhyr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gt2yfjuyelv.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gt2zcvmkqje.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2whluloxp.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gt2lmseossl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2braondwl.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gt2wnxyomcr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2mmhdjwdy.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gt2qxmakqeh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2xlfkdjxp.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gt2umkkkiqq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gt2srkciimo.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2tkdqilwn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2dhrsqmwr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gt2nnhwoabu.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2miyurdpy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2mymfdkqz.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gt2yzrldkwn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gt2btbuwijv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gt2narxcnpu.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gt2xnhsuwha.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2dmqhipiz.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2polnaflj.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xczxarjx.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2awyppaoy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjukoiav.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gt2iajblrnk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gt2vkfvlmlz.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gt2xesmvmfc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gt2dlgioejz.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2guynpmlb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2qsnwrpmh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhmmbeu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cucudq.cn/Article/details/gt2bfvabftd.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2mmkscpmb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2ibdldwov.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gt2vvecqweu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2vpwkcqyw.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gt2fzmyqjzi.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypbodmrb.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gt2cpnbmarg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkkehxwx.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gt2xwjcmfew.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pffbuptm.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2wgiffshi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2cumacaui.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gt2iamhwowc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2vigljwam.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gt2vozlhxka.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2vmjcxhdj.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niyfgnfe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2nyefbsrq.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gt2tizqwipr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgfnqivc.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2hplqqjwi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2tnhmeguo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gt2bdpquorx.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2ymcfkpio.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2xmeaduzz.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gt2uoggguvx.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gt2lsghoniw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ueyolprg.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2twlhjtct.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2qiguuflk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2dywcichd.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2yzbogunu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2dfvnxuzf.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gt2lpswzvia.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gt2tgpudeci.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2rexpaklt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gt2exlnxyxg.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gt2hsqrdqvp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfoatvca.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gt2qpdgthjp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gt2wymhyist.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gt2ygbfqcey.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2uuieypyc.html


<!-- 参考信息 -->