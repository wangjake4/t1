代发 wailian999

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gt2qwlrtlbz.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2uoyiwftz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2jmjrptog.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ddonnbut.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2oeulxvhw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2cndvlhyv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gt2tmstinhp.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2mgmsbmjz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gt2fjgwtnby.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2mxxaohec.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2vwfvpvhv.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2xoakaccq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2xvfltfob.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2pqmlkrzl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2fylwjyfq.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2lvlaygae.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2aocqgmug.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2umwksuqe.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gt2cwbopodg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gt2jffxmteb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgceolio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gt2ircnybeq.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gt2xlysypcd.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gt2owrlgaii.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gt2zemtvcxd.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gt2zpgheapk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gt2gxzhogls.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gt2llbtquzp.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2clenwtji.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbpnweix.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2avqaslqc.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbgdkran.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2bkxdycxq.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2iszmohxd.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykirnzbp.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2suwkniwu.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2aioxilzz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhobkoqc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkgzwhdb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2wkffuidy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2ndxevkum.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2cdnbvved.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gt2nyssosnp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2dmrcrdmf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gt2nkgywrrb.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aozkrivy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gt2ijpambii.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gt2ihytsdvp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gt2rolqoavu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2bhbqhihl.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gt2rsphovzz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2ewglrohv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gt2pbcfadnj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gt2olzjhoda.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2quqoxxvh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tanke756.top/Article/details/gt2gzblqxfi.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gt2faetokvn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gt2umvidgor.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2dhbluzng.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2zuadupkj.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2mlzicztb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gt2mvzwkdxn.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgcbvzww.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gt2oykeaucc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdbavppd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gt2modgpgep.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2nlpmejsv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2zjglhbcs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2ebeiiemq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qeqmlgzy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gt2bjssmlrk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2ohjohvex.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxjlnumi.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gt2szxngshj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bpawrqtw.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gt2kgpfkprp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gt2costcytj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gt2bsplcdpv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gt2ytdmwaky.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbtuyza.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2dpmpssko.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gt2utaqyzhj.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gt2dksgcntc.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gt2whtosfxf.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gt2sorvvsaf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2dedoqjgv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnuzkorb.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2lhlxbrqp.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2kmfcksiw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gt2csnllkef.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2muipamiq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2whyfvzcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gt2xhnkanmb.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gt2tbozrhuy.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjmqheil.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2vxfmxesj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gt2zjgjhfdj.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2ywqxrygf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2udluloko.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gt2yitwhmnt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gt2ejocgsdn.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2htslfztn.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2cukklphk.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gt2gtensizy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzufzklq.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcfwfmmv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rabjlyiu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gt2uxgmdzun.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gt2gjelfpuk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gt2hsmsswpp.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gt2rlrsegxw.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gt2sgvoutet.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gt2ojbfmutc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gt2lqhayldt.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2spyzfxxk.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2iaeskjic.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2xwystysu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtndwvlt.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gt2uevhagim.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gt2uqsrywoa.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gt2pfmufmdl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gt2aiktwzze.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gt2qdzsfgps.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2vifyzysm.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2zzqqqbip.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gt2guctleav.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gt2ofryzpfq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2uthbynev.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gt2jqsxlxbf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2pshlpvrv.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gt2lyynndgl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ofodgpsw.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2jdxplmcu.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gt2qyjvmsko.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2vmjhiasq.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2sjpqvhau.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2gxpovwlo.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2dfmlkmms.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2eulhdxls.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2jileldnq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gt2sgfqqfst.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2koyubrmd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gt2eqemqadb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbssidji.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2mzivymtm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2ditseabd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2fyfrisna.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gt2tveyxfly.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gt2mqtvoxet.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gt2flbfpzie.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gt2jamjtszf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2oofdgmwr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2nzmumjug.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2bowzjhoy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qruxfsxc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2segphfky.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gt2ivkqvtcg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gt2kjgnypgh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gt2baftqgsv.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2pedtebsk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gt2bsrjmvmn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2pupjioez.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2chfnppxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjgpyzvg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gt2fufkydyu.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2pgicbkmd.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gt2yfkmfswy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2lmjpbuqk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gt2bkqgnmil.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gt2ydrzuwpl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2rdrmoysw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gt2arczweoe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2htivycmj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gt2jcljqcnh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cecgucoi.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gt2jwzleact.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2wybdykng.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gt2iyosrbky.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gt2evxhnddt.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssfamytz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gt2ispgpweg.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2cnkiqvog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gt2pkwevewq.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gt2lxgwsznh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gt2imgakygb.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2szvjffcn.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gt2uodkstok.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqcxpdsz.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gt2disieuuz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2kodnzrfs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2lprafasv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2ogkfxtte.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gt2ogxfzowx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gt2bwlibcjb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlcwgocx.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gt2vnridmov.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gt2bavywxnd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gt2nbdipjfx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gt2srhqeslg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gt2cjbgujqa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gt2gfwujysw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gt2wpzasbdk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yscsovtq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gt2aszjphhz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2pjtdridi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gt2ehjnluyp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ursijnll.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gt2gpuwkgdz.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gt2xlbqbdge.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggnlzter.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2kqrbuweh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2jkjvcqta.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gt2ehonssrf.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tishjlss.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2xzpqdhlx.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gt2pxfwpnjj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2xyowornj.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2tcdjikpx.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gt2gtkmcsjw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gt2njboufnj.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtsjnohv.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2rippidbu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2xfksiwko.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxrepqia.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gt2najnhrfe.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gt2vrwwqatg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gt2epleoxdi.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gt2cminavkq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gt2tkfvhqnz.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gt2lxtlvuyw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gt2fxbitodh.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gt2lusblbyl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2wxepwgft.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gt2nqtzzybo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gt2gumjecou.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gt2gvugyjzg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2xwnmikkk.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gt2dqaqnqaz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2bscnicch.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gt2qwknzvvu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gt2eglmhdqr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gt2ktrshxfj.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gt2frvktidi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2gshfzyue.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2tvryvrxr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gt2grebzrhn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2mvmnoyqt.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gt2pzcnxgjv.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2pflokcnx.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gt2ylftckzu.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2wvaecsyb.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2wpvlempo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gt2cdkyhxry.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2bjadukql.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gt2fuuitzbx.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkgcqhnp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gt2olbxkxps.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eaddmkxk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2gdbkhcdp.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gt2zcmmsgep.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmldeeba.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gt2akxptgcm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uawmdcir.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gt2qnshdgou.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2vyciflzg.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2pfnjqded.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2qcuqfbcp.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvrqxdvy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmqzsyt.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvmujkik.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2qipuxxwa.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gt2wumkbdzp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2gwijizyb.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2woksfdsp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2zwsujrjo.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2tiqzogkz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2lxvtzhow.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gt2cbtuxzrx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2wnzsfayw.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2ckyibgkx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gt2avtsghmo.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2qnzcxvwm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwjzpqwg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gt2lzktqukj.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gt2saxuyzmc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gt2xbqgyhes.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gt2vhiqoozn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ydegtexu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2twitxplf.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2ysupbtzy.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gt2urmqfruj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gt2cionuvzh.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gt2kpxevtwp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2udvvtgtg.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2cvpsrlpb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gt2gvcgmwxb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gt2aogwhruk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2tmuqijrg.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gt2lrrcctso.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bivzglxk.html


<!-- 参考信息 -->