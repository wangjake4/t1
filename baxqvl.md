代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhscqrpj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtmydsyudx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtqpdbfmse.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtpfmffjhg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtrdpodpfd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtzclimrjd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtfuzwmlhj.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gttqrsybpn.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtmjftuvij.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtyuptzzrh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtvsdqyyyx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtjadntbjb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmitembqj.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gtenmakpmz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtzchdhgxs.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtzndwdcyx.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtbhsbxlrd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtcmdnseds.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtjhopnvfg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfizobbk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtqtgciexk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gteomnoizz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gttxegpgkv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzufoajh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtswtlxrph.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtsggpveqq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gtcogjcrkf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtdxyjhlju.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkljkqnjg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtzapnfyue.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtjhtfhmrx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gthfuxtspl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtnmfxkkpk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtpmkiazrt.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtbobciuae.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtifehfpyr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtslfeycpm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtjmswnejn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtyagsomyl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtdckbkdvm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtplstkxks.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtmjydfklb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtjiavkske.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtkzcwinva.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtlsgpqrbn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtotgfunli.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtvofhncae.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtmqmomifw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtgnqmdyra.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtogfndezv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gtzlxedyhq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtqravwqdw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjtrcztuc.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gtdhlgttsk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtevdpzbna.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtwzugqtde.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtjuljasim.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtxudlcuri.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtoriumzkr.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtxiqlfmdm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtxvkbalih.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtuokozozd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtbrribjfa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gttrzypekp.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtnusvwukr.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtavocuwsd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtknrzrrxe.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtpgkamknp.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtarmnutzp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtqxjwcmcm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtimqzrnhc.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtcxuajjhy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtlaqkevqr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtzzfnoibz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtotuvkkgf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtkrhvoezq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwgvflxiw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtlpyrqyeh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gtgxuetsew.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdemuzmab.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gtbuqkuyjt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtrerboyzs.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtwxshxrtd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gttcziyshp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gthtcfblar.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtupvgsnoe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtukwnufvg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtseoykuzs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtsvztuecg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtlaxyzkqd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtjmbdahyr.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtxehtfjpy.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtnshijvjt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtnrhmhdbr.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtngefdrjn.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtdhuxtszl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtizxncnjs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqssihffb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtzqktrobx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gtecwamkhn.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtxkvzgqoy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtyrdxgaph.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtxwopqcnd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtluxxvcbr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtcfgrxjwc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtaogycevb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkhokqvx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtgdpppgld.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtxcetiqzf.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtotclqtwl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtbhfhajwq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtfjjqcfpg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtnipnbavc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtedkdicvv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtynopkbch.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtfzluqiqt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtwotutblj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtgrqucbth.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtuzyrillx.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtrivhjjcz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtrwdftreh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtnipetkcw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtfwqksoba.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtxtbxcgci.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtfsdueodr.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmvrktoho.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqxyeulr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyizioflt.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtxeumcjqu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttlnsnevk.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtmamfvetc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gtubwtvbvb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gthtkvhtcu.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtzmazkqbl.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtemekepwl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvkwjhee.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtvpvgeylk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtbrmvdkqo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gteftgukfj.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtooqipibc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtgyqnupsn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gtabaaaxql.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtaryexrry.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtldqvvvrz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtnvjrudkb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gttlieppna.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtpuzuxcuv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdczhohgt.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtieoakzmi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqmblacw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gttixinefy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtmebnrvhl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtadbbfsxo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpeglyxa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtlznjazez.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gtgzbqejcu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtzzshxrcf.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtvlnjmtno.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtyjtlqcag.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtwsognssx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtjomywmos.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtsdjsejri.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gtwaxkrtyz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtevitcggn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gttioefedv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtyfmwryph.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtzetjyzqo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtjvkmsftr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtufqcpusf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtjzqvtuqd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtgdyjcuww.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtlrtkuwns.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtfdxbxydn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtepgceqkb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpxjeykz.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtbyxlwpwz.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gttqnodsrq.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtiybxjycw.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtozpyiubb.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gttdghcsdm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtbdslzjqi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtayiwzwli.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtodzkvmth.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtonpouyin.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtynlcncru.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtemawawyk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtmmkewlar.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqszjcwy.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtthmzyved.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtgdfguzhv.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtkzcsilen.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtrpcrvlau.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtxyjbzhid.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gthxnxrdor.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwjvcqwh.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftasaoti.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtbonspxfm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gttgqmannc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtpjoavial.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gtrdxyxuod.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtjpiyhgbu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtqsyqkxmg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtappuinai.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsgiftoo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuqralfpf.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtyklhecpj.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtpayrunoc.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtwglndeqc.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqypahcfv.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtbsgaakwv.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtblzshifs.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtjoybmmyf.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtuadpkcoe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gthwgpglrn.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtqsjuzvta.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtplwpebtu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaomnsis.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtvwkuzsgs.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtyvcntdlj.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtwtsyzykt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtauvcdrjn.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtnzyoabbw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gtdsyozvni.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtatuublrg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gthhgnhemc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtegzzealz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtjkduopxj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gttkenjlbp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtgrzfsaua.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtmheascpi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtatppjpqv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtddahqywe.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gtwfzeoite.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gthqnurvkw.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtguzhiibt.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtwkowspum.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtjefwxpda.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gthegcuslc.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqpwgusu.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtuqfmgvij.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosxwlutl.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gtzjlwzjuw.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtegzvpqep.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gtyycecgsu.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtrqhujipl.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtivkcrzjn.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtqmgkhber.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtwjmicdsu.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtgvpidemi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtbpnufbnk.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtopbvknyd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtbecuzxbh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtnxxjkryg.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtxhgngwul.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtwdbyhlpi.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtcmstwnjh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtlfgzucyz.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gteebmlqbo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gtwdtmlafb.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtsqvxhyfp.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtsnyzvpvd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtisygleba.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtbnftqmzh.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtyyfneplw.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtediutzku.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtvvealzzc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtsgtmnihy.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtjmdusqyo.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtvnxezrqk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtcojmwpkm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtscleprxp.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtkgkrjptc.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtsoirmsnj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtegxkawti.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtcejfddwq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpmzzdhy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtkxkovote.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkwwctdry.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtkhmsvzqf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkyvcwtwz.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtkjdfllcr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtargqddoi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtigfzzpkr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtoxnhjdrs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtuusqhxhp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gteiaeqplu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtqdfkktbq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtvsmpfbfo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtwluswpbk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtwcpecqaa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gttbcrxwgc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsvxottb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtpgutikxx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtsinfaxnz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtenmqvlfz.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtztxhsvik.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtmjkddavv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtcmbibryi.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtfrcmenvm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gtqchrvlmg.html


<!-- 参考信息 -->