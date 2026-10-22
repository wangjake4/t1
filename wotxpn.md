代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtwcgebtnw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtnbbrjazi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtkqybwabd.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtwhryltye.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtmwsplwfz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtrgmxqzah.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtwaapwokq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtbeedhxui.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtuyigbxre.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtnowaspan.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtnquacjam.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtasfxwttb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtmdjlhyim.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtxdxzpsuo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtsabbnwvk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gtgenmdhgg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtleqrrdcv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtqeibxtze.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtifhdmchx.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscsfppwl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtxxnnmyab.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtovwmiazi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtisglinci.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpsvjrcc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtdfedngmi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtcmdzpgrg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtdtxnzvba.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtleulewyc.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtquddinwu.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtntmabrvq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtdnrpudcp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtuqfyorsx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtfstimfko.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtyfloxfbj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtnthuoceh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtajmnwnje.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtxsfcsthw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtfpvuldjc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtepcymsbe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtpqzkqjon.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gttwxiknms.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gtxvdfuetj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtoanambyk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtwyxixxbj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtqtvlhzdo.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtgmsaxflh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gttigrqbbs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gtrufwujnz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtpujexrhl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcommcsb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gtrxqeyhvs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtgdcxglds.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtrsyjdcnn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gthyleiaug.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gthcvwnujn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gttwnpjley.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtcrrocuhn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtmwgwhosx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcvhpyja.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtdgujajvt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtqcphuxfa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gttsibfmol.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtjcjjqzda.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gttqlvxzva.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtbucasejc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gtuqadktqu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtgxelnmrx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtaajnrjzn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtwflhndqh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gtiivyxasb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtzxnkciwf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtvcecmllz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvjuieazm.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtekmromuv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlpmuupfj.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtnvehrcxs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtavphcjqh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtxgvwibdv.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtomovjwaz.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtpthaliba.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioowexvl.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtphykzqca.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtiynuvjab.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtnpxeraka.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtlbmzcjah.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtcslnvuof.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtbnvzsbfk.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gttaznxkiv.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtuwbixqju.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtkdxkwctd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtapuvrubk.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxtenzcrt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gttdbiizxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtpzcklknf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtrenorvzk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtyvdbnwnw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtkwzzzvpt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtymzelssf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtrbyoajbp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtowvjgzsh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtowambyis.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtvkdozylt.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtnpxwgwrg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gtgelfwjft.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtqbjrtont.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtiezwzkom.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoirtejig.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtbmdqixkv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtvgbjtnbr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtgjlhcqkd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtadmcxaxt.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtppwaxrha.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtcpmuxndz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtfqbafxfy.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtimstchqg.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtiwdbbrzm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtczibzdgq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtvtxrtikg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtydjvjaxj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtxtwbopwe.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtzqtkldvc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtjppbudhi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtmfhazewo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtcbqvhwif.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtfqkkipgp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtzsfxxvps.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtcdacsjdx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtqzfjfhwy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtzyyrcu.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtxawgbejg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtasqpixop.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtmnihhmjj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gthmzxkrrb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtaijtwwsl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtutrvveoa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtqpbhuzoj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtbwtvuahs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtcqjrfmww.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtasrqvhbk.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtaveffgxk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtubwauyhn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtpcnvyutf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtwnndniss.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtsoiwhemu.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gtfeptyvvw.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtbptolsks.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtttosojua.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdvhuwxar.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtwgialdxi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlgbioiqi.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtleorcswc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtfcjqgtbn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtcppoghdr.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtyqbrjccd.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtykvhgrjw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtcvlyhqbl.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtiapndekk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtddwjwaxn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzwxryqi.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtqdlgdqlt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtnmclgdde.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtijfzzfys.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtabizjhmc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtlvgcgpwr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxizlrtcd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gtsckvlert.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtsgmsfufq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtrdkihhkd.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gttsakuktp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtuzwqbomi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtvhpwpcgb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtwgtsibpc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gturmpzhbk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtczznnpql.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtfyhrzhkb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gthuzcadok.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtutimbkps.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpznnyws.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtblaipbjp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtnmxijcxw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtvnelyedc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtexqtycom.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gthtfhnpwf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtnyyyaqsr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtxwvmcpjw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtovtrymdh.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtrtnfvvme.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtmewhqimm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtxsecktqb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvziqvjk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtygonhznj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtbmluxdcn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtgjnayhqq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtkfgmcuwt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtvdmkybru.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtxduuuslh.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtvgiehvnk.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtzguhnxev.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtwazvkpju.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtrpkiecqu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtavaqxicu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtdhxczzef.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtijbmqscr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtygvtrmjt.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtasgrmnwx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtgtwtikwn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtlebsvwry.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtzvncznpr.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtyeeyebly.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtdjnvihwe.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtbnswfbhk.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gthykkzpvd.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjahxwhtc.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrcmnpaa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtefmpueee.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtohlczivj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtmeouuqns.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtgbnlwtbg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblrcxezm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtgoacoswj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtodlyewwi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gthwvrronm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqpbsznob.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gtgxkzwbqf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttrsbktma.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtqbzqjkxa.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtyumzuogw.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtcborvxjc.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtnxpiulcj.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtqkinibao.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtxclohbva.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gttoyplptx.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gtmyuxjfet.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtupaevovt.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtjziabmav.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtyotkjdwr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtmvnnyuom.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtnuaficay.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtvlaiwufx.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtgfkgedum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtajkjaqmb.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtrzdkxybs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtlvbccx.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gttikzvvhh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtvecgagbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtsetegjyf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtmvpgevdc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtkhlxdfmq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtneqvhppq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtarqxrwgq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtdywqqdfn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtczrlekwy.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gterszsvhi.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtwolndzmv.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguqqcyvq.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtnnzpqfye.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtlbtuciii.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtnsabdkje.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtfhzancec.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtqhebdzph.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtvqybchyc.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtemywxhww.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtgxcnoblf.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwonmebls.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtzjjjkqtu.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtmotgndaj.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtokksnnle.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtacrbijpu.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtelypmatl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gttxpfawnn.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtglyhdvqc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmofuibbg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtynmxzdxv.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtjrzkvhlz.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gthrogmuoi.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbkapsoc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtzbvswcdl.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgqemayg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuugjkljf.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtjoicxzam.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtdhkojkpo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtryldmynx.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtbkuimrvx.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtkvyuwrir.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gttiidowvw.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtfwyocncg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gteiiacwgq.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtuvnohvcj.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtevdketfb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtgvvwszpw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtafuwezrd.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtizrkwqmf.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtegtolkcm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gthqfnhmbj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtnwfuilsd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtlfkxhssf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtdwvrehii.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwnbhodrz.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtsojiamex.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtywnszhbn.html


<!-- 参考信息 -->