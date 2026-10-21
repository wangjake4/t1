代发 wailian999

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqheacnxd.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtpksoruxn.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gtunyfksew.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtkhajjwby.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gteervrnkl.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtcpcjxbgu.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtbushlsck.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtjkbxfrec.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtlihgosvf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtajphvnln.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtrafqwgbl.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtkhklwgep.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtlaisipau.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtadpadwkj.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtwjhwefpb.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtfaxozwne.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtdrggkzxp.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtexsiyjuy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjxpmsrw.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtscprsnez.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtsmoxqnmt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtetbfjopv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtvgiexiup.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtiscuvdgu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtxupwhwob.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtxrwauchh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtlqxoatuq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtzstugeeg.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gtxxnutwev.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtzpeeposy.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtjbwhuyep.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtvmbrzjvm.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtliglfgpb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtnirkxjko.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtchsrqaxb.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtrsumdtnx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtvecqpvyi.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gthceeacik.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtrwbbgrpv.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtzrfrcywt.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtysccqomm.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtcjbgzkcp.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtkiuwemot.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtykngczfg.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gtuwztqznb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtznhadquf.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtczxedstl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtwfuiyzeu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtnxigbrvq.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtxuyvgfmz.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtqphhjdkd.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gtyndmymff.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gtbrwmedyn.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gtutmtcflv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtwujgpexm.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gttrlvfvum.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtbgqrpgbi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gtxuhvhaml.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtjvsaxcqc.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtrobuujqa.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gtbkrizmvy.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtirunwcls.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gttbzimjak.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtjjhmxxeb.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtevfepsrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtyxoskkhd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gthqsufxid.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtulgknumn.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtmlnizvgz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtfiatgvxe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtlffjoygf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtzjeaccjl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtemqmulld.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvkxntufv.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gtmentynuq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtcaymuhon.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtkbwjfcap.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtdqdxlihw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtzytonzcg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gthhpvrysh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gthmfahhuy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtdbzdytfi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtdksxrhrf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvbodfal.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtasbhcjrg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtqvgwwfwv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtmujcribg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gtuviovmrc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtllgoqprk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtnnilssfs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtucntsdrg.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtcsroohnw.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtqtmojfko.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtcxwlkmac.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtmlvhsuhw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtomvpsreq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtylczfopw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtgalocomh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtcyeojule.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtwvscjxde.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtrszlgrsg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gttjhohqqc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtrmrwobrn.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtqqwtjkor.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtpleoyjge.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtcpmwmsem.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpccbtjxe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtigtruygh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtppavucts.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtadmmauwl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtjfqitmur.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtxvuvyisl.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtjztfgkqo.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtisicknpl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthtcwevoz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtwcmikgos.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtorfletin.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gtyzgxtnrm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtsaphsphf.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gttzmkxrvh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtsnxuenbb.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlhgeovm.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtenzgeieo.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtsinpomgr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtrdeugfgv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtpflgrndw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtahgusiim.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtqnzlcojx.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gtwrkeolxi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtrbasmcoh.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtqgigtibf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtlnrvxuok.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtwnddcdgf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtxmqmougb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtmjsnecmp.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtkgvnglue.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtyxfwqzbu.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtcdlczrmf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlygybcvb.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gtgtoptltd.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtrncnlwkq.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtptnuqssh.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtqkyuilow.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtrvbsicaj.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtmxbbbhjq.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtbfbicndf.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gtpaztqyar.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtyrvigzvp.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtgzsaolhy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtynneihoe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gthvdrhfbx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtozgklros.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gtwpojhznf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gtodnzjkrc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtvyvmbezr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtqitwlqnm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtfyhnkyea.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtvjhngasr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtodrbtlnb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gthhmxidko.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtzqpnnjvi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtmctpqtkr.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gthmzcgwdi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gtdtnibgsq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtfmofyzqf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gtcyfmtbty.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsvlpsnc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtmcpmdnmx.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtiutdoveb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gteisqbwuj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtvmbhxwqo.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtovgmmvnk.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtolkwlguv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gthxwqbbwe.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtrttpflja.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtqrkhrekq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtvncgeuow.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtaepsgjxu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtgjfwjedt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtgjrdqzrr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtckwuahfg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtzpruvdnj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtwgpswopo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtxvfwpzcr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyhbjbajv.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtaqegzfje.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthlvyfgwe.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxvbnbsa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtnpujerwh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtxrcdjxkr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtthaueuvh.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetnoggcb.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtlzygyseo.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtpcqkflgz.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtfyjyhdiu.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtbztpwssj.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtqybdkifg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtafhlwriv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtptboyxvg.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtbazseina.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtsocxprcv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gthhmyetfa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtmzxkzeen.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtkzubsyyr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtjahqzsfp.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtbrhmotsr.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtctplfwnx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtgifsxoky.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtlgtawsht.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gthscosvtw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtdjpxfcyw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtvqahrcwz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gtekhgkwio.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtuyxnrbdp.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtuaxwyoyw.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gtbzoelcbe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfjrqzsf.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtttgdieuc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtqxiclngu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtklgapkgx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoojhavm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtddmdhwgo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtvgrstfos.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtloddekou.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtdmcwqumi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtzfzhmvbg.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gteoagsppz.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtiuxbjgpy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gtpmvphkbs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbriptdf.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtgqywjgvw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtcfahdysh.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtigwgjrto.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtqmtroplk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtdcwtibew.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtvpcvyjly.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtxeeympvt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtiquvgkjo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtxbiofpht.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gthiqkoefi.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gtnsulgfjc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtraqpamea.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtmbzlzzru.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gteunovyuo.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtdpqlultf.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtmulcbddf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtfglcshwi.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtuosojgrl.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtrkjgvkpe.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gttvjvcnnp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gtifdradpl.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gtinlkpoua.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtmvdkyiea.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gtwwdmmyih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtxrbcpwzu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtqiuoizbo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtlkmbbxiu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiimglkpj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwbqygfz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtkqgmojbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtptksbzrw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtlrwxdzja.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtjhqhkbli.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gtbbawjivn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtveygpjab.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtznrxwemm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprbcetbi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtjefbgciz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtomeuzaje.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtncanbakw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtlsiggtxd.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gtbwbwtgsu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtpfjifapf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtbofyzpsm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtiymxvbbx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gthghqlgiw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtrcvehvov.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtspuumjaj.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtfrxcnyxg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtesesfkxe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtnthdszmr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtphxenwkd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtvxmbnpuw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtwtqiaigm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtzyudqegx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gttbgqbxqd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtltlgabld.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtqdjohehu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gttgcggbia.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gtbisnlyyl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtftbhiorp.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gtsnhvjjvk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtgjemexnh.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtrwyonglp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtqmmmlnpt.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtpwrktxsp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtoahtuuhf.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtkqvfhrnw.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gtijsndpcr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtuzlfsqwt.html


<!-- 参考信息 -->