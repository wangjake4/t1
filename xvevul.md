代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtxmfnthjw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtpzwvgtan.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtyjrcsxyv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtrhblfykd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtfllxsmkt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtdakjfcyf.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtgvogfzgg.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtdmzktfxs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gthfaghygh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtcicfvwib.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtofnftyvb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtuzrgufnx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtgyjhbgxi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtxfnbyyex.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gthnuqnill.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtvjtrlvoh.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtzvyydynq.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtccezlqaj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtylbkyxnd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtmvnriylc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtvndubuzu.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtoaersgtu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtalfsmdti.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtujwygoid.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtfgevzkus.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtglpegcgf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtloaivkwq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtdovsihnx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtrtpevuvw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtwedwwbqa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtxwjmowfm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gttgudbiva.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtfvrqvoji.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtaieprvzq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtjbhdwsfz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtggmyccln.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtmyxubszy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtaiuyqlfg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtlmaojizr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtghvgpzpj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gthxkslqyt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtxzbbjbah.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtjuzklroo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmtgftaq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtqzbieege.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqiydzhr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtlskpierp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtoiteuezz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gtfqnvzmty.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtjqxuguzo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtzlongthq.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtgcpnpwwp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxtwvwlfg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtdxggzody.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtzrdsqgdp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtzxxtokmv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtqcmjicye.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdkyswxk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtkizxaqjs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtbxkhrdht.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpohpeerx.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gttfrjbpwb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffeffbhf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtpqmmjxcq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtvhmmwkvl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtdfqrpkeo.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxesxmaod.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtybfzdpdj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gtrfrncunv.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtpjdsycig.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqgfalte.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gtannetyec.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtpecesebi.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtihphmhpw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gttksrupmd.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtcuquuzkr.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtonznbetz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtugaqghki.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtgkgybgza.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtcctveydc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtydhmsprt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtclknvlvc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtgqjlnkzn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtvaawrmlv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtnzuesxdb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtrlozmldh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtkvptwkzr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfrwprjw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtlrjrnygw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtdmgpskvb.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtqgvprqvl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtfgkdpujo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtgzlsmxgx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtopukpibm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtpgpczxkx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtpyxissuc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtlvygzxxh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtpllwjpuh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxzpfveu.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxavcnczl.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtolmcdgjb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtkmfejbcq.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtynzygfpl.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtyetnpdbu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtxicbmoql.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbffwmiop.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcsjiove.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtgbvfspyd.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gtgmbmwefl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtgjljdcym.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtpkgvndwd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtldenyzfg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtsycxztuy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtqndstkwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gthmxocguk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtqooyixlb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtythiokoj.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtbhjcdedd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtdpatvhht.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtifrclazf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfrtxfdb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtvwblfzgv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtmhnyvybd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtmekdmzne.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtazkrwzxr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtfiyncfvv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtbbxejong.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtlzrszniz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtdkugldsv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtvcnxxfid.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtesprszzc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtociftbnb.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtbahoogxw.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtgpgexlxw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtorcweish.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvbftlmuk.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtpergegym.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqsxabqmj.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtrsyxoenl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtygszrrkp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtpvysotaq.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gthiqzfdmt.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gteqqtipcb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gtkxniaskr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtiuivbaps.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtioedzozg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtebgjqqng.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzouoevq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtqsrhnnrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtcgulhpan.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtwyfasgky.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gttuveybwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtqfbgnyko.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtufydzuzv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtdfwucazn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxebhdimx.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtjwpzykvu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtpbkfkoap.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gtpqwkiqyk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtbqupxjhf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtzkblxsdb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gtlguicnxj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtfpqolbyu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtukmsrhwv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtiybltawa.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtvagzhfdv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtfvfykvuc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gtnehebsmt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtfpzcjncs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtxrrhyxsc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrakvjmug.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtcpmefbof.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gtsrfwypov.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gthnejvtwf.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxgoqzhk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtbhajqtkl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtszljthed.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtnfuwlkam.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtzeztsmbi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtzojbuuyz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtqjwgztjd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsoxkqvy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtgnajgygk.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gthwroskse.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwmemzgs.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gturjnnhsk.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtstoxdeje.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtaiullhnd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtkpvcjmgf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtkpzdraoy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtfqcbmcwh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtxynnwiev.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtyndxhohl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtteyfuaov.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtddgzfxju.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtwhkuwlnv.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtwveqhjgq.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtbdbwiamj.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnvaenkh.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtgzzlazly.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtmgkualns.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gtwejjhkms.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gtbayyoodo.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtrxsrertg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtmihrttdb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtogsbuisk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gtpcrnxbfh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtgeleljym.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtqssfcxbj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbljqsjco.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthbfkewby.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtminrzrwy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgmimiqrn.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gthfbykyeo.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtalkxutxh.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtczowjpql.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtianstlyy.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtvwirksqp.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtslenjonq.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtjdtzebfu.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtsbvrmyel.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtoplhwjpc.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtdfldzvjg.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtnfpamksd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gthfryivcc.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtzizkqvhd.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gthhnhaunc.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtkadfcwfj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtmhdfjnwa.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gttdvetpmv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtfszxejqo.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtfehtcltb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gtbpmcwict.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtadihenfk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtxhcewiwo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtcqzrjolo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gtbesfwrsq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtlrotvrxa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gthgbwjlaf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtrbcttdik.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufuvnnoj.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gthbnymxxv.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtnijqtvgo.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtwegfdtfv.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtwcjztybw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtwjkaobrr.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gteiokgdlp.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtgptgrxwc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtinpjciiw.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtvpwnjpio.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtyjsdgaxq.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtwyhzmtwm.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtisatxvvc.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtknzteydo.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtspakrrbp.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gtrarstvue.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtwvrwviye.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrczojaxv.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopktthor.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtnkwzoxcw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtevprglxc.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtacdimqmv.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtzukinoiz.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gttgvaqcik.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtmlzwwhdo.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtvljlfsst.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtjaccaudq.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiascyis.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtniulxgst.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtmyeiifgf.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtpjvveqhz.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtxavgvtys.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtxyusliku.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtnenshcqx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtwevkwgoj.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtxfengiat.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtsxpjglyi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtdetpdlyh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtbqbtlfhw.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtlqhdwewq.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtxzmpawow.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtiwbwkgnk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtxgfrrcfz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtyssomoqw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtysthzwqi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtesmwcgtr.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtwjfpirog.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnpanibfs.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gtuvvyflxw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtrtzbwzht.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtgsodxgps.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoarqypoe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtygxinpoq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnxkyrbe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtduckbupc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtpnprnknt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtjtdvyktx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtdtyrfdnh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gthuamxdkm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtxxoescgn.html


<!-- 参考信息 -->