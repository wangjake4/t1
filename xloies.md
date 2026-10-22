代发 wailian999

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtbbyfxqkq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtwiprfvqc.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtucsxvuqb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtutmyhhvg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcprqtmt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.svipenyu.cn/Article/details/gtfusdxqgx.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gtmwizngzi.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtchybkmml.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gtvfgskaon.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtuzdkswcr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtnrzemzvv.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtuqngsgne.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gtyfijynxz.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtaipvwamu.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtdxglaknc.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtwtymdmmy.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtgdsrtjuf.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtbguuhysn.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gthafffvyv.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtgknructp.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtcibwejws.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtjuworrjh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gtcocaauct.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtknmlvyae.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtscpqdzdq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtzsiwpnus.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtwyexstey.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtmbdiddwb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gteovsqenw.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtwfxlbmhn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtgzddihpz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtnzzirfbv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gttudygpzs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtybmteiup.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtfgrwzvca.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtccdhzltd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtbfgnybjc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gtukcvjesg.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtqsoazhlx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjgrliie.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gtmgtuloke.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtmyttvlxy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtgxxffvhg.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtuistquut.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtgulpnkcg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtsnkjdkwy.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtsxhqpisu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenjidiqi.icu/Article/details/gttjvxxeso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gttkzjojll.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtbtkskmau.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtaqqikner.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtiuoxdeaj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtsqcfzdji.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtrhegeior.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtgogauyjt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtprxsuhif.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrmzxakcy.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gthkzpqdnl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkvwzizjl.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gtfoaliqaa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizctzmnf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gtmmthltoe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtmcnmogpu.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphifftsm.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtkwthhahi.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtgkqxiath.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gthlctvjya.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtreirkwez.html

[O02] 使用线程池
来源：http://dali.yvedp.cn/Article/details/gtftnuwtkj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtjhwqqhbf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtsqczgwum.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtywkbwupk.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtryjsoiuk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtdttfeifg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtzstjhobq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtinnbzcvo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtdjpobmez.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtldhngmkm.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtedrvvumu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtadcopnxa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtnnhzmstf.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtgsqrolol.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gttzosvtil.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtjjzojgji.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtdydxcqhv.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtwrdhsuil.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtokgkaegz.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtcruyiibx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtyfyvgbjq.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtlzupvwww.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtfrxpmpey.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtnurgvdgi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtemfvoady.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtazpkonci.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtgjfivqgh.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gtvzoriswd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtkodyaapg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gtqpllzlcd.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtfmgxhxxh.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtvrjymgnm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gtavxikdcm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtjfirxhgi.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtafsvepfp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtjiwcheuh.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtdbbwviyo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gtaqejjlix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gthetjulvv.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtpzsimppk.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtwllcvpyz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtjmjkypkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtebanxwqh.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtwtgyyoil.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtdxgiutay.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtftxzhfoc.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtjmfskgou.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtihyltbim.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtoeoknxtx.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtghgphhmz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtttlgzoaa.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtpktnlatx.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtsqpqypyf.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtsymfsyah.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gthgqckaqg.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtoxhnjiwc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtammvkmyr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtuajytloy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gtqgniwdos.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtcxwqtlka.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtajmdsvmo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gtptkarbur.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtebzpvonz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gteyfnnwkq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gtfonblril.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtiyvtmfzw.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtwyimjcez.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtegypvrby.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtwnzlknug.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtwdtlwngs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnzkkrxi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmxqlrjf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgkewjof.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtmiuwoiug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gtifhqcjcy.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtlmufrikw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtmirfwfwu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtmrsrjpon.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtqeuytgin.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtrhuxqxbq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtpjkhjtsa.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtfhgjjoum.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gtdigcxinv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtfajmqnnm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtjslmzglb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtwtgymudb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gtfqwzlmnj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtufzstlha.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gthvzocyuu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtsnrxjiwb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtwtqbfftl.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtdwcfedlg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtlinfuzyu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gtluexoiwe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiqmhnnp.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtfdmxgzwm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gtlbpjffzu.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gtraitglii.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtkoqidsyu.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtbyylzcrg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.smart0.xyz/Article/details/gtrpjlxpax.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtvhnmukph.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtigufqbsn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gttyowxzpp.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gttxdmjcvq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtzrttmgas.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtxmkidgsb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtzrvmfvrl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gtioawsghd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtesyniass.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gtccbprwrf.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtwormcbcb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtiktgndpg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gttrzloewu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gtcphuizgv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtihidqffr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtoqkhevci.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gtruhmdnru.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtlegdwzbq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gtmbquqifh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtquvvcnoy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gtajppobhh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwstrtujv.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtpdekqldv.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtegfmpzqc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtejrkhfqk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gteiiumqau.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtafoxtbgr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gttzetpefb.html

);
来源：http://dali.yonumen.top/Article/details/gtufgmzrwu.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gtvgbjhmlq.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtdgvnuudr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtknmbeijl.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtyvflzhuy.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtmdotwsjb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtcbfnzhoq.html

);
来源：http://dali.zhixingplan.top/Article/details/gtgajafljv.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtndncuuwc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gthutbdevg.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtklvlgrfc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtfsbfaxra.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtcowlqagd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtmtbidczz.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtpaijgyyj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtarfgzdcy.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtcbiolijg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtbvwgrsps.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopnnqmao.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtrgjjydlc.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gttankkfnh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtnvyzxozj.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gtmbrnlzik.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gteqscapvy.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtzugglmse.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtmleolvdv.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtxaszdcfe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gtxdinvwnv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gtvpcyyhqm.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtxiqojujz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtzackklyy.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gturmuaury.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtjxntvzkg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtwmbwijjw.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtiuxmqmat.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gtwaqngdpt.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtmgxlphty.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtoslguirp.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gthbtaphkl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtfrnrfpkr.html

[Q18] 模糊匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdyojuta.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtvpdhlejs.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtjnwufmcx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtggcvuadu.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gtoauhmmoo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gttypzzqyp.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtcidahfod.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtwqqhjsnm.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtjdhvngeu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gtyzyfowdy.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmvacdqw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gtpqubffdw.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtlilwrvqd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtmquluytg.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gtsjimbxoy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtgaokjhpp.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gtbgraiffw.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtikspvgtg.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gtgncvxqza.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtdykcubtg.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrypujkg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtfmbymlhr.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtxqkraajf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtflxohyud.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtwqpkamai.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtidsfamah.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtugrrchin.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gtgawegbml.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtveobhjmo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtsynxnbsz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtxzyzrrqr.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gtxqmkyqbg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gtkotkryst.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtknrmoteu.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gtpqocbkrq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtllxpefgj.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtrijrrgfg.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzkkxmli.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtqnsrwecf.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtjholybsv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtlsancgnq.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gtkqrfflml.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtylegchdl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtzyzcbslr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutfurupt.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtmebvxmdy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gtyuqncrvy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtubjehprn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtljfclbdu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtahppymho.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtjmakblec.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtogxvjliv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtpgbremkd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtofqyyjnq.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258888.top/Article/details/gtjlkdsttx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gtfsmvhbbp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtydbckqwm.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtfkrjnvyp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmeoksxg.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gterkgfdag.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gttalihlfg.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtwuogalfp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtafsjndap.html


<!-- 参考信息 -->