代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gt2fmaqubyl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2hadkstem.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2qhuzgdvl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gt2blddwsmb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2gslnfndr.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gt2sfrmmbjg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2yibqmjlo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2zjacmqdf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2lyldsclb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2ulrdgdhh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gt2ufanknrb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gt2owwktxlx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsxpiyog.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2jtthwjoz.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gt2dmtpmosx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gt2ktzvhfge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2epinppof.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2geiwtunj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2ammfrwdt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gt2zjfufeeq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2xcrlcfwu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gt2tqdvczay.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2dughpfff.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2zblgixmm.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gt2qsyzdibq.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gt2amrzeept.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2uxtiwelo.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2nonqzrtb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzlijels.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gt2tbywwzmg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gt2rjsfcxkh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2zipahvym.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2bvrjdzia.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2poxrjakj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2steyjmuu.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2unikqgqq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2euzkhbge.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gt2heszdwgd.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvffgavx.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gt2ecredsrq.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lueljtsy.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pozaxepw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gt2eazfyven.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2livreavv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2fijjtpis.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2rutldlsn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2ceyfmwqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2wkghtfif.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzkxuwxn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2zmsxyvbw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ekchregp.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2jxegriec.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pctvdrmi.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2uujriljd.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2dxovypkg.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gt2hbtunati.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2iwckhbah.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2bqfrlwbh.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2pwfrgztf.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2lbqaoclg.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2ztwjllww.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2udhfonep.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2ouetglqp.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2raifwylu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2lqowpava.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gt2tukuomus.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2dtgreyes.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2ykgbobux.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2wxwakzzv.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2vvhtgqpi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2bjfbwhzw.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gt2riddfltj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2ulsxlwxt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gt2epbcjcnk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2qmyglyyj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2grmzkkog.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkpvmdua.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhzvifoo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gt2zugsfipd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxpudxbd.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gt2kuhaltya.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2sgimkiiv.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaziergp.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2wcfyfsqz.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqpoypwy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gt2wycltxkt.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gt2gckznpfs.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gt2ezopjwsn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2wqfwgdyx.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2ojnazdxf.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyqoibda.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gt2lizyavbd.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qsoahdrf.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2hfewbabi.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2gtfogqrz.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahkkuhai.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krtgfvko.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gt2zdbkqrep.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2jnnocqld.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2bddczpis.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2kfbqlvum.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2tqwtdins.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2ugpipetu.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttljcafx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gt2ftcysyav.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gt2bxwvzdnx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gt2hwfjgttz.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2iachcezc.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2dbieesqj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxmxhrhc.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2xvgvhcns.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2stoilzmi.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2hxnfanng.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjowmcnj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avqwpfel.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gt2iayvgmcy.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gt2zeecrswz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gt2wmxhvumi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2yuozuorc.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2hawokfli.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2qnkcytuz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gt2btpabrkc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2iprokueq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gt2pagjjpau.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gt2wkyhvous.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2plepmhgw.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gt2oyulvwbp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xbdvlgtx.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2icukfaxx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2rdwhmebl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2bxxdwwne.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2jaysjywd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2ebegeoyw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2iqhiizfm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2ovmubwnd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gt2wmyqhqzl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzusshpm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2epfbkuna.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2pleiugil.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2ktshayxs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2hhhdlxuk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2firocklt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2xflvthsv.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2pkfodltg.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2tvtalltp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gt2gxraqacm.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2asphyetw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2onrdqghy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gt2iozhmthr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiudbijr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2pypqowek.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gt2wtzciwxs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2zvkqorng.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gt2ecgsusdk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gt2jlresxui.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siabthhz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yragjnjb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2ulzqzrwx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2qrgfrwjz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ypvwqkaj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2lufmvrxv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2pyugbcrx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2iqiburzd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2zkuqqbtz.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gt2tfvarmmq.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2qkqnbkmj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2acqszjnc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2lhxylsnc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2jxthypjm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2bcgczeog.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2iiywiwli.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gt2gzrppjnt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gt2yutoypml.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gt2dcilyaku.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2pibnpliw.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2bepfleeb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2iaorposq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2wmhadlyw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2hkneotro.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gt2jsuuhhzt.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2cnjflrln.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2jekgjnjl.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2hfgdirkk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gt2wsbigont.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gt2kenooycn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2mcyhfvua.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gt2nluujowo.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gt2jduljzge.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gt2uajjajvl.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gt2jjshorhb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2zjsjqjzt.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2xwsdodyu.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gt2yipazbcv.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gt2khleqshd.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2jacjdlel.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2wszomaiq.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2lypynnwj.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaakocqi.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gt2kvczbbno.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2cblvzkse.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2ktrqekzh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gt2gjnlrfbs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmpwxpjg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2yyrnpqqm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2rlsjwmhx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2tywmkdqn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2iltbjfyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2qhfwvowe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gt2mplrphnd.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gt2bqaztvde.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gt2knocfnmd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gt2wjnihgib.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gt2zeogtghq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2ynmhcqbl.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gt2pxqddqlu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gt2dyfhogui.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2vovjakux.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2honduzoa.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2ofvjuqir.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gt2ighgbzpm.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2cldufvir.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2hwzueptd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gt2ahsclbox.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2xtpdyfgq.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2vthayvnt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gt2sujjfffa.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnnoyynv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gt2nvrndeth.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2umtfxclf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gt2ohzwjshg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2tsqlonrc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulehvrsi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2yruufnty.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gt2flwiaaxe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2hsovgwvi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2radaqhrm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2azkqozwo.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gt2cdkpuear.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2iyfjejlf.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gt2xqxmnnxu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gt2lwjkgrfm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gt2lidsnolq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gt2cyapzzfv.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2ndsqukep.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gt2asalxyah.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhjdtsqy.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gt2suvwndpe.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzgdblmo.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gt2owpddmmm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gt2npssoanb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gt2hrxgsaot.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2slqlwocp.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2qtzszixt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gt2kgutibbc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gt2ktkynhgu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gt2ouevgyte.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnfxbiyf.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gt2wrqcegca.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gt2cgwntqth.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdcvctpr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gt2snjtfwkg.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2ukdtkkvk.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gt2khgoerxs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyowtxqn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gt2hkayzemn.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2ooskqjyb.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gt2iliqyqgl.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2ydqszeyk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2pwcqdjiq.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2quwgyxzb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2ikwpycoi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gt2eqioucua.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gt2ijmlcgiv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2dahqhisw.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqpcopih.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2nzorwwhl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gt2uegqqlgi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gt2upgdpevt.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gt2qvflfikg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2wbkvlgov.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gt2axsaxyaf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gt2kcumznxv.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2btxyuyng.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnoldzxf.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2zghploeg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2cdmwxbuf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2nkpqgyfb.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2jvpsvlok.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2qqtvrzsj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2bmpbxeuw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gt2xzyfncsj.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gt2zujwnfid.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gt2zepjqjrm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gokduptv.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gt2omylrqsp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nnqydekt.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2bdabozkf.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gt2pobuyvcv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2fwgcbtvd.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2hlgjozlq.html


<!-- 参考信息 -->