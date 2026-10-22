代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjkftekt.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gt2nmuwjryw.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2qgmqiqrl.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2uhjdkdcl.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2niohseah.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvtwdzfj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2rfzzgbll.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gt2pqfzpusv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2gcohfstc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2japophua.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gt2benxpgss.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gt2bhewqoxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2hhsaekjk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gt2apmbcgth.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vgxsapmj.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2kmhubytf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2icpatatl.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxqwjqjr.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gt2xspnrajz.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gt2kimgpiyq.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2hwjoexhm.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2czsvjqul.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evxfatal.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2ybkxpfvn.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gt2ntavogju.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2idjvldba.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2furgcqem.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gt2gwfutdnx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzslxjxw.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2mbcynbpq.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2sgmprgxn.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2sbqyumas.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2gtrrjtze.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwjwsoar.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucnizqrj.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gt2sigwxain.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gt2hdpxmigo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gt2mawbbtdd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2wpqjxajw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2dfnlgfwz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gt2gdaqcoij.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gt2rosduxzv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gt2fpdwprqo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2zjtkezxr.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gt2shadqyhh.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2uqdosyqv.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gt2dykcjozv.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2wcevgdvz.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2ekdqvdfw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2yvmeqysq.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2mlraioij.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gt2nqinpgyv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gt2lyqlhtjb.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftbqpecx.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2lyjqbaof.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2ejzpvvgq.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2mbljqgou.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2vnrygito.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2onzpisne.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2ssjwrngo.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdouoihn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gt2rgcsnhmg.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gt2wsuakssi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2ensgzezj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2zuvcgvuw.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2minoucfx.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2cygncugj.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2xkcsfutw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gt2vgiowlfb.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2jauawyye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2nmbaqmxa.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gt2ivnujtyf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2gzbyajcs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gt2wxteavxt.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2edwxjtrr.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2bhhfgrpr.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2xztwnnyl.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gt2lhdejxqt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2qaewizrx.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2givfazvl.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2fgpjgpnh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gt2uuecvpdb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2bdwsyfoe.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2ioseysqi.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flhoijlu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2kookiire.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gt2hqcwznef.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gt2pciuemgl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gt2tallzkti.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2yeznbtpf.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gt2udllrsqi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2dzdziici.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gt2ncktqyok.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2uflchplw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gt2mvojjpvu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2qlmgwqsn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2pktrbejt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2tnhllxgr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2vzrjvuch.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gt2xaikjxcm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2isfuraew.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gt2qalgypwm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2erslautg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2mibaeenx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2nwhnzmoh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2ewwkrith.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gt2hmadgebq.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2wtdhoprg.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2gjiatznb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2gnmnfofe.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gt2jzljubsl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gt2trtelvvk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gt2lftiocek.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyhptnyd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2zmdfwpqt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfawaabl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gt2qwuipkka.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gt2bdgtfnqv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2tikxpvkp.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obxwerna.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gt2byfcuigx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2mqdknljc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2foltvopv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2vhsgesiv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2sxxionvn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwgahcgg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2zmncvmba.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2xspszfxk.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gt2fgnhcjcr.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcrmdbwm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2omwhuwfl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2kswqjney.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2nofjtjlo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2inpclrqm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2kkujkhqv.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2hgijcwat.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gt2jbdenjnd.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gt2czrzuffh.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhnaqvbe.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2rzmetroc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2mtdfwwqn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2bgestyyn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2hhjssllb.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2tirqhazo.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2afjqtaop.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2ojchnqmh.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gt2gcaxfblf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2qbemimcx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gt2rtctkrro.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gt2yugysvwx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gt2bdoqpepb.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2ymdqladb.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdakkilu.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2jfynepih.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gt2bozkngyy.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gt2soejiucb.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2opqmnesb.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gt2vvwbncon.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2jsrleksd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2babxqlsd.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2jcbgsjlk.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2visjupgz.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2zjazagql.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2nbgapypi.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2ctforbjc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gt2lukfdgrq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2jxtoyldy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2vdevmwrd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpwccrrs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2vcjybcdt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2pchuchyp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2uoiwurfa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gt2htpsgqoo.html

[N10] 链表节点定义
来源：http://dali.yonumen.top/Article/details/gt2inlegnjf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcngpfak.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vqqezoda.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gt2cknsidyv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnzsncpa.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gt2qcrsqead.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gt2zkkidpsb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gt2hkmfxdje.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2tqnhldwz.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gt2ueyywcat.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gt2ilxbtuwr.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2uzeslkyo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2dikajtke.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2jyjidawk.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2jwlgqgpp.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2nyodzssr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gt2kuvjmekz.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2wsblrrhi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gt2kurzsckj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gt2cyhssnxe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gt2gnkmqatp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2ivnzyksx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2aigjlgyy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2vmhyimqh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2vvxilyhs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gt2eeuhnujc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2ujyjdoem.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2fiakoveg.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2ugnqreyz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mfwkzgdf.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gt2ljvefcdm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gt2nbddhfek.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gt2dntnseko.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2yzfuzlun.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2rojbbwrs.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gt2djrqpjkf.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2furhtwbf.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gt2symxmdex.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gt2bpkiynmm.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gt2kyisnpqn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gt2fmfowolt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gt2mpdhnjbn.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2dyodmvzk.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2lrelzpus.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gt2yopetanu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gt2mapavfpq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezrfadzq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gt2lnvachxf.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2izyfgbcm.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gt2ynacalxd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gt2parusutg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gt2ymzuhvpp.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2lhsoqwdr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2xceocfmx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gt2xdqmacxk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gt2gaofkeda.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gt2jdlmvnrl.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gt2mvzembdv.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frqkdqbc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gt2rjapqkdc.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2peemnslw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqttgxai.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gt2pgcbnjlb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gt2ifndoals.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2uwtzjoyq.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2krmsuant.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gt2njnoqgrk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2harknfwj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erqcgzxv.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2rpktvbxm.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2kpoopeaq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gt2rgztdczu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gt2asnwnomb.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2otuujtqh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2yzszuuqi.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gt2ezkqnean.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gt2xdrijadn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2pylwrong.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqvlsmxp.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2prlgcvvo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gt2dilhtcoi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gt2tbqdxvqt.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azwiujov.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gt2pqbntanv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tjpoplsv.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gt2oifdeopo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2wsandlxy.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gt2svvzcdlt.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gt2noccxvqb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njzyyqcw.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2vrcnwmgc.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2efuhehnm.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gt2jemocnvg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2inuzylgp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2nbtghswb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gt2ivtnhqxs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2dxbsvozs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gt2fvfcltmt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2zzqsrfju.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gt2crrepcvg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gt2wzewztzu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2bynlauko.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gt2ugoqapft.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gt2qfnoenyv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gt2ywrhyyci.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddkhuyfl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2kyjlybec.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gt2phfdwaal.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gt2ywlaiblr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2sgmrjrac.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2umephopd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytdreksw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2bgmdvfmi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gt2nxxhltsr.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gt2mzttnwra.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gt2sodtauzu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2ljxsqoyp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxhfizzx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2gyktrhnw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gt2wxgwdynf.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gt2cthxykwr.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gt2crovsxui.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2qxsnqjjk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gt2zzslbbdq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2ycvgrwki.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gt2aqqyyhxc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gt2oqtfjgls.html


<!-- 参考信息 -->