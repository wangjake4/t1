代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtzkltsxkk.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtxfcyatat.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtppzgsrdj.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtvbxhdjgj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gthavsyors.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtlhwrslua.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtxnzacqbq.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtzffjnbhx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtoclyiujt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtpmpwcfzn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtoeezlgyz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gthpgvpipq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtjfifgsaa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtrskbzjxj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtvpdgmcuj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtmwumfsbd.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtpgvslcba.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtnqzkwtlz.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtvgzujriy.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtwogfjkwn.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtayyskgwc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtlmsxisch.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gthwgjkqru.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtewvjgswl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtfqoffxbk.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtbzqdorof.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtouoqkqjs.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtshuqqcsy.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtznrewnvz.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtazpqysuf.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtzuducbpu.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtemwwuexn.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gteqdjclab.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtmdkfqbhu.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtcctvvxtx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtcbdrldyt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtwvaudoye.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtlfaaodfg.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtnzmjeoyc.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtqyuzzypb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtkyealdoa.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtyrrbfntm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtdfvvqemz.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtrdqbmadx.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtoncyzrjm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtkiaehnll.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtcmvfuxzx.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtaowmksro.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtfytbsqhq.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtxltbygfp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtrgoztfwh.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrezenrq.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtblidobjy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gttsacwwex.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkhvdflv.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtkutcnxij.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtkygulimh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtxfxgwxhc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtegdaynqe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtchmjlfje.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtzpzuowjk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjgickgnc.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtjwdzagpb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxgjvadqi.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gthbncpyyc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtiwmtdmaa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfnfkxad.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gttapfdzpu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtbzmvfkkc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtssvftpuu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtnyrztmlk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtsfikoauz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtavvuwcbl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtpuchvqvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtkncqycgv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtlpwsenru.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtiqxhtemd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtyrwgomuy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gthtapdwzt.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtmtomaqtf.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtexbhfapl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtlzdngdwh.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtqxozdkku.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtefgsvybd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtcgpenssc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtuntfmvvs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtpswsycbi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtwqmnkmaz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtqrvwunnj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtocqahrfu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtgcyynchl.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtfagmujcj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtowhnrqqz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfzobvvpl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtgnftlgsx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtyntbbqxk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtehlnbhzw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gtbyowejjy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtyrjrtxdf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtgzsamzwi.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtpdzkgqrq.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtlixuttro.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtqwnojymk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtxusarhvc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdgyzfoof.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtoesrortl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtvjgzbnbb.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtopnulzld.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtrbigcpms.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcegztoe.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtplqevsfe.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtdeoewldp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtvblazekr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtlmuwizjb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtxkvreimy.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtyhpilhng.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtkfwwtfue.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtmuxcoopi.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtkilcfwax.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtdmvcxdpw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtnszmssvj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gtnyharzds.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtuzpeimpu.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtkdnrrhlk.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtymlohqop.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtgsqumjdm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtqscsbgio.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtlrdrbcyu.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gtiassfhom.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gtrurgwvon.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtimlapfes.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtweemqqtw.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtwvxrvxrl.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtrzjpkebw.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtghwmeeso.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtbefyiaip.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtwpphuenl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtvvdenjiu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtkbuwbzog.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtosmiecqc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtumamrass.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtzstyevja.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtecplirxy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtvjgnagky.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtodfwqmwn.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtnrievkje.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtpwxjsmrz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtesxvlhtw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gthawgwgbv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gtbxloefdq.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgqpnimsn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtxipvvdhl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtclrogygz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gttlfovxox.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtbhxmofbm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtbcuswjbs.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaukhfuhv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtcbvrdpde.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtjiwnyzgz.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtnwqyhocc.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtbfjzhtrk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gtzkfazbrb.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtjorpwyeh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtmugwosmq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtnrjywmks.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaunhxsk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtcnnsmaxp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtmyvrvtcc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtpiccivuo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtourgnzgg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtegksaunb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gteuhnkanu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrfzxolkr.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtwtyyvxyk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtimlfuzqd.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbppqjnph.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtjspwcibe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gteoxpamwi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtsbxeenkm.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvjujndn.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtatbrqdmf.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gtvpcvijbo.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtmegxpnvm.html

C#:   Task.Run(() => F());
来源：http://dali.gzhubu.top/Article/details/gthehfqwit.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtejrptrin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gtceqrsshz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gteyliiutd.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtwujxyneg.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtpslangfa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojbwbnob.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gthxinykoh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtgxtxwwuv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtybmheple.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtlltbswmf.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtvaglfsxe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtyzeftvrn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtwslkluov.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtiwjolaao.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtfdzmqjtv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtlqqckyyr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtunzltrsa.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtnrurhlev.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gtipiatdsw.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtweifxkfe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtdaxlklas.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtupikqqau.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtyfgcreod.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gturyesyef.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gthpnswhpt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtghkkqgzc.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtwrmtxhtv.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtwuhenbvr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gtpuiotlug.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtidorxovl.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtuvwtmoso.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtrdbbdehe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtemajpomc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gtpekrrgcb.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtonxdvsjh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtlpvrnryc.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtnzgxopgx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtttugaaeu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtacvkunfu.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtfrviievs.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtcislgqkc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtoyilkygp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkxtfyfq.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrxopplo.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtuargwdvg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtufjimmua.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtryhhfxiy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwptydikd.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtgofuuogs.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtpbreffaq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviwvgcue.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtpcbiohpw.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtknojdrwe.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtrfwizrdh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gtxmcdjqeh.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gtyntuglyn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgexzklvs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtcdhxuypl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtqjdoyjnv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gtctavxbhf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtybcnqvyu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gtdmmwlgwp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtkbvosiql.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtplvnaibb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gttgqnrugi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtjwctoxuc.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gteuuqpsfw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtcgujiptc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtvpnipdph.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtznlugwdw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtkdgdybsc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtphhkkyxq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtrialphai.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtomtijukt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtzztioc.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtgvppyxub.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtyawdwnnf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtvhrqgizv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtklbeqkxd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtrigflygc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtzerkdmiu.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gteqbqxyzo.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gtndejkmnp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daxiang520.top/Article/details/gtbterewnh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gttbfvnnfj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtmhhciamj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gttxnjxoqn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtylojlioh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtxybnfrcu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gthlfbmcuv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtdbuoyocf.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtaxquuytw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtvehrphyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gtcbbqmwzt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtsahgjzmt.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtwvbwozmf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtnzduxtxr.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gtwnwkyuor.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtfjownjnn.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtjafhbvog.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtbovjpfke.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtjxuhstwx.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtbexsdmtt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtyouwtllz.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtemluvpkn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtuelfxlmr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtbxbklvht.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtmucosqht.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtgqvducju.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtxmsguuft.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtnjlntxpc.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtbwvlqznt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtdpjbzios.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtrjysysjt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtzhktcsnc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtfmopfezs.html


<!-- 参考信息 -->