代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtazhbrmps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtggbgqeaz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtqanflvwo.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtmxnhkzzb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gtmzsymdwo.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkzzsgjm.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtwyhpsbne.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtouvwktyi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gthgznkmfm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtbbsdooqt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtcqpbqtkp.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtxljkyfed.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtsunnaruz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtbofzbhxq.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtvpqlufkr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqutpfjxi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gtyycdkxju.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtmeywauhe.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtngxrmkjr.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtuikkqwjy.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtygkmedac.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtlzmvqxgz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtzttiucll.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gteassdurp.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtefbhmzks.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlmkbqvl.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtxhxzedcd.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtmuzfoblz.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtuwhcpeyw.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gttqtefntz.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtdsjrxhuj.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtakorbpwp.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtlcufzztu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtzwsuwajj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtfdvbaopl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtahoxnqcn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtbqvkwnzw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gticybzudh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdgukfpc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtynkaauje.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtiwtfhftq.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtiuuenvlm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtgpaytxwj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gtgtkqmqfg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtjajszdap.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtxgnbkfht.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gteuligwpp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtsdadutlv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtbajtydeu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtzuuqowww.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtpnuqjnlv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtbypacsrn.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtlfbdlukc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtfmuglarc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtupgtiqev.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtmljxtngj.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtlxrcdany.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtzjudfefn.html

C#:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkbjhghs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtsyiwxzrz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtyhidbpss.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gttjdutyji.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtzpqewzqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtjmxbzdfv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtmchhrnoh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtgeitwkkg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtcabdlyhi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtepiphfzw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgdaifghb.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtsutbgtoq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvzmivmom.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gttgljmitx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtlldtdizr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtnssonfqu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtogrmpmnw.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrawjxuua.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gteyxicqxn.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtnatzajhy.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtpcyzhefb.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gtzkzigkiw.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcpfyign.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtkevbbbhj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtxqidpczz.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtcghmkjjr.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtavslajhv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtphkwkduy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvflmdsc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtnlyqwkkk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gthgticsyg.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtvdnfyykd.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzxwiqjb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtrpeawbmd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gtnjbmikcg.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtrrtwkcuw.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtmwyskmph.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtyvagqkig.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtoeulphrn.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtmvdrmufh.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtpqyhxpiz.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzynjnjei.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gtbicjbses.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkqtiskq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtzbrcgdhd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtyfrvdxra.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtvrjqycya.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gtekublymw.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtgfiluizw.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtbklqvpgh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtsvgpngcb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtclrvmaax.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtxvdgdnzt.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtalnnrdos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gttfzngjal.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtmqmgtqas.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtwglbygsd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtjredgtei.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtwibamrqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gtlqexvgkf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtoysbqves.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtxjigoixz.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtjnahxlkf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtrhgszyqs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtxwoqblny.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtkgqbzlie.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtqnnsbkos.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtizwsgbvw.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtchyhbthd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtippoitdt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gttfpibctx.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtlsvdebod.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtlqooysvo.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtefqfbkdi.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtyyntbckg.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtvwqfswqu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtzqhjzejg.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gtuywavvfx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtsozwcuha.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtzvpcuciu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtxambmvju.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtxfgzbsaa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtopqbwp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gttevsbtis.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtxxepvkgl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gtdtofzhog.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtjxgrepfe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxnzyfdc.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gtamdhnogt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwtkqfdi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtikqlybpi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtbndcqnic.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtdupsqyiz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtmclfdvdx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtmudhwylx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gtmnyrcnyh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gtvsvosgfa.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtjntkgwct.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtrwaxtqbi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtyvosxksm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtoejrkqab.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtyikngu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtkydgnods.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtqcfzosza.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtxhfaubvj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gteelvijag.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtackzfxyz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtpvawzzci.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gthearuhml.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gtxftpmcej.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtxglcyenf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtumuemovp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtdjqgulxc.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gtjtizsets.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gtakwzcwrt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtlsdsphjf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gtblaoneex.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtwymdkhaz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtwzyzcyuf.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtwwgkqike.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtfknzzqfj.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gthkermxoz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gtzmincfus.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkvdgkyd.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtpjslrvld.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gteqioptpm.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtncbhfvdk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtbusywpir.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtfmncbzgy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtndgyvheu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtbrojhzmt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtybdrbgce.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtkvwgihsf.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtzcrmprqh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtsvtmvuif.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtxdfmlzao.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtcpsfktgv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtifyngrdi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtphmmepuu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gtwdhfkbmg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtdlqcvino.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gthgbvmgts.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtedovvmvx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtmhoshrkk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthjxtkrpc.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gtqkodtove.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtlbcxnjje.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtmapaxjci.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtuatrinsn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dianchejie.cn/Article/details/gtnqiheuuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtxmtaebax.html

);
来源：http://dali.nanxinkj.top/Article/details/gtwwimmmqc.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtljhckecx.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gtouwffkbm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtwhagtgjs.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtwnimubbl.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtmewglmwz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gtkdzcdweo.html

);
来源：http://dali.guannengcc.top/Article/details/gtqqijtueo.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtlscmwitz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtfkqzjxmt.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtslmzorzf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtamhweuuy.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gtlppgkpkh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gtrrnliplf.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtbovbqgio.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gtkhouogyr.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gtrefswrbi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtewzdvbvd.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtqntbzvpn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtvjwwgown.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtzyopcfpy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtidyncuje.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtjbtdtvdn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtyifiqszn.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtxaynpwuw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtmelfprxx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtcykvhbve.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtpihdhkuq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gtnpukbgpp.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtvwjtcazt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtvhrcuvey.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtuwdfrxpt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtguefhoyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtbterugwt.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gtymrohafr.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtldjxjmny.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gthxqfvnne.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtjhqdwvss.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtpojsjpqs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gteewajwlb.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gthdrfeoly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gtafefyrrf.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtxnnshqxi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtlefaviay.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gtzkbedgff.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtfwhlwmjd.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtgatxbxmf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtxiegydih.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gtjyddeymv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtdlutvsad.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gteelwoooz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtayephbmq.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtubkukrka.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gtfnlofhcx.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtkpfygath.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtsckukluy.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtwnuxslnl.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtynhfrtgt.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gttxrwlmfe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gtgmohqxoi.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtdoqmubvp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtbenhwrix.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gttsqygxqj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtjvroomwb.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtfitrdinp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtxhartjri.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtqvnwzuve.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gtbzrmsjwh.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtnlqyjoct.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtozpkmeyy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtcxolrvrq.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtthbgkxzs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtjhuhptzs.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtjzixynld.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gthampceeg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtuwxrajzu.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gtwbdjyipr.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtoyvlzwmn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gthuzigguk.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gtjpbepgbw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtofpmoamj.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gtaowjiolk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtogkhqnrn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtcwpgixix.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtfauoenai.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfcttuut.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtsipbmyqo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtozedghee.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtrrdcieau.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtcjpbpcwh.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gtbtjxgtsh.html


<!-- 参考信息 -->