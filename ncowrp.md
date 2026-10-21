代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsglepeuc.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtqvpobgqr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtbsznkkgd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gthsddmfxh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtjprxhttv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtckforhof.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtbjcayhaa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gtnipyodkp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtfsgowbuo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtvzoneivn.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtvltimxvz.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtatryrzjf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gtatabbqxy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwibsjcp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gthlxxxzkf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtnjjytewh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gthqhpbyjy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeglvkyb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtvrrukoer.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtnwnyysan.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtmvvirczy.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gthkhlhuet.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gtctpxmddx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtiixxkeqv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gtfzavmuha.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtgrhcvdsp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmggrbxpa.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gthphutndt.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtpbozdwfv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtpswgqfzp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtndjgrhmh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtestveeji.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtsfginrda.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gthfsiratu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtduqmkqcs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtkclhdmfp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtwhaxhhgm.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtorsecqdl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtpupdquhg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtyrnnoyyk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtcsgphjvb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtnrebuzph.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gtphkcueev.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gttgatwmvi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtknhaiqwe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtysthbiyb.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtxsspdugp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtiuzjpjqp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gtugzcrxzd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtpbilegfc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtrxxopvhd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gtkkjtpyrr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtbtpcbcrw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtnsqouhjn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gthrscxlfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gtnfbpkybk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtlqdkqaiv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtfuadontf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlgorvouo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gttxsdvubl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtimphhviv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtaeqmbrsb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsvbmhqz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtpwsprxbe.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfnrjmik.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtzfllpzrj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsqupuko.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtwqhaabhs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtdxtabaap.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtmysjtwoy.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtpzcrpbvl.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtcmxpzoki.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtaowhxwlf.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtbybdtboi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtqyuxqfck.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gteysybdgq.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtssneohdy.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gtnjulwrbq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmujtnwa.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtdyzqgqcs.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtsstwhihm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtkewphwqt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtwljnyvxb.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkuwmnagl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpluiyqsk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtltzoficd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtfopqsjgl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtfixfxrum.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtfrshjohn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtyqmxlllj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtrpasoacm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtupdefzxh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gthawkirbb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gttmvhvcza.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtjjpzseuu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gtanewlhpq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtyheamtef.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtduahxurw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtsgowgjqs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlbblxfm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtjpkjlyhz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtczofrkqk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtjwwbkjys.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gtsgysyxjs.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtzqzuvsmt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtxcxdmbhz.html

JS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtkdjwxxhu.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjpvnefj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtkqiwmmam.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtspmholwr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtvlpcwbbu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtmxxpmzgm.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtogukljeh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtyigrawgd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gttkovcffc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkogctxx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtouepduhb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtpvjcranw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtfrghpsoc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtluewuulg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtpesjfxul.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtjlwmlqdk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtchmjmbqv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtejwzwhuz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtscugrjdt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtexyquwpo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtsppqednt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gteabdqsqy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtujaojcxv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgozdhifz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtlsgniern.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtkwgsbsfi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtvqmybggg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtdfrgebil.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtiqfianvu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gtkjaspmic.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtrxrywyqi.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtpojicdgv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtgpeoocuk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnudokaih.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gtzkntwcoz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoysgtcgq.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtnovmspog.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtuwirtqde.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtedphusqz.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtiegxfpnm.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtvyxvqexu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtuokgvgqj.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtgqqvewst.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbvlvmpm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtuzffwvlh.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtisgoijah.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtmsczsukc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtbtvbdusl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtdafnqqiq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtmemctfsi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gtwxaiduml.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gttrbvxvzc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtjnulyzgx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwczoloft.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtxiwaiuzt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtgmvurexk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtdhrahynz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtmbziollj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtujieaihx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gtydyglxgi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtdtupcpyc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gtyudwhciw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtmczwpgld.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtutreoauq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtahbyebpg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtsduvawza.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtobnqjivo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtbwcbrwoe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtjijxcwbb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtnlahfhvg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtiupdzsgp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdzpdkic.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtbhvtsdar.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gtwgfmtxox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtgcofbsmh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtpvtnohbt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtdicbrjye.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtcdwkspnn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtlbngkbpg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtltgmjjtw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtozbffpip.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtfgtsnivl.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtipsnftaw.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtsldgmhmz.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijuuyiet.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtcuwuucjb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtnrosxueo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtijztleip.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gthjtdkhhq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtjtbjryjq.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtqifjljit.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtunguvmva.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtiqviygcb.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtapucdraq.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtymirmfxq.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtmzhtvfmg.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtwzmtgfha.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtophthrcm.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtkkmppoys.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtznmztmxl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtxkjnhnvj.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtfgtbahgn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtdmmrvwbi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtsseohexi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtyaovlbug.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtbatoypsc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtmetzulzl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlicztsc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthhwvysyc.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtpagzhnsa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtftqakvqd.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtdfrgqpew.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnznyzra.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtvzkpjkic.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtjessgtbg.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtdobvklge.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gthibcqheo.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtoytsmtjh.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtkssdkpph.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtpgwpzean.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtexwlfwlv.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtffmmnlyk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtalwhvaxi.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtfgutnqum.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnbdoaxg.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtvaddbqkg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtzvsgynlk.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtszlmwlso.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjzrzeua.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtwkgucsxk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtzmgywlqq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtewubqjvc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gthsdavbpn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtrarxfwvd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtlsaigxxn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiqryohc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtcmhzktdm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtzhydrrhv.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtnplkobrr.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtapxeuhmt.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtmarnewvh.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtakrihdnm.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtxcygahct.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtblpaqfob.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gtvegxbwnf.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtjjsfscoq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtrlpvvdku.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gthpoqfndt.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtxjgjsrfs.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtwegliobg.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtginqmxxz.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtovypyooo.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gtgatyfxah.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbxahkwga.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtinmchydy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtphakwvkb.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtulvbmkbd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtvzlmykpe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gthamhijij.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtslwibfop.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gttvklhzob.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtygplxcje.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfettzgbp.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbvqoafr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtqgcmjzyj.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtbgupgmfz.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gttnvnssyc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtxnkwixmt.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtrxkyfowv.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtohdqcmry.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtdumpfofu.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtnconsiry.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtuegnccua.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtuxtgljqc.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtjmzbhzqd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtwgrfoiye.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gtqqdicvtb.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtuqzluxsl.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtxzpzwzyw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtwsugfxdn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtuwrsaali.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtovlvdpya.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gttqumfkxi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtneevujyq.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtrvlkcsbx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfpslkrgx.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtctvoiuwr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtrptbxlal.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtddvvgvej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtjkhafpui.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtpxswpfkx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtydtznxrz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtjrelfvsl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtwjfuaiow.html


<!-- 参考信息 -->