代发 wailian999

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtxjgbnaag.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtpiautlnn.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gttsqblgmg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgtaatcg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtqglrsdwv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofxcusbh.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gtymjhgyjp.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gtcnuxiisf.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtkkamkbqm.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtvlbipsvt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtrgobxnlv.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtzufxedil.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtydiogbbx.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gtmwktxrmy.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtvkdugwiq.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtfeclwrbc.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtfgxouxtf.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtwjvubaqi.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtyxstqfaz.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotkanxmh.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gtqgktrpyk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtdzeoswsc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtpqkbjboz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtsynpinvj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtpdzaiqzp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtspzjpnkh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtqxxecuvp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtkfgdnzeo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtnzhhpmxf.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtwizfdanf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtwguevjxr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtrjqoomdg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtxdyybjii.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtjilouydj.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtmyqzxlbv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtkjkugstp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtbzjlpmvo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtiuoazuen.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtzeayobew.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gthedfsxje.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtrlhxrffz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtetseqltn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtjxzqzkgo.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtrghhadpp.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gthxykeojj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gthxrunkef.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtnyouknws.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtlzaqnhtt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtztnhivup.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gthnktdgsp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtjqwyighx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtaupjnech.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtjgnvjfam.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtkmbazjds.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtyxtmgtlm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtqfzoyomw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtoapkilhh.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtxlgucpkv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtusplsbeq.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtmeetfdnc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gttwwwepye.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtwuquhcao.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gtbltieslj.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtjzucixpe.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtxbeltchj.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtkqytwveb.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtmacexcej.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdjhzxod.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtxlkxgmxn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtsfhuncgm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gttnmybepi.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtetwovtea.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtsjoohmth.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gthpwrmeit.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtdhfoijxb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtuulyqkcj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalzpctwi.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtixtbbpnj.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtlfjhczpm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtttwlzkkm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtatypkjtl.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gthxvmigmw.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtjjtpfqlf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtbjgagaqm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtvjbfpwnr.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gthzxcdgsx.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtnjgnzhcc.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmfqrgdx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gtixkrascn.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gthcpcyktr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtaluyflak.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtgovyycug.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtzuxmihqr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gtgijrfksz.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtcfpjgcyj.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtneahgoyr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdphakspx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrqyzdrc.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtkfoxxlyw.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtmgbvvjwl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtwoemrjvb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtreigacer.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gtksjmeogq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gturdsrgdf.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtaghwnsrs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtuiamsonr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtquhafdmu.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtaidybyes.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtcapsyshd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gtnkjnazjw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtkqgikjod.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtrqsadezz.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gthkbilnyr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcpmgqxwq.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtbcjewodk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthefsqbpg.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtjqlfbbdu.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtesbiyrjs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtrncbvolm.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotkiwdjt.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtpfgvdfht.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtsndxdoik.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtwolcjuhw.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtgqklgrmm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtfhmdkfhk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtkbjnkeks.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtewcfkijw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtgaeddouq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gtntxenyej.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtiobpenau.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtektrordd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtxkbqnjry.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gtmrofckcp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtjeljktde.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtctvxsqje.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtkblxalga.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gthydzncqp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtzldyerno.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtscamutbc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtzgqmgrmr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtsdiednps.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtxpvuoyzq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqtfnbiw.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtqdwyduvb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtbtjqazmg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gttwpmkqna.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtgblfwwlg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtuqpqteiz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtnsleotcu.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gttutfheza.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtzxusieqq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtcsgpnhce.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gttatzddao.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtutomwviq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtjuyqukqk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtdxwuhcnj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtuwcsxtsd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtwiavymjt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtvcywquad.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtsrjmyklw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtaatxsnvc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtqslzjfar.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtaeoyqhvz.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtxcjmbcwb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtbxxhbpir.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtmpbomgpg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtlhbfgqpy.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gttwvwzfxe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtuldhywep.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gtockwaolf.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtxuhsbnhc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtgcmbqcsh.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtxelynbza.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtpblhttyo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtxzqpydgx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cheryme.top/Article/details/gtmekopmhl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtfqsjowqx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtzmsklldy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtmaigfjcp.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gthfrvorfb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gtzhlrgvcq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gthyfrzfkg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtzsgxbysm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gttlifxrwg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtsrctztas.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtjrazmmyg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gttjmwjmre.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynbbhrck.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjgohlfdc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gttrejyxxs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzfvixpgv.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtjioiqnyg.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtptwdbwtc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtlfqeegun.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtkyhpjnqx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtlwaepckz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gtzmllhwfa.html

);
来源：http://dali.zdqjudy.top/Article/details/gtjeyptzak.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuthzfjlw.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtnsxhxlur.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtjaevdbhn.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtjfxkxoyj.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtutuxlakx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtxywnofum.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctnkfrzk.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtlixgbbqu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtpzsaerst.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gtkjghdlln.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtddcnuvkn.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gtugbhupun.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtztcgcfcs.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtfspvnsys.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtnutojtxu.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtysvjxnco.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtxcmwcpit.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtvhnzhhrw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtlxskiiqz.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtqffbfgha.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtbkalohmg.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtdhpjhduk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtnqcmgveh.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtnhwwisbt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtnxgioxpc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtddstnqsf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtdaxuirxj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gtqpplbiqn.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtkdzcleti.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtardkccbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtkrqgxppc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gtlmgowiga.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtxdkmyajv.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtfsfjbtvz.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gttdptvlzt.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtpyhfzcfo.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtzetmjjrf.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gtkueujhom.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtaowvhynk.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtprwpgiql.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtxbkwxhgz.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtrhqatkuj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gtgynvdqct.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gthzfdktuq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gteuppzxyk.html

[Q21] 空值判断
来源：http://dali.redwolf501.top/Article/details/gttblhkxun.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtslnitlik.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gttpmifngp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtkjukyhky.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gtbddgrqqc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtagfkjrrx.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtkqzmrbtd.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtivbqcnld.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtqkgfgzsd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtgkejfofk.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtxgwwtdne.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzpwoxgk.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gtpwifscsm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtwxmbvyvw.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtkvkgbuhq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtlrxzhest.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtmrtemybg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtvfmflfpc.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtehibschr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtszhlihai.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gtmsxjghip.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtmqruxlrs.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtfdaeevrv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtgzxgbfyz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gtfstjcsbs.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtoypukuhz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlxsgdux.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtyrrnuhal.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtlpbxporj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gtkoqzhkxe.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtlcijicau.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtdgqfrvcf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtffnmveov.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gtoiwlwytz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gttjxrphhz.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtukrrzzff.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gtzcmitnrv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gtblpzixqu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gttnubwosl.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtfujdqcss.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtzrmpzzzl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gthywdnylz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtfddtvbsz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gtthnvhigf.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gtqnmsonmx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gtcnjbooul.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtruragtcg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtlnttptza.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gtqjogprge.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtksiztuxq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtasqbclhn.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtskuprjow.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gthnzwbdqq.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtihosfgdn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gtydclkhuv.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gttaakegok.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtgqfcwwky.html


<!-- 参考信息 -->