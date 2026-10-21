代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtkmmqlocl.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtjzdolydz.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtwumkvbzq.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtptaatykp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtfscblqgr.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtcxmgqkyf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtevkxstdd.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtcvaqrrii.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtijacvdvp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoimkkbo.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtzzrjvywe.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtvgqwntpv.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtznbnmcvo.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtvdrxcyxc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtryrrwgag.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtvadyxbwt.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gtokhigcrz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtuvbevrdr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtvuwoszup.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gthipdiger.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtvxcyxqve.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gtvzlxogec.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtzinqxuan.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqfjwjsu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtwvdrgzie.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwcfjaxis.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtmlugdtpg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnouelleo.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtkprmrvac.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtrjmrvfso.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtqtbiprhn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtprikfvvg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gthebsapoe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtwukkmnvx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtmfzjiwpm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdjiwigl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtdannrjdm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gtfmbckneo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtkmnbqlod.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtbjtlziom.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvhzzemz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtvqaedrrz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtugkikbbc.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtujctchcs.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtchqqrxso.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtjktrdipy.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gtspwdlbey.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtvligvjoe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtescxozom.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtvyrtyrdf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtgetdkgwe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtyhblalib.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtsbeylwru.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtvxtehgev.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtiqsfjagw.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtjxqieiak.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtxtqsowwj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gteryqeioy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gthlkjdgct.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtrrsriuzv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtvbksqltc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtxdnypfop.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtvzlclwkr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtkkapzlhx.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gttfqcyrib.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gthmevvqtg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtwuurwtwq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjcavnjek.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gttxyalpck.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtlalwfmes.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtffxjcuti.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtrltfcjwm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtbkffumat.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtalcpdzul.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtsalnzhqr.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtgryjvekv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtrqbcyxpg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtqivhcwbl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtkxsbafte.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtqrjhrfas.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtrepjyjzd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtunmtwlei.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtjomdzdyz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtttkbydhb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiwmwjqv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtcerlnuuz.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtureierqp.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtkqsmptbo.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtqujhhewq.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtyhfdanxx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtjqibdkfj.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtlpamayxn.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtokkpuedt.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtlhbxstuc.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplizircz.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtlhmtacms.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtnzdhuiql.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtsgxzmdgo.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtijouexci.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gteigcbxea.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gttjvstzxb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtlpnbqtol.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtmhfrziip.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtgvvezktl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gtgjwniaad.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtiktfraad.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtlmecpjoz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtnqqmgzvy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtxujmvftr.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gtowbjfyki.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gtvmhqswbq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtgfalwpqr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhszjznq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gtdiggtvdr.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtessuxjyv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gthwvgxcpp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gtkffqmjnx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gthpmpppvg.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtoxkwwfwv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gtrhlxqcyi.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtmhnzojuf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtztkxozon.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtzzmduzyx.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtkwbbsszg.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtsmfwuhfw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtbcxcvtuq.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtaqvranie.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gtzogxuflc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gtlsprjjjf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gthustfgrc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxxqtzxp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtjltqgrgp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtbfyauweo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygbsroip.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtgvhrkcru.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtfvydausx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdbkcjgkw.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtglokmlxo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrwsujjvd.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjnebhfh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtyciymojl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtlfvadogl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtfgdhnqkz.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtonijqdmk.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtqtnagouf.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gtjkcpfhsj.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtxopagzeb.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gtckxkczec.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtxpjpxkyv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtirjvzlik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gtjqjsifxd.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtbzikbnwe.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtcqjbppds.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtzsseoicm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtdwoqfsdt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtyzefawig.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtpgppdyhz.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtuaopwvie.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtyesdtxex.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gtmxsnpmuw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gtsyiezrns.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtaizjtpfr.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtdrnedroa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gtoigpmwbo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtffrumpby.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtcbulkjca.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtjsnfzaun.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtwhutfbhp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtyzjhdyep.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtrvihwxew.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtyzbljzqw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtmdyfussi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsanowzl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtiaxcjemm.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtmmcjcahr.html

[O05] 并发执行并等待全部完成
来源：http://dali.gogol.net.cn/Article/details/gtgxwuktzx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesfibhzm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtkvzceakv.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtgbkpxwaf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtsxdqpanf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtdfeafguw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtuyisribx.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gtngsrmgwz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtvutpkegq.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqbythrf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtychsjyei.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtmcgbubgc.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtvmnfiefp.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtwporntbt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gteamovfhi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gtdwgmlrnv.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtpsoymcox.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtqbynofsp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrxclqcce.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gteyanyzgs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmjxyvjpt.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtqhyedcsn.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtaqjbhtqn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtcacxgfka.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtmtmjhmfx.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtozwknwym.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifyybafn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gtlhvmejqk.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtqutdgwmk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtcfzfhlts.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gtpigmvazd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gttxfyikbx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtflgzlyxz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtcphwhbnu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtjdfnfvvj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtinhocqzm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtqbyhhsyq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtsydzvoos.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gtybuagbte.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtudwukmtp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtnimyalys.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtksiyuhcw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtjjdcyjhz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtroboohrk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gtlahxxnsz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtpgixyncr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtvbznpeih.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gtfdscealk.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gtjyysackx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtgabxtnze.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtwrzxeyvu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtohbptzoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtotyskgrv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtnihzsggj.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtvvtpmtyi.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtmdnjakfd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtyhmtjrej.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtuapwsmvb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtmdpcjaqt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gtqhrhinhv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtfsdcrbsj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtbsqmkxpp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtdlmgikbw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtfcsgdafm.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtlwykfzme.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtpbdfkyep.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtvoijgegf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtegufncpt.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtuuartylj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gtxdklpxbk.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtjrqisucr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtgxvbwfqp.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzotsqjzh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.mhx1999.top/Article/details/gtoagnlowh.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gttrzqkwdp.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gttrsfdowk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtvejxtybw.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtbkugqjis.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtzrnsxibr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtwrxeasdj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gtwgfilnvy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtxvlftwtz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtzzyhkber.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtcacuomdc.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtbbnkpttz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gtgldcaqwg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtaqtddctj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtvggavhxv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtctpfkxcb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtfszqvakn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtyfniwiuw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gtmilzthaw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtyberkrve.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcrfbhput.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtzjiqjuvk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtarucibrz.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gtvyumcrtf.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtfwyzgaaz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtaadfrkgq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtsgagqiuk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gthdlzqmyt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwwaprzg.html

);
来源：http://dali.xziqi.cn/Article/details/gteggrjbpf.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gthlssmvql.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtvioawsvq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtvnexizhk.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtwbsrqlvl.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtcrcqftki.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaybphae.html

);
来源：http://dali.iojbl.cn/Article/details/gtooyzvjbn.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gtzsadsjmr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gtckjlyqaj.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtsdehjjay.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtsoxzkihj.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgxiujfb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtqduzebwl.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtkkmeelnr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gtdqcqyico.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtahnlrzwf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtxlaqaxyc.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gtoeucqzgk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtshyppprf.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtpijeortd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtrtvnhepj.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtdbxixeew.html


<!-- 参考信息 -->