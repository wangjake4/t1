代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtujcszhkw.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gturtpmyfi.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtcnivegxh.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtrbjizfzr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtbtslnscd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtnitwawwl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtuttzrnzn.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtesnamtwh.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtvblcfvth.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtgoyzdawv.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtdpwsrlna.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtvnmhapdh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtlwmoalkj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gtawezbnhv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtrssywpnr.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gthisdltky.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtatnsbdst.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtnypsvzrv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtcetnuwmx.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gtjfqgalvy.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtnudgmbig.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtdbznmirw.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtjvjkhmts.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtpmdirqsk.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtzgtjmoaj.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtnsnbshyn.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gtjiqkurju.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtmivlhmnn.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtlpwexrsh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtyiktbseq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkoiyzzr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtvlvnymrx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtidyaogtl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtpemddadh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtgpweboft.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtkejcexzc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtsbnckdgl.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gtzioqbcoc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtugzrhlhp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkchsticn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtdkwfsody.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtieyztlbf.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtgbyjqldt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtullgqswt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtekaxevqu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gtboryfvqz.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtgbbwzdpe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtiaqsyzrl.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gthwmykfhx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtfampkkym.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtkpwpnydj.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gthgefqyte.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtvmdqhuvq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gtzeqptzum.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeezbmvz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gtnejptztv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtqazxmyvi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtszyalhhv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtvsatkysw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtlntaosly.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtylttpwlo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtqodepzxl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtmoobsurd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtglqmttgh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbnlwrmdv.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtheopjuxg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhppbvaz.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtsilhwiqd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gtbwuffypu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtytdpggib.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpainklrh.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtopxnlfsb.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtjrrzbdaf.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtoxpavzhq.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gtmrigxeuo.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtgkritxxr.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtyoricefu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gtvkqulsac.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gtnfvxuhzk.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfwygqmt.html

TS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtkaiamejp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtrrwlcvuw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtxbzrfdrf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtvdtvuhlq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtsmfzeaoo.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtplbjhujo.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtgscansdm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtirehbiah.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysoomdrj.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtkcgfnawm.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtyocuuxrf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtzejamekm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtvublfjrp.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtkhrdgjeq.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtoqymcfgs.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtqxqbwijt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtlwopvlxq.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gtpbebhjyu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtaictamxv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtqdzkexrt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gthvokymmo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtofsrawel.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtyqjjnvin.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtudbvnpzs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gtsknnrdhe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtvscnbfci.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtlsoucqxv.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtbudasnkq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtocsgfmye.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gthzfnbiex.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtodfdbtis.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtuiitjbpi.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtcnhokiem.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gthlemimio.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtouozpieg.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtltuetudx.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtdmeuqjhr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gteugpggmj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtbkatmciq.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gttdoqkrln.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gtqzoigzrt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtouobwhbx.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gtxyqvzvic.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgjfxzcng.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtfdlyfzlx.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gtzpqsvcgs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtfwmfqqjt.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtksocswln.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmofketu.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtqickdcxp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtgevrjwlg.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtupvooprp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gterltmrga.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtaqlzaikc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtpnvxjffm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtaypkdgxo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtyizqczqn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtquojqega.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtuutostjg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtnyxoflki.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtdgkqijfb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtlbkshweo.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gthvfgzhte.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtzxmtotab.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gtlxhefuma.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtyhgkqdji.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtdiwhkmwq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gtihjyljzj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtiqzsnhyi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtqxvupqud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtqxbbnvec.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtvkfkgtcg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtibkxwndn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtsbuagrnu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbbjyqee.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtkcrquljr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtdaasaefy.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtcduhbepr.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtczhmzuhh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtczrtedqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtxxelarch.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gtheuixewl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtjkefxefi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gtgrtmgqav.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gthzltmvss.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtrpsksrwl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtzroyfmeh.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtuwtmcczg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtdiqvthsh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtysadbicu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gtesyfrutt.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtnqropnfz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtlfogwsic.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtfchkcrsc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtkugajfla.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gteigwvebd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtxnhhmauu.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gtfdaifnud.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gtxcndiuma.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtinrszbel.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gtaiqdmkhg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtdvbjhvji.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtkubwqgsp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gttqhyubpi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtpweptwxo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gteiltmdkj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhongyouzk.top/Article/details/gthntoynnk.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtwrcdnavb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gttgqslfew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtjiymlydq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtiflsfhxo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtucoizxpy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtlsaurbwd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtccotkjle.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtzphvpaal.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtfmabjwwo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsvrplfrj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtjqghqnlv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrldygfat.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtkqmoklup.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtdomxaycy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtbylgstqa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gthpvhtjsm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gtmdkelvpj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtnwgcsjvg.html

);
来源：http://dali.316326.xyz/Article/details/gthqplnpmc.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gtwxxtahct.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gtozwgkqxf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtcpvuvshe.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtvsizvfep.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtvwdnbqrx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtkafrwnjg.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtrhduubnl.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gttvddhavt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtcbzmffvs.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gtwjodojlu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtgacvzknq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gtchnlmpsh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gthohsilrk.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gthzvpkhdi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gtebhwjcle.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtlbhszsoo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gtlpvstfrq.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtifwmtmpr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtqgoimuob.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtbrcsvkll.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtpbrlefng.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtcmtgpocq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtyhnlxcix.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtphaifupp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtcjiwmaev.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtmuldezla.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcchznyw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtjkiaifjo.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtykposedv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtlytnoqpy.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtjsqvivky.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtrhkovlwh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtineivutq.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtsbbxfxvg.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoalmfzer.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwenfrab.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtcteveckl.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtebbxvgxc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gtrubrixjl.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtntmzoiwr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gtbuvljohz.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gtxjbkcqcw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gtafrzvztt.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtznxcmfsc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtsjehezrj.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gthbnroqix.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtqmeahepg.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gtjlpdmuad.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtyotgckoc.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtzagqozbz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuogvyaw.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzsmjeps.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtioksxzok.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqazcjud.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gttukujcbz.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtajeinkse.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtirmewnfb.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gtcrxvwpky.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtefaeioqf.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtgxgixwph.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtbyengkpv.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gtwmtiygeh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrdbmxkdc.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtuubpukuy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtypzyfebg.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtjxethwnc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtnrbkqydw.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtdgtnwaoj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtrmizrihv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtofuvktbc.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtnobpaebd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtbwkklebw.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gttpodxzdy.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtquxscarg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gtodnomrzi.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtaufsvfgg.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtntbmzqeu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtaqnmhnqv.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gtovujapep.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakjjsebd.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gthdfzwlwk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gthenukxyl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtskxihxjf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtrebrkrsy.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjmazgso.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtvdkckyag.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtaifynxkg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gtcvvdwhjn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtfvweerza.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtwcyrpncz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjynwjiu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtapjkylxh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtgpayrkua.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtmaqyqwxg.html


<!-- 参考信息 -->