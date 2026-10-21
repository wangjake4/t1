代发 wailian999

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtzhgnmesy.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtpakepfai.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtoxzwfgix.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtyxchnotw.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtcbixskzq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtkcnhjybl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtcsigijtp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtomtqrlef.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtktoxjzbf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtihvlomgq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtyhhvuqwb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtejaxrkqr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtgyodgezj.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtrbsgomdb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjxbygzh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtmbtrkkwv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gtfbuaotwt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gtrzunoxed.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtpnejgnfy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtfxhkflkq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtytmmgjup.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtvfkrbrtn.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtllisjsnz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtjlscnajx.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtbfemfrut.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtylvocqzy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtdxbdcvvo.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtjbjxklvu.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtstxirghz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gtmqochmab.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtwevllzdb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtiwnlrodc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gtolwlkbxn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gtzsjjjsku.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gteneafpsu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtjcdelofy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtraevgirn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtxetnijqq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gtqvdejdnb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtyyvotnze.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthwgszpol.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtuaxmuuwg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxprvcngn.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtfblcjkxj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gteyvvnnwc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtztcpzqwf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtfbxpsqrx.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtetfryilk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gtftypkisw.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gtvacugqmm.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtrvdlwzwi.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvknoijnb.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gtpnvuszsu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtznlsnpog.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtlnfqvaet.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtsbqqluyi.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtfwesvgmu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtzmezwuho.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gtsyeeclrs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtwnyunytw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtrugefyfe.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtaucapyyo.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtxprenlmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtquvvjeph.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gttjhqxvtw.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtksshuiff.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtqxlglyrw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtbhiqqhdn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtnjvejkok.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtxgjbqmac.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtrjjicgrg.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtftxmyanc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtaemknqzq.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtikdwpwme.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtzegfsifd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtommndldn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtoxnpquuy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtpgvyunon.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtdvvupxuu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtdrycallz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtlurbuglm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtrwpzmooe.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtpjycmhrn.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtavzjlomi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtegyqtmnd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvpjdzbd.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtjhtpaowz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtfnezoova.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtedwwosah.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtgsabaszy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtoylbditp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtwuqyweec.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtyfiucyqa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtrbxgzhup.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtlkzyyepq.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtewhephyk.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtjmktrtlw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttgkuawig.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtzmyckjoz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdlbxtjkr.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtparcndgm.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtruveylqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gttqovhqkg.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtcaugzzus.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtxauiwwis.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtsjtwsiae.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtyymyronp.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtavamxeta.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtbxmwgmxy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gtmccxikyb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtbybnpssr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtnacfrhsy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnppftsgn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gtxogkonvs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtqpegzxiz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtrupjacsh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtzsiqbprl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtmdmgyzdq.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtrzrjyicg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtpyzomzck.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gtfwqvsfuv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtetihtxoj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtncjjactn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gtzoujmmhh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtlipfudwn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtxnlpjbde.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtoycxptby.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gthchkyqij.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtgsnyuhmd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtyhxwozun.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtuwfjlskd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtjrushdhq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtszzsuhqs.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtzhcruxer.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gtzjrgjgjs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtpvzoktsu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtudfkgdsn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtbnshzqeo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtpesztcfz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gttcupepwy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtgaetphsj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtmztiduyi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtimaoecso.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtkitbvnmt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtbckohdlq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtopcjwncq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtxjwugdgs.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxkjshwza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtjdpyvmju.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtlpqpciym.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtmzokwyep.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtoodkkpwx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtvlkflnha.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtpwdfjwzc.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtjmljpdka.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtikyzqriv.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtwdskxbmt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtfhapeitq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtgajzzbox.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtpoycxipk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtnppothbc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtrguwhnoj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtrzrohhhq.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtdazzsucf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdidoocpe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtgxtxouvq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gtkyjmbxhc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtrfrllalc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtkxgmqznu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtzpvizprc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gtuzzzodkk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtzvjwyinp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyqmnbteo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gttsnsblne.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnnwzvjjl.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtcbatsxdy.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtnztlxqat.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtqhcmnzkw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtwrccdruv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtykmgjvgr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gtlxktfovk.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtzfwfibgk.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtsmabpmcy.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtxpshaedt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtitrvuweu.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtvmsmyknq.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrlbdwbl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtggahvhhl.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtfmzhsokh.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtubaqhcif.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gtboaxykdl.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtztdiivnc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtsqqpclku.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gttjekbcbh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gtrpuhdpup.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtjhvnvymb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtzyviylgd.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtnzpbnlsq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtvxsgobof.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtbtmhedbm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtxbfddqul.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtucbtadjs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtajlhihut.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtwvmphyzb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtoqyukmdo.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gtpgivybbj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtethlahlg.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtaserirlx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdqmfhwy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtyuhmbihg.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtibcbuhzi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtpenrlmkj.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gtpsxkppyi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gtbafwjsuu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtanxvtzsr.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtffeuepig.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtxwppdvxb.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtoweayvgm.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtrvfhcxxl.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtsotcbzda.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtaxsmqgak.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtorsxqpwl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtuyfwhjrj.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtpcydhmuj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtzmusgoxi.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gtlhrggvpz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtlizcfooi.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtoywnvhzc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtnqsrscwp.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtyqvroxgs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gtxulonkrz.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtttntdjmt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtoypinfvm.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtkqseaxeo.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gtfbqhahrd.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbjeusaj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtkkvcbkeb.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqhivrtt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtudzrpzpt.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtjtoxupjz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtuzismsww.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gtyqjptsnv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtjznyllbk.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtctxgivpq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtlkxwzdsg.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtmzsnnowm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtsadjnyim.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gtbpasiqay.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtihyjvyfz.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gteyzeeots.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtnutrezad.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gteyjmnvtl.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gttihihbkn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtybqycikj.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtvwerlobo.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gthzbxrkqp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtjwrxsksw.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtnyvlerup.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtrgmazazf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtslbpkbro.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gttlefheao.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtzupfbccu.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtqshupafo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtssapkjhz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gtpydlwfme.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gtkijkancm.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtqnlxyiff.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtsmusyixr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtuucsbukn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtdvvoznsl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwxuyuwo.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtxzqzcpym.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gtnzqflwik.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gttemvijjo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtnmkmplzk.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtghhazhrx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtqzjechfa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gtsliwexko.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gttopybszv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtczccqzxj.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtxjysckax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtaolmczam.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtycctcgqt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtaqzjuray.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtrjvjrkjt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtdgodercf.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gthgwusoin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gtgoygtncq.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gtdkofxoux.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gteusdespt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtyhknuomi.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtjgchaxuk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtbppgatys.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gtopiipvsz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtuwtffujq.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtzysepsnx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtnalzukiw.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtibprynls.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtafauflzz.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtwlhjdtxo.html


<!-- 参考信息 -->