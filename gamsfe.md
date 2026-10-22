代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gt2uchkclzx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2jhxctkia.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gt2mddfzpsf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2iisskljf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyjnqxiz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gt2egslgsuj.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gt2qijxsmui.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gt2mrwfmrrl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gt2mhizdkml.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2sepgejmh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2iweeswkm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2dzoueypl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gt2wjvwyxzj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2ifpsmkam.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2blyhivrz.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhedhwxb.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2fmedmxpj.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gt2nqkcivlg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cybdqknp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2qzhxjnvb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gt2jygvuact.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2knyhiwhw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2ouvuvmsa.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2lhcviegh.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gt2rqzpmlse.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2itsdgksl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2mcawtrhq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2aoywikhw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shzkbmkh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2nfuoabeb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2dkyaquih.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2bubqdlbw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2yxsluftu.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gt2vetaymim.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gt2iziqkbbr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gt2nmyuhpmp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ellboobn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gt2ojnnlbzw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gt2bmafpgwj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gt2heozciku.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gt2idtgpwwt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2tpbozdrb.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2ptxkokzw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gt2egmtxrvu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2gufdnsyb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2ifrjlbxd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2skddfmpl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gt2xssaumfv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gt2llfbskwh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2lfgscnih.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gt2olbibwjb.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gt2vybcfasy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffzibfki.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gt2cujfotfd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gt2ysfjcaue.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2khenqcog.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gt2gjpvwtbc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2oqekmmpu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2ufvuwybb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ppvuwulw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2erqpziye.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2ondiuijp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2rrpnboon.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gt2zhwqbrsw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2grkhgart.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2kbgallvs.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2xmnwrggw.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ehludvmx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gt2dziytxae.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2ipabfhif.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jccydgzb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2gxjvsmze.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gt2tyhscdfc.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dffwfvgl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gt2pvjfamoi.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2fvggldsk.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2yzqetbll.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2qgtqwdai.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2shzzbvzx.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2byowfybm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkilxyqg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gt2jwuasppy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2jwsjpcdj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2qahumkgm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2ckmixcog.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2hwpwivgc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlxbbwcg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gt2usdayjyx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebqwqrgy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gt2bvpklmsz.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gt2ofrzpolp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gt2rortzrtn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gt2xylnagjo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwqcrxub.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2xyfyyqgm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2ffsycfrf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzygaxxo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2ukelztay.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2mfbbulvz.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2hdcjqxgo.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcugljau.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqsvlggy.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2hkdpneeb.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbrkuyfo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2phanokav.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2cmhvlutf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2cxqctafz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gt2dqwdjjfp.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gt2dbpbmxvz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rugnwvno.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2vlvonbsx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zakimrrt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2mtozdpxx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2bsmgcuqk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2jsmxbtcp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2wiavywpz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyzizchp.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2zttrokfi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2ffetwsmn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2upmankcc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2nhxhywjq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2cxlfrzfo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2zlbgpcld.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gt2xpvkpncv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gt2iscwuvan.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2dewwubxq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jatdsjjp.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gt2xlchsnts.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2csbxbdkh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2apoorehw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2qcldwfys.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gt2mtcdfyvl.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gt2xinennop.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gt2wkfhefwr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2wayuhcqm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2bhjgnuwg.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2hphszded.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imuejcjt.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2dgqhzfqm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2dyrerfaj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2ynaxdtbz.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2aclqmvre.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2bseuzzeo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2xbnqriuc.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gt2pcxnwhwm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gt2pvgzfwpx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gt2enauqhlk.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2tisgwetf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2dhukrzvd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gt2doquzlug.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzuwrkan.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gt2xcbuwagl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2ilqnhikm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gt2spnoexaz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gt2ssbhabmt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2lrvnhozy.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gt2lsablmxv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gt2caokwhhi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2vkgmfcdi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2xzqfyrmm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vclxkgce.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2nrmkiqtc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2tjfvmqal.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gt2wdzgvsey.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gt2xrmkirbs.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gt2nshfmlvz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gt2cevcxima.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2iwgrrgsw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2jlsdxmgp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2wuoysmzb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2znwwxgoz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gt2wlykovkm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gt2xjynacfb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2uoozxawq.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gt2psqujlqz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gt2wxpiomel.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gt2hucopamc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbhpgypf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2duziwzjm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2zjaesrhe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2gzfyvzwy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gt2sepjbnpg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2kozdmmot.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gt2okovumat.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2ensepmyu.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2jqbvmfcv.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2rmncebgo.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eivokbfu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2pftobudq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2ebqhsmlt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gt2tiwfvmzj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znielpzj.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2yxwhtxuz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2gnkwpnke.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gt2asfkenhe.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2tdpfbqjo.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2qorgztox.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrozbtyq.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2akzgxsma.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2sowjhjbk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2qteyntsr.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gt2kmkeupcs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gt2vcnonnrk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gt2gqxfoktf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2ooihzcqj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2sysjdqpc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2tohnrwle.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gt2pktxrlbp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2nbknipwk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezwumuzc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2etbkrpmp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gt2rmytqrut.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2phsmmrqv.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2ddtygizb.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gt2cocehvhz.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gt2ugfkougp.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2gddmuexh.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2lyjukbyn.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2uabrtxhe.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gt2cqluqepz.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvzsjvfj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2gbfukjge.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2vgcvwieu.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2kpkimfjq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2rqjaceox.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2voaddyux.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2crdizvds.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2daimgbpv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2kvoqenmq.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gt2cutddxsy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2azbsfctx.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdqlumih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqwyzkbw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bguupnyt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkesdufi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2bwxgdglm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fadwhohe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gt2yuuzbspj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgtqvzlh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmwvwsar.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2dvxwkuky.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2ywpwadwv.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2bqfxtmue.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2bfnjahjo.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlahpqhb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gt2efiepbqw.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2olvjajck.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2qzuaoilq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2kuiodqha.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2ygqnpmos.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2ogmgvamd.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2qrmpctxi.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2qdzyuwjt.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2mqsflkkv.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2stpuvbbc.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2qujipxix.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gt2zevjfsis.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gt2gavngxuf.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2fdkdkgui.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2rbeqfwef.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gt2dpjqthan.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2zeyxziiv.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2oaonalgx.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2nitwkibk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gt2peetjbmi.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gt2jqkmlwvk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkmtxhcy.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gt2bcpymkfh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxamposf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2zaozkqxi.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2irlenzwu.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2algxljap.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gt2kldoblgn.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2vfxpycqb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npzeswgi.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhynalvj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnmvzbfn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxzokews.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2ieitiawk.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvumbguy.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2hiojvsgk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gt2wpuxkrbs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gt2pgrwrmrg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlaprmsr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gt2ydlurzat.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2suptcmwl.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gt2szduwazi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2rqpepwga.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gt2tuxcrqdp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2injpelod.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2uyfawpal.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2srvqctpw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2otceujin.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2qacclmje.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khebhdem.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2evkayjem.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2fpsonkem.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gt2cjrageov.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2uomnbvzv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2stljqnmn.html


<!-- 参考信息 -->