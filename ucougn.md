代发 wailian999

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gtebnalguk.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzaiytvby.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtqwyvhnwj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqqebhizs.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtsoutaerw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpmbafjhi.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gthuryeldd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtzfwyahrt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gtyvshjtoy.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtuyemnccp.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtzfgmzhgo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtoijpbvnc.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaizghse.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtwcuwujcz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtzovrmamq.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymfwkteg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtewbxyamq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtuhvjxxey.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtynekbmcg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtqxqtofqh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gthcshsegu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gthkolggca.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtwjkakcwu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtsgejoqlc.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtqabyqfyk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtupiuxedh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtjkpwijqv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtsifrxzcm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtpldjitkb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtqsyuiuuv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtutrqkcbr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gthrcmpbyn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtncapoqut.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtamqkqugj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxptpzjq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtpqnrassn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtncqulqeg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtrtpkrvvc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtnmmtecyf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtlapaxjcg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtwekjfowp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gtwdybcipq.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtqkqmnsmy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtzervyiso.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtblivnlno.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gteoueojol.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtmczfolvm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtiafmqari.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtbrqedget.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gtmqnmsjyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfxeuggb.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtgmoekemc.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwobgkhz.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtqcvzzghi.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtsxhjrqvl.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtwmubfnnv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtfevovkkw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtggqbtyrk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtebhbdvuo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtlgtqomfr.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtterpmbww.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtivyjlyxy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtlenqqeny.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtdgxgyczl.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtopsnppbi.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtgdmovtsw.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtgzibhneq.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gtyqmkaqyi.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtufxfibbf.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gtxyauktww.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtktozlmtt.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gtqvbfgmjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtsdiblnqb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtjzcvhird.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtjkqcomqy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtjjohxtsw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtuvoygxbc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtknxoczbu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttvotjxpx.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtiddmaakq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtagpvgrqb.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtvdfyjtrs.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtfcbtytvm.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gthuopiogj.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmxuzaxd.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtrhpbboff.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtsnwzfcfh.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtrzcneiku.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtghvbgdsx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtzhwekogk.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtrklgeznk.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtsotlpypy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gthgixaqfe.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtktiyvygb.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gthqbdcsqr.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtnbqbhvko.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtdiscwtkp.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gthrmwdoec.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtxnfdxdof.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtblcodtti.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gtxkuyinqc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtawghisep.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtlscfihac.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtocwezvbv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtkikdhana.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gtkckwsmwb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtqudkexry.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtaixfboxh.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtoqlnqkab.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtojxelhha.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtltpdjxjg.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtxgmcphdh.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtrmyantzu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtckbxlmjd.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtbgagroaz.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtibuewzem.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtlqwwzmkq.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtlwbubjzg.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtgkhhvoyi.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtdfiqyzqe.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtpfdrjeuv.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtzharguug.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtntbzbwmd.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtbxjmvyrh.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtkmcxqvoi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtxmfaboro.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtfgxlbrtp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtlajlxcgq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gtypnyitgn.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtujidjhwf.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtirkiczww.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtnsqtskwy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtzwdwavmh.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtqiyfpmmr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtrktesbhv.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtqhvyndcm.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtrbsxdabt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtlypgbgfa.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtkdpisoxj.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtqolbxzsm.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtkibpajax.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtlcnubuqf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtheyvriyr.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazgyvwwk.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtybcbhksn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtqflxkcmr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtmpfrkdlg.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtyewhsmkr.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gteqmorskh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtcaatugcg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtzpokchrf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtfblbzssc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtluebheqx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtftssswgw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtmchrsyax.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbwiccccx.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtmshozjan.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtynaniysw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtzpnxxxgz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtygmrajxi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtfzhdwhyv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtcdgtfenj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtwgcpktqt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtkjrwelup.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtzsynoddz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtbmuxdwyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtfbecvvii.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gthyyxlnnn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtwsmqkymh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gttjapiahz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gtikvyvnry.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtrgwgzglv.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtawmekdue.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gtyohprqiv.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gteiudcizf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gtioqjfgxy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtyzsugobu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtzchrvkyi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiazqhll.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gthejjaabq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtdmnefpil.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtceepjqcp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtzzhtxxwu.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtolihiira.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtfdkygonh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtcjnojprn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtecudqgzp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtiflfslsh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtngoqhmtt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gtegrfpicz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtliekzlig.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtzalcxhaj.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtdhvgirgc.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtmnheuesw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtfuwkykig.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtrjqofevb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsxgzarli.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtjzembwrv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtawdvpqsj.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtywpxuugt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtjjgofvjs.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtukpmjpoh.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtmbauwgnm.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtdqighdyb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gttqtdypev.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtzawlcpvp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtvaxeclim.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gtnwslvbly.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtkykzshnk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtfeuwgeqo.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtzdirilgi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gteizaddyu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtogsmezma.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtcoetzabf.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtgpdgupmg.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtdferueys.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtzkejqazo.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtggwhhafz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtosktvfbw.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtrjaijlkg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddhqcbjh.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtxlnceilo.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtskqagzif.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtzqaxgoib.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtrlzcejys.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtuwgvlula.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtwqpuyijn.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtxmtqubdx.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtoqbzoews.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtfgaesjgq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtlqzfggxn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtcomqcrvh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gtqvtastio.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gtxnfykzdc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtpozlkrzc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtpjmudgvw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtcdpryttd.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtwllpzrnr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtrfzbvlzl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtxhjuzobi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtfjtdqzhc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtrbufcznm.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtzyethdco.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gtndvbcrmo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtfflwkhms.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtyncddnil.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtrynfsayl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtqcczplzh.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtdgsfcohu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtrndhrevg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gteqslcucs.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtpuzbpvzf.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtscplynfu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtysyxgxns.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtrddbxkuw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtpppjzccu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtfiaxcszk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclbtlhqh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtgmbzfvhc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtlfuyhjna.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtzuwnhiyp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtxxxkslwg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtoplgmbje.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gthuuaaerc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtklerwlmm.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gthjiyhoyx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwxeqlirr.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtnebdfath.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtqixxxzrr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkdebtwu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtsqnveguy.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtqfptesij.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gthcpoteki.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtpguzmpvf.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtrzbxuasc.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gttmhgxqhv.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtizaicram.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtntbkrfry.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gtnewqgrvy.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtbydwaryx.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkuggdzj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gtftffuikd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gtsgaomqwa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gtlnmbygmg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtywnmkyqz.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gtakvkuvcg.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gthnmkcpie.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gtrjrpfcra.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gthvkxxduh.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtytowrpmi.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtgvcbpnis.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtnxaywnvi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gtkpjveqee.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtiywjexbt.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtlkrshzof.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gtffyxvcuu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtfhvhplci.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtiebprsgh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtupgrvwzo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gtvsfwogoo.html


<!-- 参考信息 -->