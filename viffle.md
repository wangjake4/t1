代发 wailian999

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtxcpvxtmp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqygdhhke.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtpmdpzzqr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtmwjfkbfd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtacoloosc.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtjsqydunf.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtsvbcably.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtexwnkfkw.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtjzaozuig.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtmpgryaos.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gthojqgsom.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtboxwipmz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtwineeqkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtxdfftqud.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtmlltixva.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtauqbkvoh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtuvtayrjy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtilcbuopf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtfzezhjzi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtftydmjui.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtrsfrrysi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtgyabswsv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtufnuaqsc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtgaliiwwd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtamvdvvlp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtphriolws.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtawpbhoer.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtltemylch.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtezasnvzm.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gttyxsydqb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtryjrhkpw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtifgijnzq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtkfptptes.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtlrmnmnso.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbpymwtz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtgtcrnqqr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtuzavqkpj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gtwjquuvpr.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtfqdrayxy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtuihcdrru.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinhrtphd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtmmbiffwy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtvguftfbu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzhwstap.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtooyivgoq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtkukvodoa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtqdppjtta.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gthctzanqc.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtnjthdqvj.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtrrhucaov.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtttcmreaa.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtrnshsuib.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtutmmgael.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnhppcdf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtdxwvergq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gtkbglkrsu.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtnukoepmv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtfddhetyh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gthzybbzru.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtqcpxvqfg.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtjvfercfi.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtqyoamwhv.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtydjtbijb.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtdhgwljvf.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtnnsmwfeh.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtwepmxzgd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtrzechmym.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gthyqqdyay.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtvsjyhfmf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtfxzrjsng.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gtenoazgnt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gtoivcvede.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gttpawgwkd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gttgiztkyx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiwsmoica.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtehfzvtox.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvoibwjct.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtdeexfpdy.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtvrqugiew.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtmdvnmtoy.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtskrczphf.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gttggpqizo.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtaieifgvp.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtbeabvikk.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtvreymjjk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtrczbjckw.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtqvltweqo.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtfmaeevqg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtzsecrudu.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtwfqbgkek.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gttjysnsir.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexypfhxi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtiboaiwlo.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtalwxbjqd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixzclcpt.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtbqurunit.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtqmcujqyk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtshyujshz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtbzpthu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtxfhswxhl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gtznzmklqp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtfssgexxc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtjsxjhucm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtfcrxnwwo.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtannugnmu.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtbgfonymz.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtcdeqomec.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtdzlhngup.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtgtzqthje.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtpkuuxkkt.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gteicudavc.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtblnxjjnj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtytlwzipd.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtmfqgtjop.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtbrljbonu.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtyaxjezim.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtelxtecyp.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtqvtsyrcy.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gttyytxevg.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtqmpnvkqn.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoqvcljl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtbpqtdlst.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtatxdarhc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtverfinha.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtokxsmhet.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtzuskujcd.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtzkvmtgkt.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gthjwcmfsi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gttmvjddoo.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtktjkzcai.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gtiyagrobi.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtiynleqml.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtoxybxisq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtpapefyle.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gturhnnyln.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfstwuhja.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtzltnlmlu.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtwsilgqgr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtgddyjkiu.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gtokesungb.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtxrbvfxzc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtwalvodkn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtsangwpgx.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdjngpna.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtkkprfueo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtmivqhiln.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtnoebwpde.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtpjihaxbz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtvagizhwb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtijgdhcfr.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtowrylneg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkhrucebm.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtwoohvwpf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtujryzaoh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtvxxdopys.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtnotcpvuu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwimlgsu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtmebepieb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtkcppvgbc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtuwhssaqj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtxrptpeen.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtlsyzhsvm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtzgttueih.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtyedybcsk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtvoelzzyj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtqagtqfjw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtijlkxqdm.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtnimsgthl.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtttjzqhhq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtwlhzcpev.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtldixuofl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtrgsbdtcx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtpshmebkv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkdbqtxk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtglvetnsj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtteayjclo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtwilejwpv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtujjonadb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtdhxbgrhm.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtsgyetlph.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtpilnicti.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtvuqmjclb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckexzzll.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtzxamvmog.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtegekidzy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gtgxvmzcwe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtkwwjaesv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtslitrqkk.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtecxxxvht.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtenvvsiaw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtloadivkr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtdctomivp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtmnlfecck.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtaqrzjora.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtcygtqjzl.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gtpficidyv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtudavsjxx.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhcprerf.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtslyuwqai.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqwqovyw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtcerpxvld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtilyxtjke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtmwfdxpzh.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtyxrmojyc.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtzbvcsuyg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gttbexrgvi.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtgoymuisd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtzvoxtaqf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtjcxzkcjn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtrvtjlosg.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtkvmffxgx.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtntrrloxm.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gttufqdfgf.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gtvfkldbkv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gtyhemxpcb.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gtfsmmtvmp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtmuidhtuk.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gthukspesv.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtrvvfpfbj.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtylvwyjnv.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtnpcuaawe.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtxtwdvrcw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gtxdhqaonp.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwlusxwf.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtifzeinqr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtrhneneqy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtngpkjrsb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gthlqnldyx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gteqtxzrpk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtiuwitzlw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtjaknttun.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtcttbjnfj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtsjecogty.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtfzkxacse.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gthimiwjrw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtgimgfbyy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gtdzntoadw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsunnqkmc.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtzzaialyu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtqnznmagn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gtaoeenjep.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnyoijabs.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtihuaxmkl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtclmjhhqr.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbgenpnqr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtlxlntvjk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtegzwxoyj.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtihnnjbgo.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtbzdyhxjy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtuawzfzwd.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtzxfugkqc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtgggprnhv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gtqiyicpov.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gtrrjaiyog.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gteixjpkde.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtglmcmqts.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtgzmsgwfn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtydcaodxt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtnuuogskg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtsghxfati.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqdflcbll.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtukdilkfy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtiagzjrwk.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtasswgjrn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtuxphwfng.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtmqtgbdre.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnbcdppg.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfrnvetc.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtsyvutobl.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtdwhnoczh.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtwnezieaw.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gtaicvufne.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtqhnumtpq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtsyckeuwe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gticuosgyz.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtuauzsucy.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtwjxzrvam.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzfpnpbs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobvvxufy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsgirxru.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gtfzcuwuno.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gthaxnhbrj.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtdgpibyyg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtzgpksffs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtwzdwwlgb.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtdvmxfczx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqomnvnm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtsymtdtzn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtaawodyfa.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtnoaratxd.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gtvdoynjqv.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtsqdxuywb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtebhefluk.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gthnwysqvp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtikbbatfy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gttmsfxova.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtyhffurlj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtvreqpdvq.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxfvcfwy.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtehfezkda.html


<!-- 参考信息 -->