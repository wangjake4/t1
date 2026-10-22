代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2qhwqnyqc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpeptlsh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2uwtwyjzj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2nidwgana.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtresbiw.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gt2oeyautid.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gt2wymaicgt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gt2dygampwc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gt2twltcuvf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2zqojqjhb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gt2hnxqysmi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2owqorwpe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gt2ubjvsgat.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2wpdpktkt.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgcrcbkr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2vilinhgf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2lkfrxcge.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnkzqkam.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2pduwnccv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2quzovqpy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjdepita.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjaiymvp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2ivrnswya.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gt2klnwzadz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gt2zrhgpwgz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2esxaxajy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gt2mhtqsnql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2zvomypdc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gt2dgaxcvsx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gt2xijbsrgk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2mrbmgpeo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2jblnoyeo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2bmvlugjs.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gt2sowkzyhy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeisoayk.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ewttfuau.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2ybkybctn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2pqbcahys.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ofzmmvjy.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2nwrcwslm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gt2wtbelohq.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2czhprclo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2kuzkdvld.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2yesgfmhy.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gt2gbjvfklk.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2jnbvogvg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gt2riqlxlzi.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2xsbncywz.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2qjusqmmh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2learniix.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2efxoqjgg.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2xlalmxfg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2cktsywye.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gt2exmduycc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2rngvlzgm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2mdmfgrpc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkjoflky.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2easbewqn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2rysfjapn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gt2mvyidgnu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kersxbzq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2jgztnebg.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2ysuwzhns.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gt2vlpwctjv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2wythxtqh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2emclkvut.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2rggmqjdy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2erxnjifm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2evudxuum.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2bnsnkrxu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2wovtgymh.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gt2wkmeqgpn.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2irptnfca.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2znctisbd.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngrqjxcr.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2rpikyflm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gt2kkymccen.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gt2srqvdwxl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2azuedxdg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adelwmpl.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gt2bktgywgv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gt2ekpcbidy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2drviqcgi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2seuhwxue.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2ihlfokxp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2khouscps.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhtucbop.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2kjajikha.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2kagliaie.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gt2spdlptjf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oepipvme.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gt2dpncosmy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2cxebvsey.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2losnbfqh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2jiccaprh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2rljfrmlj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2jxsnbfaw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2cdxvhhni.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gt2jnrnqzoh.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ctnldotb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2jclaxoxj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2aofndkmp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2pmyftfsi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gt2gbtvnplz.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gt2lzwbfjfg.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2oqvciwor.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2hybgskyt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2zxhfestq.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqlkchso.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pysrxiex.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gt2aanjhpdw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gt2touluurn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gt2wjndsraz.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2svgdyrde.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2ljjodoff.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2uzupyxed.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gt2memgccny.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gt2zqpoamyj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2jkmamjsx.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwkxwxis.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2cbdedtri.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gt2qqvkgynu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2drcdkelo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpipmqpo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gt2wsreudhf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yluairey.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gt2esgvegsh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gt2vuswcsfz.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gt2qrzksynx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gt2vustigyy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouxrdbgc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2btiqozwv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2ymjzfryo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gt2mclwzxvt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2oskcjqjl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uehhnqnc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2wbthyaxz.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgezvcca.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2sgozonqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2oqoedhec.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2hltxwbog.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2ifkgzarw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2uuhzpsgo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2wnvguryk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gapasava.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gt2dskitlaa.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gt2tllgoajl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gt2ybrxxsmi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gt2sjwkyxsy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2zfzcyyvn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2avdehglz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivnohmsw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gt2iniufpyi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2pnubipyq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2khzfmblu.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2hgxfarjp.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gt2wnarhqiw.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urdhkqlq.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2ahqasgiq.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2aykaffpx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2khvhsoho.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2tgkeyzyk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwgragfi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnksejkp.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqwkewyg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gt2osqmgcsp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gt2bkeinpvb.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2wlmolqzs.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2cddwqwoe.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gt2omqcuyrk.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2rvmnajae.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gt2jmcisayc.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2yzbljkba.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gt2ggkjtrwr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqawjooe.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gt2kxqyovol.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2madtffqn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlhnwbro.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2qkmslumm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2pgpoggjl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2mewvoivv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2smwrwdlt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2psjadlmi.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2jzajoifh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibzopret.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gt2tsvdujtr.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gt2rncdigbf.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gt2mhfyttvz.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2iryvnxtu.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2qdsjujlo.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2tnmwxasc.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2bnknpyko.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2hmfetctt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2kfapnwst.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2hiqdztcp.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2gpufmhhr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2hrwgmnkz.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gt2jocetnzd.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2jzpccjqu.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2kmgwegae.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2dgkbisvz.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzrxsbir.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2wgdjtdpd.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2mahjzxdu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2rpaglzcs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2achtvagw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2jwpwtdww.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gt2cuogymux.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gt2hfitxffa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2onneasoh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojqneytz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2xmynbsfa.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gt2syyxgqtd.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gt2gyluogrm.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gt2jqwsilod.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2oedwfixp.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oposazxn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2gbdmerva.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2xrtslbzg.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gt2szrcgpnt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gt2gcqmcewv.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyldevqg.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2obblmtcv.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2thwfofyk.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2xpdbqvyr.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2edjjzssh.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2tdwjoivp.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2niskvpzt.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gt2yierwvhs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gt2kquypthj.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfadxvmu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2veuichus.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2cethczew.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2ixjbfkde.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2gqvtethh.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpzdylwy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gt2nbkhvfvz.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bndtxlfs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2erbqtgwk.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gt2xcvouwfr.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2svjklnak.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gt2mvqshcjb.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2vgjmfrtx.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2bevanwbj.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkzddwac.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gt2uhvpwpxp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gt2rvtxznmk.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2cfbxfalx.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gt2zswmcvba.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gt2xttshcur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gt2rffzupmr.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsktjlfd.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2vzncnuqg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2meclbyra.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gt2gzfxsqys.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gt2btvwhnex.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gt2euhjhtwh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tcqepmsi.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gt2sipzbbac.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tckcslbo.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zewyworo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2mhtxhhbg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2onbvxedx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2ggmulajk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2atweukfz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2bvwwymhr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2eqnvvwbf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2flcsgknd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2teiuedmi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gt2xoqpeqlw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2ykmunkni.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2oebwduhb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2xttrreef.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2feipqmid.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gt2mpulroeq.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2kzifiesu.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2ucohskhx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2hyizkwpc.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gt2womyocgs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gt2fwndflbz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gt2lalntvqo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2zvejmeke.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2brtgzmov.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gt2mvlywzli.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diprqymu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gt2xujegjel.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2ghemvcud.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2qvgxqecr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2jgcmdgyc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2vcyazjqc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvfifnxb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2qwtydaxi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2bedeyvgm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gt2bfexeain.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gt2fotpofrf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sntpagsr.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gt2vyjxjdie.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gt2chwqploy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gt2ldkentke.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2hzbhuccg.html


<!-- 参考信息 -->