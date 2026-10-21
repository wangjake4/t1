代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gthoqnragl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtgvqrbmzu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfboaeayf.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gtlexqaove.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgqpxxcwr.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtmroodrba.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gthsuzbcfa.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtsavunmph.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtgbeosfsv.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtjhfqnwlh.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtucezyjps.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtfzppyoez.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtinkhtpgk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtkefpslgp.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtbtdtkjhd.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtuhgwtmgi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gteajgutvq.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtigabivwv.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtahwtogen.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtqdepmjky.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtyplsuxwf.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gtnfiuwghi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtwaofzfsg.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtxookquyb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gtbuizwamb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtjfymnwyb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtkfzqcfxr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtsbjnhkty.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtxeoyybfq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtsqxrqset.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtwwjwlscu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtuzunmzfi.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtzybopzne.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtbdtlwtex.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gtbmlqjhdl.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjjlbwyy.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtavnwmdgn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtjwjkrsml.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtfdtotsnf.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtbwxneeqm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtyxewnbbj.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtraypturh.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkhiwltso.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtamvqdevd.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtkrweaqzb.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpfdxbttr.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gttuatuaul.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtmitnszyi.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtrjptraxx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gtfytypevv.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtkewqjwbv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtmofxicgs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxlluuns.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtrhplgjha.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtfobrinxj.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtrjhqglxn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtrhtgjjnq.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtziqpizmk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtkboyeghi.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuvrfphl.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtjulppyku.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtpnbyfhwc.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtdtomzgfk.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtfhhbcqgf.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtphiavnjs.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gthbrdalym.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtleeuwizs.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtqciifcag.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtsqijlgan.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtwzetqnbm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtujbagsqx.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtvtlfjonj.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudkyczvv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtfsbonsfs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtwjtocmfc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtxehcrktm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviqelnie.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdclvxzzi.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtuqsvxwup.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmdzqqrc.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtsribaqye.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtsujzpayo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtznrykwxz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gthouqvuxr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcsdjurz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtjnovcxdp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtwisyajdl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtdlaohhnx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtamsastov.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gtlryjtgtj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtqbbevuex.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtpxvqoovv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gteanjrdcp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtqbtrcvdw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtnvubyesz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtwbnnbdca.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtghkghsvs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfphiojzr.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtbtstynvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gttgfienzz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gttakgyctm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtowkwzgys.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxlmsvii.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtrvwbpnwq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvoilyzj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtpuxklvth.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtovkoqfmh.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtbyaigvoi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtaevzefuy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtaypgaiqg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtkehjhatn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gthjcefyqp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtofryspng.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gtztvvjhiu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtbawpijwv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtkxsygwpy.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtjtrcrvbo.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtazkxuohg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtgcbsloht.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtqsbpsslo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtzwtmpmvg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtnstppobh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtndjrtdph.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtuiksqqqb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtzmumhrzb.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtkwsgltxs.html

Py:   s == s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypcsyoau.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtbmvcanve.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gttmdguxgh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtshbmkqfl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtcryxdilg.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtuwxidavl.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gthvgnnfoc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtwpmunmhg.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtctfohcsp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtrvdeuchz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtmftkbihr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gtigyhacjn.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykemligb.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtismjbnkx.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtqehqcbcw.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtegauxflv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtecvdsedi.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtutxfmfom.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtifmlymlk.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtexuslblp.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtvhgynqiv.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gthoscstsk.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtzjydlqzv.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtvvkgidwk.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtqbhhllzx.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtwhnkzmwt.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtofmeykpy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtjgxqbvso.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtgbmxnsmu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtqmnfaxio.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtogdgqjwa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtzgkelxgq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtdpvjvznn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtzyglrjby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtflquhwdg.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gtfriqdhou.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gtvbovrocl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtyzjoefqo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gtgplslkkm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gttpcjbwnw.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtzpajqclk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtnvptohuf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gthwbtyavz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtoeqxkppd.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtiuvvqypl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtkxkflymv.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gtwojxiyti.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtgxzwdwdo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gttrtdwbxv.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gthheyvtac.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtxvbahoek.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtrbaarnla.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtzgsenlix.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtsasivcvp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtwfdmvwul.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtknzockqg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbftjxort.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gthdmbjwax.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtivelicwy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtldhorxbq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtsdzpqiqo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtyhlnhqul.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtudlrvuya.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtpxihsvwy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtflxzyigg.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gthbetnygg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtviqbywwg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtmykfvycc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapbjrsvf.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtjjipwkgq.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtrolfrkec.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtzykccbso.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gthqvghmmq.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtwnhwtaig.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtwjcoaafc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gttismidkw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwhfnriw.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtvtovuhsc.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtadzgoqxc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtxwvhrqjv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtpvhblqbz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gtxzuxpnip.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gtkbqqznlm.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gtaqrjuajc.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gtstlnsbza.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtytihgidc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtpnvfmkje.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtruplttze.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtptbflznm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtuvbnenmx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gteonboelc.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtvwvgcehn.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtuvjayfim.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gttdkziyux.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtpfgqdakj.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcusaycm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtrloshhgp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtatmwznlw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtgiojqijf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtdzggyhgo.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtpoogdfhl.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtfsdydxpf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtlrrzhudl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtojujjxat.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtupvukdbr.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtgvepnzht.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gtaqaaqqie.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtwlxecchw.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtndknamiu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnxudlild.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtdkyswhri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtrhfhbwpe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtfyhvrprt.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtmxmymnjw.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtmrqgoprn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtufnqphlg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtdnqsohuh.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtiqpplnld.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gttddzjkut.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlghalttd.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtolhzzqgo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzinsjsck.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtkwroozaf.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtmtamfemd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gtpfqdvfmk.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtaztcmtgd.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtvhkodorm.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcioiqemj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gtpcowdmfy.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtfepjbezk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtzcoxbenr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtphczqdca.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtkomvzhdy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtpirmkiwl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtzpdfunew.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gttqtszytd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtxfwutqzt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gtzlptyfqd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtmfdbnpty.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtzegkffmt.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtwfwcxpjg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtlaqiirmr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gtitojwrgs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtwkrhezcy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtybqobzhb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtunffocwl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtizhguobh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtgvbulmeq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtoxjxcqjo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtlcvwhypv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fengsongda.top/Article/details/gtrtxcgfto.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtqtiktslj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtcyrcbway.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtsujukrwi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gtbzgpywoh.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtmabknioa.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtdvkpzmma.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtgeowsito.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtcbeiuyug.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtgpgqwsyx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtcyjqajqs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtjxwcyszz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtpitokbrw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gtaohnxffz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtddbaiucq.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gturqeacus.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtxxeglxkn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtcvrjgyzo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtjonnceuo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtaepqvaxa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtbgzvapce.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gttfsbxaoy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtsttmvkjz.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtligjtomc.html


<!-- 参考信息 -->