代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2lsauwxbr.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2tbqzjcng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlfrikpm.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2vvkzeikj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gt2gnrbxgzh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gt2eefqnggm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2egjqrfze.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2lwnrsuts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2kmrafdax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxfuoexe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2wftsuijd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjberfsm.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2vftulihv.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gt2faqhuwog.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gt2fgeezzkn.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2cbvbihoc.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvbqbmlf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijikgyzx.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gt2siomgbke.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gt2okfvbeqt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gt2dajywsxz.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gt2dhzhpeni.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2hixkappx.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2gxyvercc.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2zvbbugrd.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2pqjecdlc.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2xcbmhles.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2shrbpjzy.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2picjrntq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2huiyxicq.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gt2rxzgjspz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxfltvat.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2owwngepx.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2rtlrkjvi.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2sucfkopa.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gt2emzgszpd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmmtsqql.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gt2jjvvaaym.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2swuypeby.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gt2cndxtpok.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gt2ohxzbeny.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gt2allxnqio.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwnlvhqc.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2gitgkvea.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gt2cskupaol.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gt2qboqvhwo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2kvoxnbdx.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2aiogvctr.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gt2znpfolxg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huakxajx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gt2yuzizuiq.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2yuobywsu.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2asqxjkcw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2qxfszuyw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2cvmlwlua.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gt2qhkegglf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sufxvd.cn/Article/details/gt2ewhyhobt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pjmcdood.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2uesvcirr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gsinxybo.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdildbjs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwzsqcds.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2jmqkdyar.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2ubmbkdcu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2vmewtkto.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2hpnrkwxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2hcanzoen.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gt2vmrtkzzi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2iyojgdgj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2apsrmdzz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2sgzcueef.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpkrhilp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2xilakpxi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2oqoesyyy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gt2poivbfbi.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gt2bdxhiekl.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2cpoxirvl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gt2zmitrkyt.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2iofmlfay.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gt2husbtjdr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gt2xrnxdbpk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqlixjpk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fojfgzix.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gt2cqomwpwh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gt2yyantgzg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gt2wctfehzs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2fbwqwabn.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gt2eviwnwlc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2nxfcsvap.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2ujvhnnqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2dmibjqvg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jktyadmq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gt2qjpsqpyd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2tqfbylal.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gt2alehzyud.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2judjjqcx.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gt2yqzjpchh.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2qrmnbdly.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gt2ybatsvfh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2jghzrgwy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2cgrunzer.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2qiwnhhgg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gt2pwxneccj.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2vvgjrvnv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gt2ouwgvwea.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2ixnzzjcg.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2jxiudyrq.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2rgoljfmv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjtvetcw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfkalrsp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gt2xigejcnw.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2lmmotbbs.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2veimykfb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2zusooxmf.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxjldcbk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2ecwepbxv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqntlxbr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gt2awtuuocl.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gt2xfxbpqhg.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gt2hefwzwhh.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gt2lvtfnfdj.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gt2mzjzzgxf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gt2ejhycwlv.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gt2ygcblooh.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gt2rraifjrj.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmlbkcba.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjhthygs.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2ewykvcsy.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2cszuvgag.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2lkoxaawc.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gt2ssxkfznl.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2kolhadiw.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2icrkdlwr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gt2ladefomt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2kuwdolkp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2igwrvyzf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gt2vfcvkokc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2muxerqjx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gt2cfshvida.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2tsrjphzi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gt2twrdpnif.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gt2piblghha.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gt2cxdejuas.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytdkqwkr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2rsfjjlvk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gt2mcyqkpsu.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uoiwwkop.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gt2nkoblktf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sejevmqg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gt2hgrsfdyv.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gt2anvqwhaf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2xpibwjle.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2tidfpggo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2ofzijiqm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2hipqtmxv.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2kxcdidjw.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2qcysdcsh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gt2rmurzqet.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2upxobwiv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2anarsylw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whbbwzfl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2twbvtuyf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2ppiowtvb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2hsrafjhi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2eugjbctd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gt2dxsdafgu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjoydpcb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsoxfzsh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nzrrmtkh.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gt2kpaswijp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pyjjykuq.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssadxctr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gt2xcpxqzgn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqhokxhj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gt2lyylydqy.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2igqepkho.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gt2haebtqmx.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gt2vygbjbpg.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgbbsaon.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2jjbwzkch.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gt2knkvvolq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gt2cbjahcqh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gt2ovnsavsi.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2rcxjvmjm.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2zshdodfy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnsplrac.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gt2htiywuio.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gt2qunxjxte.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2luhdmquf.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2tdphntiq.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gt2fommurcy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gt2guvqcnhq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gt2pjxqkmrg.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2rgkypfjd.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2bdkktswm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gt2ydvgxsmx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcremdxi.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btygehvr.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gt2bymigiwk.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2kwkuenrs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2hllhdpbp.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2dfqhjpeu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2mkgmhulb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsuhfzuw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gt2tummwnqd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gt2gqwsbbbd.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdkqgcvj.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gt2bacragsp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdkgqhzn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gt2wlproshi.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2csebixzb.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2ixparbgl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gt2lolwynpr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gt2apbbqghi.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2avhnbdwq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gt2ezammsea.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gt2yqdkbdxv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sowrolxd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blibzpac.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2dftytuwa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2nmpbdphq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkatunhw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gt2lxcykihu.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gt2frzsrafj.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2nujjftbg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tfdvepwf.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gt2aljqunwu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2joquuqsp.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxnfmkxz.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gt2ntncobax.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gt2sbtwkxcu.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2wapekqxy.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2ipeiyfdy.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2llzciynz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2daciqmph.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gt2dtchpcqq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gt2htyszmcw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gt2eajduwhi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gt2fafvmfho.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gt2fzextdee.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2ukdrrjgj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gt2kkfcjodd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2fvkmpfmb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gt2isdyolnq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gt2rmvswvqe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbmoshtj.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gt2zmuzgiww.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gt2mogypast.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gt2kwgbjzbi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2fesyxlwq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2aoktuwug.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gt2urubvtrw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2wyufplpx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gt2pmpbbuib.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gt2mvmkjzlq.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gt2fyuiajfb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2jbgbidbx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2nzrzglrz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2ubzwqeco.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2xvprpzyc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2ptokspep.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gt2wyqinqbi.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gt2dgobcyjy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2athwksqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2bmylwtlk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gt2flacxeju.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2imyxtnnt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2eqznwzev.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gt2cvhevdys.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2hlqbgbnf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuymwuw.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gt2ztvvcvgn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pumrdprk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gt2piksskti.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gt2lpnyfgrp.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gt2vluyyrhv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gt2jciouimc.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zbcpjbeu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2omhuupgz.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gt2hmfhgbpm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2xvcfgkys.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2yfbyuoef.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gt2ahlvfjrn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gt2nxzqkyed.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gt2jkimprgk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2inwbsoim.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwkpkhpd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gt2gdnzykji.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gt2gefjsrpc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gt2grtcmgmo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gt2lrzefslf.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2nmxsqdtd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gt2adlkadaw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2xvtrcarx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2gibqktvm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2wnhpfdww.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bypzulvf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gt2fkvfydkx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gt2ofooosbv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gt2azhiexbl.html


<!-- 参考信息 -->