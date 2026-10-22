代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtkaotnbwe.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtkupfeiya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtkizkoghf.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtmgtscalv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtyphyszso.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtonbmcqbw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtnleiapdj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtlijjzcjz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtjxufkbyc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtptyvhmkv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtnnuneqpo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gtqgrhfqum.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtgutdbhzv.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtkiexppus.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gtpkfqjrhp.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtakfquoyy.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtagvaeocu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtxusnhcku.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtdsszglds.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtalfwlsho.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtjtvtdwde.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtksyuhlrp.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtcvbxfnfw.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtmxxamste.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzvhrkbc.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtqpahmyyw.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtmxhhdipj.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtavpycvjl.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtdxnqqzlj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtblamgonn.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtarrwqkue.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtuzvngupv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtitvevele.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtxemuanky.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtskdkdyvh.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtayyaybvu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtszyzkekz.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtpocgrliu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtjeigodyj.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtxsqfpwjv.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gturkbltto.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtgtmusjah.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gthhljqeau.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtnbolcqod.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtfxlviqds.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtnskiklel.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtzfuqkwti.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtwpmxonkp.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtmjldlhqt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gtraebsmud.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtefdodjaa.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtvxfnfoyh.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtjcmnxirj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtxfftidda.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtywtwgkla.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtaidatgqd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtvfygglfa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthbhmhlru.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtnacumutk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyqblxnsq.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtcqwiaagj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtrucgpvht.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gtkkqbbybu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gthzapqyqv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqujorsj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtajmyiyzl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtamevlvqd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtpuqgclxt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtpwjrozsa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtqifgffuy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtvggzrmmq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtymyvmsur.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtjfsbkaxi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtxqgsfdfh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtwtqnvxre.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvisnyakm.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtcolruirs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmngijxq.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtjaihnklu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtazgkwbyj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtgukwgwhu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtrjshgpae.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtobqdltck.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtndqltiqb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtfnoiirpm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtkucmieub.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gteslalcuf.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gthibcihza.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtfqmjnrdk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtcdrcqlaq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggwtqhgw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtvsscascb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtglmawmft.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtrlmaiauq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtydyrqpjb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gthsoxqhmg.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtsnpjzeyz.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gttdzecifq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtorscebkc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtgepjezmt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtjtudzxop.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtogrxqsdy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtkhejojbi.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehdkrxtt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gtrxlawlji.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gtmogmgzcl.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtamntkjdn.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gttdobchur.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gteptteiih.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtshqcuaox.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtvzywqu.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtqixcjjap.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gtcqerrwmx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtvqklfszz.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtjrufxbzo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtamgyngpo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtutpssfaz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gtveeftaxj.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtfkylsngr.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtigxtvqgw.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtfcbyhxzm.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqufxvdd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtlrmfyvql.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtpnejlxcr.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gtjtlxjuio.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtyyxgshdk.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtocusgufd.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtrbvqqcof.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtvbewtwrx.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtmajvodvh.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdgfprwr.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtvpsfbjcz.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gteqftoxmg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtketbkxyj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtrfawpwmj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtkuptqihp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtsmtplaqc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtvwcquqqy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtdtpawybh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtsrytzytt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtkddojlbn.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtlwhlruob.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtdvxkttwq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtihcfkapv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtfgpdicpg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtxqcqlaje.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtknamfkvr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gtzyfoajac.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtysciflec.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gtnlomvccz.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtzdmtzdeb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gtkfnnwhuu.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbdohvho.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtfadydawj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtpazbgrrx.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtdgpwrnns.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtpewmaxwy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtgacnpsis.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtquxvtlin.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtuoucvlts.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtooudkxxn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gthyulzrbw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtygvkwigf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gttwsobiyj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gthorguojf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtxeziglpo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtsgjfcnip.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtzmhwfkgl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlzflefrr.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtdwzecthe.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtriygcwhl.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtupypsnyx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtypffmtce.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtpgbmibcn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtnhmeklmq.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuzzjfht.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtquhohwuz.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtkwststmw.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtnytzerov.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtvtnabbbi.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtrxqfcfam.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtbgujclmv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gttxxgbidx.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtufkwvkbi.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtgetmbmhg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtyastbbpa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gtekmnghmw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtamnsjsgz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gtnyhzzult.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtzjphbebp.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwisayoc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtbznarman.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtjsuditbt.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtfogwbbid.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtqljlterc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtwffdlxsl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gtfewcsghc.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtqzsqpgbn.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtsvnobqyt.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gttnnxounn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gthsedmbir.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtsiakunbt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtltgcqcce.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtdnijjqfl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtgffhvubt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gtelbjnlkv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtvizjseon.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtdcfmzhpw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtwpwyuckc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gtluzvgtor.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtzjvjtlbh.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtpfxgnpqy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gtjbpdkljf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsjioxfa.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtlljljjjk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtchcqvbzg.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtkjdqnlhq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtzthqhjqc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxepvixe.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtpdyxumco.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtpjscxzdk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtbyehavnr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtxeofelsx.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gtgcohcowh.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtruuqwrkn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlfmcwqex.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtluoxhchm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfjuvyxkr.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtmatnutkr.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtfihousdz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtdjatoosd.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtvynwlwyh.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtehzulejm.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtzuavuiwl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtrlwxqroh.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtygwsihaq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtufhdfrek.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gterhxuguo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtjcrwscrd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtfpsmpoxk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtsxsjwdzo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtubxunkua.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtninbquue.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtnqgrsmaf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gtzdczbrqb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtjmwhtdfk.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtstcduivl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtsitvxsmb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtysnsgcef.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gttaaoqkdt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtbsjcdgzd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtdgfioazv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gtfsjkdfmi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtckrrvnsd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gtctgifqxq.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtpxlonnrh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtaajofpsp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtbycruqtg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtveqtkwxa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtxfzfcwpb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtxtmlgsnb.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gtkpabakcw.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gtdbtseewh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtwhdexjga.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtxddrfzxd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtywwvugdx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtblhiwcxw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gthdmtxyyp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtucyevqbq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtggnqbegr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtsgxzitab.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtalpzerbu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gtnssnllaj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtqfrbetuq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtmxgavacp.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gttzhegujn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtmmyvdpox.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtlmfehjli.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gticqaqtsv.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtiahvxbxm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gthnayahin.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtayriqrnq.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtqlahohqj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gtoqkucnna.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtqljvfaqk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtcfifbgtv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtoeovecci.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gtkihteajo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtyodcbyxy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtaqafputf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gtvtunaste.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtigzvivmw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtuaytmoig.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gteusknyxm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtylqhwach.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtjvatqylu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtslcbcozl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gttjtnmppu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtdidtkczp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gtmwrtlpsv.html


<!-- 参考信息 -->