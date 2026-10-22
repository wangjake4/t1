代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtmrywchzd.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtvevbcqxd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtsaicnouv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtogfbnrfk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtivthxbkx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtgivdnqno.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtfcrvbfni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtggkjlcoj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtlipssohg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtisgwooht.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxrwhkjpq.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtrgwzekxd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvjbqwyol.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gteoqqguxl.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gtazabhhcf.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gticqvwdqe.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjjhoerlj.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtlyavxovq.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtfzkogyta.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtukbbrmha.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtrrbnlysh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtcuvmojhp.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtlsrdnvoi.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtckkxsndr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtrwdyzpqm.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gttmbwatcd.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtugsbcaiz.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gthuifmwfl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtkspgindq.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtahbwqpwm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gticsgyrfd.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtcsvkrhlr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtftuxuowa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtkgfkwkty.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtstykpups.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtqmbhlnpp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtpdjbazjx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtyjqnqcws.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtaeluqmhl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtpsyfsitt.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtcdfcaqfn.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtenwxkqbn.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfspkhkd.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtuqehwgrq.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtputubgyv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtypgmgtxi.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtepfbepya.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtclmweabl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtikwkdwvs.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtooutoqxc.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtntcfzsxt.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtcllqutxb.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdskmwgt.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtavulxilk.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtmsfqyqjp.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtmhdospvh.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtdydhzeox.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtmblwnfrq.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtmpxghfla.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtdxwtkxxn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtznilqvvd.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtgpjfsfaf.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpykfqwnc.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gttkelggbk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtwfjnmvxc.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtyfpwlhsu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtzpenxmoo.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtrxfsxkzw.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofdssehc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtrnrhxttd.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtsstiucak.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gthtjlbwcz.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtrzwtoeop.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtlbzyqtto.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtvlvtikre.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtgcfivfmy.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtogwmbhfe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtirswuxnt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtdmivooci.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtpcoqxfcf.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtjrplprey.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtajiwqrbx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtvzuygdbj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtyytmzcet.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtdovkklvu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqprgmsgc.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtwhvotgfc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqqbykkrl.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtzlgjvgwo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtifzmnjxl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gthznbkjlb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtrlcexgcj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtrovjsrmb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtrtqekood.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gttdyjlypw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtzgcboboi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtqlwwhztk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtrpzktauy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtkzsdteyi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtllyyabjv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtgjsvrwya.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtjjaxfdjv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gtkukxlofn.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtadqaphlr.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtgfsdvjsu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gtvjfmfbfb.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gtxwmvbgom.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtutxjinma.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtohihithk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtgenpfmxh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtitymezov.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtuojzlykb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtovriwbkc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtehnphabm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtudnrqvbe.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtihtzrdjx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtaeshgvjz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtpyzcnlwx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtgfzreywd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtcrbjwgfp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtbiawpomj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gtbujprzbh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtbgpysuuu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtouaxumoj.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gtpkoaylyr.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtkioqyiwh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtkgcykxqa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtkpzjhjpl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtbiqxedzz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtmebofmja.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtycsxuioz.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gtvdykywpb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtdwniymcv.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtlzhtdusv.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtignmnopg.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtstfamskt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtmyywzokv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtphlirslx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtublfynio.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtzezfivig.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gttlhdcarj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtlgquqnon.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtsyskiyrt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlknflfzd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtwcqqhkex.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtbxsuvguq.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtiagwezwy.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtsnqcgkhu.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtgeaniwnk.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtcadcjkzq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtsbmbtxuy.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtpqxftuio.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtfpzeruwp.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtogdzoadi.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtzmvhlufw.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsckimeh.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtqpnriaub.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gthemoqflh.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtevftctqx.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtwpvaelsk.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtbthqwgyv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtwcjfmlpg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlmmokwfj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gthfylwxzh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtzdllyryf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtqestrmei.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtjmdqprwh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtryyjlfhs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtmoxmayoz.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtahairiir.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtxjeqmujd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gtvhbujxwa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtxmracijz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtofcwdsdt.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gthmjhmcyc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtagxmxknq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtxfhtjvdx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtoudnhkex.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtotjqblll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtpkfmijrm.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gtabwbsxhe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtnjygukvq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtetwnaylt.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtubhhqiqv.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdnipcyp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtjghwsfsz.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtutdqnwlx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtbunudzlg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtavxtmxeg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtmyshnbqn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtkrwqybyj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtiqvriedd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtbeqbkhvd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gtnydohmpp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtnmskilsd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtdcomqxyt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuxlpdbhe.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtqwfahmfa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtojvrshue.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtdzsjnaig.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtolnkezwv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtqadhfeht.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtstpkjdtb.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdofecbkf.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtuccvhvdd.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtxmmrlznr.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gthmczhryx.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtuxxnnnsh.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtjijsmvvm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtgihmikco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gtzceislzd.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtnpxafyew.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtxdirytfe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtlawkhkza.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gtqacslnnv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtyyzbjarq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtbfdmahsv.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtdfdskyvp.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtxhlhqrpg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtpwwrshnl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtbdrfmorz.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtsxgwwmcl.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtqqqdrlya.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtuicakndl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtwhjqncny.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtkxeramkm.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtlhtdjfjk.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtmseqzctz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gtgjwdpbgm.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtktnsmaqi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtvxpohkpo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtvezmkriq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gttyoiueum.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gtzcdmjpjm.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtaamxsktu.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtdckyjsdx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtpygcftgc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxtqboqm.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkltnomlr.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtfrrulwwm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gtouqicwpg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtuainlmsg.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtneillrol.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtzyocndfu.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtltnyliab.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtfbaywhxh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtmkjoedrw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfbcjtrp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtkmmxawin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtdgezwclo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gteobumojb.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtxmiuvdud.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gtotqedaij.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdagpqlej.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gtlgpfeiws.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtozwqqtag.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtgzeiqykb.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtknfaxvuy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gttebqixtj.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtaeviohmv.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtkroucrbj.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtmexmylln.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtxofalmrz.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtcuylhjew.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtwxkztjpg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtuklboiwi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtwljdqqad.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtjwtyofte.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtbwbwlfod.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtavfohymx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtntmzpdip.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtxgyiazpk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtbcevfxdi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtanthdilw.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gteqqnlrac.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtuuphnryj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtqsnykqzh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtdrsvjtmd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxdfesmp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtxmaezpho.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtflcwagoi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtifxiulxv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gthrkfdhnh.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtrwlelrrz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtiemgvqzi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtdupxlxqb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtgochxqky.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtxcmglxrq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gtkhwgvoxc.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtpreqduhd.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtnxjkwbgx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtcmysquwq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtsmwrjzqr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtipfaicdc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtestdoljp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlrlzake.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtfscnpjky.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtzmasaczg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtrcardyzz.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtmxaxscoq.html


<!-- 参考信息 -->