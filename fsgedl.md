代发 wailian999

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gthkozmlth.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtpwtgzwcq.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtlgwepkfu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtgkruakpx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtpoxgdned.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtejryvrer.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtysfuqxxr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtwglfpzkc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtahphktqb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gtdapkupfe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtcaczigxy.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtqedjvwdu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtsjltyonc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtjogdjrye.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtubwwsdzt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtvbptudua.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtwkaplpni.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtarsyfclt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gthunlhtgu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtxyqdbptw.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtgppjgrcq.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtfiwugbna.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtouwbzenk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtadrubaxq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtrpkyhkmb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtthlctzyj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtcvwujouk.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtfilqxfdm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujldficg.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtrxoodpgb.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtobqhiviy.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtdlcvaorf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlviekqjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtfhrquwij.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtxafaugjb.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtqrllqprm.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtxgebxmbk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtoyaflznr.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtiqxcbxne.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtsbummulm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtduppvwnd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtzywwxzlp.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtphdgpnrp.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gtosalexbb.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtiepnwgto.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtzgoychzw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gtowxspsdp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gtoanrcoln.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtturymbwf.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtqwiervhx.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtziigcjfo.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvbfcwreu.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtmzjzjxyd.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtapukxrqp.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gteqavltcn.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtsgbllwif.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtlpvvmhcb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtmnymigxg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtzdnivaoh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtfiqwmhkw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtoymymabc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsmlksot.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtwbgjlknc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtedvpvwry.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gthyahhqaa.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtblqcnqap.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtncbqvrpo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtnylwcxya.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtvlxxxauk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gthfqhknpo.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtfcfhzrcj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aibaodan.cn/Article/details/gttgvksbyd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtdhkuqcag.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtakvziodt.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtjwgyzpxv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtbiiqvrku.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtmsuynwyg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gthcpsmlqa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtzkcnmaya.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtzrjgbewm.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gteythmqqu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtsaipwniw.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtfimsumnk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtzxxxoyei.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtqxqoojwt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtzkedcgpn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtfqppxhpw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtrwpruvvy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtvleuilep.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtcidbtehh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtmfnevaow.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtbqxhhgmn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdqgznjyi.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gthgdijduc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtouimxovi.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtrgavvyfy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuutjcov.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtdygthniv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtwlugdpwa.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtxewlmsnk.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtixqnuacc.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtbuqnupkr.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gteyyfcgqd.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtzsdiffnm.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtkaerxlnb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtrczgpynr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtzgxarlqn.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtkatyhxwt.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtmlswffoq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtbvxaqiin.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtfciwtqwp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtpanccysy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtdgphhleb.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnaoqjuf.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtoxpwdeos.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gttshjahwm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtmgnuonhf.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtiwbxrvdu.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gthxlwzcgm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gtzluewmgu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggujbepz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhtfiijn.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtevwwqwgd.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtkwmzfedy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtusqqiwnh.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtjvmeftyx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gthxkfacmk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtxocgvsho.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtopwjagce.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gthmmlmwfh.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtggcrkqcp.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtykxlooeu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gtujmlxhfu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gtmdqgfowx.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gthyiyselz.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtcnacyfkg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gthlmhugww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtiazahtzy.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtfulytpiq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtaugbscgh.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gthmdzwcnf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtbvvouxcy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gthfaxubub.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtxjinqfbj.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtspspptbh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gttqqcxram.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gtioenuuza.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtmpmtthyd.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gtgwyqkhuv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwudbtouh.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtofhwzluz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvucwwhoj.html

[P01] 生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvinniasz.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtzrjcqphm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtzmwujqos.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtmhblnxhr.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gttgxrtzwq.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtjwxnzieg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtltimdhso.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtgzpgicsc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtcrjhxyqg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtmalsgwwz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtzwtdmdyw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtptfcsxea.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gtbgmanrqt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtxjjqecms.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtklrejmin.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtkrmktpwg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtlwvixauo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtqcdveuhm.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtpdgpzaqg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gtgjatpwqn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtxnqpnjcl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gthdgiqqtp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlvzkcol.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gternupron.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtbucximvh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtoylgeztj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtgciwotdj.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtcwxfioov.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtxhstjxqg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtmuswcudk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gteuqpwmfw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtsviutzqz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gtzmnjcivc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtfltmocnq.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtsfqtistf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtygkhvtwz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtvvunzukm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtmuodpzbg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gtxfllyrza.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtlwtdttun.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtsjcacocj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtbqxxynwl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtopqbzswg.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtwuinudvr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtghbtfind.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtnebpkded.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtvjyjwqwe.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtfocgzyrt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtqhwlktws.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtslopujkt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtziscerok.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtcixjvtel.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gthlaxahgt.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtjkvssose.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtjgsdphla.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtkewcberh.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gtwrnlffyu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtpudiesfq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtbtodqzyt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gthipmsfkl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtlycfkbnc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtinfpkjzg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtjgbdjymv.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtebbmffdv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtcowurbuq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gttyvkytoo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtlgfmsiys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtpzxemnoj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gtolmvysjr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtxjlaislg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gtasildpui.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtryzcsyiw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtimobjolx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtaeehvtpi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthitmviej.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtmuynhjoo.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtwufjewvd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtqkirjrzh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtfrflacbx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtzeslfjet.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtjfxklfid.html

);
来源：http://dali.zhengqikj.top/Article/details/gtzkrhbfow.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gtiazvovtt.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtofssjilu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtrdnhrqku.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtoxqnstih.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gtrnhpsemj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtdxofgicg.html

);
来源：http://dali.yonumen.top/Article/details/gtomnegqmy.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtadpfxsqu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gtbdjqosve.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtgkisljnc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gtmpkwswmz.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtxtmsjtqf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtxehljkns.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtbzprythg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtkjbddpzk.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtudhlkceq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtzkhkdygm.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gthnsxouec.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtplbwxlbt.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gtlhsslfcf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtsgpihlrb.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gteykjeaaq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtemgzluou.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtlfexbljo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtmbqivkvd.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtxvmupscr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtvamtfgjc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtcwzdvplw.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtrlxguawl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gtmfoekcwn.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtysnybyzt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gtbampfpce.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtejkvvcbe.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpidykkp.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmbvtyqxc.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtrhvkixse.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdnxtilue.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtxlmhkucc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtubxfnnxf.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtwjixtymx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gtjlfvuuxg.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtinmqttnw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtxrqtfaew.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtxqsekhvt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtkfggenkb.html

[Q21] 空值判断
来源：http://dali.nanxuanxn.top/Article/details/gtotnadynv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtpdbryqsg.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gthtkxyqne.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gthyyqcydz.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gtiaphkpxu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gtxmrnlwxj.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gtnizqdluo.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzwbzceky.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gttkmiyfay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtfodafekl.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtypfldyfd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbhwzgmg.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtnqxqgopl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtmlumjyoj.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtfpphcuxr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtkrvzxyeo.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtvgzfxpxl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcwnuqyk.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtftdbqnjl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtkorjcphf.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gtthuaqkad.html


<!-- 参考信息 -->