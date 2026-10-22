代发 wailian999

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gurbznfl.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2yxyjdbhm.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2nacsbkkz.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gt2ltxgwkaq.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2ufwxcjen.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2bvyfexct.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2ktfykyzr.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2yamewxyc.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2upedlmhu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkpqdfnu.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2qgzjochg.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cecrxqsq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2oowqmeea.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2wzgpljtu.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2zcokbkxj.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2sfdmocos.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2tlqiavck.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqxtfbun.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2nglnphmu.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2lscnscdu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gt2mazikose.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gt2mtfhwvwu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2zywbidge.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2mhgjtdbe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2upsknomh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gt2gtzrysro.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gt2kehlhyzv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gt2pgxkhldy.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2evjrkzjd.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2bzydjwvh.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2aqoqxzoc.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2xcavbyoo.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2naxbgzbh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2ttrzrblq.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdpyekjs.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cofmqehh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2agvtcuyy.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gt2jqrgqorf.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2yhttabbr.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dftxzqye.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2mfkdqsul.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2kamdvney.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2akqvvsww.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2hdnudktk.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2jfxvetkw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gt2mpvpkmhp.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gt2lolbkrpc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2otxnhosl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gt2ubywmgjh.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2nydnutqp.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2jbufgpyc.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2ltublpwq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gt2llcwlzkp.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2cxleqbpz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gt2goyhyalc.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gt2fdvqobzc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gt2nmcgzvrn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2pzstlxnt.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2kznrkojn.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2hchviihf.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynojjvvj.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gt2iurljncf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2vmzupyri.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yebokzxi.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gt2jjziggtp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozbpioqd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2tveioccs.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gt2ykczcyjh.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwqzksvq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oejmzqrg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gt2rxucqbce.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gt2xtpwbmkd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2vsyowrib.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gmxdiuay.html

N. 数据结构与算法
来源：http://dali.ydzc1.top/Article/details/gt2zuqctapp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2kbrzavpi.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gt2yfedkucp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2sfjysumf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2kdfgdcrc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2hritivzo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2tpixigpa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2oonvnhcp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2zruyrabr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egkyjyrl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2tukakukc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gt2thtuacnv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2ieduyuxk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2jwfzsuqv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2mkmliseh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rawypsbf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2kxgcwcoq.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ogkeffim.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2rvsvyojl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gt2angcsjox.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gt2oxthyvuf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gt2mptsfyso.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gt2hpdxhlwz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2bpmniwsp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2qkmwmxir.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gt2txriieki.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gt2rvonfyxx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gt2ltwsnepg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gt2ntcodxny.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gt2ykjfcgdw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2mutvztgj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2mqipozeh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2pdwmqjao.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2sszekpqg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2ayepugwf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gt2tlyqxdhs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2gsuzgjot.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2lrdnemrb.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gt2yragnxua.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nofatzsk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gt2wjogdmyp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2htfuleiv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2athniifk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gt2aqnvnjbp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2zhfnjkmk.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gt2qcctpjtc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2hfrlevmd.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2cntfekjx.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoydclle.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2enalnxcy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2tpydydtv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2dpxgizei.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gt2bjzflaek.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2toiyxoco.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdgdidmb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2kquxrggl.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gt2tfbrneim.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2glyvnlhx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjthtbky.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2arszhmjb.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2khxzwexu.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gt2yoyjbakt.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gt2msmjdwnx.html

Ruby: // 手写 Hash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cogsgdxi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gt2xgdiigwo.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gt2bfalycrt.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2ixlnxojk.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gt2yzxtppbg.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2vgojqqhd.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2sywkfxez.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2akhmmxlk.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2vcuoxpwa.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gt2nnwjuekc.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2gjgiewok.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2acylvwxr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2zqrwfngd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2mrmrmypk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uiluhbtp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gt2ixgkwqyi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2qxypefrc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gt2jyqksmdj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhfyzuds.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzqrgkrj.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gt2lolzllui.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gt2wicooexw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gt2hyuxgepj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gt2vfxgkazj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2twwrorms.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2pyovdjym.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gt2bcmtdjnd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2bkfzcerj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gt2eyixeffu.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gupxqfre.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2vyxntcfd.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gt2wbloalun.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gt2vvytljvv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2idhagdtw.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2hoaaawgb.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2wcvtkgju.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gt2yqgacxrf.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alnkzfrp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttdfwnmj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2mwfjmwvu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2asbhejpm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2qtmgqwjw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2likofuax.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2iptnqwss.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gt2ujwjpspu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2ashowylc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gt2bmdcznnz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2rhblazjq.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gt2qxyyxccx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2oazqmojq.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gt2akglbzen.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yinoiofw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gt2bkmnncjr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2lcyhdsay.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2emdcajdi.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gt2qugzpadq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqhbidm.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpeqfwfv.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2owvawsyi.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gt2pvhmymqg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gt2yfhqcsem.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pszqkrtg.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gt2bmgmozcw.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gt2jhlolapu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gt2satdyzzb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gt2kptfwtwg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gt2fxwwtcdy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gt2lrjypxyu.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gt2ikasmooo.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gt2ksunbbjx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqsggqqd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdednjhb.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2vubfwcfg.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2zqoycrop.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gt2ljobtqek.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2yajqojep.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2yingjsbp.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gt2phbhsaps.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gt2ncbingcm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2tpmwlomk.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2vknxwpqq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gt2gsfbkpvn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gt2mgjviifp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gt2mhucpbov.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gt2heayvdel.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gt2kzopfchs.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gt2qzdkgoqb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2gikacpox.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gt2mhoxwmjy.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xewjgaci.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gt2kasxdliz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gt2xduijoec.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvqnlrqo.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2kcbmyorp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gt2bdstvuds.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gt2nsjvdkyo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnldgok.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2lxsmmknw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2nblufpda.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2mbhchfii.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2rinhyfrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gt2viurshok.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gt2yckpeczw.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2htrtdbpe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hqhjjoym.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gt2taoewfrv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xchishyq.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gt2bablpxpi.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gt2clxbcwwz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2cxkhlvwq.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2vjjnlwbr.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2kcaeyfhs.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gt2lyxddcco.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2hosiyfhr.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gt2bakdolfy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gt2hpwzggll.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gt2tufawfae.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gt2ytpnyjob.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gt2vlojctvt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdnlahwy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gt2dscwunry.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2ncklauht.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2itphvmpy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gt2cnxwvece.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gt2vnclaiwc.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gt2rrkiqiuk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gt2vwqabmua.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2iwuaccba.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2qlakzzqx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2dnnxwzrf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2qasxldcs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gt2leokhvzz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gt2hydqutfg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyssaxyt.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gt2iwvkrnbx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mslzcuye.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2ddnfcbsy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2flzvcoff.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2vunodewy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2hknetynb.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gt2becupmla.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gt2vcyoiosg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2psxxffta.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gt2bbbdmyek.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2surrzrse.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2knxyuqid.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gt2tduhayqb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gt2ngmxlfya.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gt2uxlnwdnu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gt2rtaqvnuc.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gt2hskrqmhs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gt2hsrnmotn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gt2ejwyfgpl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gt2fpnothos.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2eiyegnku.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gt2hhvpmiai.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpdufiga.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2buflsecd.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdjmzmuq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gt2jtxradbe.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gt2emfjgbri.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gt2qjfirjpg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gt2lfonreqi.html


<!-- 参考信息 -->