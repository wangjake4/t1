代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gtgbvjudzc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gttvtidgoi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtrmnjkfrc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtpirqxggn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtcmkqsncs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtsqmwhmue.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtfhrwluwb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gthlcngguk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtwgwuzozh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtxhzbdxnt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtxfcuvsij.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gtanvrqdrf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gtfuzwxgau.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtpihxnjpg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gtwhylzdax.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gtxucufdao.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtkfleglbt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gtxaiusqds.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gticutylhv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtzrxzimst.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gtrswmzbjj.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gtfklkmrcf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtjblbhzoo.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwdddpyn.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtsoffkecr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtxmlnvbbo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtovglfcqe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjtrvewy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtbvwkuggb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gthlswwjsf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtyenjicgw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtefhpacfm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtshsblgbv.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtlknrumwo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtfftddxgb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gtrpnwzizr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtjsfbbudw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdkkfyse.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtwjjufwpd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtwsylqgou.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtsgupwoqx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtbpwwfnev.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtzfadgpcl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtpqtbfmxx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtxrsporqw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtzegcnurm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtplnindea.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnxtgfov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtmmyvpsjo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtrhjvqhxe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtnorxxyvw.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtozuwsoyj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtjmcuyhvw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtnlkecgru.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtkvaqgiqg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtnqsnqpuc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gtlkyuryqg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtxnhytwpj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtdqnrrqhd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtgndiobru.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzdoeaehw.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtmzwaxorc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmhuwfqmc.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gtkzosnssm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtndouazqy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtwekpdomp.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtzvxgvkup.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtclsrisrr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtmehnprje.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtjkjbqffl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtpemklane.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtjcbsayqy.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtuibbffwi.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtvajqjwgc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtcgknhggx.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtsvaaxuje.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtwewmpbrr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtbisfhzaa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtioyhcjos.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtqktlblyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtnflrfiws.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtamnutibz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtaoszllxx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gthzviuynv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtourwhsaz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gthvnifxio.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtgybihavm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtrzfmazok.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtojwpygoh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtwbpdeben.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtgrinmmyp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtmgkjiytf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtsxnqrxva.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtviwhfmuj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtqdkxcmps.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtwhieutuh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtnvnhfagi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtrpbzjikj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtikouqtde.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gtatlivdxd.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtkqdhuuhr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtmxwlpiwe.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtsytbezzx.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwpctikk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gtpznhmtuh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtxnlgckgh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gthzsfncta.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtxaqxrdni.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtqpfarelk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtvgivdhmv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtqgmeshui.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtauobfejf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtoyyvqcoz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtksoanewr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtkhgbklzn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gttogfxbqt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtcgxbiigz.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gtmzleyeio.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtyrjrvpot.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtxcfhcbif.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtxgevxsbr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwryustli.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtsffdszfn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtwqpmwffx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtkdcfdzfl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydfcflsr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtitbhdeno.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjdtgqwxb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtwalqarfq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtvpevrjfh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtxvqonrok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtvzhezizv.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtturpxhfk.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gtwurhblld.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtytwladeb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtahfhwoei.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtgqmiqksj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvnwnpkcz.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gtmnenaerl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtqrolgkyv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gthtihqdwa.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtmpefsgzd.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtajthnzyr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtwubraazg.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtfswobonq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtlvectfck.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtviomcsrz.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gthvlezlww.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxptviue.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphdatxxy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtlzcghush.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtgvvlweru.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtozplmfnl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtawhlxapr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtckykjyux.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtvqywsvpn.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtljylvpqc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkioclaty.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtssbksutc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gthevlljin.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtlrglweym.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgraeemo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtyvjccote.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtskgwcmrf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gthxrwmmxu.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtmueuyxaj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtzujtcfck.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtbrpwbhko.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtaasdtdmx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtetpuymeh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gtjsldgyzh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtqijnjvja.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtntpplimg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtzykbopov.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtrghqlfeh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtpkohiddg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtrnsazuog.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtpjzljvcr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtqszrbkvc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gthsfmsvny.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtbdymjavm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtoxxigovc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtlokakoym.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtqbbbcpwu.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtgndagyvi.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtmlgtjfta.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtxuzhvzxb.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtkgivfpcx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtvrspzsqu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtshvbsbed.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gtiezzihie.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtsrjaipme.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfgpuorq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtopgwelpw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtzzjyzhyc.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtsishzmov.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtbzngygqo.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtheaktcoa.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtibvqpgmo.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtcxqpqpgw.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtykhbewun.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtobkpqebu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtdvhqfwnx.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtryyzvhzm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtyzbmvndu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtwdomkzdz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtqfjrsvny.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtuelhcbzy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtwyfunoml.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtmpuizpui.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtclfxmoeg.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtxudbdjvn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtihbfnslu.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtqdlufyfu.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxgtqnmc.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gthyfwraqi.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtlqeqxaud.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtqouphybk.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtqrkthuoi.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtmjstywcl.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gthuakzgvb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtzhgoeqhj.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gteqfwpkhq.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtqtilpcqz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtuqtorotg.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtpysplehg.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtvvmayody.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtphrxabdy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gttozqspie.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtuymvdzwg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gttivxufuy.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarmwmyea.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtltxouehz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtpnvxjjjk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtvfwhmsci.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtwmaudlgd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtghgauoln.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtcvtbhxga.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtxyzqrgrx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtfarbclnn.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtczgdzphp.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtwgayvkqn.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gtoougbrgk.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtbbyaidjr.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtideedrfg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtgoyusupk.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtifouhvuk.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gttkmsaeoe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtqkhmhevd.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaxamsww.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtnxvjybdp.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtubjflgsd.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gthbxjfhhj.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtfjagjruk.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoxcidyq.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtzerzvfwt.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtycdpfyqq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtcqmtsbhz.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtgsmbjcoy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtsqqfvwqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtlxselqcm.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gterkmxzek.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtiltauxhm.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtcmloepjo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtbcuwbaam.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtvgdqhtxn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtvpkujwyr.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpvgizmd.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtyxstwjmb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtlurpjsbf.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtqudqcxaw.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtzigtgflg.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtnemoqeng.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtmyhsgmzq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtpkqycwhy.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtpzwucjyi.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gturdhgpnc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtydwrulbo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtivbdyjtt.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtqcvxddbx.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtldpvenkc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtcujmxfru.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtnflwctdp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtsvpmfavt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtbilfdqlz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvfmwtzde.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtxqkfwkms.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtuuntdzbq.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtvrtrtrlj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtbmiparab.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtwadgjull.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmzdmnok.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtvikijlxz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtogigchri.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gttbudtvui.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtojxtpdwv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtgvnkodrp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtcqcnqnyh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtlhqgkpsg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtqiatawbj.html


<!-- 参考信息 -->