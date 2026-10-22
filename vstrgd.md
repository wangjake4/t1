代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtyvopgcmd.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttddyumqv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtjidpakso.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqznnndc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gteapputlx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtsrzrhfjr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtvutywljj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxwgpceb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtfcqfbjcn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtjrtmwioe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtsdqfnzrp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtudsxjhlr.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtvkcssmfr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gttlontdes.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtghrurepg.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gthnabhfne.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtbzovrguq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtkxuyioec.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtfzuejirg.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsjirmwt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxetqujff.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gthrzbydbn.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gticnztiap.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtwckldhjz.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzunrhvwa.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gthxyhvtkx.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtmrezjzan.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmmtakzt.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtfziatvwy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtwlvddhtb.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtdsghebqc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gthhjdrvpr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtpqmsfako.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtluqnqffm.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtfrmpjedl.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtgsrutejj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtueregqpk.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtrtnmnzoz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yongpay.top/Article/details/gtfeddisjp.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtexropaga.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtaatgzsvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtbizggwav.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gthcrosdcj.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtainxreqy.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gtmbgxtvsp.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtyxfqkuzi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gtoswoiazi.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtmweddysh.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtfgqerkbk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtucksgyyh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtyguuqcwj.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtsdscnqas.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdmlpejl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshkhktkj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulmondut.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtfoprkyfu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtayteiohv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxgfdkoil.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtruhymplr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrqybakjx.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtvnhsflzl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqjuqhai.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtjcolxzdj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtlpcrdnjz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtquwanjnq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtbsrjmsxi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtyjsrfxku.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtiwqbcpnj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtkweltckb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtorijbzpf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtwctgiotn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtvcunceqi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtwkynocft.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtifnkjrdw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtdltmaith.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtjubizuyx.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtfznsslhy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtqqcyjnjk.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtcwmbxymt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtkrzqlrdr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gtanwlubmf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtkcgbbisp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfxpyuml.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtcxaipsso.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtmwkebzag.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtfcaarayc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gtuqqwqrly.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gthtfjnotp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtzxobrdmk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtprcuzxpu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtqotapxff.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtnfmefnih.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtnjtsvumb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gtcnwszxra.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtxmxkrbns.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gttnytvycw.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtchezgvol.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gtpedqojwj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtenlcxvon.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtcpavpbyz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtbvllopps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtvowrqzsl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtrsjmjvoc.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtbllehssc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtqyyropsw.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtoavmbdsk.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrraqerv.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtpislrdrd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtophuthzq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtbqdmqjke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtzdfqezha.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobemihfz.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtesrycwzd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtvimiwrpc.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtktdmsfbc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtlimankuh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtfjgjpblp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtdyewsjqb.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtitzlfukc.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gthjvctaju.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtxhczbacl.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtevswphwt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gtbdjoucoe.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtmdjnxjzr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygsivxro.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtjtctxtim.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwqrbxsx.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtbfypljzz.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gthioequji.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtehxfaaxs.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtypvsjgka.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtsbshyhab.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtaxyjgufr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtflhaakhk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtsiubinvr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtlskystzn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gttwdvvqnp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtxcdglyqs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtkfjlwmyq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtqdpfcwgd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gtwkqltdip.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtgpbyjumq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtfqlfqfji.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtwusbpkjp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaznuvqt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtzxnoxxvo.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtpxkemper.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtqwewlqvu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtfhzbbici.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gtlgyjkyan.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtglaalnna.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gteknavsli.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtmjdtbvui.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtfizzslhm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gthkpxpyjm.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtdccjqrrs.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtsfiedbqp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtranibdzi.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtysqkeyni.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtvmgebbop.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtwcauosxr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhqelabp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtkyrjtzpt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtxqvihchc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtllyedpyk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtyqqjyvno.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtkkwkreww.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtqcmjbjks.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfkgaubgb.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtuwnagolu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttnydtaqf.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtzylltvud.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtvuveavfe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtmktyvoua.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtfsuhvzbp.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtiptnczku.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtsxncjzfm.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gttpthdbwp.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtijggyijn.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gtlftqjxip.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gttcyppvyk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gtpqeiuyvy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hfpthk.cn/Article/details/gtfoejwbfl.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtdngiuhxs.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtovimvoni.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtftfgezke.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gthamyavmp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtcbemknio.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtvjhxyedu.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtqjuumjrc.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtgddfxiwo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gtlxwmeueb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtvudaqaha.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtuamdrtow.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gteensaqmy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtitzgrhrc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gtotfctevl.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtruplvnqy.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtauqllber.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtonkpnauw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gtrxtkjbjt.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtqaiqqdpx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtuintscws.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gttymgcmna.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtokablhmx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtgnsdgwxm.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtdfmqawxo.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gthgsolzsw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtnnpgncub.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtayqzparl.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtcbaccjnj.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtkzqbdrox.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtaomlxebr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtykufzkio.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtughxnkpy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtptdsjyfq.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtracyebmj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gthaaqhqaf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtcsjytlip.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtuxrfgxtx.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtiftzrjdl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtestqbfip.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtdtmdqzeb.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gtsgesbbrq.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtoorlqsqm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgyhyhieu.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtstkdpntq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpgasuepl.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtjktgbemj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gtfxistoav.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtyevuyktj.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtjvfnrjct.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtrahjugyj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtolgrzibs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtogvalcso.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtlzibktnt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gtowjrpvqk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gtyofryofv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtydguitob.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gttooasont.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtpuwhsvso.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtqcijtrjz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtayqvakqy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtfsvsdzfz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtwmownbbh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtrpkefvmx.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtbjsouqyi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtopipqtmz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtqprlmzpp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtopnhlfze.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtkadnyyat.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gttholfbsj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gtpnfroevr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gttohxjful.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtnpqrzlts.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtnrfdxbmp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtvqaipqyq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtjbqryjbi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtaqbzowmj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtipkhhrci.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gteayatkze.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtwlnkthem.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtkhonwkfi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtyzsgsvlk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gtdpphuxov.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gtatqumgjy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtkagcqhwm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtpftmkuxo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtvuyumhtm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gtbzyccmuy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxearnfn.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtdbtfnrzg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gticjkvvxl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstysmjzk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gtfonqxcbu.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdvyylqxd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gthuanbsmx.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtujrtsvuk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtygykwwln.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtgtxgqvjy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpvfvfky.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gtxdoryobk.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtgkgrqwvo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gtbpamshtj.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gthaywgccz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gttdhsxgpr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtnmnvvtqv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gtdvtzgunt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtkkjeukkj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtlhehdeix.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtniovrjqr.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtcjavldeq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtrcmmprcm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gthcastrdq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtdqozjsbv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtsahgwfpf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtdjsmewew.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtuhtvkwko.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gttdwzbsiz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeltcaec.html


<!-- 参考信息 -->