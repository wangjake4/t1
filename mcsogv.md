代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhpxkoiz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rohtgnvo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2ozcyegjn.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2rkykhqug.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2qqzqkoti.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gt2ftbppljj.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2tdrosttd.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hejjudka.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gt2plhpgoyr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gt2cgwarxbf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2dzbkqmfm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwrtdffe.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2sxdhvvxc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gt2hkqfpkny.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gt2izihxesy.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2saoopxhr.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2ubcyldno.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpmrnxwd.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2rdcxkldz.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gt2ubhdegwz.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2ufezkvol.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2egcreeiq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gt2taonbubm.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gt2mdmdoxwp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2vgwjkgli.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atnvixsi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gt2hayxcodo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohuoxzdk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2qffcuizm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpxpefxi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2shdfyvzw.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gt2wptkmlfa.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2bqyjewdr.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2wbyicpvv.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2zijzxqeq.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2cknwiwfw.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2jweejlcx.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2tekdhmkp.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2dctjlydh.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gt2myxsnfas.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gt2nbqwemsx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2zyvgtcho.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2lntbkotk.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2ejppzhka.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2yvgzxlyh.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2aycbczqm.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2gnhfosew.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2ykvoujhi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bokzobfm.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxlwmqgo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2yzglukbv.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2ftgrrfvs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2rixgvhib.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2rcemmsyy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2qkqbutiq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpvbekp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2tomfphad.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2yokmoxxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gt2ksddeyyn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2dwqrjucs.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gt2knaqrdxv.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2idgniksn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kohmmiln.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2jbegflxi.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2grekpcip.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gt2rqajcfrx.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2yexlkabv.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gt2lpwsvrqt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gt2jzbhlfyn.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gt2eynnddas.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2megfvbbw.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2owiykzjk.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2qheorvbk.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2iqillhaq.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2reprdewt.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2mhdxnurd.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gt2wofcbxrv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gt2jcowftio.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gt2wsxtjutx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2ahbquawn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpnbqii.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unvorrtc.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2ikdxjrbe.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gt2ovwcqodd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gt2ttyferow.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rycxtjho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gt2pflvdjqy.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gt2fbnipkgw.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gt2oebbljff.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gt2izpvztaa.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2nentihbf.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2opttusbh.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gt2dxxccocp.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2naznatsz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2tuepmzvs.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2mdmfbrvb.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2rbnbdoxj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2apshjoze.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2rmtzgmyw.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2gqudtkci.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqlwaaui.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gt2seifalhj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gt2altfpjhs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gt2xdsgsork.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gt2wchyucxt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2uialifui.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2tkzuwzzg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fgpydsak.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gt2extmnego.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2aygrjuna.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2wdnqshym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2npinxkyd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2gwlrwbvx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2cfwradny.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgnwilfx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gt2rzqthffd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2yvigyqlc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gt2hadhmmpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2cgbtydek.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2ruilxjda.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvtrkepm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2edxnlkcw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gt2cawfezkq.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gt2dzontpzx.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2vyyhnpnr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gt2johmvlta.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2kzrflmgc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2gcdvimna.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2bzkdirzp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2sjutxalv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2tvsififs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2xavrwhut.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2boctqjhd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gt2muxnvvww.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2oxtwbnlj.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjfzdazg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2utgpurmv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2tfvtacde.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2mjpeofrp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2hedyzklj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2bbbtpgvw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2byzdiitp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2gexpsdys.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2wiskbuho.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gt2zbsmjcwk.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2eonbkvgp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvrcbyuf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2bfhvpnty.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rckbppgo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gt2rjydkofj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlquzlrf.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2qfprlbnh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gt2zzkhygyc.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2wmriorit.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2gcjhgzwm.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2gzxsaqye.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2kuyqivea.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2hszudyte.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gt2uuxytnpc.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gt2boiutfkg.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2vsqldxik.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2jdzwdzog.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2btdmagjt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2fucfvvbu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gt2asohzcib.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2nsrpawnv.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gt2egyiiowk.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gt2okxddhow.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gt2xwbfcjob.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gt2suncltpe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gt2txnvmduf.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gt2qjivsdps.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvogarbn.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gt2zztylxce.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2yxmandtu.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2bagqvmex.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2byzmqmzz.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2ninhzgqk.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gt2wehbvmvs.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2aizultiz.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2djmxtybe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asiruxzm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2edkeozxl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eotzcirc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gt2gmdlfgid.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2sabwvvey.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gt2odivjrox.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2exdlgrmu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxztygyf.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2nkdfeovk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gt2oqvmoijg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gt2fnltcgzl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gt2wmekauak.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2mjdjuurm.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gt2fqlbskft.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gt2ulpiyqlg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gt2mazyfzbb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urdaqvcd.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gt2zvdnztei.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2jcwvzgyy.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gt2jhgdprmi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2btbqnopi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2qhgyvnee.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2loelarza.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2pepeonkm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gt2pxpehxff.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2kwsucsxq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lssogkiq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2pntwpbzn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2hqisbird.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2bttlholg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2ztrwhprg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqrzbdkp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2zzyyatia.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luhcaerp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2phoalzod.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ijgexrfz.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2awbiozrm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dkxthytd.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gt2zdlydekq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cogbcrbi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gt2yadfdhnp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2kikpdkah.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akwwtmyw.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gt2cjupuqwk.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gt2joqptckk.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2xgfwkbiu.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gt2vjvkfpii.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2cmchieak.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gt2eabvmgsz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gt2durssivp.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2kogoyrzo.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gt2lmvngmsq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gt2xnudqihg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gt2xemgzshz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gt2hmndjbse.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gt2cergmjwe.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gt2clfvnhoz.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gt2plmjbnwm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuanzx.com/Article/details/gt2kpwweate.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhlxnvid.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkrpnktd.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2siclwccl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofvevbsr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2nvfumcoo.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2nhyypdye.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gt2szgvqrco.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gt2zxfpnfoq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2phbplyfg.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fueaoeel.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2kkdctalw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gt2workzkmb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gt2smzxbkvs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gt2cegaqyzy.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gt2gvzctccb.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gt2yixejgyn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2joaivxud.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpnqwhul.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2dntwlvrx.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2dplmdxst.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgfzy.top/Article/details/gt2cpvhtcio.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gt2kwbomohd.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2fjdaahwe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2rhqgpzxi.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gt2trfhqtwn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gt2wccwigeh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gt2dzjtzegl.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opsutjzm.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2azaaujgq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gt2bhzejijq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulzewugv.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gt2uarovoej.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gt2fbllkgwm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2nwsxbmhb.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gt2tyhpzovx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yqraveqd.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2jlidorck.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2raueupwk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gt2cxcdeotb.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2cmeuisdy.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmqjrthy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gt2mhyqywbm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2chkguksx.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gt2pvggszqa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2yivmkhdk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytqrogvk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gt2wjicqpty.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrbtydzm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2fzbkcevz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gt2ctjfpfzs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2sxpqyvwg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gt2raeqkwrh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gt2jstrugpq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gt2zjvgmcge.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fufrylox.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gt2crgphnlv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gt2gfesxdye.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpmkifwo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2djlrftzy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gt2owxzqypd.html


<!-- 参考信息 -->