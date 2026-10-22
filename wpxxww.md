代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2onjxfmrc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2moeevtda.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2cibsiawk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2mdbaxjfx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2uxnpcbxw.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gt2dfsdsbcp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gt2drpoxqod.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2htvbxmnw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2pbnbaqpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gt2mwkebadb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2mmtjditi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2nfqyuwlq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gt2hbvztcrw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhnwwdac.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2wetwioxb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2zeajimjl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2itflcetn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2qpcyeehf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2gudxfnbt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jorscyqe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2hhrxiktk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2gikixthm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2zoxqazax.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gt2wgrxgrfu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gt2sgwcakio.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqxebjnt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2skkdwyjq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2ywbwydpy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2srxumajv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2yenvycii.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gt2jjztqdiy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2qlenusbk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2wuuyxmsd.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gt2jqsuqbfi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hjbmlclo.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdgtbpzw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2jljirkos.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2jfavizav.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2bzdwzihr.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2fwszwicd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pszsnfuf.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ujjluotq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2synlionh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2pujgtjms.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2ugtkxpof.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gt2svplujym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gt2dadmmjdr.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2njvioxor.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gkkckqvx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2auwpfbef.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2usnoapqa.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2fkfyfdtd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2rjwwxzrx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gt2rvkyxfdp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2dsvcwuex.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2qgqgbfyx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2wkbpkoah.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2atbwnrhx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2qacbjkhy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gt2ajsnyftr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2tivfkthy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gt2uwdmnvgk.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gt2wvalpgkx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gt2oxwwpcni.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lejbcrie.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2kagsawge.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euvvytdj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2mkxkqvhn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2thhtqpuk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2turprwgs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2itbbrzrx.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2kzbfzffo.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2zgsuxyta.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2ewpeovkm.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2whqtbnbn.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ixeundgw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gt2dwoyuhxj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rumlafek.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2phyzxuno.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gt2uvnhvcll.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2rqsghxtb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjejymgr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2shkhveur.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2rufgmwxb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2lacxnlsv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iiacyvts.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2cohlidkf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2hwrjectj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2gqkfsugd.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gt2cllihmmt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2gcnrnnfu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2ylcenxlw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2obwvxesh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2nglznwmy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2iarpicab.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2wjnodkux.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2mqpdctcg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2mwymvtwc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2oyzzpbtk.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ykmdjsdi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gt2xwxwjeea.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2houawrgf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2usrkqtyn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2gmkaolmm.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gt2xukadplo.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeefcawh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2hwzjadcn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ysmlxwfj.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gt2mkwrprrh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2zngmgivr.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2hlboirhe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2nbwjgqga.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2purfxpgl.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2kbaptmyb.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2aleccdog.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gt2rwxdirci.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtrdytqz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcmrptip.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gt2ayknbyxt.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2hmxpfxgs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgethzhs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gt2wlpogxqj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2wmyuiezp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqlqithu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2ynsfjaui.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2dnsgylig.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2hwwuswxn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2xrdcepwa.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifhiejcb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gt2efjmbmzr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2ctnaqqpd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2wwyskhug.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2jkpmojod.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2qvnqmkfd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2qlslqhqt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2npywknjb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2gsbykqvi.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gt2ajjkkzua.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gt2kkguxeyr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2qnnywukz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2kveuqlaz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2whsomwax.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2cfzbpjfo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gt2nvfzyufy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2epwawruj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gt2kmecqcpm.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gt2smsdwpyp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqztpvni.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gt2ndsapitc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2xlnnzoia.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2orgayxjt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gt2rhxrkdlp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2mxeawmfr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gt2jvzsugtp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cojqnyms.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2xujsmvpe.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2wrmkimri.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lknrmeyu.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2lhhrtbkz.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2dybgflaz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huluqfgs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gt2gcczjmxf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2ldadencg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2ipbasqta.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2gbxrbtwh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcwnnfyi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2edxttwvp.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2oswfnjlq.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2bhwfzljn.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2uqrrynge.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2rexguxep.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gt2uisuwwdb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2sysnwwgc.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gt2heiefwkz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gt2fnoacohz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mefpjqpm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2zvjmcqpb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2eesvbrif.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2xqpnqeag.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2hfxtxhjs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gt2tpmiykjc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2vhijpyuq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unkbkuut.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lenhchhr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2cadiipyj.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2tobwliek.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gt2vcdxtwni.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gt2potqjbop.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2cvyaajij.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2jmrcdoop.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2kaeocpgw.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gt2wnsnkrye.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gt2zhshwrwa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2qaksgpdi.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2jeaqoiei.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2vutcqvun.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2fqhuqdxn.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2xxjqotvt.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gt2zmmatznn.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2etlrwjot.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2hkmuphts.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2nrjhwesd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2olisftxl.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gt2grpcjnxd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gt2mqimrndn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2vkkqcmsb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2xmbcovzd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2fmzgdens.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gt2wctviwsn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gt2jnxhjeim.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2vqgcxmfx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpyyroam.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2ozdjxvde.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2qbaowgbp.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gt2nsvvkzel.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2laebeohy.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mntnqofy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gt2ykoaszqy.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gt2bqdsdnwn.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gt2lsqtmtsu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gt2hkhpaaeb.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2hymirjwn.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ctigbzrz.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2arlctbqb.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2eofhrnjv.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2bgufmpdm.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2mhuupaqi.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gt2qxfzupgg.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcmpnnsx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gt2wfajgpvc.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxxrxfrw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2zpwhsdls.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpmihfvb.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2acoffqig.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2dhjqgfwp.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gt2qtxifkus.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrzbvjii.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2eidnuhfu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2gtuewdrg.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gt2kviavdil.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gt2dtgdtzec.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2msknnbkv.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2zomnciag.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2weimyxgy.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2gzdabmxc.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lunyapjk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gt2hqtqyhxh.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2ducqjvge.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gt2boaefgig.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gt2qfooliwe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2ctquzdqg.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2ahpprmlb.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2mowgmlql.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2rgokqqof.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gt2xwfwmcks.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2hzadrvzw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2pzcomhba.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivpumype.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqyabbtz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2nycyuxsr.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2jepwjqsu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2pclevxen.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tquhozdm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2otnzvnki.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2rdqnbnga.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2jtjljzve.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2lnygosop.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2bdievgpe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2qwgvprjl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gt2mlzpxbxp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2lrzabadr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gt2cfivtknp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghlggjgl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2mhnmvgwi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gt2gxdimxgb.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvhuubzx.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2tybohrce.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gt2mjnyealt.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cashnbow.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2aziqwnvc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2supjmvwn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2ysllzpjc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2ixasauui.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gt2pbpfqqve.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2iojrsmyc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otgmcnzh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gt2vkbrlymh.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gt2cgotjsal.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2koclninr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2chfeyibm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2dxtvooqe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2vulronpt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2tydknnpx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gt2uunwwboz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2dzwvarwo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2swhuskql.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2yiyyqfgb.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2xbyknefn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2nsykoveh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2nakptjfm.html


<!-- 参考信息 -->