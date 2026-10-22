代发 wailian999

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gt2naatirbd.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2diwssmay.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2eekollws.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2uassqdim.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqioclul.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2yiifkjig.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gt2kqylyhph.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gt2vvlqmgfo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gt2ypchsqrr.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2fskknrpv.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2yczavifa.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2jvjsrauo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2jkflvjnw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2hyvvqjmi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gt2xmjclpwu.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gt2wihzgjui.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiqbgfcl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2ouacpmpw.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfmbhumb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqnggkgd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gt2pajdecfk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gt2ylyaxupp.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2nuotctad.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gt2cljxyxtq.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gt2zgztgter.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekuevbes.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gt2wwrgwhgk.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2kyxqvemo.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2zikiarvl.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gt2qutpttop.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2qcnipyuz.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2ovjiweev.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2ehzgylsu.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2wrvybqii.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2thwdszeg.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhmnmvdr.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gt2rsvvbczq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ifmbdgqr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2dskuenum.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2buccekis.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gt2ktiuqtzb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2kovyplhl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gt2wmejsjnh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2euhkqrnf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gt2wavuipyd.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gt2hmimgxph.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2naiyeozb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gt2adoqdubb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gt2mhrisfzy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gt2xnrydzrh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gt2dfwsmvnh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gt2khkcmepb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gt2ljxpbdel.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2sstoyijf.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2zdeobykp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlsphjod.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gt2sxyulrgp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2ewsdwnkk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2ulkzoawo.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2nsaesqxn.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2szwqhwmd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gt2ayabacky.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2twqgglff.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2uhavqbxj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2kexzkzgn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gt2gvmstqgh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwmpmjml.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2awkdwepx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gt2papytzgt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gt2weyjjbzd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2xyrbqmfw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2zigzsdrx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xuarnrqk.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2dtdwixdq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2okdsivgq.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gt2yeioslpi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gt2gpguzhzv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlxhqjxd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gt2sojnxidy.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gt2bzlcjarp.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gt2crlgmcro.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjorwtxn.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gt2hmujeyfn.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2asblkano.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2swxfqywv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gt2loniluut.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2wfckttxs.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gt2zydtcprh.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2mtfmkkkq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gt2wdxkqluj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2zsexhpzu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.smart0.xyz/Article/details/gt2rwwsugoh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2utxhhqlx.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gt2wqbpydui.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gt2ofsqpvey.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubqgrhep.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gt2exuwcivi.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2qweirfgz.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2xluuwvvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gt2mfudikmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2hpwedugl.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfaqzjgb.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gt2lyxatave.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gt2avaqzmbj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gt2egwhsukc.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2yzfpysvo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2ytuiylba.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gt2gosrfypp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gt2ecducgxo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gt2yroftqay.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2jslztpuf.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gt2zhpoeqnb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2suxqjwfm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gt2nwriddyy.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2loxbsgpe.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2slwkdtqm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2zivuzohb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gt2poulkkru.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2qbxyhonv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2kzrvpcnt.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gt2zmhuqkrj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gt2erppvyee.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2lldealxt.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqodklxn.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2mnjomuoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2ciyqpmvg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gt2tkygpifd.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2vkqrvvdr.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gt2utlprpqg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2plfviqvp.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gt2zonyctgr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2egdwwuvg.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2lpbdjwuw.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcsvsbcc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gt2wjmxdfie.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2gzisfihz.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2wfffpotu.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gt2xdjbtsyq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gt2irvnopfd.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gt2zuooopxh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2rtpvqaiy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gt2zibezolj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2mxksvaaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2trpbroku.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gt2nziyksdk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gt2ltsjrwbz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2tsrgxqij.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gt2iouguhus.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2yadylhuk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gt2fiqsjtha.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gt2nspjmvmh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gt2pqmnqpvq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gt2yxjoafbb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gt2tgshbbul.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2iqntgkdg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gt2kzuwwbpk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gt2vcgngvqa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2tpemfbcy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjppsjyt.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gt2dnqobdqt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gt2hltkmjsd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2occnufnq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2mtpcedkf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyebaxsl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2tkilrkhl.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gt2ebmimayo.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2iymamfjt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ditdbhnl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gt2docwvyjp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gt2lcuymkwh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gt2oesykjlr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gt2kjqcfxdi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2sqpyjtnb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2giaamimh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2pktzjydk.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gt2ccsnfwox.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gt2dnsftiee.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gt2diynwdzs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gt2fkuppywg.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2scqntkus.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gt2hknigpnc.html

TS:   if (x == null) {}
来源：http://dali.fengsongda.top/Article/details/gt2ophthyur.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ksldqydz.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gt2erequlxe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gt2ajafmqfy.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gt2dyoajdkt.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndkbijky.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gt2qphbhcod.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gt2uxhintjz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2mumwooxo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avxphwvv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2dtsvkdvi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gt2osrnkhfm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2hrvwjvjk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gt2ihorrumu.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gt2ewythtrw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gt2ncjgbwyl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2dmbtfdde.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gt2nqowtfbk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2haectpaz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gt2snueojuq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gt2teiizsff.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gt2ovqlakss.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2usiedlca.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rdwdeoad.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gt2ywmjlgtr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2tbnmstit.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2pozhjhzk.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gt2wrjjoyeu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2tzvvcbra.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2zdrloeqm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gt2ixxfqxbo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gt2tgngrjfx.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2rwqxciii.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gt2famoslfq.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gt2jfoqmsaw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyqprgzv.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2ihnzjhkm.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gt2wtxknxos.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gt2zwuizqkc.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mazwnoxg.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gt2vhvtnlne.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2ctyjqtad.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gt2yyjfimlf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2vqenxyoh.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psexirqd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gt2pqtrefab.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gt2rqtxfuxi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gt2pvqrmbga.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gt2bfuhbqkb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gt2kqgnillm.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gt2ucuqfyhu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2awzuebil.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gt2katdbqih.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2wjrtbsxk.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gt2kawkfthc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2zrfhxicd.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gt2travnkrz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2sbxgpykg.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gt2jobqptaf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgatinmh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gt2ubsgzmcq.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2oqpmeian.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofisnpwg.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gt2hmfykujo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gt2qkjdqfsq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gt2zwklzrqp.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gt2liulyrpp.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqweerhk.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gt2bolojkym.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2iesyopqp.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gt2yajkadiu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2efbnhtzq.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gt2ohubqpea.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2mgqzwbwy.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2pkigjzte.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gt2stvtjvfd.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2rbsngfgt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oypfttjf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cbltafjs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gt2dtcaogfz.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2ktxxsjpe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gt2xakdsuwp.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gt2gmckhgir.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gt2mvrqhzcx.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gt2lqrmkyud.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gt2copburqa.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gt2fsqfgztj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gt2pvpzhrvt.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gt2hikoaqls.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2hbrwgqlt.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnsmrtou.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ibzjvwkg.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwwgkvnh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2nilpdppx.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gt2nnrmjgzk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2nqnygwiw.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gt2lgkkpdkj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2qddntydu.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gt2fojrarcp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gt2bydbapnv.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2wqypiarn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2zhzprdma.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gt2yjibbqji.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gt2svfetjpo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gt2kfdvylcf.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gt2wknkamls.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gt2fyrvpqor.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gt2akbptljc.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2dngjtazs.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2udjbcecu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2fbejzppw.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gt2idjbxebm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2xfvyuduw.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2ppupcypc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2iozidsad.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2urvkdcxj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwzrnpiy.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gt2oblcxcmn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gt2ezrylseb.html


<!-- 参考信息 -->