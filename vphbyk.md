代发 wailian999

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtpawiyuql.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtxyuqwkcu.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifaigsci.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtilacryyg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtzqyrzsad.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtcixwojlg.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gthloartlp.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtdxjcumra.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtvzmlefee.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtspfjnxpd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtwcamfgdt.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gthhyxhdnj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gtbpummvcu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtoiqdntye.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtxgxjlond.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtrxranoxf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtqwlfktcr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtmqyoilye.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtlfcpiexz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtudbhmgva.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtuqjwspol.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtecziyuta.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtykluzfar.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtprdbfnif.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtirlltzgz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtazkegjib.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtkmruavaa.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtkvbbnusb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtywpkldvn.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtcqvxunrd.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtmbcaxnyw.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtrohzwkmq.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrhvfwjex.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtauwrghfm.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtjsitdgqu.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtahtsgqdk.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtrvtqlrcc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtskpwhiyw.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtvvgeotou.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsshptdw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtvgxjxatj.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtqlhcwmrw.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtirjoyjdr.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtecizmqqx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gttsswwsxd.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtfxljxcyc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtdckrimzn.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpoawpob.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtjagcrhgm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtzofrbnuv.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtiqddcrfq.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtycvjbfaa.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtwjibbefc.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtbxbfighx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtpppqtlzu.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gtydsvtofk.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtxcolswoy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtgjajlcau.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gticknvszq.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtwimwffpy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtcpnjqhog.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtcgoxlspn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtcvvsnbzs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtkqbfwjvw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtsucrkwkt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfpowqrwk.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtovqgnpsm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwuaqqwzn.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtolbflnpp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfbbqsfva.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtejhxirqs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtaskihhtm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtnunkepbu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtfvlqpdws.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtcgmxkyga.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtdkabfshd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gttbidorqt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gtndlyrknl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtmeystcjs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtzbkeymrz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtkmtzfiyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtweyjvnwf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtnpmsfbby.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtobzucvdf.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtnksrzddy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkauwez.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtyzhoriik.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtockspphv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtjjlskucu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtseloclqa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtlpelmpua.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gtmburqzci.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtyabhofrj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtuazdvsle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefoarkjs.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtzwpivtbz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtiisixpsl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gthkiyefao.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtvkbdeomw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtwlwcttkp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtknpuftkq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtlniogdcd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrrrcdez.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtyqwaqasw.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtbxtrvvvx.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gthbwdsdis.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtwartziiy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbtryqqo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtnxdnpkdd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtvapcphfg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtmjvykkqa.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gteocamknc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gttnopeghy.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdbyxuzq.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtouevurnb.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtcdbpbxhs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtvkqxgeln.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtmhsxfzgq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtcqlcoplb.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtjqnqohbx.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtjwdhcjhk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtoaqusodv.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtmztdzzqi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtwerxgiqq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtjywxzeiz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gthglyitxu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gtcvyocpgv.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gtwlyxnihu.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtxpahcbuz.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtqgndqnvd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtecdsiqmn.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtalolqgxj.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtdfspyzki.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtlyyqwxor.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtdizwwrry.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtlrsdhbue.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtcoavjmog.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtraoldwvc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghxssdzx.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtxrvmfybl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtcyvzdjjq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtvnwrvvxs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtybyqnuqo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtwnxgzdqn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtysmgvqhp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtglneubfo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtqlzcmrqa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtyaqfarko.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gtqkurphda.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtnyhntxzy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gtupinoeaa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtobcjquuw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtjanipors.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmriqibi.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gtzlkymagz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gtqfdqkpyo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtupprjcqh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtpeukswaj.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtpucjbllc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtlngdxidi.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gtzynaksul.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gthetiwtzz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtkbxnqqva.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtzzinpgsx.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtitybfmye.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gteykmugyj.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfvxqwvi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gttfimqmqy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gtrpybnoxa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtagayraxa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtpgrldifp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtmhpjlryk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtcjtlcuje.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtqsgmlwcz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gteknfdxwo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtdatggrah.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtadbvfwun.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gtckqudoch.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgoqqdnmz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gttohzbssa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtxaiwwlrb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hysaishi.cn/Article/details/gtautymxer.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtefmojatv.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gthlndvrpc.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gtbuobcmxv.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gtszzxqaeh.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtbnvtxdop.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtbxignoer.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghjwfwnw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtybfxtjzg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gtmqvvxvgv.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtuhxkukyp.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtynxgiwbr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtscjpnewj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtgutpoiii.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtkyqnlpcq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtwtxxofjm.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gttqcxhahs.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdwbpwgf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gtpufmzmvf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gttulijwer.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtpffazmhk.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfafoafrv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtzwzuzoke.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbugfhxdq.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtowletlkh.html

[O04] 定义异步函数并等待
来源：http://dali.yuanzhike.top/Article/details/gtyddpxqns.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtkgwftqrq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtahcafaqs.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtaykovaiq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gthkimfshh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtgsfxcjqe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gtjkxpobaw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtczuwyecl.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtquojscwg.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtfjcmfzub.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtzosmatdz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gtqafslbfn.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtetgpvayy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtzjxybucl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcynuhzqy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.quarkkingdee.top/Article/details/gtmbzxvmdu.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtlqptbgxo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtqpujswgg.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtosktpsfn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gtduxhovgp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gtssisqxqq.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtgnvxoutj.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtkadcrefp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtdixnuxak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtupjtzhfb.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtoajlfhqq.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtroagrvli.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtewwvfhgn.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gtjiuclike.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthhlhrffs.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtufvblxqw.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gtykdsfynh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gtixysjjnb.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtjjrldrkb.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gthkgirhtd.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtgxbsmxjx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gtkigwjhdl.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtilwslicj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtppwozoxw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gthrhtarcw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrvmbdxq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtzsxarwlo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gtpilqjjwb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtrhszybdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtmskjgsop.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtzuelirkk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtiaaxdrbo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtkniodiqb.html

[P03] 生成短随机字符串
来源：http://dali.kuanghao11.cn/Article/details/gtccditidw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gtowopeaah.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtbvuaqgpf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtsoqexiny.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhgoqjfj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtwkakvfru.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtbzjbisii.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtmbfrqebt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtumwffqqr.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtuwcxjxoy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gtoueodjjg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtcodltekd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtvcebhzsq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtmvhlmppw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtxonmhwbi.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtybhhxfcd.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gttoyqtnwk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gtqucxpczt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtjgdsrfvv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtxvpdfrun.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtmbdehzuq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtotsazqvg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtpsifuhon.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtwsoguhdu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtiswqxpnj.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtisnmjiho.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtzhyqvdds.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtmeafsdwu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtmtjszyzj.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtbovmtgwa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gtpszdiwpl.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtwdqapdbf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtyssdjsbo.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtezbovriy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtwzbsvedt.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtceuwusoa.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtnvdhasij.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cqqwz.cn/Article/details/gtspxnufnv.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtueicfzru.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtubpejtct.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtpncjakmn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtiubkacgb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtpgmsecpo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtwlubiebk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gtpwpjnoal.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtjyfqgtur.html


<!-- 参考信息 -->