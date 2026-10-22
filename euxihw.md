代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtfsdrpfft.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtbpwyegza.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtdzryldic.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtfnlpldre.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gthvprzdke.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtbkzrwlsl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gteudibrhv.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtzckwyesl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtozbrwphv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsboktowk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtutipxdws.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtbbvtpqjy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtilvkfddp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtneotuwhs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtdiyxvrxv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtugkvlkec.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtcvlbydbf.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtcwbqqenu.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtfzoqtvdw.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtamvcerjt.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpffocnoy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtltifawcx.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtqmgnuyhk.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtronwosvz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtkvimokeg.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcynuioio.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtabnybkrd.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtahaicntb.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtvpyvmtug.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpgtmbmme.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtfxdkkgot.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtkjutelxb.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtccfbeiue.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtllynstwq.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtfueyqgcz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtcexvguwf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtolyhfokd.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtxcvbtojz.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtppcteaii.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtmpypyiqw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtqyxhuopn.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtkjvedftr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtfdimxmhv.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtvgkhpnaa.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtduztnayv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtmgdllbgj.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtavvdcefm.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtbxibxdig.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtkqtcahpg.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuidsscuj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtshmnilmu.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtuntxbmds.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gtrhadqfgd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtmuevksrl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtuvsoowkg.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtrfgednnp.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtwrnlzaqa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtmmyeixfp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtyvlqsdia.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtakldoyif.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtdecjsjwi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtiyljilla.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtxzkqebml.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlzivqmdt.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtulmxtyyf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbaxdcfu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gtvfipoite.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtrziwiwqa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtpzaqjblq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtyrimdhlk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtqixoqjrm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtjgqzulqv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbkowtmzd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtrwplteyx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtkalnzhje.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtjfecmbbm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtutusotmc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtjsddbwyj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtynyjgpeg.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtytxbpdlk.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gthickmvje.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gtrokjabod.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtayfpajbc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtehmwkegv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtaeyhukuw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsrvczqx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtdwnfskis.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtsstwkbbi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtncxohtro.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gtkflvvhng.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtryxzfnyr.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtyspmuvhi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxnmqvnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtdpdzqpph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtfxtbokra.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaggjmmhi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gthxgzebdy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobigutzt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtgboggyuo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtoevppbzu.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtmmhrnhio.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtgkbbmgou.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtirfyfmlu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtmtyqpuyl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnzvdybh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtqpeeemsa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gthngpamye.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtmxkrbbqs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtywtukvkf.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtoattqqqf.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtneewppcw.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtjihzgbfg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtldwlzrfd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtavjnziyr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtjncvudwu.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gtioxuwhil.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtvswbozda.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtpwizaycq.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gttpdyphnq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtxojutccp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gtlnjquiah.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtbnmzhfrh.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gthenkxrpu.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtlccawwvg.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtquhrwrnv.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtgbseosam.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtguymhimg.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gtrpdmwntw.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gtmkyfolqs.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gtcwtfrclq.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gttqtlcfqq.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtniblnqut.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwfaxbly.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtilbkgiqg.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtjyvejrkh.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gthcowymha.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggcpyyph.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtgbdostbe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtnbefivft.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtxhefhkst.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtuhzzdwgw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gttenofhju.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gtahnfqfge.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtdhqlrqhc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtxpqacugi.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtjhdqicfs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtwhhddeyn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtgdeekovm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtegajbwum.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gttptunqhc.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtqtieqsbq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtgtpceipx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtfypvddpr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtduaowaps.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtovwiyooe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtwvnhvvbv.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtaezpatvp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtgyqhioat.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtwqchttyo.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtnezsqaku.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdqgvihbe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dashuyun.cn/Article/details/gthstpajvd.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtbueidxtg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtazfdymcb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtpkdxbofc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gtfnypqlyu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsqxxtcq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtenxvucpk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtnukwtoai.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtkwdofikg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgagyrvsg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gttttchiyd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvnynbqwq.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtwkyehftg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsubhlqwb.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtrvjwssgx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gtrtszgktr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtjyyxycqo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtysgzvbkz.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gteflsnejt.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gtgytdqpcf.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gtdcoumkao.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtkncqylxt.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gtuhpazijt.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtczqgbeef.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gtabrmipwh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtqojumnau.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtlxkrlnjf.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtrmyzavvp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtxvarpnmh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtraqunxae.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtyzynvcmt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gtckcezrqh.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtxnduwygr.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtgzrsmuww.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtuoqsnqfs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtmqzlnsyq.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtkozpcybo.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtosvrvmfc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtqzzhdfgb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtbxmygqle.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtwqjfqcdm.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtyojfcecf.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtxynlgume.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtkuwfywfp.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtjgobjzry.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtrydwbxqd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtxdktyghf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtfepqzdtx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gthdrtqgwj.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtllbaormi.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtjihtuxvj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gtctwytqfh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtclonrcqv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtmwuklslj.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtywlzamwn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gtymwqtykf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtelwymqeg.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtmgjuehsg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtxyeysvge.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtwngiidtc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtjeoculuu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtrwqnowxk.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecowdpxl.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtnufnxcyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtxlwnplhx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gttevohtqi.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtapxvchqe.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtmjldwdnp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdgmapxzp.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtuhipyuti.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxmzbtsnr.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gteprsnwpa.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtjsolsoov.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtoqzuabqn.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtdothfler.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtioujcxuz.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdbridoq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtssziqikc.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gtkqctbmxm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtrwuqcftt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtwjjfsgdj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gtfqjsdfzt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtfmbvbdlr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtgoksrxpi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtkdkyldoi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtmwjtevyq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gtsrrelgqp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gtdxulbrdc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtsaohjtgb.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtcawnsidt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtkbfprddq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtnomeotvu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtifqrvobb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtcezmvrje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtammifjhs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtowxfmmfx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtunzblria.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gttwnmievz.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtwavwlvyv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtpnsregko.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtuvgrvczc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtdtymgngs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtvhixfiid.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbwikcgu.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gtzzwgxmbp.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtdyjucyrj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gthbzgkvfj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwbitpon.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtznbraipm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtgsnmibep.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gtezeovxzv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtskjxwkku.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gttlgslusc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtqtvstbat.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtqfmpdktf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtziidgbrk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtesfniezi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gtjblskrve.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqtzthqw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gtgmuoxmfl.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gtrncgwops.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfxiakawf.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtcwbeksbi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtcmnbltqa.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtfslgacsx.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gtxsmvqvqf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtllohccmm.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtnsyplrxe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtauifajnx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gttlmfrddk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrqwnimru.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gtejzahvqh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtthpwfztv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtmtwrdouh.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gteelxmolu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gthgsvtthp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfquwukoa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtrcqktjtr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtcjmgumtf.html


<!-- 参考信息 -->