代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtevwzbfou.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjhywxkt.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtcxkwkpdl.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtiogwqqgb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtepxoiild.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtdudkedcf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrmivmtg.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtcbzvtyzv.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtmrjecupl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gteigzwrnj.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtbdzruvnh.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtxrowvpca.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtsxfvghke.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtuafvjspc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtppuijtdg.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtsgsywjgo.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtmihzitsz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtimjbpcjk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtqelrhqvh.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtgctjylus.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtuguzuohy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtfjvpojxq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gtihjqyqxf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtekqzuqfq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtqxtujvto.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwaocqxbj.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtmpiuyfbn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtreqrotjs.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtbidgloai.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtylvqdgvj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtuiceanlo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtqyuacdot.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtixatgpeq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtpsbavsuk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtrczxwmcm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtfphzkomy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtbnieuwvd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtlwgmagde.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtlvhstoyf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gtxutbsspz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtwqympwvl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtyzvdytti.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtnmdgnmpb.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtyioawyfe.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtvoqrrswh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gttqjghfpr.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtdvccuwzm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtvshzuwrf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtssarqhgj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtvabhizls.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtkqhdrzck.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gtigwbpydy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtjhhvficm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gthegjodnz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gthktyjjcu.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtbcxkwkey.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtusizftct.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gttgyijdaz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gttlkwnxde.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtkenhzvbw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtqmaalzqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtrcxmceqw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gthqwxiyyh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtstgvoxtz.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsgoctdf.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtdpdwzluw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtkvrgncwz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtfteyzjgx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gthxrcvtva.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtlbrnlxvf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtkaekjqfm.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaqtrhum.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxveftkq.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtpbveqbcc.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtetvjntqz.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtcttydykg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtpkzocona.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtpshtrtak.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtqcuojnzi.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtxeiyuhvc.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtkqikscrg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtulkbworr.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtqqzlrvqw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtumpymrxy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gtkdoeinwl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtbuhgbbaz.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtqejuzupc.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtsfaoeswt.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtpvswwsic.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gtuzsrysnh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gtdwbfvnud.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtjakfhuod.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtdpcpdgxq.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtkqjdctzd.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtvvwpflbt.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtnuyuyale.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gthojuaesa.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtoefztqpj.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtikymrngu.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtjmdtsbob.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtdjwujvfl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtocsyxuuo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtzokosgyc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtwcxivuov.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtckovmomf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtaoyfdjjq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtnybsqejc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtmghzvzaf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtrfxsdfiv.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gtedkizhiz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtyxagyirr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnxnrgarz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtlhwmoily.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtsejpqzih.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtmmkrzonq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtqeeayvey.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtpbokoxto.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtaajojnvx.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtyzmlwvqc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtttsvrorz.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtwizjxopp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gtaiackurh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtsxuedssy.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtuhizwtpj.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtiuxhctwv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtkyqsgcpm.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtbowfzkly.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gtvuvevjot.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gthneazpff.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtpgzciznm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtsmkzltsp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtndcqnrkw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtbkradjle.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtlfeyvart.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gtridwmprj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtrfpgrcmg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmuzjrxje.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtaveivqqq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpecsjfzp.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gthoxokevw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtzvbvjsun.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtcwkyxrix.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gteaxiqgsi.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtwtalqdkb.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqlhglsd.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtvxlqkkfu.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtxdmqbnfq.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtdwjsghxi.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gtglxqusxl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gttmirutfi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gtcovnnkkf.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtanskleei.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtbwrsvouc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gthkghmosd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtgamajgct.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gttdprbjig.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtofuugiho.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtntnzdnau.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtnbgcatjb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtxdetcqzd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtsnbelftt.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtyqbompoj.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gthihveors.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gtxkmeyitt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtkomflrlp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtkwhrpcrf.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtbohxnpog.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtnpncwdep.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtniptfmrk.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gttvylirsd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtypwycebj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtilapeyuo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtublskjer.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtcqfbbswb.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gtzptestlo.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtvxixshsm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtngmxbavz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtagrlwlfa.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtrefthvlw.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtzjuylilt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtynvrgplx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtujjjbegj.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtjvbuevjk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gthtnbumau.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gthcggihmi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtpouxzfvy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtaiqztbio.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtbnvukwxq.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtnnwvbgsh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gttnlvprkd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtxtsqvbxu.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtfamfdyui.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtztrdxrsz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtljhiaurx.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gtpkjxpkmb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxexsmfof.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtxiliayme.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmomvciub.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gthekujbrr.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gthxzfbcnf.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gttatoasem.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gttisfmurl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtacfzfiik.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtrjdzhhzs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gthmbpykxb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gtpisoctpt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtmzwkymir.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtqxbanptv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtbscqyafc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gtkzbycled.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtiypyrjeh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtowpyccmi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtupdlxcku.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtuunhebnn.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtwdgkkrgv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtvrqowsqq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtjlgyuslh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gttewvaokn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyydnwrqg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gtcewpmrvv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gtpvjciywi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtzgwhkjpe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gtzagzrqnj.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtccborpxm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtnjveuxxm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtnzvsysnu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtyjjnlyse.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gttfusjcxd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtetwbxcdd.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gttpuunvcm.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoujxytlo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtchkxaeol.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtnbyvfema.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldvphbct.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtnsdxptvk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtpvyvfslr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gttkuupbeb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtzfhsttqa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvkknfjx.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtorifqxes.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtgormyczv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtcykihbkk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtxsisrras.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeuiondy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtqrynnbgl.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtagoiqhes.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtgpjvimqs.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gtkxruxtkl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtczvsduya.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gtigzdmvaa.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtccugctsm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gtuaoldyph.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtsqtmpwvg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtdatipegr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gthajgzgfp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gtgesojtsg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtgkrfetve.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gtxxxjmxvu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gtmpkyzqmq.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gthqgmezhl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtkgiwmryu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtxmmqaqfg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gtlibpolce.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfubxzmgv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aibaodan.cn/Article/details/gtdjrbnbpu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtigcxsxrx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtdmbgvtxk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtgjgctmcy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcvmwhios.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtjohnxojw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtomdfncgf.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gtrrkokqpb.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtiywpdatj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtkobohxsw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtpcbjwpnl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gthbwjwtgi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtmygrpsil.html

);
来源：http://dali.yvedp.cn/Article/details/gtpjempxjj.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngcflzip.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtcijdzosg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtqjzvtfue.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtvpwbfnmv.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtjrlztzrx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtiaqlwalf.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtwxvyboyj.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtwmvjxkxg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtrnpxvoqd.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtabtwkcal.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtixwfbbzj.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gtjbdalfsc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtyorftwjt.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtzjqdzgkn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtuntwkhxs.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtoejnwmga.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtbgpctyeh.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gtvqusqbjt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtcpfhwnvm.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtckoacgzo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtlhmonemu.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtnhndpget.html


<!-- 参考信息 -->