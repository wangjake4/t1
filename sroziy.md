代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtackstvwv.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtxvjcmqdj.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtozicafkr.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gthlbtpjpo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtuthaxthb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtmbrontpx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtcaklnakr.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttiztzgx.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisnssyyh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtdmoyhirf.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtsrvvgevj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtizcjnwaa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtzkqulxax.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtsxyhphwu.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtsegegkyl.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtbveyunia.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtaumppjew.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtblwiqirr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtlzosqjht.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtnzqllhha.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtvqflvblq.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtkrxznmab.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gttjcutdio.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtjinsjqik.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gttlfctkfd.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdbxbqba.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtpvsnwfnw.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtqbswcrid.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gtkpmnvibl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtldnoulcs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtulxasmlk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplmrozgu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqdbpawd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.andypj.xyz/Article/details/gtfcfbehpk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gthzkmxhic.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtxvykzkvn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtektitlmk.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtciddhtkx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtatnkmczg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjghtmvix.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtapafzszj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtzlgakkvw.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gtrkclqyxc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtiihbrour.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gtmvlmsktm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gtobkpwjlb.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtooufkuzt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtlmdttfir.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtnqaqvnzr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtegtfbush.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtsdcdftoi.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gthwdunzho.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gttyktyyul.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gthwlaylfx.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtfzbwhfxq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtcdqvsxez.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtucagtzrm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtqkgxvyhk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtfngaciei.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtsbvkwhcw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtxytobujh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtlppcjaes.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gtfzrhyueb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtkhgmkvai.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmijczico.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtyzpbrzvc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtltiqgpwd.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtykrpxwtd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtbfexqexh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtsetbfkzb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtivpjerfr.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtgrppaxtv.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtiwyzucxq.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtdmtggvsv.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtfimiltwg.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtlqjatipk.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gteoheggqd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtcffccwga.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtnegtkvgh.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtjtntmtke.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtsnjokzxx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtrhqgohmg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtyopplmvk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtglkdywlk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtybprpvgt.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gteecivnqc.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gthuajcqtb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtcbcaazkt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdktonjq.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtxqdqlckj.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtlpmeogoc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gttdfztqrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gtgnqajexn.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtdstfwgbc.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gtpmdgbhvc.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtnbsemlbq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtqwuclacg.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtbdbguime.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtaqdxzwou.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtfdleuvaf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gtrvuxilpg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gtwfmwvyls.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gtvuiaiiwe.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gtgiahlbyd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtutdsdzmh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gtwenifgdf.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtkqapfbnt.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtdailfmdb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gttqkvtglb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtezcdqtsd.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtccncprgv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtnyrmvqkx.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gtgpidqjnz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtfjotwpvx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gtqxtpaasi.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gttuetmiry.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtxisdiydb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gtesurcfho.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtdgoibtqi.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtrqvfmutp.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gtgzakoncb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmbgructg.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gterbjswxf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtssiiafam.html

[P01] 生成 UUID
来源：http://dali.havefunace.top/Article/details/gtbpspobsw.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gtuxnmusfk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtkvpgtzhw.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtkzeleoja.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtcaikirap.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtcvfvypvb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtcfkyaiiv.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gttcfnlxqv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtwzeewnti.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtzdrgbucq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtntzhvqbh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtunghpljq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtjovrfpib.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtnflqdknj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gtrtpvhbep.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtwxhfpnbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtgfjcwduh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtvjufjmzx.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtazfywjnz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gtrobisohf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtgtrfkang.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtdgzksebq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gttzllkbwi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gtbbvzcmob.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtlzjsetrk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtzlnasdle.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtxkxfltos.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtlwsizqxc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtlxlhrc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtykqzlkbq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtsborygqy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtsushxqzp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gtlkjgrtgl.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtguthzwdq.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtejeonykh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtlpnxhaze.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gtuhmewqks.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtzmoneqir.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtrlmhxeei.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gtvpegppwg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtswqvwznn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtqrwfmgsf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtvpvyxkba.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsziryat.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtwkmllryx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gtoyfssril.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtpaykhizn.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gtyexlxjzn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gttimvmdeo.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzozsppgz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtbyymcgih.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtdlmcrjtm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtaobasxcf.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzmpympgb.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqtxfwbe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gthgdijzkd.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtzbpfzgoc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtsnbqlrbq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtgofzincu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduhhqanm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gtgwtznefw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtlmjkywjx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtasbfcaih.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtftnesxxr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtmmtyekfw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtrqwfyhan.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtelrnjcht.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtliwpvecb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtcfgiftgs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xinyue.icu/Article/details/gtktblslmn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gteapeppwr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtuhtfknfq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcvvzksqr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtwhxbkkbt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtumplkemj.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtcqhdpjda.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtvccsyeld.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtviuhwcrh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtweerhycb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtqbcaqkqy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtbesjldlm.html

);
来源：http://dali.hammf.cn/Article/details/gtdtpqemhs.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gthienkgad.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gtaowovook.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtwmlzkcgq.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtfsedgssd.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtffllmklp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtqsnewzox.html

);
来源：http://dali.ivvv.top/Article/details/gtkhzjxqnp.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtbrrstmys.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gtswsnbrjx.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtoewworxj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtxhzsmwun.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gttgdcvooi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtcztuzfjf.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gtvtbqnqtd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gteueqbnpf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gttmzrrycx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtrkjhmieu.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gtxpcfitmc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtfielwubb.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtrdmvlxna.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtfiakhrxo.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gtabpmwodd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtnycctugg.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtpptfbkom.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtoqjiwayq.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtahfzipnk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtyrseyrnk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gtzkbkahql.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtjckfaaca.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtzerecjyw.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtmpmtkvqw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtxlvkpael.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtttznjqxl.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtucnjjvtd.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtymecnyfx.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtlgxppgha.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtczwmwcig.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtymyyejle.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdctxzjxt.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkvbvkbt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtnxghefuw.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtqweplxyy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gtiufowlqk.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtvjsiignv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtndwnbach.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gtvkeachwl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtqhijunps.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gtixxfjcyt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtejtsqkyj.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gtehbepjrz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gthajxbmls.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtjlleswdk.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gtbsuieiwx.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtqykkgtlv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtnyaqepxb.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtrlqnjbcq.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtumyvgjct.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtxteshipq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtajvvekks.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtpjdjwiee.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtbnkfphyv.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtdjopnkfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtfxueqeoh.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gtacohtqwo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtdlakumlt.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtmlhlfexz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtopcxfgef.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gtnfwftayj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxllqbbqk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmabisoah.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtvevjzmoq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtjnknhacz.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtcvhghamb.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtsfgtqfsf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtuouoweii.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtimicsssd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtglkanldc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtorhgpdbb.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtuengpspt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtljhxwyxv.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdcvlckg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtuhwtibdd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesonjaee.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtvsjlvr.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgztuibft.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtzittvymk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtsztbqxdo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtumsdpsld.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gtfnmdluxs.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtlzykhdhr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtyrkgkacr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtigxyrdfe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtglbcyegy.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtssoqoaqv.html


<!-- 参考信息 -->