代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2cbiksrim.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gt2gbmymqot.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2lwrbdetv.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpvlrher.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2bsxrvrml.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2egxqapds.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2oislaybn.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gt2somotlwm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2xaonwrie.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2uozkkxpr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gt2bdttwyyt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2moueylhd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2sbaatpaa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2wponitvi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kjckqhxs.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2lmzwetlp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ttcciyja.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2cwhzrggh.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2wichsiwb.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjiizzmn.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2pkibsscz.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2lkkdhwzc.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2jtdwicbj.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gt2muwgeuka.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2rguufkxx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2cnbkjhrp.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2njbkktuj.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2tygxaqxu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2qrlableh.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2mgxntgse.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnmfahjw.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2bkxizyzq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2uwlwgxod.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2ifgzarti.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2qlizthfq.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2spwtvqnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2gljfkblw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwyzmoyy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2copmmnho.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2vrqqmfqb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gt2cenjzvnt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2jpfnsrhf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gt2ntdoxkmg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpholczi.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gt2rrigduwq.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gt2ggnbpmor.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2tlxunaje.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2luqazhxw.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2ltkudkvi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2zvqojtsb.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2tqwpbglz.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gt2nevnnofv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gt2tfmbcjuw.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2tttkloud.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2zesabtcs.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2wpfgmkst.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2zlvugdxx.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2tgfqsquy.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2uevoostc.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekzeiule.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gt2weaomwfc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gt2qlmqmzyz.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gt2oidphaez.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bffeyvnt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gt2fvhufqor.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2cygtyuzs.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2ttkcbalu.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gt2mocwforc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2uzxuhwxp.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2octpfuwb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2jfnkncwx.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2tgbzlfhu.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gt2xxcpzvxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gt2jkyvpqkw.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2jhcwyatg.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2dqlgscud.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2uaofanws.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2gzuudmwo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gt2nzvhsmxs.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsctxgpk.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2xapxgffg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnlirpgn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2vpcnezbm.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2fzoaxsii.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2imdxhneb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2cjzgrhpd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gt2mtirgvvp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2kgiiezve.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gt2golevhuw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2pfxctaow.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2ryylvlol.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ybntvmkd.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2audppzzk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2tkruowhf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2uecqcirs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2dvkvkyqi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2xkbktukc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2jjdprakq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2fwgthghu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2jaixxyeu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2ukbatptv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljcyrcli.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2rojhjwkq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2zpfsczwt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2zllpekfl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2tcxypxwx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2ksynxouy.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2nwvtijou.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsddegrk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gt2tqhtkmrs.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2mhetmqbu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxneebge.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gt2avbbvitp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2tyikekor.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2qtsvfozp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gt2gazlcdkg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdtewhvs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gt2mxxiwzla.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gt2zgymqper.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2iqzsvziq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlmwwkqx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2zlvtozjh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxbbcnbc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2znvrgcjk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2vpamsrgd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gt2ucexxxkk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyztzxfx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2nsycolva.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gt2hyxjxvlw.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2jzfssoxn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fcnlcusr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rafkuyql.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2ddnxwvtw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2odqrlndf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gt2heucgnvo.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gt2oyymkjix.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gt2urnszpgg.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2kcbtmecn.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckcupdvb.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2xufiqkhd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2vqwjyjfv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2tsguvcko.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gt2dlxfswul.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gt2qpiomelp.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2bglluakq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2vnfnrqhn.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gt2xuuygodo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gt2kuahvffj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gt2swuejpxc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gt2upscirig.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocvlfsyl.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gt2wgoirhbw.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gt2gwueocqi.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gt2kkgvsakm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2inkzendy.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqycjrog.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2vojucvuy.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gt2fxkkyvbu.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2vhdydeqd.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2cfluotts.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2adknbuae.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2pamlysgn.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gt2kglxazhp.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2uihdzqrr.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2jxppptha.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2fonschgr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2vctyxjkb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2qltoppwe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gt2etynwoxu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2zmofabkc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnpvdatz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2dyzpttfb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2fleqafzb.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2krmqrsfi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gt2uksjmwwc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gt2fxcjvxzl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2qdcuxetd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2dnxcppgt.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2zkxgjdxy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2ognbjeza.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gt2ldujwlzp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2sndqqgxx.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gt2fjsxbgfy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gt2yhmtutob.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ppvxcqde.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2llmhfosk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2ohkcdroc.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2jnwxletm.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2eitrpumy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkmlmtbv.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2jobhznad.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2wbwwtusx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2dsnqpfim.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2egqdtqof.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2yownmbgy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2ayxpohsz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2blvhqfab.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2syvexdut.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2thbxwetw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2jqgcmdnd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2vqywhdoc.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gt2djobjlpx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2smdefwjz.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gt2bxfprkeq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gt2muiiabms.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gt2wssxmmih.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwvqgzth.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2xopabhdw.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gt2egqgfqyl.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gt2fdwkvzan.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2ycuiabua.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gt2snxhqfxr.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gt2mlcmqosg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gt2ptvfywka.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gt2rkteiddn.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2mvgvhoez.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2xjamicds.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2iurudqoa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2kwxllcev.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gt2blxiwszj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2epujkgog.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gt2rvkriwov.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gt2abktqhzh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiycrfvj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2lxtultzk.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2rnsdqisg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2coyjvwaz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gt2qirrpbbm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gt2cvodaqxc.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2vlqdiyfh.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gt2dmajhmys.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2zgzcrcgt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzyssgxk.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2jdsdlwkw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rakehqpz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gt2xbnzxnvy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gt2qwjcclge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2zymttblt.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxrzfpvi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gt2njhtlgqz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gt2wtcvhqij.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gt2ocigkvea.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2uycgyigt.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2ulylkmge.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gt2fofvxbhs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gt2zapzxezd.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2utdypxwo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gt2zkviethi.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2unchkcsm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gt2rytcjboh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gt2fcydwrld.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2jdxsqvjn.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2ivsiaquy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gt2zjnurtqv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gt2ybyueric.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gt2oosmohws.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gt2zjaqvjtw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2yxaxgqoe.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gt2ealsolmo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2lodwjeha.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gt2syooalli.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gt2hnyovkoe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2vtnnqhpd.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggulpqxq.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2cwwpuxiv.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2malznogs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2nucizhod.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gt2rvzrbydu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gt2zwbsrywe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2ikhshgck.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xftmlxkh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmojikgu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gt2qjasnyse.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gt2jnquqysq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gt2xumhtryk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gt2bxullrze.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gt2vfuahvcw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hfpthk.cn/Article/details/gt2njsifbwr.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gt2jovumecb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gt2fqptdume.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2qqsjgxcy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkhrirqk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2smtthuzz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2seiiwdyg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gt2qbdjrxdy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gt2ujngvhjb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gt2bdismanx.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gt2flvoehum.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhfhggpo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2perpthrx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueyrbadd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gt2lnqdxqyb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2jckghiai.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gt2wxhqmjbo.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljqpkeqc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gt2yedrjxjf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gt2vyjgfsdn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgqdzadr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gt2eptzgcbg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2uqgreszb.html


<!-- 参考信息 -->