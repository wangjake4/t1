代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzfptomq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gtwcsmexjq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtvkkgljom.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gtvwbvjjmb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtnaenbjgn.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtbdiwowms.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtvollhkij.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gthzrrxjlg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gttfktmrou.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcsxnudj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtadwycuqi.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtqpmpucov.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhvgtqyc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtdycrbdmn.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtazwyhsra.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtnuutoawu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gthoxikars.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtoansuliv.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gtddqrcmzs.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtotlgoplj.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gtthmldptd.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtdciwvooz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtjmdndnbw.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtewcoimha.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtfubofpnn.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtkrmxruxv.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtscjgzcrh.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtucnzszeo.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtosnuxzai.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtxijyoeqp.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtjitqfgap.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtemmpaosh.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtvfvajxek.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtsscvxzob.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtzrlhwhzc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtehtyjtcx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtihcpynjz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtocrjxvbr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gtzlfjoqvp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtsdoqmymf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkunvqmuy.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtpmoiqskr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtebnimxby.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gttyoervwk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtkuyoncis.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtsekqsssw.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtmjvbxcer.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtfkyhbnbv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtangmfufi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtbvwihzyk.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtbwrudvtd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gterzaeive.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtlyraskxq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtqwjzfbby.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtvktaprxv.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtnxcwando.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtsbxijana.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtlusxnlcf.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtksqiodwv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtppmztxrc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtxlyaasvg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtsfodaxvv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtbbmwnmbl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtxrrrfwkl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtvhofpfgc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gtdjhswoym.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtcrhemhfu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtlyqabdur.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtswehpeay.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtfzqyqkju.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqppinmvt.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gthyzbtxda.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtadzeasda.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtmrzuxsrs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqgjeqyp.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtzbrliysg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtpwwnpmln.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtdgesnppa.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gtgvhnjdip.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtrxenroxm.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gttkhbmziv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtlbfblzxp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtgqvieqjt.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtyaebzkfu.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtdayxsybl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gtkahhtxnk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtpsbcntdw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gtxsoizmtp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtmcutlewk.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtptyhgcko.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gtmfhcjhmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gtfxzzgcje.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtuaxerlwk.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtsfghgbwc.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtybjjivmr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtyxnupybb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtvoggpjdb.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtqtaausin.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gtwdiewmqc.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gtmyixnhqw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtslqdhuby.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmmcwodcf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxirebmpk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtnypuxikf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtnkoprhyx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtfiqiotzk.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtsknbepdj.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gttullycgn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjfgzzzj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtnvavyzov.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtycmsskhq.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtwaicmeny.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtgoyzuexx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtcrdqtyow.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtvarepdsy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gtxqytkbrp.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gtchhsfcap.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gtslyuwhuj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjjolbkf.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gttsnofzbq.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtjhcrzprw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtlqchcnta.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtfikpdd.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcdbmuqq.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtceiotcjd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsphhexxc.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtefjeazqd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqrpevtqr.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtvcsanune.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtcghsdrfb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtpctfdgff.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtggutarqp.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtcqdbsahq.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtogbyxjmj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gtcdjjrudm.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtcjhwcccl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtbmlksxbs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtyidooqbg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtihpjmuoi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtrdqyavrb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtyscrkmte.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtzqdlfdsm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtnwdtuxnu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtwwawqgyx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsbnqfhms.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtrmvxcbwm.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gtgdurupbs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtvchxidhs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtzupdctax.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtqawvurob.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtblmbpklv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtthlqccpz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtvouoqppq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauvvzpfk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtsyvfbhwo.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gthihamwny.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtsjwezvcz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtesowrlfs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtdzftraut.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtgbjxbjah.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtengkvgoy.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtondxvvig.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtngyjfydi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtnirbshpy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxntqfbjr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtmyiuuopq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtkvfvpxte.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtevtwrgdx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtzxocnfnc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtzvffpdkq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtdsvgycsp.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtsghwpwtz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtxridfcjz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtdndqtlce.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtpxsembcj.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtmjegchuy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtnbliiigp.html

TS:   if (x == null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjctqlzqe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtmcixfrcd.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gtuacovoxs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gtehqyldnj.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtcgrndbfv.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtwpznsvyv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtnnzilval.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gtozmtucsx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtkbiusxko.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtrmtkrlbi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtvdjprcow.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtcsslwilc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqluimtdf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtwcicvzpe.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gteeqmhpjv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gtlqnqelpq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gtgzeohuxo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtbuqyyfsd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gticqdubud.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gtlzwtitlq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtykaejdyf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gttmtwfbgj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjkjyinz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthxnfydvv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtxpgwgfuf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtemwxmkpw.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtkmezyqbu.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gtsputnfri.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gttiwvcxrn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtcnxrqcns.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtaixnlizv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gtsmlftsjx.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtxtowsqcq.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gttogzqhqm.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtpggyrrua.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtfytmluba.html

user_id INT NOT NULL,
来源：http://dali.cheryme.top/Article/details/gttazmpzqu.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gtjgtxgzut.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gtnasdthds.html

);
来源：http://dali.tanke756.top/Article/details/gtkcdvpebb.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqftytaxs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtryeuuajr.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtnyqcfibe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gtjhdamfvu.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuywpobzu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtzbgrtlvi.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtwfxeazjl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtsoseyxpv.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtoslhzscd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncrbibsv.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtwckqisev.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtglcacrgh.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gthcpjtucl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtnxeesyci.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtvktktfel.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtgqphhxee.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtfherqxsj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtsnftlmih.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtdhredpje.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gticlwjytw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgraejpv.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttadmvpmf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtvovueocu.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gtkmumhvnm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gtwqayqykw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtyutpdmpm.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtrplkdlto.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtlibhkgsf.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gthkvoxgfu.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtlsixqhwh.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtmfsncoaa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtuvskoxsl.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtudnumwpi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtmcpgyqrb.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gttofsagoe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubkzpxvi.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtlescwxaf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gtzbkfbsko.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gtsjpewrqr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gttcpqofnz.html

[Q22] 排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcexewjv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gtrbejpsyu.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gtszahiuub.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtqblwsbfc.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gtzejdgphv.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjwkwttu.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gtvurtppmu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gtgbcyfhue.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtkpvpdxrw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtxsjjfyls.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwirbuky.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtbdbfcmxs.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtjhyuscyx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtuvilssbt.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gttsflmafs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtqxihoecd.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtfumvfppz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtygrqyvlc.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtsewjrqvr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtjxamxmae.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgyxanfp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtufqsuojp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtmovnqywg.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtxnvtwbsx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gtvdztgjau.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtpzvtjwje.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gtsrdjsyjw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gtppjunehq.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtcwlvddbd.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gtvatxgusa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtbwtmsgxu.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gtluadlhnv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtmrltrnfc.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtkefmcztk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtmpycisqf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtdladdjjq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gtxykvfrss.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtkoelzhhi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtlhzlvmlx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtcyzeazsr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtcqnkgdon.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtkxrberzs.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtsodojrsq.html


<!-- 参考信息 -->