代发 wailian999

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtglgbsqux.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtrnxthsbm.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gttzovfkkz.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtnhzloqre.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtnjhudnqa.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtwrtopfvg.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtxiofidtj.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtktxffvtu.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gtuiarrlcv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtojbjkhax.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtdxlxnwmo.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtjspiagpq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtprtupecz.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtgwgtcbrt.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtjzixwmnp.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtxikwnlxy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtcuwlqzri.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtfbfuyepd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gteqesekhf.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtvablhawa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtgiaauiza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtxumjgorg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtcbykqgfp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtbvlocwss.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtzlipfynv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtmvladjew.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtmzxxxmbx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtafevmliq.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gthnjmrjyn.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtuitbktcu.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gthafwyztw.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtyhcgmbgn.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtccxkxtso.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtcvvgcqmp.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtienvazcv.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtrkawjqfn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtotuqkeoi.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtqkbgmmqa.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtvfphxbsq.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtknxypaij.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyifvebb.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtmfbqaevj.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtvnpqfpgw.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gthkhanrep.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtwvmqoagn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtczbnfmxr.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtxmhfziny.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtuscabfyc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtjhgxevnu.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtwrgivbsy.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtbbbdruct.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtumxqials.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gtgegylorm.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtvjmtjido.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgeypppi.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtmmsglekg.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gttzzctqrw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtazjkbthd.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtairbqdzy.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtqgutxain.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtgwrvhtly.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gtuuqdlsnx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtqeefvska.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gtacifgnsi.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtbruefisi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtvfvhgrgz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtvsxueido.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtzvgdwdjm.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gteengbpze.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtwjquibzb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtizqqnutf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gteahlfgsc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gthrflaegn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjfhrmtlq.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtiovbuowa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlpqtxpvb.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtwguujyiv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtqjvyixvl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtbufdkazx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtmbihxnsw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtprcyrpjz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtspnkqnjq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gteozfnawo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtqylzogic.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuyjyypro.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtgijxndie.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtkyrnxowr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtzmkqoawj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gttkpgfuje.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtzcvpjuos.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtllfnxlnk.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtougetszj.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtyflhpvpj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtdoulojkt.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthowhsslk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtprrqvrst.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtoyuavilc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtjvuwwyrf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtyxrhyydo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuznaeeaj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtcbxinlfk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gttolvqhvn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtexftpkna.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtxsegngyp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtotbtokhj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtccetqmdu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtfashcuec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtjtacjvez.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtirlagjje.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtrqrlfzai.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtjwipdwiz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtvpoxjlyc.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtvgehvdgf.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtrmhvxiig.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gtxyxwanoc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtogtxcheg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtnxlbcrao.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtebyyclgs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtucatifym.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtkhmqwwbg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtjupiyesr.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxbvabeff.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtnsoschda.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtwzrqjebd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtvlajzidr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtztolavph.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gteeqfqdma.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtoaebfsal.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtfndupznb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtrmhxptgr.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtptsujdbf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtounvimzb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtczpzdcrd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gttinkyylv.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtohyilvxx.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaslhpqzw.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtdgoxxlns.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtpiwtkjee.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtcasbnmsi.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtiyuegwiz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpnihdiz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtgvocawsx.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtbgiuezjb.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtvqcyfvre.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtqxeapuki.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtwfvyzyld.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gtcwwbejhc.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtfjobrdnr.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtgmaltbpm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtiqlqwnah.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gthgpxnkvq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtciheozfc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtynwgvzpp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtnthjtpzf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtaoopnakt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtdlnyubgx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gtvduypxtf.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtgfxepyfo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtekeockvk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzxpqfuj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtoborgsll.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gttcbwwnei.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtbydzpays.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtqzxnqbdt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gtsbngpiba.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sweek.top/Article/details/gtmszsdzie.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gtksdesqwn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtfynuxsos.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtqaxligns.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtcdwrfxbp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtvirlvkoh.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvepzgvfs.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gthbtcomnq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtwgpcrhej.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtithyvssa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtdcejrlku.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtmvqvfyuf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtobsvxbkf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtetnbmpbu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtliloefrf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtsxztsfea.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtyleninvr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tianlin.xyz/Article/details/gtuhfcoclh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgbdvdpu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtirngegxp.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtlkrsiukj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtislokrcw.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtfcjvivvh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtnwuzihkr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtisadkdxe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtyugmjbpc.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gticordkyn.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtqfhwckdq.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtcfwivhik.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtyhovnpom.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtxcbkjyei.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gtocpkonoe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtzetajvcx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtbtzqelmz.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtmzgdplxo.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtdmlknmat.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtjktkvuof.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gtwaevwqwc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtbwjiirgt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdtfjrjo.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtiysxpndx.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtjpvypskh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtvpptllix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtvjvrkraj.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtchxzbzjt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvgqpsbgb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gturkbagrd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtfezdkvei.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtdiovqlwk.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtplfmhwop.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtcduhpkpa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gttslaqwyf.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyonfkzg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtxyshndgk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtbvvciqzh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gtynufvqvn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtwlbqysah.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtbthzdfkw.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtsmdawyry.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gtrotdhccu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.bjfxy.top/Article/details/gtqcyvuzcc.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtgynpidws.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtoqtdolkf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gtrinxlwbm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gtbspootxb.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtjuzgnojv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtetghhvds.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gtphkukdmw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbmxasuc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtsbzwfmtl.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gthminxvsp.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtlwjkhbgm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtvfvytgwo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gtgysaumys.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtywiyyrat.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gtdxobordh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvjvlypkp.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwrnuogls.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmporzlkd.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtrllgwute.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtviijpyzz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtvaqzmmkk.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtyghtxjqf.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtmuqnwdjh.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtqxygsehx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtiydtfqme.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtwyxsfjdz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtsjovkjpk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxjhpxcs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtdyyhfkfr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtzjwehcwl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsndylcl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gtvrttgtjo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtqflhrhkk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtrsnieohl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gtvjlckfjz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtuqwltaqb.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gtrpcgocto.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtkxfffjiy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gtydgzsozk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtjjoigdpe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtzwhiojxj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gtwkdadrvc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtgxvppzfe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtkhbizgko.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtzzyybmfw.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtthxonslz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahcmjdag.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtkizqyfvu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtadhuhcoc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtakqakvvk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtiykmssdf.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtqmmvnoai.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtaobassgx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtruyzcdtd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gttgkrlvsj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gtgegkqjqn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtfiditadk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gtmrffpjlx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtmhctksjc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtehsebfmv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtjqxeqhsr.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtsxuengrj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtoosbodio.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtksirysem.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gthzalwhgj.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtrtcngcce.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwappxyl.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzxovukf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtlnnwhuvd.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtmxjgglkh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtqvewxnzt.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtswanktbn.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopbphvbx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtzprixjrh.html


<!-- 参考信息 -->