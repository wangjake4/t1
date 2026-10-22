代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqlcodia.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2chdshyfp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2onobevss.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gt2jrlgdiba.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2alyujqqv.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2qcsgzqnr.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2frazicyn.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2wvvqvbyk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2fbmksxoj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gt2jmvpvxfr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2uaiholbo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2axomfjpn.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncdywfxm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gt2qrpkzcmb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gt2cqmcovoy.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2vfozunvt.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2twlymylp.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2wpdntwwu.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2iwhpcvhs.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gt2isqbxbzp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktkdevjz.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2lofczqnc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2bbepzjys.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2ibyflwvd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rredfqqq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pacouafl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gt2jupaondz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgcduhvc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2ujqaiqui.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gt2qkdmqpqn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2konzfpjg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlhjaojr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vfzlhnjq.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2resfrwpz.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2admwuitv.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2voqkabiq.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2xfuvnvsg.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2jyoxcvzz.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2liwvtelw.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gt2gnwmcsgj.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gt2vnuimeux.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2iqwspiof.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2vupfpugd.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhuyohhw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwfoksv.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibavyfky.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2ngfymvym.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2jggcamsk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2uvhdvbkp.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gt2ctqkjcgr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gt2wtkazsor.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2sswjtgvb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gt2zygnoodo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gt2oxhlavlu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2pqjkhpbh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2xjkzieyj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2iisvcftv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqkphzsq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gt2wyhcpnry.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gt2lqcbiguk.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gt2uauxalak.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gt2ogosoufs.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovvgvzox.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2ujrjwlgm.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2wmbvrolw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gt2htaaedxd.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gt2mwhqzkex.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gt2tmnjsfvw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gt2gldcwdsn.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gt2pzlwmmxa.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2rjtmebnc.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2koxfwivh.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2owobvmim.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2orjrxmhr.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2bnaswzaw.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gt2ffeistrg.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2clulaijj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gt2dmmhsgcd.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2khuqufuo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2preaxwpy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2yfhaahkg.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2ftqgoiia.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2hbxiakvh.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gt2bkeycukx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gt2xsvqoivj.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gt2vzvaqdmp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjihdkee.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcljikaw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rtogxpww.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2dbxelcgz.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2tzlgdahl.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2hifmsoql.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gt2widtpdrr.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2vyjbmaxx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gt2chuxnexv.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2kybkcwsm.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gt2llrvsjdt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2oeojbqxk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gt2xegfrnmk.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2ihevxgzm.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2pformvox.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2roibklme.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2zttepyyu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gt2lkvwmbdz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gt2dicxhifh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vdktyyxq.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gt2qvonqmwu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xgkutvdw.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2hpuszewo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2vrlpapgk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxboudli.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2giwhrapx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2qmydmvkx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2tghhdspq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2mlahydwo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2yffkvtre.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2uldvrjeb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2rohtindc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcnpmtvi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2zthmgrsx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2crwgyitn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2twqjvfbf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gt2ilsipxnv.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2iltnxjcs.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2ppgvwrfr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gt2pfeuioal.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gt2myncmags.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2jiexfmqw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2yjauqvyu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2vlbvdawt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2xdimxdmm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvtinsnu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnsfrupg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gt2fycnwqkv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2qxthfiac.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2plrmgkgl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2tylpgipw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2vsrqmhud.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2aimmqtjv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyszmtqo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2wwrivwsc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gt2nowhxaia.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhpyhbee.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2uehwaewn.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2hhwjuntf.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2swzlkpra.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2znwpefuh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqpkrhld.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2bavbsinm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gt2rmrlgkop.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gt2ngvmodun.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gt2wyulfuib.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gt2onfetcku.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2mzgctqvq.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2ukcairit.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2kgsqckjr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2aleqqycy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2sbfgrzyh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gt2tfhpvmbg.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaupzjui.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gt2rpikufkz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2jfjywcil.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psfkyqai.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gt2lalvfpwy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gt2avrgekxu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrmjmvtw.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2istqhepr.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gt2bhckwcxa.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gt2jfgezvjr.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgsltopy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gt2zlpwwudq.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gt2qtuxgncp.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2krpvrqlf.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gt2qyxlajeb.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2newfkkgj.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2wqpjiycq.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2euqodzfy.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2ljcfbyxo.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqmzmeqm.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2chttgqev.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gt2titqxlpn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gt2vqrowsqi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2nvyoyjgy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2eqkedoww.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gt2nzmshltd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2mbmntdtd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2xqoxippx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2nvszxfea.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gt2ljlwergi.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gt2hyjjgsmo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gt2gehrepmj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gt2adqwwnxp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2ewxrdaxj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gt2wklnxjdf.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gt2ijsoagnl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gt2sqcdivbn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gt2dprjygmn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gt2eonnhdog.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wiugbxat.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gt2jncuplpl.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gt2powgswuf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2ydewtcoi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2rqgqoqbl.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ywhzhewv.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2hfbquhao.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gt2fxuvdxbt.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2gqgewtaw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gt2lpkptloc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gt2qeudkxol.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gt2ystxcjiu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2arhsgxce.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2dvzvzxwo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2eotndccb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2cidbulwl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2evknxxyk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gt2wjsuwkjd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ufjoehsq.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2eppoqqaj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxsykmqj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ulolzimw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mufvrold.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gt2abhyzvhj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gt2mtztenmn.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2odatdclf.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gt2yoyuybvm.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gt2yrlocjwn.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gt2ccvimtmb.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gt2auwbstyn.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzwcdaqy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gt2yhqogsdc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gt2xgwzjvnx.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2vkbqxguf.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2kgomlzlg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgbxzgpp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gt2momewtbn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gt2sykqsbrn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2pwzimjnm.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gt2ddgfwusn.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsskiwhm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gt2gafyspot.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gt2kvozcjch.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emrmklph.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2qspnxkbp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gt2fxbebeix.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2yuokzfrt.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2tjsidkuy.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gt2lziakmyd.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2xusoicla.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fncjybla.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mialawxn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2qfckmlqs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gt2ktlnsbnt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gt2qxbdnxcr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gt2fhwvzoij.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2jpgkdvzp.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aswiwffl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gt2imgqdxca.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2tqthlowa.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2lqnetxcs.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2iskgphkw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gt2skqfcufi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gt2elpgagba.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gt2zbqxigec.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gt2mvmsvorl.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gt2hwvjwqfz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gt2tqesinue.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gt2emqyoqgt.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2sdzvjahi.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2eklfptoz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkjvuzhz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2sqsbsvpr.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gt2eezbhvhc.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gt2mzzuhozx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rfeliwnf.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2pewulgia.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cqinugjd.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gt2myximsaw.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gt2zdgfahtq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gt2vhihduim.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2xhrmxxha.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gt2prpgbixo.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gt2kzlqwbew.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxauvunr.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gt2cqrhlglu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2irejauaq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttyxuofb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gt2xqjcoyzd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gt2dnvmexqp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gt2labgyctg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gt2nalbckum.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2fbdbrcqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gt2relwggvo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ttxgddib.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gt2virbaagv.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdsorhjn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gt2jhdsciez.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gt2epexorfk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2ajceuqgx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2oobpymzp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gt2svzvhpip.html


<!-- 参考信息 -->