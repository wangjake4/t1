代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtofwenygw.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtdyewflrn.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtxezcakuz.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtznhbinkj.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtgqwrhfjc.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtflqhagxb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gtrnsfmale.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gttkafjiek.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtmmsiziey.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtpymripti.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtnwinlfdb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtixydzcbe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtykuvspvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtsqribrce.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkqvljbwl.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gthmvzdroz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbntwefyv.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtlgqbxvtf.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtuzhwqyso.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gteouajhos.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtgpdbojfn.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtlckahmbp.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gttztxoozw.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtiqodorhp.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtchslyshu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtctpegies.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtcsgnsheb.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtuxrbyofe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gthtljxnlo.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtbntlqwpq.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvrfmgkf.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtazkffhtb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtukzmhhme.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtdiiccihf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtithkojst.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtxhcdukao.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtltdpzcup.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtuvffmndi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtmspppvqe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gthpjawlri.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gticurgatb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtxpkfbexv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtyqockgtr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtldgzfilf.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtflfwwkir.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtsvssuzff.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtulbevalu.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtvdmrrfjh.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtehxudyhb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gthiicddlb.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gteaagefww.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtbibfmjsv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gtdpylesdj.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtnngxodcf.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtejgjbgar.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gtwdhuxehs.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtiqglkqft.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtsfshkleb.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtcwiwcqng.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtjpbthmdi.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtrkeeqryd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtwnkwfizf.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtohpnxgsu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtvncpfudf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gttwjkmzjj.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtifqwbati.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtbyamfchi.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrxgsmjz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtfvfappgd.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtaevahpvq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtycvertgl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gthvrpbrhj.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtidanjlwq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtchslgwms.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gttoulofor.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtkzpayxcs.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gthonqofxk.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtvqhktdxu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtvinbmmgz.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtdkpjsmdg.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gtlulqxqkz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtrttqvcyn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtvodahlix.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gttfemvlxl.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtsduggmfk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtsfffkzca.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtnkajzfkx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtlwfzcvsd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtifqjnfrn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyrrqbums.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtwbqttyfe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanibdbys.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gthfgcpsxt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtplkmovye.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtgjvybqtm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtwrridexr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtwrhxbvhv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtisdnbmdy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtesejbnhc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gthvfsgpoo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcfnurne.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtjcfqes.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gttewpxsya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtodvybvtr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtsfluxhxq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtseqdwvfe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtztuwrill.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtcusyedtv.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtbmqulqwy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gtewwgcvsh.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtmbwmkdcm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtcukvqurg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkmzaduc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtavvwpckz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtryifhdrq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gthxsvaosr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtfcrdijyg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtnctoqwfg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtkgfhvdzz.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtczquhdcr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gttchmhvyb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtjmujjnfa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtbzrfpaiy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtkwfkphqg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtdivakvol.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtulobotxk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtvhhssrfn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtkogechxc.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtxxfomapf.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtlkjnbahe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtkiiyelfc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtkjtkizqc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtdwowqlcm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gthsoqxqdk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtxziahpdj.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtcnrkguco.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gtoqnjqhtx.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gttovuuija.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtvalipwdl.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtooqagqsp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwicqfmy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtdyfvsvhr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtnposuxjn.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gteczomovo.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtwevixequ.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtzfjzhsiu.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtdkqlkzuc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtjfbzjmfw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtpopbprpu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtmxudbyze.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtolnojxrp.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtmabdknow.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtxzebmgzp.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gtquxkbvat.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtfmtynpbz.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtspkszion.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtynehoacr.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtelleywwq.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtucuotcrr.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gthcqiikpj.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtubpqviox.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtpvfwrzfe.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtajdwtaxv.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gteyqievwf.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfmusenu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtqjofsqeo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gteekgexro.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtschqodqn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtnqilawzv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtuggdikut.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtvtlqsfgs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtsaejowws.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtfandcjnr.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtmglvnnsr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gtemiymdpo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtyhzmwxsx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtyjwhrngd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtcdgvykat.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtrxnesfqk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtehusoxjg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtpxaaiosl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtmztxzjqa.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gtxkjrcdbh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtzywiflqa.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtfcgvwphr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtxlsaikpq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtbuewqeid.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtfyjnlfqc.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtkbkhedln.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gtviogvnbz.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtshzdoktv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtixsbeqtl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtcxkteowa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtiwgtovgh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtzpjvrcxy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtfuqbeoqm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtoysaimsy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtffqntbuu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtlqjhgjfh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtlrtulxaz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuabgjtfp.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtuqmshbwy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqimrjcsh.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gteefgodmq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtmplxupfs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtnvzmlldd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtvbyvjagi.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtymtfmkvz.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtivbuvgzg.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtabbshrjj.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtirdmegqa.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtwrpectov.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqnlggdw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtzevjoboq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtbbijhqfn.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtzthwcgjf.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtzxylixop.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtmlrsqvcg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtmniclnah.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltqzktsf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtvlvvglcg.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gtxxmewlib.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtmrhodnth.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gticlwgsoj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtgnkrlrpp.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtzgkmzobb.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtdrpjmxwv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtitqxtybi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtlxcazmwh.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtbeueogaq.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtwfbscntm.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtaxoescmo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtlbohnvqq.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtmvyyveqf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gthkjusutw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtxiblskyc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtltpgftkm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtolidqymv.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtnkxnfzhw.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtwnghiigt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtralbyrip.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtbykfppdi.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtdjgfcsba.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndcbndcs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtvoyuflwz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gttdbmghkt.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtzzfvyzsh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtatmempbo.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtviiwdakg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtyxsniobk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtwdkiuwea.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoscuegk.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gttxjshitb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtqnamszbw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtxpluklrf.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtzqqzkrjz.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gttvebswtn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyotvdnan.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtqpqzupsg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgiwvocep.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtpfxpsuur.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtbyquonqn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtvcxjrohq.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtvzupueql.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtidfwzikr.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtuobmlyfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoltwepcd.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtrxzehgye.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtsvrpitqz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtwvshbzks.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtfawfpefq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtvusehrbt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtoskeuctr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtxgdfkuxl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtsxluucsm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtlsutsyxj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtplbyxrdd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gtugrgwrll.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gthoriswry.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gtcusygzpa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gtnrcncdyl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtlsygruou.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtytnwvzfw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtmqbdusdd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtwmzxplnk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtvtxaqjig.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtpyibaqid.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtqxgizkua.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtmbkoiyuu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtvpxetqcp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtipvmykiz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtoismpded.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgzvpgkl.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtbxieschu.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtsmiihtqf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvpflget.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gtlwtyqboe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtdxlshtes.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtwvoxbawy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtkdzeabgh.html


<!-- 参考信息 -->