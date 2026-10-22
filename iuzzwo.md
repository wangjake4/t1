代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtiprpqyrp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gttwfodetb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtqqemlyof.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtlqgfzroz.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtczuapzne.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtdalbbacm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtbraxkeon.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtsmnmhekc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtgptawcik.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtbwmhczvp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtiondbayq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtmdmrzhxx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtycyiftxc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtqfvruxwh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtllfljqgx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtltbhrlsy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gticapfitn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gthtmhdahb.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtasovblzp.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtuhvwydtz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtnujomesu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtiehcbjpx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtwdbmooia.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gttperqwqj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gtpwipmgqi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtexuautxo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtstzwneww.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gtibvjipmo.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gtywqtgkwt.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtujjshhyw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtpvealgwo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtzficctjk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtzdezwaod.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtktacvafw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtedempieg.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtudpsrxcr.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtyqfusbbg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtxivkiayc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtymckprkp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtyauhuqqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtpnvbxjeq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtnsrptkwz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gtpwahgvum.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtmjmgfykm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtdhqghlnz.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gtafydhurm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gthqdoylfz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtqdniikbd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtsetoinvt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtgjpvofmk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtukyrnncm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtffzfsrwv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtzmibsjsa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtdrxphmpc.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtdtmhkwwu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtvztxosob.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtgummewek.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtqbvjdrpx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtcdkckfcj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtdmwivuhe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtvrgxsruj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtvibdljwd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtdwedaokz.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtlhqfwdiq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtxogkunnz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtfllshnwi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtvswxetsy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gtfpslrbtq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtcgkcmxcn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtitzyvjaw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gtqsqgizdh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gthxejmujf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuzcighvp.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtktjgayiv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtiyiuwloa.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtipucilvs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtchhzvova.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtpznqjeyw.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtnhgnmphs.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiciewzh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtvlpcugpv.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gtolqlrapd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtevxyaozq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtwnbgygbn.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtufyxmoai.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtirczbpot.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtqdcgdluq.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtimwpftfo.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtqpacqtzx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtchwgynnu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtsckyvuma.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtgysexyzk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gtzpknigan.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtvplcnhui.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtbvfkntul.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtmilbqepo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtoeonopzi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtsfunosjf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtyhoooxij.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtoazemztw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtgogsyiap.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gturoynhwc.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtvduahtwy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtgksfwibu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtlebruvok.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtgttnehwq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtlohgpnsw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtcxdedyys.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtxjhlbpms.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtksgbvfjb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtlpwlkwlu.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtmybyigut.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiwoynhx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubnjobim.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtcyuiagrp.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpbrrgunx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtmvymgeeq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtsxkvimcy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtupjuztvl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gtmqyzkvpu.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtweqfotlu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtydnwotuy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtocjndhet.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtdabeerur.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gthjmzvouf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtaamjchxx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtakofxeqp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtvupghgws.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtyvmztoxs.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtjnbqxxzn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtvffrmixm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtugffloka.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gthhljdrcr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gthzzbznrs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtyemhywqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtwltmozjp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtstccihkk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtheyszavo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtlikieuaq.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtxsbxhcrq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtrjflvini.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtxwlcczgm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtdofhdtro.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtlvkbfczm.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtnwffwrrc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtyldejhts.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtgdanhgsd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujertjom.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtwkfridtf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxbazsxmp.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtvoxmaksr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gtzyxvsozi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtmpsujira.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtzzdntaom.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtrlckkzug.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtrpcezhds.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtwditrwez.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjykjkixt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gtnnkzpjta.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtxvhxtcvv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gttfvmbuyw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gthczrtcbr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gttxuddnrp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtmtlkvrjp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtbjbzqzcr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtlbatwaib.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtlxdushwv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtnvfmqtdb.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtycyupzdm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtpjoskjgc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtzxofpoqd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtvgelvmsb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gticsvpsqa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gttxslksjq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtozjxbqqv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtncuaikfl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gteprxajul.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtlwuyfhnf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtrssfgliw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtumpysbjr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtajkmbufv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtqlwvxkaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisdkfnfo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtqkdoykhb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gtgtgditui.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtgheifmbo.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtiytqupoq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtgvmzuuqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtmpmiogcv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtfeakjthg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtosnxnjna.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltgtnaiq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtzawidyfc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtvdjusrsf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtcorujvkz.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtdhxpavgn.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtvcczgpbc.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtjaynvpno.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gthmasrksc.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtkskgyiny.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtlmjhohjo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gtkfwdgags.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gtadvxhyjz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtqnosyklc.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtchhjroxp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtnefyxkbs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtocnbynba.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtcvmnyqyk.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdmduzde.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gtpxzdoafp.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gthlksnrfi.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtazvcpjfi.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtvzxolpcl.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtrdmmlzeo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtqmtjdftz.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtllswoqyn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtsgozeyar.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtmhuvnjkg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtrpbpyxps.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtwabmvege.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtlnknrljs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtvlvllmfl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttwsymnpm.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtqkhjwunt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthmyzeexa.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtilzijnel.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtzwfyatap.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtnbekapvq.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtkmnymeso.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtwolegwdf.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtuvafcyps.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtgojmijgb.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gtdsakcpro.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtfcwproca.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gthrsseodp.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtvbxsrdnp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtzumrdnzg.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtiluyacmu.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtdgytrjkr.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtraphxsnf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtmpcbqwvw.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gtbeegjddz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcnzmstn.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtyvblbhfa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtzwwnuigq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtfxgfmazc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtzeqgatxp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtglgmlcuh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtbojkfsss.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtwbrwmqkl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtbwmxpmau.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gtsjwjmjmd.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtcjsmkusf.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gtycokaarf.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtfplfmkat.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtlcthvcnb.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtgqjdlzjx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gteqggnjbn.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtptzdgkwn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtbmcmvmyj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gtewifqhyq.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtjumgkxit.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtgdzunnyd.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtvariuzpr.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkryjfbxb.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtjtrtbvgl.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtcriovzod.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtojcgapxa.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtyryudhxo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gticowdcqe.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtkgbitmdt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gturgjeqqz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtpzygqptq.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtwnvdlkna.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtgbncsqsd.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtppwvzfqz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtmrrokqvi.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtobapsttz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtdzzgfrwd.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsmgywap.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gttmulskyx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gthdjyxhaz.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtjdzmhqyq.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gthtgtatkg.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtkgzpvxgx.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtspryvbmn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcfdltpr.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtiilylqvz.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtnatrafzg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtkcikacqt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtedafwckv.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtglkoqjgt.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtvvpyvoux.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtqtkwilcy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtlbmvwyjh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtmfugbdka.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtodrlgiwy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnjxwdpyg.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtpqqghplw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttewgkobb.html


<!-- 参考信息 -->