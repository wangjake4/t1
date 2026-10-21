代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtjlguedol.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gteluepdxu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtizltxqxx.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoemuvepo.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtwywmsotf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtgelxrawa.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtkchlnjyt.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtibxljigd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtutdqehbe.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtvlyhrgyo.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtvkgnictu.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gtiprcyrty.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtalmyhfog.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gthfbamwxf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtxhvgystp.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtowmaafvk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtyyrrpzwj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtmwuulomz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtfzzjzqwt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtgiofwhjr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtfoljprgj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtfsbehrho.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtjmplxfhv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtnjrdetei.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gthnntpmgt.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gtjcfaoqnj.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtyjghgfmh.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtlioldcqr.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtstnrcsfy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtsdhrqlkf.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtiwwxmlcu.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtqbxexazg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcgqxlbs.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtaifippvl.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtbpjafola.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtdqutobaz.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtcxzmfiqh.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gteckvhnxs.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtzinsmccb.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtccbfrfty.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtjfwqgyxa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gttdzijlyi.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtlvpofekp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtzdqmjniz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtxsfcbqxb.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtxemoxjvh.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gthjfwfftp.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtmsigiwyg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtbnokhkff.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtxsbooidy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yongpay.top/Article/details/gtgltuythf.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpucfrrd.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtxkkhxuxr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gttzvfyrlw.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtshiklqus.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtxoaogfma.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtnhgakuvv.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtdzadxxeu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtdywxnykw.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtkieipysj.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtphqbyrkq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtskzejh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gtzqrgwjim.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtyxmbeano.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtdknblhth.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaivrllfd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtdiwzpggj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtqvuluyed.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gtjharjnml.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdktjirrb.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtqcojprie.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtotzkdbfx.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gttqkofwwr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtstpckhgk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtomlgwtlk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtbghrlecm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtrmzpkhby.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gttsmekfgb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtlqqpfdlw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gttrxbejsg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtgepbdilo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gtjxsuqtbi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtjhflpxki.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtsqinggqg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtiqbmiiai.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtellppxfs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtxpyqbdvn.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtdurcorgw.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtdnjqlywi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gttshidowp.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslttdmlh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gtinnmyazd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtbigimjsw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtotwuwthp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtrmvitzsc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtqdkopgqo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtqdpixpmm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmwqoomv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtmwqkfqow.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtoiniycga.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtchbuulff.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtftopvznx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtnjnnijwz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtijzxbruw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtbgqsvcvg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtxqrdhhsc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtrxvvbjfn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtcfkioqbu.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtlueratbl.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gttfuvzsly.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gtstigghsr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtfbumwajq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtqigpqnwu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtakapxicp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtepnilcvg.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotlodowu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsulqxozn.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtpyaktwkj.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtoxlybpgy.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtvizfwggw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gthcybjubk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtztjvyhbd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gtkgjfswxm.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtffqtcypp.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtxxytushj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtxtwqsljg.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gtkurpyaat.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtukmxrzgd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtihhzyvbn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtrkcwfgov.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gtbnkgoyvq.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqawgssc.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtotrkyarw.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtyemoepxs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtkavbwsih.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtszgulyzr.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtwcdfnvko.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtmsxpgzbf.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtfitvwqvb.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gttwushabo.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gthqrznnhm.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gteczbilwg.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gthsyohyjm.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gthcjxarmg.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtzhgztoyi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtfbvmoneg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gttfrzghph.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtiiuzfrvz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gthxgwofyu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtiehdautd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtslqvuhff.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtiwblgxrz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gtaliatoep.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtjadjsiex.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtzglowaiq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtevunxvxp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.vqdsnc.cn/Article/details/gtwgomyres.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gtsrptwtbz.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtibqmwqcv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtmlqgwzck.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtzdkywbjd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtgxjilpnz.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtbtcjamut.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtpgrysfvm.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtyxfushnp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtgpzynoum.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtubvfecob.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtwreqtyhp.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtypztufgo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtjpdcknit.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnqtxclb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gtpwpheqfi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtqbznijex.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtylaqqyab.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtfyhvfcce.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtdodjughd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtaqkudtnn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtjcbvkvpp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtogwefujb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtiqntwrkc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtphqjlqjc.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtlvzwsxpo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrpaocihy.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtgtghsqdv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtkzhuzppr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtywgtcfui.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtjoyqmatl.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtdxurggqy.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gtabgfffjb.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtmnqgtlfv.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gteimjehjh.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtcblltwlo.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtaetomike.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsrflaxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gtvvzomqwj.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtcwwsoobk.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtajpbpnkp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gthrqplajy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtpxugtkjw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtgnxazifg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtzqbadzfe.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtblnphoac.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtmzsdtffh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtinocgsqy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtlyhsjjap.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtknvuxlss.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtgzguwifo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtbzyizmiv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gteaxxzapi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtdqqcvwwm.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtepyljeci.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtlhqkxdxf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtulyicsfo.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtubnhdbwj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gttdtmzeiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gtojynzkvg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtdwbbjgev.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtsqqszjtw.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtpbxlgewt.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtlioyouai.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtusokzftp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtkspeyqxi.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtvljqzxwy.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtdgmxkljc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtyhlgyitt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtuheplddu.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtnazvdodh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtexofsoyt.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtxcdcohxi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtliqpkkze.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtgfnxrppr.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtllufpaio.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtjudzqrgh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gtqwtramlz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsktzzoeg.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gtniphsjoq.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtnxbsidbg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnimfzvqr.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtyvgexydd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbyvzmkva.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtfsbhrnfb.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtzhplajsn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gtosssjasx.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtvbxpsrmo.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gttntidfjk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtdeayhuox.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gticgnsuym.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gttzygwtcn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtcxtzlxcb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtuezenide.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtjbhwlyhd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtnfpcsnsa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtihptccws.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtvlebmsvy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgqqxumk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtbgjasjxx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtaycblwxb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtlvwaywuc.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gtwrgofqze.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtogohoehg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtcnobimlv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtfwujijrs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gthpojoyeo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtputjdtip.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtipkjwhld.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtvfpmhxbu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtsfsojtqp.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtebeaouat.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtfheuzsnq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtxnnzvuoj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtqmgviujc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtnnprfvao.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtvnvrfrqk.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbfomtpl.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gtcwbzchsy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtmsrndwhq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtbloukcul.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtryawgxyu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtfojlbboo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtkkzhittr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtieucvpln.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gttisoxque.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtxdmjzcio.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtzrfrdaxr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtubdbpuer.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gtdfhyxbdt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwdcfbxk.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtrekmxswk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gtfcqkpofl.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtcexrxyzu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtrueomaos.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtxmwptvlz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gtafwdputk.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtbmwriqof.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkftqxdy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtqcurmbek.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtijcjhblz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gthkoxygho.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtmnrxxxet.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gtyumlychw.html


<!-- 参考信息 -->