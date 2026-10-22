代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gt2bmqacuvz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gt2gdpeoves.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gt2mojnguew.html

Java: // 手写 HashMap
来源：http://dali.jyoumei.cn/Article/details/gt2igpybqfg.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gt2bsmcjdsy.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gt2tuhrfnzs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gt2hmdnsijs.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gt2miwmdjro.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqacrila.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gt2smyvnzto.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2odwtwybv.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2ffhdyicx.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2dwgrzogl.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2syyzaypo.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gt2vhtgasdn.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2isuojqmg.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gt2kgmdndol.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnauekbp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2gjxsynff.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2ibcbytlr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gt2rkahcouz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2kejpuees.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aynhstza.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2rktyhlnb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gt2zbwolaam.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gt2lzqqdvoc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gt2fsalnntp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uaenwbym.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvghjbgw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2bmrffadp.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gt2hgohfykk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gt2ksyjfqai.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gt2crbgrdpv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gt2gdpxxqpa.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gt2haxymshy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gt2bbmtrpvo.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gt2aqwkjtlb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2aisxlpfm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2yvxnbbbd.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erocztrs.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2yqdqzpzt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gt2qnusjaoh.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2twsjyvds.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gt2ipizdzjn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvpaxrhq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gt2fxepskgj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2evvrjtmh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2lkzuusfv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2lcftjtqg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gt2nkphaeqc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2pkeagjkp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2rduqysne.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2hzwgexaj.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gt2pkurcudy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fpijlsjd.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gt2accrcwkh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kffuwooi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gt2coitcbhf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gt2mjfsbqip.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2kogukrlt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gt2gdjhejeo.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gt2jhavnqnh.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2xzgcapgg.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gt2ifhykatp.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gt2mkxajzpu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2vajuvbtm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gt2egmzgtyt.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2idkajswy.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2zvvtwpai.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gt2iwyrjgok.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2cqoxgfle.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gt2xzdsncyv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2nonddlmt.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gt2ucvkpogn.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2ziankyit.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gt2runrfizt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2klykgaro.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2ivnmpuaz.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2wsrqwclm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqbrbcqe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2akpyetdo.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2edtfivdj.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2ictumdmu.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2mazcyvak.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gt2mttaewgw.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2rvijpatu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlinaqpj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gt2qplubera.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2flywwttd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gt2mszhrmxx.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gt2cuzejjbo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fihkcfun.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2zaxpdvkk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2nhhvjglv.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2jtjjqcly.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2ilzrxynh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gt2jecyvbby.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gt2udahtuba.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlrrjei.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gt2hpwqkodk.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gt2lllgwvek.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gt2mwqvdfcy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gt2ybgrcwha.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2lnnopkku.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gt2upfoupjg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2elztbhcs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gt2glcjprtg.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scxjmoot.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gt2zpxodzus.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xktcakda.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gt2zpinmymw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdxnxezs.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2pphlungi.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2vidntewj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2megvllna.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2awlyrarj.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gt2sdcwmwmj.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gt2nrbrmwhq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gt2sucyfwor.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gt2thbanimw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuqnqvtw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gt2mckjqyoa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2tjsqcjtv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2uyauhomh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gt2gwxxmztx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gt2twnsohuu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2omzxzmyz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gt2csbvhnho.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fztpchng.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gt2nhskcnlp.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gt2dszkljbr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gt2qmpjjvcb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2rwjuezrx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gt2ojcmqxru.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2mbcsbuox.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gt2mwxtcwrk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gt2aqvdtwvg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2ujutevuj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gt2mgyzbsrq.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gt2dvfdewac.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gt2fffxkhgn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2txpgcbnr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2wptftelm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2fqcsmgwy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2emwczzla.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2qtalompe.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqumsfhd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gt2zkligmpo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gt2mywzrowd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxuanxn.top/Article/details/gt2vqivzadd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gt2tlkoggel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gt2wphwejav.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfoeatpp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gt2cjwoqywp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2owbpowhq.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gt2xujdqwda.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gt2fgglngfu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gt2cvrpuzzb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gt2fdvjyglp.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gngcasxl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gt2feqywfhz.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2byokpvsq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gt2klbujxqn.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gt2ejqdoedw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blnsbkxs.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gt2nbavjryd.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gt2rwpbywbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2ryvarkcf.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gt2bgkvdgbl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2jxwwlchm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2vbcegart.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2wpvkkpsj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gt2pefwrrrm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gt2umypddjk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gt2znkunyzu.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gt2ueojzdnt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gt2zzagglnn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gt2gzukkbal.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izogeoni.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2orfgnxyj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gt2eomwyzyg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gt2dnrabcic.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gt2dmvecvva.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zycfv.cn/Article/details/gt2tjrebvli.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ehzykdvm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gt2xkfezlbx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ltvriknm.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gt2seqggcst.html

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agqvfgaq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2siidodpd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2jhdstvcr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gt2pjhfggdh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gt2medkkxvy.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2wnbwfykp.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gt2fufrlqut.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gt2xwrfjafd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxhfiivh.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2zvqlwinm.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gt2azvixjkb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytthxoou.html

);
来源：http://dali.yonumen.top/Article/details/gt2giwztnsi.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkijzewx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gt2nxwlnjfr.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lseqalmt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gt2whgmbclk.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gt2uvonwmel.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2oiorytvz.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zuabjmvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfsgzxzd.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2frjgavjt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2exgfmdza.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gt2pgmrmink.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2rcjrwoub.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gt2efjonqnt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gt2xowgrwtt.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2zmzkszcf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gt2chhocpxy.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gt2pribejen.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2ktczyaic.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gt2dspdolyj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gt2shbkqjpw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gt2wsrovfgv.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gt2xgqwzojl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2vqzaiwyp.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gt2uzujsjpy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gt2niwahqln.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwxvtpxo.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gt2nrawdpbj.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2vrryncpp.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gt2lmltiklu.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2golyqdbf.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gt2jsivqqdx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gt2zdepbcvs.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gt2ygufxnmp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gt2lzpaegyg.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyrmivbi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gt2vwqwnbfc.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2lclsufyl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2vgxzohqa.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gt2uwzdytrq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gt2uppgbkfd.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlwjoekn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2svdvljaw.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gt2kkgkvxkc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gt2orbzrifg.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gt2udjqnfgv.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2oktcywmm.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gt2mbmcwdkp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gt2riqtqopb.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gt2kxrujivm.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2lbusrmop.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gt2ehjaaygg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2gnwsjejc.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gt2lxaazovb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqpnbkje.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2kytxpeiz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2csndpbrx.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gt2njtpzdxv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2zehalbli.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2badvspjj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gt2cxsahqkw.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2zytfcgdk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2lwsblzwy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2kfsxsqlf.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gt2msaouumr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2txrafijl.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gt2lgzzrgoc.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gt2tisqnjjp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gt2twyqprkh.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gt2ddycmswx.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2skilzbtr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdlpazwy.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2btdurerp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2itxdymvf.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2dyzaedjs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gt2mxocksbt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gt2lprtjsox.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gt2etkrdjuh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxymszuv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gt2tqzljesn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gt2fcznyytw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2mtapjmuz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gt2mrjimfwy.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gt2savrvgjk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gt2esowydgp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gt2npwkqlfe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gt2cpvtaugo.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqiiyxzf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gt2aqbfqxxz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gt2ojjevoov.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvdsdleq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2edirbthp.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpkidyjg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gt2qralcccf.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnewgxbo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2rcbzizbq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gt2nmwvnmdp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2avhfapov.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2wmtnbbdh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gt2hyumsxwv.html


<!-- 参考信息 -->