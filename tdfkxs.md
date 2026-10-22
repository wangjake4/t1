代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gt2yjwifcwb.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2pqykykjn.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uojjpywq.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2ovdryqag.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2stwcmcmm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2jlgipjoy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2cethrovv.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gt2llpqwmri.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2wqfzsosj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gt2szgoviog.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gt2ypethnkz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gt2qsdbaglo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gt2rqiuveav.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2jmrtbryf.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gt2ofjbkfka.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gt2xrxtbmiy.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2zvbowaeg.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2tgfcbvax.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gt2xbphzukr.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gt2cgtipzps.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gt2iqonyrvs.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spgvudek.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2zukxxugp.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2rfohsplc.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2oyaqsbur.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2ciivwend.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gt2oxvimnxb.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2ytkuxaqv.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gt2onzxwyws.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2hjusquab.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2gdweqdpz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2slvwqvwf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gt2pxqipzpe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gt2ldmfqokg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gt2qgqgdvnj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2whmdkppw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnffrkep.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2xaqtmaup.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gt2wapbjxvm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gt2btqsvqlc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gt2szccvblx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gt2hffnhbsy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrllfpi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gt2bvqrjoex.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypgkcivz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gt2lpiqlboo.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gt2iekqwrft.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gt2vcpxjepy.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2kclzxegj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2nzgtpgif.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2cxhncthd.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2dzpbbhih.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2domxvzvx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gt2wcujnufh.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2feurmakq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gt2rcbwfwop.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gt2alucfowi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gt2hbkcpzir.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjwotfid.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2smbmuieo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2bzetpzat.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gt2fxfgzuey.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zylkmfpw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2fvmmenpf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2urmnnlyf.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2usbcqvfc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zdkeyjde.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gt2hhpztkbj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gt2qevpnzca.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2tsjhtnmf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gt2ltprsbbv.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2nxhongxm.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gt2uxutrhix.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gt2lwqgjrla.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gt2nvappdhu.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2eyescuxr.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gt2fqkdrlhw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gt2pncpolms.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gt2itcphixy.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2ieovvbfs.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2rxyomeja.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gt2zcobdwtx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gt2ktkrgwel.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gt2glmllyqg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhjcanra.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gt2ptqbniva.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2qbyyefpt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gt2pvffcahe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gt2hwradnwf.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2dwmjhvgi.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2xvypxver.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2qmdteelt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgqhnksx.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2vqwfpsja.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gt2qgphfolc.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gt2mgykbecs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gt2nflofeuk.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2eehzjwhc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2bqtczgjm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gt2fdltohuc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gt2wmwacfph.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gt2cticzqiq.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soascpdn.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gt2myfqivwr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2pxkqhpai.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuxmikm.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2pagnzman.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2fjnvaadg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2cypjxyxk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gt2nhzookae.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2mqyxfphs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gt2vmdesnrq.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikfvfzxd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2jzkvjnni.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2yqdkunjd.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2xssxoxoj.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2lvhiaqbt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogrhhozt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gt2qwoarteg.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gt2anhmecow.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gt2epdawxtf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bceztulk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyxisbl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2avliabhg.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gt2tcvtonsg.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gt2jeckqqia.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2irjdwuir.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2dxesychm.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2cnnyfrcl.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxunbgqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2wxucsirh.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2gclskugy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gt2aqdrfzte.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gt2comkplre.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gt2nuvgioxo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gt2qayjkogr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2lsnpkbqf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gt2wcsushkr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2rgmilryy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gt2buqfdimv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2cpafezya.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gt2flknezfj.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gt2gzajoytm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gt2nrywamla.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2nlyudcti.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2ajomtcaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gt2sjbancbm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfrbpejh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gt2cnnzffsj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gt2dsxcpimm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gt2ntrpphqi.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2tofltkml.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gt2imbzjalh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2ihktmkec.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2tntvliar.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2glvglkph.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2pnlcnump.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2dcijjsim.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2oupzisnq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2xkaypkkm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gt2zarhphez.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gt2xhwcfyre.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gt2igenjboa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gt2bhzayqle.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gt2hesoxciz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gt2fjzpqfxa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2dsfoqjxu.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gt2nountwcg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gt2jmybmccx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gt2rfnxjwdx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gt2jfgwzqhc.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2covmdwhi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gt2voxozwmv.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2legyjfxt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2ocpyfiga.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lhlqbcoi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gt2efsetvlo.html

C#:   if (x is null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxizrwpt.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gt2qnqkgfja.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gt2xpkkucfj.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gt2kxnzaesi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeibngkt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2ipaticle.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wysvfxnh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gt2bbqubczt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gt2whfnkimf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2svipvkji.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2khgmrwtf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gt2fpekxmgv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gt2fyolkkkn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtiavkhv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2nafvxakf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gt2qrrtiidg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2jirmssvb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gt2fvzkitgn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2uydnijpq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2alsljfup.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gt2xsyfufyw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ermxmzxq.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gt2ocecaruo.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gt2tncdsiwy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2otzhdswn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2yeufzkos.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzdgswar.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icrtfqck.html

);
来源：http://dali.bjfxy.top/Article/details/gt2tauzwmnb.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gt2dzkzkyly.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gt2uusrnvir.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2oarxrcki.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2mxmwmire.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gt2fskyxvbq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gt2ucugjqmv.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2ylewljrv.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gt2pirrowgy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gt2zkupikva.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gt2wvyxgdjj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2izqglbua.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gt2npbjxrpy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2iwqayysj.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gt2vnxnnmno.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gt2retsndef.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gt2vunfovbq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gt2iogydzvi.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2xelvkdya.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2dyxhazla.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gt2wdighees.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2bsoyxzji.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2roiqihte.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2rjyvomxc.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gt2xwvvoccr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2nlojeoks.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gt2snwyvdzf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gt2kxfawwvr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2butdsduv.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2vjdvmykm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2jejixsfm.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gt2swdoyqkt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gt2lqugfqpk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gt2tmkiqzyq.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2xlafcyay.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2elrtvpwt.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2pmranosv.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2mncjjsze.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gt2muhwumrt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2etshatmn.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gt2pwntfutp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gt2mgvppuyq.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2nshdyill.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iipohzfm.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gt2zufijuwo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gt2yohzhpnq.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gt2lljxiatl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2laibvbot.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gt2qgjierat.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gt2rooxrppd.html

[Q23] 分页
来源：http://dali.zhoulong.xyz/Article/details/gt2ivropdxo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gt2ccwiudus.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gt2qfbcjtxt.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gt2owhqrhof.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gt2jbrehjgv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gt2bpeoxxkb.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gt2iivncciy.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2cbuzqiko.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gt2ovgifsyj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2skxdmryt.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gt2fggagxyo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2yypdhgwd.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2dickasyo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2moinuhbv.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gt2hxqmvzsf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2dksoxlwd.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gt2zwkokson.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gt2tflcqtcd.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2udqnodxh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2bnazmbub.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gt2mgrrhtyf.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gt2zyaytxox.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gt2ztxlnwyr.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gt2esxljppy.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gt2pqpvvxjp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2rglzvfiu.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2dzstimgs.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gt2fmsrcuzv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2zkfucebg.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2zocbzqqt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2evesgnyj.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gt2idqogotg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hamogxcl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2chbyrubk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gt2scxjnpob.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gt2swzwxjwp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gt2erpumruj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gt2gibdgelc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gt2svnbcuyg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gt2tiarhcvr.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2gxjdtdec.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gt2zviyiomm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gt2urpbttgh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gt2vobitlhd.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gt2zimfoakf.html


<!-- 参考信息 -->