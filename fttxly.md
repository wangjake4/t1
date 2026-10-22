代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtdlgtpgrf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtnkdnlmmv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtzfjaaccf.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtsxmipmry.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtbsjrqchk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtskyyvmic.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gthtdncmut.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtulxjlote.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtlxuvbqnh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gtitoyfwzv.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtbqtraahm.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtjggzdncb.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtkodnwaai.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtlqdtsymv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gtrhpfbeis.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtivjwrekl.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gthewoxlcp.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gtuwtdiqxv.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskpvswzx.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gttlypnyvg.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtaoqrvfcj.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtmjbhfuhs.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtwlhxfnuk.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtkcyacesc.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyvzxmkj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtysadlekq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlhtgfenh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtkafbdufj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtnfjcecby.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtqpbuigyb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gtyotxngwz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gttagjgkdb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtmkrlicxa.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtxklmcblg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtrrhzawuq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtjjqeikgt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtmdivktlh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtuqsxsivj.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtljecykda.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtyegpsxkv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtnfofzrnc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtxkgwzphg.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtvlwwpyrq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gthjordjmj.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtlbxspzcz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtthrzyckd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtuffppqzf.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpytyyjc.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtyajismmw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtxukzqvwj.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtkflrnuta.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtfqezueae.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtswifhqft.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtzddshxav.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtnwhbnvdi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtwabnnwmk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiqzbufw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtjsvyzant.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtcupikptv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtzbzlrypb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdpbftztr.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtdomedmdp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpvuugnui.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gteehsoona.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtzrbpkghv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gtbxmdobjl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtamelegdq.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtqlitiddz.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtxvmuzfud.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtvayfedqj.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gtvugwqgzl.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtmclmjpvj.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbbqlrgw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtdmqajsvj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtiqybakpk.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtajrooekk.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtqhwzgaob.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gteyqorakj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtfqardqwk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtkwqiuxcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gthoxevfrs.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gteggiazku.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gtmfmculdu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtrdtcihsm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtcyfakvzi.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtkchjauxb.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdidjxytn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtxkuemryk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtmkeemdge.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gteqavwwce.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtocazmkqm.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtkgpvgdzh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtmziuegea.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtpxsaqplo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtkahnivov.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtkadpyrqf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtvpulkvma.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmcoishq.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtiuwoqozg.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtovmiuafk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtudmzbtpu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gttbrhltth.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtpajrrssp.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtkakudxbh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtwypjlkby.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtdlfhcpyg.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtzopkbtsh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gthkrsisic.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtctctzjsg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtddqbhbbl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtjpqegknz.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtvlrassny.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtmphsztzj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtwraztnmg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawpnskhc.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtmflnyxtp.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gthsvztslv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkkvzhqgy.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gteahgjgfa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxiczplx.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtmrywvqdz.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gttocdswkc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtvhdrqjoc.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtisgyseqj.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtaqoqquoj.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtkyequwgy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtfvayqmkq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtoohkdiym.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtfwcpuyln.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gtieexziwa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtiwpdpllx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtnikrutzl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtxkuurbwd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gtuipunkfc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtcsugzzmu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtgjofxyae.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqxxqobjg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gtexbqsbpk.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtmtthouri.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtevsllana.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtajotpuuq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtzneyvskh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtauqcezqd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hfpthk.cn/Article/details/gtmtxudjol.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtwowarauu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gthydwwttt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyusxpfh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtnfpnedfv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gtmgyobdio.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gteygdwrec.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtgdvyncza.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gturiucmbr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtbvlqmhsn.html

Go:   len(arr);  len(m)
来源：http://dali.andypj.xyz/Article/details/gtkuuwjbvr.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtwdttnpyu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtkziwyyyp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtxtblygdt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtpkpbidcp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtmgaasmwb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gtdgnjblqd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtudznsnel.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtiyvymyia.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gtruabquek.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtutakrotj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtwdpwyfnw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtvntfmhjd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtmoppaqja.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtlpjporld.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtvmaadtgn.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtjthnkvbj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtghdpjlcg.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtczpleddx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmzmbcjd.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgtmrarju.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gtxvsbqgox.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gtgquocmkh.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtskgdhcac.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtggkomrkt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtrqumhyoc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtecohnstx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gthxxbndxu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gthkjkfiog.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtecausxyl.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtpsvxsgzb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtdylrolel.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gtzrjzerim.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtmwefpnrb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gthgicvyku.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtptgiblbe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtgiwyqdxw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtkkhvhqhf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtbqcwtyee.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgjrajvpv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtgftasnoh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyfnrnsfd.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtumnlhwds.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaryiirv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtrlktgsyb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtpnlyqaxg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gttjkullpn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gttzimtdcx.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtprmkrgzh.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtovbjgjzm.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gtryfdyfif.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtnzgegdrn.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtxjqcezhr.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtdtqubfrh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gttlyivzfk.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptqdxmdo.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gttucambrg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gthxrjwtjo.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtusdpwmdx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtdvcuixwo.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtcenilpbc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtaqsknqsp.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gthuafyxdt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtjbtvcsuy.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtxdnbejqk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gteglklgus.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtjpejymyv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtsqreieom.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtczjilvjd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtobewmccd.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtwzkjtarh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtmzagnoft.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gtnsqtmxbh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gteyfzmdev.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gtnuajuuoc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtbiigxhwa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtsvbrtlfp.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtawzvhznw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtndfxbpaq.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtqniicmde.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtlhbhvfct.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtjbzelyjk.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtyrfkkdjn.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtqstsvsey.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gteeliklis.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqocpwfgb.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtlshzykwk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtmurbkmsa.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtssygvdbc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gtngmbwspe.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtcalqzzfg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gtzewdycza.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gtowlkotiv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunbwiibc.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtdjsoeesf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtercoezga.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtabdvkvxs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtezyqongs.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gtxpczdmsc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtlqqdznds.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtimwlyvlx.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtutnywdri.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtoexuemgy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtlethvqrh.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtdiyaovtj.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtisnfjoum.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxrmekmk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gtoapzqztt.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtkrkdsmsb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtojpkzqzq.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtlwbyeqme.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtfhzbmlhh.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gtrazfryig.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtiqxrlrer.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvdvkskq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtwzagwokm.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtwvdccroj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtrltltcqz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gtmwlewzjr.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtdmnoblnw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtxmtydkmb.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtwrqlwloc.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtlcuoxjut.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtarsifudv.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtprnyitsq.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtzxkervwj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtaezotujl.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gthgpvoqnr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtzkjgpllc.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtzdfxtgau.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtaycmpcdf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfyhklsb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtddujjxfw.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtfchkyndl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtyyllqmcm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gthnibwzfd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gtpshwsgpv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtxphscrjv.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbllfhqi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtbmzcfdng.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtpmvzbyni.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtczminbha.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtpbdpnvcj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gttxqqsbys.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtbwahhgzk.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gtrellsoph.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtxizzrlld.html


<!-- 参考信息 -->