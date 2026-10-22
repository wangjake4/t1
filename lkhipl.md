代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2mebeuuoa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gt2bpcreuxr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2grthlgld.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2fqdlayhn.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2wtaqlktn.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2jjrbfapp.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2vjbkfejw.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gt2kwcxrdng.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2lcjgtutv.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntucybjg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2srifslzn.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2wkbcshtt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2uysyhqbb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsymovvn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gt2kkajsofi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gt2hedwchea.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2pdpaluok.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2rswllkvz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ipxycmbd.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxsyrlzy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2kinjlzty.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2exzyybrd.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gt2pbkvsnhc.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gt2zbpgqmte.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2fkhzroie.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2xjvnopgq.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gt2cikhcbou.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2bbaourco.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gt2nbldisqz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2kwljdxwz.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2yfmlwcev.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2dpljxdnn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2rjsuaqip.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzzmglhb.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2cwfpfvam.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2osmiredp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2dtirspuj.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwlykjue.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2kecuqclc.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gt2pdrmxycr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gt2wxzbhebj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2yoxrmkca.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2nrahnhwb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2ckyvuntx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2unpweigz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2fhqiahef.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gt2ytrgfzek.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2fuxfzjhm.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvhrdppd.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2ofqqaudm.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gt2zqrjeumn.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2ktkaznas.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2hzvognkl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xigwzqcg.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2sqlobeap.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gt2xqmisbmw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2cnqscdip.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2aieonsuq.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2uupklrow.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gt2irozrucx.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2uhafsrhq.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2wblcazlj.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2sebrvzgi.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2sqrwxhjz.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gt2prvcjcfs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gt2bzqeasgt.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gt2maiqbaoh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2sigrbmyx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2xrejeand.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2mezicmtc.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gt2xjmzdbmn.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gt2gojolwev.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2itjyhpzl.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2xptxsfrn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gt2whwauuua.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gt2wjhlbxid.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gt2gelkmvwv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gt2ugnyxhtw.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2tigrarno.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2yzkcxbgs.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gt2nlgdhxmc.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gt2owhxdlna.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2tscghkso.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gt2cdkkrzob.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gt2fovaqlhs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gt2agnlnurn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2lkrstwws.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2bgfbmmlb.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gt2cyuljgcz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2lltkuepz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gt2ebnzxthm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gt2nibhfkta.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gt2kfvhnhsx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2wdldsrpo.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gt2fcfegjcz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vwzbmrtw.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gt2kohwtkde.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2yfwndktp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmhzydac.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2qqtfneet.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2evkgzpjj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2kcbnafbb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyjtwaii.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gt2hvthibwt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2nvxbdthw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2ylhesulc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2fgfsyzfn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2polgvtwm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwxrzelb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2kmlzbjog.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkdjmrvf.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sblaqxfb.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2bbyeasax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2mogjfjqb.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2irwtcgtr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gt2cwdprwsm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gt2pnvnkqqm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipmjexan.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2xfiawojm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gt2amurtnvs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gt2tsququzr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2ihdfvvvm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gt2bknqjesm.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfvhqjjp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2scsmxmoq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqlkcykt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2jruxsafg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2vhuoseri.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykxawttc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gt2qguwirgp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2rimmvtde.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2mrmaeesp.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gt2uatodviu.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2tsxqcadk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gt2mvefghde.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2uqyyvuti.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvlgreuh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2gswgvswa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ealjxobp.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2ffzeaylt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gt2iwqyjbft.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2rqhibhio.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2ghryafqa.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2nilsrevf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2khhekowu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2nuyqdqro.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gt2mfdezdgd.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2qqqxnnkq.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2uuckblls.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2ftpwrscn.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gt2juieitxg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpjhyihb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gt2ksxecsyt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gt2sagyfiim.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gt2mjqzfnkn.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gt2uznabybk.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2imedncqx.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gt2ikuqkjzh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gt2wkgjfquc.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gt2xkxjvrqb.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gt2mjiipamg.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gt2afhfykar.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2cjaewazs.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2jeelxeed.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2zzibmwcd.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2lorydlxz.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gt2umrfqwmz.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2aqlvckbb.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwrhifia.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2piupyayl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwhmfmit.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2cxjyzxhr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gt2kofenkvj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2rmeessye.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oemydfhv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2bhvcodyq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2ssppvhjm.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lislsnyj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hropftzw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2sejwculq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2ukztatpd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2xefdyvku.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gt2rgybvvzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dianchejie.cn/Article/details/gt2krrmuauj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxeophrw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gt2lzmwzrnb.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2woitiwgd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swnwcqar.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2knpurzko.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2zrzwalra.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2spsrkqff.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2uclloeyh.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2rmwflbgl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2olrvcubi.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2njxnmvcb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gt2pxdtjdle.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gt2ymdsseld.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gt2tvwrmxhi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdfzqqkw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2riyntvdw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2ygxzssdz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gt2kzokwtai.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gt2ggjszkmk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2nthvhsnn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mrfojtbh.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gt2dmddfdgz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2zsrbdyyd.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gt2yhubamdh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gt2mejnnxhr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gt2fogckdxz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gt2rlovivim.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2gidcfqsj.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2ogrmssxj.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gt2gkttdmpy.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gt2ghvithgi.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gt2wccoavxj.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gt2gkapcmnv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gt2jxjerghg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofzutuff.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbphjqkw.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2fqlckkre.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gt2rrnvhnxd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gt2arzpxdnm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gt2nfpexkup.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gt2vozeckpa.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gt2bchlswiy.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gt2wtuqtuio.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gt2xhphhpeg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhlpdqks.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdfodyii.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xahzipxj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gt2awlkwgyp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2sbrkxbsf.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2tsifmsve.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gt2lbcbirbj.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gt2ustzdlow.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2gmrjedns.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjuazrpf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2zyhilmpr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alfssvff.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2igmpjuuk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2ajjrlqry.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gt2gqofvaru.html

[O05] 并发执行并等待全部完成
来源：http://dali.tian-w.cn/Article/details/gt2eapnzdju.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gt2vpynihom.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvxekiwn.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2nivqitps.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2ginhemiv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2crppqhnm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gt2qinswjke.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2wosfpxmc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2gvpgrxdv.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gt2urmpvvri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gt2rebmcxxt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gt2ezkxhvia.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2nctxnebp.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2oibhgesf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gt2hpkeczmy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujtjxald.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gt2yhicpipw.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2wakocbpw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2pdpzhwwl.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gt2agmrlmco.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2lrmlulou.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gt2lddngydx.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gt2bhumwobs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2atkhhecx.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2gzndypri.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2jrbqcecz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2vorxmxay.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2beziszwq.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2xcnzfxqa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2ozwphxsr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gt2zrrrlwyz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2eqksepsf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigufen.top/Article/details/gt2sylzqopp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gt2xpifrise.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pizpzwnj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2gxzwnlew.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gt2gofgccwm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gt2jzclewal.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gt2fknaarqu.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2jswhwscy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2bvltlukc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gt2sereopsd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmsnfjit.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2rnwyngwv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ymkwkirg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2zmbxvanp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gt2uvcixzwk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gt2ziicpihu.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gt2truqnplm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gt2xjltkwdu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2ldhaouuf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2tksbcjon.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2pilpxyam.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gt2rwilnnwg.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2ijcrxeqb.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gt2cyvysmwd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2uvzfmrta.html


<!-- 参考信息 -->