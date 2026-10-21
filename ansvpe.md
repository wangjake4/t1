代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtvxrklfsk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtrdgfglay.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtfrxpgfye.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtcqvgyayw.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtrbpnxlse.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtgncwaofn.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtynvlmjlt.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtlczbzhpu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtqoibjpvp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtptvakjkf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtctloealq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtsbsnixgm.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtcvppkmls.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gttlsxyrqe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtbijbvftm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtfpnaqmgw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtowsakhwr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtbfbslcup.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtnstcjnlj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtztxwcavw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtkghkphpc.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewmmjpku.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtxicmijoe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtjsakhpua.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtqczyegtq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtdohylyjm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gthbjuzkgl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtoidkriqv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gthlmysshw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtfinbehif.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtwgmihyeq.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gteosztoxk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gtscglgisy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtzxxaupnk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtfeafxouc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gthymrmcwk.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtoufpmgfn.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtfeeqjlcq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtmfkikkcu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtykcibfqz.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtotohyxkg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsualptet.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtrxpcmbzw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtcagiuwgo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtceuqhhlt.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtcqxwqspo.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtoyxmfhdm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gtpxaspqrx.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtjhjyowmc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gtyrrtwsvr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtwotlmlbr.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtksnjnlnk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtdlkkjkmh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gtxhxcbtyx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtnyvkqdqd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtlpuhzyuw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtdmdqsmby.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtaczkgann.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtmdimpkls.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtekolfrpt.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtkiixeijp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymvuxfhc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtqcuwzrcj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtffexdkqc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtgrqlbksn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtzlgzbuzi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtdpdewnwj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtlhnsrfhb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtwageyvtu.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gtlhkqboxc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtbmqioaih.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtsmhphozo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtnbfmdgky.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtwbusieuj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtcexvdtmn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtehdyansc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtlmtanjus.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gtyvqbxyty.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtdodomnee.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtlmybfyob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gtdvcbpysl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtghcmqcke.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtoxvzzzqa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtaquarxhd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtfywijuqa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtwphtanrl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtrkimqmip.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtgrthvgba.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtkufqmaxt.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtkrzcrnrw.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtuhlgtday.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtyjgztycx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtplgmuhnk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtfwzrepbl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplooxwsm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtkbfweqpo.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gteeecbzgy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtxnjhcmpc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtwadtrvuy.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtsbyfavpx.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtizikeytk.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdlshiln.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtcxdjstue.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtwujfyoqy.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtesanaokm.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtszzeziwf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtmtfqawvb.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtboxajoki.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtwdlwimht.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gthkzkcsoi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtjrehxyvz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeghonni.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtyrdhephn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtzktsybqc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpalkuuzd.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtwwsvvhta.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvgpvuwp.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtazqavngf.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtefcoylkt.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtvmbbpgnx.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtzejwutfg.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtytttcoud.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtrcisckxw.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gterolrbbi.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtzduwbpwy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtkrvxsxic.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtnxykwlro.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtiayixesb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gttxxeqzha.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtdmeiglow.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyznjvmtk.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtnulormds.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtllxrrtmr.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtifypoogn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gthlilujvr.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtknoiovuc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtemrqfxup.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtkowuvjya.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhqufabj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtdajjciep.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtzwupdhrp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtjypcoksh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gthncedpkn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtdcfovppg.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtdzyhbhiw.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtgexdndbg.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtzpzctdwr.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtnvvajslx.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gthdizocak.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtpbasxznl.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtpzgqguhd.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtrxtmfrpq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtwquqzdau.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtxotgzyno.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtufnymljl.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtvrsdgfde.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtqfsnkhvi.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtqattuxdn.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtwsifyvsn.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtlfyyatde.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtsyrkevzm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtqtddtgka.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtcitxtjvw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtsmerecnn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtfnpoqwaj.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtijhtdbmd.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtxnkxunck.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtlhshtetx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtttpxuuql.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtkosypqik.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtlpfrwtms.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtecabaxwg.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gtluaciopb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gttgsifklb.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtgcqlsdlv.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhdnrric.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtwkxuqfbl.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gtylakyzek.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtqxqmjdse.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtkqrgdpoc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gtbnusgcbu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtzzjndnmr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtwvbxoywm.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrmzevbc.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtilobsitb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gtnjknstvs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtxovxqdfh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofhodtti.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtfeaoobbo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbmuvrec.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtuacdkxle.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpcunqnra.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtcgsdnitl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedqcbead.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtoyxmeokg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtcemollkp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtsonutwsa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtsvunmesh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtqfdyscek.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtljiptuuc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtlkpvslhg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtjrnkjnor.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtlrisarde.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtgvxtgnrl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtndzlsqud.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtrkbkofsc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrnphedm.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gthwouyjzp.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtbianydui.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtonnigdhz.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtkcmhcdkn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtibgbdkky.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtrzmkferb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtezzfqbjv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyorvydh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtxtvxfrtj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtfckedsco.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtnbpghnsp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gtwxamrnqu.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtkllxmchu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtrcfypiqa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gttllmbjev.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gticghwpmh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtwttiyfcw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtehbwscpo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtvktuatkr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtsvtpyiaw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtuqyzuksj.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtprfbthrr.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gtrxbfnrym.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtkdqynebf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtkfgjplzd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtaqibxwaj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtcemaifvp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtjctpnocb.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtmgldsuri.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtulsyphgj.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gtcrznmelt.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gttcwlabin.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtuldzkunk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtvxlmjnkc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtymciveod.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gtfabkujpa.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gtjgsbqzlx.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtbuufmkcg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtmkwgkmgx.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtkqjelgpq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gthxcsskva.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtfoxfxafp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtmmnggsbc.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtighrysrr.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtrccmyimy.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gttzhvqnjq.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtxwcgpbhx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtwiueccic.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtgqtyqpdo.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnnhssofw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtfkwlkdda.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtbqypeker.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtfgpakvcp.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtvpikawgf.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtouuhievb.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtkzpbcvro.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtthsztigu.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gtoyhvwsoy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtjxxqzcmz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsbanbze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffvsqder.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gteicsyfoi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtoeaiuljz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtzxclhkcf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtpjutzybm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtbwrmcpbe.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtcpfojicc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtlbotbrxx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gtitfnpoha.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gteqbyroqh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gthdemlfgf.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtokuzdnns.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtfmjzsbqr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtwbmkrjan.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtwzpfrttn.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtzsmogewh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtscqccfvr.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gttltaabak.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtovirqzly.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtocphecsi.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtgidbrylq.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtxymkjtea.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtcchxtjgx.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtqyuydydb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtdzlliqbd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtvhohjlip.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtuhlxxjlp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gthalgmase.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpwbtsag.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtpdfbgthk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gtavrgpfxn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gteoexgyeg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtjbaqdsve.html


<!-- 参考信息 -->