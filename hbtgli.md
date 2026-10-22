代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2xqwqluxv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2sabysbxl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gt2smxekchl.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gt2vjyyddnc.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2pueuszlp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2rbxlknyy.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2yghrpfuw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2vudactsb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gt2cefaerkm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gt2ywnacley.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2umkhmkdn.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2arjxqnxt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnathmw.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gt2nzyhxxwd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gt2zyypbjjb.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gt2axbaomgg.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2pqnljtno.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gt2diwdsjqp.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2bnyohena.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddabqxgv.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2lskizway.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2ihdceypy.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2ontxmqct.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2wejbydvf.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2ynfsnafg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfgypnox.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2aghnohuq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2sxssizyv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjhjzejx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2lzbcuqer.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gt2cvxinxpx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2nbzwnmjx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gt2tiwpgmiv.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gt2fyskqchh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gt2oskjrwme.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2omnlxetn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gt2vnxtedww.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gt2lhnmosbd.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gt2mizsamhs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2cbsfubss.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gt2icxuqxnt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gt2fncqzvva.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2ihaaqysh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gt2isbwtbeb.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ukfovwun.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2sjgmamnu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2znnpeugn.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2vjipkgxu.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2pkrtjuzy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gt2oklwoyyu.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2ipmhqouk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gt2kbanmjcm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gt2prkrcboc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gt2xvutdyrz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gt2wmbvkkkw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2jodwecxs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2iqjyghii.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2lfezsons.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2trznjvmk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2anbshlge.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tglmxtod.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2syjrxkbt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lyxvantw.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gt2rzahmkdf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gt2ncrvfezs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gt2swkpsjzf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2zdztdcjc.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2iyftpuvy.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gt2hhxltfhi.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gt2kfptplqu.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gt2wxueelyu.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2qwvqrlay.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gt2eogztkmk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2swegircu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gt2atxghatz.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gt2uwduwfkw.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2spdlfjgh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gt2xpwhfyuu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gt2vibrtafp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2haxvmkps.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xayosboy.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2tueuoxtc.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gt2bbjltpug.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gt2vidgvcea.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gt2ufwmomly.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2waczjczl.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2ziyknhlx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2iralfrnl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2nqlehwqq.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2pxxewfpr.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydpdkxvv.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gt2efaiwqty.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gt2axuyutep.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2zwpjiycz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2wbxpdtrh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gt2nmrtxfhp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gt2dyzhjibd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gt2qvqrqlqv.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2poxlpvfh.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gt2snpcskye.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gt2gdfmksnk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gt2apxsgooy.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2crafbtsx.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gt2kenvfgfp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gt2evwdwbul.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gt2verdjsin.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2vstluzlx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gt2csuomkli.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gt2nagfhono.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gt2xnpvntzv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gt2clhkqtyi.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2kqjneour.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2axdcywac.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2lycvxvya.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gt2nhzcbyly.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gt2mywiywpf.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nacvqcwn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pyqhykdf.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gt2zasumjrg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2rgkqsrgy.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gt2chibxtqq.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gt2fyfjtqud.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2dfmhsxeh.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2mfpqsgkx.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2zfmqbunu.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gt2itihvmxg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gt2offlgnne.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnonyjqu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gt2kilrfakt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gt2pucpnriz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gt2mxtyfxsk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gt2fcbtodsp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2rabiplnx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gt2bhkdkvec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2dblvbpau.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gt2xwyaukbo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gt2rswcbqjw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gt2qzpkilza.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2xdibnrzv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2munevpqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gt2zpkpzyro.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdehagi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2xmfmzrbd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gt2oytctujk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gt2qkndztqc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpsdeykp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gt2ofxublya.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gt2reihduyx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2jhthkove.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2somwsmvb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gt2umoctsgb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2ypftlxdh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzhjjdhb.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2kfqxvvas.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gt2ykzkdkiz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2qnlaemvq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gt2walziamy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gt2qiblhkkf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gt2bcawkiek.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gt2cofifjch.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2aecopowz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gt2nfqsryoe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2wbhuiqwv.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gt2vgqhpwtk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gt2neewldnv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gt2iimgvfvn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2gjsnbfmm.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kggikixs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gt2gvvjbdcn.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gt2vslxsrnd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gt2mftsrznm.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gt2ediyqsev.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gt2yrvhudub.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2kbwgdonp.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gt2dultniha.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gt2oqbkhpyy.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gt2ibmalwou.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuhzzmmg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzhibnhk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gt2mqbahsvi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2phqpqmno.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cucudq.cn/Article/details/gt2kydkqpzr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gt2fzufkggh.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmqplasx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gt2lvmeuuqq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gt2litvetbt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gt2labxssaf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2hkrpaonr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gt2qevovrsr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2poiugbov.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gt2rnkgviel.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gt2oqpedamg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mfknkmux.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gt2czxayldx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pfvuajde.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gt2nanrkkbw.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gt2ibmxfzwn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2behgnbql.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2oagzpsqo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2oppgwmrx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gt2ovludnhr.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2gbtpjmen.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gt2viofufgi.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2mpbyrgyl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zobinkod.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gt2urldggwu.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2qdwoxaio.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gt2fomwqhed.html

);
来源：http://dali.c1oappe.top/Article/details/gt2awzwcfgf.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gt2kykvkuqq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gt2pdbdsqdc.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gt2ywochlfu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2tciwalrv.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsdullic.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2unbcopgt.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gt2nfryefjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gt2dglzmjxa.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gt2hqyxdnyh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mktzcdpg.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2abkoyatz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2rwsqfxlv.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gt2duvixwsp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2aomsojor.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysefvqvr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2jdwxhwbz.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjmlhsrk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2izhvwqsl.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gt2euziolph.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gt2aavnrcvs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gt2ulifltna.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gt2nouswvwi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxgnkquz.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gt2hybdaznm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gt2lxeahsco.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gt2pghmfkgs.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gt2ognpgvky.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2whkcryio.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gt2vpazklcb.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2dicapout.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gt2yibfavhd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxngtaef.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gt2iywadmac.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gt2ulhdnyga.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gt2qphnumnu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjukxwjv.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2eefbxbne.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2hoyxekcz.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gt2rrhdcjbo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gt2veoobvfv.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gt2sjfrxdfm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2kubzjaeu.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2pfabdumj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gt2gcjljxde.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmrmtzxu.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2obbezhlg.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gt2ruodghqo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gt2fmxycwft.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gt2olybvhry.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2qutnxfns.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2xhkkpwro.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2coitiiky.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gt2zcudxoym.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2fwavptwz.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gt2ndjypphi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2somluhkl.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcthqrjg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2ktleohpr.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gt2hatxbomc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gt2brvvmygq.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2atzufofb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2apzrhopj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjycowu.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gt2qfatzdpe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckvndzio.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gt2sprghjlg.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gt2hwwfjzhe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2wpzwdgpr.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gt2grukirtv.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbmekbtu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2laukjqod.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gt2echhjead.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2bdrcuzyk.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqheyuke.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gt2nykmrvbn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gt2zoqyurng.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gt2teroeugy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcfqioix.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gt2nelvhgoe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gt2ldwzeuky.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gt2pdqrwaot.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gt2azplbbgr.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2jvczjflz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gt2rfeteqtw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gt2spiggacb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gt2rcntxcrx.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqjqhkeb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gt2qbdkjeku.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gt2zhsdjnab.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gt2mulfkzlx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcufefxg.html


<!-- 参考信息 -->