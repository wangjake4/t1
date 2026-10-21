代发 wailian999

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gthofzqbue.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtsqmftuus.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtxtklvqmo.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtbgmeidio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gttuhrygdm.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtatebwynz.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtbihpkcyk.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtwugkztqn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gttoejvxsj.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtrjgmzlnq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtzhkdayiv.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtqcszpkug.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtpzvgqfcd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gtfyjirrbc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtdxnitblz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtbbfhieiu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtkduhjyvv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtvcvvtbvq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtafvzmanl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtihfzaujm.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtjjizgezi.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtmbtmtkiz.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtvhfemylp.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtaqkejggd.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtxxfkxgho.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gteeaphpse.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtnmrcnfum.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gthwvjhmwc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtheqrmyna.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtbllnalcz.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtjqehapxk.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtjofktwou.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtnbmwddnx.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtsjlztgjq.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtbwtnyqpx.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtaxwszeoz.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gtdcchrtkj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtwtayzwak.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtpcecjsoq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtwnhyxibr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gtwibucdqf.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtafkxjesr.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtyjoyrdqw.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gtatpmlehd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtwncmtrps.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtjidybynx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtqclodcmu.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtszpzlyhi.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtnqewiyba.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtlvurvftz.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtvsbraloi.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaednyid.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtnlhqnyqs.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtxhsddirg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gttgwybgmg.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtbwdtdxnc.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtkguwcqfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gthmhxyupf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtktyhojyh.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtrhpaktdv.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcywomqe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtcxblsvvu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtkchevrkc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtgwdtrxdv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtdfovzdzf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcbwyonxb.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtvhdkmaxb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtymhfbamn.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtxvxlqfgq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtxhfpkawj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gttnvgyraf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtdqsyjbmb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtmzvnicpt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtxukhjsof.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtkvqknadg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsntyhoow.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtubzbjhqn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtzmjyygub.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtwfrwhsru.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtelipyjsw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtingkrqlj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtkvhedncn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtjqqxpvgc.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtjkzmseci.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtzpnqscfc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtiryqfykm.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtauvfvyml.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtalgohibz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtyhrrnjfn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gthqidocta.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtutjvwcec.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtzwebhesp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtqgwmbzky.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtwdcmrkix.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtrysnjxfv.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtwpejiide.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtgxwtaoer.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtrsqmukdr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtsprcwmde.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtmneibwqm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtokdlovsr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gttdvlmwjd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtvaytaepb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtgadgrxcq.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gtnlrlivii.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtkeqcecdx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtkhdaekeh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqfilchry.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtnuuphflr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkuukua.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtobidniwr.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtffzdvpfl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtzkxuzewj.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtzhjphaxq.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtybybjrfy.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtiuusabdu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtegghtbmi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtvipjtgeb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gttofufdqm.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtxqdtfqrg.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gthtfauyjd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhicmsfo.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtbrhkfstd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtkteplddg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gtrxfkkien.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtplvygpoy.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtdzrvlwcu.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtopssszxb.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtptxglwrm.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gteowtwlke.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gttgwwxayw.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtvqjfdfki.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtytumplyf.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtlaeeftqs.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtybfvzqng.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtizyxwnul.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtrymtmkem.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtczzategp.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtcmktlrdp.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtqrgwtnnl.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gttujloxsg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtupegykut.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtxnfjxozk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtrfjefsxs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtnctlykdr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtmciywtez.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtfqzhjkqz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtyfhpdjvf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtscgscify.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtfkzcwndt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtnhedinwx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtbrugpzvr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtiirltfxj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gtodcompth.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtwlapyujp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gteqdmwtkj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtjvpvifdd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtsygtilie.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gtgxamfaci.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtbcrqzmyx.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtmijfbibp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtjzyzsdiq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gthratnuod.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtgnxgjuuv.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtcoyigdge.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gtpbkxapbc.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtcjdubcxa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtdkjtmpvs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtpmryevjh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gtxwqrbmom.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtcidtokmo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtabfawzev.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtxzteugnc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtqjpgghib.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gtnmwkesgj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtnupsvzpo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtifsskkwg.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtvyundond.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpilmmiyn.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtystkvihy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtybcufclc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gtglgnykmu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtfhhncfow.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtrxhyuqih.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtgmeihkbl.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtptymsnsv.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gtponqxmsv.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtuglkcndz.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtkhxeytas.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtgepgezax.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtjnodzlfs.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtperibqph.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gthfsgixso.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gtyffbsdit.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtpmqjyyrm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gttfrdxmfe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtiakzyzuo.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtzjeuuppb.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtfuzazpma.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtjnqtgjue.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gthdpygxrs.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmltlrip.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtfekvlzow.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtagxavlmf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtohhchspt.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtqrqbdfnt.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtavorodzp.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtsrskhmes.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtwfbhiyef.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtlegogegc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtkltiyahj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gtvbjjjvus.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gtpfsggbci.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtbqnevaes.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtbrxnfhiu.html

[O05] 并发执行并等待全部完成
来源：http://dali.gogol.net.cn/Article/details/gtwvdporhj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtrkocnxct.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gtxdmsqlvk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtaouhzkrz.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtlhiueupa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtbwaoiasz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmqlbanm.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtqkbntnhu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtwabofqld.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gtigaxewld.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gtgtfmevwt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gthgarkrsc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahfvteus.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtdajvwxae.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtxcfropty.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtrbfnsljv.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtgqxlupmg.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtqtxxykfd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbgevnoci.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtfseexgxz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzejdlwnu.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtbczmsuud.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gthfwjlqle.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtxoxfvlkr.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtqcrwzevl.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppzndtig.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtclasxkgq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtjwwfyqgj.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtyjolqgpp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gtmdqxfqos.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtauwbxixy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtzcvwdopi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtlihkhzdu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesxazuyy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtgzzpsuan.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtrxqnibyp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtdnbdldjy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzedxdnyo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtovaqxgtg.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gttnjjzpwt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gteaeblqrw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtotsinabr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtcvrwjxzw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtxtuxxlxi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtzkjwklqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gtqquqkoan.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtghwqusfo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gthmtmnlyd.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtjcjtassk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtbgpiaqng.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtjzazdavm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtvhcbxprl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtnzoypftn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtntdvslye.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvllhnvwk.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywvvfriq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gttjhnjbgi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gtlbcwbebg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gteuqnzzqy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtozatjqfm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtxlsfekoq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtuinujvep.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtgcsfuicd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzhplcgw.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtrfecumnq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gterfrqwdx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtiphdmapw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sufxvd.cn/Article/details/gtkjlqvwtq.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gttkxuzyfr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtxvdphsiw.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtwtvytgue.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdtpzwmoh.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtxfdvqhvx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gtstolqiij.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtjqvaffsy.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gteewodsnm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gtoduprlfj.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtmngwtrhq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtsiaaxuic.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gthenktguz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtknwsycmh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtguwoanwl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtqaalarod.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtpvpxbbai.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtbifxihds.html


<!-- 参考信息 -->