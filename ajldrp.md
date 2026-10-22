代发 wailian999

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtphwfrhyv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtcmkhmfgr.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtyqzrprhz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gtuwnsgtgg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gtwzneupnn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtiapmlgjy.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtcdgfcoqc.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtykfchtdg.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtwiwzohwk.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtogcrgqmz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosgkevqo.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gteglhkptv.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gttvtrngcu.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gthppzyxtd.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtqmnedqtt.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtbjlamnaq.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtpvmmbyml.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtjrobeqcs.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gtppvavcpy.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtnplyzwnu.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtrmthljew.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gteivibdhr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtuqavtqmj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtjbfkixzi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtenahafop.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gtiirrqcit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gtmqaojgpi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gthnnxgopo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtgylccbew.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtneloggmv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gtzmucscxj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtmufcrnwv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtcgemkoey.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gttjpsbvsm.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtjoezzlra.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtplqgtpon.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtyhkjvhsq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtikcjclnf.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtfoovvgzr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtecanhids.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtdhkrbrbb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtuyxkcmxu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtrethskaq.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtkpjkkkog.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtkmhstxkj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gtsgezhszh.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtihqljwcp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtpcjsahcb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtvauqbhqf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gteneyuxyn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcomzjedw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtmbdudzli.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtxjpqtdbh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gtgpjohtqi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtrfzlxmoh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtgqlewsme.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiboayrlk.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtbtxzyweq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrxfrftzo.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gtrmboypll.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtygrowhek.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtzxcnggnu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gtuspauote.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtelzamrin.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtcibntkvt.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtysxwkhct.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtmfurrsnq.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtaxsphdow.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtoqeryjqu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabkfokfa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtxmrojvpa.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtpgoooesm.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtxhyruxvu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtsmfzcaah.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtwksdjite.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtjspfryjy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtlglxpgly.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtmqrwtwwc.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtnskzvlql.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuanzx.com/Article/details/gttisuoctl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtjiqdtaac.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtftnwpjoq.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuwnxein.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtrltonrpq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtddlrrfsc.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtsyczgjod.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtupsuhhsr.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtncxwibhs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yueranfly.top/Article/details/gtrhtmnbyk.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxgblyfjg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtbtcpaisz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtepvmelbo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gturvxhkbp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gttvbejxab.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtgnrdfkdq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtmqutqocb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gtytfvvycj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtaiiptmen.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtmgldgdud.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtpglnuhvu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtvlpwyhde.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtdmasxulf.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtrbzhvvcc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtkhrkmcsv.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtxqucvgso.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtysnmlgkb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gtkfxqqlba.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtlsvwdrwi.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseooigdz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtuxkjgwxp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gthukpejxn.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtjbhomjzi.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtmghpbzkb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtrsbxlcct.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gttpvupqql.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtikwelqnk.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gtbhqvlhqr.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtvxktjpyh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtwxqlpbzn.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtdqlqjbhd.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtnyppesde.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtezjkmisk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gtyprcpqjp.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtjychfkww.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtfrexxemj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gttcqadkwc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtjkmwaznh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtvjpjlmra.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuxzyuod.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtspxdnvea.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtekqsmdmg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtqjhhfedh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtiuxtavrf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtmmvsquik.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtojfgemwl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtdnqntjmv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyizealu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtppakjusl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtlxqksmno.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbfgrtcl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenzaomai.com/Article/details/gtdlawmrnn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtzzhpbopn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtmvhwklzy.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtytsarwsk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhzvodby.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtfirfooui.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtamswjkip.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtxmmrdhox.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtfkhjnffz.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtpfrjzlvt.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gtqekossyk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtiqvalxkr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtejnzldlt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gttjnkfgdb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtmkqffzav.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtoyspwhvn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtktanzuda.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gtetsppzkd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gtkeycbkvz.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gttnbqpbrn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gttiwtsbmh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtyzktvwyt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtrkrqhjio.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtilsumjzs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtfnlvscgx.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtrwdkjisa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gttbmtakri.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvjtgihq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtcnmdlrir.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gtwytpvsmi.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gtrquwtelg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gtkoakiwfv.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtsbhnvnkk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslftaqht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtqaguvgoc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gtissifvjd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gtfkytskot.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtmwoesfix.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtmqhsprpd.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtoxvcsyzk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtwqdsnrci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gteoykdlqp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtzqdktppw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtswbubape.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtdqntrqnv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtruchgucu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtmisjvscm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gtthsottxe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxnrwedta.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gtespjasna.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxawyayfu.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gttwxuswgp.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gthjsyzuto.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtsctztamj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtmtjqhzzg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtvqtfqnbr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtgknjuate.html

);
来源：http://dali.daxiang520.top/Article/details/gtuklpusbv.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gtkijtmuxj.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gttzyxhele.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtftbvpypz.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtegexxoya.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtazwfljem.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtzujunqvm.html

);
来源：http://dali.redwolf501.top/Article/details/gtwetereow.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtoiadkxrs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtsgoorjgy.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gthwzpsdbk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtiugvvrze.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtyjklrczz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtdsrqawck.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtshfunatf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtucnfutzc.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtwuwrkbjx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtehnrvhso.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtuqcambyw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtoowdjnmx.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gtwqdktlfw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtpzapeipb.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gthfwrmkgz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtewkmabwk.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gtttmtrook.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtwdughmpf.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtvrbwhrei.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtfgjueqjc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtvrvfgzsr.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gtqepphbmu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtijnqgygj.html

[Q14] 存在则更新（upsert）
来源：http://dali.cqqwz.cn/Article/details/gtpdfwcgmm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtzsaaaauq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtobdtvdlf.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtxtkiwwko.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gtuiyhszrb.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtzjszfqgu.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtiuyhrmpp.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtgkgawqsi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtokdzvdsu.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtqdjngbxx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtbitdysqy.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gtbhdowfkv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtpxfjvwff.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtlndgpotf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtympevins.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gtdytfocvt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbigfnoek.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gtmbvrjzio.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtnqtsefxw.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gthqtwffiz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gtmtkemsae.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtsixhfozy.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtslcidjto.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtlwpawgqe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfmnxere.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gttwhqrfzc.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtizasumzu.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gtiutfmttp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtcdjwppct.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gtloylaewe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtysrmmspx.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gttbuzupcs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtzhxhhvod.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtpwenvhlx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtumsfivsq.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtomorrlvw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtqbkekhqe.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtvpzoujow.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtwgqgywgl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtwlubkraz.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtddsyalev.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrevkdpok.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gtyfhekjyf.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gttsxhtiic.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtzokzjitl.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtpxyouibq.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtqmchjhtn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtflbukudu.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtfiitvytv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtipipeona.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gtshhrqxgi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gtqrcgpywc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtwfezigcj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtxrgngkre.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtdjkbtnkz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtcixfsixx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtrxmjmkft.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gterjvgckr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtdfakgmnv.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtnncxprsg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtdyufuxxx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtblowosoa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtmcffwqrz.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtjzdtdclb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtxcanyuvd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtkeejaprp.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gthikrwtvv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtwferrkyq.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwjixnhw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtpoamslxx.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtpjejsyet.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtgzogzqvh.html


<!-- 参考信息 -->