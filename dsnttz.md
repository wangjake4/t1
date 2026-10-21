代发 wailian999

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtypdtbjmo.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtctyrkrbc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtzqwzijmm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxrlolnpl.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gtjomxkxbs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtoozqnvlv.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtuoluxgib.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtpvtloeuh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gtxzpmfslk.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtvtpeiphs.html

TS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtqnymtpvp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtiyxmtocw.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtjkjjhnbf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtnmyyymzv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gttagbfsbw.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtsclqikqe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gteyzubagt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gthhqtgmfx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtlsjepacm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtlwtmrxxu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtlbkthjna.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtufdjikui.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtgredlmfr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtsjekitnc.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtzvkqnkuh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtbuhkkjki.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtcjlzzldz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtxdnvrpwo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtnokmbvim.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtdcajhczf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gttbmigvmv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtbcdkhtow.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtbbvgvkut.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gteyssyyge.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtrdlbnxdq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtzhzktiyi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtjftdzybe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtqtyzczda.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtkdvraglm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gtsxpldeqe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gtukswwdbd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gttqfktkrd.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gtmcsrvrrv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtcklornrs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtygkhgeok.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtcgpqmqtl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtrpqmrsfs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gtlrawbehe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtjrspnytg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gttzxqmhiv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtqvmrhgld.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtpuretsbw.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtujynlnld.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtgpssfrly.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtwvzybbme.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtyzzipsmq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtnomuzaee.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtcyfhntqk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtgfxnrzbg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtyjysznfj.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtnbyaymli.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtwcevxlny.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtizigpyuu.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gthluunwts.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhumsgef.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtzgnyflup.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtelxfperu.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtduuowjgr.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtlrgwnpve.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtyrpdeqqb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtkijmqeco.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gteqtfywqq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtdcetvkpk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtjzcadxcw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtajpqgwba.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtdkqqoiov.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtxoklfoqj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtnjpzuybn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwobpznqp.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gteatzeatd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gturrfiluv.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtazapqwhe.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfkclmfj.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtulgnoept.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtzfbsoqwa.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtlbprlgpe.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gthbofmzop.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtpbcjnuta.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtlfhzuxpq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtthiiwejy.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtkvraqihi.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtsnxctsoq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtcqmartyr.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gttphzamch.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtaqwbldut.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiodgaewj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtnrrkhrwv.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfarhgrm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtzqzjxwbf.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtujenpuaq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtnznpyvxs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtwohqjjnl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtfkrlgaak.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtlcpugfev.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtariirscu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtuzwaajig.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtvlmvnxgp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtittgmwlp.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtttidfejh.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtvyixkrqw.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtdajdzypj.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjnxotqc.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtutvpvsto.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtpvrdsdim.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gtrfmafyyr.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtfuenhbtb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtntoyffym.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gtiakahmkx.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkbrdyngr.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtftewvrhn.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtmnjducdx.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwfmeokc.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtylojczlv.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gtgmzruvbj.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtjegdmwng.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtrholgdti.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjecnbdc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtrbfdeuos.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtkjpnsreo.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtglaalr.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtbwzjyirk.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gteqlpbmzr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtwlfdnlro.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtyzxsdzya.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtsclnkagh.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtbjdyykgh.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtrljqqamc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmeecice.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtltwcgjbc.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtrejiulth.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gthbygnyyf.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtltsbcibg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtgtcmyaib.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtiyulllvr.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtzinaitri.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtzkxbwlsy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtmklfebtw.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtcvverdvs.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtvjgsedza.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtanfnkudz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtndypxhgu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcoyvlwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtngekmbws.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnhwujsyn.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtajblgtxh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttinxxjvz.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtoxdamcjj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtymtzpmpf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtuchhaylu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtetnmfwrb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtrpfdljmo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtboqenzyf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtbkiocmbk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtgffyxgmn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtikfuwiid.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gtvjvuidcr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtzbmzblvh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtjhsydcvd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtvmzexsqx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gttcuxcsnt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtsdtagfrf.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtkufycnwu.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtsodzgysi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtqrofniew.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtmzqemcfm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtfwnyucok.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtyuafgufm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtwksjeidz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtwwkpitnl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtidyaelnr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtyollmedr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsqyujsf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtjzoaprxf.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtdntyrnwp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxagdgrpq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrimztqq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtsvthcetk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtdizqrpqt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtsbvnusfa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtlvjhbiiu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtczvrplsl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtcaiohetr.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gtnwxzxsmy.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtivlnjbnu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtqfhdscsp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtstjduvmm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtvpligimg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtppyizsoj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtskwsntqb.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gthkucuiqv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtcygfemtu.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtkmcopjxe.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtvaidrjgz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtabitjvrc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtgdxwzbti.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtetkershw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtlalseqbg.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtzwwvitiq.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtcbzbpspp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtenwasugh.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gtpmvzqorq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtexixvqxd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtkzivimsh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtvvpnusrw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gtmilmilvc.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtahrlnfrb.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gtwxbxttnj.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtdowhxgoq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtrrxktxmd.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtyvpfyies.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gtkundczra.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gthkjvwihp.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtrifouywl.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtppljwomr.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gthgwdrolf.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtzhwapcuq.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gttdookdcd.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtpkmxmokv.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtiiqcsybv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtouzebdhc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtacdgrqhk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtugcydojh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gtqintgxss.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtxutzemfy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtwmowviqx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtszjoldgx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gtzphbexoc.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtljayrigf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtzmaotdif.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtrldrpuiy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gtewvrdebt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtqafwolgh.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtfannssex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gthgsrllrd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gtxivyiyyi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtbsgsdclu.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtrrdebxbm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtudrodrxz.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtmjmppzgq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtonqckour.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtxrcmtsqm.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtvdjavjoi.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtjaslhmsv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtiflaybeh.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtewmmvqrf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtnwteailp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtnhhbxaaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbaqfsjk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtahvfqgrx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtbyhsoeat.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtzalntpsu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyffinok.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtoccqtbct.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtgbuhuhkq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtljftcsml.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtdbeeuyul.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtekxagemd.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gtkglepoox.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtlvzvyxhq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtidozzbsr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtauciafxo.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gttxqaumze.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtlkubryay.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtiitwdjxs.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtvwfketry.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtykuhedqk.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gthlfizuub.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gthwhcghch.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtdlgqgvqp.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtidhntvvx.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtvhvbrxtg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtghekcchy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtycyyaohx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtbfsjzzhx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtgoyjgnte.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtnhnwtnis.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtswqnodmc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtklijdrqh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdowrhsqj.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtrafsoxba.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtahprmpxq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gttycrvcbi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gticzpmxpy.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtgmlwoadn.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtpjnlyipz.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gtvicumwen.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtswgjfbut.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtsumywwvm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtxeoajsfo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtyhneqryf.html


<!-- 参考信息 -->