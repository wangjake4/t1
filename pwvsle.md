代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2eclevrua.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2btpeeugn.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2fpyntjjd.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gt2jmnmaxwd.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2ipagtzbw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2rvxmbbrl.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2gvbsfize.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2ybnyrgwv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2tqaxrrln.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2ootkibbw.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2nohrvqhz.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2mijdrgez.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2gixswucv.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gt2rdzducxy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2vshsmckj.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2hrhbtmnb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2cyctynmw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrpleubl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2ukybpliu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2cmrmfsdz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gt2wmpfxuzc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2pgiouxgn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqvogyhj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2xnqxbodn.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gt2qzvwkvbl.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2ufbhrnsy.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gt2pmcilfyc.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vztqvyql.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2uedfiyjj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzfltvln.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gt2hswunuej.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gt2chuobvbw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2icapimdm.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2ewditsvl.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2fhrsgkgp.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2myurlvor.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2hfgyqack.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2hpefeuvu.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2pfinteay.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufpxeyha.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gt2ypmrzecn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gt2oyisejff.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gt2tmewlmhv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2jrpiawqo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gt2xkxsvxdu.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2avoqechp.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2tnphyijb.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2voaedcye.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2cjewtzgk.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2yvbfrrdg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2ussprdau.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2bqqygyui.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gt2sanbvcmh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gt2ndhqtnal.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2qkpcwdea.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnglziow.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gt2bcugoehi.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gt2ryghcpsx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gt2mpsmuxne.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2tbojqdgp.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgkedbtf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2jnfkmfux.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2waxppvvr.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2wqkopsrs.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2pbapvjpv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gt2mvkrgbca.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gt2vmvgxebf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2lkatzkut.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gt2oveqsxbh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tjhbbkxv.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2jhbhqvvt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2sdzqehkb.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gt2crtnzcar.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2rrzqsawr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2zycncwtq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2fajythfk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2zyfubixv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njavbrer.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2fudgvgyg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbswwpet.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2husnrmaf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahislbxs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2gwxjxhdv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2gtqpajvf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2slqaupan.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2dohockpa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2hnbhkyow.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2uzujsubj.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2efgypceo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gt2jqlscqyj.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gt2rhtgbckj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gt2wwnjgoln.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gt2oicchdlc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2ohwwjvqm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2mlmgddhh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehpkrgub.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gt2gfbdnpmi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gt2mcphardr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gt2hooyfsqu.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gt2cxitxzpe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gt2mcpranbh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2persblkt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2qizexyah.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2zjornffv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2vdcjtrfa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gt2eshegpqp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2lnpcdjjg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2sajvlozf.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjmcodxw.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nozhslmd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gt2xmdchmoj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2utcygknf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2cmrwcctb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gt2orhutpyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gt2jwhwnzag.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2qngengki.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gt2ckcjllvk.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gt2sovmygqo.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2xvtbwjxq.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2yanvjyjd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2ahksnzag.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2mnfptpvy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gt2gwwwebjq.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gt2ooopcytv.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2kdqgzkcz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2zwzduhgz.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gt2hjxklazb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2lgobeygd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gt2kyjlcgmu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gt2jvlxvvra.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gt2qofriciz.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gt2baakcglh.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gt2pwygalat.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gt2xebdalrn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyfgnlib.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2hctnwapm.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2udfdzhnl.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdeazhsl.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2oduafoqg.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2aozffnid.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2aqcknypn.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2ztgpoyxa.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gt2ijwrmjdo.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2kwgvaikx.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2yerfojmi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2uugfrntn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2ermonnog.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2lespuuma.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fowoprhk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2hostyifx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gt2ixqtmsrm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2srkrgaxm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2cxdmfpju.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2kfnqarjq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gt2ercbxgvz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vskzeoko.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gt2irqzzfsp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gt2azlxzxzr.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gt2gqekaulj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2erqpnbgc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2giqnayuq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gt2ibqkymsx.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2qzyvojqr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gt2pxeotclq.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gt2jzdnofyf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2cllvppdz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxlruqhc.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzchjqks.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2szapvbdt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gt2caeursod.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2fgswkmbc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gt2tlalaqqp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gt2tcrigrck.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gt2jsackrka.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gt2xrlvhcrg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2uiieqaem.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2cmahjdzs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2zbzgsnhk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gt2qdhwtvrx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2vmucwrjl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2sysrpoze.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gt2xcrfttwr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gwvpmdyc.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgpfblum.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2haaxmung.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gt2fofkkivw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gt2nobttspk.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2iyaywvds.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gt2mjzwwbnx.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gt2pfmvgehg.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gt2prcomkhc.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2khrenyxa.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gt2fvxjdcex.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlowgrii.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gt2regtluad.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2bwxewlwt.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2vzbubuzu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gt2pzyuawxc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2bjfxejle.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gt2zvpoxkbx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gt2edvutzff.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gt2ldmiybhp.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gt2jwuvafjg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gt2uwizrpil.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2bqrgaryb.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2yhgsyaaw.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2yelwwbkb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gt2xfxfjfos.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwilphek.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2ldyojsnm.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2hfzljpnr.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2mumtgmwe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gt2rmjcujuq.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2omqikzph.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2hsmewekc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gt2psvfxpdh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gt2xknwwriw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gt2fkncacfb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2skzwlowc.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2ofsrajqk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2cssejmun.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gt2ekfssivu.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okpxtuxa.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2yqmvluzl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gt2hubykwtm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2uoqrbesi.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2kedtnjpf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gt2lfpwoayz.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gt2uxnmtsyw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkifrcyk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gt2znlnjuft.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2zrqjqoic.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2fqdxtrmk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gt2vgkeujfn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gt2dhspvogq.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gt2ngktdsxv.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gt2odibcvao.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ltgxpjsp.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2kjurzwmo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2iqsmcxci.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdtkixbf.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfgpmnws.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gt2uoxcihcy.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2vnyhrpnn.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2xysxavby.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2svgqjhlg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2iniphbhe.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2fawwgbzc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gt2kiwhixux.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enzpllzk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gt2zaskkehg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gt2joztimhq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmdbkqlb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gt2kkrndkit.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2gjmhspat.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gt2tihbxyvq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2phnmgfgg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gt2lbqmmmhm.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gt2bavtzjwy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2svvptplb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aslggugt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2ktyuyutc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2rrizggfq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2zsavrods.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gt2tlwyqjrm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gt2pzlapybx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gt2udvswryh.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gt2vcnbfjng.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gt2dxayxrmz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2wlfpedsi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2uiiyowgz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2tyurghau.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gt2brjacwnv.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gt2deieevnu.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gt2gqhyrywz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2rtoealvz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gt2cnplonbb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvjakfma.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gt2qfihpbsk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2ukumsazb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2putzxocj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gt2lapujdiy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2jdkscliq.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gt2trnnvctv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gt2wltmlcdn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gt2jnxfqqbr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2xacaaoxg.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2tlbzjmqu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gt2pvnpgfzf.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ulbyytaw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2bwifgwtz.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gt2wzhsqgdo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gt2annfrfet.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2gdcvfkzb.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gt2wlmekwvr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gt2kabrlwil.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gt2dnxmupan.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2jjmbrmpd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2tvlqsezc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ugiyvmil.html


<!-- 参考信息 -->