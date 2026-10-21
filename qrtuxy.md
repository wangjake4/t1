代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtbligjwkn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtuetrdwoi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtvkkdtgkf.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtthtnkabd.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbyxtidw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtujnxoaod.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtllzhkyfu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtgowrkpqs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtrpyxghmr.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtdvtcovpu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtaobqrbpr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmdgcdnd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtkzoeefpi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtjzmzmvxv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtnedowxkc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gttexqrslu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gttiayeztd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtsghhfebe.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtayzryybp.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtzdsouyba.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtkbttwxun.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtwvdiqjuy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtzylbhssw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gttytzdlgu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtbtsknnio.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohgmlvbu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gthjkcryni.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtrjmilvbt.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtgcaaxpxu.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtulqmtnja.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtwdmknigg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtamllnndj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtzgpkjtfg.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtoeelmltb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtgdvsfaej.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtmkjdblvl.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtmvkmnkav.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gteihyeylr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtaotecwcu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtxkecvngi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtbkbidvcj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhqmjckj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtnsptxctr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtjmkltubb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtrseefebh.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtmtszqtsn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtskfnofbo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtseawftqh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtgmzwzupx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtggmrihho.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtmvbxxktb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtnikcvbne.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtgvbljqez.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gttcatvrmy.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtzqpkddib.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtsyknebdw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtiinszpsb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtcauinbwo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtskjovbuu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gthsplimcw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtxuuqvdww.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtybhdzety.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtpfqzgczz.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtlmujwqry.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtiomlmdgw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtamnwnsau.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtksbvejlr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtgoybiuws.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtvxpxdhfc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gtaaokxbwt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gthcmmkzlr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtuzvtxosf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtenjdndwn.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgorpulf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpwfgqfnq.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtwwfoxcth.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtppiedman.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtpuxhmwaa.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtulpgfdkw.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtqysnnmnb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtpizyatqa.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtafsfgcsn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtpykubpjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtnplujizx.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtbttcqgrx.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtyqdoifxx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtsswdmmfq.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtdpxvkpxd.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtlobchytd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtnecebkxc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtaokxcnvy.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtjmgngvdv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtqhkpcheh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtaylbeazc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtyphrfhaa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtjixpocvb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtfpjcrsbt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcfctvzlb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtzwderdzp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtamoptnza.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtkzvwqtyn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gtnmjtxblz.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtlowdgwzg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtwvqlxgfe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtcokljgrc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtackhzilc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtdetmmrkp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtedzqdfxp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtwqeojppf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtjabjtmys.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gthxrruvky.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtkmkkisok.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoxwrnrd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaftopzcc.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtmqdwrdkv.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gttmpbxkhl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtqrpymvgk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtuejkepkc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtfcxqsvnm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtjrlnasqb.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtpnqdzzrp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtahxkgnav.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gtcinsxznn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdpglsch.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtemmxwmyf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtroqkkzvd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtepwpwlou.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtieanpxvl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhptgdhy.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtspoztsdq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtviotluym.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtcyoerdgs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtwraemaok.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtyffggyqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtudummikn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtaxlnywhy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtzfqhqdtl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtizjyrdfv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gthljduqwa.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gtczwtifxr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtyrabucre.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtzjywajuc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtdcbpzssr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtqvocwubf.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtpcurtpjb.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmvemylku.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtpfuqgnan.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtuyvrxcom.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gtrxdmdhhe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjlfrwpxo.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtqfpohfnq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtqkzofafu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtyjvedkup.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtbhylcjiv.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtivceokcy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gthdvxijnr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovqfcuos.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtqsmsxtbt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtuhhpvexc.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtctaxjril.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluqywodj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gteprdyqjz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtxhylpzjl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtkpkyispc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gthdxjrrdy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtxfnzfwnf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gtkdvncyld.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtyozcjgcn.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqedtjnxe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gterdkverx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtkdafcmnq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtkcvdsrut.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtideiwwie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtosaivvgf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtkmxfsetu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvirungz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtmtaclveb.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtxbdoemup.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtvuypiojp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gtjztzqmwa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqukptcj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtkvmzcupc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshusgyqp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtzybotgvy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtelswodka.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gthnvwjafe.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtdmhbkica.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtauhblkjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtbppfsybz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtarpdfziy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtyknsmspz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gttgvzxfve.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtqupclwna.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtnbyhntjp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtqshtojhg.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtyzbiujou.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gttqvpjcko.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gttphkkglb.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtbdbkmyis.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtgaitewmq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzdwyrpx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtqhudzixa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtqulptzyw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtlukxyvqt.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtuyrgmsuu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtkogkjqqe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtyhufnlmc.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvssxmtd.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtxmfrhpxp.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtxhftsdwt.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtvnrsttkh.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtftwnswwo.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtaoluwxml.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtnuxfzfta.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtzrnlutcx.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtxpefgusp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtfeuckkdv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtwpwhylsl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtkvcbtfpf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtlmasowki.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtwwtymfbz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtctbkvzbz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthpmlvlsj.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtynpmqnnv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoifgzaf.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtdgzgdwaz.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtexturhpg.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtxqkrhaqr.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtbvzpfnop.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtxouhgclh.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gttvcxofwu.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtpayujaah.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtphdwdpxg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtsrwhlyby.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtkynpicqk.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtfhknbzrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtglrwgfos.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjjbufhy.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtkpogvghn.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtlymtnwfa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtmxwybczu.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gttyleknlx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtxvxfpqtf.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gthwunsnxe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gthjgrcwun.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtgafptwgy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtheouliqq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtikqqzvwe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtfbzeouxn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtguqgaggg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gtjtidudbk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtyzyodaub.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtvwmcvgtr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtwtzxnpki.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtvrcuiswm.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjencsoak.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gthgbhdeyc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gtryivgtbh.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtvjptjiut.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtegbquwss.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtbkmdbigi.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtabwndzli.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtuljeoomu.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtlhpprxfr.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjmltptmq.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtojxkoune.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtmkxwflxv.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtluzwicca.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtvwyqpfnq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtbmucpnao.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtjpdaxfht.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtatlgbsjl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gtvftfkdme.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtjxvgwjea.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gthxnbvzfc.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtnihxvctv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtkeceozcv.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtworibmpc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtictmwimu.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtzenaxlzg.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtgfwvqtvr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtjegyvpwq.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtpzelezwu.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtwsbumtuk.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gthhbaowct.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtfrhfefhm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtwksuweit.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtgprkqfzl.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtwmpuxgrc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtdlfzwgyw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtzwzrfkrl.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnzxhkxo.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtfvquvhtt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gttrxtitcy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtujdeaurr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtrmrnfbiy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gtumiyqepa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsbtilzme.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtiqrqvkpc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwpbrlcsv.html


<!-- 参考信息 -->