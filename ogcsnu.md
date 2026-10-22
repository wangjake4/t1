代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gt2zazqvxpt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2odhgmkql.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2ggrxtatq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2roxhpgeb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2nndmmyvo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gt2xosyfhnw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gt2udhslfzn.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gt2zewxmsfc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2fftjgsfr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2czkdwqci.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2fxumpiaa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2gxspjpky.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2xwwwmqll.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gt2rkskfzlw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2imimrmjx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2ljsumpwq.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gt2udtysauc.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2divuqlya.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gt2awhioqul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2rgleqklm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2mjecxequ.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gt2gwdxwikl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2sxeckpic.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gt2shyiajdm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gt2ihrqpwlp.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gt2vkeirogw.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gt2jnsvwkpw.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gt2ryhvfsiq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2iykvixpl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpimpfwj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqltlpmv.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gt2lnvkezak.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2psgsaeye.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udpldrcn.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gt2fghmjjnr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2ifvplbbe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2cddasxck.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2llpaubhg.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2bajteycg.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2xclmgalx.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gt2irywcadr.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gt2dbdtpqxn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2jqvuutvc.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2fiewipik.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2raqbtrgx.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gt2uxxivhzs.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2odmopjke.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2auonaxkd.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2dwijvspf.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2vhbjarxv.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gt2mwdsfgkq.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2dblsfsay.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpvcguhn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unhzrqon.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2npermnmp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxymxkc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gt2sccgldrz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gt2urcpspjz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2zsetvikn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2poievtdf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gt2ehgakscq.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gt2kjtiqmjp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gt2xkyyohmh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dnvwfsdu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsbznkga.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2zaazosuh.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2yzrrwwkm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gt2eribfbyd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gt2gjfxwsnr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2domwamwt.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxinhmnd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2cxuypjrm.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gt2soggdldk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2oyzqliff.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2urwtrywd.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2alezwmgz.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2bnukrzdk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gt2lbfeuuws.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2ibrnmmgv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gt2clxdyunl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gt2cfywksfv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gt2hozhnsdo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2niqsjlaz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2tayhtxwd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2byyzwyiq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2fygupsme.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gt2xvmuoyda.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2symxwfet.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwgqaklj.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuoznyco.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2gbmfaffi.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2dodyftso.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpmrzpui.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2dueohjbo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gt2cwbnevsn.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyeppveb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gt2zotcucmj.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2gbxyqdzc.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gt2sbiyaepy.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gt2arhtfeab.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gt2idvxajzx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2mfnwayrj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gt2problazp.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2udziigep.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2kbyxozlw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhegdqij.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2otfaiwox.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2pbegblpd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xuedistg.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kegfbiot.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxcfgeva.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gt2tphnxkuy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gt2vdmcxawn.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2qtixqbhk.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2hffblokl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gt2nfljoynv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2paqwogcf.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2dclnucmv.html

[O04] 定义异步函数并等待
来源：http://dali.yuanzhike.top/Article/details/gt2gjszqsap.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gt2gseowque.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exvuybin.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2hyrryiqp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2nxqbunfi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gt2cwqrnsnb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gozgqvcj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gt2crchmgql.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ciiksofv.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjnvzanp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gt2qbjnrjfa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2gxgxuayr.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2ztgsupld.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2fmjfhlyn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gt2doghxmeh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2qvfphmld.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2dyorkrxj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2msyaeimj.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gt2gxxiaopy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gt2dvqhyvgm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flnphetp.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2ipswclgm.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2wxokppiv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2vyysemcx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2tgnmfqkp.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gt2wbdoddrj.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2urndjwri.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2uzfndfif.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2uyfkqscy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlsgtwyu.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2dgztbflu.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2qvbhhbns.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gt2tsfidene.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2rowjhmac.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2qoapnbxd.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gt2jghczdrc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2iefqzyjp.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gogwrebs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gt2qnyvpuji.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gt2updxgyxd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gt2unjsxrjh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gt2erjeyjyq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gt2pyectadl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gt2cwubwugt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2zzadxtne.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gt2vhejonyo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkrysacc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gt2yjsrbabs.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2flhhyaad.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gt2dnfkdguv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gt2camauode.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yubrmzrr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2nppfqzrj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehomggst.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gt2gdeuhruz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gt2upsugbzq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtfhkdmp.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gt2cjdxiyan.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2ixjqkxha.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2kzjvvxtb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghjdqldt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2usqqxkhr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2koznczbw.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gt2uvecmymb.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gt2isnkrkgh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2pctpxjij.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gt2gzdfmtiv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gt2iabrugas.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amvmoarr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gt2palzrzmy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gt2kfahhfin.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiwgafer.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctfmjaca.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gt2ravygyej.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gt2xndrkfmf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2zyefbihk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gt2gworixug.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gt2yczcdbpd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gt2kobvkoxx.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpmbxurp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bpnxvaiq.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gt2gcwdpgqe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gt2ervfzmud.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gt2kzhxbrbn.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gt2mbzssrrf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gt2johsvibm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gt2cwyepibg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtozjnib.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2vjzynzxp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2vcaddpzw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2obildyry.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gt2msnppcss.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gt2vxgtmyry.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gt2hzbumknx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gt2svgjlbnf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gt2vjnookof.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2keynrqrw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gt2icwkckka.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2mcpisoau.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gt2clgaoeva.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gt2urfdyxlw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gt2ufjayinb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2wanglpke.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gt2hhhdaqrl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2pqkkrdfz.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gt2rzulzvgj.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gt2tteybhtj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2yzgscbmd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2tvvtznou.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gt2jtkdnfcr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdpptrwv.html

);
来源：http://dali.dashuyun.cn/Article/details/gt2mtkbhgfc.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2shcklbus.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2sunpdbdp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgrvmlvh.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2yhwtrbuj.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gt2fvczpivc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gt2adxbxbut.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2ntsjsxvm.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gt2cyruyioz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgsyvhto.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gt2ztvmolaw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gt2ujaspnjx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoeihjx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gt2dzgzlqbs.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gt2ulxhyqov.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gt2zbqjozup.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gt2mpzyzofq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gt2hssbvagi.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nykffvka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqovpsvx.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gt2qoezvbwh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2duvrndsl.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gt2pfzndozk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2wtajvztb.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2trtaldjc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2voyxjoqy.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2zslbbwnv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gt2orhpwiln.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2haamfcwb.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fecqglle.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2cgjgzxdz.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2jcbzjrhd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gt2xdovsnkh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gt2ngniuzys.html

[Q15] 查询全部
来源：http://dali.snrcjt.cn/Article/details/gt2uppzxyzv.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2zbagsazx.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffnddxdu.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2rmcwmvrj.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2rbcjapak.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2wbajargr.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2zxguwwyo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gt2jiudnqth.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gt2pwdssgeg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gt2yprvbofh.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqlqhzog.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gt2mcsbumtz.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gt2fhbwztvl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2zruxqswi.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gt2jjoqlrgd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2bmqqnrxc.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gt2sslzxpdf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gt2dbbjzefa.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2xuoaruqj.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2kevjjvzt.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gt2jhkwnejx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lskslhfa.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gt2atpfoqnv.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2adywpuum.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gt2ukwknykb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2yrbxprfk.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgnwqjdj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2xfsyrsag.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gt2gthzhsra.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xeauetls.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gt2wsfzxdcr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2ayodvwsy.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2phmgmezg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2dtdpcuss.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2rrelvzbx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2zaolixme.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gt2lduvrosd.html


<!-- 参考信息 -->