代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtfruovhcd.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtxwhysulz.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtsjhzdvys.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtfyadzkgu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtkqelfykd.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtizczjplm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdjbvoln.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtqhstpnvi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtzzvsjusi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtacxtoovh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gttwccogil.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtkfwakkrx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtbudtbcjh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtqadlifbz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gtiyillxfa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gttxvfvbdy.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtozfahsjp.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtrgusgkim.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gtieyjuavg.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtbzdzvpvs.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtcxvzbsyy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtyujuofok.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtpbsjwbxg.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtbkhsawsu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtruaxmcoe.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gteqhurspe.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfmfykwpq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtwrxhhins.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtlhfiibdm.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtumvjzavk.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtyljkjrot.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtinynehyk.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtwosfyncu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtqlqtrjam.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtkbwbyozm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gthlhvfnhh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtmeklgqoq.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtpcknmkww.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtstyvfnpt.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtvsdeszcw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtekcincid.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtfwctnkrp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtvifliryd.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtxxykjlov.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtvssttuhq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtyrfxorog.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaezccibs.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtltjnsntc.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtypuqurwr.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtwanerfot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtfteplcll.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtbdmrtrwt.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtyossuxna.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtgfohwuik.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtwpduepyz.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtihfkjifr.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtcvuphyni.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gthjdaghvn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtpihtefgh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtyyusarfi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtejzozztb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlpywcfyt.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gturmgktfi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnjzpfyvh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtblaxtwph.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtisztgtvy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtebuuiina.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtcvtxpmyj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtpbyhmocb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtqoqfkryq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtipkwsmav.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtgygnulyb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtbhntsrup.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gtnlpjmmeb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtohylzfne.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtfrshiqix.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtnpagrjoa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtrsiwenpx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtpdjjgfcs.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtrzyxgyqp.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtnuqapmsw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtfnvlobts.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gtcqjqkxay.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtyozrkaqi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtmwqlpcxk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtkdqkapjb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gteiyjnope.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtlskthoys.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycapvsvg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtqqbgfyvo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtllqqmowd.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gtdasaxbzm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtlayhokix.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtdpuqhqey.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtxsbkozaw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtzmyaijad.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtayehersu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtxfdwpsdm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlvjwqrr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtuabjsgwq.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzffpcrz.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjwduxxf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gtwcltmmtj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtuxobqjlh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtjykwgkku.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtvpabnyms.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtpbubflgv.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtahpitoxv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtgetpnqmm.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtpqfmzebh.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtknhqanaj.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthwixkogw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtjaorqyyg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtbalzpijn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtdhmkeiqx.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gttoiyxwpx.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtkymelapu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtkinivijd.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfjfvppy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gtuoaxdtvz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtrmvifizt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtditvdhou.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gteachxpny.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtcndcrkhy.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgbprpnn.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtxedktljo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtnkslhlqf.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtnkuajouh.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtljwpwpvh.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtatraqban.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtepwivupw.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtzlmwlirr.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtqjwtduhm.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtspxfrpqs.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtrmcrorbs.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyisdueg.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtvyppqvfp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtpcrucznc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtpltzkfkv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtrlaystyv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gtuzmrwbgu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtglusrzxo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gthjfiskax.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtztpintbd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtmdfolpbe.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtxzeiiclk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtarmxwfwk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtgxwwabwi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtblbnhvkm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtwfgseabj.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtbrldevqp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gtrmurkrvq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gtceaoxnra.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gtzgnfsgry.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtfssypezz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtfaqwhuck.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtivkqkdnd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtekvciocq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtfghzngzm.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtmntgngbu.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtpffsxvmi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtguakkndg.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gteltfhteg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtqbhcquiu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtlsumlclk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gthcbilqir.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtlytoxklr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtgmmhaxbw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtbeztlfpg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtywmctcwe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtqrvwpaof.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdevfbtl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjkvrelqu.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtvdgnjity.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxcwqngjv.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gthknluinp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtwufdfhne.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gtntpzmvtb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtibxiigps.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gttraczhcd.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtyycgdanx.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtgzeqrbpw.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtjhgslsis.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtxrbmbgev.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfzacffb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtlwjieqok.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtcktatbtc.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtzgjllwla.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtfirizbdi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtwaovzznk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtdhgzadmy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtscvwpvzo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtejlgeefq.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtvobvcmim.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtdjlggggt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtgsmlpoyj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gtwwrdffvv.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtjnnqskpj.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtdylfhfjt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gthbznuqum.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtlbrrqeyy.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtlrjphvqw.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtsovrdpkr.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gtmxlpajhy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfruhahv.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtvhppkakf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtzumcuxta.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gtdmmmkjua.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gttowdwtul.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtjbpxrbfs.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gtwbohumnk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtztebbpbw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtzkkknnqg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtgxzleaeh.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtqvvltvhs.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gthvjlyaqk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtheddsvds.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gttowhoxci.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbbkebqu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtmkpkxvvh.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyqvnbol.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtvhokyuxf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gtnjqhfdob.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtrbofcsfc.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtenwwyywk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtglrvwnwq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtaqiowhft.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtmqizpnaz.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gthhjmspst.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvnopqszs.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gttsdjqbsl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkuuhbhdk.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtrvkbjscu.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtkdbtxknj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtrmrbdcha.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gthgobapnu.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtoykxflkk.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtnmykmvad.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtxmfpqxpb.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtattwrtsx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtypgjtlqp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtxiddutfz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gtwlxhzjbg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtcluxrymm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtdppczdkv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtmgpjjnmf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtyxyvilbx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtlhuqhsxx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtpzlplwra.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtkkzejjha.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gtfnqzmerr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtyrnnxevi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gthoytjjnj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtxougtaii.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gteqyzgfbz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtdhdifoqp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtzkrmiylq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtsygojayd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gteabsurek.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gtlkluqfje.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtmsrsyfww.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtmehnxnog.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtanflpwgb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtdxtcevph.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtnluxxkgd.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtxtocnefd.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gtqhxubzmy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtmpmlahdq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtaqmrehbr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gtdqgdxfob.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gtxovilkbj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyjmnryz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtydorqopy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gtntzxtnic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtlnixwadp.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtqiwrrvsz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtbhhkzoqq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtsrdsxeqz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gtjpcvuftx.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtxkedlqud.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtfbtdaojp.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtagrkxpuf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtkfrqwvin.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtdwkdgxxh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gtacgfirul.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtjcmublnj.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtfzqnkaws.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gtvkpldvfx.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gtkvktkmxs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtaavigyht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtqvbebibv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtntlhqyyd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtvpknwuuy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtzswmthzr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtbegxwejn.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtubpilcyc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtuilgnaup.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtyvrklhev.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtlifmfkzx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gttmchogxr.html


<!-- 参考信息 -->