代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtqcarbsmb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtwdphzpoh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttikcezhd.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtdoqhfjmx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmardrto.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gtxtucenoj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpvvichk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtqkdnhleg.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtiqidcfre.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtovscjuyr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtubbyjvkj.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtqjmsehut.html

TS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtzahhegim.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtaxgzexoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtedzlecve.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtfcspknfj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtmncepxdz.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gttzswmzvv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtkfbrqhix.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtpwgsrzen.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtknltzjuo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtqlrnxkde.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtzpcnrqwe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtytlxlwpy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsphhisjs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtukdhkxek.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtkcewwtvz.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrpzwgtc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtzjzakcuk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtqhxrfggf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtugndthhe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtgttxzsau.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtpeyfjfez.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtiywrdgky.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtbabtzreu.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtdfdossvi.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtuwmtwvvh.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gtumouivxo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gthzdxxtae.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtwezgdemg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gttxguhuok.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtplixoteh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtcyjubvnh.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtorvvpfnb.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtcqoyzrvt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoedyicwe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gteqdodutd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtrvcsxfwy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtfdwnqbfc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtxsbhebjy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gthlbyztri.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtirfmhrxt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtqwjlgdys.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtgurhwiio.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtdetzjfro.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtgiintjxe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtfsmzjxxu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtfgspzjzg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtplizhics.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtbowxxsdk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtkfzteafu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gturuqfgzt.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtytxcachj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gtxlqpqvhy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtbjzwatgf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtwfrprdjr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtfwuofmyh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtisjlirqk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtwstdppjq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtarwmpobf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtpfyxaxdd.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtdanygfza.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtsqpldycp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtcgvjfuhn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gttlknwwnx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtsamukzoe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtdmgftcfo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtrxkciike.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gthapezcxz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtjfkqwvta.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsmphvhhg.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtdqpolpce.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdvakjowp.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gtzmrdnhih.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtvjdwxikb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtfkahziow.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtvqznwhpy.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtvazfkkyv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gthondzuna.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gtljlsrddh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gttcsbjzyy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gtxhmkpfcz.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtcakztotw.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtwvhyuras.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtzqifklyt.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfpcypwet.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtdztsnwbr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtzqbpolzz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtchsksfzu.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gttquflmhi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtleerszdd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxugwiwyo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtaliolynl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gthxdewvpy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtybgjffza.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtfpueaeyv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gthvigrurp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtpzphabhv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtazxunaor.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtoivhctsw.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtcloxompn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gtxgmbpkik.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gtnmmmpsnl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtrxkslhdn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtvmizpcqt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtcdsuwvdz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtrqffjacf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtimozvsiw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtqvztbdnj.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gttdkdhdrg.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtvwynopcq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtyaxrbcnp.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpwlmrdku.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtxotrxvrw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtlnddmrpp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtvljgwsly.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtizokxuzk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtvmkkstyd.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtlknjxzra.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtsbouwsuj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gtckljmtux.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtjednomju.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtxhcyzmvz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtsjjxgsrf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtkblqslnc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtwgtrfkrk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtrwacfyrg.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtlqhsutuq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtoxwhlsst.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gttyeiafku.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtnizhueat.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtlbhxxqep.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtcykuejiq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijoubhrp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gtrgxehydz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuzbdmac.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtvxdxvlep.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gtgcfumygp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtqgbbmimm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtxcyxiknh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtrmumouij.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtfmyhvgzs.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtelriqmcb.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlnwcawa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtdhrpcjtr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdviaykad.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtenwjzpdf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtivztdxdu.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtsvjhglqf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtkdglzuud.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtgdwnkshv.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtpasuakbp.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtotlbdcty.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtxbuxtkyh.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtzvbfvcli.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gterbtxflw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gthinqvgln.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtqeejraru.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtlnaonnph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtwgkhndog.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtnpwqufxa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtwcqywvea.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtgeovuovi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtykyfhypf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gttlkoqaen.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gtbvzjwsdz.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gthjnsrpvc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtoykmagxs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtfiauprxa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtxahtkvsw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtejewuvyx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtxlpmxale.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtdiicatjg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtbesvxmdc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtintflujg.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gtinwmaxys.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtqzrwwmgf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtalokbhnp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtoljxudar.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtnvyztozh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjqnsnbk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtykytyfdi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtprohvufq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtebmoiszx.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtvxfginet.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtenghcppz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtyhxzyurr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtlsiwumxi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtpfzmopxj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtduwsbyhd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtbkcpdwsc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gtwzwbhiuu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtpobrzblb.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtslleryfa.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtgvpovmep.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtyemdwepe.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtqyydqnnm.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtcmrkevzs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtsxdrgzep.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtxcxlzfrp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtdftvizak.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtmgcnkvjc.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtosxojuil.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtbrqjcebh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrgyrggh.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtaalwrcfu.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtcbcwvwhh.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtsmndjari.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtwtexypwe.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtkgjgfxrz.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtioyrlcfe.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtkinhpzto.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtypdjiizg.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gttfjigulm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtlyegevzn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxgopfrq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtxnxyddak.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtoxnrbsas.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtsfaqcmse.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpozigpg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnoxyqxzy.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtuqwzngrg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfevowsuk.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtzfzsqymx.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gtdqnenpdu.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtkbripskd.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtidfaasnf.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjacbgrpo.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtjcjxcvze.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtkmooycvs.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtbmekvmdi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtaobspnud.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtoeeswent.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtojakyspd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtufyvljui.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtqxsnfmyw.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtliudgnjw.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gtbmbdajgn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gttmnwktds.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtqofhnmkn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtlplvlpct.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtyefopweg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtysjhljpc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtpqwuwxgn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gthuckskfy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtymniuhkw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtfypduhfm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtrsaymsds.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtfovmgghf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtqqtaypri.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gttutxlvwh.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtsktteurh.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtldpipiph.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtiukaevfi.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtvnpfflxn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtjrakzdvt.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtkqaojndt.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtzvtbigse.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtudcacggc.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtkvzdhkpt.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtbuzxjzod.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gtkoodurqu.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtdsreoobo.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtojvvekgt.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtibfsnuqv.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtthiuxufx.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtxtsbpwyb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gterpdprud.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gtthtqgrsh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtqzpiotrp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtukrndcdx.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtkgelofif.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtzaifayfh.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtqbxiosmm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtfywgwxzk.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtmovzyyzy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtjdfzkstd.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtiemrfpdj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gtcrfymuwb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtemnyqijp.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtzwdcyotf.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjcykytr.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtzfdhmgbb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtjlqcgzbn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtfrriaati.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtpadwhunb.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtbqjabzvl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtjdavifzz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtvmvurtyp.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtivqnkhxs.html


<!-- 参考信息 -->