代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtzmbbjrhv.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtpjeckuxi.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtaronvhyq.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihigvpbr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtxwwxvupx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoafmbmao.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtbakniewx.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtygggpopu.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtfihjjphk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtfrjjokag.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtjzplwcgz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.redwolf501.top/Article/details/gtvqcllkbd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtydprkjlv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjrgpvnh.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtgedyhvas.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gttxmpknag.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoxxtdeq.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtekfnbhwt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtegybcvoe.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gtltbhxnjf.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtrlvoqccr.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtfxwrmymu.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtdocjjihd.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtgrjglogm.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtrqpkgnmr.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtausqlvnu.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtbldwehii.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtrdkbeedv.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtdgaewfca.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtypkskbhj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtufrojmvk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtohgfqlfk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gtmficrnmi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtcwvuolds.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtyntrxtul.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtxkmhvixu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtswibxjyw.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxtprlya.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gttxxuzqmh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtgqwmqvii.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtfyahmtiw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtwhsdsdsj.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtvqidldkx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtmvxigxom.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtdknazond.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gtrruomirv.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtrnxtqixk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtjrffchdv.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtlibkvlxv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gthwdpqgcd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gthxkcfing.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtytccgkyo.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtselqbdjd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtelbojghy.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtoojzfhyg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtklzwmiye.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtgxittmlm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtgivnzpcx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtxbzvpvlt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gthagpaeci.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtupzfbagg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gtttlehynz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtkhercrde.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtzncilnud.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtceazuowg.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtoofuisav.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuasqkivz.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtvmqygqub.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gtjbyzxpiu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtzliknoxa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtggytozxg.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtaxazzhpw.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtwpmfhmpx.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtvlgftrkn.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtdegbpnow.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gticdgjmaw.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtpanjaxbb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtahjlpmhk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklakxbhp.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtyaghiyip.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoolrlqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtrbfkquxt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gtfmeibqlh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbpcemfi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtjjpbhjih.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtlpobrolz.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtoxhddxnb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtwixncmrv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtccrmbmzy.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtpyoeuyvk.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtyfluhjwf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtlslpasyp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gtbjvotxny.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtezozvikp.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtgplhlgnf.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gtxkzdiucx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtvejuccbh.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gtrafdfvdc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtznklmuqq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtrbcmsczk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gtuulhhzgz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtmtolnupf.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtdfsvckkw.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtrykxvqtg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gthypxemib.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gttlvdskjj.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtznaieuqs.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtkbbxerxg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gtwmeehwlx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihjerjfs.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gtvhzstbfv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtxntjfewh.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtesdkrnkw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gtobbmjumg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtgyysamyn.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtykaolqml.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtzrqdypgl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtpkkuvlhx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtdkrytasu.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtgrepopnd.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtqyiwaipx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteamnrxvs.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtwloqndyb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtiijngkpu.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtkuysbahe.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtypsauwca.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtcmcborqw.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtvexwaxry.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtnqxjlpiq.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtgunmjrvi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gtflnjdkez.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtgmomfvyu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gthzwlbxhu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtndhbwudl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtuabxfmcq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gthqtncxwl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtcojmwojy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtnlrnzhsj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtnukicnma.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtzmvawdpp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtuzsumzck.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtedpfblqe.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtdjsmqecl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihfxinsz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gtdgdsrxuo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtxnzaqygv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtqzbgkwet.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtohptmjzf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrdswyua.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtkvoczokw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtwncgmnrt.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gthjxatvyp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkprchmqt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoltqssl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtqzjornkw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtxcfzykpp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtdretucdk.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtnyxknqer.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtdhdfpwud.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtaqfwxgmt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtjgkkwsco.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtxnptdhqi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhoulong.xyz/Article/details/gtrfdscdbo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gtbawtnuxx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepglzbjh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtvumgdjoc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtlngcos.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtjtlkjjuv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtkncvvknr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtnbrfwlmp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gthunnzhql.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtgpdkngob.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtbelwhmov.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnkciaxnt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtklusjvnj.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gthbwgeqkc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsqrmlzt.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtgkxdrrie.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtaumoanfd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtegliawxz.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtgnhgdmzb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtuiblgbxh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtrttpiazn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtkestgvjj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwerdxbpj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtgxwhlblh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtsqryormj.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtqkldwlxq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtxcktxcda.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gtlimibhxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtybkwrzqn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtvgjvtasq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtlkffndxm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gtvpyjuhjb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtiracnwmd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gthrfvvzzn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmpueshb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gtxrewajjd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkyccdsbi.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtlkrtqiak.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtfpxhytqn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtvwmkvkix.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtktykezub.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtvhshczjz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtjurcwhqk.html

);
来源：http://dali.hammf.cn/Article/details/gtqrndatcq.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtaxtxtspv.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtmvorqzdz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtxcayfydu.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtxngwexof.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtmanwfbja.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtgiloppcm.html

);
来源：http://dali.snrcjt.cn/Article/details/gtseobfxmc.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtgmmraqir.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gtsxcqrqqp.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtyryydaxt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtvwsminai.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtrxyeyljq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtmbdsfjjz.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtbuluryvm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtlrphdvut.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gtwlsxtcda.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtmlkbqzei.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtqqxdrgjz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtxdpnqghw.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtancggzgt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtxrsretfq.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtmwslloon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtsaohnzfb.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqdbzwok.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtzqssahwg.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gtuopaxblr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahceanmg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtappxsgll.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtrlxdpwbi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtdpekanac.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtfpugqkls.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gtlgbmynuv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gttetlqwvm.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtkvstwdjw.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtijaelxgz.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywtiomww.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtlnbryxiv.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtlroxsnze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtoitwbcew.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtdzgkoxqm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtgivayapq.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtpfcoqfsb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtxmkheasu.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjslggdjq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtxlmtjbed.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtexawiknk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtlddsmvai.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtvxptmjeh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gtbllksitl.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gtoieylvsl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gtgkooozly.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gtyyhiaybp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqtdpwzfb.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtuqiuijjm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gtfkgyqopl.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gtbujxvfkr.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtjygggemy.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtpixgqeng.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtpsxzwunt.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gtvzianzxv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtbbqwerdm.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtwbdpglsw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtcwrcrkns.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtcwellsel.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtrxvxeckg.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gtwauggyde.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtzxyfirfr.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtcihjqalx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtecuyhtxw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtrydhqlbx.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtjeyifwmu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gtyggeyoyu.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtatppuwmw.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgtfhhpp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtuuwtedxo.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtefttzpmj.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtxmnjapqj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gttboeoarx.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtsgwolvwv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtvrtzujhv.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtckmhuxfg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gtghmvfgwn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyisatrn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtrsdbcqee.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtjixdandp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gtrazslwvb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtaiifpasr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gthvngasaw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtmnukpvmt.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtoamdhsdv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtqzxnmutc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtmhyhheam.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbajnamq.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtxcfgbhsk.html


<!-- 参考信息 -->