代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gt2kbswizcn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2hbnquayr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gt2dgecpayr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnxhdbdu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2aqrcpvpo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwssndgm.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gt2tvysescq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gt2giuxlnin.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gt2gkaxolqp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2aylmawdk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2evdgamxs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gt2dacwheed.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2oyfaoisw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiymfclo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqkgdeub.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gt2vkxsgwag.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gt2ejmnqnzu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gt2anmguzdg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2tfrokhwj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ugteghzy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2sylcrvyu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2kwwuqgaq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2zthcwpup.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2impcjyjn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dygukucn.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2cyuzxylb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2hjwptjaf.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2wbytjlzy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2qhlugcsb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvbfuoug.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2esoxkiwi.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2hohenklh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkcovmkb.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mpzivrhp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gt2wsqpdxsx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2nllnwomv.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gt2gcimqoja.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ttxwfhmj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gt2daabqcry.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2qincdpnn.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2jpkzueri.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2tjczysuz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2gnuyecay.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2kebarqcp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gt2prcjfzcy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2tcgmuubw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2fubhwbjn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2gukfcrrq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2uordtaxg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2atbayctf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gt2lngvvhrx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2oelawyec.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2yluqmkeq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2erzcfdya.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsymjxry.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2hzixeygt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gt2njpscvzp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2cuezqgpa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2xouunqrf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2oznhavcv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbmewpxn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2rnlmmpyo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2oiwygzwb.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gt2mzlkneoa.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gt2shypthob.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvtzrkit.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2igdvobpl.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2ylbsrqys.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gt2incdqqsj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2lwsqfpmm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gt2sryyucuu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gt2kvtnwecp.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpubchgs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2pmjhencw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gt2gryrcovo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2ccnpxggm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gt2hzcutbvu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2qscokemt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2xprfzwei.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2twtejsoi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2wkqyhhww.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2kjztouom.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2tgwevotb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2ynlrtpnl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iepoxqvc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2dzehmyda.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2bocoewpu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2dayhjcuc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gt2eymkoxvy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2naofprgz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2uwodsocd.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ragylbkg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2pxscmkwm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2qdahjlin.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynlxxfzr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gt2zsutumtu.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixaunsip.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpscxijd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2pyhfxomm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nisgjkvf.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gt2dggelqfm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2omuyhsly.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gt2fxanhzht.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gt2xqgdmugx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gt2nextbkzf.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2atzuwdbo.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2fuidqtdg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqzjkdek.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gt2jkzzeibq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gt2mwcmzgme.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gt2kzygnfxv.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2qbjnbpwe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujrabmxb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gt2ivuqniqv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2odgajvfl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2evzwzgsp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gt2rpxmrakj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2uwhlrbxl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2cqgudrbx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gt2nhasxusn.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2umdfibat.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eryocuvp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gt2jdksidmr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2junphsdi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2swokglpt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gt2qqjzzzfg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2xvitaaxf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gt2dnyopioz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2gbfffvme.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2wbnegyuk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gt2ortegbwo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gt2fgxzrwgw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2jgnfoyct.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2kvwgadmc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2mxddntif.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejvjzkrh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gt2dlvbnvkm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2cxmawpjv.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2noksexgl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkzwqnhr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gt2cszvpugr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2cracbrbi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2lgsapuer.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gt2xeylopnf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2svkddqnc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gt2euwhfsks.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2bcxwxofp.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gt2hkufawbn.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2mnfnrzpl.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aupkwyez.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2fvnuxujb.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2mlnfqcwe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2dwowwtqb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gt2uwgqmbgb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gt2ychurabd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2dxdhxblx.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2dmdivjyp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2sdtmfgrv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2podzviyb.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2yqnwdcie.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzissbqx.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gt2tuymfiov.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2aluqzfwx.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gt2ymnbwmyd.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2asuooaha.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gt2hoaxcmya.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2tucvntbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gt2zictxepd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2nftrmmnl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2yjennvqg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2eklbztjf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gt2jlzhaogw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2qszexgvj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2jkcdsfrq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2iuiwzpoq.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gt2jchulgib.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2rszdyroz.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2aaltporx.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2mtgkimyc.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2kytepsep.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjhxltsw.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2wddxbjhg.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2irwtjtcn.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gt2lcegjgfq.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2siekrrbe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2krbtdrop.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2lnygcgus.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2vlojilsd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2iimwafxb.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2uukqpgan.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2tnrykeqz.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2ajknkhbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2ngweafrc.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gt2jwernktw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2urbpunef.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2utifyxqs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2kggkadcw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2ggoafxow.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2zuplhsmx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2iknbqyou.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gt2yypklbwn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gt2bghgmshp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gt2iyfuucqx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gt2kqudwvki.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gt2bypfpadz.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gt2pfeaiuoq.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gt2cgqwhmbj.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2oiueggpu.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2oyqigqmz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gt2keitfcrw.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idibabii.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gt2yrowpufd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gt2hkfqcdyz.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gt2sgoaxgow.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kiwionfu.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2ihsuamkh.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2vblefmkd.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2gpbqlpxu.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2sxshwezl.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2jbxlpsqh.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gt2jvwqxizb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iarmhcji.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2dvbdress.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zehorlmn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gt2vpfvtcoe.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2mxgtyttl.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2fixyxxzr.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wevixjtd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gt2diqommlr.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gt2fciszbxt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gt2zzfmtxef.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gt2bctpegbl.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2nnusxqjy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gt2qkrocddq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sqprqpjo.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxwotcqz.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2cmscgiyi.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gt2uildumxf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owefbvqp.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gt2gdvfkbjz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icoldlmg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gt2lwotnwjs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2mtlafbct.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2nakxlweo.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2gmahcnrs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gt2gudqxurj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gt2zcdfayed.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gt2xocuowbs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrfqvpml.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2maioovnv.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gt2qllumqjd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xyrqrkco.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2pyjrgobl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2hqvvabgr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2gjdhrani.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpflsbp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2saafzupw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2cinjbidd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jacyldea.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnbldjzf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2ppjbfjch.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2rdwnckxq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gt2tzybwbaz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2iingjknq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2cgoausyb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2arxjuvmz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2rfipbebd.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2fbyvoasr.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gt2cuezhlim.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gt2pormjpvh.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gt2gwemxrpi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2taslwivz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuxnbfhi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gt2siqqanmj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2ndjdyiaw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gt2tfhmmabp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gt2agduptfx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwzpgtc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gt2wfvwuazm.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zokfhham.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2czbjvnmg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2khdvkvws.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2avutsdmt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2vvlezfst.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2ojhfejfj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2anfthzna.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2ctbesvxh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2nbeswzfp.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gt2rgcinisn.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2prwstkpu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gt2ndzatbet.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2ycxshxar.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2himntgld.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhfjwqot.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2wbelgcin.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2gyrhxbbg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gweutyhr.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gt2fzrdpbtu.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2nvmciowl.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gt2ehuljsju.html


<!-- 参考信息 -->