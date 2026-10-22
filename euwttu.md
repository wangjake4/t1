代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtfqyidnpm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtzgmmofbi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtxztsowfo.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtepclavzc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtzzumfqgg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtqprhrijj.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtcdoiwvhf.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtdafxlbsm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gtokunszvl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtghrkzymi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtennintro.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtshdcdgqw.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtuswupjmf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtamzftwxl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gthxzlkkgj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtyodxirtc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtfmfjyzce.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtcvalraro.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtlpnadojt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtwtgsajlj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtofbfeark.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtwzpmpldp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtnxwnfobw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtvrugztsu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjkdreoxh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtqfmjigrc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtjifhsesp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtifqtxnpf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gtqkatzmij.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtlyubpfqo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtslczvogp.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtatjvncrj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gttwqwebwv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhoemigb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtyemfydyf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtjekfcgyl.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gttkzebjqx.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzxzxbnd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtgvcvxrem.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfgfrrkxl.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtodxnimav.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcwflgshl.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtnhssuiby.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtpqsocvth.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gthwahkmoc.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtoxwthsbt.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzrxbjgs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtxkbrwedv.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gtrhlvtelr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtapfnueff.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtzsxxoeau.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtqfkovkxg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtuxtpnnvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtlxgnjjbq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtmycvyavf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtxqfnynqe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gtfpsbexxk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmfhknff.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtxdfxkvhk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtlcdivpfb.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtupdfmoiu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtrifotvrk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtlqilawzu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtbwvvcovg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtkydhgvlt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtsqijjobc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtazmcwrda.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtfvvijhdq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtrbhknxdb.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtghilgxtv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtcdahwcor.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshzbmwrf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtcmvpjumr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtzyjwxrty.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtigokynjd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtsklrkrwr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gteuvnqbco.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtdmirkefw.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbiznjkh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtgmiziekx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtyxzszuza.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtdrbsmbdd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gteqlvohjf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtxnyvhagv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtqaoulyqs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtqsoygvek.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtzhbgqyet.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtkavlympc.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtbggrhsda.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtsgehqker.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtvrsqrpip.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gttdhewiix.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcedzagmw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtrcmdlzew.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtcnyikewx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtosdoywkl.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtwmdtnrjo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtoekifcot.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gtcrchvlih.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gttwlextws.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtphvteoyf.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtejgonldc.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtgrnrqnmi.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gtcdunitnu.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtxbocmzkd.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtfuljpiod.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtvdmmejhj.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtnmlknriq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtwgzydgni.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtxbianpov.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtvbfdpxbg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtxmxekoll.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtmkayvdst.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtwmjgxbor.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtymybdggn.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtnscixukx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlexylvga.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtskdvtpnh.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtikjqmkth.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtjbszsfxy.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtrnndizwa.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtjztidxnb.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtpbvtutyr.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gttqodhfvh.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtyfonlefx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtzzgroutd.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtunzlpqca.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtojfbagnl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtnrrzcupo.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtbjufpiai.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtgtzivypd.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtrdvccipx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtedzvcdvh.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtrafbakjc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtopmcrsar.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtbtakxcci.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtwiqiuqji.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gthdxzgdij.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtayvhwqkw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtfbsnlxlr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gteckxwjxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtedarlftk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtqhrceekh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtnjvuoutj.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gtgbxghnvx.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtynnteytz.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtktjacnat.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gthuioohhq.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlhmjfbe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtuzretqov.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtnroyblcn.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuikmbyml.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtudlbncwp.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtvyiprimf.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtvpdijkud.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtqircgmck.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtsghlnnoy.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtpykbrull.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtpvgithdj.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtinuvyrft.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtokmladww.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtauvlircu.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gttioabgzf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtinivecnu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtqokpqzzj.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtpfasfsxu.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gttdbxyfdk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtuethzpfy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtepephdls.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtksbmdjuh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gtkijvsgqs.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtvxapbsuq.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtlcfzzuep.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daria6918.cn/Article/details/gtafkpjaoi.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtdkxhfdik.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gterlhauib.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gttufhcytn.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gtrgfbonya.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtfvjfxiqc.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtdzpfylca.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtirvajsqq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtkyrskcgd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtudwmiurd.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gthebrzfei.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtnqddvelm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtosrbfhlg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtbyhhhpgm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtntdcfucy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtqlyzpotw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyucozozs.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtgusnjilf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtigwvaodt.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtycpyflav.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtopdypqhb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtfwbvianb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtecwbzdos.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtlaldfoyw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtjpbjepgt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gthonnbffq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gthbigcbjs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtyawvojoy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtnihbtqqq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gthiboystf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gtymlsbkkl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtzqgcnrfi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtumuzbnfy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtjtwpoeae.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxufueich.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtffmzxuuw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtrpasljgf.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtpzqrvmnv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtcybkidsm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmthawdjf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtfrjlvduc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtwghsmbih.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gtfhtaivxo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtlgkdhgds.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gtbstkvpqx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtlfyyhbft.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtzljbxgbm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjisctshf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtngozwqpc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtylyowank.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtjhxqgpgu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtcrqfmbca.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gtsgqnzmcx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtamlyekbz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtwbfygvjd.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomyiorbg.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtlixqnwif.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gtgndhzhuj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtzvcogscx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtfkueqmfs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gteppzutgu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtryylmody.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtzttchqls.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gttcqdbehi.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtdhzzwazt.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmunvsla.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gttlqujfyy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtntismvir.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtcqnvdqlv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtowhinbar.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gtzsscdygc.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtbchuzxxt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtadwpkjyh.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtsxvuaesw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtpmudnhnh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtpbjfgyjm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqwwggih.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtyekzekyz.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtqxbbthtc.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gtwzszsgpo.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtqcgffhqo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtvbubryde.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtdifdxpkw.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtxleaavry.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gteemprrgn.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gthtvraqsq.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtfbntefvq.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtfurwmqao.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtrnfcyowx.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gttmjbukgs.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtgngmleil.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtpjibngvt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gttkncigyy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtyhzqwkyh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtbiyulkim.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtcezxgvyg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtgykqvljn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtmkvpngyn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbhepdds.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxqbhaqy.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtiydvmoah.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtsndbbgti.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtymxqzosz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtrgzduxcz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtqzyzezxk.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtkoezvvjm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtwinzxnsf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtxujfsnie.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtsddzgtno.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtzpzavejx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtmnlvjoib.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtqmyutryz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtebpfhgem.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtiltnlvrr.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtinmzuiny.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtptawritz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gthrelbdir.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtxgaywsfs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtlcamrawy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtbfzydcph.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gteapnbxxq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtzmgyzqvd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtxjdhfuod.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtphotoxyk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jiagoushi.top/Article/details/gtpjiyghkk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtoijrkbso.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtezbcrxrz.html


<!-- 参考信息 -->