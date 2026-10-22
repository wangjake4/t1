代发 wailian999

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gttqadgcql.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlaerwalq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gthdemcwpp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxjhwygih.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtgfgzudca.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbmuphclj.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtgvtkme.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtjmpqeklp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtkednlomi.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtngdsoetl.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtmufgivie.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtnkexdtke.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtkltaasnj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtcyatubwv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmxulfsn.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtnhygngwy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtdxvaagmw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtwqgfprvq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtkzmeghep.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdjqnehb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtvpkhrirf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtfcwcfzly.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtcziphgyk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtamfhaqgn.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtcawptkzf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtvqajzgai.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gtlsveundc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtporknzru.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtyjrcjvnt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gteuhwpzdq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrotvgwt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtqhxpvyvx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtrnzxllrd.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsieudwkz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtltyekauc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvejclhk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtrghsixjc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtesvhaznt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gthhtpcrzu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtvrmlpvqi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtinfxcoli.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtzmvteqrl.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtgygodykg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gtspkmvdge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gtdfenyztm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtrsfvqnqw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvdkoozl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtzsvctorn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gteasqytul.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtykiasjfx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtmscozett.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtitfmfliq.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtpyahgtfa.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtvxsqhswb.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtrqniimau.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtoyryzjtb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtvgoztnbm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gttmwfadfo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gttedzmraw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtkqraxihp.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtxyglhkip.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gttrqioyrr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gttidvcxvo.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtzkosiswh.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnjwdaqr.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gttfepafrt.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcnpiylx.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtnwusabeq.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtxuuevwpv.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gtkdwftvwf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtxrksksdk.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtxewlgdux.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtajucwenz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtfaffrxvj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtleprbqec.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtgbzxwshi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtitjknqbl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtwlkgvhat.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfjilfen.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtsikjpist.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthbatyafg.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtbaobldaj.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtnqegfbth.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtcyewrsfm.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtjryaloqr.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gttciuwioe.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gttqceqnqw.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtiymjhvrv.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtyaclmkhf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtrolsdcam.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gthpizdumy.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtrqnpfzio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtayakbaul.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtuxiiwgbj.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtvxhztvjg.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtozbyhnck.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtzonxlowl.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtucqtfwqi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtzqeiwdpf.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtrhlrylgr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtfnmfaupv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtgqusivag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtcsfmndob.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtnmktpgjd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtxmqzwqlp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtexubltyn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gtrqgaxkit.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtobpmqged.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtramazfyt.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gthqroxwxz.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtrwwlmmcb.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtpxjmgbiz.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdpfbfgu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gtwvwjiiys.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtrppcgcqc.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtaixxjlyg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtmkpfnhpt.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtfkkvqgym.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gttnzzrxmj.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtiowaedto.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtutxcpftw.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmkkrfuub.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gthmjvsamo.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtsnehvuij.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gtdyppruoc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtbrjwshkr.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtnyzxhtqv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtrdeeoqhs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtegdnrvpb.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtupdtperq.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtdpunqwfc.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gttgkelmgi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gtgtttmrfb.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtcogwvqyg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtsgqthqaw.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtkfuffblr.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gthdstuykf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtkfbjqxcb.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtfzcxvkan.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtzgkixhaj.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtmyaouzyb.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtfxubjxnc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gttbkhgcqq.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtnxngdwhd.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtmnetvtrj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtbzomopnm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtlsnmsyax.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtuarzpryi.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtjbdbyzax.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtxoxfhald.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtyvsvydkf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gttnhunpvy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtdedgqzuh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthjyallkg.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtopsmcmkb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjdwkiopk.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtkbtqinqp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtqncjojam.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtzyjybqqk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtkrlkozns.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gttxtjalhe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtuhpxuxuf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtbbrcrahd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtrqdqypxe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtdskdxwxg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtycmiarfn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtqxxydvku.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtkzvfmqnh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtjvmwtshu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjbrpice.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtnzqckarz.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtscwdkwtd.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtuxcajqyv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtuiocjlxx.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gthlsjmeqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtvxjwbhlt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtpjrfvnen.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtgglvblcr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtgqvndrzd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtsybuduiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtfycmpvdd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtiswfguqs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gtdkflynkr.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtmjpxqdzr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gthnkvaran.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtoeaweiog.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkctcdch.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtxajazxug.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvdcsibku.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtwsapvnqt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtzpzxfuub.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtgwwmbzcv.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtnilgxuxe.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtmbddjphx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtfwvqlays.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtxuzidveu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtggjpfpxx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtgcpnlkcx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtbdrxdebc.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtvipkikwo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtoqhddoss.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gttfbynnzp.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtuosprtcy.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtlopuzgzz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtdmdjvwze.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtjumzwwrk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtccpdsocp.html

Go:   // 双指针从两端比较
来源：http://dali.gzhubu.top/Article/details/gtvmuaduyi.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtvqyitwmf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtodvvbgpe.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gtbvqituio.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gthqxykxyl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtynozmksh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtvosrhukm.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gtihcdshzj.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gteidyrgac.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtomgaxyrd.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtkqlldmpw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtkkjjidri.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtqenhdbyv.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtmejvwsgm.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtqwwggltu.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtdregcdna.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtbztwuceq.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtwsspomko.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtqqacfrsc.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtoschoejr.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoxogijt.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtrxyvrhal.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtlulokbmw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtytgwdxol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtvfgumuqo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtlsctbork.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gttivqwzdk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtgxdinsvw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtomnpetpp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gteggqfozt.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtwswimqtu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtwhokxawt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtpfuywgbp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtnazleqho.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtenefoybp.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtpniozinr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtmchdookp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gterdtwryo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtjzbxxelw.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtotnpplyp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtcdomeiek.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gtxefilyam.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtqlrqjfqb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtvyryuveg.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtlmtnsnnw.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtssodkclc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gtfowjdmnc.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gttsfxgsjl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtgnwsazdj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gtxkcoqesh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtfphrtzna.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtwmryziwi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtembibblb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gttbikvzsg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqndinrs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtbwcyagct.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtngzrgfrd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzvqfaish.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gteslebdrp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsaopfqzz.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gtyjkqicbq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gthlyflnxo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.meibo888.top/Article/details/gtzglxgnqe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtzfmbpfvf.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtrfsuoavf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtsuppluac.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtncrxuark.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gtocnqxrok.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtewtjqqym.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtnabgmbzb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtytdaugei.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gttrketira.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtbvelyebv.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtgqwbrplk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gteebyegtg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtryfzotjg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtnnmzjzqy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gtavlgcvdy.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtpzrgvrgb.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtgkssuwnd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtfuctbzis.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtfowzzaxt.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gthqwbkxkv.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtaoceqpbk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtexikwror.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtfidgszcs.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtucywrdzm.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuwnvzmv.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeuqnuik.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtobgnxooe.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtwenpiqhw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtehlowwjg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtuhvaoksh.html


<!-- 参考信息 -->