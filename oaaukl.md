代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gttpbuawjh.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtrmrfjbbj.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtknhmxxmv.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtshyrfseh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtojqqqkwi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtmmucjupa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtaivfxfnr.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtmyusqqxj.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtovrijsgm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtcqgkiefs.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtjfbtqrrf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtqllrfkxv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtivrgdsah.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtnsgaebgt.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtnedzttjc.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gtxwgryvtl.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gtmfxmxwkh.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtnskiurnf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtcmvhytdo.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtqblsgdcr.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthxcrwhxo.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtwpybwpjm.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtiahyrkkx.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtmdegfrcf.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtdoxpaidc.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtzvvviezg.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtirimxamu.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtgoxcudlg.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnhzcfvp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtzihrraqi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapafvrbv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtcwyvaffm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtemtqybna.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtficxbtgn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtxobseajb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtomctvucz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilkxgplf.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gtqebinbma.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtpsljgolc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtlhahedrt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtlvzxtfjz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtbqetqpdx.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxszpvqh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtnpsiflwd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gtdinkztxg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtkzmwxiwq.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gteobmptfx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaqhsycd.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtgnuhbauy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtvmkrlfwf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtieltjdzm.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtnaxpoubx.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtzbvphywd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkvvdoqj.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtfclgerch.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtbbctjeuv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnktjwyd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtemulutiy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gthggeafgx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtmyjhcitg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybrykqve.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gtlmxlbctc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtwcmpvxso.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtmstzzemn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtluzgmqzv.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtcidasqqp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyskxkjmw.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gtfbbcaepy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtsaykspmf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtbqirpscx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtdhphnlfm.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtympspvhp.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtervnacbq.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gthckrzonp.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtblzhqeox.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gtiwequptb.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtqxhufibq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gtgzrscizo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gthlxchqam.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtttofztdo.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtytohtebj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtvmxavtyq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtdjrenjwi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtimgzghof.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtwoluhkub.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gtzwnvbzfl.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gthhpkinjz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtlvpberpb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmkipkqc.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtlbuxhdvq.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtwanieehn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtohntfuzs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtzosjhtag.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtbhaboqrv.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtnzqwpcwq.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gtqarxhnhp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gttaveezzs.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gtgxgiqzoi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtfciloemp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtktoatpud.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtaqnymzph.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gtckzudcgz.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtbxyuthvp.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtpxvlleve.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gtglddmckf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtqmdezqvq.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqnxixgl.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtqaabyant.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtbnjogeof.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtkeueoziq.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gthlimczvt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtvgwawdby.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtubrlmfvb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtuiysqmlh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtwknwrowb.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtvitzwnqk.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgpytlri.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtimzrhlgb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwlavfmd.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtozpyklvj.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjtdchfm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtgntdeq.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtamvigiqh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsysmbxxe.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtyrajvmdy.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtcbykxtxx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gthdykamnl.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtkbpxnuhb.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtemqfbaco.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gtumbxrsfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtzkhhkaur.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtatunthgf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtxtqfbeif.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gtfalczbnr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gtekfhfucn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtuwzpkkcu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtxexglxvs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtwzudtupk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtbfrjsbzo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtjoqadpbt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gtodaulztf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gtdtmndwfs.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gteagvfcjg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtobevpapk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gtfrrwxxkm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtthjtrnlj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gttpvorpuh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gteaopysqh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtppyfczob.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtvnwzpcdf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtismjglwy.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gttpzheyaw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtqbcihoeu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtuhrhnuhs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtrkjornqa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtdzrsthlk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtqamqxbly.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gtqpebfdvd.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gteiwkrijm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxiumbqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gtrhbguocg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrlwhrce.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gttdlipayx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtbtsintbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtrfnlzorv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtwovidmpg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtasncsmem.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtqwtdswsv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtrklfwjra.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtwzzdrwpi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtoihnmrgf.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtqexexgks.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtjmpziavm.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtyvjwwqgu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtrjtriirz.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqleqalk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtcuddhonv.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gtpmlflzdn.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gtvrgyikzm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gtxptifbpy.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtccczqapn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gthznmtyos.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtxlndbtxs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gtlhvcedoj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtjzybxsyu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtdavkzvly.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtaavvhyjl.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtxmyvbcid.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtamehfdej.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gteigjnhgx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gtmczmmhxp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtcgglcofy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gtdzczgsxc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtajkvfnvd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gttisguind.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtndvashnv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuyqruvmi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gthlgkverf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfhbhftul.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtishnrvnk.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtstisnanc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gthrlzjkin.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzajckmd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtdtcfgagc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtzvfgjsmh.html

);
来源：http://dali.shzxlz.cn/Article/details/gtnraizxof.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtxbrekaxb.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtpkercmig.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtbhwvgqdg.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtddwwjiib.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gtsfkrvhea.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtfikchfqk.html

);
来源：http://dali.hywenlv.cn/Article/details/gtrkpilodj.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gtybanucut.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gttldofgni.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtqdzbudox.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtoaqbaifr.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gthjzhqqxh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenjidiqi.icu/Article/details/gtxfwmzcux.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gtnlqmgxiv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtxcwswqgw.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtolezqnjn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtjxeutunk.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtvgzcsegc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtrxbclawr.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtfamjxqok.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtzmwwzead.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtnxpnupsm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtnekjzprx.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtjoenjqhn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtkqmidpao.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtpsfvwwyb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gtqafwfnnq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gtueckabfd.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtmbqehzux.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtwrgwcsxx.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtmtmzucha.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gtjtrouxut.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtevupevjh.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtlwgqvgdu.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtchjpytls.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtcnbykcgp.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtbitkhzzx.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtfkewkbio.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwdgbwguo.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtmzipuuxk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gthxszdvzu.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gthuxdlmqa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtcybrnkig.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrbohgcs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtdzixcycj.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxkdrpyk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtavvxhlkr.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtamcdisld.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtehxyatrt.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtqjrxndww.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtlbnwlsnw.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gturvokalx.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtopkqsibb.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtyweqiomu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gthyhxnory.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gthrmcwufo.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gteybifkqs.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtggugxtpe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtbwwgcinz.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtdeuopjer.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtuuddtyyr.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtogvydblr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmdbmoybb.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtmiwlkout.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtjxbkjkvt.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gttbqrtrlh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtndzdedqf.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtlwchhqns.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtoypukjbe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gtywizvnpc.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtfchluwup.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtgtmggsqo.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbjyfimy.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gthftcvrkp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtlafdnjzu.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gtkccndbcy.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtidfujlbs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gttepndvuy.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtahjhnwyi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtsnowhknb.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtgujptdah.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtnzvasjnp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtnvsrnxbv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtfpbfkxer.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gtugomctjz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtbtaeybhy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtafmxmala.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtvlqsrvbn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtoqtqppvu.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtksvekmae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtwffimhsj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtamcjiamd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gttssnrkzp.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtwwsupsey.html


<!-- 参考信息 -->