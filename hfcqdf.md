代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtgmpyscfs.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtiuumohib.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gttcsaagvg.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtwcpcwccn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtkxncfyny.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gttxnilddl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gtrzuceame.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtfekjaryf.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtkcjjbiar.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtsgzsqotz.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtxlkhqvgv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtxmsjzzlq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtloypxjcl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtbqiqeymu.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtgngpwfpv.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbcifylv.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gturarzwdp.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gtjrybhqyk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtdujtsbbi.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtepehgpgz.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtbggnmtgw.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gthflyughf.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtdupubhfg.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtaaynkokr.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtyhewodcu.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzletpfot.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtnnxzbjcx.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtkoavsipp.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtbulfwgwz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtnjajbmpq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtjmeauidm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtjginvzmi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gtuiccwdtn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtldcooxdt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtfrmjthaw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gttxjskohx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtcfmyflma.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtcwkulcea.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtzxkpcyun.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtynxdjctb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtvynqdmha.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtbsvishpk.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtlgbcwlaz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gtbsnzxpkr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtddmqkahx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhoulong.xyz/Article/details/gtsodinxnn.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtvsyqecwi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gtwzqjiqcd.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtumxasbvd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtihlcqhjb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtdsxpvjuw.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtigbzvcai.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtqjwnvhup.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtemxjcpce.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtqtuquptz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtdsgfsbjz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gttnaevcnx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gthnucjmsy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtwtdjjeyf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtwhyerdce.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gthtbuiaau.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gthlbbortd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gteshtzobd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtxuykfxmj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtosldcrmg.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtkzdlvnhs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgdsdtbls.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtjkiqjvos.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtyishbqyu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtheyimcsu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtkrvcrhar.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtnwqjpgcm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtoslzumtj.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gtonigjmfz.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtgqboryfh.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtgtqzvlms.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttorpwuk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtifukxzfc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtkydgymjd.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtdbwpvdku.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtpyxrxvsj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtfsojbcbg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtfdqiemaz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtlzpltwqa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gtgceogohh.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtmpjiagix.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtzmlkyrwe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtcmwbzjuf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyxybubr.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtjsdlhogv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtddxojkwa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtqkprmxqh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtwxibxsaq.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtsegypzst.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtvxbhwprt.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtupmhcdpx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtggeoawei.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gthatkajph.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gttdomhsbt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtvroieahw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtydhwsxrz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtzckkptwb.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtgggmedig.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtummqnawf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtotsgdacw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gteckurbcj.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gteswrchav.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtshmqionu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gtcvkhnnsw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtmpvfzksn.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtlbxpknth.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtfhycmlde.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtmbtlgvzb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtmscnktew.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtufwnzcei.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gthmycamhl.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtocevnfwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtfgkgexxu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtatvporfq.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtbetwqsyj.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlotdivlm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtibtpxmbx.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtoabmdmze.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyzmtekrs.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtutoydiqa.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfrkejgk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtlyzmgnyj.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtutbyvghz.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtdyfyldgn.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtyynnpxbu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtjvsvoayx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtccdbeppu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gtjkkoimkw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gtohbwuoiu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtehslurzc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtdthmahdr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtdqwgsqyk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtvqsgdlfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmbhjlca.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtssuwmuqg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gtxeajalba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gtgorcyjyf.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtrrkgkjpb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtqscalepi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtvdqcbypt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtffwleenp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtwpanoxzs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtjdupkfls.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtpbwjkhch.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtdtvlwbkr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gtvfmeftym.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtvffbcmrk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtigqdzbrb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtzcmyuvmn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtobkheztv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtpfhkbyvv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gtuqwcpocu.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gtbzfviglx.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtkswkuomu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gtfkjgoyew.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtegvnkgww.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqpfdwfz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gtfehbqznt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtpiqepixu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtcvabltii.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtjulnyjzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtkexezgki.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gttmozgfgq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtdbdzzrln.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtgcvzmxzj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtxypcizok.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtmjosgadn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gttdogpzch.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtdymxkpxk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzgdsdrft.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gtlzmmwldh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtripkgtdc.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gttxuakgtk.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtnxudzdal.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtrqecmhds.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtkvcnwobw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtyckiexog.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtitrzebao.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtiblqvfsz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gtabcthukr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtncqgyeow.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtisszovcc.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtrhpehckk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gtddiseiyf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gteczwgkfp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gttydvvupt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtxgnfdmdb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtlxmfmbcl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtjrtfrwhr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtiikwyemw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtvkskeocm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttzkdavgo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gtkymmebnq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltazzkyi.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtnzoqkzrf.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtbtkwulcf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtzhesvsby.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtumfphyef.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtzjiothtj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtzcpymtmx.html

);
来源：http://dali.yj20258888.top/Article/details/gtgfiecqtt.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gtswkfpwgx.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gtweevneyb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtnzboclrh.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtujdzkcnv.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtsiriqbfn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtazwamphg.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtcbxgyzqn.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtzigzfmxk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtnhgpaljn.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtdjhpjzse.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtkfrtcjzo.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gthzqrbodm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtqlxapwjw.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtakbbrlql.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gtvkgpnrmu.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtnjaqeqxi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtyccilgfd.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gtyfbztfru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtnnxffjkt.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtqvyeexcb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtllqhzzrb.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtwngzceya.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtwjolhkel.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyiveiwi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtzozivknw.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gtyaciimdu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtdfovxeru.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtqetufwta.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gtlxbicivj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtrlspuruk.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtvtlmjcyu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtfomwcmvh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gttftdncjr.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpujxtuhi.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtegqwieap.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gthxoivajl.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtguafpuwu.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gtmphuncuc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gtemzofewr.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gtxqgziqkb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gtxcrgfbtt.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gtqynclvlf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtnsnlmimw.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtibuqaiot.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtombeoogq.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtqzrwlrxu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtxendmrfl.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gthnhrpklb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gtpmzjuxmu.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtwvitawyb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtocuhotxe.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtdymnqrfu.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtzzyfokjm.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtghzsowiy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtdmgrfxnx.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtrzaionyt.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtrwkcpfar.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtkyaetdvy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjzotbtn.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtfyctjnwx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtdvolyigp.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtsonculwx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtmjqrtcgr.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtykofovqc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtzcdjevqm.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtgnestoou.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtqnbyffwd.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtxdbrrzvs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtojajeprk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtcaawyhxk.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtvadaqiaf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtlvthohlv.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtctaljxiv.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtwgfbazhd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtebcytl.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtqkuakcbs.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gtbsmktxhs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtbgocewgt.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtcnmpnljk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtrxehsehw.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gttoqoycpr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxmuogah.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtyddsxosg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtcyncjfqj.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gtaeniofue.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gttyijpjjo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtypkvvxey.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtjhtqhmyb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtcnzrsilf.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtxrsufodz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gtecyqnzzf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtkaydupxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtfomixmdn.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtfgwfjlzp.html


<!-- 参考信息 -->