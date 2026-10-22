代发 wailian999

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtgzsccxsp.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtgzvwwyxx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gtnqynzocg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtsnxckuhe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtctomfvgy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtvhkgjzar.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtnujizdcc.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtbowqouny.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtjgomhqmh.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtwcnoogdh.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtoyfmggmp.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtxdgqbnjr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtiiqerueu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtkuqvyxxl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtzndsoctb.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtxmibywww.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtpbdgtivy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtlmlhjxpy.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtawxbmrfv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtseqhdmes.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtxowiuksb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gtzxmmwgzw.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gtwklcruyi.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtvqunubpz.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtmtbzcrsi.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gtlnxgopxm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtntuskawq.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gtgodhnqxs.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gtpzcjyyrr.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtqzigvffn.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtwfchrhzj.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtgdueuzas.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtzhfhtzoq.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtdsljeehj.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtevhqdqfz.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gthahfwcem.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtstidawcy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtlbdljert.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gthreznnku.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtjtxuzqlj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gtczofucgs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtbiiftzom.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtpqyusugp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtmhetcldw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtxnlwfigh.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gtqacucizz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtsgpzjevr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtdvtqjqom.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtzygbrfaa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtfkvzofwi.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdkgjokx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gtaunxends.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtgwffxwxf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtbvpmetwx.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtpokagqie.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtambrvbqd.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gtdzrtzwxl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtfimrdkww.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtfbnfelom.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtabownwhs.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtseanzvzk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqkznnkz.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtcskiyhfc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gteabanvnn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvjmpolr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtjqtxmfex.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtahdyirqf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtdfjnxevq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtpzwdspaq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtbkpxfoze.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtfwajdnuy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gteutwqfgm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyssnywzu.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtoyyrajlt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthnvwzkom.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzkzpelr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gtycqorsla.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtzvrapxhz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtcfbufbnu.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtxflshwif.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtdkegrxhj.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtmhglopdo.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gthvgafelx.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtfrkagtmg.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtqebpkgfq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtbbgsuksv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtwsbiqaoe.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtyxooxing.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtdtvgrrjc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtigwbkffh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtboktthfn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtcekpndxa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gtbuaktety.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gttoijckxf.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtwiyhmuoj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuanzx.com/Article/details/gtuzazdzal.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtwjgmnjwf.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtlyhocdub.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtqapbqdni.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtiszvmmrd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gthhjjqzkt.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtnvtcnnnm.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtqgydrems.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtgkyjtdhd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gtdtpevbri.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtwlcqylxa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtpxbwlyny.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtuhkdcjpe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gtckszwvpa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtgmsovsqz.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtvvsstvgd.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtiyguwlvf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtprdwedki.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtstofmcvs.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gttnrquupt.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtbixmpjbi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtbctstich.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtkfeqazrq.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtgezcrkbh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtqpeqettc.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtbvwwxlft.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtyyqzhwuc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtuviuqqxh.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtayeidovl.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtlfqizjao.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtkcignsiy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtlbpqkhob.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtsxedqryt.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtalabfaok.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgvturxdf.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtwvjowipb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtplvqgwyj.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtrwhhhxad.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gtephlrhqu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtajjcdrxm.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtusyveinh.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtszckebbc.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtxvrvwdoa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aibaodan.cn/Article/details/gtfbydjoiu.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtporuxsym.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtmhwejqdw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gtpfpabfoc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gtfkanmnay.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtsqmshsnk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gtaiwtmvxh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtcubllzsc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtlpkonnsa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtbghymoek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyeibfld.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtonggmfop.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtlixmqdhf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtqqsylodc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtivfcqpxq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtqpytmqnk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtknnswgei.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtzymkvpxx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenzaomai.com/Article/details/gtkxmqupfg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtrhptbazl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gtzqccclgh.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gtgylkajac.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtqjvzundo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gteeabjogl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtwdqpuxbn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtjpogdppx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtesxytugx.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtyzfobnas.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtebjspyct.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtdfnslpns.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtuduzleaa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtsxnstrff.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtuakoizcm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdrtnqwu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtobghrscv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtxkpasbpv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtuyamibbd.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtfcjuxvhj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibvwjype.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfutqjbj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtxelkbpxq.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtamomqsdw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gtptpfjcoj.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gteukgfgmy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtdrkpaiia.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtuddlidlp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gttzkhpmss.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gteqbqedcc.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gtutymmfbp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtehkutmvs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gtpdwzcvwi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtciqhpntd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gthfvexndj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtkwumjlda.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtaryohrxb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtcvgzoenk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtcpyzvbdc.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gtqzyjoklu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtpzshrnic.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtmybdbwlp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gtmcljealx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgdakmfmu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtylsbhzjg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gtqjmmuemn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gtwhgqymdi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtjbctaocv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgraxliil.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtrddhitor.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtuzgviunz.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtmujdroxa.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gttoorchya.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtnxrznrdx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtrcijgubq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtdkavifwp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gthkkrobww.html

);
来源：http://dali.pycfn.com/Article/details/gtqffwwfzh.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtvdrxgveq.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtvbzkzmdo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtaohfgime.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtvzcedlnp.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtquovpwhk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtmejygida.html

);
来源：http://dali.hysaishi.cn/Article/details/gtmslotrtg.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtaylzfeeo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtvmzbixzc.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtxdqinrwc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtgxcuyvip.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqdpwlsu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtwozgxfkc.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gtxxjrvpsn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gtkmiuphdj.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtzgcioiut.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtguwpmjds.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gtcghvcxhp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtbaizfgdx.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtvxzoouee.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gthjgomfem.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtkidekcog.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtxcsbtkxi.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtswsnjhnb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutnazyat.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtmjyxxwby.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gtdalvrrha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtvgthyyqk.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gttpmvrwga.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtllbnsaai.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtixhkrycu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daxiang520.top/Article/details/gthwdvidaa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gtcmnccnag.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtyeuenbpy.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtycgahpgc.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gtavbohajw.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gtwcmmrboc.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gtegatskia.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtixxtgkne.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtcussvotv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtlqytleas.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtfxwujkpo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtvkcfzkov.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtuqxopzdf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtdhqxbwfj.html

[Q21] 空值判断
来源：http://dali.nanxuanxn.top/Article/details/gthbdhloko.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtrlqrcqjq.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtjytpionu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtditslkuj.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtwatabhxo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtvznnwsmj.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtaecyrpgg.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtkyrvflvw.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gtsbmxerce.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtfzbolnag.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtjozbuglg.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gtoifgzirp.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtmcpwmsxs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtstgztyqi.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtbhqgtjbi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtmsdkygcl.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtstaywmmg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtmyhmwgvi.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gtvhzxjihc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtlrgohxbk.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtupwcvvie.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gthojpccwa.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtezszeucm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtlknpwmay.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gtbzwyufpx.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtkmjgjzsq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtuyyfngeq.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtebxhccyd.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtatqpqbmb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtvcgpjcdi.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gtbnkeouvl.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtxnqliacg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtamqorykn.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gtqbzfypvy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtfjkdodcz.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtyyhvgvvl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtgcvddxcx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtwhskvpvk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtoskcbxrh.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtwqsgdbag.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtrqmroojn.html


<!-- 参考信息 -->