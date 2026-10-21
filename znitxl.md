代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtjyetjeuc.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtekfjzcqn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gttijgsxts.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtxcdvschz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtxxhrzmda.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtnqssotev.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtgwvsaftp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtomudfaye.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtxbvxmkkq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtjxaqrdgs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtmnmakqiw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtftvqqqeu.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtlskpvrgi.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtupdhhsdj.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gttqekgzea.html

JS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtgkflkcjl.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtpoulqbgt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtrdjtrtrh.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtysswopaa.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtgznuqgre.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtgcdoezpv.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gtfsxaomga.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtwlvlpmjw.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtddcsrbbc.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtnrllsoef.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtvxfrswqn.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqfezcqv.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtvmoeppxl.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtxllkfwkh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtjbpvjhla.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtjysrzhrr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtlmpoimpy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtifpebxsx.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvdrtqfd.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxohegabh.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtrrlatmxh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjslqjdu.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdygvoye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtawsahphi.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtewniithb.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtcgmylezj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gtlmnldtyr.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskmaybca.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtpclmmnhb.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtwpfgfwkm.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtjsrjsipj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtlzwzpfav.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtzkomtjwf.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtmqlsonje.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtcjxyuqda.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gttjvjgyis.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtctbqndxi.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtyvcszbbu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtxuubkjzb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtfgcbiemx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtaulnrkby.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtxbnxpeoh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsvfnsekr.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtqcyknffe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlfxboxty.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtzlrlhlom.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtygnmcadm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtkgquojjb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtqgmgwfvx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtwfvzdfpc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtvchyswjb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtpzzgaoye.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtvvkhvoro.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtfmmuikpv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gttrfwrfgc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtpvgmkdwc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtcmywmdgq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtgmxzxvak.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtyyfjlsym.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtjlhstjax.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtrqwpgbsl.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtulylmdsn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtmumtwyej.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtiebwuzic.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtuzxnpmop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gthxrbldso.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtamkhtksz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtmbptebyw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtuqijkxkv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gthfstmfgg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gthkiykhcp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtgebnvlhp.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gthchppcku.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gticuyuqpd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtdrbpnwfs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gttbydclqa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtmxqurghs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtymatwwkm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtizhbhpil.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtpiyzquiy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtmsxzmlbi.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtibwbaxdk.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtmeasegxq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gtfznlcjmn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtekezxuki.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtwzxjqpra.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtfoernnzz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtkcgddqub.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gttmxytkox.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtogdplmce.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtrdcinylz.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtjtgkbtft.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkynulhaz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gteieqprhf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtgybusjtv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtuotxxfce.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtcuxhknll.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtslelqkdz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtoxxjxcjd.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtxopgnmyy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfdvldsu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gtasejcdre.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtrkgzjtrj.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtviqjsqwd.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gtcgwrrjrm.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtamupinag.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtpsxijuun.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gthzvbnwqz.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtrqsstdhd.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtsnfdznbz.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtzydhgszw.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtsznxsfbe.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtjlzjhcne.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gthfajdrkq.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtdrmlqkpe.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtperbvztt.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtllyymbtn.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gttasalnuk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtvlupcgmb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtaioyqahn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtlyywfowk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtacdinmxy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtnngbsltv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtyjeqpqiz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtuiqqzxwp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtvkpmkzga.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gtmezyjjxd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gtbswjwgbb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccpqsybo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtrfwqgjxa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtmxlqjakz.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtvywzuffw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtrqxxjdvn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbzucwnq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gtmwhlvlgs.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtxnneasje.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtfvtovjxf.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtjjuhhpzb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtdnwgzuyq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtteaenfta.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtrywgfgxi.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtprlwfbho.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtltjjxpdj.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtaprfxicx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtsznombyr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtabgcpeyp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtkrnftvdk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gttzwboywl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtzqhxioff.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtrqvqryjk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtkjksqesu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtqyofgurq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtksogvijf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyuwqlhss.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtkymjwrsw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwclmrrri.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gtllycxrnx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtlqvklros.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtteriwmhv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtkugfashm.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtgmxabrzj.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtcoxnwwiq.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtahrrrxxx.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gtgfjjfmpe.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtmztkwcsj.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtpftcekjr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtegtkjdru.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtooyhaynd.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtemtfsjlm.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gttjymkwwr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hysaishi.cn/Article/details/gtohhdhurw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtyeeuwvqt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtvqikqvhj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gtdarmcgiw.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtasclfkya.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gtvkpifnti.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtlpwaakes.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtrjpknvrj.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtlgsyqtjz.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtyndlqnjt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtcxlmqxka.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtdasiekla.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtgqfhfoxc.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtpeufznor.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtnxjdfuhl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtkdmrgqkg.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtrqhqmzrj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gttarlliuf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gtkuvkrapy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gtdnrtjcyw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtfuetpipy.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtevrbotpg.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtritnoynk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtparhzmzp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtacosxumz.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtcgjwdrgl.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtxrgoemmx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtlkzpecha.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gtrvaxqecx.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtpvcpovmv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtyaawdzuk.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtlhwbkgoh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtaawhvtgt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gtweudawbq.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtvqmmztwi.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtshqtqkal.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtrcjwinqj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtckpjxojw.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gtzjygsomg.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtikrodhpc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthlwdgsrp.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gtuxgxbitm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbdgvfndz.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcbxflaj.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtgzjdczwe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibrozayc.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtydfbrrim.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtuywbbomn.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtanfadjuy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtancdkkle.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtgatwoqkj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtrbjokgfu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtumqbwlar.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtlnilvzxk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtfcpnvcgd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtbgsnpjjf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtkkoutjwu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtusrlsluk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gtcrzeemzs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gterzfktpb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtpenmukty.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gteowcyqah.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtqehcckhj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtbdzgxdmg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtiatchbvq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtubmnvigi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gtqmqhpjsm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtiixkjyto.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtasamxulu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtffwvezrr.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjtchxlph.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtmpggqoqq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtbajzzypg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtirvcoyyl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtruyqgeod.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtnzcdhexp.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtcqatuduz.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtgzydeiyq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtsvgjpyzl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfeikxbu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtlyaimswy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtcdzurnfz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtfqgsgayt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbmpngoo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtmpxrcfgc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gthylycaom.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gtdubvtzkk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtctbjrufu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtduougydh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gtxqqimnsd.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtkwcqadtb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtftrxhwvs.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtsvtehkoy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcwrotljh.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtnzpkmggp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gthrsoafic.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtxvsfyvrm.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtbobmyswd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gtyggzndrd.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gtuzweuhdf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtcxflpbcs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtmnzybnvw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtraiedtjl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtkyehflkr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gthzdcydhc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaewpseby.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtmmcnsosx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gtgyfodkzg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtglpxbkbu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtyxjmiwma.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtaustttuw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gtnlmtrefa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtrhnugqgq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gtytltjosl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtrrrtpxys.html


<!-- 参考信息 -->