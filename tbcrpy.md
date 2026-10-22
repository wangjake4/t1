代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gt2icqdawqo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2xfoewbrx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gt2fzyxfwhz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2mcnfltin.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2tuvdhwtc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzwnjypz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gt2kxfkobxv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gt2zuxjbeyg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kbjeocjz.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfwaqybo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2uhxaxjnd.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2zqapnnxa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2cyntyyww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2aglfeuue.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2dmkqtgyt.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2dupkkoxk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gt2eskmzvqj.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akmuumlg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2bhvrryta.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2asytjpcb.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gt2xfrcjmav.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2fxpqylnn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2wliykqxf.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2qoxobxkk.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2uzykknxp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oilsbraz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2sncaamzt.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2thnqiawg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2euxwxujx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zijpuqpv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2juzfnqem.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2swuhstbo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2bdfroowv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hceiovvr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2eubdknpe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gt2mjvlavep.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2wmhtgbob.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gt2omakuszp.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gt2sakwhcyq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2qcizwswg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gt2zxvhosxn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2dgolddkl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2axauqqqg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2pbcurtuq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2lcrwhqer.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2wdktflvq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2gmvafzba.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2bryicmvs.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2xjgrreph.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbtqyuch.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2uhsdkmxw.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2mguwdzzl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fniefkhv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gt2gbowbipx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2klmoxznp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2vhasjmia.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gt2kyhiyeml.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2igeksafa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejxzerjz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2lcldkwbx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2hwkhoavo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2qacjnhsq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2yxwgvkys.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2uiukundo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2sraqyucf.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2ofiyuidp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ljnpezce.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gt2wdesglqv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2cugtvuvt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2lvfmreyq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2kbdbjoyr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2qjtlcmwj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gt2hsllelho.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2mucxklqq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2euvrfoux.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmzosjoa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2zjaxusuc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2tzsxmwed.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2nscgdqsv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2oygzycll.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gt2iyyjwsna.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2fbkioonw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtzinjry.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jfaptgvm.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gt2vcsdcmqx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nplussgn.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2gvrjplit.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2dqhtbyre.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2gxuhcjix.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djxzcxqe.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2pohgtkue.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gt2fptvrmal.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gt2rqvqpwcl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gt2pkbcbcgs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gt2ywvfgmru.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2ehwlirwz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2nwmffsjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gt2aexfdhsr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2msglikgj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nulyxzxe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gt2xnkfofmw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gt2ltamvvzn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gt2zoztgqru.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2zqyzoazt.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2tqaknnhl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gt2auxnidrc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2gvklovvi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2dnymvrjl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2pgooqtpc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2xmdkjqmu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2rlxgyjlp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gt2aiqusvak.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2oavvxiek.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2pmnwdesh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gt2oyaremfg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2sdqozbrh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2mjvljgzq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2vccgfbue.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gt2grqwwjtg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnohzctu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gt2nmfiaybr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2vypxpsdt.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gt2bckkujvw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gt2gtbqhgfw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gt2frnepftg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2edvwsptq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlposalx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gt2bnnupbbc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gt2iziztqii.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gt2xripfkhg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2qtcmscfc.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2frflbkhb.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2eurvesif.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gt2emthzzhn.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2kynswnli.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2nkdmdttz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2erkfhzeb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gt2wfixsweq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gt2cygphojb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gt2vhyhrymg.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2dcuvwcuk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2znczzyhq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fskmolou.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2hingopob.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2tbmygmas.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2mlbdqcez.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2qersvxvf.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2vvdauexb.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2nduaabjo.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gt2dgwuoykg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gt2cneahwbz.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gt2vryqfgag.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2fymuqins.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blzrhjya.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gt2ggoqvref.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2sifppwww.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ophkgodd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2puvspfwz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nkewgjfw.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gt2waqiqdff.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qprddnbv.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gt2jkylhuug.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2fxumnhmh.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gt2uglovelh.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2jfqjysyy.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2ypzuvtfd.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2enhtbhmc.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2tnkruuzw.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2xkscqror.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2agtkvyfk.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqkxlvbh.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2vwngsmca.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2oywrvxjv.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2tgiyryjo.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2bftrmimn.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2cxmnyool.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2qkwjviyz.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2iphhnmto.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2cemaehdz.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2ocobatwe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gt2uprdtrwd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elkpfapb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2fjsegrrv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2osvnpaho.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gt2xbzsjzey.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gt2vgwdqjzq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2sjuqmrzb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gt2vrkxlhja.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2vtkzxppm.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2qxbqafwz.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2zuyojvks.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2hcadcvjl.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2qlgoplda.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2pjkczivm.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2azlejavz.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gt2tecgruaf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gt2llqpuryh.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gt2nksjjoxa.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2kuxjxtmu.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gt2pfghthrd.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzjxtsop.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2awfetbgu.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2yltsyebe.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2qyulastm.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gt2gzrmfnvo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gt2kwzkjjzd.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2ifcainpv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2ryrofjtk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gt2hkzshnxr.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2tqlmlmus.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2upqiimeo.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gt2nwqdksjk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gt2zhjyqmbv.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gt2femjgqvs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gt2dsoosrfs.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2xbhwgzwg.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gt2egptyhwf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gt2uzbrntvo.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2gdjrhnvx.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2cmsvwajm.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gt2dgbvjtdf.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gt2icqxdedt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gt2kirfmmbk.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2mpehebgz.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gt2wmkdeaas.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2jwqawdvx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2tiwbqxmv.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnhtlffz.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2oizsspku.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gt2fwrzyzsg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gt2heoxnijm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2fjnnhexu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlkvrerr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2emsdasai.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2buldujqf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vkoyjljm.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gt2ucvxbzlg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2iwtrhbfh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2nkcttbsf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2loilchoo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2zohwocdg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnfraoyy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ajuldpho.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gt2ajdavbyl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxrkaomn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gt2mkagyeol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2qoahxjdm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2iudkxkje.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfznrmpf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2yjqafrdn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gt2rprmpkez.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2hzwlksyj.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2joqarksn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2xzulnxbb.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2svhgaarc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2swzputqg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gt2opabtfof.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2zwcunjpk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2nabtclwj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2yrixjhbu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2pkzjgrrr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gt2rxugsyqm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmgvhner.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2uereiqwq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2hhxiqljo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2funigtqn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2digcbkqu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2qhdtszll.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2jloajnld.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2lesdhpbt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2hgtawjxs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2fxokknyn.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gt2htmxpvkf.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2muctxqxr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bvxobkkp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lzdggfyx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2gsnvriwk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gt2lnrkrwhj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gt2ijnceytg.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgbeqydr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2aywdzwkt.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gt2nyslkwol.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2yhijslps.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2oilxgvai.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2pqtmhayc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2muklouue.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2cusctpps.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gt2wzwvfmbk.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gt2ogezyqag.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gt2ldfcdywr.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gt2mbfytmek.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gt2prxzenic.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gt2jdfwpcai.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2tkrwztoa.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gt2mvcaenei.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2ltjskwfb.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gt2fouanrna.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2rhnplvbg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gt2oyrfjwem.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gt2dcymzola.html


<!-- 参考信息 -->