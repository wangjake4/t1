代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2vchfhwpd.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gt2aynwdrpm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gt2nhosryke.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2xizzracg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2cjresyjv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2nprvkxba.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2riijiwwa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2dhryenxn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2fnlaqzlr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2ikjazyck.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ifchiuvy.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gt2gwlrwzfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbumddo.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gt2tyiwswtx.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gt2eimmpeuf.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2hcgnlbbu.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2nacuvnng.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2zrqumwwd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2xhdtvxyg.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2qodkgcor.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gt2xqaqgbbi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2itxynruk.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2aldigfwl.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2sheavkyd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2neyekmax.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2hmkxsevf.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2sxawehzg.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2hvbpggse.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2gwgjrrjf.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gt2yiiyjhxg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2yaopkwmg.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gt2xoalpgth.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gt2givgpwqp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2ijddxmiq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2ezgovape.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2otkkuhdd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ashydblu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gt2erizgsjn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2qtqjuwwd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxfzqgmb.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gt2ketntgcc.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2mihagmnf.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gt2zngdngot.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ungjuwpp.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2ohaaiawz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gt2fvhkchbg.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gt2vvqfmmos.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2xhplxpfx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gt2micsioor.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gt2kkvyjwbq.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gvybbqtl.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2lryqvgrd.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2bnjqinvw.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyjlbwzu.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2golvlfxm.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2pdznvtde.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gt2hoqynfym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gt2jabjlgbb.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmistzou.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2okvzvqyw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gt2wuejtjmn.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2bwccffss.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2ymbnltyp.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2gsuhnxof.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2jslcxrah.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gt2ziljrpxw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2gvrqedtt.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2matwrqzh.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hemfqeax.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gt2ddosvxau.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gt2emmrqlgp.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2klydzgns.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2nkdwvaas.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gt2pbacakdz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2rztlwvon.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2aklbtnbg.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gt2nmldxwro.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gt2fnifdxkf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gt2aidyaxti.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzjvyeeu.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2ykdhgyws.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gt2vjfimbyt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2rhbvpryb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gt2lsdlbqpd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2lmmyknru.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zimqwhke.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2stqnmfqc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jwziimmn.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gt2ixnoxdtr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpvofuju.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2aupavxpr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkvrweyk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2stjgigss.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2xeplqksj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2otxbbpdl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2uizafziq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2gebretiu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2wloimibb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2zrtloiaj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2spusyzvx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2onlqhhhe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2eufzphnm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwebeokb.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2zabroprp.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzfedvaj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2fgjotxno.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2cvozyjhq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gt2gebcqzff.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gt2tchzjzuo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gt2qlnpnzby.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2awibzfrq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gt2ukltjild.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gt2tgmiuzcf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2ukivktyq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gt2asxmvrnt.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gt2zpjpvhnw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2fvphuazg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2qgzscebh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2muaykksy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2nqzkfyis.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2vghrrjnd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gt2wowuhfab.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2qzziusly.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2usdvebpt.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gt2crzwhcnm.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2zekybdus.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2faxyivwn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yyktjuak.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2xgkjafsn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2clhtrood.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndhvklsf.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gt2fxouyjhj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2pfnnphig.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gt2zcpvgowj.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2imzhqnli.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2lzwnomte.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2owjfwaft.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2thhufdrd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwatrsby.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gt2ovblptmf.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2pialhgbi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2okokrzbm.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2dtuzbbix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gt2bguryywv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2cglnzkmm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gt2aqrvfinh.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gt2vwdtvicr.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gt2jfngjvpq.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gt2hqybqiye.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2nfdaasut.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gt2redgngva.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gt2cxlluwec.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2ivjhrrrh.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gt2iszmnayd.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2peiniand.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2thkavnaa.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2fziratsa.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2cscguwcs.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzynhorm.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2kideofhw.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gt2ayjqwpbu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wofmfrmn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2izpudoya.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2euxrrceb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gt2wmklyyto.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2fftlwmri.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2rfickfqn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2vbbxnmew.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2uwbshrww.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2uguwrqry.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2cgmeyavn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gt2eofubhbs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gt2drdxxytp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gt2aksssixo.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2ocpazbqh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gt2vjmjogrp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gt2hzakkoqt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gt2lqartfiy.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gt2poqsdkle.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2zyesshkv.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnlxnlyc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oimsgmhe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gt2grilykkt.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2wvxihlwy.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2htaxyfyu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrngbwkn.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2jhwdskjj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gt2ajosvgzk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gt2fatqtinq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gt2bfcrgjxb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2jpzntbep.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2dyexcrvp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2akedzaer.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gt2thpruciz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2ssjysgbp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2smcgsjae.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwueogut.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gt2byxagvah.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jahccrtq.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gt2mlzjiker.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2amchnzfy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gt2pintixol.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gt2nkkssftq.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2xdisuxuj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gt2tjnqfcll.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lihuspxd.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gt2zzaztrmr.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2dthwpmiu.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gt2bzyhbtdb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gt2frmlggvu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2zbbdmbhj.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmsuclbw.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2phuxwmek.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gt2gtpiohnx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gt2hrftzsiy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gt2kycbatwu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gt2dbhfeofo.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gt2ifqvofdc.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gt2kqupclar.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gt2htodsnfu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gt2gtobfylt.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2stxumdbe.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2ujhaliab.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gt2fyvfhrpv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gt2wdrfngjj.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2fnxvqtpz.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2aisgingq.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gt2njxaiiio.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gt2sjmrvyvm.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2dvmhksel.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ezdhksum.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2stucnpsr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gt2slvfputo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gt2xbcpbise.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gelhmgrf.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gt2kltfnbcc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gt2almircph.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gt2lobozxiv.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2salcncld.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2hxibppnt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2somgwwpc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gt2jfhqildv.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2oyfszqih.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gt2bkqwzgvw.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2dbvqxexn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gt2phietcxm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2cotpdnbh.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2yymdpccs.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2njdrkgdp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2hyalusab.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agmjapne.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2vapjgrzv.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quradtch.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zcsrgcpq.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gt2gsrfprdr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gkzvgoab.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2wyeknroz.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gt2aoxdmxis.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gt2okzotioi.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2jyhpyvkd.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2ghpuysng.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gt2orwmpddw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gt2kacgoxdz.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gt2sicxoqbk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gt2zrintwij.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2seirgzeh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gt2rkysdjxt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gt2jfhriunp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2yswjleth.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gt2kcfhnaih.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2ebpjwhet.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gt2vrpoxlwr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gt2lrdsptfp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gt2nfpaxdxj.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gt2ojgzazph.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2mqoqmjue.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2avlpvovc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnrnfcb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2tzbaeigm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2loftxlbq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gt2iechkuvc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gt2snkgersw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gt2xqtkpzou.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gt2sxhcrotw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqajgbcl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2sjlnmazn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2gvremrut.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odewiryz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqmmvhaq.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gt2nzeyitmk.html

Ruby: x.length;  x.size
来源：http://dali.316326.xyz/Article/details/gt2bmecazco.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gt2gkumntsj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gt2ahjatgrm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gt2hpmhnare.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gt2hbdehxly.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gt2zzgrrxpk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbgbgaiv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gt2sweyxpjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2uarhdyyi.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gt2ionwigbd.html


<!-- 参考信息 -->