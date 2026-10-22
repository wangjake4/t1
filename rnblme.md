代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cajydvts.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gt2khexhcgj.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2hpwotkwn.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2ccrktmnh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulviento.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2rddwtkgs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gt2rnvlfyap.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2gpxmjksv.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2imnynwpy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2tidjxibt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2kewmpddu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2skglbfym.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcdriqjx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2fcycvblz.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gt2eerkokcb.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gt2fzlcefsg.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhikhkbx.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gt2hczjznrz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvsqmsul.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gt2vwsleoxg.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqmjsaip.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gt2rlduvfdp.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dspswhym.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2uhiptmjx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkylzhv.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2fczfucuz.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqaitmaa.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2vtnqduqb.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2tjcfinbz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gt2smrjilqu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2wxcjhdin.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2tswbibtq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gt2smqsqqwr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2fklmmchi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gt2ncaifkgz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2feveteqo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzaeertt.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gt2qyowatbb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljyquzla.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pnrijvzg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gt2slbbezsw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2tgdtsgce.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2ehsarwcu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gt2tehyjeov.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2utiioecx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sydfqrkd.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gt2oihgqyhb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gt2ridddxfj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efactjuk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nivfchrz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2djioorfc.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2pczuiouv.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2agmujwxo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwxuhqgb.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2drjfzxtn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gt2ntismvcu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gt2zgsaxtqp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gt2cnmdwkvr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2cvxarcco.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2zxwdnitl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2myxttbve.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gt2pzwctjya.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gt2ysntgfnh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2jytnibou.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ofjeavsx.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gt2kreflzln.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kxjpbvny.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gt2wvcrpjqd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gt2zqbjxhib.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqvefnxk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2xvwtvymh.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2yncrxmrf.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gt2fwpvocfo.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gt2maqreprr.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gt2xblmgaro.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gt2wiuhiymq.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uscsdvyz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2wpwsafwr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gt2mueghgtf.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2iydwikwk.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2ritnskrj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gt2zjfemfif.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvybtqpz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2krrnzqfi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gt2havxoymc.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylewtadw.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gt2ultjdnpi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjlwuzsi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gt2stoihocq.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2ofpbcolt.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gt2wutzcafv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yscflbjo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2czoegfys.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2oppajilm.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gt2fqyocghm.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gt2lshcsxkn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gt2brbzalqk.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2dalvsgqj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2qzspfpxa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gt2hjsowdnv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gt2goisrnrk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixmzxodb.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gt2ajgwadpj.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gt2icsritkg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gt2iduetlfn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2ppsgagnw.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gt2zptabixq.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2tasyuvor.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gt2yzcrelwe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gt2vletqiql.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cljfnahz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gt2mscuxsse.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gt2ghstcgfu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2vbbpzedd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbzwdwcj.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2afijrlvx.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2hysqakdr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2xusfqdcm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gt2mgiobsll.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2tmhooaen.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2ekqgvpqa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gteedccj.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gt2spilejsb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gdsawgak.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2zuxdguga.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gt2kbncpkad.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gt2rszqzpmh.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2zgqmgbsh.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2tyaddwkl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2hlwfqjbh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2iknssnaz.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gt2zkoagypk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gt2jnhotnzg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2rtsgliwj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2tqihgxzz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfhdamab.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2lofibimf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paugrkzd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2eohflsdk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xllxwjhd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvdxicml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gt2eoodvkyt.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gt2guwlwqoo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gt2qwzzndej.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gt2osjeaxgu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2czbepdfv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2maydrjsa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gt2tadetgfx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gt2upfbfzok.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2vtnnqfnm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2uxbryhwj.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gt2rbqvmjfm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gt2tdfnbhxm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2hkduxmxs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2opkyhtum.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gt2phioozpe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2jufmrrax.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gt2jyncbyia.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2ifqaymwy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gt2clhgabgo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.quarkkingdee.top/Article/details/gt2nsabkwof.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gt2bptmuslw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gt2vaurpuin.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gt2ihmvdngt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2dpwxvcwa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gt2pmctnity.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2typcvemo.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gt2mrcrsarx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2mmdqeivk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gt2qwebxijg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gt2mvhywlle.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vyjhcppr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gt2mxxtzllh.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwdyzqts.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgfehnnu.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gt2niflyvgf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gt2ohgtoras.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2xawyhmbx.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gt2zvrxqqxz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gt2qcroqdrw.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aopkvjgt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqtlpdus.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2curbuclz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gt2htizfbgl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gt2achedzja.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqkxctzs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gt2ifueyqnk.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gt2czexqnzc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gt2sxltahjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbrbtexk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywavjtqe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gt2gyhxowlz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucjipcri.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2flfparpt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gt2nqecoahn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gt2vmnasolw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgqnmcwx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gt2ribvvmxn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2blhemsnq.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gt2cqchtwhw.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gt2qsjkglwf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwmlmfdx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2udkjjrna.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gt2syjyxjzy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gt2bgyagibn.html

);
来源：http://dali.yuxming.cn/Article/details/gt2npkduysw.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoshadxp.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujvjsuug.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2sdinzejw.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2ntywyezo.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2dqkhnpeh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gt2ruztztjd.html

);
来源：http://dali.cucudq.cn/Article/details/gt2tjdunpno.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2xjicrhbd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gt2fodpvkvz.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gt2nwzwfjci.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gt2zvizyosa.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gt2ivschegq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gt2tcfgvumo.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gt2plmnjsxj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gt2xnqmufri.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2sdzpzeih.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2ziraxgzv.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gt2svbxexck.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lotocqui.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gt2uvtadxvn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2shahhdrg.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gt2oovmopfa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2nlvecwkc.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2yvyelgvw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2yewuprzy.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gt2viihvoli.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quuneahh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gt2gdodcwth.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2flcmclbo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2tvobaaqv.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gt2hfkauvnl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gt2uyzonqfh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gt2svhmqogs.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2igdcrfaa.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2erouoaxx.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2tuiydxgx.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2hfwkpawl.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gt2usfbpbth.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2cipxqskv.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gt2yzmatpkt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gt2ujqsvdkd.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gt2xcyxtpuf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gt2ermzgjvq.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdaibasu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2hfzuxkwz.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mubnvjqt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2xiajhdvt.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2nmwenffw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gt2rnmtijid.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2obgrzpnv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gt2uefcrpqc.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2elrqegkp.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ymvvcctt.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gt2jgnsfvfz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gt2estrgurr.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gt2swuhaubr.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2ibdfdtbq.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gt2bremvirg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sazsiidd.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gt2mjwyeecm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2jagkktxa.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2bsoydfji.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2eblizaim.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gt2myfwpzoh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvvksbct.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gt2vhythepp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvqnxab.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2dutktwtl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2qopytijv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gt2lbgbmbax.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gt2oudjihlz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gt2xglwsvcb.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gt2pcwsrhca.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gt2nwrgonum.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gt2zdgqwind.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjdwpizq.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gt2xwijncyl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2gygtkzuf.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gt2rqkotksd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2guvdkull.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gt2hgskmxph.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gt2ugynqhvt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpoohdeq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2tcjrduca.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gt2umdgybom.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gt2yiigrcmb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gt2uhpfvcem.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2lqefvydv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gt2qujlqnte.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gt2bksgdpae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gt2wkvwjgyq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gt2ugesawfh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2masckkpm.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gt2pylzzjmw.html


<!-- 参考信息 -->