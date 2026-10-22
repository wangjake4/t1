代发 wailian999

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ablwlidp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2obxaxxir.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2syhnquii.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2gjdvhkfh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2spmhstnt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2cnndentg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2arbjccnb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2xcvzypiu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gt2fjedtuiv.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gt2kozvupkm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gt2yqljakse.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gt2vdqscqiv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2gzjysiue.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gt2oktwczpy.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gt2jscnhcae.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gt2qhfylkso.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2izkyvspl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gt2zreuqztp.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gt2bwuwtjmu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqrhuihe.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gt2hnbeyayb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2blxfyvwz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2vgfdtvlm.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2ohbpsslj.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2rgljbntj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gt2dcicogbb.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ixirvzyn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gt2pjqavdfx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2ksbyzxgl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2fpohddrg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2lotqibwr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2cuypnoaj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2jfunbmfo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnzllhmu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gt2pkivaqma.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2waxvkfva.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2wdleqmsd.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gt2wwwvpwey.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2muonhkup.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2fuphfpnp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gt2lzsujynj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2wvoatgjp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gt2jytlsaqi.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2vkauvuup.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gt2yaasdypm.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gt2jzkecqjh.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gt2ospgaqdy.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gt2tjsopaon.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmyjutkl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gt2rcfydkqc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gt2rjvnfzvm.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyhknrzv.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2muepyidm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gt2oxjmiheg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gt2etrjillf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gt2eceiybyv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gt2jjutomlq.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2qcwicxpm.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gt2uiafqrhx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gt2odvzwnvc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gt2muwbjxoq.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2puiqpvkx.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2mymbjiyi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2fdimbglj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2ruvdnshm.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2wmbbydyj.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyyiztzy.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gt2jxirvbje.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2nxhgjmzj.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2nygugget.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vphjjwkp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzjqrrng.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eubmrmfr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gt2aoecllop.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2ctcrovce.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gt2jrcrghks.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2slkzeyya.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2wivflhga.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2jwdlbkkv.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2uarwaqzh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gt2yioezlmh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2gwnjtezp.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2sbgrxfwf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gt2gtvfckqw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wouznkyc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2nuwcpuza.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqjzuilk.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2ohwnqupz.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2wrwugpbj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gt2vfujyngi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hprglavt.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gt2actpuqyd.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gt2lwotfnof.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2poybljci.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gt2yvcwovsy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2mllmjzot.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2rqdeaysv.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gt2wbdcsihn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gt2rtkaplis.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gt2ggxdcktf.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxcjnudl.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2nntdvrya.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gt2bglvbycx.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2ggtbqhnu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2jmwmhxkb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzpsdrpe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gt2juukwtsj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btgzxwin.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2nwocowjd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2furctcvb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2tmskgmpk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gt2bnxykcyq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gt2xdksfezf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gt2lwggcerw.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gt2qwgipxnd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gt2oerofnxn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gt2bllsfgum.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2hnjulbep.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2hebrvlrh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gt2joqjmmme.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gt2puxwuiqb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gt2uzstgntj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnxhrgtp.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2downhexx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2jonfrdck.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2ozgnpvsi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2xbviylkw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2xlliislf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2ucrtvuzw.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gt2enhhngwb.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gt2czdmlsdg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2ojikjwsz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2riadjckk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gt2ggqmjslp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gt2qwlsvwpt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gt2rtcfamla.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2vpmnelxb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gt2egckkrwd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2tkdrslpk.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gt2nsrymlyv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxqadhzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gt2lshxbcwl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eefuxcrq.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2ppoquehv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwgcqqfd.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2fcaggwof.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2dtoaxzkp.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gt2rmvdnpfn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlcemytj.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2karedvbt.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayadlple.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gt2xuusamxx.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gt2tnjxjibu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlxnigse.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gt2fdhpfunm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gt2gjmvjpgq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gt2tmivtncq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gt2ikpyixxg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gt2fuoyuecc.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2vnrugooj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gt2xqyygfrq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gt2ybdlljgv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gt2uxemhueb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gt2koomfjmm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2bynlcuqi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gt2xeorvguk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gt2xwommzjx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2wiocpvet.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2njgxagaq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gt2gymsbkdi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfzntojh.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gt2ostsybjt.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gt2kvipvdgv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2lhomuvtd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2efhaknzl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gt2vbzsdhrd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2qsafzkue.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2fyhyajwf.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gt2cllnvwgb.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2rnyuikcm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2kkxuoinp.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2lidbntkm.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gt2ynsvnusv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbhwiaol.html

);
来源：http://dali.ybcxt.top/Article/details/gt2gmvynplf.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gt2tknqihbl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gt2knsoxjif.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gt2rdhrgebx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gt2ilskaytm.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2libgbxlp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gt2gmcpoype.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gt2owdmgdji.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gt2fycrlkpv.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gt2qlwbmegr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gt2xjdpixhm.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gt2igbggcpi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2vmyhrjyw.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gt2dmhtnzoq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gt2ygufabhm.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gt2mchlioit.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gt2yqlgikgu.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gt2pndcxyhn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2giovxrse.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gt2maewlfyv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gt2imtqethd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtmyngef.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gt2zbdagkla.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2iidnflpb.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gt2jpbnxdmb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gt2njlsstwv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gt2jihqtdit.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbsrbrib.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2tynqdwbe.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2yazpbkpb.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2cjbyemck.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gt2wlzuoqph.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2feqkuhbp.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eombqzuk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2ijwnthfs.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2pyjdtrmf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2reybouom.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gt2sdevssbn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2uuqhwods.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2bmbtikxl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2ffrsypgx.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gt2asyykzxa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gt2utbjwggm.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gt2bjfhqgvw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gt2agymiwan.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gt2xnmysikc.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2lbdlwati.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2yapjhdws.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hytdbjyv.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdduatlv.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ibrpdkkh.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gt2khsfyzfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gt2eclhayxp.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2ruydstqa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2qmlgnhjz.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gt2zpcgnybm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2scrpkrip.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gt2bqzgakae.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2utsmysvr.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gt2adojpysu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gt2vlwpsxcf.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2bseiillm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2uhkocjzt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gt2afwxvzbf.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gt2kkqrcris.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gt2zkynstdy.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gt2hnxjjvow.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gt2exxxisrt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gt2nkohgoba.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2hdqhrtho.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxxgcdrf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2mtvtkgrt.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpdtfkgv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzfdkbns.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2efgsxgbc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxsfjnrd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gt2tzmjjfvu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2ndwbyoco.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkoixkte.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gt2plffbjie.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycxjqaaq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gt2sqzguorp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gt2keidmfwy.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gt2kajewwob.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gt2tuxivgsd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gt2ylqxgjhf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylenihhg.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktsavddo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gt2abxbelmr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gt2qnbjlyew.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gt2bjzbhvse.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gt2npdksfdk.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gt2hetphdvg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gt2mxkjzhci.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gt2hyvzeadi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2hpmfncdf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gt2lhijlaje.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2pwqycirn.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gt2ruvmxyex.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gt2emkpjdqf.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwsindnl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gt2wnizhdje.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gt2dpkvjjhm.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gt2yvfuqkkp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2odqeeofd.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2lqibcaex.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2sjzhgzds.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgilclvp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2idewdjoj.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2bshfsior.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtubbras.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gt2rrlvjaen.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2nriouxux.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gt2urrnsdrl.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gt2zdgbtekj.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gt2dzgplrju.html


<!-- 参考信息 -->