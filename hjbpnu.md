代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpujrktcj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtnqfwdikz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtygbitjzy.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtylqgideg.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtacyjrbrb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtolamqfbf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtgwbxdzps.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtqujbhjgb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gteixubarg.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtrtpeienm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gteuayorlz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtfatbmppj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtouzewvut.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtjislfrzo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtxaubuahc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtzlgraooh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtuojsqnro.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gttjpdeuce.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtotjzacrb.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtsjfgeocg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtcebxmbgp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtjzjgxjqo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtvrecysdv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gttoxpanbm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gttjkdwasg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtxrtkwxew.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtdntselax.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gttetcyjbz.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtdyvbclvl.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gthpnuqcjy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtrzzpmnjt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gttvcdvmge.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtxapeqqrg.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gththuurzi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtjndkidss.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gtiwlxzluw.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtzkchcanw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtlckowdxq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtfyliokfw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtjdcungzm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gteaxqnjmk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtspyxtlbn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtdhqmjybj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtwgahueoc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtipxfralm.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsbetwou.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtcoiarbof.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtalcxgdpe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtkhusnmzc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtvxmqwsfp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gttznrgugc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtpvhvgzbl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtjuvnejri.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtpjxbbjbs.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsmaaoye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gtiwwyhpvk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtmfggrtux.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtryqancdg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtgtffsyho.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtfothjuaw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtigrlnsfn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtsijronhi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtljbnpkse.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gthzmsnszm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtmsxkveoj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gthokalmit.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteouqrhl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtstewjihv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtjgxsigvm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtldoxjbaf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtnpdsvkwq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtgvqnzsbr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzpbffasq.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtirfmazcj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxdpgzkfz.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtzcabnvix.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtonznqmwy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuehrpibf.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtryknjbiq.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtxqtcvvit.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtyguyugjr.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtyadvfici.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtruuoanpl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbkbnzyk.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtgsqmkilc.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtrgipafed.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtrpkjptbf.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiovipcux.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvsptdao.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtewuqyvko.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtxxqkipmz.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvzbclfxd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtletdzehw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtpzkyikbm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtkfejgspr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtbtmboyeq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtlxslncdh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtnrqzsbuc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gtzfczczvz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtqhjeahmi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gtwlprlmgu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtqlepjdox.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtecokgahl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtfbiflsfb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtkzygvshn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtiibykuld.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtvdwdlnze.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtjnrbeujp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsglbnvc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtoabgmcav.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtbqccjgyv.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtirihigyr.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbhlewtjh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtqtqfjipb.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtpflpjnlg.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtlkubstvb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtorvwbapg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjqitlwq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtbyeegqgx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtddxnnswl.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtipufrxol.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtxveatlpm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtukbfgfql.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtysgopvlt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtkjvfpedi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtzklipdcx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtdvqoeomz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtpgujpwyu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtgpyiqknp.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gtljctkbtr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtaqjfgvhq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtrgkzjupg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtpvhxddtd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtdcaszyvd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtulhnbxcj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtxxwqellx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtrkfyxxxo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtqtyqcguw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gtlhihnyqu.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmtriwnkg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gtybalwmgn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtkskfxjvq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtyitnrwrf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtoimgkfgm.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtixczsgae.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtejyfjwfn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtuidoqapf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrynuwku.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtuseizdua.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgjhauwbb.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtowkzsfcg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtdqwndieg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtpggkruje.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtuwnwlxgq.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtiemejapc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtgjeicozj.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtrllsgtes.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gtbuhiujnz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtbliihkpo.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtkwmtgjkl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gtfrlwapia.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtfjobuajr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtatndrxth.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtbjxehtql.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtflbzzxfy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaywlvct.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtlpjkwgjr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgsnlhkg.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtytjlfcxp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtxzxkvhbw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtmdfounid.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gthansemwl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtcgrbcggr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gthldwujma.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtcdnekozr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtyazmcpdq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtbnjghlpj.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gthdsomfzk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtiecraixk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtskawbgpt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtqdtgxnkj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtalfsijqh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtvdavujey.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtcarsxdpf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtvyglozyl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtfprwpddo.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtweyvekrr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtmgbsgsak.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gtukioctsj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtrsncepur.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtvlymadsx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtldkrycix.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtpwmmlnjs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtkuohgglw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtyxjxukmi.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtqanuutqn.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtcsmnrdjh.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvfdhekd.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtallfspna.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gthuvewqac.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtfllxauwf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtorzjoscs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtevgxygcn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gthjttzxuf.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtssjkkfro.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtucdlocmx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtgplwlnhr.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtfxhknuio.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtynkymrfr.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtxynagirp.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gttenzfzfw.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gttqxpsyiy.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtpxdikodu.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtbglldvzx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtupzzztou.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtjgeerimf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtsoheqhnl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtbfhmkbru.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtnrjtwddi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtdprqiaal.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtnyxnbgjc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtmjbtdedn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtedrxigfl.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtqzwaeblq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgfkepxri.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtvgeidojp.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gthhoitwza.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtiyxzsdam.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtzwddwnlp.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtcxspjlni.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtpwoftnxn.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gttbpfqvpz.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtsmwtjlch.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtqrhpisjm.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtivrwbrwv.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqxguoka.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtebiumoxr.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtmirqyonu.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtbnenrbhi.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtqoqrnjtd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtngfsyfmo.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gtwavpxyaw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtfbpousne.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtzkbgabgo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtchwjjyid.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtygsmxlkd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtbdduvqno.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtryieeltt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gthpmlrgbo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gteecyjlln.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtyqqnowul.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtfkzboguh.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtikjziovh.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtsujmosec.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpsbvlxe.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtxsceamxh.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtqcbgdvlv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtzqktqlds.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gthiwkcuxr.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtsxvsudem.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gttjilthlf.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtidmggcrw.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtkseyanwa.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gttscypdxt.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gthnxpqewf.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtetatvjrx.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtdpbmwdwt.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtcqsobrvr.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtcdvvpqet.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gteslmbust.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtaqoxybsp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtsfwusjgi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtarhkhdxb.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtkvmhgtez.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtpbsrzpij.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtrrkjqrsq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtbqwkztrs.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtcwmccwit.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtgeuxarxs.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtisgttklb.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtrskcuoot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtotaahlji.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtiebebzuv.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtxxdaznkl.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtxfeylpky.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtupmdsphm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpojxjjpe.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtxnikdyxr.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtsjowzwsj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtbeyyyudk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtwfxcyllz.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtebguywgx.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtaumbrptu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtxmmgqsma.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gthokivblu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gtgxbyiyvs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtwjhzqixe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyciiytir.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtlqvorblj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttfrjxovi.html


<!-- 参考信息 -->