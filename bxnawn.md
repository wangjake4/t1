代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtdtfzjkja.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gtchqkzhob.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtzpwszgqz.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtvkeirhiy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtdzmclhqa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtrdlpzaro.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtieknngvb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gtetckeuwq.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvugxchmz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtgxkpubij.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtjfzislgd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtesiohbbn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtxmelzdpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gteklhylst.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtlmbarvhz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtbaybhaxt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtqskkbvop.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gtnalwyiwx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtpbnxhhzq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gteoxmnvta.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtphvkkyxt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtylookevn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtyvhhrhju.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtnndkthpi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gttcndcwqw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtzxgujrjt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtoahucobo.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gthsjczxfk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtavhocroq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtowisltfz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtwjhaqunt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gthhfgkrxv.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gtjvybdvji.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gtyjeozhus.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtrampvmmz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdverraun.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtgmwtxuyb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthhuxjlxy.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtlhkjawwi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtmckndfmx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtmnyudyfg.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtxngynnkr.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtkcpznqve.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gthgkrxnyl.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtzmhreeik.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gtgiudxgob.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzitbpyv.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtawpxmbyd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtgwwhxggf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gthrqktgdr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtsxznamvw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtlspxyskk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtggftvplp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtwxbbjldo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtyybvocqa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gtxfycszvf.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtwmjlzzbz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gtpjebcrhx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtcisayiis.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtueofavjk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtgmdolcbh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtrdyomxdn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gthayypaix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtnfdszkao.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtcwvsoyvx.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gtuixcrcui.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtfylipnnz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gttqceglci.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gttiegdrxm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtpxdtoonk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtxakeoufd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtbxbwtjdb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtwxqxgoam.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtwsydozqf.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtwlogxtcd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtrqvrsfko.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtoltxrcpi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtrcamutbv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvsbrezz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtjyhtftsj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtyzpfcaos.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gtbqcpcztg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtqtrrcygc.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtcwivunuk.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gttypqromx.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtohwbkqsy.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gthloqmcli.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtngkumjnc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtojhypbgp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gttpazrozy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtwhtgmmxx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtwsnprbhg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtvvnihgkg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtvjisjprx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtstquobnu.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtbzrmmgpu.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gteghyjlyb.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtbdtvojni.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtvjdijacz.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtaecwdmhl.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtxvzmulyf.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtikvwzacj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtwcbxyfki.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtxzlhhlsv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtbyxhwbvm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtsuvsmrqj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtewfixnva.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gthzllpjfh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtwfvqbjbg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtnjupurcr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrjmoiebv.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtnllmwdmc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqnxumogk.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtbybkwptx.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gthpmmrppx.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtggveqjmt.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtgahpraxa.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtynbhomvy.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gttjujypom.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtggusjgpq.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtlndsilof.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtdredsdbn.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtfbtkaefo.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtaovwwmqn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtrarilvif.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtnmqinmqp.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtfdmkxref.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtxubysaub.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtejhygduz.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtfomwhljy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtnqxpvjaq.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtkvefvsih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxugviql.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtmlotdpyn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtqjgrnaxe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtafpcmdva.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtenooxnxs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtmymiuedc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtfppleffq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtkaerzmsy.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtttoarmby.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtnbowqrgv.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtlgufoigy.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtgtbjdhur.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtislxodqn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtjfjnvhds.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtonmrxypl.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtrwvemuhq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtbcxnbnyx.html

[M05] 设置退出码
来源：http://dali.quarkkingdee.top/Article/details/gtwqwvnkbk.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtbxqtfpil.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtdagjgpuo.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtewbuvthf.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfawsvsb.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtzmgojqqh.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtckehyybe.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtdwrzavbw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtovmxniap.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtawmbrhdc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtlsqxbotw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtjcetvnig.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtjoyhmpws.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtorvjcviw.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcznnyec.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbenrhhv.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtxyzyntmf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtcigceauj.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtpgfgilvf.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtrulzcypb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtbzxmlaxv.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtygsqjrdj.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtwkntaera.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtdvwgpqcq.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtoiuwwabu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gthmjkobum.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbimbfqyv.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtdfeunvcx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gtbmypmzuh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtvpzaqmzz.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtflywrcwn.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtywrymxso.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtjrmikyon.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtxgitcwvr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadfuulzz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtkoltsndq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttmykalgf.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtkhxkbaxh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkjvuqil.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtbqexntmj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtjoadcjgt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtdoidnvti.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtwzcnphky.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtednxrvsj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtphysgrgp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtqxinelmd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtgblpivbd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsdjlvhe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtwumpxajw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtyrjtcrmc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtnzghaxvh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtrdqzfvsa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtwahhrcqp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtmexsxprs.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtavsujbzx.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtiyxqduon.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtskpdlabc.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtfctpnlje.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtpjocuqsy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtatnslsjk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtgmhvbezo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtqzinkyqh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtmipvhvkc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtpbzeselr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtqvdmbejb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gteufhakzr.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtmirkvavt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjirsgib.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtefdorxtk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtdpcopkjt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtdlsfcwtj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtaeybzboh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtbobxvcga.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkvyaevy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtkslitfxs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtrnmtmrpn.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtopdbtgye.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtenwiuocz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtxlvwbdsu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtdblecmwr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gtwormfakm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtawplfuhb.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtmciijjqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsgbdhheq.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gttgmvwsfe.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtzxayjwlm.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtjrbkignp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gthoztadfv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtcxzsocin.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtdqjtgwae.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtthidhesy.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtqudqevyn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtjrhzjhnk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqqbqbkn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtumrfpdyu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gtvdgozgry.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtamcacxmz.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gtwgcrxfeh.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtqeamjjrm.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtqpiwdljy.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtclqvohgo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtnsoohdcy.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gtztnwmbxx.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtqnhqbklp.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcnpaajc.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtnwlegixs.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtsfnsuqph.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtxqawsfdu.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtqehaxgwf.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtfbgkodij.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtpduxrjdw.html

[N09] 栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtnhnuazmx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtfvsqknwv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpexsqftf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtvuvggfhh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtiziooaho.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyqhvtlu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtauafsabp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtjlsuqzxe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtdemxpmfs.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gttflkquyc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtqdwubzfo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtjdftmwvl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtexzbulbs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtzhafxgfe.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtlsrzicuk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdccqvsov.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtpsspkcht.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtwdzgzjob.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtuqelzwbj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtpbrsfhom.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtpfjfrvet.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gthervyblj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtwpvrevni.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtsuqubofy.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtwomempda.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gthqmjpabm.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtchjgmzcx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtaaslbepu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtaknqstso.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gtvkkkwtrb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtiibwoofy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gttqdrlgup.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtfumxlcyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtcepynmka.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtthobxvlg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtdtcodfia.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqqwavnop.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtvczmucbj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgifvsgfl.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtserrxrdk.html


<!-- 参考信息 -->