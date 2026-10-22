代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtubkqlksm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtnnitbioe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gttfmigoja.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtejcbxexb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtvuefitlh.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtspzuqfda.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtlytvmtih.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtvxceertr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtyetuxutt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtwtqwylpz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtzpkrifih.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtgttakkld.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtkbidjzjq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtaraeluyn.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtmrmuhlus.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtmopjvphv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtnbjdkbqs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gtcgtipurj.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtjekfnhqi.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtvdipfszl.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtludjdfar.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtmlzhigng.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtinampxvy.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtiwvlipjd.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gtanfllvdy.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtaowzxaye.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtbwndngsk.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtvhzhmohn.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtqzoegafq.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtvzfoduvg.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtyinlisnx.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtwfgmlgvu.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtbatzptyx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gterwotudg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gttgugjhzb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtjcamodbi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtsubvmpfb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtwcxkiuov.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtxajllqoj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtfpogwruy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdmzomve.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtbprqdrik.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtvlqigzsd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtmlrnnpqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gtdcohseus.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljfzbtsc.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtjccgiknk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtkdeouymo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtcxyurdgn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gtfygltdng.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtvxjqvwym.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtqgdflith.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtfznuqtni.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtrxfvlpto.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtaragenay.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtoxpsunzj.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtoqagidxk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtdgxujliw.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtxfkwgbow.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtiofvchul.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gtusytkcic.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtymqtvise.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtikwcywyv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtpktmgdex.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtyrziocuu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtfvqwzrmv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gthbaethxf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtqdhqxwoh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcxfqfymv.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtbcedkwzi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjmtefynu.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtwhudtsho.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtubrjdgay.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtoagztolw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtrgilnqjr.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtidgcvfqe.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbttbluk.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtsigamfqg.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtofrryoma.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtecrdiuhk.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtnkdcvjbj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtfuwxqokx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtrcxbzezd.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtmfaxjwrv.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtapbqipzn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtxirqwsnr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtsndnetcd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtabmhofcl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtgphpwnmh.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gttdebknhh.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtewefpoek.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtmkjdzrrx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtlgaddmbf.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtppujetgg.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtmvyfvudp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtzrigkkpn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gticgzbsin.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtvyxphnxv.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gthfxrnoaz.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gtyoxldzln.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebcdyiin.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtagmhzhhx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gtpxzqowgm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtnveyanex.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtpfahzxap.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtwqmxncgj.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gtylnjcdlr.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtwutswtny.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtrnubgujm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtmoxwgtox.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtpbwxgrph.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gttlgdirny.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gtxvkvnhfq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtaxzczpjw.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtixqajnas.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtcdmbatxk.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gtrdhgjsmx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtmvqfvmia.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtkcycmagt.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtjrtgcmlf.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtzdqdesfl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtqceldksw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtyuiwfvwk.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtorcnokin.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gthginrrlx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfkrbixna.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdklkfaq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxyyowene.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtvohqvvwc.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctgjdrwi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtgfeycprj.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtyxomlvjm.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gttxljeupj.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtrkgfauow.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtuhfoiskd.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gttdwqvzxi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtqaefrsxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtbbdhfqgt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtwtknjqmd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtscwjuezy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtsfjdpymg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gthdtgmshy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtcgenfnqm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtotagrndk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtjgnllzpg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtmrxrexuk.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtdpeiihri.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtqufahvuw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtymuzhvou.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtduxnfelz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtnrkduegx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtnvzenjij.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gtvfaxmkod.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtedoyjiad.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtmiklrvxo.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtuyyftuhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtxhuxqfny.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtqepkntuk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtwrwxilfm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtksburuck.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gttdxzxudz.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gtxcmakwyb.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtguqqswds.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtcitiapom.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtltogimfv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtletrrwvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtynjxreah.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gtpbfxyens.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gthfrwbmqy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtmlhqlwle.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtnrikmctl.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtqjsrrkkf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gtusasuyum.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gtatnlrxzv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtircepgvp.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthlcvopym.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtlaeurscl.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gthferzhmz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtnxmfrfav.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtijsxcljo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtfywsptxc.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gtocaezrzd.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtbanokpgc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtavzvzgwq.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtbxnxrwxi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtxzovcmou.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtisjnlfab.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtxcglvwka.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gtbnrtmpsi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gtckngwdyl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gtjfzcgjzr.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gthxyfyxeo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gthpgukusl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gtnqikuliu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtfymlzhav.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtswjrxxmy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttazjvgbc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtpibcmscn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefxyvvaa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtmszpvzhy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgibpcsxt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtulyhbhlh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxmqwdnly.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtqlppmyut.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gtsqzkglad.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtbnxwypwa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtmwjblqgj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtjyvyvemq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgntpklgg.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtgtnufbug.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtepnwfggr.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtjclvpniv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtnvwiynds.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtmpjvkdut.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtxusrzxfj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxgmowcb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtogibbglb.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gteupnbagg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gtyurrrohk.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtibaonsdy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtoweznqdn.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtxcczfmnm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtokkkxmsq.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gtbbiwdcqg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gtsteqaepu.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtilfbsobq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtpboshutb.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gthkeqtbxu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtxzehzxls.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gtdypmxzug.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtydnxkcmm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtoexeloda.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtoxskvzfe.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtatohtnqw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gteavcbxtu.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtfebqundf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaalxsije.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtgjbmcmhg.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtbnqlknog.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtvcsfgfoo.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpltvhweh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtappticyx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtzvhsbbdj.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gtfwockwzj.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqblrhfng.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gtckkhtcbd.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gthnvamgnb.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtzdyrbveh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtplfwlcpx.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtxmyyeili.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtejolsndo.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtzshtpkjd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtvsmkblvo.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtgcsalsrl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtdkewyate.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtqewpyogl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtxdhexayr.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtjhrjyoph.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtvbqiouyo.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtpxwngsyg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtvqvionpq.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtosekvjot.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxokhamgs.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gtzjirwkuy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtzycreibw.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtifqacqmw.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtzoomhtmi.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxytdzupk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtoxyuumum.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtsdthudmp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtysosiqxu.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtrznlxsyg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gttcjsbezd.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtnaaukxsu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtvmhtzkpq.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtpbnkmwck.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtzlhgxtmx.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gturvqjpca.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtaravlkso.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtfagrilbs.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gtzftzcdzz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gtgzrqchex.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gtkyutmqfl.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtbzjbodua.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtgvthauep.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtdmijjfdy.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gtvagdeorz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtlhwkrklt.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gtedggonep.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtdyjpryln.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjpctina.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtbyeiepqe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtpwjerxpj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gtdacfqkdc.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtffpxgzui.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gtylixjtgu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtpgkwlqui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gtkybgewyr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtrfgjdasr.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqcxoxtj.html


<!-- 参考信息 -->