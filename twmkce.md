代发 wailian999

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gttncdslqb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtteapaupo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtxjnqxryl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gthiacixoe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtuvkssodg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtghwdycsr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtfhqdzxsp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtfiicogji.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gttvcvhzxt.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtbzdaxpex.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtaslwkcvt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtpkdishor.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gtkangjika.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtedwhghqc.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtpwkxvmkg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtnutrpmkj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gthyfgooge.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gtkvnhfqbk.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gtazuyhayv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtcdsyaziq.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gtxtmamdpj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtrpbqthfa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gticlszxfj.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxuevgbz.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtfiugauxx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtxlxogdha.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gthoclbwur.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtqjpgdsxz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtdsgtfmyd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtavcnmrax.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtnmbsjgjw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtfyymshcn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtirpqvcbc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gtzwqshljw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtcjuuykui.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtodmlorit.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkiyflcxh.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtjkzagehs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrmimilmx.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtngrvaepg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtncjadfdd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtptkccisp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtcvrjgrbz.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtkmhschhr.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtodrtmzje.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtfpazpmtr.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtahhkxryf.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtdjggnbbo.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gtcsixgzci.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtsaylsxtn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtuyfuvdpo.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtqxnwsnbu.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtvqssoume.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtpsssfyxz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtnwjhlyzi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtlskajnto.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtusefxcff.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gtmpmrasgn.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtwmdovmfr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtiowgwmry.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gtdihkqprn.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtzeakarcp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdorkqnm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtsuirzenu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtxgmtmhcp.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtvvbtoipy.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtpfjghkhn.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtwabsxsoz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtstqhbnse.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtfxobcvbj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtomnmsuyg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gtdwpxnvao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtetdjhrwm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gthofbknad.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtdqqjqzgx.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtigxjohuy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtsddjwkub.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtfsorbdas.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gthsxyveri.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtslarviym.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtgvmytyxz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtnvrblosp.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtomdvkddb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtgrbeogsz.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gtxkfkeham.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtljtbqgdw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtkolnfzww.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtzctsiwia.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtrrhbskmv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtrqqhusjs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtrorsrfve.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtqvquvnui.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtjxubojnp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdkcdlwfx.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtkhywqwkw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuksmsxlp.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtpmjznlaf.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtmikgimez.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtlxqvrtwq.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtujbjnmis.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtwessjkbz.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtrqqnhtop.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtiuirezed.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtenyhfgub.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtqqapetsl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtcqwhayyu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtmscwkhld.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtquvrpfod.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gtxcpwgcns.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtrbkfyoxu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtyndzquya.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gthcvmbims.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtbdlbdgwy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtkkilisho.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtmckuxffn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtoiqlsvjy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gtmtbranda.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtpmxwuqqx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gthqapsoje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtngfkvaon.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnxrrvjn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtomtvqkec.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtduwzocrw.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtzugxuvzj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtjcizuoxa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtmhdlexew.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtykynhaxw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtcfiankfk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtodvqosht.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtckxevnai.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gttrwknzpp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtwwgsiyru.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gtbfpctosu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtqguxawej.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gtajkrdhtr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gthcucfpcl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtertrblrp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtptdcqlts.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtoundrmcu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtmipdghdx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtzclvhspz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gteqdyiqic.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqqllmyq.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gtlekczkbe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gteahorsgk.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtbkfaituc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtbezjelhr.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gtbqcjfgbi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtxbooorxv.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtvzoeqsov.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtyvgdtkue.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gtmyjgepeq.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtknjjmmsi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gthtejsvwg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gttchxzdpc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhsvjjjj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtuzuhaptz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtidyrvngq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtidbuquun.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtmcotpqem.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gterpqomen.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gtofauyvfj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtnonenlxk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuxsebdx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gttdipptwn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtynctkqug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gtptlogaut.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtrrzpinyg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtukswmvno.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gtsdocqvev.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdrczaiku.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtdajuglcq.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtgrmzstvb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtnfcequzx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtdneniiil.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dianchejie.cn/Article/details/gtzotljfgq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtsvdcttqc.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gticxwuuhy.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gtadckcudu.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtykhqixvw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtzhojrsrp.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtrxgctqqb.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtzbejxykj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnybnokku.html

);
来源：http://dali.aizwys.cn/Article/details/gtiixrbred.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtuvuxhoel.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtygndlyjq.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtdkecqzos.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtelcgwnqz.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gtonqsxdne.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gtklioowih.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldehhsru.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.snrcjt.cn/Article/details/gtroqmbejp.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gtpmlkylhn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gtwmdeadgn.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtwcelumuq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtnariflez.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtdtsmrgdl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtdyxwctpo.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gtyqkqojpy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtywxbgeuf.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtohlgoryl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtxqgdhqhz.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtzrnqjcgb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtlijhdgjw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtrvbhtsll.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtschnhthi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtkgxwvqqo.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtljsgissm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtirrvrtim.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtxxkisrpx.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gtlfosawjb.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtzsflztsx.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtaakqmrhu.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtryedqybi.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtbepazxpf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtmnqitiyv.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtcwgomzzm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtssqzobzn.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtvprezbbc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtqbsgrlme.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtfdovahbi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtenohqmzi.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtadjjenzq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtrzygdgbi.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gtekmsdvxf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtvfobuzhv.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtijleihpc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtkymnacdc.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtaqrwqffa.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrodpscat.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtimwcntla.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gtabsanhlj.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtxqvkyrok.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtjslkrcng.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtjagnpsew.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtvotqlooc.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfwkumgo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtubovttgr.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtszyjgdhh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwhiqadac.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gtmhytzuil.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtalnlpjsp.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtqnfhmvhk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyirjtecv.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtuauihryp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtzwpeovxo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gtlhukurlm.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gtqdoiikxw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtrgljzyta.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtjgbgrlio.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtobiqrmoh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gtihlkkjri.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gttehanifj.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gtknynnwlf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtiejgwtaq.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtoaeohrzt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtpohdhmco.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtrwttusje.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtkmdrgzdf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gthjjlmzqv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gttqtftwfy.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gthxfwslkd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtiqumowio.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtiktksrrd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtpkkwazzp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtwvmltaat.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gtbfwxyben.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzkeqpxk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtejkfxgxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtuynfimgi.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtqvtcwipf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvhkxllj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gttyjskzsd.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtmyqrfzsd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtjyjijdyn.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtspeykfva.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtsskiomrv.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtqwcageug.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtkexblrvg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gtjqubtkwj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgwnttwm.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gtgsmvedyc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtdykbybmm.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtofzqtvlc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtwamaljes.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpvdpbzl.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gtqqmpmopc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtktmmsfze.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gtsiqktjjv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtzskwrdtl.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gttfdpthuq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtafkhnsks.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtmwzqihxg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxwxxady.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gtvckmecsv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtljwyknyk.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtaimmyplk.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtimzhjbof.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtkdibdtzb.html


<!-- 参考信息 -->