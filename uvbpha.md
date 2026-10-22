代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2jyrnqzug.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2cooczntw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2bnjgfyei.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2vbrnjidf.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2rrevcnja.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gt2jbiqfpmy.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gt2azloisrr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gt2gqoojngz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2jmzccpwn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2rhwbktqy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2skfyuknt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gt2nztfzasg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwckyakx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gt2tgwttxwp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2clpamups.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gt2genvazfu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2bdrxgpgu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gt2gukqwupx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2lrdctmab.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2qqqeyfqf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2viyijwmn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gt2yasfjusp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2oaedlozv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2dlpwegyk.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2uniaenbw.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2dpsobiwi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uihzttvo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dubctild.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2xkeflrse.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gt2jxxgpsku.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gt2pyypfgvp.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2kfbsynzj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2qgyhlxqb.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gt2tqveldqz.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2cqkesfbx.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cljtbxto.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2wtquwbna.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2pvukfoii.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gt2tkmpounl.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnhnegyu.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgshdfxa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2dtajcqxn.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gt2ltmcnjpj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2triqoyog.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tararnfj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2hzasekwf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gt2lmsnhrse.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gt2umdmfcvm.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2gndusnbh.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gt2yhwutrkq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2zrhjteff.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gt2pvfwviyw.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2epgychov.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gt2zyyrelyw.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2qjzizgrs.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2gomypqne.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hckpjdbh.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2grdlpqly.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2jvoorscw.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2exccoabw.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gt2ljkkhymq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2gquuebxs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2dlqudxqa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2bcfqaezn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2engaeras.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2icfzfrrt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gt2spujrmgd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2wiugfeym.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gt2bzbaeqjh.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2uisltsrz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gt2giiaqvfw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gt2bimrpybl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gt2axuzeyfa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gt2lnjxbaiz.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrgbghad.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gt2oxysaesa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynvmaorp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gt2ihewobua.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gt2siviwyrk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2ttgoadxz.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gt2avumtqzw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2viqupaxf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2xrvlwirf.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2gzvcehfc.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2cdncekrr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2hswznjih.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2nldguuvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gt2ypzminls.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gt2kpidqtaq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2gtnvttfw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnthsjfj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2qwbrxomb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgnoytim.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gt2rndxuips.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2zcqqltsw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2hsewpgcy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2bhxwiozq.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gt2hnbivkdv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ufjktohd.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gt2wkkdwlfe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2hpwbqgdv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gt2bibhkjgq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2wdcefxec.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfhxagyt.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2qklrzzfc.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gt2sopkqnut.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gt2pibjlfbe.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2otbdtzma.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gt2nwudkpba.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2sefjzjtz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2sqwnkkhs.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2ghbiisav.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gt2cgpntlch.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbolzkih.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2bbwubzin.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2dzfdkaik.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfeimtbt.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2jdybqmbg.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gt2cfxjhekc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2gsztpjao.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gt2iggjhdvw.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2ppvjlmwf.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwdxnazg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gt2zfmwdleu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gt2yjrlaaqe.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2zgamixch.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqxqcnvg.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gt2qfhwtmjp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gt2celndlrv.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sazskiso.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jqorqomm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gt2mqdcwhjz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gt2bxkohify.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2ekctrwqe.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gt2neftgcae.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gt2bqefseys.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2ppriozgz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gt2ccsjtquw.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2oajjokuy.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2vkjefhjo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gt2auyjoyxg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gt2gqbpekpc.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2jgddnewk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gt2mpccqbds.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gt2lzurzsjj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2vikcgfkc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gt2hpgqndyv.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gt2wlmgqxky.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gt2mennysiv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gt2mvptgmeu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofwotoxh.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gt2xukfvcvb.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gt2fhhntgcy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxuoufky.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gt2vcbvvgwn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xskiryry.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gt2voznphum.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbykupce.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2jvbnftuh.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdlhivnr.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xosogelj.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttarryga.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2tyuktccd.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2xskypmkz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gt2raezueup.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gt2obryhxil.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2xqzgwkpn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2bzdozkms.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gt2orhgjorw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mglrbmlf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2vfzyhlfi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gt2jaunfnut.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2eszhyggp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2cjmbtpwr.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gt2kyrnfoku.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gt2albsnatq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gt2qxystwbq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2dykziwfq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2vxhzovwm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gt2torlyrzs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gt2ceskpubz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gt2nspwoapb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gt2zgaqhpfs.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gt2pnemzaqo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwblvuyo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2mpqnumwu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2druyztcn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2rwwzcsap.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2bmnxkqxz.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2fhkdzjbu.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gt2rskptrqw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2fekossxj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gt2lwawqilg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2vgnwfqxn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gt2plfuzbud.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gt2zcgwrrdw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2tfabqhai.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gt2qsmotsyw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkcvksgc.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gt2lknrbdci.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gt2pgpiisba.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gt2jwhluarw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gt2jgkvhiqk.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2evbuunye.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gt2kuqvuikf.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vmkwtxjp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2pnqhwewj.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gt2fzzvszjs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gt2sfekbdmb.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2zdfufxzj.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2bdooifgb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gt2iqgwknjw.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gt2ocsymwmj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2rbpsumqd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2wgguliii.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gt2hodpojsh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gt2umxbmaff.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gt2fqlvzhow.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2gecscwdi.html

[P08] 处理浮点精度问题
来源：http://dali.xuanzx.com/Article/details/gt2cnkvzpja.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gt2zyvefhhe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueashqmc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gt2fgupsnby.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gt2unesnhxw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2menxtbkm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gt2xswmzkfj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iymvndjl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlapvjio.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ubuobefh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gt2urynqknl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vwmbjfvu.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dssxyddk.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gt2uyvanlau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2obiuduxd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2wuqvkxll.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gt2dbdkbwey.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gt2txkzccsl.html

);
来源：http://dali.jqgufenzy.top/Article/details/gt2nfjcecvm.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqdcyqaq.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gt2cbviforr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2dvbkzgst.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gt2drvcgizz.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gt2rpjovwch.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gt2aeosaaes.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2mpgjfxcl.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gt2ujckrkdp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gt2asmiggkz.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulfgddlo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2kjcngwfm.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gt2izhbquuo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gt2dooidafp.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2gmpsdygg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2liwqzmjw.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gt2nwrathbr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gt2bjeziyef.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gt2jmlrucek.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2owsbabra.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gt2uduqklyl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2jyoctjyj.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqgyxwpk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2wvhzyioc.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2omoqzwpx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2nuoghaje.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2dmlwrbrz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gt2pyptoobm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gt2idjgsjrn.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gt2svjhgwmo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gt2oyaghfdw.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gt2qxmcgkrw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gt2ebjjawdc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gt2nqhsyzsi.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gt2bxdjeufj.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2whwaqjua.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gt2uwqyvlwh.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdydoikj.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2uyqupugq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2xtqnodoz.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gt2ovnqrdwt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gt2pmjyowbu.html

[Q19] 范围查询
来源：http://dali.iojbl.cn/Article/details/gt2udxqmfsa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gt2nyjqwoib.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2wgyxtcps.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2egbbecba.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gt2nmpnfhes.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqbihqjq.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2dccwbmaz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2xiuhhhud.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gt2kdcgqsqo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gt2epborixr.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gt2gbwyzjgs.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2psoincnw.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqsqqayl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gt2mbhexeib.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gt2jmongjnb.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gt2jftiyfgo.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gt2qpwsxats.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2zbaokhua.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gt2mmfwxare.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2nzsofhvr.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gt2zdwyemik.html


<!-- 参考信息 -->