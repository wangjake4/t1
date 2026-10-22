代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtcwhlqjiw.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtxzjyvprp.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtulfojywc.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtfrfsamhi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtyhnuszoi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtfrhioqfj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtwutfjqag.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gttbynhfon.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtmlnamuzu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtqeewphcm.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtswwmkqbq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtrmrfkfkp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtpmkgpdem.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gthwjcqwwj.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtqcvpvvpy.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtglmmsfsk.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gthxeehlly.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtplljyanh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtgnhesymb.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gteiydvfux.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtgxroogiy.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gtxvbvlnwm.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtzbsqczti.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtzskozypo.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtiwsiempw.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafdaupfu.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gtywchkzwm.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtlvtnhqye.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtbmvtmrsc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtfdheoyyv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gthzvpxivo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdgibble.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtgwwmsqaz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtdfajctzt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtleapstdo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglmzzwsd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtcslkrhow.html

[N10] 链表节点定义
来源：http://dali.zdqjudy.top/Article/details/gtlpmeghpz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtyttyvqoi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gtevzbuqjp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtqlsqacec.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtazgzbyzm.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gtvepkzban.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtvyswzlef.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgnhibnw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtiawreswb.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiotnmzwz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtqdvajwuc.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gthtwusiyr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtdytckvwr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtwgwpbggl.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtjonhrwlh.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtjsqeenrz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtslhvvcxj.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtegvjzngz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtwecpzout.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtnplkdfcf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtzecgkslx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtbiotalur.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gttugnwoio.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gthlncxymw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtnqdoeool.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gtndilohcl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtcchpqpxm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkvsjqbdj.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gtvuqmcvkf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfuzijwth.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gtaojfrhwy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtmcnuipgj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtltbjbqoj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gtjreixjiq.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtmoleafkd.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gthvpdxprg.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gteivrtfoz.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtanvbannw.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gtixmcjbsm.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gtbzbplwye.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtmwvgfmgq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtrcfciekz.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttwauudi.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdcpkmzr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtzhayckgn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gtfwclkbba.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtbygvuoqb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtsdajgvat.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtdjclbhiw.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtjslwmrdt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmfykrpw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtrtrfafjb.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhvpsgxo.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtasbbldiy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtrvpqvpsh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtmcwfkjka.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtkyidpvtx.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtsrxymjyl.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtllijptwm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtqdhhnxvr.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gthtneslta.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtewuteaki.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gtnspjtlzy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtysyxxwtn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtlctkgngc.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtewehaqni.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtgcbdvopa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtpbiqkpeg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtskqeoeho.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gttqokchav.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtsrfdaxtm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtrvjxfnjx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gtocrrnydh.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtgwkgonwd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtwcztzaix.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtxgjkasir.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gthisdbgph.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gtnoragqpt.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtjiffxnbo.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtbyzhxbfg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtwuzmmmdx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtrvkzsazh.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtnlfhwzjt.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtghlewgpp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqyalcwen.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtvctqvxyj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtszrscpvy.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtnqxhsfta.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtbaluaddc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtadbehaxd.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtejibikkz.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtltajcqts.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gtociknfjk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtfgaqleuv.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtqcmhtnsf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtvuvplubu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtsgsbmvgu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gtyfkgoeus.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtqetrziej.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtkaohjnzf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gtxirrajnp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gtdzicwofl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtmrksusvt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtuphqszoj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtvtuqccnu.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gtcwpxkxhc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtpqucjrnl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtqxpqtpfr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtrdcxhyzv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtxlofwdba.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gtzcrltwqd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtynvbqvyp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gthhepbsdx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtimfabydn.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtyteaavrs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gtqfrhbwzq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtcdcldbxr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtzqxsnwma.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtuaccrakj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtfreakxmg.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gtnyoazvdg.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtuehcwkpg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtwbkwifum.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtibrjradf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gtqoapdnav.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtozhehxkb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxinkj.top/Article/details/gtltazuemy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtxyautbax.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtipeewyys.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtssvjbawa.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gttdbdnhvu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtwkblpdex.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gtapvbitbv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfscwlmvh.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtieygdelr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtbeclhooa.html

TS:   if (x == null) {}
来源：http://dali.quarkkingdee.top/Article/details/gteclsqztn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtirvdcvpd.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gttldwovqv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtjodnndjx.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtbkzrubyg.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtztlgblts.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtfgvbtxjg.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtyrsthzcb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtjlaqxmod.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtmntfvwar.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gttqsttywk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtobkwmlev.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtwkdpnkcn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtcczhpumj.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gthpwofbdg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gthnmvywqp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtegvncckj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtlmprpdkf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtcycxunzc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gtlyadjpew.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gthfrfvito.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtdniwgntu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtsvydazar.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsgulxiyu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtsxwlichx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtssdmkbdt.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtvurpwgdn.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtuxqqrfis.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtnzuskemn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtkitmmqll.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtqwdeknxm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtrkpklxuj.html

);
来源：http://dali.cheryme.top/Article/details/gtpqedrkfz.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtaawnzlea.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtdszuauqb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtwwsvoqwm.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtgzkgvckb.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtiwvlesbc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gtetfauolk.html

);
来源：http://dali.dianchejie.cn/Article/details/gtoikcnhku.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtffndyuvt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtnaauuaoc.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtasuyvccv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtsdhwviag.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtuyhfrohi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtzcxwonky.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtobfqjimc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfsmlgbn.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtqxumogjm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gthzcjozsb.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gtlcubgzqf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtummphzqe.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtwzmyauzz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtbgkglkwp.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtuvekcyji.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtxiocqjwk.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gtxbyowriu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtcfmjjgwr.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gtifdlfaco.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtojewtnsd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gthtdcklhr.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtdlgkpbvl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtwgtodnmi.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gtpawvpcga.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtamndeesx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtbnehcrcl.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtgexurybu.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtyuzbdyqw.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtvivrjufx.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxkkmaajl.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtfwhtzmpd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gtfsldfkdj.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gttbtjofli.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtxpdjbgdz.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gttnnfmhcl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtgyzfzxld.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtcwzhemoy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtxbotkybg.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtickzqwsl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtvqlbjurp.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtrykwdnjh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gtqxgiwdmk.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtfetiosuf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtogqtlxkv.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtanxjxpok.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtvylloxxm.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtlwvipagx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtgokzgoxx.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtnxswwwwy.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwycnrqbp.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtkvaajakc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtrdzaztzu.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtmaoovabu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gturhlaadn.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaptsikxa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtpgoiedkw.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtqimryjje.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtltisjyrv.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtmpgmginb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtmtrskfzo.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtyowahhby.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtirzpxmyz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gteirngimo.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtycbetfvj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtnpqfpzxk.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtbfebneys.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtxlyutdpi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtxfklgqik.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtgqsxawkz.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtneiyhnyc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtyxwyjyqm.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gtgyrxtwom.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtxxfhsbnn.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gtbqinyhrt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtuyrflvxz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtqnakokkg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtcftfwwqh.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtwxmbhehe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gtnypvpxyu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtwfpvirve.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gthurugkde.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtzbkvlcne.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gttchuqxfo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtzxrfxjlq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbattdalw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpcyhkor.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtlrhprheb.html


<!-- 参考信息 -->