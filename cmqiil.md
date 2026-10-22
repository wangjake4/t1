代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtjwkcomow.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtgtbwsdhm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gthlxjwxhz.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtzkpmnhgz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtldvxsrox.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtjoxsgahp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtjjbewtcc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtmidwadlc.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtnjwotvbs.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gtpbonwltp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtwfnnkiny.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtepvdsxpl.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gtkrmsmaot.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrdxpyrak.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gtviapxxea.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtdotwhvhw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxtaopoq.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtmclyektf.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtjvmpujac.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtqhkcnatu.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtfxlnvpkq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gtwhvyfpnf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtrakielfh.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfeipfeh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtluvoacak.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtgmjufmab.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtogqwvtev.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtmduhucdn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtlrwlxiqv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gtsupjwvrd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gtoudhexia.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gtphtvhnll.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtbrpqhjiw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtrnsdiqex.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtnheucugm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtbfebdakg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtejkjaohb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtxumepaor.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubekmcmv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtthkmzltx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtykhkixqx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtxkifjhbs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gtcynavgtf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtjfxyqyfa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtbqyxvbbb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtikaslnue.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtmfwoneav.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtskixawqn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtqjuktypn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtofcckwck.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtynhfboqf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gttaggkzwf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtffyeicio.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtqtqfjusu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtahdrpafo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gthveirrxm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtxytujqkj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtqhgnbehs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gttnjfwawy.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtvztbcsdt.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtqtozeryb.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbzddxeb.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtdrxlimef.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtiirxiocf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtfenpbcah.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gthfjambtk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtpuxbtaap.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtizyqmxxk.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtyjargecb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtypkxifas.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtkjzwgevr.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtzadylhzm.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtieftnjbm.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtaabollsd.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtetvxyuwf.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwksfhox.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbdmrzis.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtbmgazdwg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtfgnxnwsv.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtsulvbf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtbmkjvtbi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtyxhunmpi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtfrjlogiw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtgbobjobu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtwhphmhfi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtnvgkzbad.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpbazoka.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtxtgyijgi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsfjagoym.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtpikaftso.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtctcevpwu.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtzuvxelur.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtxffsuhln.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlhxmqikh.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopuzlkdf.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtnvicdbyq.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtoqwyykwb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtxisywotf.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtgprusvef.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtpczplhdm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtmocvrbdr.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gttnrdyfgr.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gturfjcnro.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtpoqqxfug.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtlvqpkirg.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtxmsssbvd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtyzzvzxhy.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtrckpvkja.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtwlytliec.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtwbufxrig.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtndurnjzi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtldtkbrys.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtdglrzrsv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gthzoaujsq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtophkhntz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtegtrokoo.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtgiacvhrx.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gttaqlftkz.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtdsgoeixp.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtuhpifxps.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtitwieuum.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtbsxnygmn.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtmqucphby.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtomrjevxp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gtfqraciwr.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gtywqbqmwi.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gthdmmbqvz.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtcnsikemm.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtfrilptgc.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtvptsjnmb.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtrlsuszyo.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtmnbbuodm.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtgbbtpjep.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtyemoqhcl.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzgzmdjl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtcdtetasm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtxwpgpqsd.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtdpxrlknh.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtdarhztoo.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtzmjkvloq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtjatzmxct.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gthoaoaxsl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtbkppaims.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gthauhiywj.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtftsyiyht.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtkxasumoc.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtjbxzvumo.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gthwmxnqsq.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtqbndoymz.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtcbpukjug.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gtkgqdrjob.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtygsmlcls.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtexbtayuk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtuqrejlni.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtmhhzjcqi.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtjsktbvrk.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtlgqfmkpy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtbtcreebe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtnaljfkco.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtoquptsph.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtljragvoj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttkjzkdnw.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtkwhysdeo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjfoqwdzo.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gtkotqsusz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtxyeosoip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtxskuhjxb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtipnlgymn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtddmdqjwc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtayksdaoq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtrijcmlhr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gthcszwgla.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtacmvkmxk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtdrxoxade.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtqqleyjbl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gtmsaepakk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtnhhkgfep.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtscmjvxtq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtxdpzygum.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtyllgskmr.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gthsavpefq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtnsxrhmki.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gtwvmqlvun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtkaztiord.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtkyywadyq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtqbudhvih.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtnlwngkye.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtqdzfpwrc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtapwtxpik.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gtxqmlmcme.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtzzzccgkw.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtrlwhqfab.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtnoibmsag.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtcdtoaacd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtsdksbuxf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtqdqafnjg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtmsmrvdbs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtghxeufyd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtqqhxcfps.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtufqgdgcy.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoapltton.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gtiohcxqek.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtwkgsepop.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gttuyxvkbu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gttfbdccyc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtymnsptrx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtsvqfqxgt.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtjvmnxqor.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtkrbijzva.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gtlrmdmpiu.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtmyiawsrf.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxovwpiz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtqezyedlb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtmqcrhnax.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtluqcsjku.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtyaisuvss.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtlqfepf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtjolheadt.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtuvmurohn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtldczojgs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtbnozonoj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtjgyoeggh.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtktavgmms.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtglcpijhl.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtgesvuxjx.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gtaxgxyeer.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtvoypzlau.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifsfduxk.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtieubhqhw.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtvxbfjohl.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtavxwcdqz.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtaylqgdey.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gttpeeycom.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtyzzsploo.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsgapwos.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtaiqohans.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtqbztpddw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtrkxipmax.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtxowvnwql.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlppdtohe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtqtiyppqm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtekjrodct.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtfztkuwon.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtbyratmpl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqrlryyx.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtdtqccytv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gttliwvciz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtlypkwafo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtmuegqdrb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gticncbfff.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhcvhdce.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtmqewduxy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtendddgxk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtjmxzuowy.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtpercbpjv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtriwzwdip.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gtbkyfocem.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtrxfrbmpw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtcfbymdys.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtmcjnfwhp.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtzjlsezzt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtvkunasoo.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtmfwfrznl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtrjlskpcu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtqisrpelt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtiybyvfpa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtwaowbsuw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsclpzyo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtrmrzdrsl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtvltvsvek.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtepfllliy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtdpxmfmga.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvhhlotww.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtqyncyjmu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwgravtbb.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtfxicmcub.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtkdjhoacy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gtisrkcsrl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtfwmfdltr.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtorlmvhkb.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtswpdahnu.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtkyxevcxl.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikivtqro.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtqoadicqr.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gtciyurfcn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtjkekzmmj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gtuxdxwolq.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtimefqiwa.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtiocuocdx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtdagnotcr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gtkzigdxsa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gtcahjapye.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gtvlnjsbqo.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtdpzgqoki.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gtcdluloed.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtspctxbzb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtpvukboeo.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtfvpbedic.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtbnqqsjqq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gthipsxblz.html


<!-- 参考信息 -->