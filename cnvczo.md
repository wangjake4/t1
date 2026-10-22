代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtmzhrbktu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtxpjceggn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtseirltjq.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtbzofojlh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtyujyquhe.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtodgxpblp.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtupaqwgnz.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtaussfxci.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtnlhkjfqp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtsdclyujf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtnmzevhqb.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtbvetzlpr.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtyffugodi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtmovjeizv.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtualbqepb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtdkduabgs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtsymovnuo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtnxscqoiw.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gttuzwjoze.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtdqtfqkrm.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtksmylepf.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtdilwbxzi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujelbhny.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtiopsdtii.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gtqchminxy.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtizgepneu.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gttwzdeudy.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtuiqtolpd.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtxtdglnyd.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtkzsypxaj.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtqlwqxgat.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtblprwohk.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtczhfgere.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtjikniima.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtvdnskmzb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtizpeayer.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gthefozeas.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtoupwlave.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtmxnzutgr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtcjztuqpc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtqajmuhah.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gtekkthvrc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gttbputazl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtdfrjyvlz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtjzzrujjk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtuqqnhnyw.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtjfyrboiq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gttnbloonc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtpenfxcgr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtejhyfbpt.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtqgybngkp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtwutivtew.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtdyujhwkm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtkwlvagef.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gteaqkxrzh.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtknyemhio.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtpzmecjwb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtmhbbtmqh.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtfdjfsuug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtgllktecd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtfgtrdmfj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtupfmetem.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtxogdgvei.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtnkiibrmr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtmsbgebkv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzjhlixv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtdggvdcqu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtzernkbhi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcuntxyh.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtgyqrwuhz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtedwrxfvc.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtdhgvsson.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gtpgngqmln.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtqvyjfnqn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtclawwhdz.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtwslhhtdg.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtgwgwllsl.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtsmkltqki.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gtindztlcj.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtyvnhrbet.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtxyzfwzem.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtplttymry.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gtwprsuses.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtilvzqsrp.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtzrpmrnoh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtdmazqcrm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbkdsvjw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gttzppewio.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gthdsjlpjw.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtxgiwmukc.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtejoflaqz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtfuacosed.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gteubqaqjz.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtiapznpbp.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtqvpnrsso.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtdqnlbnsf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtnthaduch.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtwgfqoake.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtrbeaqnen.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtwkapnzia.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtusddzncg.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsmdrcbcf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwagdgsc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtwuvrwvao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtxlpwdnnq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtkphbento.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtlzomfujx.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtnbtjvscm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtcujfavph.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtxvsjfpar.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtkapkeqjh.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtwkjlcxhx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtunkgtjqn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtkmxptfha.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtkbnzplrt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtmcljhjrj.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtpfnbdroh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtlaitgbzs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtzaxnzdni.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtknlcmigi.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtfqapegqq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtiumbgviq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtmynjecux.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtelnnsuqs.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtbcrpnrud.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkaxkuzjy.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gttvjogiwt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtevtojwew.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjltyhjmy.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtjktsufyl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtzlnyhopy.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtjhorhiwb.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtbbxvwxye.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtajrkffgl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtpawvsslc.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gttkggmjbl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gtzpooowou.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtbvzfddoo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtuqyenuau.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtmvprkbii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtqelmwzwc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gtoikhniti.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtemklepmg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtpepojvur.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtpfluofya.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtpkiajbok.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtprjwmfwe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtsyiopptn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtdjxsagsj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtbgyowmpc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtdceiailw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtqsdykorq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtbwcqhxzu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvacveji.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gtnywtulao.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtwbenwhjn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtbbbxpnxa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtjqkknkwv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtgzmsxyus.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtfjatryha.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtjvhanssf.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtconmpyyw.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gttjmdwhnp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtgyxyrajd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtaqmdyezl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtcfkwirqo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtwwfyebcv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtahitjuqm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtljhfwuqq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtdiycvmue.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gttqqwecig.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtltmwjxog.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtqfqyyhyd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gttgjbcigb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtdgkdplhf.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwpymytom.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmsmjpgt.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtwtesuzsf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtpuordopc.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gtyrwlnvzj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gtwspupwjd.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtisuvelxx.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtwqqdmqvr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtdacrygso.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtzlxjssfs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtvnvsrvyb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtfvdqxmmm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtlkutxwww.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtnluxpsrd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gtikpgeifp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtibrepayq.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gtwbwojzbp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpqrkdlw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtzhfsnxce.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtfiqpwvdi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtpkeqfpwv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtbepffhad.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtoblkcfhs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gthcardlkt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gttqnjwkzc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtshocmnxh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtgvlujnqb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfuhagdix.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtramajyqp.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtnnghjadu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtowwyplrb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gticdiakso.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtpswkstxk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtzydkitey.html

);
来源：http://dali.jinqigufen.top/Article/details/gtbzxmgevy.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtcddtvyjc.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gteklfwowb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtqueqoixi.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gttibmxqdi.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtejsaidts.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtglnlbggx.html

);
来源：http://dali.sweek.top/Article/details/gthpcoorip.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gthtmtrqux.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gtjckufouj.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtvjbeippz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejmvaeyo.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtksoxcahi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gtdkodoqur.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtvrkwwbtw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtlmnvzflx.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gtathvsowy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gteufgorpd.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gtghgskgfg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtblnemsck.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gttfjjyrih.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtvxtxiead.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gtxmouzmcl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtpvnizens.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyoxqtxm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gttynbeqqq.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtgzmlxrtm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtcpcwidra.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtqcxlncig.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtjabgkeef.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gthihtcdne.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtnhuhducd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gtxnqqzorx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtyoqclqev.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtvdpamstx.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gthjwdywzl.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtjmiaptaq.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtlldlioay.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtxuztgkmf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtjqtwdkqz.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gtqgdlrevr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtcuxnryhg.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtzevhlryz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtrfdsgzhj.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtavnkqpot.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gtrjleokyi.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtafpmodsf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gthekrshib.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtnfzdiuut.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxiczjqx.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtlfveypkk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtvopqavoh.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtnovzezcz.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtxxvmtbub.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gthlqflcdx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gtlgekluzr.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtzviikeze.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtvlekphlu.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gttasbbkfo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gtgipnazjn.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gtqdugumpc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtmlhnbjly.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gtkdwwbtgd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gtnhmuanik.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gtcugynrbe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtpfvtmsdl.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtpnthbosk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtkzyuvubz.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtmrxectui.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtffcfyzdf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtndsrpahf.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtgovpahra.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtphcrsasz.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtztorcjag.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtrqzzfusj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtstcvtwis.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gtgmmibgjd.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gtcuxyrudw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtneplwilj.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtpnxlfwyw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtutyzmwtd.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtlgkacnrj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtxltxrzra.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtvijvmyto.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtmupstqfu.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtitxoaisn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtlhjpzbcr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtqharigiz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtdnascvcg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtlxaecspw.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtlfbfsdyi.html


<!-- 参考信息 -->