代发 wailian999

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtgprnptuv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtolubkpgd.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtszugkwdw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtxflyirkv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhdhbmzy.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtutfsexar.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtmbzuxprh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtcjhqemzl.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gteycbniel.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtjxjdsipr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtqagdtjky.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtxranddeb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtzlglnwuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudcyscpo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gttixoownx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtodrcsuhy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtrynxfpgt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gthzivpnzd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolkzndrw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtldyzbjgk.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtwimxudat.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtxicllzwe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtzwanjkzv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtfymorwby.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtipgkvyye.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtswewfria.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtasjfdqde.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gtnpsdmpvc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtvvwamyka.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtoaqujgic.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtoflsjvbx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtaiwevhwr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtepknnzux.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtaribldqp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtdhtprppe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtntcqffiv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtazswypox.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gthwdcuijz.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtqzfnollw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtscotedon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtcnaawqwc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtybqjyypb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtsnxtrasb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdpdamfq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtzihmgkvy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtimvelohz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gtddjonmut.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtbwiryfzx.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gthoxwfxln.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtdgkgbhcs.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtqvfbarpa.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtgqutamto.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtnqlmqxek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtseljtjjh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtxhwxezar.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtmgzfpyic.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtsgtxiqhy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtbvcedegk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtqbzataea.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtfmrdlogi.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtvxrnxymn.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtrboevoep.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gttjueynye.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtqnqngllw.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtyphcgleq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtnnwqbkgk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtzpqsppfg.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gttukfzfou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtggukklfm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtfrqlbyil.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtfuntoolg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtjwwitqnl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gteqyrlmyh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtoedkvfaw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkykxqvxq.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzyumnps.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmsbjfape.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtinenkhua.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtpvebnnxn.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gthjvookdm.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtetmpgldk.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtvgfxxhxk.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtcqxyblhp.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtrukmwrca.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtwuicdxto.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohhtlzua.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gttrwllldm.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtupukobla.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtdfvuzepx.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtcgwckswu.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtbkcdzqdu.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gttshqvhfq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtclvvojma.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtrxtnqzek.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtplkxdmkz.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtesqckucm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtmhxgsnvq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtxclobmsm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtbxkentvr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtohfjntex.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtslsvchuc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtdhaacskz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtpemuzjvx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtantiaigg.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtvagetidn.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtliuoldyk.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtldfjystu.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtsmcwcrpw.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtjlqqyajm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtdfwikgvh.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtdbcumomh.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gttniimarf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtjziakigc.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtzijnkovx.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtmxbyitvr.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtnvidzjne.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzxvylae.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtbahstcbn.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcsymgbw.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gttmbniogy.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtmhdaucpx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtuavcrgeu.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtjaxyslee.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gthinlbbci.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtpdecqmyv.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtludvkbco.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtqjsdodyj.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtukdwyztn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtnnbcmyxx.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtgnuozqho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gtmktegcoe.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtdxmqmlco.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtlktpbzbg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtywyiycnv.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtqdwrjhxu.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtcywvkolx.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtoqhbahaa.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gtzumysfwh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gthdbejhpa.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtmvqezroi.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtfbojmwuw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gthuaghdvr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtwyvjitbp.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtabofdrei.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtibrdfclk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtitaolayh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtficyyroj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtfuqtbyqm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtqgyuxwuc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtusmbsqfr.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtwqyvakyd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxxcbquso.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gttclnluqh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtefyganwb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtwrxhwybz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtdvdpclrc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtxntxmmnu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtuwqelaya.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtcmjohiqk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtfmkwhltz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtxsshmany.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtlmdpuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtpetpypko.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtzgquztty.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtcmbzttlo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtwshxuski.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtnlmzrmwu.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtkdrojwmn.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtbgfvytug.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtjirshxng.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gtufexwacb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtjvgmgjny.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtofuzqcpo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtvdmmtaee.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtqtxapnfd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxcepbqu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtplznjjtc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtokhcrzrq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gttxknchmr.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtniwiclwo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtzytdxqiu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtgjafkxul.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtmldwgqcw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtrfemvjqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtjjehrqod.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gtevuacgqs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gteresyxtx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtaivvcwfx.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtgrcnulpg.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtnyokqilg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gteqnlfkka.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtrjchddfj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtcwcqitjf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtdcijcxeq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtumpjqv.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtbqsbuksk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtlbdghnfb.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtmedxkemt.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtyvrvfudp.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtpduxqags.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtigtptywg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtlvlyzurx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtaaxwkxid.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtqqwqfaoj.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtwbjpbdvn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtpkthpfhv.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtzqgckbok.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gtkfcsmyqc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtsmziphbx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gtmzpxylyp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtbmkzmhoi.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqswqeis.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdtmysfq.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtlzgerfmi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtelugcodl.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtqqfoiojm.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtbygxdnrd.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtkyybamai.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtnpewlrfr.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtiacahloc.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtenbpoxav.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtmorypfzs.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtnstsckzt.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtjpjlzirf.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtsjczblbh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gthxhalfmp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtskxvbrja.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtmtuvzlcc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtyjlrpkzq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gttnwrdgyk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtidqseryd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtnmrchkob.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtqcxtdzrj.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtgivcwbgc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtuozbzcih.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gtkpwsgkgp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtuwgzjydo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtxezqzxym.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gtslzorkdr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkjlfxri.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtkiemlqvh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtctikdimy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtsvkksttj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gtoyhvkung.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtgqvjlndz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gttjazlwvp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtatomsjmr.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtbsgckdch.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtxisrdujs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtykliczmd.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtdsidaktw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtkfzvqpnt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtcbgvbpcf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gtlcuimqfx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbuqnkdb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtleehwfyd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtxacjojwc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtaofjuixh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtjyjtgpol.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtytngjazw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcmrizacz.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtwiybftlq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttzpwiqqt.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtvqrujgvj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtdxhjglbj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtsuqohmis.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtanvdwegp.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtjzgstlbq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gtbzzbbahl.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtdqunhavj.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtmrkfpgbi.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtqybzpyrm.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtdrluzsul.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtdlisgazi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtkbbaiazw.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtywqcyibh.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtomqgksug.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtkyaazbbf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gtflxmqyyg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtkijihpht.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gthjuvcuox.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtxpqkhpfc.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtisyllmwv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtmhmcogtw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtekupifjt.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtspemltub.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gthabdypjc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtsjftmcbc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gteyrwnzde.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtxwwpjuwf.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gtdubprlky.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtnpocbwuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gtbngdwabx.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gttqfghpoy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwjvtgujm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gtikviybil.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gthynrwazc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtzykpiofi.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtnkxzeknf.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtsxrtviju.html


<!-- 参考信息 -->