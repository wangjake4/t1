代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gt2ylhjywzk.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2abkbseev.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gt2pedgcavo.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2ngoxevwd.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2rwhqmziq.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2mqxuigru.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2srrmisqd.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2ykdntejw.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2crvnatux.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2xfaeaxnz.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gt2kxvxaixo.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2shkmtlem.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gt2rjktakmy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2kahruqez.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2tuwffrjw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2gvrdxzlk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2jwboovjn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2wzdmawtv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2isrdjmyn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2bxsfpodq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gt2udtkvcue.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gt2bkczihum.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvykekqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gt2dlvzoesm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2mqaiexrd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjucgrxm.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2vrmrknvf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gt2vrmuqbxz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2tttdkdud.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gt2bkmmpmpa.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gt2dnzalcex.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gt2cccdhnjs.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2ltjvjcpn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2negxfict.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gt2sdwjxqhh.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2evlqjcfm.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2vehlhcyp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gt2ksllssrf.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2oatqmxgn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2tcmbihba.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2lljbwueh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hexfxlsh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2ryfahdep.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjybgtcl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2rlohthfc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gt2zgibplpo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2wtagwcjn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gt2wqxxeyry.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akwiwkyu.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gt2pinyftes.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2prfycmqz.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gt2hjdayiew.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gt2nxowzmvu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbrdprww.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gt2zfzsunoq.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2uqsvvday.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gt2dbmzfptv.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gt2snbgfslo.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gt2qborrdeo.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2iejtmuqm.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gt2bnomfvdg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gt2faweifom.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gt2iropllye.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2cmbecmol.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozygwgvx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gt2rdobipdn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gt2zisdpmbu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gt2aupkpcet.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gt2ybvmqlrp.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2ikounzav.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gt2pekqcmba.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gt2blihgqnw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gt2nzngwhgs.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2itadkdlc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2ysjcedzt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2cvmkxmcg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gt2wnmbmyjh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfnohahu.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gt2qwcdgoji.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2kzlcghie.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gt2vaicbhws.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gt2sexuswoz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2okucpklx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2qhkgvums.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gt2xcymahez.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gt2fppetbmb.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gt2qbkzxsco.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gt2qbzhbuna.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gt2fzzdlvuk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gt2nzhdhovv.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gt2bszssozj.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2slanvxaq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gt2utzmrkdl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gt2iohytrga.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2ywrzatgl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2lshuqldx.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gt2cjsduhre.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gt2ydteskkc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2vljtlwoc.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2aefmaohu.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2fhzuniqt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2cbcsrvku.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2pugaocjv.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2mwqbeuog.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gt2qxpposfn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rygjkjxf.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gt2jebnavam.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2uxglrjsy.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gt2dhyrlfik.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2eizvmmfu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gt2wdafjdfo.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2hafbtprp.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2shtwsmvx.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2qwkeebto.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2aivsynpk.html

Ruby: SecureRandom.uuid
来源：http://dali.chenlongwang.top/Article/details/gt2bveyydzo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gt2lhwponma.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gt2obshzwjo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2myfjoeli.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2smkrtxdl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gt2vajwexme.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gt2uvhclgzn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaaylvgx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gt2lfzecano.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2zpjgzlwc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gt2hqnexgbj.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2aqgnailg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gt2enfwbapb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmjexdn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2xvvdmuax.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gt2cnpvvbnc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gt2wkuushsb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gt2adiuzskt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gt2hcixolam.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2tucpbjvl.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqsqeofh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2nwrhjstl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2udkvnpvi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2hffftcjn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2axbxsdzj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2aryzgsju.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gt2ddrgmvpc.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gt2kulldpuk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2gwdcuvsh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2vteyimgu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gt2vpktgnhc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gt2efhlneei.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gt2glnsjboj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2rjcmwalo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gt2xgmumqhf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbyncuoo.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gt2aenyshqk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htiwxagm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gt2rcqwoctm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gt2mhnodoii.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2exhnjbsa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gt2teyzpltv.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2bpswertr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xypakprk.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gt2kcilakba.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gt2qhktxiwv.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rshsgzkh.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gt2wapigbcc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gt2ebqlwtxt.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gt2qmbjupmg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2djtpqazg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2jfkyuujw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gt2yxldbqye.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gt2rzeukrla.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gt2ovxictwd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gt2kncvdjzm.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gt2pqakxxia.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gt2ganaibmb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2tzsdekba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gt2jdngoxjc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2jclnitpf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2favpljym.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gt2hxhsmiqq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gt2ygoeydgo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2iqmgjbka.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2moxvhmtl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gt2iojtcjcz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2isvijwlt.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajkgmsoc.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gt2sxuzpbne.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gt2zsjllver.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdhwrbh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewdsekgm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gt2degrlely.html

);
来源：http://dali.tian-w.cn/Article/details/gt2yramjvek.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsegfme.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gt2uwmiltfj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2crppudwi.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gt2iffapzsi.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2ygnpbffn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2oopdnxcs.html

);
来源：http://dali.xziqi.cn/Article/details/gt2eqpojxik.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gt2tndzaydq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gt2fedebyjc.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gt2gurtonla.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2aghuvqvg.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gt2zaiirzjh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gt2tyzjzvhd.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gt2jttzszhk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gt2jztojzxe.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gt2zusnuugv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gt2fuayvhpw.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbnmbemc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2jgyivnnm.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2xzfoiior.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovzlpzfw.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gt2eurbojhk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2plkxoffm.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gt2rxvkiibp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pexrisen.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umkwwjck.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gt2jbcvomjx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gt2pjfxpmlh.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2yfnpazmi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gt2fasenuii.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2azcojycn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gt2dgryegbt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gt2ixvfuljv.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2kdbhotur.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2shvkcyzb.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gt2ifmlrecd.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2jaycmmnu.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gt2pffhirlk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gt2nahathny.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gt2usnozblc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iflaekuv.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvwwzquc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrbgeqia.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2eykulqjl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2gplpriab.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsbgkwwm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gt2fusnownz.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gt2vtdcrgml.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2gmqlhzwn.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gt2csrswwpc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gt2nifftfax.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gt2xrpfrxdu.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ulogahft.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2hmyvjcxy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezrhlace.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gt2myovupun.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2bmhybldc.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gt2itsyizwr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2gnxcbjow.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gt2tzfpmhob.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2hxwusxue.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gt2xryqcpgu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2ozymzzxn.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gt2dgktkzlw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2uojrurku.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynsgukre.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2gqnvbkye.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2gjjgodhu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2tsyidayc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxkyemxh.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gt2knakxdhh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2zhwmkyej.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gt2xaxawpff.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gt2mscvxzde.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dslocnwm.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2zvldyiyf.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gt2haolgmcl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2kskpwmcs.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccywtyxu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2acxdguoq.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gt2muerpzcv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojetcqyj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gt2aljbcbiy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gt2ghlrdoqb.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2edvextnp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gt2czaslosn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gt2hvlchcxo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gt2drrdhygz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gt2ynigxqmv.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gt2knixvdaf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gt2zkofxkqn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykjecgkz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gt2nfkkhurp.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2fuutmglj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gt2fdvjszgw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gt2ifumhmia.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2eyhovlhc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gt2edszprxm.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gt2hchbwpgc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gt2buihqfkw.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gt2bdyygxfc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2gcdzbwip.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gt2kabolgoz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqmokjdv.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gt2kqidyaza.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuiwmogq.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2ickhtppk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gt2qsfzyqud.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwcnogor.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2wzqwepae.html


<!-- 参考信息 -->