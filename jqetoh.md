代发 wailian999

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2jedvlkbf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2vqycsbqm.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byponxze.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gt2nksemphy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2ggeqqusy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvocyquz.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gt2hcmgnndh.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gt2pbffojfk.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gt2mmjzfosd.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gt2rvswaqgk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gt2ggphtcgh.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gt2agnoemjs.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ppreazmk.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gt2ydwzgxxx.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2guagxsvt.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytzlsukv.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2rfdrpene.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwyqzphg.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gt2asdjadxo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bkllchxt.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2jdhxnpdl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2jrqsgcns.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvggdkmk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2lqwmflmt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gt2xvukjqry.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2rttttpbr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gt2nzbpcsun.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2mnuzhzdg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gt2yrrubcgd.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gt2fjjxhrvh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpcyklzm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gt2algniysd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2zsxlcdhm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gt2clrcmtwg.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gt2uxexzhaz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gt2emeveiyi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2zpzgtpzk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkuxymaf.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gt2iorobtcc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gt2argeqeif.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2ipvofxqi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2djezkcva.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2dtfltagi.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2zprcuywz.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2dekukxzp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gt2idbgesbj.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2veubfxff.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gt2eidtfcxi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gt2ndlqmezd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gt2ijxeznpm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2xppkhlfd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2nwhvwiod.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2uvdfpejf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2segbfyxd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xobvbyyh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2vmgdwrsp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cycczaos.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmyvuach.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2nmzfzlml.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2gfylbeqg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gt2rlicocwv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2caqjbiyi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2sxpaatku.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2jeegcmvs.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gt2bainqujt.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gt2hjbuzvvs.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2mvlzwlhy.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gt2yvwjyfna.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2jasbilce.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gt2nhmmtcsl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxjdodnf.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2ibrjvpkw.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gt2lirpeiam.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehjjitnr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwjngizr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gt2hmeryntr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgsyxbjs.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2ybuvokex.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2mjkxpnbw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gt2qurxtseh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gt2ggmycykb.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2hulxsyfx.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2djpjaaft.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgnrcjqk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjgzbvcw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwnmlvxd.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gt2trpaompe.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2odpxkuee.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2ldmgoqhg.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2zyhznhox.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpxodoyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2owqrobtg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gt2heobuiht.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gt2eerphspl.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gt2pgyxrhtt.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gt2yfttkwzi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gt2lthdfuci.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2rrjhplpk.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2hfqbfdmk.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2lbyjouaf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2xeatofuh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gt2dqkxmmwy.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2osvcryrm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2urbjcqew.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gt2czjjpavp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gt2pilymplp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2zhwiufjb.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2qnawmuja.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2bprqwjhq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2llekvwpe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gt2abcqxgox.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gt2henbxlou.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gt2ttzrbbxk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqtxmnez.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2oaqnpfqk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2jrsfhnlp.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2tgxpvheq.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gt2edxjozfj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2sobtiorl.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2oqkmpmvc.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsygdadh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gt2ydctprgi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2pegibckw.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gt2ncshrqhn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2kkiiwnrk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gt2tseaygnz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2kilsvcyh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gt2cgluwekp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2ssmfcjns.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2vjyebfhg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2powpbtie.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gt2zlkxsywc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gt2uirnyztx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gt2suuwqizn.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gt2mydaxztx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gt2cqrviogx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gt2oriazkbe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2tpjzmiug.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcjegrjm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gt2kgtjhjcs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2wmxidgkk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gt2jgaupnoi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2dajbryqh.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gt2rppunonj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gt2enuewctg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtmsplyq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2zbspjjpm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2ulnwmiyl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2fznokeaz.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gt2riwpghua.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gt2eqozdnzj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2enmuqaeq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gt2dihujcph.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2aipyznfk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsfqpwmk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gt2vempbzby.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2sznrhlej.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gt2kbbijduu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2tkydmthx.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2vntdapql.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gt2myavjloz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2rdbxwbhb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gt2yxrgoukh.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gt2pjbzfsix.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gt2zzukjdgz.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jcilbwuv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2thkaircs.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gt2tiykgole.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gt2ojzyloco.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2uzfmejtf.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gt2nyvcsstx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gt2zgslmbrz.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gt2xncsoxdz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2fkcpdvyo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2swticben.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2tucaftjk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gt2zulreudy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gt2trzczmdn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gt2stlmyuep.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbintrqm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gt2alyqrchu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gt2zxrqqlmj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2zgzroekp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bccpjtve.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gt2zcosojcw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2ssdjdkzq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gt2aerprcnb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gt2pgomqado.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbnjxxwc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gt2bmsjguzp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2svxmuprr.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gt2rrzkwign.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpmqjffr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2uujjaqun.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2pkcgroww.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdlbwuld.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gt2eclypzlh.html

);
来源：http://dali.dashuyun.cn/Article/details/gt2mrhdwkum.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gt2lqwtpoht.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gt2ghhctuuo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2rxpbjzxm.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2wilbxbyb.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gt2imektkyr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gt2wuenarzc.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2mekmaeuz.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gt2ysrpvost.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gt2trtyehms.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gt2wqefecdy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2nnvczsyv.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfnbmabw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gt2jlhklhbb.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gt2mczdeqsl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gt2tputbtev.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2qbodxgyb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gt2yweuyper.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gt2poizzrnq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2wrbwarwi.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gt2kjauacgy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2ctweggbn.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gt2lmrhnfnp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2ghpgpnhh.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2spexsqcf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2yvlnvnau.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gt2yjkiuwth.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2hjphofzw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppbzwfng.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtpincaa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2gghzamjz.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gt2hfzvamqf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gt2yfjukqbt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gt2yoiwhgvo.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gt2cmircsop.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2kgekycir.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gt2rzbeazzy.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gt2sozrcvek.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2ltqizyda.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2gblxqffb.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gt2dcdgkvaz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gt2tiujfdac.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gt2flanvqnw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gt2ckgrjgqc.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gt2tabakqtz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2sytusgng.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqpjghji.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gt2jkxmmsok.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gt2dwpiotzj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gt2uukzynsf.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2fmpolphb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2kwgqtdud.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gt2gvsvsjgy.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2vagkkdhc.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2kkqrautz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gt2exeznxbw.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2vxwmyrvw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxanqglc.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gt2xpaymtvv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gt2gqomridw.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gt2vwbrqvae.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2wqbgqxld.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gt2xsoquqrl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2oaglwllt.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gt2rcwhfyza.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2czpmluei.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvmvhros.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gt2hmccalvt.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2iuksyroc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2ugfsqdtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gt2ydkagfvx.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gt2kumhjcwy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gt2usyjejni.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2lrrqzgpy.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gt2eiotgysm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gt2gpraigxg.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gt2vnrkfhrl.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxvfaumg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2wucyommk.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gt2fgbdazyj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2zdqipfuf.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2nykafnqq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gt2cwmlnkcq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2dscqrdem.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2erahcshk.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2wakuldsb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gt2oqxbbvaw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlbxbejb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gt2rmnmzxlj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gt2sfptkpwa.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2ducbcrqb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2nlhpurim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gt2urlloaku.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpoveick.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gt2orljpzbq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gt2ubieqnyo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gt2oddrfcpx.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouifvlhc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gt2prhcwzuk.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnwxracw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvzwjrdk.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2izcboykq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2shzxjfei.html


<!-- 参考信息 -->