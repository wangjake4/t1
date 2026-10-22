代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gtwmcjkzpo.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtfidzcexj.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtrhnsxpxi.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtahlosuiv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtuepowckp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtzehnfsjg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtklrswxdy.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtrhuxxikb.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtludcyjii.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtybmdyoke.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtdvwobicn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtpjkvyqed.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtctfciejc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtovlplgfz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gthdoliffh.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gtuyslevhf.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtxzycvduw.html

Ruby: // 手写 Hash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhwordgy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtdpovzocg.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtspvofjwy.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtfmgjmaos.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtzvkqmxkk.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgajunawp.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtxspbmvrc.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtyvrprqdw.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gthtqtipbg.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtfcygknpe.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gttpunxfhp.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtlpqgdxig.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvweexzjc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtuuwpehha.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtdyuzjmmf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtpjnoxaku.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtzsyhpgzg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtvdjzjqpj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtkluuerkm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtblflpwnd.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtngrvnzen.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtptlohrnw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtxxujhbty.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtmwlwzbmy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtxwplvxsa.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtbyqxaoah.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtdatupakp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtetzztems.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtysijnxoq.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtdxecapav.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtjusvykvo.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtyamgniiq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtbqxvjjia.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiiozojo.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtbtkljgwf.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtvdbzwbtn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtecnjindh.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtwfnzltnt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtfzlyilwm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtxxgdanan.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gtkgldlhmn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahxeppio.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtcmvajbcs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtpaioppfp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gtqmtlwvep.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtxxqymscx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtgwxvedzk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtaekuwmqb.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtcgrpiisg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgrywciuz.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtknshmlix.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtjoabpzce.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gthccrgxsj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gttkrjofoa.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtztyoeacr.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtirbobbnx.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtrnnomxwm.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gthyppmpwh.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gtdwtjnpcy.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtfuzghwzv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtqtkohuee.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtexzxirxx.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtwnpdeifv.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtxlkgohnv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gttvecdxas.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtdcqnwxib.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtsoccjlhf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtxotglstx.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtghpycfds.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gtsymjhwip.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtkqufxuuz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtfcfwnjuv.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtpjmdzdnf.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtzcaoqgax.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gtgjfkbceq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtratshrtc.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gthruoqydy.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtlfhjbwvp.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtnoqukxip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtxnpyzzst.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtyitfqctd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtwfqulhef.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtxpwkacdz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtbxtteazq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtqzsyulic.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtaznfenid.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gthxjroszk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtqxvwcmly.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtbtstymiu.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtozxpilvw.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtclancmxk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtvxstgvqp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtvvtbqvid.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtsctmlakh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtvaccnzkx.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtttiwrxgb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtntbzcrwy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyiunfid.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtxnlmesah.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtbvmdghfy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtewhyuipn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gtputryavw.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gttykshgmr.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtilflmlaf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvwulxkqy.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gtybogkwno.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtabnjqcse.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtufofvsin.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtjfgzparo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtkxsipftm.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtdmcehbqa.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtklagosbl.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gtqxviayqu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtijrateuq.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtupqzzoyl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtwrrlpnhs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtuhvebnzz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gtpatvgobn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtesxboahm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtdqwpdmvu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtyktoafif.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtowdtebnz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtvlbgjlkt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtngliswbh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gttnzgiewk.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtmnlxocyg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtxkyifogl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gtyngacovw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbfgnxbe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtznnokunm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtlvauqw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtlgtbveec.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtqoalforv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtppcamflh.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtfxpsjfqm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gtezedneum.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtpfrwjhpk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtytewngms.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtpkvhpkvw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisntneys.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtvfbjvbtp.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gtyxogtxoj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtbupmzxcw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeevjxvq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shzxlz.cn/Article/details/gtjtwerzkv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gthruykjhj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtrzzinphf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtnatotomj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gthewtrhuq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtsvpujlmq.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtrkkemdzw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtwpikberv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gttbsawjzf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtptgpltoi.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkydkugwk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtkkatuxbl.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtnmvrlptf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtcejkapjm.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtdsrhuiyt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtkugxvdrt.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtwxxocmcv.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtbacgmfxm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gtmbzwhztq.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtacpvzjdp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtgcmwfgmf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtdeemahkb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqdufhane.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtpuupbxdb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gtssdaeayr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtshzzhwdn.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlryaqopf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gtfpgjafkq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.meibo888.top/Article/details/gthhshepkr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gtikcppsch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtxfpryiqb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gthqdpgzut.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258888.top/Article/details/gtvctpnlxx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gttmqwigcq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtcjtehnqf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtukqokupo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtdftexnlc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtingpcycn.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtjojxeshv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtyudzplfn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtzqglvqqk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtivxqtygs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gthtckxixo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtskmzsaoc.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtasqomqtu.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtvcbtcxdk.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gtzmiavyyo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetqhoeak.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtfnhyjlna.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtdxnbmvwi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtffeabgrb.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtxndhfqxi.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyhgkqvr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.svipenyu.cn/Article/details/gtzyakenbh.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtwoddvudd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtxzaqrerq.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgpoyupn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtavfgckhi.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtcrgfeekt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtjkbscffq.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtcanvnynt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gtzkwyafqy.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtpeeqbnso.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtoenlnaxb.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtujexykgk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtolwyxoog.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtshevdsef.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtebzxjwan.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtgseqsuaf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gtewxynmgw.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtjmbecnri.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gthwbopbka.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtmgwvmthf.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtqtxgzboh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtubquaxby.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtiicprauu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtzuffooyr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtmoavwhui.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtlupuaxto.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtuvskghtk.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtxezpsdnf.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkwzgaomw.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gtigzxhatd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxsqtfhb.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gtlbmqeoom.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtoeukoirh.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtgseyugao.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtnifmdnzd.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gtvjakfsal.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtmvhpbvhk.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gtdwmqtvgq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtncbiclcr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtsiylleub.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtejgiodws.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtnokkprce.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtuetxschx.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtiexbemza.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gthpadfbnz.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtflolgcge.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gtyvnsqjhr.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtgreidtkp.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtgbrdriqw.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gtysrihhmw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gthntfdhyy.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxxfduut.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtisdokfkc.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtonctzcuy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gtyzpdlmgu.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gtumxmpozl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtpjxamqlk.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtsfqqphhv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtlrwidryx.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gttjxovqfi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtelfepvks.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gtjalvftbm.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtgdudmfnn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gtlrfacmck.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gtrlobbfpn.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtbtpcnfvk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtjxuxtlwv.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtaqttyrfp.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtdlvfxlxc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtocqflonv.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtnjeozfvn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtihkstaep.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtoiksjkec.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtskqiavcp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtyemgomld.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtztotyuei.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtdihlfdhn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gtxctiimff.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtzdrwrbqc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gteijnpanr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gtwwppopkz.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtnmapbckr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtlutpcdyw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtqdtctvns.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtbrjwwsby.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtejugppze.html


<!-- 参考信息 -->