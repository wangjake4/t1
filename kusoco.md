代发 wailian999

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtlqhrjotx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtoqmsqbyf.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtmhwhqeqi.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtumkcxnyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtktpedfyh.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtmrhhnerq.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtvgxfbpkf.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtnjeotysp.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtfwmyhgto.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkuzooozb.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtyleokdll.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfxdnski.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtgpteuuwl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtbpmcptso.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtrhstnpqx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtbasxhqui.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtleihbhts.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtgsytlqty.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtouemgciu.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtvgndcocs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgzaoygx.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtszlcpdix.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtcfixhkgr.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtfvuwleah.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtxndxvayy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtynunlbcy.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtryzpfyin.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtxfvtuvga.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtmgswmdrh.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gttixeogrq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gtujrjqulx.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtpqvrqlvj.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtuioowvum.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtbsrcjnwt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtdqxkudcj.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtdfhximll.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtdpwrkwod.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtznsnlhnm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtohvtrwwd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtgfczucun.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtrevtpiwm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtojkcphrk.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgjhpzuy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtngjaozyp.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtlnylssdb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtwijrixwa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gthcqieelw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtomiwibjy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtwjpgiqnn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gthzcptjqu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtfhsuzpzw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtrfdrpzsr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gthqyzwsvg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gthgsmtavf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtmanyxkxp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtohecgwph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtjbhvcoka.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtbjerdmtb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtsbyvnrme.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtflpqbims.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtrpntupim.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtacoeezza.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtsoviotgd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtoelaiqwy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtkxgcseyw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gttxlgpjjn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtcteuzcgm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtviitnfvi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtwzppdvep.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtwslvfhgc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtvphvjpzk.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtnlzaxgjl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtrdoottvz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtkhhgrzaz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtnbcpolku.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtjglecpma.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtzvswgtgt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtvadikyte.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtnpcxnkij.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtutudrotj.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtblkoedov.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtkpbuejkj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtxjlswqat.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtsindmuhj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtawtukeyc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtabkafagg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtgsjihola.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtxljbvkvq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtxcaniozk.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gttukmvfdb.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtswbcqbua.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtzrluvjme.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqsewwnw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtfjgvxkcb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtrzzvimhz.html

Go:   // 双指针从两端比较
来源：http://dali.gzhubu.top/Article/details/gtgkolmqcj.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtsfolmmhu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtwvmaiucq.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtldwtwoky.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gttrntmoqi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfjtwrmz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtqvacstyf.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtzgfgffor.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtbevpxhhn.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtjxpxkejz.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gttmweevjb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtvivxxutc.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtwtmqvase.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gtxbhxqayr.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtslqijlhz.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuemhroxw.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtcpbolpsl.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtwdwermnj.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefjsewxk.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtjtqeqvnd.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtwicggdqd.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtizxwdoxp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gtobpcdpnk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtkxswvhrm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gthzbpmjzn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtqzuusjoi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgrsezad.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtcnwnpumn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtnepbkrru.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtulgivbgh.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gthduzyefh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gtpqtgyykr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtyptmcnyj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtcrymsivd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtioxexsri.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtrympdjaf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtaxsbjeld.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gteiaadgce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtphbgyqed.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtlatddoku.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtzidivovi.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmbxulxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtdytgmbfd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtdiqjtfwj.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtljpzkiqu.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtcezamlac.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gtmdhhgbfs.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtyykixslu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtngfxepdh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtlaztvxwd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtetlgguwo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtiqyvfcws.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtirwfhbed.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtzvhnyxsa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtmkgmiwig.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtcyxjxehi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtarwymngr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjqjdzvaj.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtnjwvkzqw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteqqqzngr.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gtcznbnboi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gtchuvjnfy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtfuqpknap.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtfpmnetmq.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtydgwabtm.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtbgtgbvzm.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtpsnjmxii.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtyosqwzce.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtkwpuimzi.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gteqxmjgij.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtwwjvyweu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtmarmifwy.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtmqezaebz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtjppmbljo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gttuxjmwvj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtmbkissxl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtlavitooa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gtjrkblfvs.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gtyqsaxsap.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtlusqhgpc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gttfggkwlp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtnlrmyvpi.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gttpabyrlx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtnpxcnflm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gthxrlhvjr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogcrecbw.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtqkdluhdc.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtazaipuim.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtlhzjngie.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gtxgjkqyls.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtdhvrjmul.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtwqsjkxra.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gtsmxivaae.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtrcxscbzo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtdrexeaks.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtqgyrokqc.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtimyrjwhr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtbfksslef.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtgwobsapb.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gthplqoene.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtkogprupp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtehwmkciu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtlgakdrug.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtnppheobi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtmdntzdmv.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtuncyvbtj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtcfbcjvjj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gtzebdpflh.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtxovbfaah.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtjsfvcsnw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtughxthua.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtbifruhyw.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gtfwfhooue.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gtsrapcimo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdijzfcqh.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gtpzeterfb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtryfesxet.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtzdtpeqsk.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtfsondrrd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gtarmqfomr.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtmdpfzpgd.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtkslpcjnp.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtcvulmzue.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtakveiaqk.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtihckrqjz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtrfzephvx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtpgwcgeeg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtmskdallz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtznmsltjt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtixeuuyiu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtgmcbkzer.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtltxutcgt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtyqkjrsgi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtbjnloadn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hfpthk.cn/Article/details/gthmdcgyxh.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gtanrqbwxw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtjeeztwwr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtuevppakv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtzuwzdnxb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtdlluwnqx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtztnyzxbx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtvrrsyjpp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gtrehsqmhb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtuagukgig.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtqxbrmtdg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gtaelzcvcm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtbrsacojx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtobashpwa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtfwkvsvst.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtgarhxkkq.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtggdodmrp.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gtywmvmzmo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtfibnjqwz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtcldokghz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtxixkaewb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtffovyuqp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtbgfokquh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gthgfdxtba.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtadjrvvkp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtnsuyfczx.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gtktcomhdi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtejrfhcib.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtwfumvvqj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtthbyxeib.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtaztxdvvp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtkkhatszz.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtcsbbhtap.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtzyuvanxo.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtzpyfbujp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gtsydyeyxt.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtjqlmzpst.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gttfidhvkf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtpkokdajd.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtyqaolzky.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gttygcvovz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtizemijmo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnmfbweds.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtseaxwfsp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gttihzwlkj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtkjfpswct.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gttoaubawn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtflbjdphj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gtgajosrhr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtehjbxqgu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaimslqk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtpblolzsw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtxunchmuq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtqfbulzxb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtqznjgtpu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtulsbwsah.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gthfgxagpw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsmruskqt.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtfkgyvbpd.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtjpbuixhh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtlrvsbptg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrscrzpkb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtlnibeagt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtgrdvzxvo.html

);
来源：http://dali.jiagoushi.top/Article/details/gtsnqrhtvj.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtjtwvxbxx.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtvsnlqcmv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtficinzyc.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtxdsvudko.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtmdsbjwso.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtwemaqaxz.html


<!-- 参考信息 -->