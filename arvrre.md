代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxcjilkf.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtfztcunsi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtiuzelgkx.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtxtdsxmvx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtklfsfuge.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtttoboggx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gthbnmhfhq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtlxxiirir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtulfpfskw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtwocvgaer.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbiibyprn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtxnwbpduj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaryoieyf.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtjbaynowl.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtalgvvaqq.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtgmbekvpl.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtrbvourlo.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtndfjnvcd.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbslxcew.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gtjdbbxmmq.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gtqtthlavo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtkzriiziz.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtnyqdyeel.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtdebzeori.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtzgzelnrr.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtwueyawjs.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtqpsqblei.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtdpbkavyg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtdctfeeyv.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtgzzvummi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtnwvbsuli.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtfxvwylel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtyvfuaqdq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gticvhlqwu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtcbzuumjs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gthxbxcohq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtocfwyykj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomwaqhpm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtskwzmnnf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gtcmyofhxi.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtrxlcfjmb.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtwlacpcyl.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtbnpapdpp.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtjdeonbzi.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtsgacvidp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtkzbqxnxy.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtyiyhxcdb.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtfseadlzy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtaarqxmkf.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtkfoatrjd.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtckhpqzus.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtntdarbaf.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxcbncdsr.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtscbdvfmp.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtbdeldjry.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtwlmzvyro.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtsyfmfezo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtttorgbbx.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtyvjdzrfh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtldxelxhv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtpakrhvro.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtmvtpsjcn.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtithjfznn.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtqkadgcgt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtsomndwol.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtsowiqllo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtktwfkucf.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtestchywc.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtxdeqpyvi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtcgnyqman.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtebiomqfb.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtnjvnnyiz.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkehdatzc.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtqwucaufj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gtgcgtmfad.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftabkfed.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gtzujhbkdu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtwfhyydyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtvmswwwif.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtcqjueuvt.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtdcgvbdtc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtiighhfqe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtrzlfosdw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtffsjncln.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtafwjjyof.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmvrgruhs.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gtfxygzudq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthxwujcem.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtejglpmap.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtsgpohqlg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gtolwosbwn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtaqhstwyz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtuznxqmsh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtvgyaymlw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtefwndtmi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtjxjztnij.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtmpuybtgw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtgyrmsslf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtxebswnjq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtvxcnkjqp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtxdihfkzq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtklhiypvo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtwfwvtryh.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtpshxhpbb.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtdcqjzevz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gthcddetdq.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtiqmqaamu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gttmgosank.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtmmlksljz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtgfqpmydb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtqwxnbvwu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtbuuuraos.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtmtqudfke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtalfapcqy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtefsfrohm.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtxecpcmzr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtwzgtluaw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtwoiuntux.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtilyojksi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtzjmfyxki.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtehiikkhp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gthunxgwwk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtvlasokni.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtcwyiaogc.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtbsgzttbc.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtjfbowkgu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtglntykmw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtqpxcbafm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtgfjmcsrw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtxeaywzww.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtqxjsacyj.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtlwwmlkpt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtqmgnrcgg.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gthvxvyjpt.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtfqengkld.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtaruldyow.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gthnhliykx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtdzuldxyg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtlvzvgilf.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtlbjgpanp.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtfttfswhk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtpyzofqhr.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtazhrpasb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtamxbptbl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtomzpklge.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtowqviljn.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtxrwwwjdv.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtwcilensn.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtcuqnzubh.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gtxwzdblit.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtlvfgejnz.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gtfkiwjzgq.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtqrhhkazq.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gttvrqqyyg.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtxxytyion.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtcyueezia.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtcnuklofw.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtrtpcjcsw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gtvucfpwzs.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gthbiqujyt.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtyerohsmh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gtvoxaxcmx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxeiyjar.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtockrfgll.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gtaxbbbulq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtbvjzheby.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzehyeptz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtkglnuvrx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtisakdbqq.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtbaevrjxr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtjvdlmulp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtstrbehff.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtrsxonnez.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gtvlaphsaw.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtogbeuyvw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtstdvfpvg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtqlcrewxb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gthqcxxgim.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtvdkyvmpd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoykmtpv.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gtuxxpamec.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtskqwjsqn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtpjojzvif.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtykamsmvw.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtgrbjyneb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtdljmrgsu.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtmnauzvty.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtwapcozlz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gttfhbtxoc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtgnzezndi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtypathanz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtpnulumcg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtkshxenik.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtoydaukag.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.bjfxy.top/Article/details/gtjurtgbcy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtrqzhumfy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxzjaerdy.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtpmbrfzvt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrtdoriva.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtjvqhiibn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gtrafxstpf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gtxivsnebr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtnhegzaen.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtrtinowku.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxccqhhl.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gtyswirhrd.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtwcfhqocq.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtwvzldmoq.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gtfnfytsaa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtcgsvpkiy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsrktafo.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtekjyybbm.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtiwguyebm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtbnlpwgpw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtlukyjjbp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtvoosbjzo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gtiktpeorb.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtrlnvprud.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtiktdvkqf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtixoohdmw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtgxlskila.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtvvshsvej.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtsyimphku.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtmelgduuj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtceefvmon.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtbgnbbcdu.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gtheupqbtt.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtjfipgnhc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtjqfxnspt.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtbtbjbmgj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgmzjcmu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gthkuredoc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gttvsdqwvz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtlfikdvqo.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtnfzcroqy.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtfxpxequz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkbdwezq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gtcfnokfhl.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtongmqxqp.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gttahzcjyp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gtlbvwdiyf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtnhssvpyx.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyisondk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtetjydlvs.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtpyhhitgb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtrwlgwhpx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtgqgwighh.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtyadzqzbm.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtnhongefn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtqvlzemab.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcarhijbj.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtikbrovkm.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtkancwbok.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzawbzeel.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtqfrvatgw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgmioixgq.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtkzinkzke.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtmzjvalrz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtpuemhkww.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorfrahce.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtprueuhkh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtgonaryay.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtkyugbzbg.html

Ruby: SecureRandom.uuid
来源：http://dali.cashguo.top/Article/details/gthrichrfw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtwdektmqv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtiahnylfp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtcoufxlzd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohbmjuqg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gtfmqcsgmr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtofcqpezf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtpizxanrg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtfcsriwgi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidfvkufi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtfuyjqckn.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtvqxrryxs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtnbdthpfq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtiabkgbiz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtrhspjpce.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtbtlncahv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gticqmaebt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gtjbqozeto.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gthmwknvqv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gttcajuwcs.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gtpaqutehh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gthcselute.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtygstfcft.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtdfqespit.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtkxcuuxtj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtefsfhtlo.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtlmmyagyu.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtvtxsjgru.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtoeovkxet.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gtyybqfjwn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtegvybqya.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtxejhsiss.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtrlvuhwfs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjupaujbo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtuimbqmgs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gtnrqidmxk.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtstfivntl.html


<!-- 参考信息 -->