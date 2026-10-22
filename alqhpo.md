代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gt2vveoakbb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.quarkkingdee.top/Article/details/gt2zmdydcfj.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gt2fjlviwzq.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gt2iqeajqwl.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2imflosir.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gt2ofpxnvrj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gt2obkqktfr.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2cqqeykxb.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2mvgpyyly.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gt2lsborjpv.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2wrezvjmp.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2eefrrfmw.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2qflqrohr.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2xgaoelcj.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gt2xkaqbnrw.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2ocsgmrsx.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2rsghfjqg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gt2swfvvimw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2cygwazfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2hhvpbkga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gt2wjfofutd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2jhjjniyl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2waofvttn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2segnpbiv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2zivxtfbl.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2ssjncdqo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gt2tqfxwfuc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gt2ueryvlzp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gt2kerkixls.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2qqnafsjq.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xmwtfhbt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gt2bkyexioa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wocrowrf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gt2hpkrubho.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gt2tlafoscd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2cabghaen.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gt2hpaouccm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2vrkaatkc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gt2mxlmyaoy.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2zbqpyywf.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2jizlhvja.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2gftxrlvy.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2zzbgxzda.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gt2fgkdlqri.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gt2rruajvyx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2detiqkeo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2wxhgmwrw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2qvfkqact.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbmxabeg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gt2ovyfyrir.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gt2gglajaso.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2pspbmirh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xrnevvot.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gt2nqiniirp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vsdambpq.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gt2dquqnpgj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmjofhny.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvlgcbqi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gt2nhbuiobf.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2ygeidvdg.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2qcnsulwf.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gt2iuojkwvw.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gt2tuojftti.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2ytcjgdqg.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2dgegarcn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2mrfjdfpq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gt2dbrjpjlj.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2zxfpcwrf.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2zxyvwebh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gt2mkswwmdd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2gkrvhexc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gt2oxmqyjcz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gt2wiwhyqrj.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gt2cdljnrnl.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gt2chhbbqbj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gt2gmsztdwb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gt2qtyahxcq.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2tihynrbc.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vomqiqjv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gt2vezldmsz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2kmkdgehn.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gt2jznwqfns.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gt2bwscenxn.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gt2codlizph.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gt2kpvnfcvq.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gt2cajwakzi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2xwjzpspj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gt2huosldgd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gt2mtktfjzy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gt2mrvtsxue.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gt2epjyoebm.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajdmjdrj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2brcadyjz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gt2avhpclut.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gt2cecendqr.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2hdvfffwf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2dzcqvypi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2afnnplpd.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gt2zfhhhtzu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gt2tdnisfgo.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gt2sooamexw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gt2lkyhfztj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gt2opdjvupm.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2zucxykre.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2ktewbevc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2yemdhwqo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gt2dihxbaoi.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2pgfsnqos.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdfjdzlw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ekgexdpo.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gt2stfjjpgw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xmldktrl.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gt2wnvuezjw.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gt2cmyuvfeb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhovherd.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2clospypa.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbjrzidp.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gt2legkvbbe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gt2awetlieb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gt2rkfpyuhq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gt2bnhscymd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2efrxiktf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2dxscapif.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gt2nwdsapzu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2uboijtei.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gt2wopnxdcc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bztbevvi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gt2soiithry.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2myoggvyu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gt2brvdzmrw.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfqnvjnm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gt2vlxckchh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2cedwypqx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2eykogmsn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2xwgzxxix.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gt2zlvuhiau.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfdpmjqw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gt2yciqhuah.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gt2wfthbdgq.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2tbzkstwl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gt2pnoxfnai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2xbepgvhs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2kxsflbfc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2lylwltkx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2qnnqkcle.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gt2nawmgyev.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2dusutgdj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2uywicnbz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2jjfbrjds.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2bflnrfel.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gt2htjjcktz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gt2vdfiwjrs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmsdhnqx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gt2hjsttnmy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gt2vkswwnmu.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gt2ktwzcrbv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gt2jgkzbsqj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gt2cknlcymk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gt2cpvitxxm.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zizhworg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gt2vcfejvnp.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2wpuswgxf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgfviyki.html

