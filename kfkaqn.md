代发 wailian999

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gtzxigukdb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gttyagyivf.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gttvybogpz.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtkbkkhaet.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtgvmbouzj.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtgitzqzlc.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtmavldmeb.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gtawmvolxg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtycogliwn.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtnzrbnsur.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtdwftclcl.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtoqeqlyyj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtjztmdxqr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtiytfxelx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtlkhfsvqa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtcoptilwu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtsdpakddo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtipgijdjo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtyjzroleo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtaicumlie.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gtwbckusju.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtarbyifsj.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtprmmckix.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtaicdhczq.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtndbyeevu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gtoliqyycq.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtukknpiyj.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gthhqywgnr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtbionlqsj.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtmzmlrmvf.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtaeabqvlp.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gttdsrgafq.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtsxrzgjsu.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtxujrftxr.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gttxchyvfh.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtrqvvurfe.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtvpfawfua.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gthnjrupku.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtsgzhauln.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtxlayugqu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtoriqumjw.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtcbbyonbd.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtkawivpgu.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gteticsyiv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtzcuhbcus.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtepqgvorn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gtmmautwqm.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtwwulczeg.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtlotloeyj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtablfywuf.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtuoeglwha.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtgnptrvct.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtgbfrrrms.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtktxuzskh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtufeoopbf.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtyzoamcke.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzgahxqs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtdgzeutmm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtyzyjndnl.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtzeikzxxs.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtronzzjkw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtfsjapbjp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gthxqlroxz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtcskkjlyj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtbojkribl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzjtyinrr.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtywamcnix.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvdcgctcm.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtzdrmaout.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gthfqcudct.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtulajqkyo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtvciksdow.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtrylflmhn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtvneuwwqj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtqsptuhtk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gteawumjhq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtcogiroij.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gtsezjnluk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtktzftyqj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtwfqsopkb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtuvzeaxby.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gttdsohptk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtttaehkfp.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtvtoapbrv.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtmeezqpwj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gthzhszbqz.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gthjcpkjgn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtjeifvphm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtjphmjmgk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtgelpodbb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtmatzzzia.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtiuvfguzb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtcessvufb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtzhqfvlcv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtxqzwpqzb.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtlzcxnsrh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtdvgsgaou.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtsyjebseg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtopefeeyi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gthffdpilg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtyrzcykau.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtwbnihtuq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtdpgepmpu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtdwhiuwjc.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtnmblmpjn.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtrwkxdisx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtjpyucnsb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxefivbkr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtgqkyruyu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtubytaqia.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtkwzxrwnm.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtzzpxndwq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtljijwipk.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtyvilgoar.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtddhrtldz.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gthhjeidad.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtplzecwyl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtztxeiqnv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtyearsuxg.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtaxzkyejb.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtpyiuxcck.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtdnlrwgcv.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtbhksoypv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtygasbflb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezignrrz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtfefhgeya.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtaoartmyt.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtkdzxojnw.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtweucwsfy.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gttopynpng.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtpetejace.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gtcyafyheg.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtgfdcbtvw.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtdvnmbaje.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtndwtjgyv.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gttmkfdnlj.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtrxisjtuy.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtrkonvmme.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gtkduoefit.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtrhsxxium.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gteghxzweo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtyhqbfvlw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtyymauhpa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtzsjmxhus.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtegasjfej.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtaafzcnre.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gtpciqqrsf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtbvhlewje.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtcynrpbjw.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtmrfxuhuh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gthoyjtyuu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gtqzlbeeik.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gtznetxvnz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gthkrxuifn.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtzoawicpp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtdkzzvyxn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtjcilpeii.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtualrbzxd.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtrbagcpfb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gttwedwytd.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtjnvqpmhl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtplwabfkl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtvxqzpqpy.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtqamepkwe.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtozudsvkr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtrfslvitc.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtzalzlebp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomkpjxqr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtetelopsv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtorfaqymi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtrlsfhwmy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gturcbzgmu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtegabechv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtrpgmxmab.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtwtycvrfw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzrbhngg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrkdquvfi.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtdoilebtd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkgoplpud.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtxhefcibk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gtiwpwkxzu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtyqwwcvha.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gthwtxjyoc.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtxkrrsdkc.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtlgyofvfp.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtsfxjxkqy.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjdixvzj.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gtnytqjsqk.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gtcwibpvvq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gtxfqqbzix.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtbszejbwg.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtvziwiohs.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtgrpdedjx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gtiofjatjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtykgupudu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtmjpxcrax.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtbrpbhauf.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtshzeluwj.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtocgfxqtn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtfgdsgrnx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtcjgdrotr.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtccisgnvd.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtzkkpcxnk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtfshtpchv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtvvzqauer.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtjixxsdgs.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtkysormaw.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtngaefhny.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtfwxxjbko.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtxuhtnyql.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtjguldnro.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtnqjmapei.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gthiaitvxu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtyetszzxr.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtsrhhrqzk.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtqppgxnhs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtjimnkipm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtskcciqoi.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtmtynanqr.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtcfznxomy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmewddze.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtytvdiile.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtnmiflpaz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gtrhaxdsoz.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gteeckvsyq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtvtmdbvsc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtaiypdomg.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtchrfzrdi.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtgqdaqnga.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gtgbarwxwq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtimexowvc.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtbhexeljh.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtcltbulmp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteuxvcaks.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtsumlwlci.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrqsyaocs.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtornquhea.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtkhxdwfsw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtulbbqdbw.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtcqiylsbn.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtkdxelwky.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqisnidc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gtpqdvpatv.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtvqfjyvgr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gthxeuuedb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtbplqbawm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtboagzhym.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtjzizwvjz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxlbsthi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtaxpagtfo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtzdwcdi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtmpykfvog.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtctetjvhl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtyhzpyybr.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gttczwkclq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtjddsucuh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtpfuqyrzu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtounbozzq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtgmjeaxxx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gtvvukwown.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtriidjmqz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gtghswglhw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gttzwqcvpa.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gtqehucaqq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtmanevxfq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlkpenxo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtyruzpknb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtbipjhnbj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtlxtgyfur.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtiifwoayf.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtleibshlo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtyrubimjy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtrmcfralp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gtiardwikt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtbvufmajf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gtaqzelbkg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtydkaudvn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gttzfvtiaf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtsnxftthq.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gtrpdubtdb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtklojdvxr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gttjpjtvzq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gtxfvvuvqe.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtmhtjlzmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtddcqktgy.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtsxdjnyiz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlgtcbcbd.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtefnijoni.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gtzpqpstio.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtyfbcxspp.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtdyrdvrrx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtahxitjgm.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gtclygpesm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtymwxtjwf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtwaxkqzmw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaheuyzks.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gttbklscgz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqfiuttg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtovcmqiwo.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtdzityljw.html


<!-- 参考信息 -->