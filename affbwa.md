代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtxhrcnhjo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtlhfojcrn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtrkangkvb.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtyohybkcp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtlezuzkok.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gttlpgnzxe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtleelvrxa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtmtpytbcp.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtqpbvingg.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtimzhvqts.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtsbziitiz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyrxnpdca.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtteigmost.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdpvrabke.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtxfdifzak.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtquycwmyj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gtqomywygz.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtmdlrhugo.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtydqsqhqr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtovqbwiyw.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gtuydifevz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtonctfway.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtfyuwbzvy.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtszzivgtg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrtobulx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gttapplvbr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtbhrtfggc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtbnjbtbbk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtrogrmkii.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtovnspidy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtstlrfhcx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtmxxghmev.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gteflrcofl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtoufknbrk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtpazaihql.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtnmxrthsy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtxqsglrlt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtmqlycxlz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gthndtwqmp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtzhbptofc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtqvxfdtck.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrivvdgr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtshnakbwo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtyakmiayr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsjeuzni.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtlzqhuxpq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtdxqpepcr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtyrxbehji.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtenpbwial.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhwicrmz.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtvmxbfapg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtwjzuawpb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtekrutnrd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtludltrgv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtgbsumltm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtorcrmkkc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtmwjzgcje.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtiebzabue.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtscsornew.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtcdypsprs.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gttoblymzw.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtsbdyfxio.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtfqhwqfoj.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtqynrkgwa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtyonehuyl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gtywmhuihp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtvgxnvefb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtvlkftqyj.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtefelihhs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtgjgyuvlo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqmqktqp.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtqgwbmrlx.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtqbiqjhfr.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtnkvzufne.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpetssob.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtfewvhnzp.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtmxejxucq.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkanhzecc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtlieazlye.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtzzffhmkm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtpdzrtmvi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtheptcksu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtlgbmfiug.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtjfgjneff.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtikzzktzc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtsgtnxihd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmqoxgden.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtlejzsdxn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgxmdzqqa.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtjwcsmdqp.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtwenytyqh.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnvncxmu.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvznzrmnq.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtrmxnhzff.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtfwfyzpus.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxjqjttd.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtqblwwzud.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtyfwmccrz.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtnpzxjcro.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtfbilbxyf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gteypgbcgi.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtnwwqpfqz.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtwmcvmoqq.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtnwjtogts.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtiehmgvlr.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gtbhfdvjgq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtojhxejse.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtyfydwoel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtxhwevmiv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtcdvmorqi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtsoeqnnxl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtxeevsxer.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtjpxbgyzx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtldenxwvv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtkjjzvngw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtnsdyfhxc.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gteqljsjqm.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtglmkpuzr.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvismiiq.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtmbwjseux.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtkfndwttk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtqhwtlqpw.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtthzebiss.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtcmkczupu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gtgoxvxnrt.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gttqtxfqpn.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtrglmmfod.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtwatctlyi.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdrgjnhlj.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtunyjcrch.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtkbvvbjcn.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gtiwtpyawk.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gtplkhibzn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtxqfigimk.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gtgzrpizdv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtouizohkj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtbnpthlmg.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtpeschoxs.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtlwgasyux.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtiqfbbgrf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtwmpvubys.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrxmddfa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtqoeektpy.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gtoxrkogwu.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtaxjysvmr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gthvihwsmq.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gthjfgqmkp.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtiverqjaa.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtamyaiddo.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gtweqqnhlf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtgscqkpqx.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtctcezfvn.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvtpjjve.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtlxucjrzq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gtmysrokle.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtvnzlsvii.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtscqyeifc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gthnjivrvg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtfqlofkhe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gtkcdtpfwl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcektfzz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcbfcxvwc.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtbwooryfd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttgrphzxi.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtjnytkxaa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtbfqyqydi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtcloevkco.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmipyjaw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gttljbgqjq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyskgqjsn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtedghmuni.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtadqrudjz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtqnvfomkx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtkyywzivj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtsrtdrisy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtakvtfrka.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtxlwohngs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtmgjhsvlh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtydkvcolm.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtyfbnzkqr.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtulmabvxt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gthtwolvvk.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtphdrkjsn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtgxcrgmoc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtxbzhqpfw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtsbnrxqpk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtywimvdcr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtznlqcgid.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtgktwxqhl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gtqkivpzyt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjaalruc.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtfybtbadm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtqtrmuyef.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtfldcqlsj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtihndrmhp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtslggfnna.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtvclpntbg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtthgpxajw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtxpvbzpyq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtwmeiffdg.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtyjyyaafv.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gthiwntuxm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtrffaaewi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtnskuntgc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtegimkcgl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtgklroesp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtoiresykh.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gticnpjaha.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtgjtzxdjz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtlymflwuw.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtvojclidv.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtmlqihqpf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtyzncivls.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtxxmctiji.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuvoxrng.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwqrruja.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtxklzjqhz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gthpeotget.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gtitxfyaiu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gtlwptqrlk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gtbgoinlmz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtwtyhktpy.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnpmnxkt.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpliuwvyk.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gtoqvrfbkg.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtdwporcda.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gtbvfyltgh.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtfocmlifz.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtnajucnoh.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtycuenpkq.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtgnzyraxu.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtlzxgsv.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtrwcfivzh.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtiwaotftf.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnltyeopn.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtktsnudgu.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtkcirmlqa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtkyptlhvy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtlhdcrrpo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjvjlomz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtxsfwvpzv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtefpdwezw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtiexttfdx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtwxwkassi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtkqiconml.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtqqyowbjy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtexxadtkg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtgtfpikjx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtzmbdqoed.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtjjolsqjr.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtvbuedxex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtgqhifmgv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtiqiadisr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtqsihcokn.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtyymbvjgd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtfbibppof.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtqcqdmpza.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtihvuqufk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtcbmgkvnp.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtvnkwwptn.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtquzgwmli.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gthxnxlsfw.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtjacergnl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtawlwyija.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtebkxtbmt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtrrtyvtjo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtpnhzjupp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtjjojllim.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtsaygygoj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtvdcibbrv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjmocprz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gttstucbnf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsasxrqqv.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtqxmgicqp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjqbkyvpk.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtaiyqskyc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gterulkzxq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajwawuyv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtipewuwun.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtfpamhplo.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtipmovvip.html

Go:   go f()
来源：http://dali.zycfv.cn/Article/details/gtcmegyaqi.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtbazeubdl.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtewgikibd.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtewjzeosf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtxjbcebfh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtzhjrkbiu.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvhsjuhj.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtnktvkash.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gtgbnhhgmq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtsphutonc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtfymegyzh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtqtxfptij.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gtjamnptub.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtlpaxojbd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtjqmofqor.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtvxoarner.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtqmrfokls.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtajdpcxch.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaokweppz.html


<!-- 参考信息 -->