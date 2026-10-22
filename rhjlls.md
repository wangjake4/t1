代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtivgxxwwm.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gthcecffrh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtaanteure.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtodwvidiv.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gthmljzccw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtjrixmelp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtjrfjsfup.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtsxmzsthv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtonwvyicl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtjjwgggsy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtupmyyjjl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtotvorvdh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtjutynpej.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtfspkoexi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gturigmnpx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtmvmmdywc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtnumvgert.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtvbgzxoqt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtsyrasyzg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtlpgyctbw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtchzanhuc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtwsjomzgy.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtgtliemla.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtenxjmmsn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtziwkuawl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtotbuguco.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtebkuealj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtpkpnsnhx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtrbumazzj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtzyulqwgu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtfymnblvw.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gtijgfbbei.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtiglrqygg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtkfvtlenm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gtzxfspufz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtxfmbbrec.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtyyzawcsx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtiqoozlho.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtkkfujlcc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtbybdfjei.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtapifhxpl.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtstwszsxt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwuwltwdl.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gtkuxjsvte.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtdqlcqeqm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtelucbsxd.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtplbfshul.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtribhtxdu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gtjotphcij.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjahngcq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtviesaxvk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbtieehth.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbarojcbq.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtsfxrletr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtcoshnrnf.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtuxlnxdhj.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtpephlkne.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtravckgna.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtdwwngjhd.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtlvymjpnn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtluyurkln.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtuorxsrir.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtokxsvrcq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtxsuszjmv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtbmyhtfxw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtflixzeqz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtebqwdgoy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtxvhtbsdk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtvgyiejqb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoupalulz.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtlcilgvsz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtmscokvsv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gttujxcckv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtpvoblgcn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtskhbislv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtziycqagi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtzgixhwwv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtagzpzsmf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtrsiakmnp.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtekmfeyyl.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gthtkamnje.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanpctasn.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtpifepghk.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcrsgfqcd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtiveogsbx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtdblrrssf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtjbfhvcjs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtbtcndhzr.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtnwvowasp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtsxtkozsq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtzdnorgas.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxczgjht.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtbnrclayx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtlcuvhmml.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtafwifjnk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtscazggdw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtuyywqokk.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtbshelbfz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtqyhuwnqv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtriggorri.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtleftopqc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtbyfzcnhb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtttbthgqh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gttqgliphd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjetnlbq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtevjxgrxw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gtnqjradfl.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gthtadfdir.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtiwtanbpb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtrhtwedsz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbypbiuaa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtzhjnumjn.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtprkebsix.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtakjhcwkg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtrffuhdfg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnhjoblqx.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtcgdzhdjz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzpvjtehs.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtlntjvycw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gtxwevawyj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtzrtynyyq.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwybnajb.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxdfhidy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gthwcrxjry.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtsmwzdzcl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtljgxwybj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtqqerpnjx.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gthkyzjewn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtcsvukqaj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtxvpsyaso.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtzzjwzchh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtkpdrxpls.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtcczjayin.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtamfbxggs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtdwulegar.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gtghudvpdb.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gthaqvmspe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtxnroetch.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtnownydlq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtzkjktoue.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtpnuzjbav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtmpbngkhy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtvqghppwf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gtdrgipvnd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtrpmqimqt.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuhhruqv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtnemnohob.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtjapsvpkf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtxzyvglaf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtwcgqsnoj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtsbnxputr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtrihizwoo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtekljvxtq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtqoodempn.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtgkabwgyo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtdypdennj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtfiowacid.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtzimvnkwu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtiwtqnlkw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtvjajpims.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtmwqcyzuq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtmdlsjmkz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gtcbivakwe.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtyuqcxgre.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gtyhfxbyjg.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gttpvgbfzv.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtaywvvylt.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtpxqthqsa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtdnwzitgp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtnhndsstg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gttbpayllw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtyqqxfjbv.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtxwarrmnv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtzpjkchnc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtgkjtnyzu.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtnkchjgje.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtgxswrglr.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtmapenapk.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrngxtye.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtjpemkklc.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtcdoopler.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtszuiakqo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtupcbcziy.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtddhjlfun.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtqqxrsxds.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtqvzmxjuf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtctekwzry.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtsawdbghj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtumrinfdw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtywwqhsjm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmapxoybt.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtlxcfbhjj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwtmkyztt.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtkcgmlxdu.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqcuylyi.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarfuzuys.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtxvmyorgd.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtetbnvcql.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtpvhghvbt.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtdlrwhmcz.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtfodgunkb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtncrmpahj.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtosxpybuf.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtaiwpyfsp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtmtvuuvgq.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtaednjvxp.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtauotafpk.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtdslgnlai.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdiqaoun.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtnxeczwxq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtcxulmsac.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtfwodqkou.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoeegwei.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtpuxwtdft.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutpbibbn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtqxzdbnxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtjajydduu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtgxuumccp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gtddjqkpuy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtvxdxvfit.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtsynvagei.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtudhzsmjs.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtxlbzgngv.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtvcxrhnwd.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtzdrtdjke.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtfjsloira.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtgphpfgbe.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtqoecdcyj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtbfegruzc.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtsifdzell.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtafidgfyd.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtvgertuxl.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtjcrnhpfd.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtommkbsrp.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtstshzqxv.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtagkjljkp.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtzkeyxlsh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtbfiammrb.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtbmimxlxs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtvjteggcu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtxrtsmcjm.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtgfgpityz.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtwipafeys.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtynoroogw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtwfvrjppg.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtgpjbompl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuuejmsj.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtltrubuov.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtoeompnxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtaejvyuit.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtyinewvsg.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtwkktzuvh.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtkzlmmbby.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtopsbxrat.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtusexqtrm.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtkztnxcbo.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gttyulhyeu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtzrtnwrfk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtwscsonof.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtiebkgzes.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gthghawzei.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gtjlqmebhk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gtcaxdswqq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtbcynpobt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtaxrfztkn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthzrbuwdk.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtimzuxmga.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtolizizxv.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gttfrvlycb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtrrspcuic.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtavniwmka.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtifcflkgn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtjhgoxdux.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtctxclmvw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtjofcffmq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtkthefman.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtkugclzlm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtsirqcyxs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtvqisbqot.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtxsfjbrul.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gttqkngtql.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtdbpnbmnb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtbwcxtquw.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtbyaudcxa.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtttobuffl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtdrpdrxas.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gtelnvdqyt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gthwhahssn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtippuiteq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gteihjajtw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtuzayyqip.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtounkxkix.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtscbaxbvj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtkcyahzcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtmkxxdsoc.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtlrtoocdz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtyqgetaxx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtgvbejpja.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtndouqcif.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtvmjjjtuy.html


<!-- 参考信息 -->