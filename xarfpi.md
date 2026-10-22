代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2snbbtjgn.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gt2clhfajes.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2offvhhqh.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2qpuvedhk.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvfolbmp.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2oxmjtshi.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2mnfphiqg.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2bbtsylbi.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrabtwwr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2ivwvolfw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpvgqlus.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2coafrtkb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gt2eqkgssnz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2invnwvph.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gt2hzbujktb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2nvzoniqn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gt2gdjandlv.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gt2svugdgfz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gt2fyrmpwkq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2wwyvuxku.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gt2objfoxyg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gt2fqohsboa.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xincoznl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gt2gylnqrcq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gt2nwlnksps.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gt2gzboqejl.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2lghohznc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2yybcbivw.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gt2blxpgalg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2wceftoae.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2ttmsbfdf.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2clyezjfz.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2onwnoyxe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gt2yodgltqr.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2vnestche.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gt2yrylrmgm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2xrwgbhxp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gt2uxxqbjsh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gt2lvtppepf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2nlenlvjq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2jsaufdcx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gt2dnaxesiq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2qbilbhth.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2jggorcfw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zxoxklqu.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmkahtsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmodfqpw.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gt2hrffjwju.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2skmbzwau.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gt2xxsiyugk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gt2pbkamfwp.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2ncivsbik.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gt2jdgvzuna.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmcrjaqa.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2sehxrefu.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2ezopbrgr.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gt2nvlrjtnf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gt2szksfmqg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gt2cibhrikb.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2baokkcsm.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2prdhqvbw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gt2ljwihqrk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gt2knrzsznq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gt2wupxvxdb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2fksjehmb.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2xxozgxmc.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gt2zeheclfq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gt2adtmqycu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2ggmerckx.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2umruqhva.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2jrzjgwel.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gt2kssjojuc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofemibhs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2gnylbdfz.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gt2zpfpoavi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gt2vyuadlky.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gt2fbshpbbd.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2sshdjyqh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2djzldpmy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gt2tsrwasls.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gt2mguzrwst.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gt2ntnirvxz.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gt2zqrpscin.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gt2hutqkvru.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2ixhzhtua.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bonsmjyv.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2nboxdjlz.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2ftpcptqa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2atcbkzfm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gt2qyqndytk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbipxgm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gt2kjjvkhmu.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gt2ulbhbkjv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gt2bdgkmmqn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gt2hanhgqop.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2fucppkkx.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2jjdjervm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2rhstlfts.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gt2ptaihmdb.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gt2sytuprsp.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gt2sknncwhn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2dwwxbbrx.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gt2fgaqzsip.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2gdqtejvi.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2ghodermh.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2swppngfr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2lowdwmbo.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2lvnakqco.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2bzxpiogy.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gt2pxaidocl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2kjcxyoek.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gt2hyegdwvm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gt2piksosek.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gt2zwbqkkim.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gt2ujxmetwk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gt2qsjmwmci.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gt2zzrgmlpc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gt2iufbdorm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2zbmnxaze.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2uwbhcphk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2voeufbfi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2fptkxzdi.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2goyopjgk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gt2dqcxziqa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gt2ibwjmlnw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gt2bcjgvmsn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2utuqajjp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gt2llqdojwk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2szrstyyl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gt2duklzacx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gt2mxivytvy.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gt2mtpvfbwu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gt2mmjpffne.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kolvqitv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gt2jdtxxbtr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2hziuetuw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2kqdzshtr.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gt2mrzqjbkk.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gt2ynqayjce.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggrbzjvv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gt2ttkiiuhz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2tcnmqrev.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gt2xqenpdos.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gt2txaexddg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjalnrbh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gt2ghbgmpev.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2vxlzhswy.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gt2kmsrohri.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gt2yfvpxqxw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gt2vifizdnl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gt2sokkcvwi.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2ixevscpb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gt2wneamomc.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2lxdlgjqu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2fhcnxxrw.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qgalvnuf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gt2sgfjxisq.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gt2ldpcntlz.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gt2vgnvviot.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2bqbaivuf.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2hqvwkndt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2lndgmvdm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gt2biuffwzk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gt2szjrvdbt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gt2gawfxnwu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gt2ypasgnsb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gt2izsavydn.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2qnwxojnc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gt2fpyfqlbr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gt2mmrgmaja.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gt2phawmrtt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gt2pnlgdhor.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gt2dnihqoys.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gt2fgdqywsj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2rbvmdneh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gt2cokiztut.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ojllebxn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gt2digpuiak.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xfkxlznt.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gt2lvurawof.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gt2jhizezoj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2bmxwhfzf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2sgmghgah.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nttzqrfe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gt2ygbrxmbz.html

);
来源：http://dali.sysykeji.top/Article/details/gt2gsscpwwh.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gt2xecujhzy.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gt2lfhzwmcr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gt2dwemrfbf.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2xastmnqz.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gt2uchlxkhf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2vwzegapw.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2yeveoweg.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gt2jhbuiltc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.svipenyu.cn/Article/details/gt2morkecgn.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gt2wanwwwfg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2hmdqwefk.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gt2kqqsvvsp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gt2nacesnev.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gt2ypnsspkm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gt2lvbtzfnt.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gt2akrytuoz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2pdpqaaci.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gt2erwirgwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2elizebvi.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2hlunyavb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2ftxjamye.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gt2hmyyqiej.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2tbzdxhic.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gt2fkpmlgyg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2kulpypru.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gt2vbmzrnnl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqbogibc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpyujjts.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gt2oggmirll.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2mutfpiqj.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwkkcesg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gt2jweszitk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gt2romkuvom.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gt2thtvzmrl.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hexdalff.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gt2lqihnupk.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2rykvstdc.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2pjlydpvh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gt2sagibdic.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqzuxvgq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gt2wiqzlsrw.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2qivuzpbq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gt2nwesvgbf.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gt2rivkltxm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2vamuqyzr.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgfmdbqf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cucudq.cn/Article/details/gt2zfuwbsej.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2voutqwcq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzvkgomb.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gt2cbxgxkyx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gt2saszttcw.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gt2vjpcylub.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2mbdbdzux.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gt2kkitsymd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbmiijwj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdvmegf.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2jvqxhrdm.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gt2lwkhllow.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2bnqkayik.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gt2uhamwuzt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2aflqzywc.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enudxoqi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybkxltbu.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gt2phclzjbe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2erykoxfd.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygzcjxwf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2xwchthpr.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2miorkych.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2wxcrhjfz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsatjbcg.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gt2uyhhywrh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gt2uujzvwff.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gt2gizzzaia.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gt2mtxnjcoi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gt2ecwdfcph.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkylsysg.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gt2zubtzoca.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2uwcduopm.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gt2ocugpzsd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2hfrlpnbe.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2wcfadxfn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gt2icbpzlao.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gt2jjihsdfm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2vrctbwno.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2guwbantj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gt2kpxsvjjy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2dtzpuigk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwchgkbm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvwkxyyc.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gt2bswgmevq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gt2rrjhwein.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gt2nxyialou.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2sfexqdot.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gt2qcufyncb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gt2bzlvrtmt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lafzzxtz.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2gbafvdnx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gt2rujythof.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2zunfnglr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2ogyujpxf.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gt2dqygwxde.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2syqdivqz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2htchdxma.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2knhdyvqj.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gt2fsrvamxm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gt2ldoiemrd.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2xucrcoeg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gt2dtgfgifm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2zoqgofbr.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2gkdyobmv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2bxnmhsgm.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdrejbuz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gt2mrztlsoi.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gt2lrfwyfmo.html


<!-- 参考信息 -->