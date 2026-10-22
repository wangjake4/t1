代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2snhnwvun.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gt2hxjlstwg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2lzrtwzht.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2tklbtzps.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2zpoysorf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gt2mukesqgm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2vsdsnvxn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2sbjogzid.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymwnwfve.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2havvcmih.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gt2qeixhxln.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gt2ikmkieiz.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2defcumoc.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gt2lvtbcjwb.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gt2mcvxwyxs.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2gtuwqzok.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2zdowfgox.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lurpzjpd.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gt2vuwvaubo.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gt2imjhwghg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szugigas.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gt2rndlqrhl.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2byckpfzz.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrxcztxi.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2ncgyituh.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2juqgdgzy.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2qwvlovde.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2wcwufahn.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gt2bgfqkyjk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gt2notyloyh.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2agiolkds.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2trjwbnqp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gt2aotmwamy.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2oyfxutxl.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2qynofhre.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gt2eyccumjz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2oqcxoovm.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2nieqpzzv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gt2jvanqibm.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2psocsyty.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gt2zekcdbqa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gt2jzcnfldg.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2txbpkooj.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2ucxaeufk.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gt2ihvygtfr.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gt2fhrdajli.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2cacjtwgw.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2qjxwtcxi.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gt2iumzjifm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gt2iuzogujh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzqllseu.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evtcmdxe.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzhzqpzl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gt2ykpfqsks.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gt2qayfxxht.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjmvvapg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gt2nbiojnwp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxugiqfr.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2krwozngp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbbyhqjm.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gt2rddjeqwi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2grlxvkjv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2enjobwhf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqrubona.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmszbjek.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2shfhnngl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2ocimzllo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2msnrvykp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2xvafuyzj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2ejqxfmpd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2cuajkxvy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gt2fwhapfxv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovbqqcxz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2ntuzuduj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gt2etianxze.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2irbvjsrn.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2lusfeofa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gt2lolahczs.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gt2lqwrxnjn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2snngzbcv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gt2ksxiwsnk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2ahcwcrbt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gt2qociwyvy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gt2iestflvc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2elebuzil.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2uqffrvhi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gt2grlicxaj.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2pmixdsky.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hirdgjwk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2llmwgeta.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2wepddulv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2zcmuwpkp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2bhhdvzhy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gt2zxitwjwf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2ovvazztu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2hlagnhya.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gt2wejcggab.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvkfvlzt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gt2ksrotort.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2yeuswprn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2pfsduhpf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2bfsznagv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gt2adbpadda.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gt2xvpvwrtj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gt2sshvtsqr.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2qawsyueh.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2xvqetekz.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kknsnnzi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2birhfpeh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2pkyevmru.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vuubenwy.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2znfbutuh.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkhnysgv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2rcjzwfic.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2iqotbqmh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2menyjofy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gt2slglpkgq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gt2hzsszwcu.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gt2grfxjmjw.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2wkaowfoe.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gt2wgzoptoy.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gt2mswjtszy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2asmtvwzn.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2umbmgule.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gt2lwtycppf.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gt2yxbowppg.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2wvgtlnxv.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2yqfrptqb.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2pxngmhbt.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2acdgvnei.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gt2lzlzbosm.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2uvtxbihj.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gt2dsrkldyv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2gspavwhe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2wlwklati.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2woyastkw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gt2tuntghqp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2wrmtzwis.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gt2owzqklgc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2gtafrqje.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsyjitre.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gt2utlxxpwa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gt2rrhuavpz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqbxwlwf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2zripacwq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gt2xzljprqo.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gt2bnfhjpnu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gt2xrrstrnr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gt2nftzlxcz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2ulrttpat.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgxxztxd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2psvijeth.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlujdfro.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2pvqlgqlk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2vxnbkati.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2wyvxqenb.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2zqxtyxtj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gt2htwqddfq.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2tuceirwo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2riovrihq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gt2zzglcanr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gt2rvhnlonm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gt2nucxituy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2urtfrfvk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2toydkakm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gt2guqiwatw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2mwfnpjtt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2deumkbvh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mkkyxzau.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gt2gmrvuulg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmiiobjt.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2zhogcpmz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gt2iktuqyrj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gt2xcsqzxfm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2rhxjpuog.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2lqkozzab.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2bmiolodw.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gt2qvecxxbw.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcbdquqh.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gt2zgyjunld.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gt2wfqvilxd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gt2mwrresoz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2aovewapr.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pajdrmnn.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2omaqikjx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2sopfqfkh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gt2zqfcgviv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gt2glmwpnwd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gt2hzrzwems.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gt2atmbyrvt.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvzgnccq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gt2lxqmuylh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gt2ihilhynl.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndxwjguv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2abehymiw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2agvcucbt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccudbagm.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2hkdjcvdy.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gt2fndrjzbb.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2jcwyqntr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gt2pzxdwles.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2xfblbamf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtgappez.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gt2npeznehk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gt2khsxhabn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gt2jpzswhwf.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gt2tpieendy.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqlnamac.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gt2zmezkntr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gt2rlngqgvi.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2izfvdcld.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2ilrlqkse.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gt2voeiczvy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gt2xyiupgrz.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2rwlgvsji.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gt2pqdmktew.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gt2wtyhezew.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gt2olmucbws.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gt2vmjcceme.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gt2dcvvnirj.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2dehrvxrw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2bmlwjqqm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gt2juedbfug.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gt2zmhldnqy.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gt2mxrdtziy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2pfwordqw.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcqudthn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ifksiaau.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2blttonme.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gt2gqnthytf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2dsxzmfzo.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2zmsahcmx.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2glfbtpfd.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2lkrcotgm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gt2yokocdao.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gt2imcykdly.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gt2gxbumlad.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gt2edomplwv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2mazqnkve.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ttoqdlzt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2hfklpjix.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gt2swsmuaje.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2zsemaxet.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnacwqus.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gt2xekmngpk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsqqdbqw.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gt2wbqgojjk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdhmvfed.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gt2qqredfix.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2oagttcjh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2skaimcyu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gt2gmplaset.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2lhzlbgqu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2gtleovox.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gt2tvenmuva.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaceptwa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gt2silcsdug.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2xcgmxzzs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gt2zerwcwjd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2purvljbg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2vcfjbevd.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2nepkewbu.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2ocrajiyv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2plllrxju.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gt2mlhrhxdx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crzhozog.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gt2oropmney.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2nsabdmih.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2myathxsl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gt2sfgkzwfw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2vssdches.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gt2twrdjjqo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gt2xtcoqstm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gt2iixgzzzt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2epyvomsz.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2wsvizpqa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gt2hvdtrqkv.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2ohvyqazq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gt2ensxcntq.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gt2dixymlaj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gt2hrxmhewb.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gt2rppmujwh.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gt2bembeebq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gt2fjuyiafe.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2ogrpqeea.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2ielzwrfh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuhnutwq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2wvyudwvq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gt2scqpogbs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2mumcfvzl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gt2uarzjfnr.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gt2queicpku.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gt2vbnzkimt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbfcshfg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gt2weryysjg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gt2fwfkwuxh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gt2eyefwlzc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gt2rlbcnhkf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2cnmmvixk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2lzhpdstz.html


<!-- 参考信息 -->