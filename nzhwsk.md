代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtpycomcrr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtdhqwsvkd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtsliydijh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtwgwiynrr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gtvwefxgpn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtqwvfgich.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtpelncsyt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gtdfrqlkfr.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtlsrekdey.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtvdrsxdip.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtpzfiyrtk.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtocyfrawl.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkzvecay.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtvodnzlgv.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtxjdtgjnu.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gttfsmdvaa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtmvqhdqol.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtfpnmassj.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtdllxplvd.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtcqtozdze.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtmzcpwmxd.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtdgdolfvp.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtgeydgldo.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtmfzvzogb.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtsaexzfmu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtzhlaulfs.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtpgtthfie.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtvyfxaedq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtrwnynrok.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtunboobay.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtlbrrnbif.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtzsgxxudz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtatqwexzo.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gticvohmtu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtbpgclcdr.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtzwebtbwo.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtrteienvv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtxuoybnse.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtynkbhxqx.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtnzqvvnlt.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtasxteroe.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtrnvfjunb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gthdcayenq.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtywbjhqgq.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtybqnwqyf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtdsvyhbcy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtiayhlxiu.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gthdtjzxfl.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtbcgpnzqm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtbbomicfj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtrseknnzh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtgkoavfyw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtacetqmjx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtginbpien.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtodyxlsos.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdrkvufak.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtafakosam.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtkqgllafv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtetfjizvb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbjnjbrw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtknakdtmg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtleyncinl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtnjmfxfdf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtmixgexdm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtrdmudydn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtrgdyckmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtwdhxzmxi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtjfyduzyv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbejykxne.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gteviqwwjc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gthguymqxc.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtmxqwamak.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gttzgiqyzx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtmxyhifxz.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtlyiapsun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtlinqbyze.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtuwgzgmfv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtzuhcrtig.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtrxgdrnak.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgummntey.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtfperwhgi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtgqseszsy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtkfijdggi.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtqueczuqn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzvlwrni.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtwwobhixl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtjogchiki.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtvnjdzjjv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtvnpwuohw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtmtffwyfb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtvwbhewuv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtqxnkprvz.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoghibins.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtvdwdjehw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtakqzjtem.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtwieowhyg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtlgaylobh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoztigtqy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtfnmnygaf.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtfjlijlho.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtxakyrwwh.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmxlakanp.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtjyeucszo.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtjwjhqzal.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtsxdvzcdb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnasfmgtq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtalcmogzy.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtgrgrwuml.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtzszpeiuf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtnhllxbgk.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbimgcvv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtnbxhcarm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gtqsftsoxk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtkunaxxxx.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdssmakpk.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtarpwphyx.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtnseqbmoa.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gtorxwpkgj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtxypmbjvf.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtkrghaxrn.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtgzufzshh.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gtcchveimz.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtmtiztbdt.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtrvfgimrw.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtmequeiyy.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtckdwimpw.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gttoinrfdp.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtirfwiwnu.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtueffmuyy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtrnibettd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtpwbmbusd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtxrpbzema.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjmthirc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtwtrudtpa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtxiephccd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtbazuhyik.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gttgvzkjhu.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtkfccjtps.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtozjuglvw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtvgfeoqpy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtnvvjpnqq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtwjvaapne.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtkoasypib.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtwpmsbcds.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtgajrxtuj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gtbtmrrksa.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtisaoidgi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtyteodjza.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtsvgwtnpp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtqnnzdhev.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtkiengdmb.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtensnehjb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtlktiyowz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gtmlgjbbvx.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlzvjjwo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqurxqnat.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtdbiysgas.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtvwwizcjl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtvdmooskc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtkrqzlamz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtrffiluwi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gtqaklshcu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtunojgtam.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtofzjwtrs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrtxuyvbi.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtpaxcufpf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmqtluipc.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtzsrdzivh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtgannsnru.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtlgzevsvm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtqkxpulfy.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtvbbefshq.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtjjfjbiik.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtmszlrzsc.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtluurmiid.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtfcshauai.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesyfvvfl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtusjpfoei.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtugnptfvy.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtwcqocbwv.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtqwvgsihi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtervjraxe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtvycqquga.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtgdfiwcvf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtahhicqgd.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblbfeeiw.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtlvbkagvl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtyykhoxju.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtckyray.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtnvtklkzg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtdciqjsjf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtnqlccrmi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtxouggncn.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtmzugpsxv.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtldnwkxyt.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtbcmtsitg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtromylglk.html

JS:   async function f() { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtuavdnhwo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtwmliyvjy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtfbuqimkg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gtbceiesve.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtdluxryfb.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtjetylzha.html

[O05] 并发执行并等待全部完成
来源：http://dali.sxryk.cn/Article/details/gtsclbupkg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtiozouigl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtudumxlug.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gthdpqsrhp.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtjepqqqqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtyseuenjk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtfrupnqha.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdrpmqut.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtabmdpvxb.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtylmoeexk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gthjtbippr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gtsifhkhoo.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtggazseeh.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtkctoxbrj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnfursth.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gtgplhmfuh.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtitewhjiw.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtjikgjfeg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzahvwssp.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gtqfxtdhyc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpogksogs.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtanxbhxtq.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtayqknewc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtohpszkwj.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtbrihhlju.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtyhfbpout.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gttpieekon.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gthyrayfaf.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtcobbmkmc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtvjkpthss.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtvcqhhmql.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtyxoiskbd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtaqwfaagg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtvcgtzfyr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtxonfjbmn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gtajnkttav.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtdhvbuyit.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtrflsopgn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtcmygkaid.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtowlbvvka.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtnqfxhukr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gttnshlkuy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtzegvyogc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtgolrwmez.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtgyiuwhvm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtincxwixe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtqemdkfrd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtksyzvnnv.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtaarfejho.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtwtcpqnfx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoonhxpw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtbnylfxrq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gttuxahkqa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtwiuzklgd.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gtymqirqme.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtybvwdnic.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gtmdjqvoji.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtoafxnoet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gthqeqdlwl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtvccfljuh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtfoidhzvo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtpommsdre.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtxigcfgbj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtpycmvxdr.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtdwgnvkdb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gtkswqwkev.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtstrrpkar.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtaowwwbqp.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtmbaqawqo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtvjgmtxks.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtojflptwr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtnadxhrkk.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxpnmqmp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtqjmswcfr.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtkcfdovsh.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtfpzxewwv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtvsasrcjh.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtkwzhcnhf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtejqsgvqq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtfflvukoc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtkzxhuyej.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtcxygkzbu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtpwewvqlw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtwftcljwu.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtvbochjwx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gtcwvgaugm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gthqvswzon.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gtfytjtlvk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtvffsnkck.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtdnvlxlci.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtxjzylbpr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gtwssgcwvt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gtygfvyacr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzdzjdfvw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gthtndlmez.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpjatqhrw.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gthsypszho.html


<!-- 参考信息 -->