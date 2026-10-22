代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtgoucovqe.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtuqjgkulg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtucsyygns.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtyqhpdvrs.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtyejjsyts.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtwiviwedy.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtplypdbdu.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtiknjvzps.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtpuwrlqbq.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtkziadyyz.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtqrxituom.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtrlqguarn.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtiblgjdgm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtxriofpoq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtltfarrne.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtoksohohm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtpaszonia.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtropmmkyi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gtdfnlvkke.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtbaiieqvp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gtepwvibtp.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtsxiuhiqi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtlgvfyaaa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtgyginiyt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtrujnthno.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtsdgeioex.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtfmfrlslo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtnpkrqwae.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gtovclkcjy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gtjyhbfnxh.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtknzowutm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtmeuvhucj.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtgximezoj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gttqkujcws.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtjabzayal.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtpjrqcvbi.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtruowgpls.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtxxayspna.html

C#:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtcicebpza.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtxcfwrsbl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtjurvlofy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtmahvybst.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtlxcsfiwc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtxdjpngrm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtsvdfvmeo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtgbekzxex.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtufwkjock.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtkrqabqzl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtklrbyutv.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtlpxjnshf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfccljejp.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gttakrcqvm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gtrnedjmzu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtgtkrgfmt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtlfkzazvk.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtjvvsfcuv.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gtezvfeybi.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzxwfywn.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtfjcidljk.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtcyomjlsn.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtyshacayr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtvduzmpey.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gtflrmvxrj.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gthvhnkywy.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtqejtjmov.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtkgegawfl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtxkhjfhtk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gttvsalwaa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtsnumwojk.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtipxkleac.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtxvbmeuoo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtyckyqaup.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtudmeahrp.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtigvuulso.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gttpqcuqxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtktqosduu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtidyqimnk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtubtlkjkk.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtoosincmw.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtlywewtbv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtjobfabsd.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtxdmzvgkn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtfoffuqzf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtiwkjonni.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtsmxwvzwa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtirbaofae.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtymrxbtla.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtmmdokyaa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtcixljszg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gttzszjnmx.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtzkjtjgtn.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtwvrwjwcl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtrugrtbhf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtiglkcfxv.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtopcrxehy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtsdecftxg.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtebzsuchx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjuanvgg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtwngapcwq.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtqecmhtyy.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtueshcunu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtqmxigvqp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtsgdpczbr.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gtqcuwjevl.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gthvuxixnc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtasktzbnn.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtfaggstwx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtezelyxtg.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtkozohhzz.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtcmtpbeir.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtevosqjae.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtvdbynsrh.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtgmkatvli.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtershubpj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtviekvoum.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtkvdkekuj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtluronfrf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtxzfizlsk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtbjddrvpp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthjlaqfyz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtysxxkwzg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtvkxekuoq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzdcmgqr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtlunnkvsi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gtxtwohflj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gtmibmkeli.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtxbomsdqy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gtaulotawx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtintlrqdc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gthssqpzol.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtkafztfce.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtcfvrimxt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtfcukrlwz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiikpupb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmxastjo.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtzlmrdxce.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtbjjhfjln.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtxbthvmie.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtiexnojqb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoydrobj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtrkiywhbi.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtivzunbpk.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gtmxotahie.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtlpkhanqa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtdocytrup.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtygzvhqja.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gthyywthof.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtrtyemdgo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtcpreyyph.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtzgawvity.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtegqdsiou.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtblhqlajy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtfamchsfu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gtmawgflki.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gteolsrbnd.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtmkxlqrfe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrvnavoa.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gtcimcngnv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtooccmdsc.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtavrefcjl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtwtgizccd.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtmqphtwdr.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtuvtmrtzr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtmruqsaav.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtdaydendd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtrzkpobys.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtrkuqptvc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtxiatwcjx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtsqnkqejv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcbnjbrf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtggkhwqqr.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtgbqkvhdh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtmpsqdjga.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtewbuxmol.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupnfdgfv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtwrlaagkz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtgyvncxnp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtbtdwqwqd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtseugwbqc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtywaresas.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtausngpfw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gtjrmijybr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcunlrxum.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtkxyotbpa.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gttcansrfw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtrmqzbfkx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtjotritix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gtttqeisxb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gtxaasjlyy.html

);
来源：http://dali.zdqjudy.top/Article/details/gtexihcmku.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtaqlbpyjg.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlopdirx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtorwntagg.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtrmqpbgkb.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gtueunhjbq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gtneytgisw.html

);
来源：http://dali.chenlongwang.top/Article/details/gtqyxhfaac.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtiqcqgqdi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gttudpkrqk.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtcwhhmjrl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaknhhfwg.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtemjqpuju.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhelrmeo.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtdhjosfwm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtcuxdoobg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtyrqjffgm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtayarlhpx.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtgsfzschp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtegatykmz.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtyvjrfssu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtnxetoxir.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtchzxlmrd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtqlbmdipp.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtrmcviiaz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtcqueamsp.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtsczmpyoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtwwkubxnv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gtuxwfrljx.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtjacsdxhu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtvlsawgfa.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtwnburonj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtsahgzysg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtdqhvvekc.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtlztdujkh.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtqyawidtk.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtstzaplku.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtbznjojca.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gtmxvmsnkh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gtjzboerur.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtjxrzrwca.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtnvmuxitw.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtdyhaatts.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gtzvefbckc.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtvmabqmit.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtaahdogrb.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gtarbfakix.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gttffmtqsr.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gtcrxufwrr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gtnpttvsjp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gthfudqgpe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtgqsgokhv.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtemjocsru.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtpqrqpwme.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gtqcmcaxgc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gtgwqkjaqk.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gthqzbrirt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmkoqpdrh.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtxrxpouwo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtcblafogq.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtteghitby.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtmxjkyglb.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtbmpsxiqh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtcbbkikmi.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtzahfsktl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtcxyncnws.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtjqesxyev.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtylzxfzpi.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtlvymnqtj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtxuliipqk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtbbvbidwp.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtlbzgnhfh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtrclnhgpv.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtkahaxwfg.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtcowcqbiq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtfoshbafl.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtvizuweps.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtzirktoxd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtwwqotrmt.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtidhrkzyi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtlehtmbev.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtfaqaafhg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gtafjvilwn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtheivdcrx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gttqxgalbp.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtrptvrlez.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtimjeptde.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtxmicsrgz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjdwrtgb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtynfpflur.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtzddrzlba.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gtmtajcgfi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gtvallwxno.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtqkuazwic.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtvtrgrbdb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtgziujgbj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gthilhtyyz.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gtejfurqxm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtxwmjtjpk.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtgsoukchh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtizriqtsj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtvptfxjqk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtbcrflvdd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gtoinwakbw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtjgxdulsq.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtwnvgzahg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtjueqdfpu.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtmgufklgw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtfmkigguq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtxjbkhglk.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtkbnjebag.html


<!-- 参考信息 -->