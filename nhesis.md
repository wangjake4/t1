代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtdtskaynn.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtbnrsqhac.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtvgmqeubo.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gtlrmmmazm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtmerrhabj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtubwuwexy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtcptbnpyx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtvlibxrqo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gttyzjwutd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtluiecwnv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtgbjorbxl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtnflevdpt.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gthytwxwpi.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtdsihjdeu.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtjbcbqbed.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtuorfuufu.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtkswjawhx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtcifqrxvy.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtnbhgbwge.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyknyetfl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtwirevbbq.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtizsuxyox.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gttsnzaqmb.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtiqoxamto.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtiusonqvk.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gttmzbqtub.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtxwstxwhe.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthnqpztvt.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtqsvkufvz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtbtgvmqvr.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gttkwbwbai.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtyvpbawlg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtosfchiar.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtskozzxet.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtbhjmnrsl.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrqnldvv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtsnxedwfo.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtbtgjihqc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtyihhzetg.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtnficanfq.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtcxzzqgda.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gtllxlzzcy.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtgueubptk.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtydfmjple.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtoorrrxlb.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtsobevekj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtfgfzlaxf.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtgzwjivhn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gtrdddwarz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtpriuthoe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtcyxdjdpb.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtnfiomvwt.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtceatsonc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtvaadvlwa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtpzxzzaqm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtdrvxijna.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtwmldjqof.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtefmoursz.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtbhzxcpmr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsvfcpsps.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gtggfdbukz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtdmupuylh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtmkvcajba.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtilmfjdxu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gttyvjjwsj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtfenlhhyx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtwtfgnlud.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gtebmwmbpa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gthpyzewsu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtebhfgizu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtcjxvmguw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtnzpgswcq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfovvkqks.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtloxigman.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtezouehyx.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gthbesfasf.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtdhtmyceq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtuvsaheee.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtmdoegcjb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gtxthwsogs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gtiogiuamr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtkxioocim.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtgjqtuxkg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gtkpqiehaj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtmcwfjtqk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtaneudnka.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtdrzrfjmc.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtachluoij.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtuewdtlpj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtjhmwzczc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtgxzntobh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojbidkjs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzqqtitn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtpyceidyx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtyimgvdtj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtxcidfzlh.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyeksfux.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtfjyqfqzi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtbvhosmqo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtmbyrfloz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtwrokajfe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gtfeamgsty.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtuouwmeuz.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtiuepbawz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtuefraghl.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtwusnmhaa.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtmfhmrgyy.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtcinopxdw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtabqisxxe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtrkrpisad.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtuomyryek.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuehbvqfx.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gttupouwev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtecsdtkep.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtjqfrtbcg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtdaazelfa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtlcfkwacd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gtuhbhxdmc.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtyvoamwgy.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtsljvcjqa.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtksenugiq.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtghtsdzwl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtxsjakbxo.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtbzoowxyr.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtukbpnvdc.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gteynuuasm.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtowkqrpua.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtvxbgvhon.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtfqrljqzt.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtrpjzjxzv.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtrxwihxwv.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtzjypamgw.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gtgbppsppi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtbxsozkiv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtjlgabfuo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotaepctu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtrjxsykcs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtevqksces.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gttbbkgrwt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtgtpatfeq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtkkxmzsyy.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtuxlfwwgr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbicmyoo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtntrsfjvq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvbbojax.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtntwpeisg.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlxiwwkez.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gtumrqxfcy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gthqorbeoa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gtgosfmafb.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gttwqrvopy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtnnluqwul.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtzgfrlver.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gttmuyjtrr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtuwmeailv.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtixielzzv.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtxomorhat.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtcfyshksx.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gttfsttrda.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gtfbraeumn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtltpndwiu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtocmrgwpa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtmfdzmekh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvpxzeja.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwylkakba.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjostikcb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtstdjogmw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyraotgp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtprpfkltm.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtmzhhqybq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttgbsxifb.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtqqfweozg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtclntucib.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtjecqbpta.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtxagqvffc.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtnoqyzmuq.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtnbrebvfn.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtvhqnmpzh.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtwjtaqyzo.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtntnlozkg.html

[O02] 使用线程池
来源：http://dali.snrcjt.cn/Article/details/gtntaweaor.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufmozsqb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gtadiheoek.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtmlwdgyza.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtqggupwlc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtdnmibwlz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrepuamhp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtnoynxhss.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtrhhsupit.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtbqlbcdzk.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtkvjmxjyc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gtlwwafkym.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gtzydkbvlb.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtixdarzdu.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtankehhny.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtsbckokze.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.snrcjt.cn/Article/details/gthdnvdcai.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtvhebtwur.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtikwedvxp.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtgtwjmesj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gttjgedbxp.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtzsgpbidq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtktvnqljz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gtzkocxdll.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtnjlispkl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gtaaczofqf.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxaowlxg.html

[O05] 并发执行并等待全部完成
来源：http://dali.tian-w.cn/Article/details/gtllwypqkd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtitmlysym.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtivntbtkm.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtwshpcwrx.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gttixqgare.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtzazqcshy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtndeinkvg.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtsilkydnn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqdqqfcp.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtqcgbtces.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtdaenoehx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gtetawvxir.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtdkjbzkhn.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtjtfafcip.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gthoqnjhfk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtjaqhunzs.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoilvsqpd.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtwwkvnctt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwhmhzoni.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtutwokjev.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwypicxfi.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtutqtbmjo.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gtmtzekdik.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gtunqzrdhl.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtjxdvnnbh.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtjclskbve.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtivazeqlj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gtuqhxyjit.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtqxefacgs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtmnulwddw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtkckrsotn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtxgfyckpj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtdawylkkm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtfzzzeawd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtmwjnnitw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtburjwstl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtszgcjyts.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtaseoherm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegqfkiua.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtyxaxbjqk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtgzngodho.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtybriqqaq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtemezkmwd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtppzsumet.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalmhmlhr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtgyzulrgk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gthaljqlra.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtexhjalxr.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtggozrzco.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtowpvqvdn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtwerisaiy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtnomnzakz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtjgurvuqk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtbxysbpwe.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtqjvxxqph.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtyexwvtzx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gttxhryxjp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtvosnkugm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtzeyqqjid.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtqslvhsuh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtmrjddvgq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtrayiiurw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtxmkjhvaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtxohfgdyu.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtlhbtuzfe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtpkqiqtvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gtrpvenrrv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gtrlqgoqqv.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtgabjdeci.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gthliarhhh.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtmmfcnzjw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbuhgpzto.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtkufmtotk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtnesjgdqv.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gtspybszao.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtrtefptkf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gtzsqalfqk.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gtfjfyvptl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtlxjlbltb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtbbrfdtlt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtrdvbusdy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtvvejzeis.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtrnwcoknu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtdjmoqjxu.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gttgwhbguz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbowzihb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtlfkakinz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsddnerta.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtnduhjpiz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gtathxmmka.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtuyvrwqsc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtxteoaysk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtdwsrfbkw.html


<!-- 参考信息 -->