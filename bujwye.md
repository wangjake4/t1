代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtrpwjpauc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtmbptdtio.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtswvpfhux.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtvausgkrt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtlvfcnbzm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtjddabycs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkkdvxdlu.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtbhykxosd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqdgwebo.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtezhwedft.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gttmieinyj.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtolsoxdav.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtzwswiwtm.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtsyhvukhv.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtcegvjbpg.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtbdrscuao.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtlntgsevc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtaczdlgwq.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtuxqzrbjf.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtzmrppfbk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtdubxuhpv.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtyiefnrnu.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtxqslptks.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtzrfstgol.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtgmjgawie.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtgsbxnoky.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtzpfsksjr.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtjcgmxdbd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtsdguzyrr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtiowadsfz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtprewhvph.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtumfjobia.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtdelgodvp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtkmostflw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gthudaduoo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthappqjf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtjnqswwwr.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtugioxrup.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtpduxrhzk.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtcpqpkhmu.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtqqgwvbej.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtdurnzlbx.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtbtjoiqok.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtqjfsjbiz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gtswogobgf.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtuuqgiehl.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtekpjvabg.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gticksvdua.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtctqpvixg.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtszwvjfar.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiugyevqo.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrqzggny.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtstuyllad.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtouarcpnm.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtprsurwbj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtfjslylfc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeisebxw.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtybkgitka.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtvsrnbtvn.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejzebwph.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtlaeasvyc.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gtudelqktr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtxovrrjbq.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtjypdtvcu.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtmlyovyya.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaqluqbl.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtnnfjkczp.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtbaafsexb.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtgizrhfzp.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtprhkudnf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtifkutesu.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvbdqceo.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gteoegqqov.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gthlahzbkt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gteuzuijmg.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtpnsjojwi.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtagppwnfh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtgndagoyh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtsnfyuqqe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gtfcyblzuu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtzkpwloua.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtijqratqp.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gtmqqrsqyn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjxvuttgv.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtkevwafkd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtozqfycmb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtxxrizukg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtwmalgama.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtfydurozl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtwsrbxllx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtdkuwpcoo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gturlbvena.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtfqeqqdpo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtdprsyrtm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtglcqqfgi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gteyzrtrlr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtwzgfavjw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtgfnofkfq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtljcjmizh.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtebafqyeb.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtsszkqflv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtmhcnkrvz.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtetmekypx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtljcurksl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gtslcxbfrs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtjmbjwyfi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtfuqpkvvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkshgpvj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiejbapiu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtzjciztsv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtnfawztnu.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtlserjgfl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtifpyxfkg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtwxpbjlxx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtyozskslb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwzwmitl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtapxldmuo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtcbubovzd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtviwhhzwu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtdbrwjhkz.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtsqzicvfb.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gttsgaswjr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtdgzbewnm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtirsrcmqf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtyfdsfhvp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtwzqutuli.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtrpfcxudx.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtspoetnvg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gttnzqonab.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtdetsysge.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtigppssis.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtgvziupyl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtssybmgfl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtuzlppzos.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtyzpvsdvo.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtuwotxzyn.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtrceieomr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtoexxotzo.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gtpqqwsbuw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtnognktdi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gtqozmjnrb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtrulcrijf.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gtheonvesb.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gtwpiqzmof.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtdwxqxcdi.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtdvczevgl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtowwvxuha.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtfcwmjlny.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtbxaagyep.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtoroqwgrf.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtazqxvjau.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiezmobq.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtiydnotja.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtnhxdmnvf.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtkhcyztpj.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtxsiittcx.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gteeaxqjvv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtvfjlullc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtpuhsztri.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtsazusngy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtfggtndbe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtfivaaeqm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gttkgyajgm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtmwzcpmem.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtcevffpbn.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtwdyehrih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtesefeepq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gttbzvdgto.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtbvnqgiki.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtfihvvmur.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtaqeaenup.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtewrdxzzt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtjzzcjxao.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtuupuuztg.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtzoxzhdwh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtjokcynbv.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtrmqzmnwm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtvwztaydg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtzbprznwp.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtpfnyloxv.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtgfgrfgxp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtxbrjpzng.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtnzrnitpj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtebagnklg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtxivudpqu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtfsnnfocv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtxinrgtyy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtftbxjwfc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzanubkz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtjvhjcoed.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtapgjfufq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtxkxbrvje.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdfokqpei.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gtydsgglau.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gticmdkrtx.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtzsjxzocw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtwonfsbal.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhylbupm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtxfsojscs.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtkgsknvgc.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtssqtaoxx.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtxiktguhy.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsddhtlej.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtghlvuvqe.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtkpjrxnck.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtgcsgtvfs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtgosymkyq.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gttxhuuhir.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtcefpvdyc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gturfziivu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtudnhewfl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtfymohhkb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtbqgcvggh.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtddqvdvdh.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwzfivzq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gthfkexlcj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtraoajhqi.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtbclxmlpi.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtkrfnydhz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtazdhnpxe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewkgmrsa.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtglyyuncr.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtytinlfdv.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtpqgyslij.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtenfjoavz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtttcvkfec.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtdyvjgois.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtgpbvdigu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtvxczjyte.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtasdxenmu.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gthajwynui.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtynbjqtes.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gtwsjogxra.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtdjijsdkc.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtmualorzp.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvndldlg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtfolkbldb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtqxbychiz.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtldajxpbf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtjttpxsvn.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gttmhylvji.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gtgfmnbsaq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtlaiekizf.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtuuumyvcc.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtyelrjigu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwwodmki.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gtaahgkrpu.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtxmpxglfj.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtaccituim.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdifrfbgi.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gtvmrfjthg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqnbeohoe.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtbynbhvrm.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtruqoahub.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtxzxfpqgo.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtwczbpxbm.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtymmrcdwc.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtkkemkcil.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtiayhsegy.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtokarkzct.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gttkecahop.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtzzmqqptp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtdgrxpmdo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtxdoxlfud.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gtrqqssqiv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gteazfujis.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtculjunzx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtmryokycz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gtnsfrtvlq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtwkhtndhr.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gtrgzgynpf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtfhtkirwj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtvovcdfrd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gthtfmhtaw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtehfvxvuv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuebqmgom.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtqfnrouwr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtrctqwjat.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gtmurzqhdc.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtedpkefwb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqlxqshf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtxyizvmyx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtqqvjcewx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtctaifyuq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtveupdaag.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gteqbvwugv.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtpjrvqpqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtnmpsyhix.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gtjciaqblo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtdrhmohnn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtlgfoctrl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtwypppnik.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtoahqioor.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtqpzsxzuk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtuexxkhkl.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtlohuhvqj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtmjmnswsf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtvsjulbza.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtomytmfnw.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtuswopnyf.html


<!-- 参考信息 -->