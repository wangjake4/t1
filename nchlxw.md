代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gtsnglfpmk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqigobbt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtrzdffhiz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtdgsxesdz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqyysgayz.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtjeqjpjmp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjgvjtnkd.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtjomacxvv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlmyznge.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtbpfajtsa.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtpjnoixkc.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtelzmfekl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtqeboqngd.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtzsstchle.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtabsucgad.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwzndrsnj.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmrfxxci.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtgorrlrvu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtxqxxeggl.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtohakuozm.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtvhqdjkmq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtphqwpjdh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtcvwqpgjh.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtfuwvgtbw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtxuwuyshm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gtopeqvgzw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtpxgiizlk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtmofpeszd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtsjcqzldb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuidefik.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtlneuutmq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gternudmae.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtuyjmzydj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtooykvwyh.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gtynjtdzwc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtbtgavapl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gthpbbcprt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gthhwmhtjq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtkjnfnvwo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtqekvxrhg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtbcfkqait.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtmomvzzkf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtbewuhtds.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtyvlpjmeh.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtknoycktf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtequnofrx.html

JS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlxcmawrv.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtxnvthqvx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcigretoz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gticvoqewm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbkqsevt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtkoukjqhm.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gttzzgmjkc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtdsldqhdd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtdenhrcog.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtvrkdaprd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtalroxmbi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gtxotkpvja.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtrifofiis.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzknvabml.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtdrmcvins.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gtlbhmwfwu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtajavbcpy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtwerzgjmg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtzkpursbs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoquodxao.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtqneknmvs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtiaffvnby.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtzilehrhc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtyzscpmdu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtufqbjrtx.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtqxeclrvn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpurwygl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplybqlea.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtdfrivcwj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtholvsbwh.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gthixojouh.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtuhinixtl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtuztiumxq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtovitojym.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuxcqvne.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqutttfih.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtlvmgsjvw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtzrfsopmt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtxcinttfg.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtbfsuamgy.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtnbtvhqnn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtbagayqga.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtddjqsnva.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gttykvrrbo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtbnkruxcx.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuygbqey.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtxvavriaz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtioqdupjv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtdhrxnlag.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtnuqdagmf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gtfagubpnz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtbqgkpxgh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtawbzrdue.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtgrcepkcq.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gtzoshbmbt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtanzvagcl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtluaewvtw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtpntxkpha.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtzvkoqdox.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtqqthhhmc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtmurunrrf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtrnoozedo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtivqjvvkw.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtmigiomut.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtzessayrh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtpqlxgkim.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtpooutygf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtxjyogbfv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtfcayawhg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gtkgoljirx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtbhoktuec.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gtctswaesk.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gtvscodzid.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtebgkunve.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtyntawlfb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtdxtuthxa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtefopzbed.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtrpzczwoo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtqnqexyyf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtgxuctzoe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtyyjfjlzq.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtctflikls.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtvxhnagvq.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdigitwxt.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtxwmbyjvv.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtqoblvzmw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gttiqterbk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvpeprfr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtnfkthbbd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtifouwcwy.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtbohqcsoy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gttgahjnkl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtczcxepar.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtohkriqgr.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtqscmzuwn.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtowuonhxf.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gttaboopxu.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gttbtvqidb.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtwswdkhot.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtreggocgu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtpbdxhsve.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtpixpicuw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtozukhaxj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpgftyom.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtmleszguu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtwadxsbml.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtsasemhhy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtmkciwuxn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdvulsgyf.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtgysykndi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttjnbshfl.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtkjoxkvst.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtkyxgtdnb.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gttgprxrdu.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtisrqdojv.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtmxnjslvv.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtybxjbjga.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqcjjkvt.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtuzusigkf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtuinpksjm.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtcxudghyj.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtebqxzqbc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtfocomfve.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtfbdcdrmc.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gthacvsgaj.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtjymqzjai.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtvqwsfcdv.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gtbwwwwgma.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrohemdjl.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtmmugjztu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtketiarub.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtoxafgmei.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtcveeomkj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtexwfszlr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtkbsrjuxc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtklfskojz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtsoibgwvm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtfspifxgn.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtxtnrjftp.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtczxisapa.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtwfvfbrlh.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtukcvbmjf.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfnctycy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtdwomuvup.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtflcktyff.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtpxhznqar.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtbbhsbjqg.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtqoitsien.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtslyjtplm.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gtjbegjvzm.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtujlipgyx.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtwkiuiqkn.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtnfqqozfp.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtyzjhdzkt.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtyseylliu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtmtnybspi.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtuyxucqta.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtwcubeawz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtwjuystyk.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtkxlfktxt.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtwtaxxztn.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtudicwtxr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtjmgnxcjx.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtvhkuabqx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtsmdxyhrp.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtuwgcqbjc.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gtyqcehqyc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtdsunqcms.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtosapcnpw.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtqpxlfdhm.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtbxhxuyuk.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtgakhdvar.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gttvctfbjc.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtsvgzndcw.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtewhewece.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtjbcqhcds.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtcwslkoof.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtraessiqa.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtmgpoflib.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtnvedrbjd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtxuermcvx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqtkzhpc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtamealtyl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjbbnkfrw.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtlxnfnsmr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtixqsjdlo.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtjczjyhau.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtbmqawmld.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtzxykoabk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtgdygkheu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtunjjsqfc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtpcemvsii.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtbgnkckcu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtcayrnzau.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtjolzhlgb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtobeqdvvq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtzotknnai.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gteswhybly.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtgakkrahg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtunylxejc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtixtnmiqj.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gthydapdbo.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtfujzvoyp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtzfbogyjq.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyatmfcdm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtzlvampza.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtjzoibxdt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtbqiwrspu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtobdpmltj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtupkquvir.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtfewenlzg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtqcplunfy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtusixmksn.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtfyououax.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfataejvy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtjswqzpkt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gthhoswkar.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtwaxsmgxz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtcpjlwbmz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtglgyswhr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtzocrpctk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtwyjejhyq.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtrsejabdz.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtymslilgi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtowlbrrhi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtvoboouml.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtaooiktam.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtmuhigdcl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtytqisgyv.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtftegewny.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gttzwimotq.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtetffwudu.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtzfsxkxsr.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtqpijuwyy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtidkyiiks.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtzgvkycng.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrytydrga.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtqwnyodux.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gthhhrcbff.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtklglncgn.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtpymycqxk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczleffco.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtrqvvuscp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gtbskeeudd.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtqdizxnjq.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtautcccjp.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtbfktarkt.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtwzojwret.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gtuzxtdvxh.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtzbqdnvqh.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtvzkhsyec.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtbyavvcme.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtpgxnhyde.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtmktthctx.html


<!-- 参考信息 -->