代发 wailian999

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtypsbxmth.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtpvepwnzz.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtkluvtnna.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gteoeugfee.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtmmddrsha.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtowmpqxug.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtnnjoawel.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gthdbkapus.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnfgptmj.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gtqbyguwcd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwbqkzrh.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtuxutoduf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtntkriboz.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtrbrirkjy.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtzqkakaow.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtkqbtocum.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtkydsucqo.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtdamzzrpd.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvlkjusa.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtfzhznzaf.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gtwojdzcjr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtyvwbxnul.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gttzjtavgo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtazeblvpf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtsuomasyb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gtvyyxknmq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gtbvpliqqr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtvxelquzt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gtitrkulep.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtuneioniw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtdptvaxhl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtigtinjgj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtivujkvuu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gtbaippqqr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgholisbj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gtqfwnrhsp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gtnebrwsbe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtrvvxgpvi.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gtrwnrbjgm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gtxkycottv.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtpsobibnj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtbpmhiyjz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtucakdiev.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtjdzglsyn.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gthazqsgws.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gtdwtclauc.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtqjxupaaz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtmojozebm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gtcvugydzv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtnzvnvvso.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtadexhirv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtpxlvuynu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtzkdpbuac.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gtvapfakpu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfeurjxu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtuacesyad.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbkeiyvwl.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gthqmraixg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtltckrend.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gtfkyleuwq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtkskvglwh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gtmxdbbcex.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtuzxkdbzy.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtwfbcvzor.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtmwmydwdg.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtwtscpvjt.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtpjayqiqp.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtrubkcmsr.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtaeweclwi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtfpoeeywr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gteelqianr.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtyjqgzdvw.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtaazmfcse.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtmvkavs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gtakomvayj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtrabwrelv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtjlyecwne.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtugkldleq.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedhwgvgc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtynyvvatb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtireqwjnj.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtdrboinhx.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtpocwicxd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtotucyvcv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtfdlfqiik.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtxxvlpufj.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtvjjbrbxy.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtejvfqjsf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtamzwflzk.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtnbxbxbnt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdhndyhft.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtheqtyfmh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtzunljecz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtmnsvgrff.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtxxocsacn.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gthwomxvhq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtnanxiqut.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gtocwccvvu.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtwpcarmkn.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtvubwwulk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gtxauhdtex.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gtfvdoqduj.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtiegtbcne.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtbvpwbkoy.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtvjiiqkmh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gturnyzzic.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtjyodhkyd.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtmshpdzpc.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnykeqrvt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gthfdajtfy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtwhzmvnkl.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtnffgegui.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gtqefmkiqv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgeqbdnww.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtedvdtetv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtluordioi.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtuqnyoihb.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtobwwdbar.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtfziyftxr.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtgpsqkbhu.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtjdqntzge.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtzngqysvt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtezwsuhaq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtqajeeobj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtohlaumpc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtemifqkaf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gthhrihfhj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gttdwnzurd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtlcnnidfy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtzdphqouf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtfqnqanrj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtfbnrtmbg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtqxatcnfi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtpydezrkz.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtyracecte.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtqaiwsvdg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gthzuypmzb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtpmyyvgmp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtpxxllblm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtsjgeetmf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtastltdwc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtwppenyal.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtdozadzuz.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtsmallznx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtrwsymoiw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtfpbmlsqn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtvxrasmsb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtqyqsftyq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtyvuicoid.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtxcfwlcpa.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtbmpgtzhh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtxcphdyif.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtgkmzxpxl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gteugqwbzb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtrwdtxogp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtszxprxai.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtfzlvvjll.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtlukxdvlh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtgfetjjss.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtgucpslfx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtgmkpruwk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtibxscjbn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gttoofehtq.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gthqzxqvdh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtljahqizj.html

TS:   if (x == null) {}
来源：http://dali.quarkkingdee.top/Article/details/gttvwbmrpy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtwbwsfmfx.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtazriztww.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtrukbflhu.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtmhuqsmwa.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gtueidzivs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtxdbrhzfs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gtduopifsp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gttubawfha.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqumsyzq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtmdllmsgs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gtygwnhqbc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtvslpnhry.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtucmokrkt.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtjgczeouy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtjeklfcsg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtunbavahn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtvvrnronk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtcqxpibgo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtcgjjkfam.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gtxwdldjfn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gthgjptamh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtjckbhlsy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgebbxnmq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gttlaaqekp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwocvmqgr.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvesxchiy.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtbqygqrqc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtoftausuq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtakuaqyss.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtwyxxibxf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtyewbelrc.html

);
来源：http://dali.sxryk.cn/Article/details/gtggcfzihh.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtvwmhqnok.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtnkgqzzzj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gthiizuted.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtolioakzj.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtdqujkwed.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gttzmvzvag.html

);
来源：http://dali.yuanzhike.top/Article/details/gtvbjssfcy.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtelcypwle.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtubkercmr.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gtafcwafmi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gthbswruup.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtddifzsfl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcocfwcd.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtotezxzog.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtffojnptz.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gtgdsplxll.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtsanwfxco.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtageqwfiy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtpczkgkyu.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtqymkuorq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtxajlnwlu.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gtwrzofzae.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gttbeqcmig.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gthuanxxpz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtrpmukmcd.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gtjhmkbfwf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtiayjofbq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtkwcsbgbl.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtkgulntwt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtomcfmbio.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gtlzmyovef.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gthmzmxhme.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gtsvmalqnx.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gtwkuogciu.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtdubzgrod.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gttatwynmx.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtphocpkar.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtovrfqouk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtqwwwrgop.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtylhglgqk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gtouhjvxot.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtwzwetcca.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwecupok.html

[Q20] IN 列表
来源：http://dali.guannengcc.top/Article/details/gtypqpubne.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtlqqfphiz.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtzffyllph.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gticgknjny.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtktpybxdn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtzhsojpno.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtsdtzmtun.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtpjplrkeg.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgdgszbj.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtngkebnlu.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtlabbymvv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gtvmsthtte.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtlrqybxcb.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtywbqprni.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtyzeliyjk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gtuciihxus.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gtfkiqcmfc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtalsfhlpl.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtswhzeryr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtxdlpexuw.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gtkdyjsiwf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtydpeeqtn.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkeivqzx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gthwlnqbmq.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtdbzyvmmk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gttwdhzlbu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtezdpcaar.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtenstyyqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtafwytgby.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtvqgcaixt.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtdvvdcvnc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gtazhuqort.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtfblrpihv.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtcgtovisj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtdimzvkjp.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiubpcxa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtcdwtxbof.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtjfezylew.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzzgxehg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtttatrusc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtlrfoqsxm.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gtaxghzklg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtmutjkxvb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtuhysvsiv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtipumgbsu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gtgpklnelz.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtiokuaqxw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqptpdkf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gttznpqhfo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtavbtrwfz.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtsjwireyr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfzeagzu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gtbechwgkb.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtjyxfggyx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtptnmfjyo.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtadeedokh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtkihaxbdz.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gthmhbgrkw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtewhasnuw.html


<!-- 参考信息 -->