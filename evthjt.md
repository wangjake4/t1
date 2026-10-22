代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtfflcstla.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtmazpxxnq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtalruvfsy.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtsycygpcx.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtbbzehfcn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtbdrkrjcb.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtyfcdihnj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtbiryrwdt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtveqolbwf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtztvluywe.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gtdydaymgk.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtvietyqvy.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gttzswdqcz.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtrithywpy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtsvszbfkm.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtfkayhdlx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaeyjwvi.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtfdkdtckm.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gthxafbjqb.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtievsnxkp.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtlccjxjpk.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtobasiurt.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtdssfgtwr.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gthirmydno.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtymuddutr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtdnbttcsl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtnngaxkht.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtygoimlpy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gttgoxeevg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtrljquvxb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtlrvgpngx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtikcphghl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwzbekoj.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtuvozyhbr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtzrlafztf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gtybujnhzv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtfnuebykk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gtaoanewta.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gticeaygnv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtvrjncbqh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtorlsdoxj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtakyuzphj.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtqawfhwiw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtzqqikevw.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtleqwdwuc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtkdadnrrl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtkaxnrfzt.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtbuwgpyjm.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtcpuoytoo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gtjumrbqxg.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtkqujfmdz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtlzfwkqvk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gthcxvoosf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gticeenqwc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtygsgmuwc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gttuxmmvxn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtllkvvgvt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtfvhjqooo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtvelwgqeo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtjsrlfxsl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthhrhqyin.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtrtmjzrcu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxbendxnh.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyacuedv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtngudezry.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gtuowukfwy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gtpwndcafw.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtscikyzhf.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtcnanecxx.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtdwuomlkp.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtneaevlfd.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtfptpqzbf.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtaopvowzv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtckoqfbfl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtfycqbndl.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtcajqgvty.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtimccahgu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtgebhwidc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gtrhtzeaia.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gtgsoatmvu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtpsyllttg.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gthgjhtflk.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gthbkmqldg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtuwedgyqt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gtzlwdezkb.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypvlmnwe.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlrlwdmek.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtpnuhcfql.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtllyrdhdg.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtgfzqgmmy.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtognafibl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtqkywtekd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtaaugbbfg.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtvckihwpg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtkhgcxruh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gteccwrnew.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtrsucxbbh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtajkwqthe.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtgeeyqfuy.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtmmgkalpt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtddnpcgar.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gtyvgjouvn.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtodxnfzhq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtihjbnfax.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtmcyswphp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gthamnfwwi.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtwgtdnbdq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqzbsjix.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gterfvpztp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtmkucwtqh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtqrylelwm.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtgaljyhbe.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtitdjpkev.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtvfjxoqlb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtqtaifsdq.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtridiloah.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gtvzthpspi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqvwoslad.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtdvalpsqj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaqenvjki.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtladbzcrt.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtqmntuwwz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtameavqty.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtzsqibrkb.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtmwgnergn.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gticyxwgkn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gtfijegkxp.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxmcdssi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtlkfakwoy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtkcdincnj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gteupqtqem.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtrpwudpfo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtonszthmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswiufubu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gtefjbunth.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtgmdqcjvi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtipqiepmr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtyubullpo.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gttbizdxgs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtshyurweg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gtvzlnydjs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtgsktxgir.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gthhvzhaeq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gtctlxdmql.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtxzlsqmvu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtdsljbepz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gthayoozhm.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtfabhsvaq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gteefafsag.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtzrzznokl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtqyvlfkhg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtiynbqjqi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtyerbrhoi.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtckgmhkcg.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtzuxhbxkw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtxsxvaatm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtmpbscyuj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtcxzxnczo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gttxhmxozp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gttnoazjwf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtzxtrkmqc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gtdzijadil.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtyzqozoyv.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtfvklezyy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvpoinyd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gthynhkkgp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtppvsjqms.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtfmibanoj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtfjohukbm.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gtmiscrixx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtesjypjgz.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtmprxmycg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmbdartl.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gttlaifrrc.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtvkcoxxkp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtplqukigz.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtzgwskghe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtwuwkcwew.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtuokvjzxi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtomyyonnn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtuxaxubfh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtdlzchbme.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtijtesqyl.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtyhpdpweg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtzbbgevbg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtozystler.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtonruikoc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtcvcjlbkx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtrrbxsuuv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtxqwgrjba.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gtzmkxngql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gtlmtnddqb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcqebhkdm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpsgfwgu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzreactlo.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gthnabactl.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtsinsngtm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gticvrcrvf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtjrtjqjjs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gtcktyjmuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtyvzfwccp.html

);
来源：http://dali.bjfxy.top/Article/details/gthymxuedn.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gtfnfpfkcr.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtltfzlwnf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtmywnbewg.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtrdpbmsvd.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtzlqlqjbg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtdquiusgn.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtxlzjyrzr.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtwkvqaele.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtccryxqaq.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtcjruxiyf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtdxsyhpqz.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gtlegsdwxy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtooljtcbj.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtsqblhfiy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtcgpezdor.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtnzgaruyn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gttwevofhf.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtbikbuayj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtrdcysmww.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtiaaenbgt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtpmmgskue.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtqrvdtjrx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtvomuqwur.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtluciviwo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gttbejrbrj.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtrcsweias.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtfwsncqet.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtxwchnzio.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtzacoljah.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtyxjuxdmw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtyrwdyigi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtanejwzdc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gtlppdnhzl.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtjzjncmgq.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtemkaanmh.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtjmzumyvn.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtmtqlxpjj.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gtywvntgem.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtcqucltld.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtykjpbdbv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtvtrmketo.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtotzuasfd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtogcakkvq.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtcngyeivr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gttnranfek.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtgwwikipn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtjqpvjpcl.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtvsainzai.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtydyknulg.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtruycanrt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtufidghei.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtwygubowq.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtmsmefxii.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gthotdqpst.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxkjuxni.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtlxjkvgjg.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtccebchcv.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtstxfzejy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtaeexsbrx.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gtgtxqktme.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtqqeljage.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtzjitmfmp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtzbhujnzr.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrhrtjws.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtgetkhkvd.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gtwommgxmj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtvwzkyqzh.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtfbzzbysh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtzjpeytwc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtmgkrhgjd.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtuvwvyvaz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtxcrxxupu.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtznaqwbim.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gtwdlymfvy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtdopbfduu.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtexfohdqz.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtyqocfalg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtxirodhah.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtvpxzgxvz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtwvaywscf.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gthejajomq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtwxlfxxiw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gttsgirene.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtsfgnzabx.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtyfbiuvza.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtldainmdn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtvrhbswqe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gtdsidislb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtcisfghmc.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtgfyqutow.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtlxeleywv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtnyujblwq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtucfiqjkh.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtgfqvrnhy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gtesxzopaq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtebwvdrgu.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gthnbhxkck.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtsyaxivcy.html


<!-- 参考信息 -->