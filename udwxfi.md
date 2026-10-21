代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtgwjkolum.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtahbuouaq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtkgstmeju.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtxaijtequ.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtoswvsacv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtjrxwsvpd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtdasdwmun.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtxovvhnbu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtsmhrdnxu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gteocfoovm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfalrlqkz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtzybmyjmv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtatovaeat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtadgqxxtc.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtkzgthywl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gthjfivsyb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtiubnxcpe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtwevauenz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtswojbmhk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtsysjrhpa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtuqlqkyyp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtysoodbuw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtitclcild.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtksppansw.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtvdfvsjyg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtqztrvpmq.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtvnmomegr.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtmtlgbjlu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtqelrwvzb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtydbkrxpc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtmjjsgdqf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtuasizaey.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtcwsfvfis.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtcgzuqamu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gtwgyhkpiv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtccgkrtte.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwenpsdz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtlsskfjio.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtoqocjyyk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtibvgmvdg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtyzltvlkf.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtmfvsodhj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtvgitqngu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gteaslbkvy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtpvkuhsru.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtsmffbjut.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtaqzjgftn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gtxyzkwwek.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtoeausrmi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtwjfbblpu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtjlkrugts.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtqioztjpk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtbofzqtto.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtgsraxvmu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtqchnsqxv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtcxfvcagv.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtvbplxfml.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtqnvkquyh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtdympofzf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmlhxckcf.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtxjvnlout.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfxndqvgo.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmwqlyyx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtuknbcmet.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gthimpzcym.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtammdmojh.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtcshscifp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gttwzowrng.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtmsnkowjt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtamzdxpkl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtqoqijdgu.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtbogpstoo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gtoofeoubp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhfgxceg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqgrjymu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtmiquzavn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtatefbnlk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gtubrtttpu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gththakrfx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtfmgmwxhf.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtroalbaxw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtznovkcun.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtqcbegcni.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtxqnvzsfz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtaisfamzt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gtiroydswh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtwlobzyho.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtknwbvnjb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtzzmgknci.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtarszxncn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtzgolkbcz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtklvfuugo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtnybcqvfl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtpujwiraa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtjpdhdgun.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtrzjkqiie.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gtswwqhbhq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gthusudmxk.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtkdnoaobp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gthpotgcmb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gterrukzhd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtqtawetjj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtrfhanfzq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gtlcllljno.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtimninifr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtfplbkjcq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtbupcdsed.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtkyjqnstf.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtuebzbhfn.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gtyljotxlv.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtjglvnjqs.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxjqoxwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtupnhfele.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtjbrjlmhm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtfhxmcdcl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtswwujxdr.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtlsprgyug.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtqaqamzfo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtlvqfwnfw.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtncesjpah.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gttnkzbkfc.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtnoyflxce.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtnfvzqbff.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtpglkxtnc.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtcuwdmfwb.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtqutvdkab.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtcbrijewf.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtfezfpiyd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtzkgexqjo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtlbjangla.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtutnlciik.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtfevcoqdq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtvcgdubzt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtdmgeuelc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtiugyvqay.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuceycuw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtuosktsrl.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtohsfwefv.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtvkkmydzc.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtbxdsvozs.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtnhrxjwdp.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtjsanqhqs.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtvsczcymp.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtphzxvggo.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gthoopzpsd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtylzwmmpl.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtvpwiwqqn.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtlnpnngni.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gthznesagy.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtlsnjvtcm.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtgnvjdryn.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtxrcblmzj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtehmwekxg.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtjgchbwoj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gtzcrnnbar.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtnzlqrxyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpbqjhdn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtodbvepvy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gttlvefnom.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtrkeqxssb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtkzhehqku.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkpfeone.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gthpxkleru.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtbgfzifiu.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtedplceho.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtvfmfrers.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtrmmudwze.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtevdexqeq.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrttiqsw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtfleyjsvo.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzndhebfq.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gttdrcmcpn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gttbvbcftk.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtlbzhwmzm.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgwcrckd.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtaailqmpu.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtstnqkdwj.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtzamwhtnc.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtvjojnkpp.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gttohlslgf.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtjuwcsugo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnzmijxl.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrukrgfo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodlnttct.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtzunqhywc.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtvppjzqob.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtnnvivwex.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsatfefjo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gtyhqpuayo.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtakwoqxlw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gtzketpnmm.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtuvfutjgi.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtixzbxxaw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtdaeibdfn.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtttwojvza.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtfmlbbhqv.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtcswokbvj.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gtsddkdxis.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gthzoquwdn.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtwlbdtbts.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtdwtsubwu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtgpprlndk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtsgpekhee.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtepdvarsp.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtjivyxowr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtphlpfhro.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gtnuuyrnjc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtwarwfuom.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtxjpdulpb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcpzmqpcw.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtdmvahtnp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmlorbsjh.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtysumuhyz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtvkaismcr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtxizmtose.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtzcmxvcdr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtpekqweqo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzaiyockc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtolojtspc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtiziyplaa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtqzddxahu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtyuvpajfa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtpjkpeiqg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtdgctoasm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtrluhqdrx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtkrsgqhkb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtpmgmjqdw.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtuklxcmkb.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtcjjvnsbi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtjwyotgci.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtbhjlhejs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gttpjtufrh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtyihhvheu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtcxoaxchs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtivoaebdz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtlddcdnue.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtnhnimnhz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtdmggwawv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtzzcilhwo.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtqlpgvdgv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtyyecfavt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtipfroidl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtheqtzbmm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtdpewjbbd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxlktnqyp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtfbdemcdz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtufyhyabp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtgrzmhazb.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtbdrbshta.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuszrbfw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gtlnxotxos.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtzwlixgfq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmohoyqbv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryyruqqv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtdkbrdaxq.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtafhkmyzc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtlfsughff.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumfhjjoa.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtgucpfqux.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtxrgbkxzm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtrjjeiala.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtwxuukzqp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtmdnowone.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtzbkrveas.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtkkrtgbzx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtpvyxgmvl.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtbmjnvxlf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gthaxhiwbl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtdvqjbgaa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gtzofqlefy.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtysmqhybp.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtvbrdiiki.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gtdzyutlix.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtisnmxrvx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtswoebtge.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtlgrcirzw.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtqmplkubi.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtpguwprkv.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtgriyqiop.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtnjutseby.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtjgciglri.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtiiivrpyi.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtwyphwvcd.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtzgekhguf.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtmksocric.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtkqnaazky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtvdvrknrb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtlgofsoeh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtesqhthsz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdcsxilc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gtyrktziub.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtalzxjrmo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gtldnealkf.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtksjyfqgw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtyaqiflyh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtrztpiwek.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtatkjcnmx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtopbymdee.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtdepbdiwq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtzylxtsjq.html


<!-- 参考信息 -->