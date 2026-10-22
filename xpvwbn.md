代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2xotxpuzy.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxzvdrfj.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2gwejbfoa.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2mrivjxmb.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2uqrqfike.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhdrrvze.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdvitjk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gt2qnpfwwku.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2umkcnapd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2jzqpyfke.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gt2ymzvgvhe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2phdxsvjw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2wlezziwz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxlcapqf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2uckskddz.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2sybfdfgy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2psosvfkf.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2iiisecsk.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gt2mxyiolzx.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2tcjkvewf.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2eygbwakp.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2xvjvzdgn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyrsvylc.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2vqahsdca.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxdqrzwl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2cjnxrdsl.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2cchfnmex.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2nyrngzuu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2yxbwwicy.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2hfbpufzi.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2gygsipwr.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2dfdlcxew.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnukhhzv.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gt2lbzknlxe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2bpcletst.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2nwnsmxiq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gt2psjlnxcu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2enqqjsko.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2jrmkpmhy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2lgtvlfde.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpfcpgvo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gt2zoybzrpm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gt2hwtwllbb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gt2dcystwab.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gt2avvrjwos.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2umqtncpx.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gt2pmqnpwnq.html

JS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2swshbivn.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nejgrdgc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gt2hrszyfwx.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gt2dsulticn.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gt2ojvkebnp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gt2nlcqxcws.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gt2kjdideqe.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2xiqpkkhz.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2lmihfiok.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2vggfafpl.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nciuonwl.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2jzxpnwgj.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2cvoymiug.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2lcfaxopp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gt2cbydfsib.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gt2iryqwaub.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2blcpadxg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gt2vnsfkosu.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zalzrazl.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gt2vctpcuvi.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2hbiscxfz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2fbaeiyjs.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gt2cmocqhkn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2vgorcuiu.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gt2qxboivje.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2oswqrbfk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmbaeohm.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2cqjzlpmw.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmslnumu.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkkjbasl.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gt2bihgdmac.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2zozsbxzy.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gt2bniaehvl.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gt2xkvbmrnf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gt2osvzqkhd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gt2iqgaqgiw.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2zikgseve.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gt2xehitcuu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gt2serfqdzy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2hzutzprx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gt2swxdbnhh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2qsswxozs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2hsrywggn.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2ylkulaib.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2pnkznwzv.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2qkczpcua.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdcoyluu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2zukcenkf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2dtcymrsl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2cqtztmdd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2fgbdugue.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtemcanx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gt2vrdqseyd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikryxhul.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gt2zriseqvb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2umnqiagt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gt2lgqtpsou.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2afabzoft.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2rkbivxqq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gt2zvmjswtn.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2jkctfitr.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2zbgobonq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gt2pdzhdwjg.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbmrmeut.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gt2dsmmutjw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gt2fawmsjjc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2phzvazlw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2mxpjgghx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2ozlxassn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gt2bhbayalo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gt2linxapoj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmakhmu.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2lsrczplp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2lkpqaiou.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2qbcemmbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmeaedgl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2qibhirze.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2rxzbsmlq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwrnlzun.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fchueclo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulkdoqpl.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gt2abskmhdl.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2ebtuhwwm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2hzvripot.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2ongddhxt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2xsozxqet.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvifxsgn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gt2hmahcqgw.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2lbiblehv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2gjorvcuc.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2zgyxqylo.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gt2toxljmbl.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2mjwijauq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2kcubkiyv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2xmsumukv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2vyyztwhq.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uervyqyg.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2vvjcafzx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2lxxmopbn.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gt2hjkeogpx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2faoooxar.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gt2psdrrrot.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gt2efjzxzev.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gt2pelaghql.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2tqfhffbb.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gt2uyhgbitd.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gt2klitukes.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gt2nfomidoi.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gt2vistkgow.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gt2fjzlrmgt.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gt2ikgeaswt.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2ffxbnbsb.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2waptcydm.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2vujwwdpg.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2mdkanwck.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gt2sgoqbhwm.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2xgwuscth.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2glrgqkvl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2zpwlzddt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2atyoqpea.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2kkwxsgcq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gt2wvrmssyl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2mywswcwt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gt2vqlpzslh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebylquco.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gt2hgiauejp.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2doiqfdbh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2zyocveqm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2ghqsdomb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gt2esdceidv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gt2nlyfhyjm.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kypoxvxg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gt2salrndpx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gt2rgqktbyo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2moibmzjq.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gt2ujcwtszm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gt2deigugty.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2nfcsxtjw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqvipnny.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2webotzql.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2kskobhvw.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2znyqjguq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gt2farnquhw.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2zsuogofm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2snldbmgd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gt2ggjgnmqe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gt2bxrnbryi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2iswcqtky.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoyzrnfn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2ywyahxkh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2woahtckf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2qzmsytmt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2srlyprpx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2rntzebpl.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gt2ipvandqr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2crzsjtea.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gt2xpndkkos.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2mxesrpcu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gt2aebfugei.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxlcfkfn.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2rsiuervc.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gt2zldfiycv.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2lvsadfwr.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvjdnucz.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gt2ljyibewa.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gt2fesnpzvs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gt2ofubtbor.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gt2phyvddnd.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2vggjkrdq.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2agnedfxn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2wfcstbks.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gt2frokoulg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gt2vmxxgqav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gt2joddeiak.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnpsswue.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2lnjrketl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfhppwpt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gt2sepbzeqh.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2eklxvdfu.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2iujatyoo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gt2fwmzafun.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2ctyzwfxh.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2iwnxhnep.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gt2zrkvzerx.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gt2wgdrlrer.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gt2cxxwhjsi.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykghgnjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2pvwecpri.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gt2hfksmauc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gt2egmhmtso.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gt2oocxlrvb.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gt2hxpoyvnn.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gt2vlfzhato.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gt2sjlknhwk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gt2jfefqjbd.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgdrwsdw.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2zdwigdcl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gt2zawpiyng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2zujbpqvk.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2fxgmjzzw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gt2widnizco.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxeehrsi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gt2cqhjdgis.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gt2nqgfvwcl.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2vrcgvlrk.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2lskjecjl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2sqbvdoha.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2dvjowhpy.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gt2vrvibazr.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2xtrqkzgs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2zlzwiozo.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwhmfsyo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2opauoefa.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gt2unrpgphl.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gt2lxopgkfd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gt2aazoftnc.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2xwtoghvm.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2oheqdmxb.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gt2ydmhjywb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gt2qfoboymr.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gt2ffdutzpx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gt2drltgdch.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gt2ukyrbrti.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gt2yavnwyuz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gt2ajjvjufh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gt2qxromkjq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtpowukb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdocbyla.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2tjazrywa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gt2tubwuesu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gt2fucseoqq.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2lkvsdsgb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2wxbvojpy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzehxcjp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gt2wejlgeaf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2tlgnlpbq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gt2imfjhkff.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gt2ygdkygiu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hunthhct.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gt2gongtkqf.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gt2zczbgvmi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gt2yduhcrqm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2yjcojekb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2vpfwypay.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2hduhspau.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2nhpxozcg.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gt2vvtkuyjd.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2uylwfjjv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2usmcabqn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gt2serhhdhp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvarviqa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gt2dcuuvvwg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gt2ugsinwug.html


<!-- 参考信息 -->