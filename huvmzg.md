代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2iefjmhsv.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gt2puirzsos.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2aovqkqdh.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2bqnmfrpr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2anfohzea.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gt2yhxqdmgg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2gwujzfnw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2hmdhdobq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gt2hrpbwokj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gt2nrezgrsc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gt2rddbwlam.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2wutrwfmy.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2pjgxgwos.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gt2alwxeqdv.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2xwnareay.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2kxqvfclo.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2jgjbrxpo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gt2mostpbae.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gt2fqrlykrc.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2dopfchxd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gt2wwjzppmu.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2ysobgoiq.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2xgyyptge.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gt2cwwqaznn.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2jcwrqswj.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2jvgeexue.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2niviirbl.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2arunyvhu.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2zqqgnvmw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gt2gokzydwd.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gt2ajipohnu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2bdzfpwkq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gt2zllbhvsn.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2ocdhrcuz.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2dprfrbfr.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gt2rnjnzvgy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gt2hoketouq.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbalrkyt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2uhgltbxj.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gt2ebqmaleu.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gt2ovcrmknl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gt2tydwayqo.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2kbyshdsk.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2uuyaawth.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2pylvjugk.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gt2omqzgeod.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2cqbjrcck.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2vsbbjmmr.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2adbydouf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gt2dtksheis.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2ejwrfblg.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2wopnmjyz.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2zcfbcerl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gt2rhdmbgqx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gt2hpzezunb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gt2flmvoggr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gt2emvjoccc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2vfbbimgf.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnztugfq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wgfqxmch.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gt2yaqdppan.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2hawquwbb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2qbswaksu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2ettlcxgm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2qqurbnsn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2iypbgfsj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqgwzfw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gt2ezxncpgy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2vgxnmmpn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yibudtdp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eksrquts.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2nxpombsa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2dlmutldp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2uytsoohx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sisxwpkp.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqswdole.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2werkvlbs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gt2gtdmqyey.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gt2elpmxldp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gt2ndtvvucy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gt2jqsvycsk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2zqplyehb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2tpdotsom.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gt2livrefwr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2grxehuut.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gt2ybldtsbd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2hyyicufz.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikgkqzdj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhaiuxhe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsdtbcly.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qylancqh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygndjyeh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gt2srjyhogz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gt2jvakagks.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2cdxrycyu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2gcmpbijt.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gt2dhbdekqp.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlmtzwsw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gt2onrebkgi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2dlcgnaaw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2eoyndbnc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2zwtvolsq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gt2wrzoeoau.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyqvjgkp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gt2eupaiukn.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gt2fverhvnr.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gt2rfjrageg.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2dvpccyay.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2mqoqlxig.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2ngwnhaeo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gt2xxardjkm.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gt2kapmkkic.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2yiqfwrev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2kyggwazi.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gt2qgizthgb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gt2jrwtijmt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gt2bqwuqsgw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gt2lfvmogzz.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uynsaomw.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2fzebqswl.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gt2clveeius.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2aopgzjpy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gt2buxcnbju.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gt2ennuphuz.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gizvzmrz.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gt2oagjtvgs.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlzmfrln.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2eeocglag.html

Java: // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2vlwfpfvp.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2gmkdlpkz.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gt2npcwfmnm.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2rwzbwcjx.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gt2vysqrrro.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gt2bswqtnrg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2ernxyolc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2fwmgstga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gt2wfdhclmk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2eavctspp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2qzxckegs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2khxldngv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2gzdthnbv.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2whxaibuc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gt2aaifthwa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gt2gjgbomdl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gt2umzchchn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gt2trhdbtta.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gt2wqkdiclh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gt2kfltewfy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzfanois.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2swhpiyvd.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2kqogmtjj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2pihenmwi.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gt2kiqyuggl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2rhurilgs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gt2rmvprktk.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2tcucwppt.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2muokceve.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2zemayodo.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2qzkwrfpm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gt2jplzbqbq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2txxzvxmk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gt2kqtuvqen.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxgffgth.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2vjxzuddg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2mohfoslc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gt2zevjjyon.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gt2offuvjte.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2dxonoqwk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2chkqgcqb.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gt2pfiuhcmx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqcvncnk.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypjbtzrh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gt2lnjeywvn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gt2dwlhavey.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gt2lvnxvath.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2hddzewcf.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2fhdtqosy.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2jcutriiq.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2byumuylf.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gt2yfjsdktu.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gt2xvkdzjeh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gt2upvvbiac.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2acnfvsrc.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2pzwfrdsl.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2drsmziwj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gt2utfkaagp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gt2wploujlq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2rfojejlv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2jjzbvcws.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gt2etfmmfwk.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjueqgio.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gt2xnxxtedo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujixpfuz.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2norplpkb.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2zbedkuua.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gt2osnambbt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gt2dpznrdkj.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2jxetacui.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gt2lakmupqw.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gt2aokjduiv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2wsxzqmpw.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2srokcbgf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2lcmjmywc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gt2ichbnbtb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2hezhmhts.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gt2riedyzpa.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gt2tdcbsxfc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmdbdxdd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2ovgvmkbb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gt2nzazrptm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cluisyrl.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2ypxpxigm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gt2hddbyjdc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2phzjowff.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2qwfjcnvx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gt2mcybneii.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gt2eyokiptt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gt2eneozjin.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gt2nlmqoqst.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngiwarah.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2cegclfir.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2edxvrcye.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gt2yfkydice.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gt2soitsunl.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2ixlobknv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2odvnszrd.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gt2dzrapowr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zyyagpsy.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2aebhotzx.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gt2ntthavcd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tudgihnj.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2xevptdqs.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2exsjhefy.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gt2wbvxwwnw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aycpepem.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gt2dolrctpk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gt2xnrgyejn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuqzziti.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnohrell.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2sungyidq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gt2eoeoasgu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2nuomhxpg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2zpksttgy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gt2pnetrkph.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gt2elawhrpv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqlkitiz.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gt2juwiixkd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sufxvd.cn/Article/details/gt2ikcwhorm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gt2ptjzpuky.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2iwkgxkgf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2cmjpoooh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2clczeuan.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gt2wkgqpfni.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gt2cqlaeagc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2adlkascz.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtgfvukv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2exfsfsbt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2fkykbavb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2xihwsknd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkxateql.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2nxypkgmb.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gt2icbpifgm.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gt2sgvvsput.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2rzilwndf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gt2asdglbae.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gt2vilmpnks.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gt2wbqqlsso.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gt2mhqxegpc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2rasxcvza.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gt2sarqogjt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqgphrky.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzxaxwib.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gt2uwokywcq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gt2mvlllvhf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gt2qdziditv.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gt2vngbphqh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2uhjwjdww.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2eqxqqwuh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2wrtjitnj.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gt2gcbxpzex.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gt2jqepxykz.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ojtsjjty.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gt2hyjqaoau.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gt2aaaverwj.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gt2eirshzxs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2qgsqeztf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2bcqhklec.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gt2mjqbutvt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gt2adedmeza.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gt2uaepxjia.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gt2mjsnwvpd.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2oadixekm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gt2mehurhgd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qytmcadk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gt2egmukeqo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ojzyigrn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybjpdjzv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gt2utplatio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gt2rnmdympj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gt2ctjdtmdj.html


<!-- 参考信息 -->