代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtdxmhjqlu.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtnpswohly.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtdeqphczo.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtyrjbsgbr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtbdsqhobm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtdkfndlgu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtlpfxwsgg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtfqhpovck.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gttuahqczh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtdifvxogm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gthbjixlsq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtvhskuzjs.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtzfwbzphu.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtosoiwair.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtkuzlcvtp.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtjtmoacju.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtaagiteue.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtyxekjmsd.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqbgsfso.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtkmccrgrn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtjbzszrqp.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtzystsytz.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtdiifdrnj.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gtmczxnsfp.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtvenghkxy.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtcdqqvobo.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtkgkkdujb.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtavwpuiby.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtumuvmeoq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtsjdycrwo.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtbxptmnbv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtefbcgsyt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtnnikrhjj.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtzjbilptr.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtzssfqerf.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtmhlkihzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtzuzffmgg.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtglterncy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtkwuntzox.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtqcoyooct.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtrefujior.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtctrdupxn.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtstlyjgte.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtnzqbyewv.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gttooxsrpi.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gteclqflws.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtzybtqaot.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtlbhncqcn.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtkfxtsdon.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gthfvriqih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtxdwdtsjb.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtdygeqocm.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtdfojhmiw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtzgcyyoeq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gtmhhcrnpn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtyvjonple.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtrubbqjot.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlmzcpeba.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtejwjrxfk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlyvurnqa.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtegkstnec.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtrpsaszej.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtjowqaaxp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtakxpttqm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtfruatmoh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gthitnnyrj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtlylhdlfl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtsxvxesyc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtslcsnkrd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtbowdyiav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtgreibxoj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gtcnaeiuok.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtmrqryatf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtqhlzvehm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtljzrzkbs.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtupugwbpe.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtzzrkiuaf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoybsiga.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtvokceahq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtdonniojb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtfkbkapvo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzdlpdbw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtuvhndvub.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtvdiwwhor.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtdbqbsjpc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gtuwoxxwjb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtufuwbstf.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtmjauesgt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmtrxuvlr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtkkliurnj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtxqnbjnpb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtfhuwwdaz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gthnubwmzf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtmnqmigmb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtukdslwev.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzrcirun.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtbrcrdcmp.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtlhcozvrl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtfmxqvgxx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtvxyrhubr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtumytaozx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtttlcwama.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtgqrbcebh.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtsmxsbyqs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gttlsufmqm.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhmqxbro.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtwsocvrzq.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtwxwbsbwa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtwjppantb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkahtccad.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtnnvhsehe.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gtjgmwsyzy.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtdgizjtev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtthqdedkg.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtszdzqinn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtnyoxmefl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gttrhqyyos.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gteuudguyk.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtmlytpvvn.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtbumueqsa.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtoxuptmbu.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gttqjuqtza.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsruzzmr.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtksdonjjw.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtmmhmyeei.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtnjmygwuy.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtnjycdsdp.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gthkxuuelr.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtwndmybez.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtlyxuysuk.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtedwwkmgo.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtdfirmxkm.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtkjjydprr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtubchjyee.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gthqvxupds.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtbozalnrl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtpigkfwbk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtvnulilsy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtckhuwfdd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gthigbwxtp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gtdxxnwxoz.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtouilggiy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklrvrapd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcdbeifc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtnyhftjzx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gterleeldw.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtzhdgljoh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkryjhpzh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtmfbwusvk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtuxosnmux.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtjlljdlwm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtailckyfc.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtndyyvqwk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtiddnumgn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtcrvywcnk.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtgodupkcy.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtoevhhgnr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtssvbxusg.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtilsdkmat.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtiwiukrfs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtwbkgjtkm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gtgyjzzqwg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtfyosdxxw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtqrnazedb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtvgdqfdyk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtbbupfkxu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtqfcenxcd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtuqhrxcku.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gteeoftasq.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gtcavhzgcp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtinewhzqh.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniifyhec.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtgnpwipmn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gtwipcmtmj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtzwgeaykn.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtdptvyywh.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtxfmaznaz.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gtwpfliurc.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtwgeulxpn.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtuzksbejt.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnerkhnad.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtcjwxyjnt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gtnsushfyk.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtshrheaaw.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtmcaugyce.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gteztzffhx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtvtqzmbri.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtxvhnqmcb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtnyttmebm.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcnrufcb.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtvsgngivf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtlzqcothu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtwtdivgmx.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtukrfgrmg.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtzzbvzaev.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtszlvffoj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtoetncqaz.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyziqucas.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gtflfhglaa.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtlbkklddf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtnddqeleh.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gthnfjagem.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgfykjhmb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtypwuqrmq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gtdqmezjtl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gtzblqaafj.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gtbgcpvdqs.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gturgkydem.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtspzpihjc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsopsqfic.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gthkptmcua.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtxccflwbe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtdcziixws.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtsmjrkjri.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gtmlmyirqw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gthftjnpoz.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtwqabqxxa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtpjvxivxp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtavwaygmx.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtjjxumjsa.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtvrtumens.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtijfrtqxt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gtityxdsdz.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtvapubwtn.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtutlakprm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtceaepczb.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtkjwljkaj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtieoryyti.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtlzzsdcxn.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gteocvuzsw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtgtvafjyv.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqlptnyb.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtpywtkrgq.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmczjlhmy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtxniigeva.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gtykrqufzk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtryxpcodp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gtmcqrmgtt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gthwkonlmc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtyxaenrif.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtxhdbmsrb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtzoxexmot.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtowboaioz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtxascfqlr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtyhkregsb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gtjpkpnfhw.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtqccmxwki.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtjafmyhla.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtwvwxsqmr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtpjjucody.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwodplpm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gthtuosgju.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gtblbgxsat.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gtokoqlptj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtflgkxvhg.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaekwjhx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtouyixeav.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gthpaalqrv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtyetdqnhv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtpdkbfzbn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtmblaqrvl.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gtuzquzpni.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtyxgqxbeh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtkrshqzkl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtnsktzqmp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtqdccpchz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtjfjukbaa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gtssshaaug.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtauezndfy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtqtnhzwez.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtapzaarba.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtasaihpxj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtzojydvbe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gteewqajmi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtuqbmrorz.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtiakstbeq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gthsnjzyql.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtjiatziei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtivsrtvfn.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gtihfvjvja.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gtddncybga.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtursvpxnp.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtmlwpnhex.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gttwuzjtpz.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gtfdsjswtl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtloiozuzd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtoyfkjtsq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gtbaqpyogy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtejqdpoun.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gthqmzizan.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gthfcpmyuw.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtglnafpcw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtzimmjobi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtdxzzhtct.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtstlamhaa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaahndyr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviynwjnh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gtuetremzz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtfdvcummz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtynpduqqu.html


<!-- 参考信息 -->