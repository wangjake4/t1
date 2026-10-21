代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtxmlyibmb.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtgjwgilag.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtkgoawnai.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtbordcmcu.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtbtijnbjp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtftzhnadm.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtyruymagj.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtbglofbrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtlsjuzdvz.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtbvhwjhbm.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtrnfuwaos.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtvignkzrw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtpbtzjavh.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtcfhvitbi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtouzwvmuv.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gthbigntrj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gtatkzrssr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtlntzcaxb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtpggegdft.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtgxotnbzv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtxioipljq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzdkwohk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gtwukkztyd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtgapwphgc.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gtegvvkxmh.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtvbbypckl.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtfhlsftrt.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtgswadojq.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtpxkxwmhc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtlifjuxji.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtrqxtmona.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtqhzcxwgu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtfuwhqnad.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtgzzftjer.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtyffgtpbh.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtxrwbuizz.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscfsmvoz.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtrfnkndge.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtaohiahgd.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpxleqyvu.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtrzetrvww.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gtgoaeocab.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtrcdjzbup.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtlscfcoyc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtezznylgf.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtxiuktxwa.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtnlsohfiu.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtacokcmus.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtbktmnxjy.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtvvtheftj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gtjaythran.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtiprlgewb.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtkjjfgabc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gttrtfybrv.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtlyfqtksi.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntzbmceo.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtulfdotfl.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtlczscfwt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtosqqhgur.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtkifswsah.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbkougyf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtsbnuknec.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtlykxxvhw.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtilxpbend.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtdlqgvxwd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtepuoctrm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gtuxfyeewp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtfpusstfy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtmljunnjj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuzyzztse.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtrdsqipxn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjlyfvdgx.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtiuuwqczj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtbafafzup.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagtzurcu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtzmvrbbvn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtwptalcqz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtngqpmbig.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtriubdkpj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtsosgohwi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtfthahxad.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtejcmvyle.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtwtbawpgd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtzflzjosy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtbxkffryx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gthjzrnspe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtqcjebyos.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtmmjknppu.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtakfhtrwq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtpbfaikxp.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtfwqlbdtw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtndiafool.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtkfcfqujk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gthtifyxdg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtvjufsgei.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtqebkiicv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtxpibuqua.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtkaklhxez.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtkvpzfrui.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtlvvcvhyb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gttxyrcljj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtgrcwbtsg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtvztulnhi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtvspqsqvj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtltnaswto.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtnkrqjqki.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtrzjikdlx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtxmdgpybq.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtfnagqmgc.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtpdyqmbel.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtieakespk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtqslwkdtf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtktbjcaxk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsodwzhq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtthweaqgy.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtrlcbxbux.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtbpobdcgj.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtbzazeaed.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtehgdorpe.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtwjpdhjyv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtzsjoryhj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtelftsilh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gtzfaldyir.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtlrxgqjwh.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtwcqhclzw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtcrfxpcqm.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtxoeslvch.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtpnqxwsby.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtxerqfaig.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtegyjpgxk.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtzmceefdu.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtflvdvwbv.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtnpjkqpap.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtrafmfcgi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtcnabdmil.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gtggeilqhq.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtqzmzwevt.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtunyuomel.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtuvgslyfp.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtffvghrfc.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtdoorxsoz.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtbzoseqyd.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjhkwyii.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtjubzeync.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtzzoifvtf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtxuvfkkey.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtwzcimmme.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtqzlwuanc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtegjxsinn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtzehodtxj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtouwjdbmf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtfzowhips.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gttocaaodg.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtjdytcaut.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gtagrffobc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtsjkqifya.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtvaewlwwq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtanwwjdxt.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtxvrcjwpk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtpmbjpwoq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtckaniehm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gtfwlpvvar.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtdpohnuzt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gtmcixgiyr.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtzytosiee.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtzfuqdyqz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtqgssasen.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gthjflqgpl.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtvvymkdva.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtrdyoghhd.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtdddivrkd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtmczxfowc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtzikjpekn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtbhzackcf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtpulxbxui.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtqetbhnwn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtdckanesi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtztyrpuga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtfunpzlah.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtxykzzyjt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtavuafqrj.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtsalhohrw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsenxnzvx.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtjharswes.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gtidblwwgz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtnxsfifdh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtuignlild.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtdqdpqkxu.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gtuhnwdwai.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtjyfwzzwl.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtutewstkv.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtjpbdvxcj.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtkjaefjdr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjhhotck.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gtfalvecoh.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtcsuxieib.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtqbmsdotf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gtkememgek.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtgkgmsufs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtcflwrasr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gtmyqtpinr.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtxmptqplm.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtjgzpnzwb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtrkafoukp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtrvyfowpr.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtwforbcvf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtmnovkjem.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtglcunflp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtuvzxrbgz.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtrqsdzerx.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtdcipapzp.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtdkqexxtx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtwrscklta.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtdwxumbdz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtrrkougdn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gthjlepegi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtonwxenhz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtecsbyctf.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtcnjyljwd.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtturbnmzu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtfkldefth.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtusqboetc.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtmunbydrz.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzoyjoxrw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtshpdxbeq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtuhlivdhr.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtjcgqtlzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtfvykfddz.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtqktxkrur.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtvzafisdj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gtmcdoskbq.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtrhewtahu.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtbsxjlecx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtbiwcgulb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gtgcsfkueu.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gthsnczwfd.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtpqmbdkdr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtaembjrqu.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtxjclrkmb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmfqgefww.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtrjxftgel.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gttledatun.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtfeefxrkv.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtfawcuqto.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtqymaajin.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtbtcckgxu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtawwdepsd.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtpfdquwsu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtohcgptwl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtjwxuaptn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtinzjqbgm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtmytfsvbu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtxmxnsofu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjugfqnum.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtvwretstq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gthygarmdx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtntydbzpf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gtqbhjsrtb.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gtpvudulzd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtbxnfazgf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtwscolbir.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtyjzfwxcv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtvkmqulwp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtelujnhks.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtjkpvqrti.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtlxhztzaa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtrufbqvqe.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gtcpxirvuu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxbcehct.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtyblmrhty.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtswqrugtt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtanbyghpm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtigybbjgs.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmizfzgc.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtunkwfymr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtoovkavhk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gtnpfkahoj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtqqpjlqdr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gtupxztnmh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtjyhifkma.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtzlxhzqnx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gtamcbgvkv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtrqmxopta.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtbeqvwytv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtmthvuqly.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gttbgehtfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtrshmidcr.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtjjamtdax.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtnhfuvilg.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtiqtbdkak.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtenklwdcv.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gttooqddws.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gteoccdbdg.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gttrwxfsmu.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtzjtmvlbw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gtozzrvzmz.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtaxxfdhwx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtmvjvpieb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtqpiyqzpk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtbtpjeqhy.html


<!-- 参考信息 -->