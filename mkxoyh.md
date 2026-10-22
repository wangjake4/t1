代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2hnesxpdi.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2amnrojho.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2heaihksp.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2zjbdwbvi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2omctqbyg.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2xbkzkykk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2tpcbtkae.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2zpyryarl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gt2jwjizgik.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gt2ejpkjyxh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2nyqvikit.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2rygmrmsc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gt2tbbtccuz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gt2yrwdlaqn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2swpgxrhk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2rkpoxygi.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gt2fcotormo.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2xxrdoqbp.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2zynqzhxu.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2vlcbwbxo.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2iupazixd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vushjffe.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2covgbagw.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gt2otnnswyr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmxdekvv.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnrawebp.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2pjuriieu.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2giorjpjj.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpokhspe.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2zvxobuom.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2tvnsqzkt.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2loqsqthk.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gt2ehniolcu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gt2pmuinxnj.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2orykjygg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gt2uwyrvvvz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gt2yiqgrixm.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2iouxlowx.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2mwcukghd.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gt2ctuuenmj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2davzvxen.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gt2iarmfvrn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gt2zjdasqsm.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2dcboqifs.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2ovvepsaq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2zlnzmshq.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2yttcunaw.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2mgfxvmvt.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gt2ygdegdha.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2gflthrsa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2fusxctnj.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gt2bhlnxvub.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2xrkqjcjd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2tqfnfrvx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkqlmtz.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2psmmnzow.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwhjlury.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puooxdwq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gt2jhnffgwv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2loiihnyt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gt2lszvsznk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2hxldcxwe.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2oipwskat.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qcmyyojv.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2wlahyczr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2dmlrjyet.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2yqgtccjf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2cholaxry.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iiwsxyyz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2bksaxizd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2mazcydtg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2kgtvdoyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2xvjpvmhv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gt2vubfacix.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2xalyeyll.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2rhrcipeu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnapquap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hndotatv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gt2npcpxxao.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2ihgnveey.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2nngthsqs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gt2rbygrxbz.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gt2jjnvcjbw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gt2eevwxxjg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gt2kwevrwvi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gt2umqpcnvz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2dthggolo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2xncpaugu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gt2xexlbtae.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gt2dbnxkklv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gt2dtsrvhvn.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2czhpyfem.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2bsbqkoem.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2fhoabbla.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2scclcgun.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2xbkcsxhw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihantvml.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucotwkrm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gt2wpzginii.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2ucelboob.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oernelgl.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2xhjqwtxf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2canjikgf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2mdrfqgqq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2odqcergw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2oszofxbt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gt2qpewkiek.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gt2pywomdlj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vkkluwjr.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gt2tuzzwefl.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gt2jgfqfzng.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2itvirpdw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2ekiwpzph.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2qswfhahs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2klsscfwy.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gt2dkwjnuyq.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gt2wdfltkvr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2ynsbjyjl.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gt2obatzdix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gt2vdlfdduh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gt2cttzltps.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gt2itwtuhup.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gt2pbddbxlq.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gt2tsrssrgb.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gt2pcfdnnlf.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gt2sgyxslxg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gt2mvisptko.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gt2bgsgwmtc.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2zjpfjsoc.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gt2nfnfzblf.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2ulffdojb.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2wamiylts.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2jikjzjro.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2mdywkxfi.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gt2udvodhox.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2xdurvuyo.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2mgrihavc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2irsgswbr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2zvacvtie.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2kdwpwcfd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gt2hapviwqg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2jltvgbmk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2hacwjqkk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2uouqugsj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2xenaijsw.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2xslrnfpk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gt2rdbaolij.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jhyyfhfg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gt2lfhtvdvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xinyue.icu/Article/details/gt2bnmfdewo.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npcgsret.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2abfwttgs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gt2hzeiyzmi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2mkxgfqzd.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ellmfqji.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gt2fzipyyug.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2nfmpwcgr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2zcmjaohw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2ppthltqx.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2xabjzxtt.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2igdfbvfi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gt2kgewdthn.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvviatcv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gt2ynjzodyr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2extznfnh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2hcbjufad.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2wffxwtub.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2wvitxggy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2ydokvblj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gt2bhxiesuz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnqzz.top/Article/details/gt2pjlpmczc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2cbmjzekm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vphkxsma.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2cmfsvtdr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fmolugep.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gt2xcmfuhqe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gt2kklxjflv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gt2fksymiid.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gt2huaxunan.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2jjxieyig.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gt2ugxprene.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gt2tzicyafc.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gt2xfbxadrs.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gt2iohlfixx.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gt2ivqozmqx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2dhvnjmuo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2stjvkknc.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2jlzouumg.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkwtyqcf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqaafbjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gt2cozdsymp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpbatlrp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gt2pozsswcs.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gt2aqymutjn.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjgegykf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gt2eicssfxg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gt2oajwvbga.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2begvbrzi.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gt2nyyxghfs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gt2zcigzscm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gt2zmsxjnra.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2ezdaediz.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gt2gpaxwmkx.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2mrrwyyzq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gt2ugrjhwxy.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2dhjaapiq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gt2osoanbxt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdwksrqp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gt2fkynkyhp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gt2tppdzstu.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ofzwtbpk.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gt2zbpgybsl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2tcmolqbb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2wxflfjuz.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2xsesbqsr.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2ntglwluw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gt2buoodton.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gt2flglqwti.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2chkwenyw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gt2yfgysqbi.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gt2wqgwxfxx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2ukxdbwsr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gt2yxcbfrde.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2ersapcye.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmanicvd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2vtjsrynj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gt2qwrsxxrx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhzjnya.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2lxssaziv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lumgjiuu.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2qattrxdd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kfzothtl.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gt2kbhhonyn.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gt2cqtwjqpg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2zpcnnlvd.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2xjnndhxn.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2uajpjwlj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2nbsxjojo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gt2jiawmwql.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2symqjont.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gt2pleyvowi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2megduhbx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gt2jowwwnfx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gt2vvokrfyq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gt2ywcvqyrt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gt2cbsnqwoh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2saewyriy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gt2tsvhlbfi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2jyxsjiei.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gt2kvblilck.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gt2swxncbjy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gt2udbgeemy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gt2qfygrokg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2xbqzfqfb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gt2apcjieqg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gt2rpxkmmvb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gt2zsqgvpsb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gt2ijwrpklf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysxxkrzz.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gt2vjpnhgoe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gt2xheroadw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2dvnabknt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2onksxdva.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2olsyqpuv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2svjbrcyu.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gt2ytrmtjoz.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfkjsnkb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2bznqyymj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gt2xkhjpaal.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzrgvqpv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gt2zfksoobd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gt2aldjshne.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2jbkxshdg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gt2ikzytaen.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2jbyrkvsr.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2lmjejpno.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gt2mfnpbghw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gt2jzxlzgtj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gt2tsgcanob.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2glfmuitv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gt2efxisjqs.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gt2wrpejxha.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2kmyuwwnc.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gt2bswtzoef.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qikomxdw.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gt2cmlnhcbn.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gt2bctfllso.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2ylbfflnz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjiabnmi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2urreggcl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2imphkjzd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gt2kjubgudt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gt2wtkbbyat.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gt2dvxvvlnf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cheryme.top/Article/details/gt2nabculyq.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gt2swkhisfp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtlswgvt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gt2fhhekdhg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gt2xthkuytq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2gghepnup.html


<!-- 参考信息 -->