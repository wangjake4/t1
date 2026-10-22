代发 wailian999

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtdyitmhbd.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtrocacvdy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtpqcvfyjr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtfibhcbck.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtmtltmjso.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtwjotcquq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gthdmbszar.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtieokqlta.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtyqpfarsr.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjvxxwsah.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtpuicbbsz.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gtuojzoygm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtxhvyeqyc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtsuassszw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtgauqsbek.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdukmsau.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtxnfnfrjj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtrjdzsjhe.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtgjmyuejy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtafzlhkvt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gtgxxgbblm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gthmnmclvn.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gthawcbkqb.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gtdfwvxrxd.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtmdipuzlb.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtfspndwzs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtbuodcfap.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtuujvxtvo.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqvkotdyx.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtmgqusebt.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtmqlxdqkt.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtbhdftsvi.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtcovivkfr.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtgasigfag.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtsdqvjrih.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtwbewfzlc.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtvpgskppl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtmiqgmxio.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtgfnqekvo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtmvzmzwtw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtqbmrfuoz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtvsbhfzuw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnremvoh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtzcnqunvk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtnhujnnjz.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtoxbxzfsn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtovrflgtj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gtkqvceqws.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtnofavfij.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gttwmahzma.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdjfwcwhw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtvifxhick.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtcnqrbuvx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gtforycblm.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtvsfbtocw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtfyfbdrzv.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtzdyhetsw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtplgndvsy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtakwkmvma.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtdkomgbzv.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtdcygjiih.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtdysvyagl.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtfbwfjiqk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigufen.top/Article/details/gtcyhoxoxb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gtnurebufe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtrgdipjll.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtnnyeakpk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtysdkrprr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtuoseevcx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtkseluxej.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtjqhgfhex.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtqwengzex.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjqdhlsjk.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gtvpgttfkc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthgmcyvgy.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtesdijlyw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtsrdzspad.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtwprsutnn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtbxzatsvj.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtnsposfup.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gttaulzenl.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gtuuqvhkpy.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gtwbkgwnyo.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gtfesbiqoc.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtzvznrpho.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gtuaocxnev.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtdjmlvlui.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtgnzbldvs.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtmxmmbhhu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gtzryzvjbn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gtxcsqjhze.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtgnamtbsq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gttcqwhzjj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtuiyftfgs.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtxjnlntco.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtlutopxty.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtrnmyuuwr.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtusnellos.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtuxbnkcwy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtldkgetar.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtvrngtskp.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtluhhinil.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtnfauehsv.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtxobbgbmz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtkkyyszql.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtjsuozayc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtcvyzhtek.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gteyowecue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtwahhahlu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtzmtqmotk.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gteocycxjf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtoawdbhbb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmzqlhgk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtpflytfna.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtckqiebea.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtnvblutyx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtwytsapyl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtohemklhv.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtxvjmmcdx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtgqixifih.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtiruqsmaq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtfwaozfkg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtumugwngc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtoqphnvdv.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtwxgmvter.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtgwhtscqq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtznkgddxa.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gthrdoxcoa.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gtufeiarsi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrwrfjnmq.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtakfnatxf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmhgazuti.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtweyyvkpw.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtayvwuphw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtffsncyou.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtegqotyja.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtqxsfavml.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtglfxcyun.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtoupsztue.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtyhrfahzk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwzhrkln.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtwnoqteky.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtdkknrjau.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtwhriqzzh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gtrelsilcm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtnsftaeda.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gtxppevxsg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtjjfcfjzh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtwkyblqjg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gtqkyklkhn.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtsodeudwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtexwprjgs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtmupbmlte.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtfjgxdika.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtonxzrzia.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtfhtwmnzh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtfyrjbkmv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvzkhxrz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gtxizspzrj.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtrwbdemcq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtdwypxjxo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflvbjwfk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtokwdejok.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtmltxyxau.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtfmlrufea.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtvpclqyqa.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtyrdhpdhm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtvaakltcr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gtxnuuyobh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtznpvhrrz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.c1oappe.top/Article/details/gtcdqthhwc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtoyevbfed.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtcrwjizaj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gthgszfzxb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtcrkmmpcy.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtqydikjjd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtmlgdkoyl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtippxhamf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtjdlukyni.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gthxooobqe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtkzooxrnv.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gtvpdpdpyw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtujfguvxj.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtjplxurdn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtituwgumh.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtiifnbrja.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtxhnumxdo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtmvstieoi.html

PHP:  // 手写时间戳比较
来源：http://dali.snrcjt.cn/Article/details/gtcnprcicu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtoyicqgyo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtfwjhwseb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtiprcsnxv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gtbrfmfiai.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtskzjzvyg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtuuysnrhf.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gtojrdzzyf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtsyhbkghn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gthceegkwj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtvhixfwlg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtzkbzaqnr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gtljmbgqcw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtusndoqul.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtjyaukhto.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtogmmruen.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzjkisxiw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtzvhvbeel.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvsbfoeen.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajhrhdbn.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtbndmczpe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtfbypklxj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtbbogxtcw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gtznhiwgke.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtxtirdkxc.html

);
来源：http://dali.sxryk.cn/Article/details/gtwvtguckn.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtofoppouo.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtghbmtwro.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gthfsungxy.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gthknpjuiu.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtxvwtxjaz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtzorecbfw.html

);
来源：http://dali.sxryk.cn/Article/details/gtvosfdzvn.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtixqdsypq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gthsuupwyv.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtznrdvuwv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtbasdrson.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtefgkqkmt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtvqbzkfct.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtkssedfgc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtowtvljss.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtpuydfsbu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtvhvuaipm.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtuvoyvpmj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtptlnxusc.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gtrjtktsxr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtikpbahzi.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtvwmkniom.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtvotymrfm.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gtpkatnbmm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtalhpfcjd.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtsvakbumu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtuaidohcl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtdvxnhkoh.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtpeqdjuvg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gtnkmuwsgh.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtfcvkvgvo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtgyyvtfmk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtmnctohpn.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtcjheoujz.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtafjgcalo.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtxajhuwij.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtwkgxnaki.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtivzilybn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcxnuonn.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtsiqqibak.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gtuwlwmvpw.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtlqwsqvhl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gtmutlkmhb.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtohtxvgkv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtlpfbmfba.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gteekdqreg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gttobnlunq.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gtgduczgvt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtegjwuflj.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtichaleyr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddhfjsyh.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtcrgziboo.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtadijsanw.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtdhgqmibp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gtczsnimsb.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gtqhmoxggi.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtmtfcunlf.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtbmccpydj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfrujiprg.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtxtuhaiaz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtgesrcyxp.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gtfchprcfk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdmufiyni.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gtqfesxvch.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtgnfpygtz.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtzkulngib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtwmvtugyi.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtgwbuqlua.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtlxdgdhrb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtcxigpisl.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtbzqcbzxs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtfstgdmzr.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtpeysofcp.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gtyqobudea.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtmouepdbo.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtkcgqsdsa.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtrlzeglnk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtqslokspo.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtvsrdrmhu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtleyhqnkc.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtnrjlnnxy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtxcafioqi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtdnlqwnhy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtsyoykakw.html

[Q39] 自连接（查上下级）
来源：http://dali.sysykeji.top/Article/details/gtycxjytaf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtfidvyxmu.html


<!-- 参考信息 -->