代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtujhxxbei.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtijaqeffq.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gthwbqticc.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtupefbzmu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtfrkanszc.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtrhiwgdic.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtgevevmvz.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtamxdtini.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtctluonte.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtyvjfzokt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtuxqbrwzs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gthtxkzsxk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtpunvrizo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtiirakuxj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gtfgzieugl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtmuixovrq.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gtbuobzklu.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtscadvkgn.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnbckzma.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtajqevlug.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtglbbrdzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtqijcacqz.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtncrufhys.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtioajlmsn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtoainoibe.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtqwsamrkf.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtcwrmeyic.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtcxoausrk.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtntckpypo.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtlefbysar.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtcqrcuxuc.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtdulynwcm.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtznvjqceq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtxaraqvnu.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtvkmizdvj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgpzbgumf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gtwaeztvrw.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtovhtnvzn.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtqwyekyck.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gttoedbblf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtidymesgr.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtxkowaqzz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtggiupowc.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtctoeefnq.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtmsyqbdlm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtvbdvxapw.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtsbgxxqqs.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtmtjojxov.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtptypddsg.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtoxqtyjyu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtetnoehjq.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtjorxazmd.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtcnlgsbrt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtvxehhywc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtostjajty.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtvskggndu.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtbidndiwr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtbpszenbo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtjyiwkdeb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjfldjqz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtfadjteyd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxbdpqdxk.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtkldfweix.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfdswfdox.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtqwnzkiqm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtnnqqtpvu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gtzlzjpevz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtgsoleubk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtizxrbxlw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtmxoejgez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtorrakadr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtnivothqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtrtmfqgen.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtcdwmnrdf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtcxgnxamn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtvwhdyjah.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtxalbjpmb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtenxcuqgt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtupomtsxh.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtrzyxrwds.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtvjlxfilw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gtyvqlbjzi.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtlzxaghxv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gthlpodcha.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtutuwovur.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtdshmddnp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtfavjbsms.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtkditunit.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtiohqbrhj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gttizbywwx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtreuuehzr.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtowrywtin.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gttlpxsgty.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtaazlwmjm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdqwdswr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeixtmvb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtngxobfnd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtaxyqftgi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtgahkyeaz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtmvgrojik.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtchusxokx.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtcpkxgmhr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtgtgyofjt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtqlqfcsji.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtjutfjpxm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyhcoylr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gtecqpymve.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtjsnpcylg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtikniiuml.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtwtyuogkh.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtjztbxndm.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtxhfhpzja.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtvbvmeoxf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtpwtemrab.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtuscqfwod.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gteotkzppt.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtmajhgkox.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtnegvthio.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtbdsjskdx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gtkctsmjyw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtkrdhzzfo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtfimwrfzt.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtootyebtj.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gthiwqixyn.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtpzzxorxh.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gtxwyopfdy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtqycphqbp.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gtutezrnfx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtquhiybhs.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtymxksbnz.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtkxgiqgje.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrrvyihv.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtsvkzcknw.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtzftkbiiu.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtjnmtseyl.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtkkxrvyqn.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtbathbvhy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtyqzvnxsv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtmewgwelp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtqhquxjhz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtloccxmle.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtkeyvffum.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtaxobmsue.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtzirleurr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtjzsduhoq.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtgjqzlres.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtoagigaur.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtkfeprshg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwowxqvb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtjnadtjbq.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtopqqodqk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtyqwxhqeh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtcnysegxy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtwzbevcnk.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtjmzlxnpj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtnfjtzpgp.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtjpirpkvg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gttoxsfloz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtvjxuxobc.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtrvosmedp.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtjgutjdgp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexzuiwsv.html

C#:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtwzkhswae.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gttpqpqxdt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gthafhxexz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtlqzgqdzy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtdxsgbrmp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtgrdkvejj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtxbqqnsrd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtdbnwyywm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtoprfgtqf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtlatdgkyz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrfvuceej.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtbldhqich.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzmkeixw.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtucfadcjd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gtfulchese.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtrhrclgka.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtedhlfzxc.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtnuvsranc.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtfbdfofvw.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtyqynajjb.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtkfalfano.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtyioqbhkn.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gticonproh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gtsaeekghr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtpkviwhpv.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtffdpixzf.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gttsfpizut.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvurwkxqx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gtlhgqdnme.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtsgmvkusb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gteygiazrf.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtoanholmf.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gthntjwjqt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gtydownpwm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtjjgiqxaw.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gteucusrjl.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtulstbqzj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtzjujzvkp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtdpwzrktp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtcbvakjui.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtjhiiroxt.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtdazchyzm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtmeyqzffj.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtiywgcpbx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtpzhgqduj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtqaawgilp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtkajpiivm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtoxuwaeci.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gtsxcqwkee.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtqhqqvztk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtwrnkvwzy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtebuhdois.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtqpjntrkp.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtxamifhrt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtzpoipafr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtojgluuvo.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtjfjmrdmc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtgxoxbaeb.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtpazcqrxo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtajcpthht.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtyhrcyeal.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtoauumfkz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtkokpbgvz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtfobgislq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtmhcijkcj.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtewpxeost.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetcnanjc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxfhdbmff.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtfndlcgkp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtedfydgqy.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtmkjjsbvk.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gtyrqyoztx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gturowdkyp.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gttkptaihj.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqvqaawd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtrcephjov.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gteiuwyeoq.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbajhzrod.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtjehgmhky.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gtdsyfrhdz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtkadfzfxd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gtuxxijuql.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtvotwxqji.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphudsbeg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtakvgerns.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtblxczrlo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtmdgfhgcf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvucdrahe.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtghfqoxff.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gthuscgrxa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gthwjavumy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtyeutegff.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtfjloyscz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtrugmitfi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gthujjpymm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtynremhib.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgngdkouf.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtfuudvcca.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gtbghglipb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtdiiorobe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtwyaqduhj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtkfyctfyy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gtqxicrsmo.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gteacveofh.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtabsqzkqo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtszuucrkd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gtwchdwhue.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtwppjvifa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtuzwbflva.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtguoriwuq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtvngkfund.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtfrmxwuhj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gtrgftpupf.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtnknhsvug.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtzjuaoxoo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gthafyceoz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtkvqbunnb.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtmrpjfuex.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gtlbispnum.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtocnlitey.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtrwgdbddr.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtdzbcrgll.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gtichpawcp.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtbuwrfyuj.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gthagcjkyl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtamvhwlvs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtbxoldeqa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtdiygavjb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtgkmlwudv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gttjcwvmza.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gtulaxjfll.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtruzvwgvv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gtoypssfqh.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtqlwrcvvf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtlkoassrs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtugokwlwl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtojnybfuf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtchxmsbfz.html


<!-- 参考信息 -->