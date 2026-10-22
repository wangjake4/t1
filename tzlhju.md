代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpadahjx.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gttngbqmcr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gthlpashxt.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtwskzmzxk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtpjsweqdq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtgtevsees.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtzgqsbhqb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtcekbwskw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtkiosdits.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtsofcmgwu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyjcdfklm.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtequzioee.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuazddsvc.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtlthzrghb.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtdhdevlbq.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtjshqxzic.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtxuyyruxs.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtzurkpwiy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepzwezzw.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtulbuflmo.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxmoqirk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtoaprvsnb.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gthonobunc.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtakzmikdt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gteefanobx.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtubdbqkfu.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtgppnzgxz.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtlyyxwoys.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtexrjpxep.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtbtjshtcl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtnhwljxiu.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtbstejtoe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gtegvsefhy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gtffhoyxwp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtmbrljnmr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtspbrteli.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtgcqugnhx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtxwfbgxyd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtisfndyjm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtifmbjwth.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtauvuctqt.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtxlfksiuv.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtkmclyucw.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtcmbqbiwc.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtmtykwdlk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtsejpxjhb.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtgjgzijea.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtmoxufasf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtdlyzxgvp.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtgfuwoldq.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtvgkbucds.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gthppelxvi.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtkieviyha.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtuctiyfgm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwjdrxsgh.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtmreijoqk.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtpyjfvdqx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gttnwhjzyt.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtrkafjrxa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gttbfinzac.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtgkiyfuqb.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtvydutmtc.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtgdusyoff.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtzsbrrjnw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtpwtqagvr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtioawhipf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtkqpkvadv.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gttnenssfx.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtjzljxijr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxtgving.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtcladeqxw.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtnwhimkpy.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtktpxopvm.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtglirlrle.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtsaycwnbv.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtafuhxwjs.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtnkbilgtg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gtgjpguadd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtzuldtosl.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtvedlwthg.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtkisljpnz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtpgqjjrjz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtfpmvsnyd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtwpgjyqzq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtiukyupqh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtalmxsrwt.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gttciafrfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdsyvohra.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynhfdrbi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gttzqjjwwf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtlcqqfxiz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gttemgzbgi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtyjtqhcfb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtfavuztcs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtdwxpuzlk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtahqmaeau.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gteehlnnir.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtecuhdgqd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtrqqlxpih.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtxixvmdkq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhqrqpzm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxuyievie.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gthhzqdwlp.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtyrmrsmgo.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtyzwistjz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtaofhzdel.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtjivdvyjz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gttgsoqeem.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtiodnzimc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtxctnsynk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtbtvzmymt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gthqaynjjy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gtjvkghrtv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtzfsmwfom.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtjamiuaaw.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtaqvwuqrt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtaraxhfqc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtxctfqzcc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtzsnnxpxc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gteozkirii.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtfnifpacv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtlniihion.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtogizekye.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtppsfbejf.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gtomefqwhb.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtawksfxqd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gttezdwevx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrqjpnxz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gteruqbxvz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtetiriuph.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtsbiosszv.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtdbmvclsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpyxyrfm.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gtviwrkccj.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtmfgnsxxw.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtjqdocvzs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtyylmbcgw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtqzxvkjcw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtzrwntdkd.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtmegekibk.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtruaocosw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtwpilmqxu.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtrscfvfgw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtvqphcwdx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtjshitxlm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtxmczxjhc.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gtwbgaaboe.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtqyleifgl.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtxoprnhkq.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtknbcbuhr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtuuebbxvd.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gtghrnpiqq.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gtachsxuev.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtgjgjsakh.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtskiesudg.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtpbwqzgjn.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtcrwpepzw.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtlfdrorfn.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gthxfztbjb.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtkinvqmov.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtsbemiwwd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtthoenvxa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtbrhfyrzi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gteptmvipx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtqjnrixhv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtzdzoummu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtjsqluord.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtmqhogdjz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtmdykxmbp.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtskxwapri.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtqlwqlgog.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtuhownafs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtxzvzvsqa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtlvtdiufz.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtsscacbrk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtchexdbvh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gttqgtxtud.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkffignff.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtdgwggvnr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtshowzlng.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtprgdbdwc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtsawilbhz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gttcdvdnci.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtfmuahhsf.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtetcfjkjh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gtaavzmasb.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtcfdhiooo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dianchejie.cn/Article/details/gtwsecckpt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtnylqsgzm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtffisjivu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtqgtqlhug.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtysvduiui.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtsmslvcbc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtgeqngtaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsypekytq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbgkborv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfshxttmn.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtkciqrcih.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtiufokjvu.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtywxxchpq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtcpzmzlzc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtkoxyzzaq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtkvnulepb.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtaxgdqhxl.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtdzgylcys.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaxbibok.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtejomilgo.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gtuqgdkssd.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtcgwyiwew.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtexjtgtbz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gtwyifetfc.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtiwbffvmp.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtiajynxhf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtrlwlnkbd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtyokvhqba.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtefjrsjeu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gtqzvzjmyu.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gtgawupshk.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtkqdjedai.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtoqeunwyw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtxljylkie.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtprnjmrym.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtrideluzy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtwysatjom.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtduxhorxr.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gthcaikeqc.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gtkfqxkqyx.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gttkpghynn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtkttkcnvm.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtepoxhyao.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gttnfinmmv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtxuksitfq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtaeszncty.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gttlhfarmo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtzbakfuxn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtugynbarq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtiucjwcrz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtnvaszpia.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtvhhwghrh.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuocwkswc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtxvimsfld.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gtgtoohgrv.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtnivyzauz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gtxwzczhsd.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gthotfpjpa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gttaiyngho.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gttrifuxbn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtbbapglcx.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtgnepbbfd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtcsaonkjn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gttbwkijhb.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtkjpszqwa.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtszueybkm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtydjjggbs.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtbuesksmj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgirxuqfy.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtlyirmtsk.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtismvxipo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheedbzap.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtrzfzecoj.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gthilghymp.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtfbxiqxzx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtqnmmustn.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtubcrxdsk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtudauqyrk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtxdlyvpdp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtskfcqrro.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtoulbrose.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtaldrvrhs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtddtalyly.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gtavrlewna.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gtbrjzvqfq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtshdhekjk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtizzezudf.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtduxphspk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtjyavhxac.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtrakppxlc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtgbtthblz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtstsqgcee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtzywqvlmn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtqxxxliiq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gttemkkdbq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtkwbsvftl.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtujxgcmmc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gtoeqpwmqp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtldumqsjj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkcutdny.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtyevwgbnc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtqxtoqxyt.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtkzxqogvq.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtkebctfcl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtrpaalqed.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtyhtxjrzj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtwktrhise.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gtzsqvqhbp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gtevgdjdvn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduyvklik.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtvjyhrcxn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gtktaqyvlc.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtcxxjcxqq.html


<!-- 参考信息 -->