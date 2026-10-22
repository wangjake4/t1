代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2jfpavwrq.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gt2dfxrhdfv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gt2qmdvbgpv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gt2ymeinsyc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2bdknuxqf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2smamable.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2mvtnskra.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2krqvppkx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2ektuqpck.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2hwtsxgjf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ftolzolo.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gt2qskdcjhe.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjsnzefj.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2yrptbjik.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2ehlxbbqw.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gt2krvwfacn.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2eukqkszp.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2yqycxzrx.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2dfsvkewc.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2xrhwmszc.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2ooopcovk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbyxphcb.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2hltpopwy.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2pdbiqzyu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2lqlhfkrz.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2fbseswhn.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2amtrycxj.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2kdtsfpir.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmxfgouy.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyyqrrva.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2vvnfqatx.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2qnmonawl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gt2ttvodhvp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mapncohd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2rntbjrwo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2yelnrrdx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gt2pmukgjcq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2lbxnylhc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gt2iomucicx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gt2vwyulsiw.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2aeggdoju.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2sxeqgjyw.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gt2aakcprej.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2dubucevt.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2gadhmkeo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gt2xddfqlhm.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gt2sgmdfpmb.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2utgfnxux.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lldjbztf.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gt2tokawpcg.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrordjhp.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gt2mjgqoojv.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iktumvwg.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2phoarcop.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2wbnnsalw.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2bnvkjfiq.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2silkckxs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2rvvnilpi.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2dectgqhv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2sdbsxssq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gt2pyovxibv.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2iyjqihcy.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2mmcwcuxe.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2qfpbprio.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gt2lkrorwra.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2pplhqbao.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxpxmxyj.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2iovewpqd.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gt2wqrmlpem.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gt2mnrtyiff.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2jdjnrbfu.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2fdomduef.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gt2djhindft.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gt2rdagxmiw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2ursvaojq.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2aenkrnbz.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gt2ikcdxswx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2isusqnez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyszhvok.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2kxaeyeuz.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2ensliekk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gt2kmxibepc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gt2xffhxuoz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gt2ctbdpvmx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gt2qdeossvp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gwxiqcae.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gt2ldvnhoro.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2lhbqvsgo.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2gzeqlwxo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2nmxiumwd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2vjntnopw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2kadrpmwn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2arfhrves.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2kypukjnm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2cvmaxeeq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2atcsarvc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2cxosnibw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gt2skkasbkj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2arywtzuz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gt2qfqiipos.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2tjvpktnq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2bdoonbll.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gt2sucuvuem.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2vzeoqhkv.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqpryaio.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skphibme.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2mwazdzei.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2limovvaz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gt2kmwktlae.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2iqyavmuo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2vykefhya.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gt2mlhpvvhv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2idtadrca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gt2gjcevmpj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gt2xograuat.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gt2yurllimy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2krguuyvg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2mubfnscg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twlnlzuu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2krrcnwsm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2xsxjdnyu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gt2kiknlgmj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2sgnfadfz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2deoowkia.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2hyvbpcvg.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2abzgggac.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2dwnogrxw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2waaxlpsg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2ukztxcdu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gt2hdtskotr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gt2qwnjmlcj.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2hbhylnnb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gt2buqdmsru.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2ocqbunht.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gt2uucsgibv.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2oibmsvaj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2vdmyzfca.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2jpjkvoza.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gt2mkdbmcti.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gt2ogzehuni.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2hvhcszgf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2taqhsfqo.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gt2ciruxanz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umqvyyli.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gt2ojkjgamc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gt2mmkrwalb.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gt2yzzidpow.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gt2xhghrvbx.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gt2pkfgmbqu.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gt2hlxaeyze.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gt2xdtdjfgv.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2iayjvgik.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2qgeymkew.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fagcoauy.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcwzsktj.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2fgxwsrar.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfcsnlrh.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2gcifblbk.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gt2tjeeomru.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2kkrbcmme.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mygmtypd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2zzcrferh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2nmlltoqz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2xlumjfte.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gt2gadszplw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2tggmesnz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2lwsgwxbv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2bahkfwct.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gt2xjucjdtp.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gt2tqwpkbgx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2qgwkwzdl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gt2imbrfcau.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gt2zkhlqadt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2uctcjudq.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gt2fzcexvxl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gt2rwidkehl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2gneaxisz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gt2bwsglhsh.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2bgnqkokh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gt2mkoultwu.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2adggbsfi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2tldhhocd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gt2gbyiuixe.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2okvzzgah.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2wnrddtfc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2ghafqbdk.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2kmnwjdqt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2fajvjzhc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzedkmcs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gt2hcfumzlb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2usdfzuys.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2btkcfjsg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vogrdcja.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjqncvql.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2kgzakrvs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgyuxhsk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbozcjjd.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gt2rcptzncv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ymesdlnb.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gt2pqvarued.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2vqwacugj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ejpjspui.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2djgwrief.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2dzdulaor.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gt2zelpeavu.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gt2ordvwuwk.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gt2bkzwxtln.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbmcdnrc.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gt2wmajlnvc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gt2pgdbcasg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gt2nrhwoanw.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2aoorbnwg.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2vbxrmsff.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2igwlkbjl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gt2sqnuvlhs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gt2grxympfc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gt2yxrhxyad.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2umdatkur.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gt2whivznee.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gt2secpznuj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gt2qvurdujb.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2yfjrsvam.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gt2uznjwyus.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gt2ljcswttt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdlyipnd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuuapmvp.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gt2ysrkpvcc.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gt2ueurnmlo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gt2qfgtuwyc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igiobrcd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2htdijhkp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2eogfzuxv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gt2wvboaieu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdwsktrf.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gt2skclrdyx.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gt2rxogbdhx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2kqfzqlyk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gt2mkrytlab.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhfthcms.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2wypawywf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gt2yhkjqyjw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gt2jllhtkjx.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2pmjhajbs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gt2ggglynvy.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gt2zxcakbrk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2bpfrkmbt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gt2mxhusedr.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2uurlqgeg.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2tygzojva.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gt2sipjgbjy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2geourgqe.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2nyfcqxsa.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqwxpgvo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tkolqkvp.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gt2hcysuhru.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ynijhonr.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2flxvwfsd.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncycyjps.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gt2ubxsstxt.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2ejvxcigm.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2jodbjiwx.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2qronthhn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gt2kxvmjrwk.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gt2yueqjwuz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2enuaiywk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gt2duzugcdc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jlsjyb.cn/Article/details/gt2cxnwrvpo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gt2jlrjzgcr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gt2smnbffif.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gt2nincugao.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2skymkslr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gt2ffambwmw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2pptdyzgt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gt2qzxuixaq.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gt2hhgqamlx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvvartti.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gt2lmktlswg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gt2itqwgdpw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gt2ixztjuix.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nivzqrid.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2ywihmeuw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2zmvcpcld.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gt2wqpuippy.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gt2ntsvilqz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2pqpjwnkd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2dtyktkkm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2skwbhybt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gt2zmbfgnkg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2gxflretz.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huunicfg.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gt2gglgjucr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2xyfdqegi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gt2gyhgjawi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gt2wfpydiez.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gt2gvnconsk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2kxunpzux.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stistkcs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gt2prjincct.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2mhluxvka.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gt2gawkmotj.html


<!-- 参考信息 -->