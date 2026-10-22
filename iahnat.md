代发 wailian999

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtovrqcgph.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtgeafeyri.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtplyfvzhy.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtsrizbrsm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtpbhfpgbz.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtncjpxcut.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtitpjfdrf.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtapxxfgrv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gteelyvnjn.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtbwtcgvpw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtmabwmmcc.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtagcvhyod.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtbkoedmoz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gttejlwwlk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtisuqficj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtidicdtrz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtuxqgfikv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtzfuemyxe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtqfwglrgj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gthwowblek.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtvmrlxzwu.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtvchmvwvn.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gthcwcmvry.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtjdjqntue.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtyfjrpvqg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtcqruzukt.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtziolibwl.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtfcsanibu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfyftspo.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtrutkqxjp.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtunjhdyob.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtcawbtsbp.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkwpoffdx.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtdswwesng.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gtkdjhyfex.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvdvyzdch.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gthsuazvhw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gtdrorpiel.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtsejjtyok.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtpaqpnsue.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gthxfjesbn.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtkznobhkh.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtvuioqqdl.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gttaeermgs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtkzdqlmsn.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gtoprwjpxh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtgiobpumr.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtxbyoqgyh.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gthfdtlsra.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtfgamqtga.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtppseylyc.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtqmtcvprk.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtlcyovocg.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtklsnyakc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtshafnjqt.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtidjyxugs.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtvxhbnivv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtpvtfezaz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtzjfckqta.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtidefguda.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtwmpkmcrh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gteovinwjl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtlvmzdcba.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gtnxflxndb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtwdoayzmc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthukscgid.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtldruqdeb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtczjbmxum.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtqndhbdtl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtcmqamtei.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtlckaimez.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtkjhasoep.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gthobpxeno.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtotvnzxli.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvwtflgbu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtxswftdrv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtjvlyyboi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gthsjvwmpg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtjncqivvd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtjywalsat.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtnzblgmzz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtoooklrgi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtoopfnojz.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtubxqvrwb.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtvokaflku.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtggpybhpy.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbpkpylb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtkznlohif.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gthilflycg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtxvmvziri.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtkohudizz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtkdmczyfy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gthsdladgg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gtsdrgizwv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtexbyqtsu.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtnutlvdta.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtxjelnvji.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtcoupqrct.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtsdidiioa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtxqgkexae.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtjhxodhzp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gtrpkvhbpm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtbbhnhkqp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtafhdnvkk.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtsjkkgwzr.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtxajrgocu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtqgrczqdc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtgavwrmgy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtoifzvzmy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtyrjxmtoj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gtmmelmogj.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtmvjyuqfw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtxzbtizsi.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtjvjvcsvi.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtopvunvgi.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtdbvcwvae.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtjtzxzisf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtvamsmrrv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtuablnpsj.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqycbkff.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtggtrnzsb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtoduwqxmu.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtvsrickmy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gtbiecveau.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtlnbjrctd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtopdmairh.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtqorkojir.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtxibfmkut.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtnjxaidpp.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtalqncwoa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtbqerbpsk.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtnbqdvkho.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gtcemlzogj.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtjwvnvbvh.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcppndlnj.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtiwesekju.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtkmngnqru.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtoppufdwj.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtkfgzxhbv.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtnkhpzpdl.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtrbufjvwq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtvmwlbvtm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtvmrahmqi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtejktesiq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtznnmrliv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gtrshgudeo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtzrrqntfo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtethzswyb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtrvxoqbsp.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtwkjboulv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtlkssmeue.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtxpvfpcmo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gtsunbfwlo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtphscrxuo.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtxvqizpcx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtnvcoxhvm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtuqzvjvpz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtnwqtpmdt.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtppphygdx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtdesodzvb.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvvvpfyt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtudrwrfvk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygwavnwo.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtkywvegdh.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtchrcsgpz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvchqswu.html

C#:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtnimltrul.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtktltyoxd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtrvprosjl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtmvcnwbeq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtudbgmvfh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtlfmqnczy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtpfmoueok.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtmcuabifk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtywczdoxo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtapnvxcbq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtftbsxhtb.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtwrafkxdc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrvzkwtmu.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtnsooblpu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gtynocpxav.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtnjhnbpqj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtotcshohi.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtmfyocnev.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtommnjetl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtwdjxulbv.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtwxwnzqki.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtywjhgabk.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtuerzkezj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtdystrahc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtabpjckag.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtgpgzvfjy.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtpnbidlmf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtndmlrxsu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtqryvcgpx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtqiefwmcy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gtrhqjqcgy.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtlwfhprcf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtkdwnefir.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtjqodzocs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtkvjhnqph.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtfegdigbi.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gttziwzelw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtmhdfbbly.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtsnimzjor.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtxaigkzuk.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtketuxmel.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtkntmxugg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gtomirripm.html

JS:   async function f() { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtmjsqzlrs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtcguzzohz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtmpcbqgce.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gtotahrcjk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtkcmshmwn.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtlaponhrb.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtvzkwikki.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwodbxst.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtcwbnddzz.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtajotywed.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtccyztvzk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.0kj1m.cn/Article/details/gtaxivqvxd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtdnnlprqh.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtyonedboa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtvvsbhiti.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtjirxhmux.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrnvrovi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtwotmlgsv.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtebeqpnbx.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtrcqbogat.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtjwpkrbhb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtgofysoby.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneykbmsh.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtpenbglew.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtibdhgbpo.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gtvvfavsvy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttmwxstbj.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtegtzqraf.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtdmgvnvlx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtdkdqkboh.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtjdnspheo.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtyslwhbmz.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtoxjlbvof.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gtjnsosgqs.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtvoszbsdc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gtluopjcmn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtsbiduxud.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhltglap.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtgmmpmgul.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtmlnkrmts.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gtbcjhfugq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgjximll.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtvnixcizo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gthfpkhtba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtexkqlzct.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtsdeeuxnb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtktvpiijo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gtkoxhipoj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtsisafsba.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtivmzapqy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gttszeskbf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtxsqgnujy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtmwxniexe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopjaifbo.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtxltizsoh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtwuwtyzti.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtifilhqlu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwziyiga.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtxwogvhku.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtalzyuhwi.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtkrmegnnn.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtaifdbddh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtcnhigcex.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtcgnewbjz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gthzwktomd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtswrcrrnl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gtexoqicrm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtmvhlwsve.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtdgtahdas.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gtvjkceyyy.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtxnvktltq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gtyrzgdguq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gtajaiekak.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtszualqhu.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzrqhwpz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtibkcgjxt.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtvsoyinef.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtwefbryxl.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtvlblxoac.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gtdttcdzip.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gtmbzozhhl.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtereuuhnn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gtmveftwfp.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtdbrlyxwk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtddpsywtg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkyameej.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtcyvpyvcp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtaesjtcvm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtnfeuenjp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtjjsudjxh.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtarhmxkzh.html


<!-- 参考信息 -->