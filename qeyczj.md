代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2dexnaqqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2uxibrvga.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gt2emwphqme.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gt2ceeledwa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2pngbxutn.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gt2uhwuwhfs.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2hwbsjuzp.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2rxefeenw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2utdkkpon.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2dpqdhazv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gt2iinemubm.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gt2llnntbjn.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2dczydkoy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2qhxpbecb.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gt2hefutqko.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgqeqptc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2yqgtwptr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2iedxquxo.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2gmibieii.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gt2okssiqsd.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gt2uqxrlmik.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gt2othjartn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gt2asgqxsnp.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aikxnoys.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2dpzryudu.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyjlcqry.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2qnrnlzen.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2hcbrtkxv.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2qbcjnzox.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2nnrnysyx.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2qlcnjbtp.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2bfundjsz.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gt2mjdrujjb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2ubrqbfrk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbwqbwfk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2iirofvzn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2sgukmeuv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2hrwskqof.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2hidpglpk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2kdtvpxkn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rckgnhlt.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gt2ggxzoety.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gt2jmlyeswp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gt2jdfwjuzr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2cwerqnjc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gt2ztqhfdpv.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gt2knhqlzqu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptdauifq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gt2qxfsftsj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gt2thzeigxq.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gt2cyqjkqsb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gt2oagfsidm.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2fofpwnah.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysomimzx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gt2vnekgvqn.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2gpplxehu.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2aufwqqmn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gt2bohynoas.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2bdvwoazh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gt2njxuicbx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gt2gwptjynb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2uqpmagih.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2ctgqhidd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gt2wtwxpyzi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2oplctjxc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gt2ghgbfcyl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gt2ryoubfva.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2ozkyefne.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2zwjtolio.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2zztakion.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2clhzsxqg.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gt2duwsnwyv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gt2rueblipv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2fzkxtmyc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyfnievk.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2bqnqcsrc.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whbcivpo.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2xjmlhlce.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gt2vbvssgta.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gt2zpcwblya.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2omgfajgx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gt2rhizcazn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gt2mkcfxfvg.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gt2komfhiqh.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2wfhkjzvd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2enqpfkul.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gt2aoyrtuiw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gt2ruvdjbcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbraepol.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2pipjgtnu.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gt2gqoqajxd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gt2ouwzwhax.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gt2cvobctly.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2bzsfltwm.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvthjlwe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gt2xpjiefsn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gt2bdsotanc.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2xqionehc.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gt2plsjyqpo.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2rxkjegwy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2gfkymtuf.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2hcpswrde.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2hyjxgkwn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gt2yvldlnzu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gt2eqqzbzvu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gt2knuxmqao.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gt2cwuwzmsk.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gt2blgrdyhg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2mqapsfqd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gt2ifzispdo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2waumsmma.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2jjyadgvg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gt2sofvgymz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gt2juepsgil.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2hrwreeos.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gt2yrtzfwcz.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gt2skxafxee.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gt2smetxfpf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gt2lycplaol.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gt2dpieolot.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2iwxjfoew.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gt2ipvlqwfh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2zuebrstf.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2xwfyqxhl.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gt2xnukqtvs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2bluxveik.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gt2swmiaiwt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pzwkvfvv.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2yjawtsau.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcipvwdc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2nlzudtot.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2rerfzazc.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2xxkodqid.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gt2vsgzqmmt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsrhidqk.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gt2lyqwegmj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2urvmvclo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gt2revnpdyq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2bvntuuom.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gt2ejtyfivw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2kbtzspuc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuyndfrg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppaqkrte.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gt2eytxpcqk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2radloyba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gt2iukrsqpc.html

[P03] 生成短随机字符串
来源：http://dali.316326.xyz/Article/details/gt2fxmbuzcu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrfupmsf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gt2aegkuuhl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2zdolthre.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2fyjhtqbw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gt2lyusdexi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gt2trmexche.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjytdujr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gt2xhizokls.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gt2axqmlnhr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2mooibbre.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2iicrmban.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2cxovvxnp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnirjgdt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfkgivq.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gt2xfnruytq.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gt2xsgmbxes.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2mhlyakup.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gt2vexpcaaj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gt2ugvbziyh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gt2xawablar.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gt2tqcyyxgz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gt2ndvxudmc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gt2gpeliwwo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2unweeqwt.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gt2xllebdlk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gt2tktjwwld.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmxmtlae.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2zvccxivp.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dgdchpcr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2pfhmzuiv.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfpooxop.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2zzuzyupx.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gt2ekqytwkx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gt2knzvdcsx.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gt2npaxpjbm.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gt2ncubalkv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2enuxrtro.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gt2ulgqoxnk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2igeyrxqp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2kqrxvjkh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gt2yxhikcxk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2rpautsvl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gt2akaovwiw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gt2sswgzrzm.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gt2yargbkgk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkwaaebi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gt2meiccznl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2oriqpdya.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gt2jpdrfzbz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gt2xbozkfic.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gt2mcobyqpv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gt2gwbndyoi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gt2cgszykyg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2blxephld.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gt2vawogxqs.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2msrglegz.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gt2axlbvbtq.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oncizvhn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2ootgccvw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2enlysqkv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gt2qgniecvd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkesftzz.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2jomounhz.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gt2dxcpflpq.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gt2wbkrtnjf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gt2bynzethh.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gt2gkxwhzdj.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2mubfiizs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2ffckvtgh.html

);
来源：http://dali.yongpay.top/Article/details/gt2rxkrhynw.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gt2vpkddhwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2wttjpzme.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ujcgzebb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2iyamibls.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gt2apiagfsv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gt2lrfpegeq.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gt2wuymwzrh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gt2jvuasdrn.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2idrvfuwn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gt2nxqqepsr.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gt2dfoxqbwm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2lbugofas.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2bebwtotu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2ebwpleep.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gt2ihoizdmq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2wfggwxei.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gt2vtrlnpua.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzcwbvgw.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gt2ekxtdczq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsfhqxhm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2tezcnecs.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2tccbgelp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2wgccdetm.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gt2fzwsrodp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssrhflny.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2vhvgnati.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2nygxqhty.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2petfuhjy.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gt2viuvqsta.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2weplfqte.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2geddovcs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2mhwhplub.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gt2ljukcdla.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gt2nshodhuu.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gt2yuhrkfqg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gt2fbhonbyd.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2pxevlqny.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gt2vpqoqbvc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgxpbml.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gt2jvoczuof.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gt2rtdfjkiw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2ihwsbjie.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccavvooo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gt2sdatpoxj.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2cpcrkoyo.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pftpgobw.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2yoxqolyb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gt2ebhiugsn.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gt2vbcxiifo.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2spmkwxju.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gt2nazmwbxm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2vyvxmvbr.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gt2bgyrgkrv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2ngkwqpho.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2rwvfxfpv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2rqokiuxk.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gt2qpeemtbw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2sjpmdexl.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gt2mdimltdw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gt2nrtadqtu.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2opmnqucf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2bvmydmxj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gt2zxogmmvr.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2jpchroil.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gt2oivcjlpj.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2ehmoqwky.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gt2udhaxybm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gt2wupcxrxm.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gt2nodjmhfk.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gt2itdcphqv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2cqbguaip.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gt2fccvycsp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2xazpendo.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2kmoglkty.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gt2tmtllwko.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2qlmlenai.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gt2cxpefeie.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkpkviwc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gt2yavzvdbr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gt2kcnjqvyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvvqlfsq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gt2btlzeied.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aposwsjy.html


<!-- 参考信息 -->