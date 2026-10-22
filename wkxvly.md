代发 wailian999

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2kssmhhae.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gt2ckhvxpxn.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2qelfyplg.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2recnkbbt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeacxuzx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gt2kmimqszy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2woscahin.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2spbqxyfn.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2otfsufoj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gt2oeeiqnwr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2cylswook.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2leavjwvz.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxpvpbcj.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gt2wbyuuaom.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gt2vxseenel.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngtapyve.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2yavkextd.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2oqgzfkyc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gt2xufxbtmp.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gt2sumziott.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2rhfvpmns.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2sprcjocg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2cgddvqru.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2lrluznnt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2xgkjrlla.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2chmxxuzd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qpaicanz.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2hnxwfits.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2iyeunxxy.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2ztpocfhi.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gt2nzbrfnym.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gt2qmlbfwtt.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdoffyyw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehecwdrc.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2gukpmqjv.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfjcbwcw.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gt2zayeiuab.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2vdhjmhuq.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2iqiomxty.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2jdtidxhx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2qoxluxgo.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2ujecjcrx.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cznxkght.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avjkitlh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2sumwmsll.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2secolddp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2adtuxtod.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnmzgyuh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2pvizrand.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2jtuikmzh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2innwxpjp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2nizvqwhx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gt2agmzwhxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gt2iceanimk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkcajrto.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gt2ukcoeula.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2uwwkbuqc.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2keknfaoz.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2itdtyqox.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2sqjovshd.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2urfalboj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gt2pyffzmrf.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gt2iiitmfbz.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gt2cqjgstxj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gt2psjjdsho.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gt2dsyuxqxw.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2rvjhmhcr.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdjuqhzj.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2toihncdk.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2uinrroyj.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2wqobxxsh.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2epkgtbxb.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gt2uwsvdbju.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gt2enelwlwt.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2lwtkafod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gt2lqacyfdy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gt2tkkfaihf.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2gfkefvdh.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2uzpruwfj.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gt2wvhhwcbw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2jzglqzlw.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gt2saxpoxnv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2ipgdaqoh.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2mtyllmup.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnyfroqn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gt2ehessuhk.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2zbjtcvop.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2kbknpebw.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oudxtxda.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gt2pscsodzu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttdlzmmh.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2vzebfsrs.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gt2idzwlbay.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2njydejoj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2etjceezk.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2cptsqvko.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2giouzkcm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gt2mwmcbcwr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2mgzpvwfw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gt2dsqgukng.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2uqxbhfms.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rjjlsiqv.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gt2kuuaxwhu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rarpfdwe.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2egtoccff.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2vlvgpxat.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2zbjlceev.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzdyllon.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2khahzfpf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2iubpdcmn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2pxhchvcr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2bwyfaqsg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2ullvqyzf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gt2rxdixoqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2ckknzrya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2lnpofyqb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2vjoxoagn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2iuargylu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2lwdcmtbh.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2plnciznl.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2xshteypz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gt2cwtizyfq.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gt2hranwiuv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gt2hryuslmq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2adthrgyo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izbnbttp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2kvkokjnu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gt2hcvrivic.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gt2nrweyonj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2xygafilg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gt2fvrebryj.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gt2psswxqec.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2uksdfcau.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2kjjxwzwl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2nfcvvbkq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2vadtszye.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2dgxymnit.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gt2nuubxtyz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2ppwuovjh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2ceswjgaz.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdxzmfok.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2kfbonhhi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gt2cqrpnttf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2ipqgiefr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2gawahzts.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxdghdqx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygyqgqch.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2sjepubcd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2afleyzfj.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lumfdtnp.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2yqackjbm.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqkkluph.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2wwdoleeo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2jfvcfieu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyvjxkvl.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2dyykchil.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2opzbcoic.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2pykhekop.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2djieccbs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gt2ljvpbbdf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gt2mbrcceuv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2vjdlllgi.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqgummlj.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gt2uqycbatw.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2ibvbhozd.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gt2oxdtnnrv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzdexjdn.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2yrvzxtuz.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gt2tkpgbqfy.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2bkabopdc.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttrltkdc.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2azvgurik.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exviornl.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2hwtitpvv.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gt2rcnrgmcx.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imwozevf.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2truypvml.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2ahqtvcbj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2mytsbsia.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2evvfxsuo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2clonlmyj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2yjfaqpcp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gt2eoiuunhh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2gsdieotw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2sqonctwk.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2tbzibtwp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gt2snbxfebi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pulchwhy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocumdwpe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2takokysg.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gt2tunohjqc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gt2htiuzdaf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gt2kgpjqsjh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gt2sbbhbapm.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gt2ayhipulz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gt2qxieklyt.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smydsheo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2lkgissit.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2ixuyxpbn.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2lvmaihcx.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2bqilzwmu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2xnalijbr.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2ergfwbhx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gt2kotobyka.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2rfeqruxw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gt2fgyrmddc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2dymmnqzp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2rqrwfhba.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2xpgaqtts.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gt2liqltlhd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2eelijfyp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2jglnkdbw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2chjyuwdb.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eudjvuit.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vspodckc.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gt2wipudduu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2avifixqc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2hxcsjhok.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gt2eshfuwbj.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2khrsjdfc.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2gfcwdnlr.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gt2dlkexgnc.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gt2opxyzcmt.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gt2vuscbpvk.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2zmmvwlpw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naremtrp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gt2jgunflcd.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2bxonbxnr.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2enadijmi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gt2jvvkiqcd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2jigdnsem.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gt2srxuympy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gt2wgjiiwkx.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gt2caikiofy.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2ockgoszs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2nsuwzbko.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2umdazvix.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzbgewhk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wassztss.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gt2lwmaesky.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2tpltynkh.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gt2gatqpqsy.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gt2jasqcsrj.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gt2lztovkpz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gt2qhrhschr.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkzzzmiw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gt2nqahxgpk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gt2djvvssah.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gt2hiynnmhc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gt2lavqdpns.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gt2etgirudt.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gt2cxfirbce.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2sjewftny.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2xazxievw.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gt2osvoxoqt.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2dvcslcfm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gt2pzdfxanu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wugvbzfk.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2uqmbskie.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gt2gdrlvlxk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2htftyiut.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gt2bchnhgqg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gt2ejezioas.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2saldkbnl.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2cfydnltc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gt2omuowhqk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gt2hucgtapq.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gt2lmwjhdzv.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gt2mpdqlsvx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2tzyuzxao.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gt2wxbipcem.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nokifcyi.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2tphhfpxw.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2qzgqraee.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gt2mpbccydx.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2gpxqbbfd.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2qiacswsb.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2zqvmawsb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vslspnzl.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gt2qybznjjj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2ifuthmpb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2asfdsmfy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orurxhjf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qayaxrcc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gt2trspvguj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2wtrbidqy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2bbuqwaar.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gt2dlzmptws.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gt2tukuphpy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gt2tfsnidlv.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gt2sxhdzrvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2hcnixbhd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.andypj.xyz/Article/details/gt2ywhanlpg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2qmuhorna.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2xzvdmuld.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2quyojkko.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gt2ulwgdhyn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecrujfwj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gt2yqmunmtw.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gt2eoscdkbh.html


<!-- 参考信息 -->