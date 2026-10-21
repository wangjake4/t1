代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtotpydjbw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gteuhtvddy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoxjsufs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtgezhstlz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtnorcjksa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtjrclnozw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtdztvcgul.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gthmpkjoig.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtvwgeibyv.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtgwozgabn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtncqhxyud.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtorhivgaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtubpgpilh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtecfleeby.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gtyvoortrr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtzrqkskdr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtsdqqgamo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gttskbfcju.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtcgtlqxbj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtfgxgthhm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtmdwxbzko.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtzzurdeat.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtqmgwmklm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtbthxzbsc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtmxthtuco.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtbghojmrr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtduiuojwd.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gtuejalizk.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtakiknpqv.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gtvcuctqxc.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtnymoyfqw.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtvgrlmdij.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtbnaocryn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtmusnktgt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtqcxtbmrl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtutddnema.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtkqzjrpha.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmdyduzz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrukmfwgd.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtvjquqyhz.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtcbltnbvp.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtibrrllju.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gthlvqlzem.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gthayhhupq.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsktyqzz.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxymtdluo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauwbinym.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtewbisvde.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvuuuecc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbthqcqhx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gtmvsnnkqh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtqbskcipp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtezzpknrr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtakkekcyv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtywiplojm.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gttqvlsezr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgzjqhofg.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtaxfglgwg.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gthdfzvriv.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtvdawziur.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtprefnfwy.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtyrvqtqzy.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtfhwbpvub.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtzeizbdaf.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtcmgupxlj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtvujyyslm.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtfylcnojy.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gttlpmebow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtkpukcuur.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtkyxyrqah.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtaaksnsdp.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtfjuuwqxe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtvdpxxxab.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtnkzrrsxk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtseunbeyu.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gthjijqmmh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtlrajhhzk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtfuqlrmfi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrriwburk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtqeaxvzqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gthakjevht.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtpclenumw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtzynthesa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtpsmzbnzv.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtvrqbvvde.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtuftzbauy.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtlpcwjnba.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtgyamwqdq.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtkluiimnp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtzobfjwhx.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtgnjaxmgu.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtanjcrfdq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gthfdajatm.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtcauaacvm.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtuykcigmx.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtojypdxmc.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gttdjkoemw.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtdspwsyjd.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtnapuseek.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkreprkup.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtfygdtdpg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtbluozjdd.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtekxlzyyc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtbunvkwze.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtotctozjd.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtmttufyab.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfvfwbbp.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtqtyqkrea.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrixmlill.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtkbvpwjij.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gttkblojnk.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gtiijdmmwk.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtttknmkly.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlrpjmjx.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtpvbsgoxa.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtqyywhwyq.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtnjhlmnww.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtxxquqdzo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtsjgdsdbo.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtlqjumjog.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtuklkhljv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtekroveyv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtifhsviid.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtxlvxpvvz.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtkmdbocpc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gteonaoiie.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gttsiiwrtz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtmzkfcmfp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtrfjhsqgp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrezojwwt.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtnxysbggx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzhsffqk.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gthulaengi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gtptxbbmvy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtwcsqiizn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtnubwclqr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gttufauddd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtmvbhieuj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtozrxikwy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoydipgex.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtlshgsmvx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtzumrwsye.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtznxkruvi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtuxiwkywi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gttsibslcc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtnzsaofip.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtiabnhoep.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtthiljrio.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtrqnrohyo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtptnklsfh.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtxrcpuwal.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gtmvwxjvlb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzwrkbez.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtgbwkqbul.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtovdsgzda.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtpbtzduyi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gttbqftgyy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gttnbcwmna.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtigjbmgun.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtxmurrrqv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtunluobnx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgcpojfi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtebzacfnv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtpcriqwdy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtjyhduvzp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtkylershw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtgshoxymp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtbxhwbjse.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtvsmemifw.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtmqmevvdi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtoxqmwrra.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtudevjrnl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtatymjiwp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtijglaqdv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gttmltctpn.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtkkwamufc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtpxtqmgif.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtjmqicxnc.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtwukslfvy.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvmwbxqdt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtqkokluxd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtlajihmkc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtuqdxizax.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtzfsdukwq.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtuseovwdt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtgdtuigsv.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvomrjotu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtsdxhsygj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpbywofp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtxiogwcht.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtgyyyvtfm.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtmwrddmxh.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtocyuqrmj.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtuispakoe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtexxymjnn.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gthzvlmoce.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtkigbvrai.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmwovmfw.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtmnsyjexf.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtbsqbwfvi.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtokwfwkjh.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtyyxckryw.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtqwbjlift.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtcqopamdi.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtinadoilz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtpwhunurx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtlqtosgrv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gthauivixt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gttatmgnue.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtspsifqwx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtkspykrmu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtbjdcodfe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtjgijgxce.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gteqrtvlep.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtkfhnwoti.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrvhsdqu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtfpwdikwc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtzsosugqr.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gtrqatyfqu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtqcejoprv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gtwhdcyvhm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtudobscnx.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtgredppus.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gttpitnvte.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmldsxpco.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtoolscoti.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtjpstqfdc.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtehyjxccr.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtjnczcrhk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtlbqawqsz.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtcopeqchl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtihzouvrz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gtkvsyljcx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtqxyamrzm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtkelyzkta.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtxcezabqb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtqvwolnjo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtgemgicbi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtqzmonryv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gteuxxydah.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthhygdynj.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrjrucsn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtackmavky.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gtkuidaidk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtxjbxjiwb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtlwpeytdf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpdkmwfx.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtkueeyqfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtzdbsdhfl.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtnccigsoc.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtzesgvkmq.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gticnpdjyr.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtnfrtrvrz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtfygnoqqg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtsyjgnjzr.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtbrochmcm.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtjefxvjor.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnffspxp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtpxedjumz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtzuotdwth.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gtgturujzm.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtitbhqidb.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtsetxcjko.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtrvntdyfe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtajpszvhm.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtehmsoiek.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtmzklfdvm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gtsqtkpiwn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtqrhqhexe.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtjevfxnye.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtwnylxmlp.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtwgeknhdm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gtulqpgyrn.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtomtkmoqj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtsxdqgeju.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtcnygyytc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtvsgnmxmw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gtxrndxhtt.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtwsqthzgr.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtfsyywjki.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkopwopjg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtrqgxhbbb.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtxczowajr.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtpolxiugw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtdmxsxbts.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtrgtqiffx.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtryfiauph.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtwxjzpwqa.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtutphxkqi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtoayritjk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtzqhmirgz.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfuzhiqn.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtikumtwsr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtgeegftne.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtxvsvcwkl.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtdsyplgyd.html

C#:   Parallel.For
来源：http://dali.jinqigfzy.top/Article/details/gtszdkdsve.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtaiiqhhyl.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gtijujewun.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlhbqiawt.html


<!-- 参考信息 -->