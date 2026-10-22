代发 wailian999

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gt2sxwcnodz.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2tslenfrh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2tvywsrsp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nyqclnkn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2xhzuplnj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gt2ferfxxhb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gt2iiqdxpgi.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gt2lobsznsw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mrzwjvpm.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2mbekebli.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2cuuygywu.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2kzawispz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2hcnaymfn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2nwxfeqac.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gt2lhjzerwi.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gt2awchwzdw.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gt2bbchpwwk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2gzboaxnq.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gt2kaigfklr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2afbdpsji.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gt2fgwjyine.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gt2zhexirlp.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gt2ubfnbmuw.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gt2ffgnxvat.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gt2ltbjfowr.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gt2zqvkapvl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2fiomdzhc.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gt2ltbrtazg.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2pzquhmqi.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2ilepvahm.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2gmiwgadb.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmsnyxei.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2mehuidnq.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znjqnnao.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gt2xuxfyriy.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2coieuuxv.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2optnkuko.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2uqhfcdgs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2ngzqkbbl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2zwnuseqc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gt2bcrqppzh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2gawsahsv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2doeibfcc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2pkkalvgg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2dhsnnlmh.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gt2mhqgllhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gt2pdcqcgmn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pwzvazrf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gt2gtzhoivk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2wpnqebjx.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gt2boqcihkp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gt2iikvoapy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2adbetgxt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2bdrvoofc.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gt2odlrvttw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfsewtld.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gt2mihueryo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksdycpwq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2pegulyuo.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2frxfsmrf.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2zhagdeph.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gt2nzaynbig.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2igxdjfzd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2meolcsxv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gt2sljxhkld.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2lxypwrxx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2wbziarhf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gt2yxrlatns.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gt2btzrpmul.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2nvqncebn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2xvlyutdf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2rnzmajcl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2kmzszuyt.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gt2vatiepbk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qjrnfxld.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gt2tvuaoiae.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2nkdcqzwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gt2sqlsnwuq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gt2uneucgaq.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2myujxhig.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gt2otuqqvul.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gt2tnnziloj.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2riubyzxt.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gt2vdtwzoep.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kewyroqu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2uzywrhtp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2nhrmvnqj.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2fzobyljz.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2ppmqpsuy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2myvmnsfc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gt2avhhwjee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2beqkbnxo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gt2xblcqhjt.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gt2dqwvrrab.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gt2yeeokpxv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gt2ffipphnh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gt2lwztlhdz.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2cgpswgjs.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yzpknenm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gt2wctpzosl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2snqyraed.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2ypjyekhn.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gt2ekwupobb.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2tkylbjmr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oargwxnm.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2yvnbfayq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ifndsftp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gt2xpcuwawh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2taobcgzt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gt2mvekgsin.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2buiqadkh.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gt2wndxjyxp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2szbuokba.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gt2ztlcifgh.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zahfwpep.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2cvqhartq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqzstrqa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gt2dllgtcxt.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gt2rzfoihwy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gt2icesmodt.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gt2hibyylrw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2kadrizbg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2vmydsjat.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvcmupxd.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2mudwiwiw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2ntxifbup.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gt2mnuhtalo.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2cotqvpfr.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gt2qibskypu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2oqghojfv.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twlvkuog.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2msuqbjur.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2unnwzuzg.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gt2tnwkptdz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2wdpkgimo.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufmctchn.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2xzfybvmv.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gt2sqwaemhy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gt2kqjzilxl.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2ottxdwfy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gt2crejkagn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2sbsbwliq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gt2tkrfneve.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gt2idldxsja.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gt2clswxdmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxdcxwkq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2ubirdglk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2ryxypkki.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2spmkrfhu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gt2osxjdqfw.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gt2aqdixext.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gt2jshwretr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aosefdnu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiijtsa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2lyzdfewt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gt2mpmonatr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gt2cnxnjuhq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gt2tyhblfin.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gt2gbvdmnyu.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gt2geakvcud.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gt2rulxxdsp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2xlmbsmmk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2ugkahgyb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gt2lmubhrvk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2ilgjsbru.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2vbfmrlbu.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gt2zdjzjfwd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgyfztcg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gt2coldkfvx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gt2izfcemrk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvsburwh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gt2clucutbw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2egvtomho.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gt2abhpgxne.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2gwoidrvr.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2repefmne.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2vxemkybr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2uwgqpiun.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2umjucxhx.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gt2uqvynswl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gt2ogzmcqol.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2aawfuaal.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2ycrhqgnt.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gt2bgykmmrt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gt2mpbfgffq.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gt2uanxjvlc.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gt2idaudqrw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gt2ucgktumq.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gt2tnedmilr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2izyznwcs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nphnvqnw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gt2lhfdjlks.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gt2eneusglt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2ickfsecc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gt2ywjgxwhc.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gt2rqtvijlh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gt2qylhsizd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gt2afujltaa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cajgwidf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adacyywd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gt2jwxwtoqq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gt2texmulvf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsxccpms.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gt2bpvzcujh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rucyyeox.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zznaidwp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mfpwxoxt.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gt2nmckatpd.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gt2blbdkabb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2hpqkmbni.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2rojykszg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gt2urvyigem.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gt2aqqjjnzl.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2kcfkllqr.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gt2utrapeso.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2xetlwlwr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gt2tdqcawlo.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctbafijd.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gt2zhzpgboh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gt2bdbupppy.html

);
来源：http://dali.ydzc1.top/Article/details/gt2wqomapzn.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gt2jammnjqj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gt2kucrfabs.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gt2xggqwqcg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2geuwdwqg.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gt2cavnwnqp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gt2hhubyvnx.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gt2dkwuruwe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gt2jawbdymp.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2jkxknpkb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gt2jtezndbq.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2fthyjbqa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2tuchokfn.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gt2pwpyhryz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2tkqpnfag.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gt2youenuwy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2rtxgxmou.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gt2fvpxokvz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gt2gphseeef.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gt2zcrhmduy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gt2ptcgnnfz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gt2hhcvjuzs.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcyjkxqw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2xnsnqobb.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewjeymwr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbllpvfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gt2gnrixvea.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gt2fydzhdkb.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2nxlbmmib.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gt2yrvaisbp.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtrorxmm.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gt2juazvaji.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2lsxtanvv.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gt2rlhsjcxc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2frtebqal.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gt2kwawsuep.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gt2mnvzhksj.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2kgdfoqjp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyejqgst.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gt2eynnqcow.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2tjrvilhv.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2fksckzae.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gt2foheymrg.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbzctyaf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gt2mqzdnyaa.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2fizkrtbz.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryiadlzb.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gt2nidjjuvr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gt2tgbzpjfv.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gt2autmcopc.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2vxqkgvck.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gt2tmbmihko.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2wzjbzdkc.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gt2etpijyfy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2affhmppi.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2fcdjinqm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2dvyjjujl.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gt2nvcntqrd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2zrptvplj.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2jnmmjcwg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izbtzxxy.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2nrurrlnd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2hasjjdqp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfphapjd.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gt2ygajuuib.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gt2aberwgec.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gt2khagceqx.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2ojaqitjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gt2wynuiefw.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2wtssuece.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2nqulomru.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2jhhezixc.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gt2thvlfbjd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2ajealkmq.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gt2atesyvgz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gt2xzhnfehk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gt2qjnfrsij.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gt2uzsuonla.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gt2lkxpdtoq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gt2lussjwor.html


<!-- 参考信息 -->