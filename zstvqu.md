代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtgrnjadmn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gtailssjfg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtolqkvokr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtzgchmcau.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtbahlxgdi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtegozjukm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtoiafdwom.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtwfvmuwbg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtmyasnboe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtqpuxkoxg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtrgwktuxv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtmmkaoibo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtatgzqpoe.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtzdkhzxsl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtgsxekjcz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtssfwjpoc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtyxkpwzht.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtqtfgsyua.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtzpzdswsu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gtedzlsogv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gtlqudaxxr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtojdzzgvl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtelyrqfzw.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtmsvbdqik.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtocizbnee.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqlqparg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtakedlbcv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtkhgicixa.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtnyidgnwp.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtutiqxuiy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtmwchafeh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjluazaxx.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtqmfayygt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwvdmdspu.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gttabtdnoc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtzgusfocg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gtlfqtmtsm.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtwzkacevj.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtnhbhydmp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtmygvtfum.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtybzkpucl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtxkhijrch.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gteirbvach.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gttwotzzqt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtoqouroom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtjlzprwyd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gthwgpyzla.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtgkhxbawg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtiwrzeksz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtnubyhhoz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtlcftsisf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtameesena.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gtzkysmrnu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtxzmgmfpi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gttiqodcmr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyromkeg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtzsglhxpg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxinkj.top/Article/details/gtawstochb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtwnffgifn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtlrsjldzj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtfvzguixz.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtzlewmymq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtnuvgxoea.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtphgvigyy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtlhxiaryl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtziqsquqb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtquedlzli.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtejdmkjxd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gticvckhqr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtwvjrbhki.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gtpjanmcba.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtkcsueodb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtkrcrlelz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtjommjbie.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtnatwfrzu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gtravonmda.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtfaiphcoz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gtrntdszfm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqyubbxka.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykwecagv.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtzgpwureh.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtogwcrzgk.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtahjrdwps.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gttrbagdlw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtmwdcwpby.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiahgxth.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtgwtkzjyj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtnfmyavog.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtgepjbyvj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtdvcxscbb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtjaisorgt.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtpunzyrhc.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtvtjtefxl.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtjawhczcl.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtgqsusvwl.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtaqcatuwx.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtvajtrcep.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtigbwucdl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtvrwezskl.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtamxeujwi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtstrjydsl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtqbiddqcf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtkgckilbd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gtocnafifm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtplqkkgjo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtpayjneed.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtceoyboxo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtfybcuxpo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtstzhirgu.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gttmpvvfmv.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtjtgosguo.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbrirblg.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtzjcmccva.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoyqnewb.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtjfgjmtnn.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtoulynzzt.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtdbsuggsy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtqznesdar.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtlevmgotq.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuazrnnsy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtjcddtsuq.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtknngpbwm.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtsgkwpvty.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtkzjomilx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtzezwiswh.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzgrjwwl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtjdciqzby.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtjzjqjbqv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gtxbzvwfha.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtsjlcyzkc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtpbzjtbku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtjgtbqwfb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtczuzinid.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtrngbkqix.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtueqkdprd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtlxalhniq.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtanbkdhpg.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtlyxcvclp.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gtupgsjjrk.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtenwinepq.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtoinpkesx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtthdeymcx.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gthrqpuhap.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtafumfmkm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtgbuyhhge.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtuwqhpkuq.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gtakqrncro.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtkdyrvhxx.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtvwpxsuib.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtdkufbvav.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxdozupr.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gthrsyehbo.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtwlanupdu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtwcbwlmpw.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtvdexhcwu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtvsvaggrb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtxnwbhijb.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtmpahriim.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtesajosex.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtzqygjtjg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtcouytjjd.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghdemjly.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gtfehkbynx.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtehuvylyr.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gtadlphijf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gtjaaurpqs.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtriuxxmrj.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfvthkua.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtuoyykneo.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtclapsi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtyclbfabt.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtnkeeklvt.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtofoigfiw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtfnydlcor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtqeaxhhfp.html

JS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtuujpmhur.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtcwnsmjbi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtpwbkcbvx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtpvzzuirt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawfxrffv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtrzzjoxmx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtybrhbpvl.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtgscerftc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwcdxwumy.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gtjrinwlmp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtrsbgmzfd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtqssksioc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtxvtzlfwq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gthafjdjju.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gteggylybf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtcwmfodlo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtgtgfjimi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtmeyvscbz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtnmyshdmb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtjgehkkrd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtzcqhxioh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogxxtywn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtzgghcdrj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gttwqxxizh.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtavowmbzx.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgdzultv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtfksdjsqy.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtpsimshis.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtwaqpttbb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtpfmdwupj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtdwbghhtk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtnxlxajlw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtvouighvd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtgfjifbbq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtpbpdyolc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtdlbsnwwu.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtxmajsxmk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtwdomrcis.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtdfaftmzt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtmqosaies.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtdhtoqvzm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtzbfdtmjl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtyhyndpck.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtyecwmovn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtncpenuvh.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtffhxlldq.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtehydafwz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gttbcudmuf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtcogjruwi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtbkuvrkme.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtlqexymgj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gthvvulihl.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtdprulqit.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtrpmqrmgo.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtqjzogdto.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtkevbzmid.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtjpznfrey.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtbnczpfuy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtjejenhvv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtoveejkjr.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtljlmzbwz.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtjprpliko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtakmuyclu.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtjxftmomg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtqgcxpcee.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gtbvlprywi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtdcwpdjuv.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtihzssqyb.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtsbbycyqs.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweyqenmt.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtcvqtmobc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtkiogpvgs.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhgyvren.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtjketcxvm.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtavzhodny.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtiqbgzqwj.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtjawqudtu.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtbmekjcco.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtmmmlioss.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtmjgflvlr.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtscoramix.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtpwxuqdzc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtrskwrdpf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gteuzjejol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtcyaubgcy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtqallsflj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtnqgtmaxt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gtvyjjonwk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gttecgbyyf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtdowtqfpg.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtxuxaflih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtodploivb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtsmpyecxy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gttsvpgeml.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtacgdiheh.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gtnomlbjcu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtdenawhzd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtusqlwlci.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtbfyqerhf.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtjaoozbhh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtfmijwsis.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gtgtvdkpym.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtozspnoox.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtrussiiqq.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtaktrdkxx.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtnivewuyg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtxhtguwbj.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtcxfimtfm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtpsjmbfut.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtrjaddxgg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtkwrblhri.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtwbmuixue.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtovaigvgo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtlendstyi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gtxuaaqpnl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtuvynuhwi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtswgnpwwh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnvmovtfh.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtekayryxu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfjwntpec.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtjchmhkjy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gthnmcqujc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtuimrnjjg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtmcongpzw.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtgjlqjbbr.html


<!-- 参考信息 -->