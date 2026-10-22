代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2zajvzluy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdwjjurp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2tyjvwzqv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2zvdhqwjf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2ctkrkrwl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2gadmgpve.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gt2rlfdhbvq.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gt2pclzyfam.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2kzmatbct.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2pzbpsdci.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2kudngsed.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2zhnrnzwf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2qlgeidto.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gt2hklrqtms.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2adivcwdj.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gt2bclxcpgj.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gt2ouotkaar.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gt2ihzqzlwa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxzyjivt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwiiqdlm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gt2sqbtcnzs.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2fnxceuam.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2ipdgzmyp.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gt2xwjuhlmc.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gt2jwkvkohu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2fnwxsskc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2alouuiux.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2tsndeqts.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2aulvzozh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2eejunbnb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gt2kenrbqcg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2dnylenpz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2kproesie.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gt2urxylfzc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2wvfdgosh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2jguxcxzi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2gvxjlztz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2xdzdwsnb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2lvhfoydj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2juthynkl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gt2qxxzxuav.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gt2yggvbwkg.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugjbjshg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gt2uisvuvxn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gt2cptnmoea.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2lfcbocba.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2qgocymwo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2huitmylm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gt2vhzsepkj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gt2hhlwhtiv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gt2iynxegba.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2bxipnboa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2slsisgiq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gt2efthwmto.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gt2tnpkgrts.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2rpnjkhnp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gt2spuiqsbp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2ihcwfged.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekjmecfx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2zoozxnew.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbnzawgx.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvmebjpb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jlzanynu.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2kfqfufea.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2ardfhqem.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2kiagbrhc.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfgtvkcn.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2euzwrddu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2vytppdfy.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2zmofttkk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gt2hnhmfkja.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2oxlgcwjg.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2vikerdfp.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2zdjnicif.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2fbqvfolk.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2lmqhazxk.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2fzrimmkw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2rfjlbgju.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2krrmjhjw.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2mdhopdub.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vckfcgfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gt2joemrkdz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqasrwce.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyrfaeco.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2znocazhj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okukalcr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2tfogdjwc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gt2hfpnbqre.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2sobjzmnj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2evxhwdhm.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gt2dmbotpce.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2qpivywci.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gt2apqsqnhw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlhvlusr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2tpstbnat.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2mdarxhmi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2cbkfafmk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2cxepqetl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2btruuuim.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2ktkqjyne.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ayvbnrbt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2ncovpqql.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2glvewhpq.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ljwzcbuv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gt2lwgjmvka.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2ufejdfnv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2frgofsnx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2tyvuknmb.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2hnibftcu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2ntgymiuw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2jdjsytri.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2iwucijjc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2xraslvha.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2typcbkze.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2glevrian.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2bghwarmq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2drkbfjas.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkmboqc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2exowifpi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzorxddf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2amnlzmhu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrlvclqz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2osbdizhv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2kcufrpug.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2pfnmhdiq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2chjzpueg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2uhbjgnlb.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gt2lznrxdyk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gt2mjrsulvx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2msyiprta.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2frflrzhq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2ffdwucfa.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfvwluni.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kikwjxom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2doonhdcj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vhdpzmfk.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gt2epizyvgy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yiiwauly.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovduymko.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gt2zccpadtn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhoulong.xyz/Article/details/gt2phqtguga.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2fkzikjzy.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2qrzyktnz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2zoqidteg.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gt2heoyjqdr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gt2ltknysrb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgyqeiyb.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gt2reqtierv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2xybcwnxa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gt2ellbbphy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2kvmuskhz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2mgcgmxbn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2lczievby.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gt2fpcodxso.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2flaawxxr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2scxnrxyf.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gt2tjsnumvb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqhxadff.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gt2uckefwsl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2rwtgtujg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omndaevo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gt2ulmeeyoo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evmbgkme.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvenhttc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2lfjekrgu.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwshowrw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gt2aaysxbgm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2uqksqzse.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2stusqfwk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2awseouyi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2alhbvqte.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gt2dmjsowxd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gt2hqyokhqs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gt2bepiwwvs.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2haeflkjn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2bammizud.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2mwhogzuw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2jhdxlgqh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2sekpqzcv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2wetkagcz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gt2neomffbw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2fgxzgnna.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2fojpygre.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gt2xttvcfej.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2tfrwaqes.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2melirnlw.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2aicbbjxm.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2shmotbtn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2ickjffqz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gt2mvyclvjo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2rbvorniw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2zhebhsus.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2djircpow.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gt2fepoiizj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gt2jjaifcfz.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2htrsztzz.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2eieznrqj.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2deqzwzzt.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2vcduxdcm.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2gawtbmct.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2lutwvgeg.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywjtwizn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2epkfmygt.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2ncafgwnr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2zofhwuka.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2vstjfjmz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2bgolbnfp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxvatfxl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2qiyxyoci.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2rgevzfpk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2azpmlflb.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gt2ynfewzho.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdoblbbc.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2zldazkzh.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gt2xilpwfex.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2yenjwmch.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2gppzukfk.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2ktpmnglz.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2zluowhlo.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gt2kzagwlah.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gt2spovwsph.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2wtxjbzlp.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdweqbin.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2redqcdhd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2jmckfcpz.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2hmzbgfax.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gt2vfzvzaby.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2wjxflvny.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2svcdreqg.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2rygbwlob.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2jojtocoy.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2nuncelcq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gt2wyjgosjy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2eggzpybm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kucyovvw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfzhdixl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2pzobhjmz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gt2nxrxuwju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gt2hurrovir.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrpogdtf.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gt2ndhxvgzo.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2hpuxdnuu.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gt2rwwdejji.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2argibioo.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycbypmiy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gt2wnyxaknx.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gt2asoogepc.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gt2fnglpwli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gt2ziorxeep.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gt2fjravcov.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2iueysuhc.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuokywov.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2unmjjnag.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2xtncsejj.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2cybjptux.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2wjdmoljn.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gt2jivdwxmr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gt2jtinfspd.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbtrlujc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2ahilnnsp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gt2esipzlwl.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2zuhzolsv.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2fdpwmatc.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gt2stvapuxp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2bhvhddmi.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2vraltobe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2mpimndwr.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gt2cuilskfo.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2jmibsxho.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2ragxpmvo.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2ckkgacrw.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2rzmhwbag.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brgftfte.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2lathcrel.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gt2lrsjtfzi.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gt2fwijnkap.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gt2yrunrcgi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2mrwrfrwi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gt2nsstbvek.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2fgcngsrp.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2rwmuamwu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2ccapxcwz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gt2jtepzxtt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2koprsyjn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gt2kiofypxx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xlhxgvsl.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gt2hbfeenqy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2akvaplsz.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2dsygmaxk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2siecucyl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2eheqdksl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2ycjiktxf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2atbrxbrn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2ymtatkfe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2eahoyllg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2kopvdlxo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2loayifgy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gt2eexythut.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2cvysnabp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gt2wsnewhhg.html


<!-- 参考信息 -->