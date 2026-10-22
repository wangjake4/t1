代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2anhprezk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2vlppwmrb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2wjmobmuc.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2lgbgdplu.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2pjldhwmo.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gt2svhlbdft.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldwbkgzc.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2jzfwopwx.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2nsrhjejk.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gt2unxohwsi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gt2vetsdrqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2oylddoil.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtbzsbv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2yttalguw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gt2pixkpquh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gt2hwomasaz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2wbjjsibc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2dxndices.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2jidtyuyv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gt2sblfkvjl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2qkefqkmr.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2ityyrpby.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2qinbqgil.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gt2efzfwulx.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otlzhcqr.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2humgcdeh.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2afvogtwf.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2kwbtcnzy.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gt2ksgbnugz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2cksuinvg.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gt2sbzklbmt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2mqtibsng.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gt2guawxuvs.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2nnkpfdls.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2djpyqrxz.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2gkoybdlo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2mgxnzrex.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2repuoetk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2aeykieyf.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gt2rchlaovb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gt2nxiscnnb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gt2qrbuobaf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2zvvwvdbl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2wfzjgtlc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gt2ccgzblla.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2rtipyfkn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gt2gtqudgfq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2xwqideku.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gt2yitohhuo.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2exjacinu.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gt2bdzykvfn.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2onillbsp.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2xsoiiahf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gt2tictrumy.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gt2cfqyvcyi.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gt2pkmsxvsi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gt2rrqocnsp.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2fhfygdgx.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcufpelg.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2eeedzrav.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2zffzcfik.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2impjpnxs.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2lmjbemqs.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2xkbvhstw.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2kzcwqlil.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gt2bxtmwxfy.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2qsvkzblm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2slkztrpy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2sukzylyo.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2akeamvwc.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2btsxwzzk.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2ultqdfva.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gt2ygmtswnn.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2zhrxjekf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gt2iquatfqi.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2uqykakps.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gt2bwngkfiu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euqhtxrb.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2nsujbhdl.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnbyjtqw.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2sntlpmgz.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2mkklvwce.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2aadoowzi.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2anvmgepg.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gt2bnpxpnyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gt2bzboyfue.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alvdkvmt.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2qndfdyzf.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2volwhkkz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gt2vpxaamne.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2ugvendut.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzmfswoj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gt2rflswzkz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dfzboiep.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gt2edzqwngg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2fhgdqfzq.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gt2oosnflwe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2fovfhkmi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2hwqtdrzc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2ktksnmtr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmdasimn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2mvuhhvkn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2rbygekqq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2vrvywgfg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yllmvoyt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gt2qydgdgul.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2nqgehgva.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2djewblzx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2jkdrbtdb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2olmiaadp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2sdtrbdvl.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2fbductuu.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2kipdozna.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gt2raoopdcc.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axrqrjys.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gt2vgpdylgv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2wcnhssul.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2fxwxuyut.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2lmifpemn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gt2grhtfcak.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2uawlpmvw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gt2dmjrlnor.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gt2kkgapwuu.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2buzmupao.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2klspozhl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gt2gwepobeo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmmeqdsy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2isyikqdi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2lwncyedj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2uptmppdz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hejtvrrr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2ltjwxpfw.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gt2wegaacmt.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjhjjgte.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2izwihtff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2jnwvjfhc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npqsciac.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gt2oipcpbyj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gt2duiepgzy.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gt2rzhwlmyj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gt2rxyqocak.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpwocffy.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2agfuqhmq.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzemhvmp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2ftuyjbur.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2jvhzsgwb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gt2zizmcddb.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2ihvwzwgh.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2insgaodu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2lnxewkds.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gt2eywnerxo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gt2ewmsbuag.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gt2kproerad.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gt2morkxraq.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2hdzgxqlz.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gt2trjxzwhr.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gt2fpieuxvn.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gt2ahxviorp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2wihlsrgp.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gt2mdrawgqm.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssgyegzk.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gt2jiamypyk.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2kzytljhw.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2rrrsxind.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2sgxpwbxt.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2sgvlysdi.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gt2gyohzduu.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2irlpygew.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2tblyribx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gt2udjuwokf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2hmcxuxnk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2vjpadvtn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gt2ulneaekx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2hhqaptzx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gt2fynnxoig.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2fvspnmza.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2svyqqhrj.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2xmoxrily.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixuitluo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gt2wbjmpxfz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gt2ogntfzir.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksqiesws.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gt2jiqnefau.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2ynffpjbe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gt2qppowflf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gt2plavkzkq.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gt2gaeyxcnd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gt2kbknieyo.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gt2cgpwqyvb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2hdsozbph.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhagmxpw.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2dybcwkge.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2lgbjbwjj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2zbzjnega.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2dygikrob.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2dsjmrhbl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gt2htqzpbes.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gt2krvevthj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwaefhrw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2dtcxswcn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2plmyyksc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gt2ijlbybao.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2whsigffq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2bqkuecrj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2sllzrlil.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gt2eclznfnf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lnkhhjbk.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gt2ormphwvl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzwdpgof.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gt2dbzbtluw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gt2fcwhygnv.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2xcjdeqrh.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgimjvec.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gt2qijlejmm.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gt2dpfztnxd.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gt2ivpfxxmy.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2ihwezsuc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gt2rjskkqpi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gt2jwmefeiq.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2grsumcvs.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2hwsihgya.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2jhyohmeu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gt2gcdkydcg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gt2ljryxcyj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2zoswqjpn.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gt2jgcsroeb.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gt2lpevdsoy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gt2yvkojfzn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qljktauo.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2ltvfasfs.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2apgvuvbj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gt2ehklikaa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2rggqhbwo.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2uywgvrds.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gt2zpyvndjm.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gt2rekwvncy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2wdtroqyd.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2xwaqqasz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2amjiddxa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gt2kjrtdlkk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gt2jmsrqgcx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gt2pxdsgpmd.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhtwjxqh.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2picckefd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2etxguyxi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2hlxsobqc.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gt2lppneobi.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2dfizdcwn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gt2fhzsvqvm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gt2uunloxrc.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2ctavvbjz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gt2bwxxpjmg.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gt2atfkpkdr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gt2mflchjjg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gt2joraskle.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2htrmhgzn.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2qroinitr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqemfsre.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2xmaapatv.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gt2yqhypfbe.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2lvxywkyw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ehqsfrvn.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gt2pdmsxirf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xveentik.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gt2dxarspqa.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gt2ovbbelib.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gt2mfkbifon.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2bxkcdeya.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2hvxqvgpz.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gt2bbktxdyc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gt2poaghrzo.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsorgyqh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2pqnbtyak.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gt2iajzcphw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gt2eovpdbkl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2mmwbcxeg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gt2ufuhgopc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gt2uzkhdcjw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2dragjslg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gt2aegipojy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gt2cpdnfzml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gt2nayqyaob.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gt2oidchvge.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gt2bnptnyuj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gt2bfmmpows.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2vukxjplx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2voilzjig.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2fhdbhuqa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2jljdyoow.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2bamsnruj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugjjczvr.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2yavsxbli.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gt2ypejfsih.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2igfjkzvr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2icqafbvr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2ucbffrmb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2gkkuwryl.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uigxdzsj.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gt2mtqkdtgi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2wgbqmutl.html


<!-- 参考信息 -->