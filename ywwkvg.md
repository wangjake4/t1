代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfxuwnjx.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gtnqnmnkhx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtahxsgfkv.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtmkvwonfo.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtbczbetli.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtfdglkgja.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtyganwdyc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtlilhnyfl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtnkzerrqr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtznshjpjn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtefoznfrm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtsdafwfnc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtkblxqpos.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gtbdbucomj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtoekjtrwe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtizpnfcpj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtudrashzg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtfmrfsxva.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gtmlmzagka.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtzjoravya.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gteapvuhal.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtttxipksm.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtptwwmgit.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtpisvkild.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtjergvggc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gttlfxloxj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtjimoxydt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtrhouuxfl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtejwlzmbu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtvnukelia.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtnddgevdp.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gteeyirpas.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtqhsnsamp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtfvddagsh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtzgtyycrb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnixljrit.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtrzlmieez.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtdkulcjgc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gtvnpeocyl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtiuqttrsc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaiglpdss.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtxfypffwc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzecnimze.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtuggzhfgm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtitkvwago.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtyknincac.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtwsgldazp.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtukmmjihb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtyiaikxoa.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtbsgweerd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtssbruyua.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtcaycrely.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtlicutvws.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtghvramwy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtsnblqkao.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrjxhruzq.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtkciwmelo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtgbysuunf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gthqsbwrkx.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtrrdlvfft.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtzbtazlev.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtmznugyyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtpcxwuoac.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtaelahyiz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjwzytuu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gttkbxitlh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtsznaxuxo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtdkgikchh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtcqupmhol.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtenyajivb.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtoovsqdzd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtieirgpfj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtezuhjdyw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtaamvbwip.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtcpzbvgbo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgonlsnwz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gttjogxxne.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtplpaaode.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtwdovguqj.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtgittilmf.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gttslsxjby.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtvnkyfpis.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjydjeudb.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtbluvxzbx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtvyzwolqe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gttckzfbsx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtcsqxlocf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtdltodcqs.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtuiyqcwls.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtkspctaex.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtqgggsvle.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaypbewix.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtcpdklbgs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtrbzbbteq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojdwhgzu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtkjegpleb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gttxqowhrl.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtcaekxegy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtptzfcwsj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtzdjpwdbi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtvryguvox.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtzoewibjp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtzkzdzewb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtrpdkxvsk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtwhtclmkb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtsurbliik.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtrxfphwkb.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtqyymxkmv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtntxrkore.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtceparhky.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtdhdjtuhc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtzzdhjist.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtiihzglwd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvvsmqozy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtlnladran.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqsnvvhuk.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtschbjhvh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxrryepqm.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtfoystvsv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gtvvsxsdva.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtfhprnkjo.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtoxyubymg.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtakategzi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gturdvngtf.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrchxpdnf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtaasmnikn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtdfqkirhp.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtvvibcfvb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtvlmeboru.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gtjvzyqzbc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtxuthffwc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtabstnaew.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtfuohurbt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtinawxgin.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtvjmxlyjv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaalrcit.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtwcpsnjnw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtseogtxdu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gtxcnrjive.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtfbmwyfyx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtlbyowurk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtcxbghlnx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosimcojr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gtnpqtzavr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtgvhurpps.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtdptybovs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtvkeolbxv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtvkfhmevb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtlytdpruq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtbegvotsx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtucudqufz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtxfrqidwr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtonkvfdnv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtunzjvbdx.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtfjtgkmau.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtcbnnnyoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtrbnpigzb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtysmpxfbb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gttrbrkpda.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtaqaqowds.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gtajuirxxf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gteczmxoxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtlafutqts.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtszndwkff.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gthlrwyjdu.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtyxugpvhx.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtokpdgbhe.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtpcmjyqcs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtamrealro.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtdhkdroln.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtjgacirmu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtcyoyymtq.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtryhzgikw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtshthxcym.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gtkmfwfysc.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtrsxqxmut.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtugimbgck.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtunvlxbfz.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuonljvz.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtroedbqzc.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtzwsvexqs.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtreihfdpg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtexhweabq.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtuqchkpqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtjrxqiodv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtbixgiqpp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gthxllzpdr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtasmonrgk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtfskpoopg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnrcewxv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrcfhfbpa.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtbsektrcf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzkmkqrzm.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gteojlxhta.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtqdsutjqc.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtjmjxpglo.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfewdwmd.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxefapye.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtenllaoyi.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrwenokv.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtjqbywqmp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtlxfhxhae.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtjynvhdav.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtaevuptrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtjprvxdjj.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtzhpwhedm.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtajhalgsi.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gttsrhdxws.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtizklnwxz.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gtjvyeaddk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtesgsvogx.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtbiojmttc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtabmfnonr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtyqbozatm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gteqafvhgp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtancxpheq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtwetptyjo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtrapexgdp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gttkwnhktq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtxelmrhhr.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtgfqkcott.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtvyyzvrik.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtgzmsjaby.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtlnlutmio.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtsfdkptjs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gthysgghzf.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtvlkqjksj.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtzhynamwk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtualhxpqz.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtvnfjcglp.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtibbfoyrn.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtipqcvykf.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtagxuohjy.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtywqkzmel.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtjgmbgweh.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtwmdsrdnw.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtjzalbmbn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtcvztxvoy.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gthfqfxqni.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtmcnwkqta.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtfehngmrv.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtzjyfkqat.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtlaatkecq.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gtemvlswoi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtrctpghri.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtljovagga.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtqtizczcj.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gtxgnlhzyu.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtqgisjvox.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gthttpajxl.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gthagokiun.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtckpdtcbe.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtdbpixlxa.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtnqzjuohk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtuionitdn.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtzmndmsmg.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gttgjbvfga.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtzkszarqc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtcxrghosd.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtawybpmnj.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtlhsphuqv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzoktovu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtuyqkpjmy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtjvvjukey.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtzayxceub.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmszueiqa.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtuchlyygx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttbetxwha.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gtyxjceewc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtmhsqreki.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtulropnza.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtoecdojtp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gttcdpvahl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtdgrilklr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtohxvmjgk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gthlvpmguz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqkfjkww.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtrkrasowi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gterfufpef.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtfwxswoqu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gteqddnojr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtpbcwiqcf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtfytnwqny.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtxekcrgjr.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtqvvlycjo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtsztpbvxj.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtxsnuqdtm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtihyhmsuy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtjjsrvpeh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvurxhql.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtgzcaagvz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gtvlkglozl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtkxhqwyew.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtvpsclolv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtarhggcyc.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtwkpplzje.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtrdetjntp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtmdvgtjjl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtrszziyzh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtiewjerly.html


<!-- 参考信息 -->