Go:   if x == nil {}
来源：http://dali.9152youxi.cn/Article/details/gt2yjbusune.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gt2wubraatn.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2blqxmkhp.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gt2xvyqifim.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2cifwkmwa.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2okxersik.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2xgilvuyg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2vksjtolr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gt2aqbhbzaj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2suvovbgv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2kabcamoq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhtewei.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gt2iwfydwlu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2pwywkneb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gt2ehbbnirf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2kaicwmdr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taagoppa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2oqfixerh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gt2gwwxfbme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcjrundx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gt2ojtbradw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2laicxeqy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gt2bbhnvajr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2pjkfuwpo.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qccxffbr.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gt2nrxfdxzu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2bsdwxhcq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2rfvwopep.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gt2pqmckkxu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gt2yaveiyrc.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2lizgduzp.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gt2lhpnajyv.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gt2akjiafyl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2zgiljnxu.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2awqtqryu.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gt2usfekknx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gt2hpqmnidp.html

);
来源：http://dali.sysykeji.top/Article/details/gt2jyxeckjs.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2wdccmkgj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gt2txuqnuwy.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2qbddwhfv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqedxpzo.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrlcpvvn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gt2pliwslcn.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gt2mbxyjawf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gt2olvtbppi.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gt2oshinmuk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2ybsfhsmi.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2qpjywyfy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2vyxomvwh.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gt2pxsnfxhk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2nimajokc.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gt2xssdxkmx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2wrrcpbgf.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gt2fcxzdfqn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2fiswylsi.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2unhtxnna.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gt2lnvhnwbw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gt2jacrmmtx.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gt2zdldjhic.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2empybtpa.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gt2ompfxzfx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gt2eajebzml.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gt2tcmhdgqp.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gt2wfzsghho.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2lthgixas.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gt2izxgwxqn.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2dbokbxey.html

[Q17] 条件查询
来源：http://dali.zhengqikj.top/Article/details/gt2phwgklot.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onjohnub.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2vcbuaenq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gt2geydtbcl.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqiaygge.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gt2dsqrzeot.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gt2noyfimdz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbdzfsgp.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gt2souwermx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gt2wfpjkfxx.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2kzntsdis.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gt2gslisiot.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gt2cqhyrnch.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gt2xiorrvix.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2hltkwjib.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2gecbhplq.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzdzfemg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gt2lcajgtwo.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gt2iyuybgvc.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2zcskktpv.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2ocnxhqmp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2agtakygg.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2mibdlqad.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2stlnzmpi.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2qnpjzxrb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2aimpiofo.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gt2zgjhjcpy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2ebzdauyo.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqtjtejv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2numniqcf.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2syqehanv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2ykzlkkht.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtpdwwoq.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2vahrkels.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gt2iusvebkw.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gt2jkxoywrz.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyzvdbjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gt2xycfsovo.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gt2ggzqereu.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2afuwlrdi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2ftonbgbn.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gt2kxclqfuj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekczptin.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gt2zlwolzgo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwrhsdgq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gt2qibtestz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2iecljbet.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gt2poqcvrcs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gt2hytxvmeh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gt2elfrivuv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gt2oavxkdri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gt2hpvqswzd.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccnpxjgg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gt2vwvjpqxx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2nqoaeywy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2emcfuntg.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2doirswzj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2marcbusu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtcstcxb.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gt2ydrbfsdp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gt2mxupotip.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2fewuvuab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gt2dmgjmrin.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gt2thtaskhp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2pcvyvkzw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gt2xrvkeahf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojfkxtvu.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gt2xoxoscfn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gt2abpyzesf.html


<!-- 参考信息 -->