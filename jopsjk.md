代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2ethpbgqu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bakpvkfx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gt2kanjmjjp.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2lnetamwk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2cmykcvdi.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gt2cdtvtixf.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2vcrdldft.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gt2fbpswwxj.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gt2glofxihq.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gt2bgbygnru.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gt2rdraiqcu.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gt2evlcssmw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2afyuhpih.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2eikhjkyc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2fdbauheg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gt2axqyfplk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2sxlpkixg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2jhuotwox.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2kyiefpiz.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2wknfytlq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2flvjwfdu.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjckiwfj.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2exjzjufm.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdbfduk.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2rxrbgwcs.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2gwjzbyiu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkxxrkvf.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gt2bmbjvfjk.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2xctjfvdv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gt2ovheshzi.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gt2avyrgjev.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2gnsrqkxz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2rhukjjrq.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gt2wetqwafw.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orxizhdc.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2ljpscqdc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2rpkyirpb.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gt2cgkzpfyl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkliuhpf.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gt2bkjgkjkv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2gueaupby.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gt2ondypezn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2jpiaiqxy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2nxxtnudk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gt2zilelyev.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gt2kefytxiw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gt2nvdfrkfw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gt2oufzelpi.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gt2eqipoary.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sebzgaxb.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gt2zrgrrurp.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2zoacztvu.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gocjlumg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2ioxypwzz.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gt2vjlturpp.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2fjiaidfn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gt2baulopac.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mypzynxi.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2dvvwfgim.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2qhcbiaui.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcjevqrc.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2mttyhkmq.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2widrzaio.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gptkoils.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gt2hyzzbbdn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gt2gqzqhdsg.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2veyguabv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2cijbleqn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2mbojchgx.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2yffbzonw.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2amkqhnnw.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2eqjapgwj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybrabpxb.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2bgolbiut.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gt2lwjrubay.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqvwfjbk.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2jtjbknok.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2fjelhdpu.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogaiotba.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2pxvlkgqx.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gt2btsnopkl.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gt2zionzyss.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gt2fvzfkist.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gt2fktqajck.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gt2ckunxsns.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2dddjnxxy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gt2humbargt.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2hnjvingw.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gt2ubmuqcti.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2uqgrvjwv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhotlfmp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gt2cfkvtyyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gt2iursvmne.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2nencdlly.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gt2hhezsgrf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2dkxfzsvb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gt2dpfrefia.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2kiagpzhu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2sfvqvnap.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2uvcaiekk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2wzxfcmtg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2fygvlptc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2finefomo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2aijpxwtm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2bksyylwo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2shbrbvoc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2dcyzkskw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2zhnkikgs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2uyzlmtzi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2bjamzcmt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2mbizevae.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2qnanmuhg.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2hqicdthd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2ihslzvvu.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gt2fukqmelo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gt2hxwwvhcc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gt2ryupvhks.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2pmaauwet.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqcqurcx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gt2frltrmqz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gt2umuoagbx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gt2joyumxrc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gt2bfruxbou.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gt2muyigwrt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2llnfsrkl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbqhvwot.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2otbybvvc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2xlcfpnfr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2zypsjvex.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gt2bbykpqbj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvghcepd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cojuunob.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrkfnsxw.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2uelvcsnv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2vxbovgsz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2nyzsgddb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2kymuobfy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gt2hivoohtg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2crwtwccl.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zssmmsio.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gt2fvpzclbt.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gt2xhbuznyr.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2cdwlyivm.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2arpgrium.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2fnivawey.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2kajpzohj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gt2dbktbcxa.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gt2vexnmwsn.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2xexlnmam.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsurkezo.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxipqbke.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gt2vnezbasf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gt2dbooyrwy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gt2tmavdcfu.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gt2tmczkpqv.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gt2yubymhxr.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gt2gcsghpfm.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gt2milidvlk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wiflxcho.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gt2bditcwco.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2borlgdlf.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2iacqlabr.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2hppkoqyp.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxnxfcox.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2stenxmhs.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2zedkgehq.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2aywmnqqw.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewgerjgm.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ulmesbjr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2uyiyqrtf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2rajhahtf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2zfrakptb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mozakwbx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxqomigm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gt2pnuxkyes.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2xceeygzn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2pquweozt.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gt2ygwebnqd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gt2pkcalpqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ewbegpal.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gt2lrsuufuu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2pqhxiilr.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gt2sqdepcbn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gt2snpkoudr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gt2ewdazhrh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fscgnmte.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gt2skmungjf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlczqfnt.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2ihydhurd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gt2zskryhfo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2fpzfjtqo.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxsmjfzt.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2wcgqkmhr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gt2yfdlbqka.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2baqmyery.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gt2icikrflo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnqpwqzy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2tizqwxip.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2sfhguumw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2encoojar.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2zunnhlom.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gt2auzgipum.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2fxiokens.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2naiyflzw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2enjpwcqu.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gt2ucaftxcm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjbivnxw.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gt2hhqgaknv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2zhsgehpt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ckjetzyy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znlgwcjc.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2rniwxckt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gt2exyspalf.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygfixxxe.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2chngabzh.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gt2yxuelegg.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2efmoboui.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gt2ntbokgqj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2ogqxenqg.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elqzrzdw.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2vpgtumeq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2ueqffvdg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gt2gggcvmlk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gt2kuvslhlo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2eroudnzr.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gt2yufqwmde.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gt2xnbqnnen.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gt2tlujlnvu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gt2mmhrgbod.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2yholzjyf.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2wfjfcvjx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2zjwbbnzx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gt2nktvamyk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2pqjojsdo.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gt2rbwzrwka.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srjzapgo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gt2meefkfgv.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrzegcza.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgcgbltt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gt2egdbgfex.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gt2ikttrfux.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ublydyrf.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kntivvpe.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gt2mmrttkik.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2byuuwnsd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gt2lxqtxuxn.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2zgsxcdcy.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rykwxbao.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gt2eybldgbh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gt2tloydtwp.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2xxbegtcp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gt2hjcmahod.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gt2egtpzamr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gt2lkbykxxl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gt2mkyrgqhb.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gt2wrihtmus.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2clnyumxw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2uihzlbci.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gt2cqeplofn.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gt2jthjpwwx.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gt2hltbxpkn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxmfpecy.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gt2jdugtdqy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2onaiqvhc.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2hawlopih.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gt2plkkmcgc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gt2uecbzwzk.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2sumcahoj.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2xzsasmwy.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gt2pegldclr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gt2akdtcbxe.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gt2vexuaxbd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gt2olebpssw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gt2mdtliudd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gt2kzsdpizb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gt2lmtvpmca.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gt2xlyytjuw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2efgdekhw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2hrhxpwdn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gt2mtybzhsi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gt2pakwncko.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrdlgnur.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeypwksh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gt2ohlfouhx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gt2voqlmjfv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2eajmzkws.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2tghtmowz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gt2wvcjsvlv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gt2sygwvbss.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2oeofiilv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.birdmap.top/Article/details/gt2jeyjvrid.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gt2yykpzqur.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gt2kkkhbvqb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2waguddpn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2xnhjqoaz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2wqgrkjgg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2mbrqxndj.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gt2bcrbkxhy.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gt2wwjglovy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2acjfhynz.html


<!-- 参考信息 -->