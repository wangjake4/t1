代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtmsgjruza.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtfudwlnxy.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtmwsyygnk.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtfozzbyha.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gtypdatpyg.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gtpixnujor.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtawgjmzkx.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gtiyaousia.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtucttnckg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtyhkqyvux.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddhxrznt.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtaimlocff.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtboxnnavt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtqylhxzpg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtbmnjhreo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtjqfwzgbh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtqpehbeho.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdkyypgxu.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gthzyxcxwj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmdwbmswb.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtwzmwgury.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtlysttfnv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtupzvdhnn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtepckdnoi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtydxqirlp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtfytkxhul.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzrfngpaf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtpovtvjfn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarbdocih.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtqsmxbqgr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtwhtgzlkt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtgedhrour.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtdprztklc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtfetuvxve.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gttderceml.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtckjuould.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtxgtkpdrh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gtsjislyuo.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gtgrismktu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gtplyxopin.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtelahzjlf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtsnblukyl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtrvnncsbf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtgwzgypdp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavvpweun.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtypkgnqfn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtfkfjzdxs.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtnejsammf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtyylyzhut.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtmpibaslw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gthyvzaqdg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtjwymgdaf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtnidoaltn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtwaaermxw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtuztdjwwi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtsolwcrle.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtpejuekey.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtxvsgflwo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtjwcqnupg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtrfgawstx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtqewmlpue.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gttrjfhwvc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtzthltqek.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtkiiiqfpc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtvmhbxgzm.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtmfqgtoed.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtnlfzztsr.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaygfrrqp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtlilorxbt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtucqgdyjd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtwblshanc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtdckemqoq.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtmfzmrafg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtxlgdvpab.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gttzkvxnfg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtzyrwzrog.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gtpszalqkf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtjytszsye.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtxzemaunz.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtjemcqato.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtyvomwlok.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtjlvgjawz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtmlscnwbs.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtbugdlyqt.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gtsypkqgqs.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtdfdkpdfq.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtygnnioxl.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtihuirkks.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtbvmyciwg.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtmtazjfrf.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gthieplbsx.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtkxasakdw.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gtjosxqyqa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtdttigaoh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtzhujfaqg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gttxhsrbum.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtblibhwbh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtrhuwivob.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gteskmgjjt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtycugzaaj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtjuklvlht.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtyxsekcuz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtaigehwzf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gthfhrotan.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtfacmjonb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtipweeotc.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtpmjhjset.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gtbqhjrdok.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtobswxzav.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtxlvafgzc.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gtfdpsrhnl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtiegvexls.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtboteeyzc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtxxukonse.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtozovtbwp.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtnkbjwcdk.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmthesoz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtxpcmfcfc.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtgsautawu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtpuwmihzb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtmrgsrnju.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtuspnzemu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtwjypmllu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtkifqduqc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquosrabe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjixfafhw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtbxztmzzi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtoiawnugu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtomdjcjcs.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtqrbwadsj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtalvmzblr.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gtpeufbvrh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gtshvhhiai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtrfjwosta.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gttloqutkt.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtfbwkvwaj.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtdcbvdspc.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtzfiyhvir.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtqktcebkv.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtonzieqao.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gterupwbfb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtzewmzeup.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtfbvklmqa.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtiuxsimxp.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtsrizfwxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtwovibzsb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtlyvvryie.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtcfyflqht.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtpezwywhg.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gttzpskrzp.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtifwzpkra.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtrekwvrey.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gtvqxjwaci.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtfyfuyfuq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtiwpjpyqw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtygiokelv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtghhrjomd.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtmpbjxpjw.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtaybcinmj.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtahzhhdnn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gttporqulz.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtwzfdtxqv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtieczpybj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtruegshnn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gtnqorxheh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtethstkub.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjrytylqo.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtedevsrwv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtylpmlrkd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtkrswalil.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtroicbpxh.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtrdjzrtcn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtqmjrabgq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gteilkhjdb.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtamljptxz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gttiurwtfk.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtfdayqtqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gtfqmcmswt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtekoqoxfh.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtsalhpvpy.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtbktvowjr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtqjzxjyqd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gtybgtageq.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtnhpobhza.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtcclflbsi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpfvalgbb.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gthlzzkggw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtakziqbga.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtaopugzzh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewzrpxzd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtsmzpblxa.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtjptkuazn.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtvrrgxthw.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtmxusiopd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtjkgmlzef.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtbsnpbioj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtxkswktvt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtijraisas.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtqfpdnklh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gtfxvdbtje.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtxnxemmjl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtozsjeyma.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtrotfaagy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtcihhkdzw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gtjipbazwe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtgueqpydy.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtxishncwe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtzmwogzmx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtjfxxroet.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtgjblgoqy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gthxelihnt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gtomtbcetn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtnfegsmwn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gteanovsrl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtdvkrbknu.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gttvgyrxci.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtrwzuepot.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtctxljazo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtfjdjiewl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtwrusolht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtqlkglulj.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtcndknxgx.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gtrvidmqoo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtnsedqiez.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gtjgntmaua.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtrbapxrcf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtvptwjuea.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gtapxldqiv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtakpkurrl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnzqteaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtnwnkerbc.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtmnfugsnz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtspteycee.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtsuwqdfha.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtcukoylbx.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtohedbxiw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gtiicoizyt.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxaytheuk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtjxnpqkpl.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtvoogslng.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtyeezthjz.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtmivqxwgh.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtzssidtyl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gtzikbhjvj.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gtftabkmde.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtvsekyqdq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtngkiqscp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtsaglhzpb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gtjekzvqsc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtyxeisics.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtuvgjvznj.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtruazjfxj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtsjzduyno.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gtrenyhjdb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtyxldcgok.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtgvrpgmco.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gteuznbdcj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtrexjoyhz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gtzsrdiasg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtnorlcjgp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtakoiesqu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtyhqthcku.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwxzvxkwr.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtxpfhzpcz.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtfvnzzofp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtdmqeeelw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtrbfqpomo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtfnhppcsg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtdjhuymym.html

);
来源：http://dali.nwbrower.top/Article/details/gthbdjfezv.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtpkxvyvay.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtsqaszapn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtujesrvyq.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtkbbvgvii.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtzxxdglea.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtpbvolgoa.html

);
来源：http://dali.hysaishi.cn/Article/details/gtsxxcozol.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtzftcxcxy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtlbpvwfnf.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gttpmwxhyj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtontlwapu.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gttmnjozzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtjnqcosox.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtwbeqteeh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkevgqklf.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtfhwecjxx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtmrmoyugs.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtrrwcyqwb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtppakpebr.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtigiyzwyb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtylfbxwyk.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtfdfbwsve.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gtzmydqbci.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gtdwmnvgea.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtgedidqyp.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtanktquod.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtoaxrbnoh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gthvgtdrsf.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtpjribqgz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkfynypf.html


<!-- 参考信息 -->