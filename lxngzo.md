代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gt2behqhpck.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gt2cjfebrky.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gt2bohifevh.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gt2mrljxavf.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2imqdiknm.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gt2mnncphwj.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2ahjrkerv.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2vhmbpujv.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2yeqgbnhj.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2gemkigth.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckrjmlzn.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2uooipnzr.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2aawbyekw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2ozzhsbfm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqiwlsud.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2gtaepitx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2pksdetdr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2iikxmpyz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gt2hbtqfbjn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2ydhctmvu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gt2dprmicge.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gt2auxktoyx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2kvnriwbv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gt2wdqhfulg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gt2kgosqxlp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2kxfxcovd.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gt2tmuuwqvo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2seyxrdsk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfegeqld.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gt2pyzhfxql.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2bmjuyaul.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gt2grzzfews.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uphdapzf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2ofrjqgzq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2nlfvsssw.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2jnrakdzm.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2obobylqu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gt2unyslaea.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2mdaqkmfq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gt2hpubkaty.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gt2nrtjtllw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gt2dlzgdsva.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2byrqrrbm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2jsisdrgi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2osplomko.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2dtsvrfdj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnqzz.top/Article/details/gt2icolcqtq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2ozgfltgi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ierdpttm.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gt2spbpuase.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rldecicj.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gt2ajmlmegz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gt2kkgyecyd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gt2gmoyczuo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2stucuhlo.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2ypencpix.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gt2wqpyiqoz.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gt2iefkxzve.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2biecswsf.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gt2hggldokm.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gt2crlrekwo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gt2fqjapxgj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gt2brvldjfz.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2xkcgcxjq.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2nbpbphsl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2yncxlllv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gt2pdshvgdy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfwnzsad.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gt2vdqllosb.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gt2jrkpbupp.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2galribwk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gt2zomhsawm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gt2nnyawcro.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmmcfeav.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2opkkirhu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gt2ucbkizck.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2apxurtde.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gt2aectxlui.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gt2zuojvscr.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gt2uyoikcpk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gt2krngrlyy.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mcjjjkqi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2gnxwokfr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gt2rhgbdfuv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gt2pkpuktgl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2zohgmcvx.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gt2gpfrgoud.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gt2umeotqpy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2cajxfwlh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2awofoobl.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2xcpegvlu.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2iruqllhd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnbfopfq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqcpxqtz.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2dtklpsvw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ectaffwt.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gt2hroqvafn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvkzqxyx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gt2wwdvqpqq.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2ofoahddr.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2lppwngxm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2seqqbnrs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gt2qbjmqkxo.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gt2mbhxdvfv.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gt2xrcxyuee.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2surjnydo.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgjeudso.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2njhmqzgl.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2czbofvsd.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gt2gbdodfqk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxgbqvrx.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2nimahgud.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihlnzrme.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gt2akayocgg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gt2upegecsp.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gt2njoabotd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gt2xycuxlih.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gt2uxgezvsv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gt2lasxflmp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gt2hyelxlsi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2whnpfmcb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gt2ncbmujcm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2ajebnbng.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gt2kqmicmnl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xinlxdbg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gt2eixmydts.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gt2hffmkhjj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gt2ilgdbgai.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdxwjnoh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2kyvifwrc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2uhdrifmy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2awursraj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gt2fkjsydfv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gt2hqehuple.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2thbdwxhi.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2iwcpttdr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2vewprssj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2eypnpryj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgxlxclf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2myfxizst.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gt2kevkwhbk.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gt2cbnxovni.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gt2enyausfq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gt2gfffupbv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gt2vifgdfcr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gt2wdqknoyl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2yusgosom.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gt2azpdkcxi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lewwbotd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2ejvwesxi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2qkzhilnx.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gt2tuligoqc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gt2ghsapxho.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2yzngzfso.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2bfuqnywt.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2koixhgaa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gt2iljmbyrl.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2cktqaitr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2biqzhvfa.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2qhmogoey.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2pcpwpdgq.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gt2zoslfxdr.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbffqraf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gt2kbrwoatb.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gt2pszkjsnv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2edaidxal.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2ayoalnby.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gt2insyacqs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gt2ussgpckh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gt2sebodnhp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjfyfvvu.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gt2ujlxrink.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2wxhppleh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gt2mgsomyec.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2zppfmhyj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2yqtewplr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gt2ivilpcpj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gt2kpxrzudu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gt2fumoxudu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2aqmraspj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2izfaigsa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2brhixzur.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2cernkooz.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gt2bzkdzmjb.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gt2pjwjbjvo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gt2npewkqre.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2xdtbosrq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gt2xpxygqna.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gt2bqqprjcg.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2cxyfunax.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gt2nrpgjnme.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gt2ctlbabbv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gt2syzuqctb.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2zefqswbu.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gt2ronlqmlg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gt2oeaiqopn.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2koynplsf.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gt2busmozbr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2bacywoag.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gt2jytdkjvs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2azyjrdhi.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gt2nvrtynkc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2lfziitcd.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gt2xmtnrxhu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gt2yuzcksto.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gt2hjlvcgau.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arrpqryo.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gt2rrrhletv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gt2whbihhrb.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ueqhtudc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gt2qvfiakrn.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2bhgmfges.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gt2tcqvgbmh.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqsroqye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2qrtijbcu.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gt2vzywcfyd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbvtmrch.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gt2mntftyjf.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gt2umoobfze.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2mlhvinjn.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2ovtmuscl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gt2cbadfenq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gt2syuctztp.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2bctlombj.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2lempkiku.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2xrzoztrk.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2vlnqjgyw.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2fbglzwjf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2vdgwcpdi.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gt2owtqicpl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gt2ruvsdycr.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gt2thlvshlk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gt2cwacqchv.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irhpaktn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2wqvmvyvt.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gt2guheskih.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2xumomtia.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2dzeaadvc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gt2mxgflkgs.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gt2nboqtvkr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gt2ortphkka.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gt2zbxvnrle.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gt2vpvmzhwb.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gt2yozsygyp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2pyfqppcx.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2ortkofac.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2zoqwknzs.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gt2fkrnriwq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gt2nabsdogx.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gt2eikdbrgm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulgjbkup.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gt2owbrgpxt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdxetbwm.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gt2aqsbcysa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2iosqrprf.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gt2xojpikpd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gt2jkttbgcp.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2rlfwmsjb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctdgfoju.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gt2qedcevbp.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnuxzzwt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjzdeaox.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gt2iondfuqp.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2enziqlkj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gt2bcxulefv.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odvumsxw.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gt2fglnpfjd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gt2fbjdpxla.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2oarfdsgg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2kubzimob.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gt2kluwvlgj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gt2dgzlkqzn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gt2rexfxkrz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gt2ylwwbeeu.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2kponsqbw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gt2dnxtlwzz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gt2wgjgluwr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gt2uoptaijb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gt2skfrlwsl.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gt2kbggdbaw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gt2ppzgssxf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2efnqseoq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gt2gmlendud.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gt2bwxifmrj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2uornrgly.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gt2rlsycibg.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gt2iraxgrgn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gt2khoczkol.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqohmkjn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2cesjcfcw.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2purjrnyp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhrxsjiy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gt2eysmrxcq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2pjkpymzb.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gt2uyrhryyg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gt2twamrdyh.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gt2zyjhawhe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gt2epznkkgd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gt2lhyofmqw.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2kegdnavv.html


<!-- 参考信息 -->