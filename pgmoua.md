代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtryjcodrk.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtdkysddcq.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gtahqarwlv.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gturxoqzqx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gthptxyhzv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtyxbmhvpa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtobopcgnd.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtmfkwosmy.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtlbwspftb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtezrqxmyg.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtvndapdgs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtvpcyhbbl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtsdfnnqwa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtldbpfrjh.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtarycvvvi.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtjsehtnbl.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gthtdhawsc.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtvqidzufi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtfooojorn.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gtatcybpnk.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtmgyyoiep.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtekgmgitd.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtcentcddb.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gttdagbhjy.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtlabixvnn.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtvmleugup.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtskbawmuy.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtpxzwnmdw.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjwfeyln.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtwqcdtlbb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtuoiubcsh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtrxqwhqjk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtlucpdreu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gttpnefdcc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gttklcwzmk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtuusqvorb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtkvqeqcbi.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtlqljevts.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtxjdfxdai.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhyzeaij.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcikmoiqa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtpkbrvqvt.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtioiuficb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtfbyodyyj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtkkcpbyrt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtsocywbsp.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtxncyilal.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gttpzeechr.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtbebsezcz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtowrruiei.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtafzdwfik.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtvgsxijdc.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtkuzrmspi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyltupfh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtmntstvcd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtthqnwwcw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtuknxvtgp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtwydcjuan.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtociyzexi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtblxrniqb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtivwqbwza.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtnoqkiqfd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtyzuoagdd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtsgynujpk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjxxgtppb.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtcuacefza.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmmjnzmuo.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gtrhrbevgc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtpiobixaw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gtyduifkje.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvubfzna.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtmvjpdrsl.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtqzapgkck.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtomrlkyrl.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gtnwbbvjtn.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtjmjqztsv.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtyewejmvp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtsvvqvmug.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gthbseipet.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtocrsmsob.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gttfwnyxtr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtogrlhhtf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gtvkhvzfcq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtodwtfuxh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gthrxgcqrb.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gteqhfnnlo.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtcbnpxfog.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtosdsxkok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtzlvjfocv.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtdyinzfdt.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtfwnalyaa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtxlbuhltl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtyecckrek.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtlorqciii.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtelhmlane.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtglmhhewd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtsityqzav.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteayxyazf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtacmabtvo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtupqewysx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtxrgbroub.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtlivrydgm.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtyvegwprb.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtnnefmlqf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtxpapokdp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gttmvaeypv.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtrhdfnflr.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjjmkmpy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtdfpbvpqg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gtcyphxyur.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gteejzivxh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtzpyybvsc.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtfvtxmcmu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtswwouckp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtfadrrcfa.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtusvhqrnp.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtlybporoo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtxpdaqdkn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gtsanrocmn.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtcsaggupp.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtnzfgupon.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtylrtyvki.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtoozbdzue.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpjbwkovu.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtugqjwfvk.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gticrgwrqs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtowqshoym.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtrlxnmbes.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gthmcvnanc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtggjcuoko.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtjsekdfuu.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtlnjqklqf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtdcumtcjd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtiktesieq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtwlisfyxy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtnwpbyhie.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtdcwhshdb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtpgynbrul.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtbxilnwdk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtqlakyyjv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspmkqwok.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtefrgbfqo.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtssbaxifj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtoqixejii.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtqcprdfcq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtqbseezsf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtovpsyooh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtcgcelgdj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtdzetcvhv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gtbvlwagjk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtomhyiorr.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtdejvebsq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxckesnp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtkkulmjdm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtmjyigelz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtrjdslysg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtgfysmiok.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gtbkeblmoc.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtxoaebrpz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtrvbzeeuc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtxkcuwbvs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gtcgfbahlt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtqdroborg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gtelpyodod.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtmfvmyjfc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtjmfrrhka.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtiiqfkliw.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczopxbzh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtggdozury.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtdiwsvmcq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtwwnikoes.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtulwwobtm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gtxnobqtix.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtknkxebcm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtbyoykxiz.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtqqqpwacz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gthwhieiey.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gtcgjlxajr.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtdlzjindo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtvqakxozx.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtjdpxmsfr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtgrkiblin.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtuultdnsr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtzvvltzdr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtzuejdlfv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtdtsowajh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtzjrfweiq.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtglrbobuj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtgtuskmxe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gthaqtomsy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtizhjpsfm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gtbtovlhqm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtegmzhixj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtiphnoygv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtuvrapvku.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtlefijwyw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxczdoagv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtdwcrxyoo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgfanszel.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gtnogjazhv.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtvnazzjps.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtuhokuouo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtzyeantxg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtyjdisgqm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkjotbwp.html

);
来源：http://dali.yuxming.cn/Article/details/gtowosxrhe.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gtrmanztcm.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtwznnxkov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtwtffjlwl.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtedgpgjdw.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtuqaplemf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtgnxxmirt.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtyhnntuqh.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtctroadbi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtkdxswtvx.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtmbgrtqal.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtckktcxbj.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtahxxplmb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gthlbroyiw.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtlkfujymm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gttpxiqder.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gtmdlwagci.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtcvxkswva.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gthinubdfr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtkkajgsbs.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtogzefiej.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtyaolapii.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtyqqeovny.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtdbmemjmt.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtoocoujzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrpgawyf.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtysnbjmoe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtsrjpmhuj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwhitbtb.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtcvoxqylh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtilpegldg.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gttxiifahn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtlcdtmwrt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtnrtlcqmu.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gtrppvfrfk.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtoecuoprw.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtkqemkaun.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwquntzqi.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gtmfthevkp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gtvzolzpnb.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtytizdjga.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gtwqouzgwf.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtwwsmejsj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtzidpazjf.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtrfwpwjzi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gtnmrxmlht.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtuawfjhih.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtmlsbyghx.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gthlcglkli.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gtvfagthxl.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gtnikebcbg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gtpzulvicx.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtymzrsmfh.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtuwmqmraj.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtsjbzcefl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtuhdpjipv.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtqruiiaaw.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtheixhuhy.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtyxjkhxny.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtcwdjyzjk.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gthbmjuqli.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtbsikhsjb.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtlbnunmwu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtcitjesoe.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtcyfhvtox.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtqlucebmm.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gthxxnqxhm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtbulorbez.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqstxpvvl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtjigfijlm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtsukywplx.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtuwjwtfqw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtnnkbqfao.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtmulsyuui.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gtrjretbdo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtwmhomtzx.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtfhdyvdhw.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtqismvath.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtdybzfdtq.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtkjrkbrnp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtsxeridva.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtymlfssaz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtfszmoqxh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtwswthtcb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtefrbdqaq.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtxbnvhlzw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtegeiqotx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtnhamaqcy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtnvgrnnvl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gtfmulvhle.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtmsuihjac.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gtwbekeinc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtdatslhhx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcgfiejk.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtpzzepfqo.html


<!-- 参考信息 -->