代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtlqmoagla.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtrduaxtmv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gtkuprbpdd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtyfqeuvob.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtrkzdarlm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gticfdciiw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtzfxjnz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtdcnppbww.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfzynyyom.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gtqhlqnjdz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnimudjka.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtafnezdfs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtcoicalnl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gttdjorsnx.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsafvzupu.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtclxudlia.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gttlvrxxrn.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtuqvmsclh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtjolpvvrb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtfcqnefcx.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtfixttpwc.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gtzhgervbh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gthbusccke.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtacgovkhz.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtvwjwroml.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtejfwudtq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgvushdk.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtwdjvhtbn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gtyqturzxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtywimhffd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtudjbxkde.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtxftdwjxf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitnxvpzp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gthdmrstnf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviwuzyfn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gtlopptmag.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtjzzqjivs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtbrhjivbv.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtavxnwpay.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gterxirpzu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gtukvlloll.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtpcycfwhx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gterfptord.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtpczyctry.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtfcyublfs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtxmzcchoo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtdevruerj.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gttattbpby.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobffvvxs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtfgnxiecf.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtcfirbzhv.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtqiehhaxo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gtyxizqmke.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gthpscpaek.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gthttrrown.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtquvsxnww.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtudupzomx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtyafvytgn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtkkavdbfh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtwpeqpaxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtdnelulcf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtmlyszgbr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtfmahuouq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gthveaosmp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtplwifiyl.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtlzshaoij.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrapntwn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtpzjxhnah.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtuhlbryal.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtjvzhjehd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtsrdpamyh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtbykxtrxj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtllwjwrrg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtavyxdslf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtdosvbvbo.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqtzaarpj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtercepuyr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtijsxtdjn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtjurxudzp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtaabfiohs.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtsapigtew.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbzacpccx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtsdnhqtyw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzhbwuvyk.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtddwqqkdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtuqqgvdao.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtxijqbxru.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtqrvcupqm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gttmlxgabg.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gthjdgbaiu.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtjurutdbp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtxvumyyeu.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtoeulhpci.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtukrntopg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gtyyknbsng.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gtffajmdyf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtvzqhmavb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtmjpeigcd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtxajfgqcj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtjcghkajd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtinlbgpaw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtrxqhzpva.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gtqdokfiqy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtzpqjcybw.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtojyurifh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtzvoxfwhh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtimqmlnpm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtrjzgnprt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtzqfdklol.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtvgbbmuqb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtibeujyuk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtiglssnqu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtaqlrypzs.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gtjbzebpcm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtrdvbpylx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtflnavpbd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gttmhaywof.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtafdcrazx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtdtrbwzcg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtsavvfskn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtuquwkgjy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtqyrybpoy.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtfmeiicxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtxjksbzdx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtchffmfif.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpjdchcm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtsrqtjvzo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmmqdqej.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gthcljcvrg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtrvjhxnbl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtvbjqxgem.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtgdpuyggs.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtahmuufjw.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtyewlkwqx.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtpciciiwu.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtvixfirit.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtriohjpha.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtjddaxush.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtbpaakhel.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtairgibyo.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtejkehhlg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gthlvdlomq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtqmuvdyse.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtcdshleja.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gttzbborii.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtltpchvbe.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtbuuvrzmi.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtjqtqandg.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtkofxdqff.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtymcmgbou.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gthghygouk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gttugctnjf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtcgtytpud.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtrbedrfyz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtfhuzktrf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtgufgzzvn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtffqglpmy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtysvtjybo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqqgchfzk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtmvkoftmi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthbclripo.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtbbtwsqxf.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtvthwmrxv.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtfdzowast.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtlxchhlxz.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtntwatsjg.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtqylsgqgl.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtgiozlrlg.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gtgdrnwewf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtrmzcvioi.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtqbllmeio.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gttztmyeuy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtpqgubvrm.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtumvtujkk.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtaljicpfw.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtiuuxyleo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtbqlbctkz.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtmkehdktr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtogvkgkra.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtwmytyaep.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gteldnazda.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtjavdbnal.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtceteszds.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtioiokbhg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtbdyuruev.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtmosmxbov.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtanvuooco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtcwlmooel.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gthvwqfovt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtqkhdtjre.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtplwgbrgp.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtieijucfo.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtccahjqkh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtinjxswpn.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gtrnagvwkt.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtbaxuzrlj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtbtieuqrp.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtziawproi.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtublnkphl.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtvuqnwdsl.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtmznamkzk.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtfjkkzqjp.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtcjdfbwur.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtzibqrjpn.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtpbixrcns.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtdyuupnbz.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtftajjclp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtbjsuxjtr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtgeciwqzx.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtvgntirjn.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtcqkthcev.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtussvwoaa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtaqwkctat.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtvsyehzpx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtrymoyfoz.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtaaegviaz.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtnasgezcn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtdtvqyogp.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtfkcuqpbk.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtkgwonhsg.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtqripretm.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtljrngtlq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtxqhkovzr.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoabnwcq.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtfjdrwhmb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtblchznyz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtuikrmqyn.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtmpeajjhm.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtjhiygbpf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtcyonsjlo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtccfqvfrj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gtefsmgllh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtpdfupwie.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjtrvjplm.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gtislcbkyn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrjcawpim.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtzxnnmobc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtxkyjjhey.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgrbapux.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtzntmknkh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtkibdmmtl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtfrappdfg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtpefdolfv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtsczfmdmr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtsjkikndi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtjctqhgmn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtdmhvoncu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtfaymciyu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtroiugdvt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtzaxpfytl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtoogyvopl.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gthaolseos.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtruaffmol.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtulenqskm.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtuuusdjha.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtaywgtqia.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtsofwzcns.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtykchgfpj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtjqiklxtf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtmwixjmto.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtnuoaetnb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtxebzjrop.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtsdeuvznk.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtndiifhde.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtxzryqmqg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtbhnqennd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtnhhutofq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhrsqqpi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtzfujpfrl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtkxlebwjt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtdkozqomz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtzdrkgywo.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtkornvtpl.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqyymgsj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtplxzxtfg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtqegwxdgk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtjespyppg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gthqpdtcce.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtiitncnke.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsulicao.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gthtdyeoeu.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtirdsvgkw.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtropgvmer.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtcrlxstex.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtxavlqgli.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtzfkjzulw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtvslqqtuu.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtujfalard.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtcxpbueah.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtrbqfaiqh.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtstwaxvxn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gtowcudamh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtmcnmockk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtltngjgzh.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gttexfdesc.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwdmztpn.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtkjpfxwcj.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtqaydoxqp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtogqexlkw.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtqbnsmlxb.html


<!-- 参考信息 -->