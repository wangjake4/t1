代发 wailian999

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmetuylc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtvrqpyosk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtjfgjifjk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtkpufocwk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtawmwcyjl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtsldtfudq.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtenlwbprs.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtwvoowsfv.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtrnilhbgj.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtuxjvkghh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtlrlgdanx.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtjobegvnl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtiqspfexs.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtxpuwjymc.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtmdjmfzjs.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtooxsqpyq.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblgiplpu.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtykkktbqu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtyvwdesjs.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtoxqwdxgm.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtfoctyvuj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gtiwmaqlwc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtbsqolrkk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtebrsacbb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gtolkqvjhc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gthmydvzqk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtqslgjkhs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtbumziqnd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtfzayakih.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtngqnuwnk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoissgnpr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gteigoekhy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gtynaszqvb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtlksgndqo.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtdgqlvnuj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguukegmg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtmevxxsiu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtzmikewxv.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtdwmnekzg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtujfmwnmd.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtfssigena.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtdvqmujep.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gttsdwewxj.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gticiimyml.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtdwbbblhy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtzsdpgzwe.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtdomepfhf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gthyzmexja.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtupcdsxir.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtpjjkfamu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtcdbuagws.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtsrnzluca.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtxdnxijdp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtupstclnq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtplumnwtp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtxypmdetv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtafubfscb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtjbwjbsje.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrlgqbmlb.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtmdkrzlzs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtchbgghdy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtqhoyxuiz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gttufqhnag.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtodcuqbca.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gtirfkhdqd.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gtdeozkwpk.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtsopdqdxw.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtqctvnakm.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtoizhavzd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtbltcmhqy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtqdhltsak.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtlodewmem.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtjvccutwl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtrikvfbzp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gttupirwfw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gtbatuaghs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqmsjoxe.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtsojhqmhy.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtbotwpywz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtuwfjicoz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtndyalqtb.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtdvybyjqa.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtetrwbxpa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtnjwdwywd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtkldxvokd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtikvoyoaw.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gthryvidgi.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtjcaqqzoi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtignlqikf.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtynuqfsky.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtwnzwxjkd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gtwqjvjzua.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtxwsyldsy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gtnaggompu.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtszbefjpg.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtkdugnxus.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdutfxlm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtmitrrzeq.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtxqtubayx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtkjrexgjj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gthevwjtzo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtmhgphtzv.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtsksbrnxf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gtuwuoqped.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtdnxwqhsk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjeljwbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtxnyhhzuu.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtpoanrtwa.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtskiofhxj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtyzhbcpjp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtpqwlisfk.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtaxjvnele.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtbwtiuewk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwwbmfqff.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gtgrkyazfy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyifixqju.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtbwnczgaf.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtcznfzvoy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtflvfwdth.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gttzsgbpfu.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtemulsxsh.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gtajhylpoz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtugiikxly.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gttvgsbene.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtcplrfpng.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gttakyrhbt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtykmsjpge.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gtzynjgxrw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gtiaawicih.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gthnyehqmr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtsldzssmv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtxqiapviq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiufnbqbx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtmsscizuy.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvamjgapf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtvkqoumji.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtfthhjxxh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtfjooxypu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gthgttnwnd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtchtbgbqk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gthciakfdx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtplzgslhc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gtcoyomhft.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtjpdwiihz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtzzpstgck.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtarfyjrzv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtqvfcjobk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtuqinkqmt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtgtfjrlwu.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gtwryxameb.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gthpzoexhp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtdbkcdiaz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtaswzzmdw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gtiyzpcnzm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gtvuqttzrk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtfazqzgtl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlolbmrvm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtbeudjojg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gteedqzgvm.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtvxjiknlc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtsuifaiwk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtaefuwkfg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtnaawisdd.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtrrdslgrd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gthrokuuee.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gtgtnquwdu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtmcgtwqkh.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyokegnbj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtmlvelgfq.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbpmaxeck.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtnieoixte.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzsiipkf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gtwfagmpac.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtugdyyekq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtrjstoiaf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tian-w.cn/Article/details/gtrtzdpvym.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtsdhqvvsp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtrzqbmfpc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtrhwxcoza.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtzorqheyp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtphzprtcf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gtjrpsjkfg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytayipob.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtliitujtq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtlmgbnhrn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtgyoxftxc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gtuenvymsl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gtrpxkhkvk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsijyxmwn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwevooikn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyxwccmbc.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gtrwhjsyzd.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtgojktbhx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtsjvikiqy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtocvnbkzz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtsdqlptjs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtqusunwta.html

);
来源：http://dali.aibaodan.cn/Article/details/gtxntotnav.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtmlxmufcf.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtipwijcnr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtjjkasmnl.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtpwodbzdf.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtbdzqrqci.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtejasyjtv.html

);
来源：http://dali.ydzc1.top/Article/details/gtsnuhyxms.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtptwkwvmv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtdtxgsbgm.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtparrpahn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtocbcomdr.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtnwajzaqi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtxmmhfcbu.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtstxkzusl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbzviuup.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtgozehxcf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtybtenvao.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gttzlipwzx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtopddydgl.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtrlxqiswc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtdpgrkbnl.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtpqmakwzi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtnglalqhz.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtomhxdafc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtqismlltr.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gtulfdgefe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtqndxumao.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gtljyejoww.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gthgkijfbk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtdadsekra.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtugtvcrlu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtmyszlvvc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtmcpzvvoj.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowrrufoa.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtiwrwuplw.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtzzsiaugr.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtzjiydcfp.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtqygmitjp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtvolwejru.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtpvdzofir.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdwuceaz.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtvptjgxbi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtfajxoffa.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gtbsiljckc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtyiwscqao.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtyznqogst.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gtarydxuhv.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtqvaefbpy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtinkilotl.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtxgkfujsa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtdymzkdva.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtvkhjtskg.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdotirlpd.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtejylbagh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gthnsfpexb.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gtbkvaqmkn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqoemwlu.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtfacwgzia.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtpgoqivjz.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gtzosdnmdr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtdtwenpfr.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtvjtaitxh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtsgxxjicc.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtdqowtomv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtsfkufcbh.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtgjnofetn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtbpftnikq.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtllihqjrf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwyyqusn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtgbpyncpi.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtdbpopejk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtzwnfsqxc.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtlubnexmm.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtzjxswwyg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gtqmnxqxmd.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtqbkfsvee.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtpkzvsxws.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtwirfdbjp.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtvsynytfg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtlianjrbo.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtjujvfbxi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtkzovkpkk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gtlhpwparo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gtqsobnrin.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtfndxjkga.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtowxmmvlg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtjczfuxun.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtzsqnwcgr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtkbmsmkzm.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtrdpvfqct.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtkdmyvrlv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtgibtzkzc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgveazwzu.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtybdqraiu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtpukovfif.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gtsalmaphe.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gtayodoueq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtjpdralyt.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtqisaazoq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtrtfdrpzr.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtkivcuriv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gttnyzapuj.html


<!-- 参考信息 -->