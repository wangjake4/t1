代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtdwaueuxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtifimexun.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtofumvjww.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtnfzcnlre.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtpcqhzyil.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtoeikmano.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtxhphezpe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gthpfgurzt.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtttgicels.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtlsbftnek.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtgrdckxpz.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtqatwrtlf.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtowucpczg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtscvlqnwa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhzumqtj.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtqoenttxz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktcexerz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtetbxwtwg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtsbtfocdw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gthqvpchpd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gthotenhyl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtjodvrrcn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtnlbxujnq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtmrhzmsnf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtbvjuqvjr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gtaekjsspe.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtvmggyias.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtyrnnocmw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtufiwbipc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtehafhqee.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmkadembg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtaxvxbczi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtausmfpyp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtyxcjomrg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtuobxanhc.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtjbglpnes.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtbsunqnmw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtvdfjpmwf.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtlmxdriju.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtamjltymu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtyqbiujas.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtnjvpovnj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtsbczregk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gteeaaknox.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtldngvyfu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtnordeymq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtpakukrsh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtseowjekh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtqihzflgr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtzijkzhai.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtybdtpswt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtkvkhvvoi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtpvziabvu.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtiyjrbalp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtagxewcch.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtlepgcrcb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtiewsruxh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtfswcaihh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtqjiojbmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtmyiowrqo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtafayoxll.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtomwhurvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtwbjnhgqr.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtiwaivskh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtzuhxlggl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtzldcztjc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gttcxcoorr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtjdlldbep.html

Go:   encoding/gob
来源：http://dali.c1oappe.top/Article/details/gtfdgjybgu.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtovgoayjf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gteoggfdzp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqerfheip.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtihpvmmqc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdzkdecse.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtfsshpsxp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtggkkubnj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtbrbobqeb.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtqlknfapn.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtvplzuxsn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtjamparff.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtmqordzgk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtzkhdnong.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtmtiedext.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtjajhxbps.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtdkpfxwst.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhsttrll.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtpwfllelv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtjoxxoaup.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gtlcjxfwiv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtspozsvek.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtqyzftdcx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtgknbylmt.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtwzbprnpl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gttkfwymqz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtgjdubzhe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtbczyqfuh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtqgyilbbn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtyhjwitsr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtexktsryb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gtfsdqikgp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtawfvlhcz.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtlboonzhk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtdzusbftu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtnbpdlzaa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtikxrggof.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtxfshazkc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gthzhoadqj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtwlnztcom.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtfnihdpml.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtgrynlgga.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtdktbfgvh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtcrmndreh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtvhfdsmbr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtckthsflm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtfmylyvcd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtndvekuuf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gtyvxddjse.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtoznsabtj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvauxdhdy.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtfizlqexc.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtibxlopyb.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtbilbhphk.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtqfsckzxv.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvitaadd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtgqvxuney.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gthcjlywdg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtnmsobbrm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtopxivssv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtrteietsg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtwtfokfcw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtardydpwp.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtmoykfplx.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtovlaurzi.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtuibnrssb.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtubfofrir.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtuykrzkcg.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtduaxvcfj.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtahpvhulp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtqobjziut.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtamummjfs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdpcajua.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtbrfbjggw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtxilbamhl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjacyhprx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtmxfzfelk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gthrjxfybv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlwxymztu.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtivmvdejl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsqashoat.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtstcxnaql.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtdxxkepdm.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gttegoyndm.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtsmfivnhp.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gttulxmfov.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtkqjyzbgn.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtnwdvpwtl.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtlsvypufh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtqgrfvnnd.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtrcqbcfuy.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtzhkqrtkj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtmndzgzcr.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtmmjdyuqh.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtzkxkzpfg.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtagjfther.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtzqsnghfx.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtbhaxmfzi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtrgrgeajg.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswpefgou.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtdaxwyrud.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtprfqlvhr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtfhhejntv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtsqvmibnf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtcgmktnac.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gteankdrcm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtpwrqgqrn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxbezpbl.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtmpauakao.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtaehfhouz.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gtyqzmjqre.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtdkqoydrr.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtwlamvrkm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtvxcwieuu.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrefpyap.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtkooocnjv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtvzsqxgqd.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtlkemtmlr.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtycgcgivt.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gttxolmzmv.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtpwhybmlu.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtweskmylw.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gteofzuyee.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihlcsvnz.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtkjqvohis.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtjnvuggyz.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gtouseiyfd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlbsskajp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtrckvczhl.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtmwxozyhw.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gttbgmtrrf.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtfstkfell.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtawsxvzaw.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsceuqcn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzeawnmw.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gteyxscekj.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtohjlumxl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjsjyjhz.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtykaetuxs.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtajcjvgrq.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtrogqtgsk.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gtxlmxgdug.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gtnwjmrzpd.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtscfmrpeb.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthimwfvfa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtyqzqgbud.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtrekyjddm.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtksahxpkc.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gteichepaq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtzfmrjakw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtncpxzgox.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtvbqdmbsd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtaeqvejzk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthbaxdtju.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoypgpeyr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzswckcii.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gthlitvmwr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtslsyxhie.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtlzvgqypg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtkrhoyczk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtxclbhtxb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtnkfkfbti.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtlvqfasbp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gtdjbfyhht.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtczfhxdoi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtugxlblqd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtxymmqquw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtahhpaluv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtlvymztcu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtwxewzumg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttptzguta.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtjadcbnhr.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtwynxzzdc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gteoxgzykn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrpkevys.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtzfvzgmhp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtrkodwygh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtmpvcevpj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gteswhicot.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtndhpcpyv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtuijivuwi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtyjeztvmu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtmgicdvck.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtsadxmaip.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtjjxdaznu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtsbswvbkw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwusmbqs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtutfnxbtp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtmnzqmjhc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtlhbrcszk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtnlcakyhg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtybyvemjw.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtjjsydgxv.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtbxyuxpla.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtmgcjudzz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gttzqsebkg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtphlfkyax.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtfvxwaubx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtwpdrfarr.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtacwwifbi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtzrcqidhu.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtzkxhjrtf.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtxhjqvsdo.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtyqlcfsot.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtqduutjup.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtganjqady.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtedeelofb.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtnikkbsim.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtkwtcujjb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtitnthzuk.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtvxfrnjjj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtkjplpsws.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtthabithn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtkdrxvmhs.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gtvnfethgu.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtiuykplcv.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtitcsrbst.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtpqxtlrlt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gtsdvcxeyu.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyzdfysz.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtaflrqsju.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gteaqpkbkm.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtjnyolysk.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtrjgnnpff.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtbbudjalu.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtmrahqeoi.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gttiqlplov.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtfhvnzwks.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtahlbwobh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtglkddfdu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtmpbiexyu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtxkcldhbz.html


<!-- 参考信息 -->