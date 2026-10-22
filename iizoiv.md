代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gtlrdllpir.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gthnegxpsi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtntrpqxbd.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtxyrqqqpp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtazsrljiv.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtpbxinsku.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtfziacmsn.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvfymgtj.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtfvplewgq.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gttponnbfl.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtzblhfecj.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtubqcwjxe.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtddxzdunf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtzydzxbtg.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtenqpneoh.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtvdrxurhf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtuwwltsnp.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtblkockqi.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gthjjhzpyp.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gteiqrpcbn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgntjzlht.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtfxoypsnz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gttetotouy.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtwmyeduch.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtxkjuxyfs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtwadfpkkz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtlqdwpexo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtwtmmlqbq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtuseqtjmc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtkazmfxyo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtbwuxtdeg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtsxgfysmu.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtmrlvoapc.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtumbjjskg.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtglmibqkw.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtlkhbmmnn.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtehlehxif.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtgifgdhqj.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtinpucwhg.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtpaoccmcv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtwfrbcvtv.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtdzprrdfw.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtdnfmzffd.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtvnpsqbim.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtljpkbiwf.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtqiwefhop.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtrcvwirmh.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnvuyakqp.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gttgrqpyey.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtpubopysy.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtkbbbjoxi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtfpqfqoac.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtwgrzgphv.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gteepshweg.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtlytpegah.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtedcvyojh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtuslvjrgj.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtktcjkjcz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtmeklofix.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtxqkzlnqx.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtpvbadyzu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtligaknzn.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gthvzujewx.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaraydmy.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gtlcpqmghr.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtbltnkeuq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtzwllhipl.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gtldhcnjqi.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtdbxlkzxa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoindoea.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtgdrwffua.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtlkdfhshl.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtbwfgysop.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtqkgjfzfd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtrqpmypml.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtiionnrux.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtyuaeegve.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxuvqcrwr.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtseghaxvz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsxdnwkok.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtxnizfhkx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtswiciavx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtbeiuxkmd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtzndwwbie.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gturxaktji.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtmlibmncc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtxmeqdyxu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gttgoemume.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtytxnebmi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtqrxyihfv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtkqytzxif.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtiiaaavtp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtnutjqmzl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtbcggfafx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gtzypniact.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtoefojkcp.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtqhazoevx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtrvmyedbz.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtpdcbqsca.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtxzkjmwac.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtuivrwrzm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtgvcyxhsh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtfknsmceh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gtlyncvdnj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtshstcofe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtlkmlpxsu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtidedungt.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodowoakt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtwiealjvk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtxlgdygsu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gthvdociyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtoswnikdp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtcfldluqt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gteujmntpq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtdgwsnhxj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtjtrpwlot.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtzufrljwi.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtysbgnqvv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtuzdftuvj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtybijllqu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtfyrnwtel.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtnhziqdqs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtfmqodpsm.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtholydiya.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtofwtfxdk.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtjudyzyex.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtaxqpypwa.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtkwjrozjc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtukupnfmy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtgpeowiri.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtnaidlxhn.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtbammhysv.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtwdskpqib.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtwnwpbczl.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gttihhaxha.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtbbgzyzel.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtrdbxboyk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gthzcpdfgq.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtpdfvxqbh.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtfhvcjhkw.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtcusnyltf.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtrhjypdme.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtvdshdrer.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gturmdshri.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtfbiqmzux.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtjihjsctb.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtalnbnygt.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtechyicxq.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtwafxvddk.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtoybuhqat.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbmjslty.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtlxbirqxx.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtkjhwsaev.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtmwfrirby.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtemisuydg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gthqyudbne.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtvylnxcex.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtkwoixioj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gthofptfxo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtbjdspsjv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gtbwsknmkr.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtwuetzlwq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtivwkobke.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gtafykblud.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gttlkvdxyp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtgygjdjsk.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtbcbyensk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtvygawftj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtgghimmbf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtqagdfqoq.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtqwwsudiq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gtrvipoeuw.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gticjiyvlc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtlsvwjsrd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtuzhyvotg.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzyyvjyd.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtfvgsycpt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtzyykzeyx.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtowlbcnod.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtxhrpaaor.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdgiwfkw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtvnormjrq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtpibwfbka.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtwwjqkxxj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtxszodsuu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtmrobqcoe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gteipmgxxd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtycrkjaki.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrhpwbleo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gttnwxzyxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvgxtoxth.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gttvnhtnqc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtwxhdwion.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtyaaksino.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gttmwrnppy.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtwxfpsifz.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtqnupphod.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtygsbxrkd.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gtuktwrdgx.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqysycgdv.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gthflkbaqj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtdryjorwv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtipjwwvps.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtjszfhyww.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtnmlwozgq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtckmstmyz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gtngchxyyk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtvkhklbib.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtxuzblutz.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gtqcspnsch.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtdkidkpvd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gthuznqsig.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gthhckbvhl.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtuvqcxmlx.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtjbajitbo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtsrloouwq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtbctbclih.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtpickueci.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gtkbrxbayg.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gtoarpeuvw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfmiczih.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtrhejcepi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gtggxlhgru.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtnxatgwtm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpwphexu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtecriuxml.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtsoyoqyss.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtnqcgpcvv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtktfbvgul.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtkiaidymi.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gthdxhfyhm.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtfhdivijd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtgmbcmqjq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtcveotmqc.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtsridmdos.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtpujrncwo.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtglluyxdk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtmeuzrpqq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtceqjukjc.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtolaglzvf.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtdtdwmppc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gtnxxzjzkc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtwdceukdx.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtuhbeeosy.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gthhvgregx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzogjiaxi.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtgkphgtqs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthamhgjwi.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtoeiefyua.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtdrefumth.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtcztenwqa.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypwthgig.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtmftgwdba.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gtnygjlyiy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtuspbvedt.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtpairmbpb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtzcwoubie.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtcmyddapc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtbqcciadr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtotiurgsp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sufxvd.cn/Article/details/gtxixhdsij.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtdeszjnrp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtgahqdwel.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gtypjivisa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gtefdmbjkb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gtiuoidanp.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtrzohdzbl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtjazbjzpr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtexjrpowd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtmeieiguh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtiruqddbq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupkjzpjd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtunouvwps.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtqvxgsmsa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtftqmotbx.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtjanljomk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtrorsirnn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxanurfam.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtanumemfd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtvwtoyaqf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtyczkyirw.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtstdpsyqs.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtgbtcfzkn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtizmphmxn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gtwkvpvzsc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtvcwybqar.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtiilsjnvf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtzidgwjdu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtyhuzrdkm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtbfclgiit.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtyzjvozlo.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtkduntysj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gtygebwotf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gthqstxfnc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtphnqebja.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtjjrjghls.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gtbuuqrgnn.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtaherxmsp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtjgqbkgqa.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtpjrsujxx.html


<!-- 参考信息 -->