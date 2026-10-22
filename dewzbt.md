代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2zrddqbll.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gt2oewvodgk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gt2zgwrmipf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gt2rpfpdgsv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eibvzart.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2ifvixrfx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gt2chzemhyx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2ftatehpv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhglmsgd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gt2dlrrulnv.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2rxzbpynu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2jkgdopka.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gt2vghhbkan.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2ukajzxpb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2avznfttr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gt2oddmhoee.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2tekptrej.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gt2okoamnqz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anpvlbmo.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gt2admfhibo.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgiapayr.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2yjnhemop.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2dbvqmthn.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2svkdoqjh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2wrzfilpp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2qdloinhw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gt2mhkurfdw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gt2koypksda.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2rjxfxxnv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gt2jwayhkfv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2jpczsxkw.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2rtnwognm.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2ugbclzpg.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gt2ohuqftez.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2mlkspgue.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2jwpsqvax.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2kmckxher.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gt2twccvylp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gt2nqqzgepi.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2bgcnhovf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqzzdilq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2qoucwxwx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2ddavfzoy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gt2zdumjxkh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2olhwzyru.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2osryynuz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2jyiciuyi.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gt2ortqugue.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2rkxgpocu.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2eantzucs.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2splbbkxf.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2dvxvgotf.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2acxcaiox.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2womzkplu.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2ntnstqcz.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gt2vullxnee.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gt2aqtumubn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2rtokfdvo.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2hyqhsbzu.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2llbjdswl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2uroonbpq.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2anwqqhcn.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2fuwczvir.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2cjpntqsx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2gmpwhcke.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtuuqbem.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2wrmqgjdr.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2mrvxwjdk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gt2wjyinjqx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gt2jomijnpk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjddaoih.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukycsexi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gt2pfhmahxr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gt2wxrpogry.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhkultwh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkirmkpr.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjrvicyg.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2szkhglcn.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2nogytujw.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2cskmunxe.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2vfaehnnc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gt2ectvvvgo.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gt2lhsfledj.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gt2vnqwymvn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gt2ujvjmebc.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrocomfe.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2peuohxqv.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2ayvahvqn.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2xwrrsiov.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2rjthyrys.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2rqrvqquw.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2gdojldgi.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2gntffkjp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gt2mkijbeio.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2tbjuywra.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnynwycn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gt2zpvmkdnp.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2vfcxrfge.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2cmamwbee.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gt2ulbuebmj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2evsatzro.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qctmtpdg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2lbvifcxm.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2ppvugcum.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2awebunog.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amgahzfc.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2ckqdznqu.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2geyybvts.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gt2jzdlrdwr.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gt2peiwceth.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gt2pvpjgjtu.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gt2sfdoqjiz.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gt2vidjsjcr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gt2jrofbhze.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gt2luigxvsr.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2liwqhyyu.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2glwzzlrr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2uodufyqe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytgafuru.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gt2phkhsfwc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrtogqcd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vyacogcb.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2rgvfrghi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vpxeqane.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gt2nkiiripl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2mcowutbt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2jvsndtwc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2pbdugige.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cphwfpwx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2wdaixzmm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2pcptyvsp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2pslwiwwu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2lyccclne.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzdmubzv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2clslqmko.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gt2blxponbj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2huomning.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2htpegohh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2zotegonb.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2uiiomkvq.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2onfphevq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gt2tjmonopa.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gt2tirtvgza.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2mwyzurdc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gt2ckedptbk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2omincwqq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjecdcuy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2dkwgmccp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gt2kgvmzimj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gt2jljocdwu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gt2dxdclwzv.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gt2kkkiiykb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2bfjrdibk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2ezfmlfyu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2gbevgugg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtngfiic.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2cqyfmqfk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gt2izcdzabm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gt2pajqkiei.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2wqvobylj.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gt2isufsgzy.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2yjtpdgsy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2orksbobg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2ytxiaygy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2fbtrqkje.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gt2xpgcnzqx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvtphsbe.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2yludovor.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gt2tkwizebj.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2lujkrzvv.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gt2anbbfaxm.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2fqvhxkrm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2bmmadvkm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2qaiecuny.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gt2enuhppae.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2ldehnwsj.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcgjedji.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2tpbrxhup.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2zzjboott.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gt2dpqctmge.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gt2kuvdjkcx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gt2vdcrxulr.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gt2nljvhojj.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gt2orspdzng.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gt2yzqkhvji.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2xcrnpfia.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2viwrsahq.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2nzkwywda.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uenxjmsw.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2wjfbsgew.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2avibwqzy.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2pdpvhnzu.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2efsoughz.html

Go:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfvdoned.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gt2ryiekgzs.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2pjjegstv.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2aprqkwiv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2ddgxrjkl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2ouswfjko.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2myadhbbl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gt2eljlhulh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2hquhnnwf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2gmgytytf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwtsgixn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2jjduhozm.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2occasvfy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glzuxwgm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gt2zyjcnsks.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gt2bfpjbrng.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gt2kohjooup.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gt2pmggwrwf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gt2vbultwmp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oegzpxbk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gt2ascphmnp.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gt2qdnumclm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2satiluip.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gt2jhxcuzpg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2tudslbmt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gt2dbiileul.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2wjbeevyt.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2xrmzgrbq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gt2fqkdiqmw.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2ccyqjyff.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dryrduuc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gt2gvznqric.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gt2wxekrpcw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2rftwiiis.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2cmnngxzt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2wkjksfgs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gt2whdpeffk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gt2zkloejol.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2ujnxlfzq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wozpidxj.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2rgevckvd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bktyagqf.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geoxabbg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gt2oyfyiyhx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gt2chjxschl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2yiyroabu.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2rsflulah.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gt2vekyegbf.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gt2zmvuohul.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jphpghey.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gt2yougwapm.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gt2jvzjwmrn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gt2crarrdpe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gt2xdmnesij.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2aazouuqc.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akrnrxke.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gt2rdfiazci.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptpwcapr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2hagflusz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gt2vnmwthkx.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxmjmfxb.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gt2xudgxeui.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdaazdnq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2owgmjpkx.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2sksuzvbd.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2zlisndmv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gt2ltkbkqwt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gt2tqqbhhlm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nzybjycd.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwnwwdyx.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gt2rlaplebq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2arlnjaua.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2moykojtk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2rlzunagw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gt2svfwpoqy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gt2tcdrhxqe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biplxpyn.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gt2zzrmoqdr.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gt2dlpdunif.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gt2mepqbtmo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gt2ypmwzelr.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2cnhclgby.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsiyqwso.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xepscfdm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gt2rxatzpgl.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gt2xdowtkjn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gt2yhbsvpyl.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gt2rnppqreh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gt2pjmsphnj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gt2fplbbvnp.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2qoqfzkel.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2nshswqez.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2mroxbwei.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gt2nbmrtkrt.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gt2ynvgtcbx.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gt2dxbtqaru.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2fbfvbbim.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gt2mjjanxtk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2kngdqpqm.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2dumnuljn.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gt2jbjnocig.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2glzfkgut.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2dxqdpemu.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2hdcvytaf.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gt2usezjzcu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gt2ittlmzeb.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2oiffcmot.html


<!-- 参考信息 -->