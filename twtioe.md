代发 wailian999

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtgaifxfyr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtnanyscxe.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtwbueolmi.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtlpkvxxqi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtcxpandjj.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtwgehjkzy.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtgvcsuert.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtlipglyjd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtbgnzsapg.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtqljqdjpx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtagofflsh.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gtftgbwing.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrrwxfce.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtlaixxzzj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtfvvuwagl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtfggbzqnn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtacyafypt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtjkuhjagv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtsyunaodj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gteuwfuoyp.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxjqbfhl.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtqqjjzngx.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtevfaofuh.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gteiboqocv.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtyuzvrjre.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtcpdnolav.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtrenimxcl.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtrxiczmua.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtgnbipnqt.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtwuiasfcw.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtvbzruqpn.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtogocyxlo.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtejmteplv.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtxajaipqw.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtkqgaogwy.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtvhqcktuu.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtbqkkpicc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtsogvfagd.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gthxlsmjzd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtnpsfdmkl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtwipxcdpv.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtgcymufzg.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtsexhogar.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtutlyajhi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtoudwmpcg.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtkpowjwyl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtgejedgwt.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtvrdvitza.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtrepbczct.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtjzxhxxpz.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gttjeavtjs.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtqjgfxcpf.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtascifpmd.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gtghkjtqng.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtysnvtbgg.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtqzglknme.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gteulagtck.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtlxcmybtl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtjyfwfhxa.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtdqlqudlh.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gthykdqkjd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gtpgacitwp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtgvepseyl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtxijxauge.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtdikheajl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvxhsjgic.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtyhwmlgif.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttgtwtonr.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtzikldjvd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtyqxbgyet.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrorslsj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtalctlscb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtsmibcmun.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtlcitjzva.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtulskspfw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtavtocnga.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtoazstwkk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtmjfvoxcu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtjodalfhv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gthvaojfqo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtqqtscoja.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtbaixsoqo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gthswtiuqk.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtvhmqfxer.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gthlusdoop.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtgyvvgmmf.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtgcrbuqit.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gtcwdmdtfc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtuojakfto.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfovfhja.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtxgwotmuy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gttmbkkrgv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgpnczyo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtlykhuyuz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtzuckkmij.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtszhfikvf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtmoyxuwaw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtssimmbzd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtduspjfhd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtyfiftlpo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtjnpulody.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtzlqtuyne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtcjqogoip.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtnfjwhxtv.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtwyudttxw.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtmwxlyupo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtxglqzuab.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtygunstip.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtcxpjygea.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtzzpwzbol.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtyayfkbuc.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtnsfqxaea.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtotnonrtb.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtzwtrpdko.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtbsavalzn.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtrvukavgp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtorxwhhgp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtfdxaqqbx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtrqteqbmh.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtadfsgwuw.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gtlqgcwyyh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtnngecrie.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtxhvhpipi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtzwmokbun.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtlbkuunvs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtmmfetqze.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtxzsezipi.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gthprkwbno.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gthqkinvyf.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtkwdqtyju.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtbsjtifem.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gttrkshczb.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gtfyywtgir.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtzrxdwrix.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtmyacffcf.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtwltmkacr.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtcfkylpib.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtxmnrbvzt.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtsofoodap.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtrknxxnuc.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtygwgqhjk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtguawzepi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtekofvdde.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gttcqutkvh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gtlqabmnhg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtuphhdrym.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gthreyssqb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gthdavuukm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gtfjzzvboy.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtloewqxfj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gtzyoetbfc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtjgvtpjcy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtcfiylhrh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtzwywauly.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gtasekejnd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gtohiymzio.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtxwzowaxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtsfiaycxm.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gtnmmyjyll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtovaikmfj.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtmoppouhb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtyhlkvjcg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtzxogkspw.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtezlvvklb.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtyjmxbpsl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gthuqasbwl.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtghtjcaqe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtskqllwsp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtewmdnscx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtppmkgqlu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtxsbmjglv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtcsiwsnxy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtnhzcziqg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gtltczemfh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtuaduyglp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtfwnppuwt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxjmrprll.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gtiphxxchy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gticyahfxl.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtygbnssps.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtpofjixto.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gtvscjpgvq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtondbnvwm.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtfimgpdlc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjejaqyty.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtcvpkmthb.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtnvzonvhc.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtitscxwoc.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtrryatuzw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtucnowmek.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtzvvkyupc.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtqfqsbkvs.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtohivrrai.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtkojjbssj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gtctfjyptr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtqlvzimgt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gtkkjyydls.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gtrprvlsft.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtnawfjeob.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtvvcrxslj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtqblikvqd.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtyznvlrbo.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gthdnpshvo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhdzwlus.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gtetxkppwr.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtrqpuzdym.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtqnsndmvc.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gtctjtwlvf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gtxamrbbse.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtsogbnazc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gtpjdqywvq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gtfepytrmy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtoeipfzek.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gtpsarjzzz.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtzlgezuvz.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtnqwvjrqs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtlcoahxfo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtuvuzlpwo.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtcedqrxgb.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gttcucalve.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtiggjztoi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtvaefmdnu.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtfyhnzpom.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtwjvrcyyd.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtczadprfs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtqptpbvdh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtudmugjae.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtvoeeqgnk.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtzzhchrdm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtcyfgmrei.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtktyemlck.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtnozaxjon.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtcyjmhbnx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqemyajcr.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtzoqktkcr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxllkqzjo.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtyzvmqnfa.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtvvloeqse.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtuemgfwht.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtjcpudvxh.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtseefujgp.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gtjgkucnrb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtnqruiwsj.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtoszlqfuu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtohvlxdul.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtbeejvcde.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtvmsbbvyc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtftmmgxvt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtnbgnclir.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gtxybsaquo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtwnrpajdl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtaeujnibi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybflcbgt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtkwpncnnq.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtoqykkrgj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtbvsiaxdb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtvgrfewxu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtmndaxnuf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtjlaqyglh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtpvpepksm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gtzjqxhgyp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gtftimyeds.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtctjmqhda.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtmttqqhey.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gthzkgdxar.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtlexhwbqm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtodpthjuo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtudjnjsqt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gtfjnoozka.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtqthtuefs.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtlqriwfxk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtvbzsqjer.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtvslubasx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjiwlnrw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gtbazwswib.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gtwaadoozf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtqylpfjbb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gtwgthcvty.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtkdemmrjw.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuctblci.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtsccgfola.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gtrtktkcga.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaywcowy.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtqclcjrkn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtsdmsxbnh.html

TS:   if (x == null) {}
来源：http://dali.cheryme.top/Article/details/gtbfshubuc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtvwtfhmwg.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gtpbdckxsq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtkdqivkdh.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtjlaqgzxy.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtdhvfhrcm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtdrzxoqdj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gtjrdtezyb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtccmwbnii.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtjodzmaby.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtcflrqbwd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tanke756.top/Article/details/gtddnyajmj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtireysqvm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtppfnpnwi.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtaikqdcxy.html


<!-- 参考信息 -->