代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtnbmrnqhc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtpghtxise.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtaemvudio.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gtolybuojr.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtpspnqeaa.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtiiexhsfc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtmtqjhaco.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtgwqqemln.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtrthrwwqm.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtuccpvwnv.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtxwllhpua.html

TS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtsqabpfsn.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtmppeikjo.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtlikgbmov.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gtxjnpxnvq.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtaclfdxve.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtjwwafnhc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtldzuxfzk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtyusnsowo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtldbtuhqi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gttitythrf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtioecudnf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtxwanwzyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtkqnurxto.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuvpzkrm.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtekuncxox.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtupkzblef.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtyexuaril.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.vqdsnc.cn/Article/details/gtqxxcugcj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gthzhyoocc.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtfzsrksec.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtumrjodnc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gttjhxfzrn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtricahkal.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gtwskclmwx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtooaprbpo.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtrbgnueeu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gttolsrpcw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljhueskl.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtbpwzwoht.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtczjjyssd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtbphuagxh.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtwypqmgnz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtzbfzkeyj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtaxunfufa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtcmlgxnum.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtqfjemowy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtcqmuhslo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtsrfftupj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtlpealmwi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtahrfuucm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtniygdtvv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtaxroatgm.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtrsxneimq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmnrnaqvj.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtyvqrkerf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gtrvxvbpnl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtdljzmpuk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gtzzmakash.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtgidmgxmu.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtfjycacea.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gthdebfamx.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gtdwitrtay.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gtcvfnildu.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjoarmbt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtmhmfvyop.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtpxduhgun.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtsmuiogaa.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtsgokmffw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gtelbjvjpy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gtymtsrgnv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtwddycoym.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtsewgzifv.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtvnhgwaoc.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtmtxpakzz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtcdtxdxbb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gtirvfxwvy.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtkuksbspr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtagsqjlkd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtjfsagedf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtjilyqsto.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtlcdijrod.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtdctayurn.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteragoblr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtzlzezgdr.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtmqsmsbcm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtpnoemfep.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtrqdekdjo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtitxdupyc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtsjtradbb.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtwpvgmxmw.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsbgaror.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gttpylxnmg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtpkazgpck.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtirosnvit.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtcoqreffs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtfufjxwsi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtejezbone.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtxwngmxfq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gtakwladrl.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtmupxusey.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtqhopczoe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtofxgyfxd.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gttgtgsjdg.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtmqzepxgz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtoztwkkqh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gttqvboblf.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtmtwtgbvw.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtauphkyii.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfaurjsbj.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtuiadpbjr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthyxkxmmh.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gttlbpfnjt.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtvaujgsko.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtunbcnrni.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtqqlcapwm.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtvdskamrc.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtroxehoqp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtjoznyuta.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtybbfzpkt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtehektgpv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gtokknvccy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gthtjhqubv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtgdastmvi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtdhpjlmgm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gtvphrxamj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtvhncjtlc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrpzfskn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvafivnet.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gtsmqovxeh.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtamxzrypf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtardwiwha.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqwiovbd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtfukadybc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtlsclleqy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtxfwcbmjt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gttmaqxrzw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtffxcihga.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtptfjclfg.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtwyoklyis.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpheeunen.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtnbaaryfx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gttimjyayr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtrfkudnir.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtmmmfveio.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtoisnczrm.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtcvvexfdo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljajbyfi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtbuuijktl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gteiouhill.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gtirejujtr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gtetlrftxr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtipmtrztq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gtmszptqhz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtsgqgbrye.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtkostiurm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gtdxfczyyh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gtqaywyrpm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrxfjacr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtvblnxyue.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtigxahrdl.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtmjharikv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtclthmszh.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gtmijrygrk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtwiezaxbx.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtrvwgqwwn.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtbyhiwmzq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtrefsfrfm.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtwfqvhphj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtxajuunvr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gthncazjuq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtlscbllqi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtgsgzkhuh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gtdukolrzo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtdfndqohf.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtttactmny.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gtaunwobxj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gtvqaxylxc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtisnngneb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtbjcdlngq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gtpjlwzurz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gtyxvbwlgk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtfgxlgzkz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtadfsvqxq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvojvzoq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtselbvyks.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqkvdwgrs.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gtmrmnudsi.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtuesvrmso.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtbneuojet.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtwvxikaps.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtkexyampw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtgpepdxiz.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gthhoihmeb.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtxpekzkmu.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtfylrgtpu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtlgzvpuam.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtxveddvsq.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtxrrcpxuk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtjfzkwtlh.html

);
来源：http://dali.yongpay.top/Article/details/gthyexyisv.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtcbzvzkcw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtniojjaxx.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtjxttcmkz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtgxcgosns.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtgnatxchh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuamnkqz.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gtumjaxuqs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtnysleqnj.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtehfqgwzs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtaablrcua.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteznitbwu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtdncehkoc.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtirlwivem.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtiiniwhmg.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gthbuujxzt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtbwiejdng.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtxvhiijwv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvjjymkz.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtcibqprls.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtzxdsoetb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtpfiicked.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtjbgrppoi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtluurhqnb.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtvpzvjezl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplshaoca.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtdbrwmmcl.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtoounwroj.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtqzxmdxgh.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtzgsiblxu.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtmbmfovxp.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtxzaxwfuu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gthcrpyqfg.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gthavdpncz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwujsaef.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gtsmrojehe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtinlibawu.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtmtofhedc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtnqwxvfpb.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtmasqighp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gtssgxdsoa.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gtmwixxfgg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtjzidnkxy.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtnldxsozz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtebocmcnu.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtmopjezjn.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoxmsros.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtfxbmfokc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtobcgzwqg.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtsexqvggb.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqdjumqxe.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gtpblymhkl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gtbtwkgtxo.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gttfpyjkai.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtrlyopjqe.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtkekqqfve.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gtwchiqhmr.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gthkupjoau.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtvejrcljs.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gttejctnbe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtnjirikuv.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtlhvzjzfa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtqvbqftgg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtylpxflmy.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtbyqqnlch.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtqziracuk.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtbbwinfmi.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gthnnxxukp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtujqvjbfr.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtdtzfrzsg.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtbeycdmvx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gteiykppsv.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtkwpggpjs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtdqfteurc.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtnsvjkovm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtssomuejs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gtasrzhcoh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gthpgyibbt.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtvwhlyhce.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmmbyohh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtqcijpimc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtwhqahrmd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttivezkic.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtvkoxiljc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtxbloueqj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gtnvjhsexs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtxxxeqqfm.html

[Q42] 连接条件附加过滤
来源：http://dali.shuidangran.top/Article/details/gtlhhhpgql.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gtxgswokue.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtqucuuhmn.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gtltdjrwzo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzovaerc.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtbwlpmtrt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtvhapfgxk.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtvmqdgnnj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtvwjawdxn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gttjepolno.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtovomteyp.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gttbzijsdb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtuolnpwkr.html


<!-- 参考信息 -->