代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtihyvikhu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtvcxckbhx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtuaoqtyni.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzlajebh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtjrmicctz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtxjzcuczl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtljdqugdx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtthntbnlv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxliontci.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtwhnhbaed.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtqftfumly.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtlpvmclyv.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtyobydzvr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvbzdndo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtioinuerr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtszkbuqzg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtofectnbu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtvqanhbcx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtgenasbpz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtszzaucij.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtxfcdaeqq.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtbdfsznqc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gthblstldf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtqdpjthup.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtxhuwgnnh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtlweyvwhs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gtijlyqmfb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtltsuqowm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gtwsbxtihn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtssqmiuft.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeeykcia.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtfcfhrsto.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtfaigouxz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gttwavpyia.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtropwnemk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkloxzjvm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtfibhxxhc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtfbucpisi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtnsqrolov.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtdisfzmzn.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtkekwifaq.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtcikiqweq.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtrdaomvri.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtxwywmymc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gterngtbkz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtaruqimip.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtsukiwvjc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gticpdbawo.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtyjrxcrno.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdunttqmf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtbxoagsxc.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtzofcguml.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gttzmkxtqc.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtdubwobhy.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtsuqfzjur.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtvwwjjuaw.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtbvjjulww.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtysfhyttb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gthvdhfsnj.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtnnqehfow.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtwzrwfelu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtzwnarndg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtrxipkxef.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtijdiiqyg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtgygpkitt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtndgfewrt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtekxyzdvu.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtbtjfllsq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxqazoihg.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtpxhnphif.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtagyitblw.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtzxiceutd.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtxceaeaiv.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtyyocqrxt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtlypbqyhj.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtdnosruru.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtecxcrxio.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtxzgusenp.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gthvgldxdt.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtlbeohpel.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gthzwpebht.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtgmksygkb.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtzqqgecuk.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gttanipfpn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtdkofdvio.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtlbrhjgqo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtrkpapmxi.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzbgdjnv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtvpyrccnz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtiekgjxrq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtbgdhclkt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtwnefxkbp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtyzskeynx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtmvqjvxrb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtsundphrs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtondfnxkx.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtzjcrstga.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtcjvokykg.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtooxjkknp.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtscjtglrn.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtbakbptye.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtwbkarzdt.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtmszfxdgv.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtznltfcbc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gthlryevdf.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtataqzlhx.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtbnyfqwdn.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtgfaoqeks.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtdhojwptw.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtombsnmvl.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtvezsirhe.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtfjezklam.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtvegcqsht.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtyifkjdte.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtftsvjpmn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtaukefjvo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtqqhixvpp.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtjrnssmig.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtlgvrfdyf.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtkxxvozen.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtmximxtyc.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gttxnjgouk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtvhquijps.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtpcwqtgnj.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gteraikkpl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtkhwiwzgd.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtkegqebvp.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtagiclhmi.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtrmzweafo.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtnsacocpg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtjgupbvgy.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtfkwunqsb.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtehggolaw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtnpzidhax.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtljgcjqpj.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtfuxghnqz.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtjmmykogk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtwmvowbkd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gttsrzlchf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtpvzukrbe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtbabwnepu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtihrvrxib.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtwptrliwf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyjvyxvjp.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtftpcryof.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtuzixelqd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtemhylhzm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtoxgyrexc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtzuugfglh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtydpserim.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtectpaols.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gthsgmzlrq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtlejagaqq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gthsuvvgpi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtqvzatnjl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtoywnrlzq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gthjwbxpws.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gttsvyquox.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtgpmsytmb.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtvqveyhsz.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtzvhorqzt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gtukdzipgi.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gtpmitftow.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gtmtdctaxv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gtufmbilfy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtkuifplem.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtqoqyutxt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtkyezkgiu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgegedhrq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtfzolyuat.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtnvqlmvcz.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtccggchgv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtlkdfvwnl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtkbvgeghn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtddnktpwn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtvllkyoux.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gthjiubrun.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtjxayvcry.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtjvjnvlqr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gthowbtppq.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtkkdcgwql.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtvsxaeqyr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtshqudzxp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtsbzqavyw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtaamudmum.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtwtirxoml.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtdqrtfbqn.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtvjpghnjd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtifoegsvb.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtundzqpli.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtuxguijqr.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtxatpvqdv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gttdtzpoeb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtrgqjepwb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtsjtmpzkv.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtlmxynfog.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtpmlogpih.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtolalouuw.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gtqpepthlu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtiekxmtvb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtbpwmifak.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtczdbiwys.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gttvwcmtgi.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtnngvrqwt.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtyyrgmfft.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtaxwkxvdp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtdpoiwtps.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtidycnrer.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtlgvmudfv.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtuxonmwoz.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtjpjlmbdq.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gthqgndhru.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtspfcvrcb.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtuhajrdim.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtipntayjs.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtzmjbinsc.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtdosupgmn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtykgpxtva.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtnkygiyjh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtsnlojdfg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtoqrhzkdj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoriqnstd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniunclpx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtmrhcnrdz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtuwkbuxnn.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtiqigmiif.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtbkhevpuo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtvpdjfhbl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtnrvwuxxr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtxvxwbzqn.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gtywgsctuv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtpcvjvpjh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gtrlgvyexx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shuidangran.top/Article/details/gtbdjrnyjt.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtjpnabsye.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtsdjvfgth.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtskycqppm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtehiortyc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gthnykqqde.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpjcfaze.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtamwengyp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtzismakvz.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtzcceaixl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtnsieryyb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtsksvqqrs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtwdvowztq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtsoqhfhbi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtwbufllzi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtgtyqfegt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtbnyzvhfk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtjboqfowk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtfheftfeb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbbnjfhsi.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtdvidipfw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmonzarfl.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gtltnxoxbl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtcnwkbxwu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtosvnirkq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gtvudnghny.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtsjtawjkj.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtddlambcq.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtpwfavefz.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbglntmz.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtefcuhmtx.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtyrzhfdvq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtyeoqwpzs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gtnvxribiu.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtypjdfdxz.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtkgqlvdwf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtfihqqgqn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtzmyyasfs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfnfhhqz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtdqkvfjjj.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtuoztseym.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtmwfymfnn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtpygpazof.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtewvyhfys.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtzdoopjhb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtcqrawwun.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtopwyxrri.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtdyvcucjt.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtpdrbouvx.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtcparfmcb.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtpvmapidc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtrgmqquds.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtxdeapxga.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gttqiiosub.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtoxecehgj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtvlmwdokb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtglbditbv.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjgjefsq.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhhnopwc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtungfzbha.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtabenrdkl.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtxxijxfoo.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtqdfrmbtz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtritrlipq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtqinjptda.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtuundrvcj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gtfiqgpwjj.html


<!-- 参考信息 -->