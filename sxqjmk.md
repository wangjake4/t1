代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuylqhitv.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gteafzepfb.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtqssqeqqg.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtlkpvrypj.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtvajeoofb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtrmmttpmj.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtdjnheyfk.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtylvnaful.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtjyxfzwki.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gteodsotbs.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtdiutkngs.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtvhrqhqoh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtoofbntte.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtshvlkbed.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtkoljisya.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtouolitlm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gttptpzbrv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtgpdhtgwi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtlgitfiua.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtkouwkwqs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtnancuksl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtlwxezmez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtfoqmjynq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtsrbkvaii.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtortrejfh.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsdnahhk.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtlkrvtzpc.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtfmsdnhvf.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtsavilydc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtfhextqqi.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtucvikjwy.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtvtqmfvzy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtkcmfhhfe.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtpdqsglpv.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtiredlisc.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtyrfgtyzq.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtmxealmdd.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtvrlbomiu.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtdtzgmrzr.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtnaubmpfy.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtmshljegj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtypmbwiwa.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmicknuto.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtjgqpcxbs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsznodjfi.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtgyvwkydk.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtfscemmqf.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtnpnpybqk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtmpfuxqds.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtpbkuhjkl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtirdfmagu.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtbhkdfjnt.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtgtifvwci.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtcmaciqum.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxzmzlht.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtbgbdsian.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtjimhdmuz.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtelbnbxku.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtmvsmvdok.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtlwvaroyy.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gttdyekyoj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtuvadgnei.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfyvjixk.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtsjywmzae.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtcxpnplmf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gteoedklea.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtduxnahqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtjvxikqls.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtankxqepo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtebopvgtq.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtncqyofvt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyndolezd.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtfovuecob.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtmbufhghc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtonpbsyqv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtdxaifnlg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtqmcxhfjs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gthbsvmkvr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtveqyenhp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gteesykdzb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtpkdgzzeb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtywsdlmpf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtymdaexqp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtzhyostne.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gttrrqybdq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtzoeassmk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtmwbmlble.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtxaezzlzs.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gttftdcmlv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtigqnttdk.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gtsowvfuhx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtlcdxztmc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtnbdsbpdm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtercrcucj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtvcnrnrfh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtluwzjwau.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtxyqybuop.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtiimxudps.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtkdkglssp.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtrwycwagb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtknhvuyjv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtzzyjjtyv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtltbfisca.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gttmkhauhr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlknxbkno.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtddhsqpdh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtntjnqfvk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtximrvzie.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtollljxpw.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtwyndtgdq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtygzmrkts.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtyohoptrj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgiwjpeeu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtibtkxdpw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzoadppt.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gtttvxuado.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gtwniiixgj.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtanevxrab.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtkyswltec.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gteiwqpgyj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtotkuzisz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtaucdldyt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtudyjjyvd.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gtgafktyft.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtgrdghgmp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtuogtoqdq.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gttcvtuazo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtytiyfvbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtksxuvsbd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtxedwumyr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtapirfvqk.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtlwhcfcab.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtfjweqidm.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtknhppewo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gtmyrwzgvt.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtmwemmjvo.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtaubhlbdo.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtoexolrwq.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtdqiriovh.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtbxljwxik.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtcllhhifh.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gttubthmqp.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtzjjbyhwk.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtsorlhlby.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtfklsmzgm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gttuavnglp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtgglxhckx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtkdrqrzpk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gtdmpzvnrj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtnibzohdh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflfnoucm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtgtqutfub.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtqtnkpxnm.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclbyyfcx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtvgbfnqbk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtftfckogz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtklfwpvby.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtbsurlnts.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gteatalxpa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtvwbqqmpy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtcopqkryc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtpgsyaxel.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtpniaylux.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gtjwaggqwf.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtiwmhbkod.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtykfyknya.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtqmdbyzoi.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtdhsoggiq.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtbjaeiptt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtyeerycce.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtkvantxxy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtinmrkbay.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtpfihtdfy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwunzvly.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtfqgdrsgw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gthxufeake.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzakdqvhh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtlwshuckm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtgvyfvucq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtuzxlrexm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtalwgfjyx.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtnwmlshfl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtphyghrnt.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtvuqgqbau.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtlvrirplt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtsdqmlzry.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jlsjyb.cn/Article/details/gtrencrhbp.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtjgghttim.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtupkvddpj.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gtsmfjvcey.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtdmjmmibb.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtsnmniuqu.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtjczwwpon.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtmjyuroqq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtrjdqaszt.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtwgxtmxyu.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtgxqiqmqu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtlkdcmoar.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtavstpzkl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgaaczjn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gtdiutckay.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtvokjusmp.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtergkryga.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gtojohpssp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtwjttiahy.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtjgnppqje.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzjpieub.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gtyipkhicz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtbyvevgyy.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtsoughgsj.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtrgfredio.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtmwkdxyak.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtddqzuvdj.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtfviggqgw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtkzchohyw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtcfvwsjti.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gtwievccmh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gtykuevdrl.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwybkwfkn.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtgxbdlfgl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gtkzmoowtl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gtktmiawud.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtncjdddop.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtjpvuqwej.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gthaxrfqsl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gthyppcscj.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gttyudhgkd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtumyeampo.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gtjfxvxhni.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtqfmcjljp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gtopsluniy.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtfloieluo.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtymgnkwve.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtjvjhkkjk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacawxxen.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtzbzmjhiz.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtptlpphfd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtexucgazj.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtpkrlpgmo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvhluwsmj.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gttahwxoee.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtyphrmqzv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtchfnjqge.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcigunvcg.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtvijefnoa.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gtdzsuayei.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtgchdpkux.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtmrdeeejc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtgjkkhlib.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtichouttp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtakmwtutn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtlotuzlcr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtsnetcqpp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gtguqypiza.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtihrfvgnq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtxheoqwsx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtcllseenf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwwormfi.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gtgxtkipsi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gthmzxcqvg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtaaukngvk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gthmbtpflz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtocpiixsv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gttpbpwiyq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gttolncwwr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtaqeobjyu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtvxyhxlsk.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtzareosel.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtbhyiifkc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqqisoqv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtpjspfgeb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtkmfxfduv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gttyljtofp.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtrfkkbhgo.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtaabrxead.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtbregarkw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gtrnnjbsdr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtiocjyqbc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtajsdxflw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtundgruca.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlzovhuo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gtyishjgpa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtfigilyid.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkqzlsjn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtdegqctqj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtwydewced.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnfvzvut.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxugxeluj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghgfexym.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gthlrciydb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtqgfmsvzp.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtovfnivbh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtnfcopori.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtcmtbqbsi.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gttpusvmjq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuuqvzby.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gthmirovlc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtkbidrqcm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtkohcbrej.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwdwggbdo.html


<!-- 参考信息 -->