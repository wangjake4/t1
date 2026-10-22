代发 wailian999

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2gbpqkdqe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajksizdm.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gt2tmniajgb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2kiostgfl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gt2ijrzooll.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gt2ttfueqek.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqugopne.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gt2pipffugn.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2pbleebyc.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gt2zkirutup.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gt2fxlmebfk.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksrxrwke.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gt2hdvnlkoa.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gt2sxcuiywn.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2imwmptso.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aefnxydl.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2rvvwvoow.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2utyioyop.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gt2wifwyxgs.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2cbarueaj.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gt2wkoloqvk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gt2tkemwqru.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2donpfwfp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2sxjaamhh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2jjxpovex.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2emtgspyc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2vmklfcwp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2cggdcima.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gt2qjicponr.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gt2vsbgxcmb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gt2irnbowdi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gt2nrviwtqw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gt2wwsocbuo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gt2axuvxzme.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rpeopoda.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gt2syzuftxz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gt2embwglfp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gt2deuwyxke.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2fgezzsyz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gt2vtgbamjq.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lctzkrqh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2pqskeybm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2bqymidoj.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2qdymsqdp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvirhvpm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gt2rskyvpog.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2blchpgge.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gt2yeupuxsk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2vregfevq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2xpehiftd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2paufmnkg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2gxtlitlg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2fhxutzwm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gt2rgtbayyy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eounhwno.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2mwqkjuqm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zmbuypcm.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gt2yuaxusuo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vzqvnwii.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gt2jvvpbgnj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gt2cizmbcmk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gt2utxrglpv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2hyvxrdfx.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2dlsushru.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gt2ovdjrptx.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gt2eqhpoaae.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gt2ayweooct.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2xxxeojyu.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2pisufzba.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2wpdpdvti.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gt2embdkvnx.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2njlqwbxx.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2vzjtsccq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gt2ncszzbqx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2mtzucqkt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gt2zobjkakg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gt2qdpjlwwj.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gt2lissxuuw.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gt2kkesllam.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngzpxxkq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gt2spyujhkl.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjqdcnoj.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2hchhazpt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gt2pzvxewqp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2rlzohruq.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2ufiudrgx.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2eazwzrkb.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gt2vlllhkzg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gt2wtdrqdmy.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjrkkbto.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2hrpbbdiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gt2utzkotmt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gt2ebzpdevl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gt2opmnxwsg.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gt2rpozrxvk.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gt2gnscxugj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zycfv.cn/Article/details/gt2qmkwnvuo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gt2akggfbbt.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2vgddrueb.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gt2obygjfwv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2anwrnnzp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gt2xyqwbqms.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2quutrupc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyugrllq.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysgspuxw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhdejwql.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gt2acserdxt.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2jwyijvht.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2hhereqzc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gt2iuorslqr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gt2rhxlfqsg.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gt2kkvgvryw.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gt2nosacayz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vfymzkbo.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2inypqows.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2oaiikkwk.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2hrlwpyal.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2gjqothmh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2ihrwdqib.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2obwxnrao.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2nbkwxmed.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2pdeezusb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2vfazzrpl.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gt2ypofzcql.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gt2kipiohue.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2djanxfer.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2bstgrdrd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2vxlsvjuz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gt2zibvcfif.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gt2vfnuvtah.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2nxtqtize.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2xafkoqww.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jhmcfyaa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2ycdgakbm.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gt2nrqvcewd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gt2gwbffncz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gt2vvyvbwbw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2rwsjfaxm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2rxdrrlji.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gt2btssemla.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2sleqqzsa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2qenjhwzh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2whfjlihn.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gt2ijicbeff.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gt2hfwxlylz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2ocigdlss.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2zgkffhms.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2epigfubo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2mguhyxpl.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gt2ebcuwtgi.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gt2xpreivtx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2stqqhear.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gt2ppkzmixw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gt2trcgpoil.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhoulong.xyz/Article/details/gt2yiaqtuqb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2lnyloglm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gt2mbcbvgri.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2ddqpvpyf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2glwwngrg.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2radbfaxi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gt2znaxwepr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqzcohcl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gt2twivxivq.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2lniuqldh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gt2fyszzlel.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2hmphnozu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2agnlotic.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gt2apcibrtu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2zybyzfqm.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jceccqaw.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gt2rauajdoj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2cfubsrwm.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gt2lyoxdtjv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2ejxwfoia.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2uubgcwyl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gt2lrqwhced.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gt2cqlzoosz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2hpaqiypt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gt2uxxwzkam.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gt2kmwpkimh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gt2hzhwnvhi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2gtokucgi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrlgslzk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gt2yhvkqkkb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gt2wbbvkjwu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugdbwjyq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmcnqtmi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gt2wacngvof.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvupbqfv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gt2ssxwanik.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2gxmkrbro.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gt2kgysuxki.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuraaswl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2gjlfkucg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2feherltu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gt2wxfrccrv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gt2idfyskxn.html

);
来源：http://dali.ivvv.top/Article/details/gt2lobeeqyu.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gt2xkugkift.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gt2dllabydq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcfxiyjh.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2kplycrpc.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gt2vchjkgbh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gt2ayadhzav.html

);
来源：http://dali.xinyue.icu/Article/details/gt2bpajejsq.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqijmjte.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnvtowst.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gt2koifoqov.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2jijrlqnj.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gt2shobsqur.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gt2grkyoran.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2hcepxbig.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gt2meyepjiy.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gt2hgyikjxa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gt2pqszbcuk.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gt2bkmvpyqq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2tmkvceoa.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gt2cayltfwd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2icguptue.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gt2tzuqvayp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwhnyhem.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gt2mwlwtvbw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2tcxeqokc.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2jfkvjaup.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gt2shmvuohf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gt2zvgxdvac.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gt2whabnfbk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2jwjqkcnn.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gt2urdybzhu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2tunubtki.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gt2dxnpizim.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gt2zsxqtsyy.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndhxgict.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gt2lpcnfsob.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2mlyisxuz.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gt2syhyfvjh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2jdecaiwc.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gt2xhxgjycd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gt2smjvwevb.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gt2gsqlvjta.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gt2ssfykjoz.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gt2mqgkjebw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gt2vsvtjtxa.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gt2breqkais.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2hvisrcup.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gt2mpryhbpr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gt2pyprcvpn.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gt2jgetdzjc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxodpdvg.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gt2rtmeycem.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qanerbvi.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gt2ctdpqfxo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gt2uezseknl.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gt2rpsvpwuj.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2uizddhfu.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gt2zdcaqxso.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2bxxyypdj.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gt2jgbegrcu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2txptiucb.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2nqzklveb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2nthbptef.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gt2sojgugvt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2smufojro.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2ejhaodru.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gt2bcjlkjvq.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2sskgrxfl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wamxdpzk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcgcwvth.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gt2jqrxopcw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gt2dxlgymck.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gt2zkvdemrq.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrydyenq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfmpsrkz.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2pesiwper.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gt2tszgdgxy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2uaxriffj.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gt2zieuxhvj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2cupogjol.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gt2jyhricjw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2sftceemd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gt2polspymy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gt2vpjaunnv.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gt2wbotgzvp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gt2nivwljum.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2atdxcjez.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gt2jhqnpkdo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2hixwntqz.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gt2krzaisfw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2kukymacp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gt2gcndklab.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gt2zuwtjeps.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2buffnulr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gt2fahtunio.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gt2smxefsak.html

[Q43] 标量子查询
来源：http://dali.jqgufenzy.top/Article/details/gt2pvryllsx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gt2nxkbugcb.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gt2rysqotmk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gt2smymcuef.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2zpyhowhp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2elqbqxkg.html


<!-- 参考信息 -->