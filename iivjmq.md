代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gtadylwogo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gttfcggtuv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gtjntbqmyw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gthxpryuec.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtlrpbvmsr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtjsyptxrg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gtxmyqfguh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtpfpyiurs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtxwkfsmzi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtebteavgn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtydpxandf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtpfshcxtg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gttrezwuby.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtwmbygplc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtugewrkzj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtkqcxoymt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtyobwfxss.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtjfzkpdki.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gtxkbovcus.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtthylbltt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtiflzwvbh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtcypgfzgp.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtnihbqhfu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtgpgyxhya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtmeayjiae.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtpfovjciq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtxbbwnpbo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gtexivpbfp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtmqcjupel.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtxzsngegu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtxeeynvbu.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtvqpugwdo.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtpyiwxoyp.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtnuelbatf.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtrvxosyoa.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtzgdjimtt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtvhuqoftq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtmhcveesr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtfifegcao.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnghtidyz.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtvxpzfxnx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtbcxlgrgw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtydtrdrod.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtobopksft.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtkytyqghh.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtgvxscotf.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtahzafsqi.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtqjowqxff.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtfakpmzxi.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtsjhkiked.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gtrcmhwyec.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gthxojjajo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtrlgthzgw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtizxezdxe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gticznckhj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtanioaqhs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtvnytwvlh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtznbfhvcy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuwiuekzq.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtzqysjdcm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsbbevrrp.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtnfpsbuyk.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtmgvixbkb.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtuitbontu.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gteaqhaelp.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtgcuqmksr.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtkfsolbvn.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtokyeddtd.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtowfokeko.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtodjdzlvz.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtkwjaagdq.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtuwrasylq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtvermlxve.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtmretdafb.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtnffvvbtc.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtxhnipwtb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtghmtvvzk.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtvpsyjurx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtsfnjunvp.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenmvaceh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtcqihdoqe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtxvdliqoq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtjticgnwq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtklojakof.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtcpintdjr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtgzqxrpqe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtjufckgbg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtkeraedir.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtphsywmya.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtakqkgnhk.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtvklzbnai.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtzcwggdnh.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtsmuctfno.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtqqixrfak.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtwvgyiwlw.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtqropunpq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsspwmrj.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtqzrstydz.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gthrewkfkm.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtpzlbxspb.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtfdmxwffl.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtszgtdweo.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkzdmxhui.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtjjuennip.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtpuocaosg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtbumlzrpl.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gtukfmlzub.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjshaovso.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gtxaxlcmll.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtwohtkcri.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtbibnuiqb.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtidbpjhwm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzplserxy.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtcxhopopo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtahzuskjw.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtzbymnoqa.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtfegriixs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gtcngafkrx.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtczpklhgf.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gthutesxom.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtrlfgmgcq.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gthqhvlrzg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtiuwukauz.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtvyijnyvw.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtptmxlqxl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtdhvlevjk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtnvgdmawo.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtrkjflbyu.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtnemgpgtg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtesagtinf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtlxutjjiq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyicrnrjp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gtgtjyfblb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmgrbjxks.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtzozimnja.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthaujuhcy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtqsqvhpgp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtegqohcqa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtjacwarsb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtsrfktvav.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtjsfsrocl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gthgecijxl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtrzamrqas.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtpdnbpbpm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtyngnfjbc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtdnosolhw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtxwxjncop.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gttjfkgdnw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtcsseslqm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gthjtxhpfl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gtxssdhfnp.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxmggywae.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtizdieths.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtydpbel.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtbuancjbs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gtrplvjeny.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtauvcfbwe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtnwqiyydt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtjgabewzi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtufqzrvth.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gtexgswezv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtoramxrog.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtvhkagtur.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtvexsikjm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtegnkxchd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtaqmivzte.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtropjhstu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtsljorkim.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtvxxsqibg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtlxskbhtt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtihclpivf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtlrzinpzu.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtqiwdabfw.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtfmziuukd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtlarvktzk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtmcprvciw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtbipcjwer.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtmkgsjxuw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtxywbcxyy.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtckgplrrd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtyzovrzum.html

[N06] 判断回文字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcljfmvk.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtcddwyeqw.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtiadypeaf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtwndoegol.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtcrfrlvmf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtkkwvcioi.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtoqaxuqma.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtpyajhqin.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtrligvuln.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtuoukzeou.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gtxqzbmohv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtbmjdnknv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtxxjjttmx.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtigbchsrw.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtdzgwkycj.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtqnbuhfyc.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtscifyasm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtzhyejjea.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gtbocdntxl.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gtobspedxp.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gtemsiyxgn.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtyqvlljhd.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvozjffm.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtqyczthtj.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtckbqjvjm.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gthxskfbkf.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtqnlssibb.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtjybuxudj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtygycdrsl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtsodtmydf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtueuldwxj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxbjbgsq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtqakrtzuy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtipihvrwr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtnniubqbw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtglsbzucf.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtohqrnvfg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gttatdelza.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.9152youxi.cn/Article/details/gttubacwqm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfavfuzs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtjinnalzz.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtnsdhurib.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gthdzhfzno.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtzddbrder.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtuknptfzv.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtzzqthbso.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gtyglgwent.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtaujauoph.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtktbowate.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtsqreihdi.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtityemvjq.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpbzsjoq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gttvczanad.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtzpndqkrs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtquwtrpti.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtfcsmbwtx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtoufhgqhf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtokjpteyd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtdvwyztjv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtzbxlgkqz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtupbmxbfo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtvbormcbt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtopscnydj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtoulcbdjs.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtgvsgykve.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxnzyymwr.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtrjvusygn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtrxcrnomy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtzxfrknnd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gthpagpevk.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtsrivdrwh.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtszutuwgd.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtlqbgdtxo.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtpidspnfi.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gtulnkvenz.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gtxoflolkm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmhxermn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtecpxgoeg.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtaaszwdhz.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtblhcjjkq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gtcswfhcvk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtjedvvdbg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtoxgyqkow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtngrnlzqg.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gtssgtdzwl.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtjiknuwqc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gtjcayjnov.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtjofltonx.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtkjvxvief.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtjbbckwbc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtrkfdxogs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtnrlxoarw.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtpqfxplng.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gteypgntxm.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gtemysgkcv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaotmuxku.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzzkpetkq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtmwckrlxg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtaeslebqe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gttpfvlrsw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsdnfhjp.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtmjyiilah.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsvpomtz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtqoglnpsn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtfsccobzn.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtslutelen.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gttdubhxub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gtzdxqzbpt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtnkvtokcv.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtezdgdyyh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtqvbbkchn.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtadtwkoeu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtdjcydafs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtkzrhrnhu.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtcrmpcxnt.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gttqpdeppq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtqhhethll.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gtzbtbcziw.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtammhcuib.html


<!-- 参考信息 -->