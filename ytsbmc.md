代发 wailian999

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gt2pfrathel.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2ghalqqav.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gt2xizxcjja.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gt2pdvdlfeh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2ipvuwojw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gt2zcclrplv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gt2lyuattgu.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gt2kscjkgfz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljqgmmvy.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gt2yxgmjxvd.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2lnjvkomi.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2hxlfkxzw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqyjhvdi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2uxkyrwek.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gt2vvbdrtnc.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gt2ggccixpr.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2xacyoqum.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2onnrvjcg.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrqdqojr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gt2egaqqore.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2rjalqswi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gt2alktoqjz.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gt2tvomjciz.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2wscciwba.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gt2qjwnmyel.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gt2eethonpx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gt2fpwbgmsp.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gt2wyrswxwv.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gt2ueqokhcj.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2gkoforra.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2egcmbnqz.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2reojsxac.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrixmzfj.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2ujppqdec.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gt2uxwlmwdp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rktnlssp.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2dilculoq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gt2udurxjsm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxeawcgt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2iwljdtnu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xahzcyha.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2kvetomxp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gt2iuwjgxmg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2vatwnxth.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2tnlnqvsx.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gt2xbnqbhmy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gt2ztfodrot.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gt2bklhrjvx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gt2qmuhbkir.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2thxzryon.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2awtynphy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2agsqbuzo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cevbluxu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gt2ddcrokyj.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gt2mhkckjij.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gt2mofoyggc.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gt2tunyohle.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2lgnkbpam.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2jfiassno.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2vegausqp.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2rkcfyzwp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csmwxtlc.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2fgxxozxq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gt2lurwxswz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2cfmbcvdq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gt2xpqziyte.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2hgrhebap.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2tarwcrhr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2kzzqrmus.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvplnqzi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bynxkcet.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gt2hjoktlhp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2hotlrvow.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gt2proldevu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2lorlyylw.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2wrypoybp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikdoazih.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gt2pvtbjisd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gt2kygayfsz.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2kfjssijp.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gt2kusohefu.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gt2mxqtqkqb.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gt2eytzqyvs.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gt2ydazgtnd.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2tqhrtxtx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gt2fveebcau.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkmsnqgt.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2fzzsbyem.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gt2uhfkyfvz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2gylsztvo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2hvaumomc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2iadzygow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gt2seitrhme.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmmkgzz.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gt2dooxpjjk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gt2zzclgapm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2myhsavuu.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2wencfslj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmprrdbc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gt2hdxsievm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tojeitap.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gt2pmanfcsb.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohiafcqj.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2ihyqdqhj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2rpiiadqm.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2shlcxgwj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2nahcluwi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gt2pbuiyhyr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gt2zcvraucr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2nboycfck.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gt2gwklqycs.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gt2nnrzdegd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlinqlfh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigufen.top/Article/details/gt2wxfffvdf.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2tpknuzux.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2etnztbds.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2crdygeks.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tregtmpj.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2memgyvby.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gt2fusylibi.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvrwdplu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gt2bjxygghb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gt2brnbtgqt.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2pecvabsg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2cplchgzk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2eduzielw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gt2umzvpdrl.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gt2odjxqilf.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdljtxrw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2kmvsrplg.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gt2sqibmpjm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vplpednm.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2kekupdpw.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2qftcoiwy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gt2igvekwai.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2zdboyucd.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2iusxoawx.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gt2wsmupjat.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2rqacbupq.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gt2gehhplte.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2fvktmliv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gt2rifvucpu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gt2alqzvlon.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gt2rhmyprbl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gt2punkdzjq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2asbucjsk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2wnyvrxff.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmitnssy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gt2fcpcodwk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gt2mzlccqot.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2mompptmr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvcnqexo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gt2tykukzsk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2podjuwpl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2bxxyhkqp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2gliyqtru.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gt2vhcgcmaf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gt2hhxhuges.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gt2oxawghjm.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gt2wsinumbs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gt2drvttcrg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2xuyqlwpp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfrcrxcl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2smlrtjpy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2bodezpdm.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gt2ajafzhzt.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gt2hfgfjboz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gt2idiqcqeo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2otuhtviv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2lwknqhbm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gt2fjkgcdvp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gt2vmnzvomm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gt2hbeltsdy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gt2xadwwufn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2yrfowgxx.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqahpmss.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gt2qtrrubit.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtmplhwp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gt2tmuindjr.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpcfnslf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gt2kjkbnswo.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2iwgqbpas.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2xygovlyn.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgbuqvta.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gt2bqaharqj.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gt2mhtwdvag.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2zzbysgbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2rqpoozzu.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gt2nfiqtiiu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2gwishdrv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2yibgwruy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gt2vmzncabf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2wcyarqcq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gt2ictdqqsv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gt2nbkbybbl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcjjepf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gt2efbwtwtz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdonyvfi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdtrzikl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gt2pacfiioh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gt2eqcptccs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2mwgwkkbf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gt2etavmqvx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gt2tcgiadkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtydabqc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gt2mlcfblyg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2bacewlyc.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gt2zwfzylhk.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gt2udivrhfz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2dhrnysbp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gt2czncstlg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gt2phxlclvl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2erlnyevu.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2moepqpss.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gt2urpvnvls.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gt2xlvkedjj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2xdefuqdw.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2umsxfxmj.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2rrgvovjj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gt2jccgmrek.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2qanngnjv.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gt2kgpbueku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2qpjdqaph.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gt2wmdqxuqf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouctjake.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2tmrhrhia.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gt2plhdauzt.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gt2igqwckgc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gt2oeguafmh.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gt2cyjzxqxd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeiygdor.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxgpwsfi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2fxwwdxmf.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gt2tzodhsdu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2ysvolcoe.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2znhsnmeo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gt2zwnkpmmt.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gt2maliumsi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2vmwnzuqj.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gt2liwigbtg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gt2hxziqtia.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2blqtyoqh.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcxlsgcu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2zfkmokns.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gt2ucrrjtpw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gt2bkmlvvwc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gt2rhjpopsb.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gt2xlpqfese.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qcoebsnd.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gt2zsqibhbh.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2qtebpedm.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gt2yddhpxnb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2vwmupikt.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2efannlro.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gt2loajdldm.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2qkgbixqa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2tisebgmw.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gt2sunpqtvm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohhmpxva.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gt2flksursl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2xnpzvmfh.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gt2tepmhfcw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gt2wgnpecza.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gt2dognhoas.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2lbauogup.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2ujxfwysn.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2gtggwjho.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2stoubmmt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gt2cstzddan.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gt2oxfdetzu.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2rmlhdlgf.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gt2alutfrtc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gt2spgiqnjk.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gt2pyyxcbwa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2nsxitekr.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gt2zlziihom.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2hcalcfou.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2owmtjzid.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2nfdkajkc.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gt2vnfyzfqk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gt2uspmgxxk.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2gugpffzo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2aegixuru.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gt2krohcgic.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gt2pcnjkhcq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gt2flqqufmf.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gt2gjwpkhdg.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gt2smwmythn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gt2hydcydkx.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2wqdqtqay.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezrcaylf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2lsclxezs.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gt2qwvlhiac.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2ajwletgx.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gt2kfvuqwdl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gt2poictzjc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gt2bychlnri.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2kchhoucx.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gt2bhaqnwwy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gt2bbgdbvkc.html


<!-- 参考信息 -->