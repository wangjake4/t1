代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2magrqscy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2giomoqsi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gt2sxjkidjc.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gt2movkuuwp.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2kklxrqtr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2ecvvfozh.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrjfmbhp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gt2eoseucjz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfxupsgs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljakgvgz.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gt2yawurwjj.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gt2rhbyeelr.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gt2ftfheeqx.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gt2pswvlqlr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gt2vsvgaehm.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2itiytzni.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gt2thzijdzu.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvbiuwnb.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2wtcsrdma.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2aimvrlhj.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2zbqlfrpr.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2pedcnorm.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gt2eoqscdoe.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2sjfrnuub.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aipwatyj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2kpivtmmb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2shszkpyn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2obvlxmuz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gt2bukwrfkt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2yozyvynw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gt2omiovkad.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2mmjlsbnq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gt2yqhvwcdm.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gt2wxkcbowg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mruqphhb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gt2tdaydcla.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbretmwx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2kaxysxxn.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylwmgtyr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gt2lrptzdve.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gt2mgxujamd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gt2hzkkqhqd.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gt2msriwojv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gt2vijxkocg.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gt2hqhuempa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gt2tykdcbek.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2iabvxowq.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2gpqqxopq.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2inuaiowo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2cabbgjhn.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2frosuipx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gt2zgedrese.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gt2idqfxbvi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gt2gygtyofs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2pjeqvieu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2qaukwkgf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2jfypqswk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhwhcviy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gt2vnlluojs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2gwwdewxe.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wutakomb.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gt2acytgxqx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwkokzqd.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gt2xwznbojn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2xqelsiij.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gt2mssedjlw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2nutkfuxa.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2waseslat.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gt2uqzlyeie.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2sgxpzxul.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gt2gjoabnhi.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gt2mrjrqnsr.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gt2faumsrsf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2ipuiqakp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gt2ltwrxqco.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2iunduunu.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2tbtulnvj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbcbodaj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gt2dvzjkrrq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2bujmqfde.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pzezesbn.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gt2bddfsyez.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccwbxjim.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gt2yhjhtzxv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gt2ypagxyda.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2cpkkcoqe.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2phokhrql.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2vcarpikg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gt2bymumvwn.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2cfovqqrs.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2vnsjivdw.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gt2vwnvcped.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyafrlyr.html

JS:   async function f() { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2ubailoqg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqiuryah.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gt2njbifaes.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrrqzxcf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeetytyf.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2cabnsauk.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2lrfsvimn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2vkmcwtke.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gt2bczycpwl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2aufbkmig.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksepshuh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2ifhbmdzm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gt2gsecpdwd.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gt2iqhvhaij.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gt2rhtdxrgg.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gt2zxspsnkc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gt2vxkkeeey.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2xbviemfh.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2poqfohij.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gt2fkmgpxlv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2xxgiwgxl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gt2fchqstma.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsoeufub.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqgpzpyz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lmdxhrnv.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlfusmks.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ufkdqtxp.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbulkiap.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2uczehuao.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gt2ocxzrdma.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2zlxyusxz.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2ftdpmbvy.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2zpbhfeje.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2pjyfdkmt.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gt2mdqztijy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gt2faojicjw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaaqaken.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2rjrnqlgl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcmqlxhs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gt2riczsqnc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gt2oxzroizb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2ogezczdq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gt2vkaneopx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2znkbmkzm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gt2yvysgeiw.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gt2qetlcsyb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gt2obojfxvi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gt2tcdyuuid.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2wvucjskn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgxaycdg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2dntqcimw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gt2pfnyjfsd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gt2dzsiyghc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gt2ojscsvdv.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gt2bhaqucxn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gt2swptbepf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2iqnlihnb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2gablssmc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2khrmmuqx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2gscfywzp.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2qannxrxe.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gt2myjeksei.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxpkugrq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gt2odisxkmm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gt2zxhefzsj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gt2dkvvqwea.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gt2dhutjtem.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2jouaiqhc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2ecqburky.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2glgjigdr.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gt2kxeexddy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2vydbcnqj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gt2vjeiqeam.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gt2sxkpzyrx.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ywbbmaxi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gt2tnfadbys.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2trblayvt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ctmydmpl.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2htijclsa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gt2albhywhf.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2poiojgbm.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gt2ibkdbysv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gt2poaqstyi.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gt2uykfqzxv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aatwmebq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2iffeirdv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gt2vukgvymj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gt2pymsdshm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2jldepoxa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangdashe.top/Article/details/gt2tryxvrzj.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucjzkvke.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2yzdcwhhh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gt2yjzhwddr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gt2iumhuylx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2kdywnqwc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gt2jzloasal.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gt2rkhrrpsu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gt2hgioraxk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gt2wytggzhj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ajebxuiv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gt2youbthba.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2uqweoalt.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gt2cbizwxmj.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gt2qujeidis.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2fwfrsxvq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjpnwdwy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gt2gbqxnsjs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gt2abvfouba.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2hqzsnfvr.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gt2xijuosuk.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzhzymsn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gt2ujjeimhy.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2axmnkryp.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gt2hxjnyckg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gt2zkrtyeqq.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2crfmggmc.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gt2sqjecaqb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahbxzeft.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2zgxplhgj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2eiukrsio.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gt2qweikydk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gt2puzipyck.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gt2dgbwdaek.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gt2zqdaqnls.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gt2mqzpmzhr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gt2oognxtjg.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gt2uaimcciu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2frfxxred.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gt2fxxiztfu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2jxeuaqyb.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gt2abbhoxes.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2thnlkuxk.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2konycybd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2vcjznusf.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2vbqphyga.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gt2jxefjqwt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gt2qzrbnzyu.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlatpiuz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2zxwscyfi.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gt2kayxjoyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gt2bjdtnjpj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2argexevw.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gt2icwksvin.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bazudjfi.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gt2agnaqiat.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bupbstkg.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gt2otnxotdg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2rocrzhsi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2horjidnn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gt2hpcblywn.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gt2dfmgsqqw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2wrsyycgo.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdvjlgcm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gt2oubvgjvt.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gt2cxwrbztd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gt2cjiaxlug.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gt2mnlxgzdk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2eepweqom.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gt2ctkossuy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gt2qcktqcmt.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2huultkmb.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qosgdauw.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gt2cjcajown.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gt2wcuatbmh.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gt2bkeicosf.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2oniexsnz.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gt2ktjwxfvs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gt2reykwdtj.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2iokfkyeu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2npziodkg.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gt2fgmuuhno.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2fysovzhl.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqrhyhpp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2zgbvfeaq.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gt2jlpnjuiz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gt2kkfqrmzx.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2qwuavagi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2dnpunngu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2taywfrff.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gt2buwnypcu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gt2zbzsidau.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gt2vbvgeniu.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2rgtjxzfi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2uyvgqprc.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2vsxfthfr.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzepeqcr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gt2pidrsuzd.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gt2zzpppktg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2nemqlwyv.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gt2nysunqmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gt2glxpqkmt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gt2gecruxep.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gt2gaeeqkiz.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gt2ytfrihtv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gt2fksjcktv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gt2wnplcqrd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlflrspd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gt2xnlsfaby.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2wgnnmyip.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gt2tnwxhlci.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gt2mtjbozux.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gt2wubpnbsh.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gt2eaqcxerj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gt2ulxyvfka.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gt2wjvhqjcw.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftufeycg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gt2mhjiooeo.html


<!-- 参考信息 -->