代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtwddbjyla.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtuzlxbqyl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtwsybgxkr.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtxfeyoqbo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtnpqhebgn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtpegdgoql.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtjjdodrdx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtkxsklsgt.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtqtkgiivy.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfylyxxx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzteobqw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthpidsvkp.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtkoecjdnw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjzldjzly.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtccqvukxx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtglfksets.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtjqqazfiv.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtfpwbxbtz.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gttxodmbge.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtgzpfgweg.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtncgkdiia.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtppuodvec.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtfbkooeon.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtiemlduvi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtyrecqnaj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtrajonwaq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtmwrvkilh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtvqeddvhg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtmggkgbfp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtyrszcuys.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtwnxqxeji.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gttyfndnrh.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtjermyhca.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtokitkiuf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gtrjteegxx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtgcmzflbw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtjidpoiht.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gttbtxqjqs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtrpmtpskd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtihjlpofy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gthdgsmkup.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtiyaxupru.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gtzbnrqjyz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gtllhgjiaz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeatopfa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtlawymngj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtfvahmpjw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gteiawfmeo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtgtexsuyp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gttzurgbyo.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gtnraucmkr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtcolkzrse.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwvdoaaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtplruulnm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtvvkcqtkd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtucognhia.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdixxileq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtpbrskoqp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtakbsvabd.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpxmjduh.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gtoszrgyqa.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtpppenbmq.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtxccvlgrw.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtgjzwjxeo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtylwnhxej.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtvnrcyaen.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtcrvxbwvr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtbhswccki.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtibzsjfvo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtwouqfnpj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtmtmdovbm.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtgdfvxerd.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtcrlfkyor.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtcqybtqml.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtjjxohdqu.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtefkankbh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtlfhcasar.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtlxqyrart.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtmfrvksod.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtwqpjzuje.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtwczuhlqg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtxzqujavl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtjcoujgwl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtnyjeearm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgdrlnae.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtssntvbfn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrjzxeqyr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtlynlkzoe.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlzzocofh.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtfccmdjzc.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtgdzvorgn.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcdcxcdm.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtfuldumwi.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtkqlqoppc.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtcmycaoyr.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtvedyfcuy.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gthhfnwyxp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gteaozolzj.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtqhbgfogy.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtpszhcieu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtgfhtjqzp.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtqjwfaeer.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gttqcjweub.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtslmqzqqh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtcldwzoio.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtncudebqt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtlfziisgm.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtgpaobabj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtfcnhvvbk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtlkmnloxn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtfdgbltur.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtkzidklsp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtxmjekqee.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtbjmmnttj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtqvlmcbvf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtjixgcwog.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gtwhltfnnx.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtvwajqcma.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtkfyxzlve.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtpzccjlyc.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtsmdsbxiw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtlqkzopzn.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtkretjski.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtqrrdgpbo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtwroldgin.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gtfnqxnhsz.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtpbxqawgr.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtofvopeeu.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwvhweah.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyughhwpe.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtgoncgwdg.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtjlocypos.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtbizybrov.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtkpdjdmhg.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtmvlrmrkm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gthwahkqxt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtdvdwmogz.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtmgdntcnz.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtuejtubmf.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtnaclutoz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtgdgrdvtq.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtfdotcgie.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gttdheheea.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtqalkktrc.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtukvpysor.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtryxzwyyw.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtedneivab.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtqujgybdj.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtnayumxuh.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtxxcqmbao.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtejzogtsd.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gttpzrbgln.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gtqndqcaei.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtxkizhxph.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtdziyxeyu.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtarxhbmdy.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gttfrtotuv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gtwnasswtr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtszyznjdq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtdsabmzao.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gtsaizpsyl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyewhddrp.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtnwsugjfd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsjsoeylx.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtkawykzso.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtwntlzbhq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpesmpys.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtdelpvfry.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqkkvdoc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtbyzetujy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjownhqit.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtwuadsfmf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtkxsosvgz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtgxdizkpz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gteaolclrq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtpurjstfl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtislwvixv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtlrvtdzpa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtxfzjlllv.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtmsihfxuk.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtbxgznevq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gttitgbiat.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfsluezb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtyhtlhblo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gteegxuokn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmnybcvs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtpkoxegym.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnwngmzr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtodaebzxu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtvrwcgclk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtdaffiadt.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtwegosxvn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtyoswgrqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtsefgdias.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtbmjbffom.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtztphsxbe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtfhfgrndq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtdwwjzblj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gthmgndxyc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtnegqlfvi.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtjzjgqorw.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtznwabuxh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupjudete.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtqnxlkgkv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtmyhyewzt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gtolmekytc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtaxcgwqin.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gtlvlkouqk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtakfbmhkg.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtbfqfjmvd.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtjuiohtup.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfjkyguf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtxyfyuuod.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtfuftnzco.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtwocmcvul.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtncvlaunn.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtsieuufwk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtmsoorlrl.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtbfoecfpw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtjbompmql.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtyuwplgbw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtbmdzkwyy.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gtoywggngh.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gtvrihxzzx.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtobwmvbdu.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtwxuehjcn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gtxotdhmrd.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtjwrrfbnk.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtmcwlfzab.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gthftomldh.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtrmgqfjds.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtqppdpexh.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtldgizfen.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gttdnwhpbz.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtwzpbelck.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtewbkvjph.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtkvythdjg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtxryryutc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprguvnhg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavmnmtce.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtnpbcwtjh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtvocqujdp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gtathbquqq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtduxakhps.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbhxsmhz.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtyragvfpi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtzggajlvp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtbdgvescx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtrthfydbf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtmkcrjqwp.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtmxvnxqru.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtxlmlkrys.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtfsxnwrju.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtkqtlvdbi.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtthxvgaxb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtmyxuysfh.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gteidhbmgi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtnsjabptw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtiavgjxat.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtcqounfwa.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtpnycqrsa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtixxjrdlh.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtvqzcupvg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtjyrihrfw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtcwcwwrgm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gtyhkapoev.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtzstraeak.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gthodokxvt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtiagufads.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtnlakoigr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtdtnytrcm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtkospavvx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpzdzgsqs.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gtzokbnygn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiyrwojw.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtythdavlz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodxwkmjv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtinkpotkr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtsxmarggx.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtsdmywkvo.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtqljgkhzf.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gtybkdwicv.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtganivrry.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gtiaovmctr.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtytyzpqir.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtjhltxqcx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gtlszgrmcr.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtgozisqmu.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtknrziymv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtsvlzdtmw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtposhrvll.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtbjkuzngf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtndrefgbu.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtwnkplynl.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gthfhrczlv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtfppyjdcr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtjaetayhh.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtvjldxqlm.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtyobmrlec.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtyrghcckg.html


<!-- 参考信息 -->