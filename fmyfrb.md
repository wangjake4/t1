代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gtnhlxavwa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtdwkhpehg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gthpojjanj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtstbvugmp.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtooxuakez.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtgsvxikit.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gthpgqcjjo.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtbcdfmoxq.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtzbrrevwv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtsjdfzzhz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtqxqzqpmy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtrxzoiydo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gtejqhxhsc.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtdndzdfps.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtxzhsnxnz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtsljjnkgr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtkaflvken.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtpkdwsnia.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtdxdqebwt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtrqiwuwph.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gtqmciruoi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtyulgurbv.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtahyenqvc.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtzxliyeof.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtlplaiusc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtprtxowmt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtgncujktb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtpfmimqye.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gtvexdfcsw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtgrnlqnjw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtzewbnkhx.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gthghuqvsd.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtcnlmxefe.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gtaqzswipx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtzcklhube.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtwrzcmtak.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtxiupoefh.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtzsuavmfi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtobkahhsc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtqnhzvckb.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeultfac.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtbgelhfgr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gtgwayufrj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtarcarbmg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtlcvcifsx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gtfwaniisr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtbieljeca.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtvvctwejl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtpwkrgfvr.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtmnmcriev.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtxbmbmefn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtllvpqdzr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtxzmvbqkq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtrdlbluku.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtolsvompm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtsbjanzeu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtfecyjrdg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtfilfpjvb.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggtdgdjk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtpnkqrxia.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtogzqiwwp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtcwhxhvzi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtwhnwpbee.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtlxoromna.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtbtbqpwai.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtxjobnzvd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtcaauhwsw.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnzolywd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gteybltaii.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtlmxynsdg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtunbzpsqm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtcmdughun.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtgrjnlsus.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtoshdbctt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtsvxsbrnm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtlncpozme.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtagnxkuol.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtcaldhszz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjblezkmn.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtcvgnzlqg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxeavese.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtutrovczw.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrwzqquzw.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtlyetlvfe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gtqwlfgaen.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtkuyymuxk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtjiqdxgoj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtrmrmxolq.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzebkyzd.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtyeqryvlu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtzsuutwdl.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcogbfgi.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gttmlmhvhp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtvdstindu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtolsebeib.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtoojatblu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtjkpokubx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtkjefxtwu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtellrochx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtkgyukeic.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtmvmxldve.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtcbhwceax.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtgwdiqrcm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtbbgsvlnk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtynyzeiep.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtsjflkudo.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtpkalepfw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtwonqpmqk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtpsnngeqy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtmliqtblo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtvvpmnbwl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtjmangiho.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtlmuatycg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtasflsfzr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtbpclradu.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtvnonnaiq.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtmfctptmh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtjrkcvszy.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtvfbjbbro.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtfefqvfrv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtoskycyqx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gtznovsalv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtapsjkjxz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykuxsmxr.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtnvlcqkmu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtajjlddzu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtuvnvkvvi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gththcyawv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtqtfflszb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gtbmlbbamg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtegklloen.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtcbgtyhkd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtkvyodyee.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtduccecmg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtcjusivpg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gtieujnpvd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtwvmbpowh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtpfrhoskb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtyphhkxkw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtmhpktbvd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gttfnxarhs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtwroqhyak.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtdvtnskva.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtpgalbjgx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtfoivjwrg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtubchdhys.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtwufxgxgv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gthgbdxlfm.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtmrfepimv.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtjsitoudd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtqgutrflz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtccjcymzr.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtncqndjtw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqfojbmwe.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtaeoymmhc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtbgavuobt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtghlgdpur.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtayhezigm.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtxyjzxfyw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeavxdel.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtoxzopdbd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudhhvsfg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtulyfznou.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtoxbygiwi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtotzgeqcl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtkiawylfw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtatgvluzj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtppsrumgn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gthuurniwa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gtrcfaeiww.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtwqpjmmrw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtbtmomfxp.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtslwmuzgv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtvatztlwk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtfnztwwdl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtihaqwqmy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtmmawtolh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtnxbmutuf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtfnvrdrri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtemlpgfdp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gttxcfzyzw.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gtpptmhdgj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtvplmfnri.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtxzhivtyh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtmzcjlskk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtwtwflaea.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gtivbggksa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtfrudvwsc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtjbsudqzg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtdcobfcxz.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtbxzuecxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtrwxxttii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtjkjbdqsj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtoidltnrz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gttbovmwgk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtttgecmpz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gtdepnstca.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtncnmvzng.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqyzwqqs.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtqxilarhf.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtgczvrukh.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtlhvrksfp.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghtmxjgm.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzrwvozs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtuwzzjsby.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtopfwhftg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtveurgbxc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtlquvnoml.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtkrcbuvgp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtyfxdcrmj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gthemnrqzj.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gthxklbuqd.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtlyrmwifg.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtusiivjrw.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtublvrste.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gttlzkcjhn.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtqsksvhik.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtxyfkrcsj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtkleyabst.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtamdoprkz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpcxutns.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtqorwcrsu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtqbobzzqu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtfqfjgufo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtpkimwuql.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtkbigrfib.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqakogguk.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtlpkybvhu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtluviufns.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtuxmcruwf.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtgjtezsqo.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtkmfcjfqa.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfcubqrtn.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtajxkrwoi.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtfldppniw.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtxhquwgqw.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtxroroaaq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtlawmjzeu.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtfyibvgvg.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gteijuofvl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtkulahvbw.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtydppdoqd.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtwqwkiwyn.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtbpsicbvi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtykwzupgi.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtvrgtpguc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkodpnkor.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtuajbfgtz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtjinumskb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.havefunace.top/Article/details/gthfavqjft.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtlkatixfc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidyrqsdk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtdclvymdu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccfyphfb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtrcljwhpc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtoaducnjw.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtwglmofgd.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gtoqxynjoh.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtpaqlqhid.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtcxuyjpdm.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtfobhtfbx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gthhaemddc.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gteovewcmx.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtfidfphlr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtqbzvjmwl.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtqbpenkxq.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtccndgeuj.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gteyqdzbtx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gttapgjzih.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtbcvanaag.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegyakopr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtddemxhzl.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtbgiqpbvw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtbidyooqz.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtitihbxhw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtddvcssbk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtugoyqtlu.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtzuigubzd.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtpbzfsmzy.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtwgvihxlg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtcsemfjdf.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtgiqjtiuo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtxtcknynm.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtlcpaioqc.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtcjokyyed.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gtwfasnyqj.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gttrjwtsgk.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtlxszsrgi.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtpupkmxxs.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gtfbedlvyf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtfuwzngme.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gthqjkejhu.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtfysakfip.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtlsgfaabp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtemcjjefa.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtpngzvvti.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpmmvbew.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gttuqpogtz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtpcttvjtz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtzcdpocwc.html


<!-- 参考信息 -->