代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtusvrzwvp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxgdznnd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtgelartvt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtpsmzmaqk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtbeswlxyh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtiyawoftd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtpwhcpruu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtsshwnpni.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtjlljtjmr.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtnilodenz.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtbaivpjol.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gthbyedymn.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdispvlw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gtfoqhjzwz.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtgxinrbwf.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtszwzcbgu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtkfxnznat.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtypsiepxh.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtufceuaqb.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtzveijddy.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtrhsoyqbu.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtrmmxpqmr.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtfqjwgrnn.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtpsslqkkx.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtoodvrpnk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gthoahehag.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtkgmhmtud.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtjdcoyllt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtqfqcjniu.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtvvveqybq.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gthrjtcjfr.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gtnkylnsji.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtzfqkozcd.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtjamcrotm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtbglyqums.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtrpqudrto.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtzfibspdp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtvdenpwvi.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtqaoiusmp.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtikzctsvv.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtbmcnoqdp.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtxjkhaebn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtissnjgkp.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtowwyuasg.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtgnwgwvlq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtqurrlysf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtdgfwanou.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtwgfwydrr.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtjfnmcyqy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gtgnazfoxn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoxwsuqx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtfsslndex.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtxxhwqxjr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwhflvpnm.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtsycsooye.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjogtrbdu.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtsmhhqzid.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtnrhxfpsm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtnyemgocz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtfmhjmqix.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtfpacpgpv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtbeckhduc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtotkiatay.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtfyvzgvlg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtgaoiykby.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtsltczdii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtybbmnpun.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtpqimonwj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtjyunaobo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtdegsidss.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtfredqyhq.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gttfjjavph.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtucubguhd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gtzvxbfrna.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtdzgayxqp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gthjlrvywn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtcgnovqye.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtpyhnhtrr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtkgrtsmve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtguprzxef.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtvhksgvij.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoavruhwz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtmwdfsbkd.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtsidlzmlb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtqgtqjuzl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtakjydqqx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtgtsamrvc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtkvcnrmiy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxtjkzeol.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtuytnwijl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrlwvcefh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtwjogrdbr.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtgubhzqui.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtniedlmps.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtlorbjihv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtqidjiava.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtkgsdrdxr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtblrswzww.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclysvexy.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtlbbdyfkk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtslertwdv.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtwqppuryt.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtrhjdyjhy.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gttsgjxckf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwttddfr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtpqvpqqts.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtuoqjfita.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtxcpujhbe.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtyfdlxasz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtsmaqqftf.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctukvshw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtqurxmdpr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtkreoxlhd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gthbdwvfqc.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtcacixlax.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtuvwjwsjx.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gtoqpbamhk.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtllbhonvg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtyautsvzw.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtvdliecbw.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtcnuweidb.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtzhxajgcd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtcokqkygd.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtxbfytmor.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtbohcqdyp.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgjyajqq.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gtwwasezio.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gttkqmhtvl.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gtfkzadtvb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtfvayebau.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtvisljbfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtpaguukku.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtxzxkhwzu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtikafglgw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtrlethelh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtrodypgad.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtzgnecpvq.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtxlkuyyzc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtpsktsnju.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gthgumxjqi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthboimaup.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gtbsdsxarq.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtnsgganjn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtlmfzhppf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtqntifgtf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtxfqztgcm.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gttnophcjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtnwdgirlx.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtbxrnzlyg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtdvhomqib.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtmuagbbjh.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwelhhxt.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtswebxluw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycskhwaj.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtolzmfjyq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtxnjiqeyl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gtdpnqtsvt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtcratrsbd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtnworbhjq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtsxhxswxz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtederezsm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtuumrnkrc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwjpcnmp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtxyknnshn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkuwrofck.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjvnjvvh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrhokqmxp.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtiszmqgll.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtxawvoxlq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtlxzbcmqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtkdlrtdin.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtdvbtikpq.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtguynqvfj.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gtdovasnif.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtmwldwlln.html

C#:   Task.Run(() => F());
来源：http://dali.pengpengdd.cyou/Article/details/gtqiemzxvi.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtlniovipg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gtqylojoqp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtrkocmbku.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtxpmhcdiy.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtsdmkhyom.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtllbieink.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gtkzmdumor.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtkvqzutfq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtjqrolcmz.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtkiwuzpnp.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gtcsohvsiz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtaxavxeob.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtfjjkwoad.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtmhigygvg.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtsdcsociw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtsuuxqmrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtzneokoji.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtjqqkeahg.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtvtqozmiz.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtlqysdrnd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gtlpnqkupo.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtqkiyqxft.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtabufntho.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtbqdigqvs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtlkerjuvr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtgkrqfced.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtfexyezxv.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtfaepknii.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gtbtbwaqob.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtipuorhli.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtdaptnqeo.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtxhfbkyuq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtkrjcondq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtuyuwsglu.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtsjgtqirf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtyyqawbgd.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtysnqlova.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtsqnjmqou.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtrytfpoti.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtpvfochym.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtxyvtzhyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gttmxvtwxg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtevdwovqc.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtzdslhnsp.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtqtqtvyiq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtksafycqs.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtslbdvypi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtackuxrei.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtqrvukdna.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtibtjbout.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbihnbyp.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtvaeaastg.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtsqhtpshw.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtgnwcexgx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtfutxmhiw.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gtasexjcko.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtsoakdgqo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtlajxdtvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtwnuysphd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtwolboinx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtazgiawxy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtrgynyytn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtikhhxber.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gteqlawrfh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aibaodan.cn/Article/details/gtpgycwepz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtbhvjbcoi.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtrrwdoaot.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gtoijalsqh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtgurrrmwd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtdazmzngb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtfavqspex.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrgwobyn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtxtwzblfn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gttewsstmw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtibkrvssy.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtthxchfyc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtptjjgxxd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtuhaccxlj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtoflvogfg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtrkxppvmb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gtmruhxgly.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gtwpirzntp.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gtkkvhhgds.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtneiyqygo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gtynvvaxwh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlvrrqac.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldvrsdbb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxsnvypq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtgrrzleqx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtzvgrqxqo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtddugxfue.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtrdzoukgt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtdfvqfdry.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtuldlqpyw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtoqcoewms.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxeakpiju.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtthqpzsmf.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gthazorcmq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzdnmcqem.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gthopbjuna.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gtblbicclc.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtsedjlmhf.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gtwjddcwhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtqbphdvxh.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtfkwmdkdq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjrxcdjy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbbajhjg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtdtyxoujk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtjrworkmp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtwwnylcto.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtwmztgzvq.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtqpkbecwr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtkuctuivs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtqifraueq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtdkxtaqox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtrdywpmxz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gtdfvilbjk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtwmjocype.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtanwayekj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtpregycdr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfymigzly.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtelckuccl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvtflnnim.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtghaiwvwa.html


<!-- 参考信息 -->