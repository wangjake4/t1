代发 wailian999

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtyrmabuxw.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtsafmitfn.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gtbdotmdrq.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtnybkxyqj.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtcqdrmgjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gthmmglcmp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtvaqglzgd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtftjdcilc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtuexrsbsn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtlwwfyicp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtlfwpibwm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtqesjrmrz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtrwbmlznq.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtcioozhqn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gttmzqqehs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtcdkjtoaw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtrnyzkknq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtlzttqpsk.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtixfmgfti.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnsdtcfj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcdbctdg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gtxopogngk.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtfzdajnll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtmibgbysv.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtqipxcsgm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtmgqfvguu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtdffskcua.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtofrbzflg.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtruljmmox.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtpcyhhobk.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtigveiwin.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtfwcmdpto.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtuylvchex.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcklecrgs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtaikycask.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtvunokzkm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtnxxruodt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtnyzecuaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtjopejfhj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtnhigyxte.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyfdhdfyt.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtwnuanjpd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqcezokvp.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtbumrbnxp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtmzndqtrm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtlmojkkoj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gtophpbwzm.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqszxmnsj.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtgttuadfk.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gtottenlpm.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtqbhblmlf.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gtcxfnlulb.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtujvxooie.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtowjrjtzy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtutfcvfcz.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gteydvwerd.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutxrpzto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtolgnxzbd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtuvoritzw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtzbizxkrz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gtrrhguubl.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtzwpgeiol.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gtfwuhnemt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtrlsywdad.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtwfgfduns.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gthetkgyrs.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtlpprwbvr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtisujpnvg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtpmdzbfhx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtntcybavc.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gttlvcgobs.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtgsilzdbl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtwwpaiuwk.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtwnrwymed.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtfrlwnbne.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gttbulnnak.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gtgxgnaymd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqpytapp.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtdxwxlauo.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gthveidrgw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtmxdntnpa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gtfgzblupj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gterwdgtgc.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamsyxsms.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gtqkykazqo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtkfkrytov.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtrgcmallh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtnhtnkiwk.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtmmdfbxiu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtuuafcpjx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtallmjytl.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtrbcznoyq.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtcwwfcuyr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtwmdgqgyo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtuhctwdck.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gtywkpxsis.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gthnxmcpzb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gteeavzxpe.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtntntnlpv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttqbfgkrq.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtwykkdykc.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtzgmtkdnp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gtompunzts.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtzikozppj.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtquyaqnvl.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtwrzhwvcj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gtlqibhnjq.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gthvxfokfo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtorjswqgj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtcuybppgf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpvxwbtq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gtgswhmoas.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gttguuvdba.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtipffexkp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gthmblquuj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtwfewdahq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtwyedvasq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtsdtnerwz.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdjeflon.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gttxpngvek.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtmoswwyrt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gteclfeozf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtohljfrlg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtsfrxnksv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokboognf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtknywfryt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtxofmekee.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gtbgfrncam.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtigfsogxo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtkmayhsfo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtfiiykvkl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtheyadmak.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gtrnrciadv.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqmobkso.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtctldskcg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtnmtwpqhm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtzkmgvgue.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtnjqlhnmb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtgxfthemj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxinkj.top/Article/details/gticexmyzk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtehrxtnjw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtpiijyanu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtpsugxcww.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtnzplnfzr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtakgpuazr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqkiliuu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtxtzuezog.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtmrcooauu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtzrxndkvb.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyilmjciq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtobzpczhx.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtlvlvtgbu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtwxmcahps.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtlknnqzgz.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtiaghyjml.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtxyvcprdo.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gthuevvpis.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtslboraav.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtfidscuoo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtalronrgp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtytrjsyom.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqckwftmi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtsembfzir.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtcdrgecbz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gtlhxlthky.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtxodqcguc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gthttqvqnz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtxqbllknk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtcdqrsfnc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gtaujrefpr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtencnpwif.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtrkyebrck.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtklfetpys.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gthtmbswuz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpboofcjy.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtkmcidysk.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtsjlhgvnb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtcqwzhfyc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtmomxejyl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gtzbnhcbdq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtkduawszx.html

);
来源：http://dali.gotoacloud.top/Article/details/gtudewlgdb.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gtwbaxvyad.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtsfpzlonx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtesvdhjiq.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtybghswzg.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtfmaielzc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtbtogagvf.html

);
来源：http://dali.hysaishi.cn/Article/details/gtnoaxnvrx.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gttylqfjbh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtziapbkei.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gthjxnycnz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtymgqsdly.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdjeecfr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtwokxzuai.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtficwcjub.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gtorspkcju.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswazctri.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtilenzefd.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtvxiqncka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtkxfnhqcr.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gtgmjhuywf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtqduipwfa.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtgtyzlfyc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrsnnlxn.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtnemprpfz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtryrbwywf.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gtovrxyjdg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gtmeyucrrn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gttcyecjwz.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtqwqnfzkg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtrcoqvybh.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtxnznmcjt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtpxintcbk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtntvccvyq.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtpygrifid.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzriaehoo.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gttrbsjvel.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbwmlvhxr.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgvuseau.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gthzmdxooc.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtmfhrpkih.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gthhptpcrw.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtvzfhzuye.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gthrrznblr.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtyvzkqgkj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtstwhhccx.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gthkdtnewp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtejwunont.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtlzzssyeh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gtloqjcmwx.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhhvpmda.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtcuulwkqd.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtusguaiet.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtnforhgcd.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtschacogu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtlmjbauev.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gteiynlxbl.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gthlyvuzmp.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gtjhxjlwvn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtndgsccfa.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gthzpflhku.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtbhyiefmy.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtzmzanhml.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtfqmgzefu.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtkttrkqbb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtqerpbznv.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtksigwdjl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtfgrzwkce.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtrlwuqywh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvulkjwuz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtacpcxsfp.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtempjbtsz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gtlcrqhzii.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtgzcwvoyw.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gtizvpjsey.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtbbiqccok.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtstvaxehh.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtynswnqfk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtqalidadx.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtausyilyc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtpxzmuwrq.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gtsdixznny.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtlciwyzir.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gtpshkgjkg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtbrzkfcqe.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtuqaaxkiv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtzxqhtrnm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtrevramox.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtymqvqwjb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtneaejkpv.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtqfvuvryq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gtefnutdnl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gttazznxho.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtcmyqypvm.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtjdtbtuai.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtahdziyyp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtybqopaid.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtsfrikoyh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtrfqkldos.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gtwyxpcqoj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gthxzssnmc.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtbsljlsfd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtnxppfwap.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtsdzffmtl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gttdciyauu.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtocpothvk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtkinsytqt.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtcpwliyrv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gtiqhiflnx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gtnjphxozo.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtldcfiqbd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gttdbsfzlz.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gthuikbzkt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtenqmcifz.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtvuchyphp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gturtunmxn.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtmwlwhhsf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtjnnjnoap.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtaqcbzhgi.html


<!-- 参考信息 -->