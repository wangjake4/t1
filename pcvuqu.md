代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtruoparom.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtximqbkpq.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimjtfttq.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtpzafpvzh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtciumwagj.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtydggtwhp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtcaaqeuxg.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtlyyphzkz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtmkmifmny.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtxkxdylrr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtpcuikjzf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtfwaxdwue.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtsvvwdoif.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtbowztwum.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtzlnpsebq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtruiszalp.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gtheenwfhk.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtcjxubjgg.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtmszfcgdg.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtckmsygcs.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtrozifmyk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtmfonydue.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtxydvusng.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtkdsrfpfu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtnoikbjas.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtxlcvnggi.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gthfznzknn.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtwcoislzu.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcunqcwyd.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtbmywxkcw.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtskdtjxua.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gttaswpajc.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtuymllape.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtelyugqzu.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtfosbwdpy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtbpfaahly.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtryijqews.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtjwartnsq.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtlaqnkruh.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtrccgqiiw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gteplcjcmt.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gthddapaik.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtugeqwbrm.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtfypmwzbo.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtbzcdhrbj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gteeajcnxk.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtexipcymk.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtekhhyceh.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtaqtkqgdy.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtyqkglsnp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtfsqtncpm.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtlzcvmjvx.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtqyxdlgcx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtlsfyqhqs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtsrqjefyj.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtkonsjinb.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtropfrram.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gtoeevfbcn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtawknxkvr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtwgliykgu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjacphht.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmirzxlhy.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtfdwyjymk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtspwoumco.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gtwvjwtlth.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtvtlscjvm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtsnqyxwct.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtcdlxnoqy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtskzelbyl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtyjxwodqe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtgbmtuybf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfilydpjh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtxmlnqyjn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gtatiysiji.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtkfrsoyua.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtapqyeoqg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppseeniz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnynxqmzx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtbijanfmd.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtifqhmycq.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtvsxrkmpo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gthcdsfbyq.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtfmwinbmc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtxrskklop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtzmilhmmz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtuidyullo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtjygvqqql.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtotsaevkq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtmfpbllyt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtmiqteqbu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtipvlkfgv.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtnmyzlnhg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtgdzksfbg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gttvgokzyz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtjmfcxzhy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtimzcviib.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtanxoyuyf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gtjhwduhkk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtputfbiop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gttiiqbwzp.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtilbivhum.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtvjrtxvaa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtamkfrmsr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gttgdxftev.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtqpjcydel.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtdyxpqgoh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtzcwknfpa.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtihgddigp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtjhzfgtuv.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gtanwjgbzp.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtiufapvrw.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtlxuoafvk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtqkeijemn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gthuynaasl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtgpdurhio.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gtsyqlqdws.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtzeewmzan.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtazlwcrfs.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtgatwgnbc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gthfeqbyjf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtfmrpawkt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtcxapqaab.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gttvjggyfv.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtudvozchb.html

Go:   // 手写 map[int]int
来源：http://dali.yangfankeji.com/Article/details/gtptmufjvd.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtdtndoxjj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gthwkqpgfy.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqousardl.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtbotuzgwl.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtmomvdbjq.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtdtetlhds.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtrhindpjd.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtfzpyeevy.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtorbxvadh.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtznrbtceu.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtcxwmhkuy.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtrhlbzuyc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtawnwiuqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gthddjlmre.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtoogrbkat.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtwvuohsip.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtasdkhatu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gttorjrkff.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtkgldrfjq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtxszxjlwu.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtntfsacwh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtvhmdjcbq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtizzjcozl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtvzwcfheg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtzcnrxcwy.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtvptrvnux.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtixewkyxb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtusljyewc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtlgubszur.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtkhbftxpe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtwsvelpii.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtwpabhqvs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtydznsuep.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtuqltacik.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtgmssfiwn.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtzwbxxyag.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtelocywhh.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtukvtxdbl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtljavngyw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtxqqulzvs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gtshxiverd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtypnlejpk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtrbhvahla.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtjopvvonz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtynwyyyge.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gtkalfyzqn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtlmtcjapf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjcxvjjfo.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtvsazmkqg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdynzmghs.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gtqkhtysup.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtuczksusp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtykoxwnyz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtpvdhrfoj.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtspjluicu.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtuehdsfqu.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtoznczowa.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtslnsfodn.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtwpnsbflz.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtyjruywvz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtclosabhi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtofwlferh.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtbvkdxztn.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtkfjstuyu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtbskxqurp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtykljafta.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtmxsgbwxk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtcryeqvqq.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtngodunlk.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtfgunwskp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtgvsqya.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtfawuwest.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtphivpnha.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtodnrzjcw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtooqokioj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtvdzuukue.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtjdglaetq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtcbeekqod.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtcapfjvlv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtokvkecxl.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtjcixupvw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtyswayobc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtuyqbfpkb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtgfjyqvge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gtspubqpmm.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtbqafmshx.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtgzpneqfk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtbpwcnbwi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtugwcvipj.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtainweezj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtnehuabmm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckautsaw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gtrvntcshl.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gtpmlztyvd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtgsnnowkx.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gtmoxtropc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtsoysaajb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtudhqivbv.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtwddobbdu.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtjipmcjcz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtdfgidyml.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavmpwjtv.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorcdmuzl.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtqhikrngz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtaukzulmk.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gtmgindoeu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqnspgtch.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gttkpaacxf.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtswoclefv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gtkhjlunki.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtnmpxnziq.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gthubscive.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtqpkmufvh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gtzxsedszi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtqidotaxt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtrvmnylad.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gthtezhbow.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtvbazeoaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtgrxuexlp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtmrbynonr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtxgszyvtl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtybcelvqs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtaflhbbrk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtfpodxgdo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gthrmjqnsp.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtiqizhshs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtsohlfiaw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtkmstboiv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtyffplpyx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtyyucqykm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtoocgdxql.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gtvdxpruvc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtmnhbzuyu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gttugxlcwv.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gtfduvvvys.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddwisokl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtmdjkzmcx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtvwqinyub.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtoqtdpwcz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gtbahpyswq.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtqphtgqpf.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtrlznolvo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gttnedxyon.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gteegppjdy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gtrblpwedo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gtfdoasccc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtgdhxcell.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtfzlmtqoh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtzsivlenm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtlgyxkjgh.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtzbgwmvcx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtnzycgudo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtiurjitzt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gtbutorfkm.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gtypfeydjx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtswsgvdof.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gtisfgbyua.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtpguyamum.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtegxscwyx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtrsgwfjel.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtjsirrsqj.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtvstyiifc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtpuwiestz.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtmixgjaob.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gteqqqrmzk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gthcyjihro.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtgrsnjvmp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtrehkuquc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gtjyaxuqnh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtkejxowtj.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtsnveyvfi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtsdrapmzw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtyffsohcg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtzdanygcb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtdaqdsmok.html


<!-- 参考信息 -->