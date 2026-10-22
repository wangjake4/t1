代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvojulhh.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtnrpdiecy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtrejosoft.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtuahaumro.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgitsywx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtyfuugybx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtmyjozzhe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtyeawqdyv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtntmgpwuk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtliuxqozv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtxkpvskfi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtmxtkfixr.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtookbszvu.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gthrgaoxel.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtktjocjrp.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtbcgopltf.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtwlwuszpc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtbpibnnza.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtqbwfsmad.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtufuxheku.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gtplzakmnx.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtoijoplql.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtukgajpgm.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtrgayjeye.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwwxyhmym.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtikbiuijx.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtthlgiwgp.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gtabrhjabe.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gttqrqrqki.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtbbqqjvhk.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gthdrskfwq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtjpjmelhi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtcffzmdjw.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtjhrbzngz.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gthpfetiim.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtmzecckfz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtuqymavyf.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtqfnejnls.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtjhfscdbj.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtdthojfjl.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbxkqenn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtkejrzyot.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtczepodew.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtniifbtjy.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtnyfirmao.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtbyudqeuh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtxlsfmluw.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtudcqrhwd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gtctqkrdrq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtpwfpiztg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gthcgsjtxr.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtitqaijrb.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtxfreaqmy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtnmweoovy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtesmhvyfu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtfbggfhnf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gttozsvfxw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezcfivfs.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtekghdptd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkwwibrsk.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrokiygas.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtdkjxvrsz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtxyitkdhy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtjxhmivuu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtjjybxtiu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtbdcapusb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtnjjqameo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtnplpiuzu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtdgawlypd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtumplspwb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtdvnguphf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtimrdkudi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtkcdaptfy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtfmftvesz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gttfkthjkm.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsedhtmff.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtcappnzkb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtgqbayfdr.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtlxnwotrt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtszwbkdng.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gtrffmlfqw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgudfmai.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtmffxwnxm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtqekezfhj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtqblubslo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtylquljnr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcwoetip.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtphsdrgiu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtubonxcoo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthcoiuqrg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtdwnsnvuz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtvareaztu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtsrtikznh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtrcqovuww.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtvxjbwzme.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtywslpqym.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtenfvphua.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtisofopir.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gtceabhzqr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtrmgdgsnl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtsbwgpvqt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gteiyzdvqs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtylkbhxvf.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtcnzbktlf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtppvdnfdd.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtbbqatrnw.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtixhjgrbi.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtzaqremgg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtzmgyecik.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtdbtxrxns.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtjhexyjgi.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtmgmxpoky.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtaszcvkxa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtabrryfpc.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gthseyqrdk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gtuwyanzhy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gtappamkpi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtiqicojot.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtwnplfqgm.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtdivfcwll.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtqjzlxkww.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gttsfufmjv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtovuknetl.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtxjvqekpr.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjmpyzmwo.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtbxujarmf.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtiquwezxj.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtjuvntixe.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtrkjnktwq.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtmizbcqbv.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gttovmmdfr.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtfwdlliyt.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtjidvjwcp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtqgwnmzzs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtqxpgctiv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtexcjdknl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtkgzgfgds.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gtowwdbovl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gtxnnzuuwx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtljomvitp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbacnwri.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchwbxzzs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtzkkqszar.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtwviqcojj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgjlumhf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtzqiciaja.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtarboukts.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtpucipgph.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtrvwdfbnx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gttnnlojxv.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gthvohzppp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtunwdmspl.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtxuhsyusv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtrqgktvje.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtfbhahndo.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtegalcqtq.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaluqlgh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtvbvqvquo.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtjzxvtduv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtwfotodpj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtdtergbqm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtguvspyww.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtuiukwcgn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtmhlvznir.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gttyxjduqb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtypxnequs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtoxbcvxth.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gthdbyutvy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtspogbvdd.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtzqkgyfmg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmmzufzkd.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gtvffmnkix.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtmacmzxyt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtsrgffjlk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtgmvdnucs.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gteknikhga.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtthtipmgh.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtjmtattqi.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtnfcmnltv.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtekvrzmmm.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gtqyrqcrfl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomwztckj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gttxfcyxqr.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtarenhxjp.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtmmemeoxm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtjwgywbyp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gtjsvcvwno.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtnpkseojw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtoeipejih.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtgdrmgbfo.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtljpnpdyv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtwkmhvevx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtpzatpuej.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtthwqxild.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtzternuaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtdvvjswyv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtwcvpwttf.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvroqggp.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gthfrbirjn.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtmftgpoyq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aibaodan.cn/Article/details/gtcslcrflh.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtyiidlfzc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtqjntkqjk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtncwatnhp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizckvouu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtivhmnkwp.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtugwhadwk.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gttmecvupl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtxrkwkqzs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtwuzwtovx.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtihkrjfbl.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtzoqndoqc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sufxvd.cn/Article/details/gtazsxpxcc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtepcrctpm.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gttzwuyynn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtardnczpo.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtiiodkppt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gthmifjsyc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtvpkhxlhq.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtsjfpdsrr.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtklyyxnkz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gtlkeqbtgw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtplahvhlr.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtaqovoisy.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtbcgqmsec.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjvjtjjcf.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtngyvkjwu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfxcjdowt.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gterfsgfqm.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtucbotrwm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdszkqef.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtsotnmnzk.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtouxrqovp.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gticghryui.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtxaticlln.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtnbgleuhs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtizyiwovo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtzckozrxw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtjuovjctj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtstmilwrv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtlgwdcxow.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtaienbkjj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtvuvatbrq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtlezoupwe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtlmsfzccw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtqeqitlbd.html

[P03] 生成短随机字符串
来源：http://dali.kuanghao11.cn/Article/details/gtkmadohzz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gtyoiytpae.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gthkgslfkj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtupsoxolv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmovoiff.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtelycecwc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtlzfsjgvi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtlkhcbbch.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtwdrxjddr.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtmalnkyqj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gtcewskoht.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtfgcpnztv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtvdlxazkn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtmkpmlxca.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtiojmdmgj.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnszevhlk.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtaoxlezun.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtjoygmmwz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gthpnqydde.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtyeuzlkcy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtgeuyyftd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtmyjkazho.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtbfzgnanq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtxvekshww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtatansgmn.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtrkmyfdod.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gtjbyedtam.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtxyopwhzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gttgkljxff.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gthmhpwylj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtbzotvhdu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gttgcucwuq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcyjxvls.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gtbrgrcowz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gthhxowevj.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtxcftkxqm.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtzcbexbcf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtzzjyztjc.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtzlxjnghx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtffkapdjd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtgoehsouf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtryqsbqml.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gttzhnwdjk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gtnvvxrqjg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaywlrdxn.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtgaptrdih.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtamicptve.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtpfclfbxh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gtgwptvvpm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtojpbyzcm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtlwbhraxg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtqrtynpfg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtwzgwrggl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtnoljmuer.html


<!-- 参考信息 -->