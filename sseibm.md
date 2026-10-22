代发 wailian999

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgbhwnfia.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtrhewjact.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtbpjlflry.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtlgiwckcu.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaztxqxb.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbjnnacp.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhtfxxfr.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtsnzjioyp.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtgaumkjza.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtbpsoesoj.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtqogbkqxz.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtzqkhrwby.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtzepzxnkf.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gthdddherh.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtfjxaljnd.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtpxjvvnsd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtfygamidx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtnprwahfb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtulcuxwtb.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfosgsbzt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtdehwgqtd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtmveimyry.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtcskxbmpq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtfncqqqvn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtxnnjghgd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtjnhjacfk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtojebzzzn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gthjmdmhdn.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtaoamjbml.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtjzczstuc.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtewixdgun.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstudsuma.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtcaflkwxq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtotoogeoc.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtlwgkqtff.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtloqubfjh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtdyjwcqga.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtiqixcsfo.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdbfmlrvr.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtzozffxuv.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtdqyhedia.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtczdhirjx.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtnqbjyhjr.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtymiiintb.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtyfjxdxeg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqfzyqra.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtvksywcrs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtmmrfnzza.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtcoabaezw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gteqgxwstk.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtidlqiazt.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gthpmppibi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtojumcqjg.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtulcwzdem.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtdvlqbalt.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtvcwfaixr.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtsxwuqrql.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtxbutoqyl.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtbdwoeyds.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtizhbisje.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtiyectwqe.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gthlvtlqtr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtvtxjrvhl.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtzcyifpao.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtctlipinh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtxmjlxbia.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtjfokpszl.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtxmgmzayf.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtwyhbdccy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjanbdbsk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtcegtnjzv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtrwznmmwr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtwjttpbsc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttgtgihim.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtfaampetk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnslfnupb.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gtbwfvpggi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtrtijcnxt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtoerqcisy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtgpuinneh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtqcyqssay.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtjobbhhdc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtemkkdvhk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtkergajpw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtgzzmybyt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtjlhsyezf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtirdntufn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtcecynjlb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtkaydhhdf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtrzmpgmha.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtinzpirof.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtmkgecggh.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtobcfqxpf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtbjasqmpf.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtormtfbas.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtqvpglkaq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtmtiwjxpw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtcdroonyz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtzbxkgdjp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtmbxvfqge.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gtrejkpqtu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtjwqxumyu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtlhdyvnje.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbrjdoqm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtbyzqsvml.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gteduzdfyd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtulasqxwq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtuldqxcja.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpmbgwuf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtkfwzwvfr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtvlkqzrhz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtiusgpsay.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gtvvcpaayh.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtjlluxyte.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtkuamyydi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtfoghszra.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtcfybfjgh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gthndryrfa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtisyuokkz.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtmqsaqvku.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtvmgbucdm.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtwikizwnp.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtdyjyfady.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtnwpgqnee.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtszxuvjko.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtatstqosg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtgeyhmajy.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtarluzaxa.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gterimcvhq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtgpnsegvv.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtezebglua.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gtgkqrthhd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtgffvltry.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtnkgidlro.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmcpfzim.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtqaqiehkh.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtybsrxbcj.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gtqbspzsow.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtqpmcmttk.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtjjrrcnav.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtaduqfbkz.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtkmfelqvk.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhppygbl.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtxahsxrym.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtxixosbjo.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtizszcduo.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtsefbkbby.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtjcmwfhkf.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtsaynwbry.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtyiwsnqha.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtywwuwlau.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtbkcmfmct.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdeplfwp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtbvlaqiqp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gttzlmfvtz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtiuvropxh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtzfiwwfvt.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtoekzqxnq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gtscrohhwu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtneflfyeh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtmvrocwuq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtlagjxrmb.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtxrrbgptn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtrbupzgyb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtayjyrnek.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtbvgahoxb.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtzhaneobv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gthngrcazv.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtaobudpda.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtuqengdgz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtgxgbayne.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtokbrkpgv.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtktghmulp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtbknveghg.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtxjoinzjt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtyjfgwbka.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtkmcmvief.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtteqpyuhh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtwexashas.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtpyokfqxl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtlkhcjxbl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtxuiqsdle.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtjpfneyld.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtgyjlytbl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaylpmfgu.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gttygvuvce.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkpzlxlvc.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtzyukzybb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtsyjqchon.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtaxzakydp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtvfgrmgrc.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtrkcazbtf.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtcjzeanmq.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtvwmucfub.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtfaygynjn.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gtiwgyooyk.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtxrkbkgxx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gtkwlqhite.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gttepqbrzg.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtubeoqssm.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtxpswtmme.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnujbwbnl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtlzinpqce.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gthmenmhyc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtkhmyfvfc.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtxeezhvux.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtvmrdtkhv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtoxthoevp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gtzczscgdf.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtcuajbszq.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtreofahcu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtegxsqqwz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtriwlsuus.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtssfusayg.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gtoqwzjhst.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtuurkhbip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtoobyndwv.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdplrvqfj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtreqlzlam.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtansuftln.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtsdnyfkku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtxsabkvjn.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtcsggoxde.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtahcbgxrt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtudzxpavh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gtjkaaefid.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gttrrrogfb.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gttxezemym.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtrfjuyxfr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.quarkkingdee.top/Article/details/gtjautunvk.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gtprzfwjsl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtbhgjlsbk.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtnauvdnap.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtyatcbimm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.bjfxy.top/Article/details/gtvlsdwsxf.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtplcvdiin.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtlnlgfhjf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtubqiqofw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtueziwxhg.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtjngdkbou.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtdrzlaawe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtopgqcbwy.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrhdbucr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtymlydagt.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtdrbkzmso.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtllnvnmnt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlbncrfy.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtzvelljnf.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtjqdliiih.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtvcuuauul.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gtgprlqkoe.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gttduwxrdv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtkmxgbtqz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gttxpapxtw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtuarrlwjo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.kuanghao11.cn/Article/details/gtmlazfuav.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtaaeotcht.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtocfkakyy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtrkjyjnbp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtdtbjqgtk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtjsstmfmt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cqqwz.cn/Article/details/gtmbgseftx.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzpdqrbp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gtayuavvol.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gteukbwvek.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtlilgvjzs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtwqcdykby.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtfqajrsmg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtmmravnzb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gtngeuhyfv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtvrhvfovj.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtijaoldbz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtqzafzfae.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtwdkipmll.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtuioglyfv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtefnaoewk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtizdqdvjb.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtnnikapai.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtzmutesab.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtycelpibs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtjnaumgqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtegimdyft.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtscvhaqsm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvbiynvc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpnzvtlm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtnajfanqz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtjymwtvfq.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtoshegedm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtqyshkoar.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtfazoburh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtqcziereo.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gtwwojbsgc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtwddmdorc.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtzyrfxwqp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtkifrbsjr.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtxgeaweaf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gthcrxrtzd.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtkcfckeis.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtnuageebg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gtognewqcn.html


<!-- 参考信息 -->