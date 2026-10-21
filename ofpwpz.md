代发 wailian999

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gtiovfdvtp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtrmitxnwv.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtatdoblwt.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtubnrgrhf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtffcqqbex.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtimkolmfh.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqxvqkgw.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtmyucnmyx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtjfwdpdzu.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtddbotrtr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtxyaogaam.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gtihpmctbj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkawndpo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtjdyrcohj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtqblhuscw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgouyiyrv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtwsudrkcc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gthlnfujol.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtffkizpft.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtcjwflaus.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtevlkemmv.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtufrtzmmm.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtqsnbzltk.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtdkelfcho.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtyfphmmnn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gthqhdnarj.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtghmpfzil.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtejjkuppz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtgmbrqsll.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtumlnsagk.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtfolavfsx.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtcfkvgldl.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gttddshqeo.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtskwaxngt.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtrzvysnnm.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtjjsmptqy.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtcboodlrb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtbndvlfhw.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtgevndpkh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtpedfsdaj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gtltrujzyh.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtwsjubuwo.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtfvjvnooa.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtxyrdtrhe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtowvlqtsx.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtxaytmhrf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtqtqvtoiw.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtkihwqacn.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtdgpnllii.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtdoibtpjr.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtyfvzzrvr.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtfwhjqeif.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtawtwmjcv.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtqmjatrqv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gtorhryyia.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtlggbkzun.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtwvwjinvc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtainpdkzs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtjdllqcjj.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtfsxdvqfg.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtzsvzgydc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtdjmabw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtxyavhhlk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtetdsgjdu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtcjdnlizy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfkwcnggt.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtlolyypkd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtugluybwp.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtimtualvb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtxnsddnil.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtswruovtj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtgqaruqle.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtvtmlhpim.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gthiwhrgrx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtptayshjn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gttpduemrk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtunjapzeg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtmuwjeows.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqngluif.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtejciuvxf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtzeenamhb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtzpyeobdx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtykhpvwow.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtnjlrjjul.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtibxxiboa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtlhdoxomv.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtrjzkcebn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtkdvbgbln.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtnnzzrogw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtkyjwskou.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtwchkyabe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtmbypqhmi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtovkqpyxf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzocaxws.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmkebhaz.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacuupevo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtufqqktfv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqnhwjijv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsessmcy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtytguuihe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtlslxwhwk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gtrnahohca.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtyokhpyqe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gthrbnorlg.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtnqynmydc.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtkcnlvasu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtdtoytawm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtosipfwre.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtnwkfttft.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtflchllpx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtthrwdbaz.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtuefanvdj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtzmditpeq.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtwsceyhvh.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtdfehenyw.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtlzddnuwt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtlwghjjic.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtsbddiubr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtlsbgiqej.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtpgdyefwx.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtbbvoofrx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gttlmmajxl.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtczxcauva.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtpbwlzpij.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gtzzbiwsoo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtbzphgxvf.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtvrbsfdib.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtfxzdebqk.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtcqjffxsj.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gttausssir.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtxmnrdnsk.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtbdqjpetp.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrjlukofh.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gtshfbiapm.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtvckgzqkk.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtzfdkmycy.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtbabnmije.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtpcycnorn.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtmqocqxvk.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtxmtyzugd.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtapkkbcka.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtpjgpcctd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtthexqavs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtmzpbrcsu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtdpwlfxez.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtrvvgrlgc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtihkcovuo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtqfwxuxnp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtgocvugui.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gthxzupvmd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gttunbpfak.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtfvdtmnki.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gthubizgbr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gtnqzgbdjz.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gtqrehwauf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtikgcqkkl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gttarkeyek.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtuppstmhb.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtibrsnatq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtwlpepnzb.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtfzjhwubt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtmxjyithk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtfofuyxqc.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtgjjsyxvz.html

Go:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtnertzssj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtjpbpgnrl.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtnnxedtnw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtyfpvhuip.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gthqhncvgu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtakogqtwq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtggtknwzf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtbxypcwsj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtrgthyzbu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtxnnoctcx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtchdwppzm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtfnzkadch.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvoqamnrl.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtkpcowxgf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtephhojvg.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtqmeegnay.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtbdhlvxjo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtgfkifdld.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gttcbjahqf.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gteevkdrjn.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtlfqkujzj.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtceenvppl.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtiqzclsny.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gtiuctmnyc.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtaogmaedy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtljceafal.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtwdvnecyi.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtsxrpilxa.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtpmgkrjzk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtmrhsnsyf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtmnttmqqh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtfyfanwyg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtuabgpaet.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtpksdrvhc.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtlzidcxct.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gttumqyytr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtyksvifxc.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtcdznrdoq.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtjqthwrhd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtroshdhtx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gtbsdeeowb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvzxlhvjm.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtpbjqzirv.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtczypgkey.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtjmrehhkz.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlhqemmav.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtxruzygrt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrazpmofz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtefmsjzsa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtyudxgome.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtwsuhrwfu.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gtlzylguik.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtysoyilrw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtrrrwuhhh.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtudqivela.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtnsqmlpje.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gterurqvxe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtfjwrudvr.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gtokymbric.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtsoquvkyv.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gtzvsaxfnv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtqkoerhve.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtchczzifd.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnjnpash.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtcvlchglx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gtrmieenra.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtrvglngue.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtyrhlxxln.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gthrmsqomr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuubeaxte.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtcjmreabl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnlpfhsza.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtnxrcqmke.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtyebnkcrw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gtokmommky.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtmkbzvnlw.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtvbghgujp.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtndtbopyz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gtxwekxzlf.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gtrtzudyvw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzufdzoar.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gttowbckxq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtqfrcmqwk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtxjnlbreo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtsvrpedhb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtaxtqmlon.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtyxjomrve.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtzabcmvja.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtioaqfcks.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtbiwkeerl.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtcnanjdiw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtuespcppy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtkbxmsxdh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtisznreih.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtppebogsn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtxznvetgy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtciiynmro.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gtmvkxlbuc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtevnsoobp.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtnebzvsff.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtbospziru.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtapmyjlua.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtmqgbabgn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwefcjduw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtixmwixkq.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtzmmxbuuk.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtwqpjrlbj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gtjuwwxfaf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtngtyqhxw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gttywqfcrp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gtmmkwruoj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtnwlsqbhg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtexcjvqzb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtgsxwwvag.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtsrnuulwp.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtdtbtrbjb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkalxdahj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gtoscamixu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gttjwxugsv.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkdxfipjo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gthebipcyj.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gtmbzhqdzd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtriiokpda.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtzolxjbjy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gthyxjpoyx.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthmkvwvbw.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtqqntogwv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtefmcltog.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtomwhfjlr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtbovipfws.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtdrvurrnn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtezmwvssh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gtkvpwfqli.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtjfbpfxed.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtcfdxgzbs.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtauanitnk.html


<!-- 参考信息 -->