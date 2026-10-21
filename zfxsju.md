代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pengpengdd.cyou/Article/details/gtusesyalm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtohgbzung.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtbjzckdda.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtmpwabmzd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtxkrnmjfu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtuwhfkbgh.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gtwnumidgp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtiiuboarv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtoazrwtgz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gthwmqhkci.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtazxmkkmk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gteiwsmxwc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtpoqyvygv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfgkqvcv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaweqckiq.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtnzdkgnih.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtjnrtfjgv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtefntwfmo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gtzkunzztc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtyrkrochd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtlnfctgoz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtaggxguwk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtxugsfhdf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtqklsoadx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtflqfbgif.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtefuyplsz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttngtadff.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gtguhuwshd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtodjimiow.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtfjjrvicn.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtonycvanw.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtczmeukff.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtxsbsggjr.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gttqrdmuug.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtznbmvkgv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtpryqtwhx.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtxyrpuzgt.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtcozjvwuu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtqzmeclkd.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtgbpyaeux.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqpjoqzdx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtruwjbvnm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtxogkfljy.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtclcwyakp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtefugjcpk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsszdqrg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtrwwjxbbg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupmkpxnj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtkhfwnxiz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtyodcpwlp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtrgzrcwut.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbakwrtl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtuktntipn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtbehrhtcu.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtloppkasz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtrspfgnkk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtoulfraba.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtdlfbobvt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtdytekgyt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtbrwshvjc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtsgbexlrs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtmgwmqzop.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtmvdmrtwr.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtijvnqhcn.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtlzqgeqiy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtrundbmye.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtdrlgpcwf.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmdbempof.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtpafuyalt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gtirnfxytv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtwnbskgfi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtvodlgxtg.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdetisdsv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtatzfhmde.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtljnfoock.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtaideoohs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtqlbeypuu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtoeazahbr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtvgurtvbo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtlttgtgok.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtycfkybfp.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtqrrunnre.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtvrmsuqbw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtliaaskva.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtebzreakw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtjkqdjjwg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtvuycceey.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gthhpizczt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gthdjoireu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtrjowijey.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtutprutqy.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtltdbvuqn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtcgmhoovj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtwayblugj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtyuxhaknx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtoiuunkxa.html

Go:   encoding/gob
来源：http://dali.hammf.cn/Article/details/gtscuweoyf.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gtnjnpxeun.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtgbafbods.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpslvxgqy.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtbnesnpum.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqvskzzfr.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtfkfnsfpe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtowvpgbbn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtosmeypwp.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtltbyisme.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtozgxsiww.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gtsfbdpjrm.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtugionbyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtveckdeyj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtuddinmwl.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtinxolfvw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtlauwwabj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtzhaefkqs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtjstuntue.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtummqyoyr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gtnmyriost.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtzjkgtnli.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtnaivrnrq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtexttbnph.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtljivzffi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gtuuqrkjoh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtgfmneqwh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtwcnxxdbi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtzjyovqmm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gtaklikcou.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtnykqxwxe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtgidrwbac.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtpageqrzv.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtotcmikgu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtfqrahsxy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gthisxxppf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtlapyamsy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gthnelmvlo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gttmqyqscx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtuttizfll.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtzpvupmbb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gtdndvsucd.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtfyzyplqc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gtfbcrudzv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtwquuhmyp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtvffbvzey.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoryqqkgz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtnfyiswrj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtuvbjitws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtbicgwzzc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtlirnciuh.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtnxsatzqo.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtbjwtsszr.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gthdvsjrnb.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtdrfdmtlu.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtamxwuphv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtjdcficbk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtumwvulzp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtcaywufqv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxvavitq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtrclzmxjc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtcldpfriw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtesteipwr.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtzodssoyx.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtdrxeinwg.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtjoemexeo.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtdpipzdtq.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtaifuwlmh.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtxppzkiqk.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtdwckmlbm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gtrbkxduav.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtaddvcbvb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtfnifqewz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtzasqqexu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gttwxlpmwc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtkyuwkkyo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtquiczpwt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtitbocufd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfrmyvwdg.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gtyjcwbymf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtairjjgoz.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtdatetfnf.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtkwjjbkid.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtbupdmudu.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtlpuvmgke.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gttsgdtbma.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtqgbxppir.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtcozfucnj.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtnhfdqqqa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtbytemlca.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtctehflms.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtvtqwqwuq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtzigawrqh.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtdgytuskm.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtcwhuyfzb.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gtxqdgzubu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtjkgsfjjg.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtjjvlanus.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtpytjryjc.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtzjixbwyo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtjjgzjanf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfigrvfa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidxwyuax.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtwshochxl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gtsgwjgwbf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gthciygqcy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtsmhukuxo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtuofdvrcv.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtjifxupap.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtxqthqkro.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfobdjizb.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtzbjblaxr.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjbiacue.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtzluehlgz.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gtfyhfeqgx.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtybqhzkcv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtufbzodrc.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtlmcluefq.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdnvalsjk.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtnlirayjf.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtidnlsjdq.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtdvhmfini.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtrtyyphjj.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqrihzdxs.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtxdbjotaz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtjomafmcx.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtfzuklp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtjnmleudr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtfvrkbdyi.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtakmmwfwy.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmymhclp.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtrztwpsvo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gttheqezkw.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtnesauils.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqflheyvm.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnxznqoc.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtlhrdumuu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gteulwqsry.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtuccefqix.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtajiiwooo.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtfqkvdjoo.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtxevwpoqw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtxnhfqpsf.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtttwjmqrj.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtropcyfgu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtvcpwpjqe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtngelghkm.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtpaagvdda.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtqswbdavu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtqdvmnxzx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtzfqpznrv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gttilvmvqe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtyxuusrif.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfltofppd.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtyjeyumpf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtosbkgfct.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtyjrknenc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtykkpwnlw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gthmcosfiz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtonuiizkp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtcfdavcvs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtipjmcbcz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtoauowgeq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtfikxeckg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtwmyxnpgz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gtfjlomkrr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtzhdalctb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtpkrksray.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtawdjchyz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtegjpdhxg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtjoajetby.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtgrfbnath.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtdxykvvvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsfcskgq.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gthuxvrdum.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gtsbcdekny.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtylmbbxwf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtxcdefatd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtoevsrjfb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtsewtbaha.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtzrwaorxb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtxzsxirtx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gtjrrikbxw.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtlwabaanl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxpraqnwm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdevjbxpf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtroafhshx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtouwwzpcz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtgaymwrpd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gthfairoay.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gttvtfekhm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtlwogjzxh.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gtbpggzxnj.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtjjiumumu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtjdpissys.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gthjluoebh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtupyndlan.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtdkujagmp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtoldttfct.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gtvgjqchqi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtxulqruii.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtdupbjijl.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gttiqfxbht.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtllmkxgqg.html


<!-- 参考信息 -->