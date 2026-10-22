代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2iequwtqz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gt2nsujyete.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2wjspuszp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2jpsthysi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2rnawxvms.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gt2uvsilqzp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2diuohxop.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2rjqaaknk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gt2tozkbhua.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2qsstupha.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gt2pwdpuxem.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gt2gybgyrwq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gt2wreevfby.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gt2artkadag.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2syevpgvp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2lewpxibf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsxzcllw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2wycqblcg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atenvtor.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2hehiwtgi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gt2bwyduebl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2evmvyvtd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhxsiigt.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gt2iinhbivb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2isckuimj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2itxqqdkc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2zqokzvbi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2atrgblbw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2tkcqxkcu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2gjmmaxrj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2gvwscetx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2epxtgnjf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gaeeyaub.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2dlixltuj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2eqcjrkvm.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2xrvcspyr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2jcmsnmaq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2gipmulft.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2ngxzodmt.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xsehnzzw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gt2rnaeofmh.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2fqxniaxw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2jjyaqzlk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2sorvgnzt.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gt2iraihksj.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gt2mnafhtfn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2zyagvzdo.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2jbrqdfmj.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwpbwtno.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2avhawiff.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2qhjoymog.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2umravlun.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gt2mitnatrf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gt2xufgcukx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywnnzkby.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2xqowtlak.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2hhryskbm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfbirtdq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2ddznvmvt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gt2ylmifzcp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2tygotpnp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2epnkizvy.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpngksuy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2hhjyielw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2cgaznwii.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2nkerlasp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gt2bgelpvbj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2uokdfnlg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2janhofiq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2abgeeyjs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2wecqsmbz.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gt2vofnfjkw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2wqsfjjsr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gt2sujzfgzf.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdmqhyxu.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2czcjverv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gt2anzsxdaz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gt2gwahlqzq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2bwxhhxqh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gltcydrh.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gt2fmsiyzrx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2geqdlleu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gt2wgoibrhi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2btclxwwy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2yndbrsfg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2gicqoyaq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2olsiaqdm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2intoramy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2zytflxhr.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2fhurygrh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2wfuycgmn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gt2zcljfsew.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2njvehyaq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2awqxsgxs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlkrfpha.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gt2uwganvri.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gt2rbprdavc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2rfmacshw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2ywncmlbe.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2tdykysan.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2hvnlktss.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msawndwz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2pwbxapmy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gt2mmtkypgq.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gt2akicdfod.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gt2jtqkxrvc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2mirwoxkr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ciydixik.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gt2ieakimgp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pgvxdmsl.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfomfokw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2zblvmkmw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2buzyhbwn.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2aibmifkn.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2tviqzvoz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gt2rfrjdlrp.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2lndhayro.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gt2mizbscev.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2soyvozgj.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gt2jnteeguz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2nwskqgbn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gt2rkgeadtj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awjdugsd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2ifqjtqpj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gt2theqezid.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gt2uwooqrvi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gt2nemfcrzz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsiwuivq.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gt2ydevsoyf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gt2ktyckgcx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2mkuimgqk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvhxwwjn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gt2oqvosbyv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gt2vwxtejyv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gt2qqpvabiy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2hpszpxel.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2icwqhpwv.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gt2ysmkmrqv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gt2nyoabnlg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2hxmfkzos.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2jpxysezz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2tjypeois.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2ijjemcgr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gt2wzjfbxiz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2azugdnsz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2wkavkjcq.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gt2hxeezyns.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gt2szudxqix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gt2elmmdasr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2ajuqkbvp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2nvjuxzkq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgbkcxwl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gt2rryejmak.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gt2mjgarbyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2qqxikwew.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gt2zmghcfis.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2lpggmolt.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gt2psfnsyfx.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2geisadoq.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2dhphasby.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2ggunpmdw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2gnunspti.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gt2pysemdee.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gt2udegoasw.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2vroufjwm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrpexgsx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2esebzvni.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2lnzldxpc.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssteoqkb.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gt2zsqhjwlx.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2yeabvhzw.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gt2bquxsmha.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2aqolzykl.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2djntcdgp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgygntg.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2ullplbml.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2prredxql.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2yqznbepx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gt2psbniicc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gt2gmvytfkb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2qflxwhcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veluxfjz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bhyhnkzh.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwemrblg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2rpwwxuso.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2yiilxshc.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gt2ybelucjr.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gt2skjqbtnp.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2kieeyfxr.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2gtvtpfbm.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gt2ilneyrri.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubmgfzrc.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gt2yolgkhzp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2plzamjkx.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gt2wuywfuhh.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2pjopfiny.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2ikbbcigc.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2cqjyjumk.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2uoqtwjsd.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2otygckpd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2mkwqpvdu.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2siuacewr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqaqyffq.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gt2mwezavck.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gt2csvcrass.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2isxgnbsj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2dhghfsdu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mavakaut.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2lvbvvhmc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gt2potgvxmu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2htmkefgm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqbgjgys.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gt2dhcyxuvt.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfelhdcl.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gt2pqxqtwbx.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2dsslftvg.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2qgjkeipg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2ujlvqgyz.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2cjzrfazj.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gt2bbhqjdek.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gt2oeocyhyu.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gt2rziljagz.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2yseepaxw.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2hvagqvms.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2nxuyjhfu.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2wqmixozf.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2msoaacxb.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2voelqfxc.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gt2nzwfwdoj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gt2rfphjkyf.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2ffeckxqp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2ulutlwsj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gt2ezhnvfli.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2njwrdgju.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2jfejuzez.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2gimjkfwf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gt2lsuohwfx.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2xnurffct.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gt2zzqnnoir.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2yctxcwqd.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gt2cqvyuzea.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gt2xkwfxqij.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2fcanwbka.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2ejcxazpk.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nldalswd.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gt2zamibvhs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2ghinpwbg.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2paktkxsw.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gt2dfwnykji.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2agqqswfo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwsiivdl.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2nvfyvttc.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2qayiutwc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2whqaktte.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gt2ddvgpkyb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gt2gypnkwkz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gt2ldxqubkz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ncmsldtm.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2vjxigdkf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mnwjujet.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gt2vngmbmdy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2blvpkdnq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gt2tprdkppg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2kszznbuf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2prhddmpz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2mvlyirta.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2shfwinyg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhkesrtu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2lwijoaae.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gt2czjdjleu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2vhjudcjw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gt2okmyruxi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2dhmcputi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2kcveudqw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2hweepmsf.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gt2nblchciw.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2fsbtqtqr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2xocvdsmx.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gt2yinhpzny.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxtlisxn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2gxaioymy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2lzhxfwww.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axfsepfx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gt2svothlhi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gt2avhpatbd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gt2iluzeijn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2nsoujnjd.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnmgxndy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gt2xgodovhb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gt2pnjcmqtd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2xmghcxtg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2wxxllzhj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zshwprsu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2xgornttm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2jqhdemxv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2cveqtkny.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gt2nweevior.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2rfpplnnu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2byjkyyzc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2poaevleu.html


<!-- 参考信息 -->