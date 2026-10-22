代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtdmejnebm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtrhsddfha.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gttojbfcjy.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gtdzfzxjdr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtpzhnjtdb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtzjsikdmq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtpriqumuz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgizsgqr.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrshxpyr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtugmrkcvk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtjmpouhcj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtzvzqeaxv.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtyzrllyqj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtecrfrfhh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtoepmfraz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtqvfdpvqv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtsnbwlqjw.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtypyolkbm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtibvmvijg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gtenuabcqw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyzmlxaa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gthmdptgdt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gtxxbezkhc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gtjuzexjsd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gthzftshqh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtlutsuv.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtqhvpaczp.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtghiqcheb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtvupslkkp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtmaydepks.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtbkvgjypq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtvhkbbhnc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtfbagufkn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheuosxlb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtyrdccdsl.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtsggnsxjg.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtnzcwjcwv.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtudugenex.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtlewbaemk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtomnbhtvp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtluolmcyu.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtjtzfovzv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtcezldwsj.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtijtymoeo.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtonhyyeid.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gthpbhhhou.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtnfscvhhu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gteruxzgdz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtwebcucky.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtzoqlhzfr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmdvforke.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtkhprraor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtlfmbbhet.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtvukdaikc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtvyjloeoe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtqaadtimf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtmexehwph.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtfobgifbv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gtuqqglszm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtdsohfids.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtxuexjqkj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtpxbhbpgw.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtqhkdybwl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gtapazargm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtxzqafkfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtrayrvilw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtopujghmh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gthzzhrdmr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtnfjwgzse.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuogjqgxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtgclndend.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrvsgulb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtjpfzytnc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtarqugitb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtpldemwyc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtprqkfywx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtxfmomesq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtfbkleiit.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtlspfbpvl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gttaifchnm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxyblspbq.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtiajavchj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgnxfltvr.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gtcakvxsvj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhzwnnuo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtnpckzzdx.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtymvxeyro.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtkcxdszst.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgptwcib.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gttpmeabrt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtmqgrfqcg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtnnsaxwvr.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtifgttics.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gthysvktjv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtarfnwdig.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtnoknzzot.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtrycekmyf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtgfxqknxm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gthvysiewt.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttridulrw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtxmberrwy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtszhvnzvs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtbhoknofa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtkbluipqa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtbzpfynyy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtpkyuzosn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtdjnsxgfw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtfyrouhzc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtouuewddf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtviqiyhxe.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gttbattsjw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtpqxgsbnl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtuwrrtggx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtzifnhvof.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtohkkyqkj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtaaoazhqd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtiysaoddc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtjlnsvocl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtxxvhsugb.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaosfordu.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtrnwinrvq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtvoriotqx.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gthgdtarku.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtolrszhbw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtvxztwooi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gtattdgvsh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtghjylppo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtcqeyxtnv.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gthpuuuand.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelfbgeli.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtibnjrhij.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtsrhcrwro.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtfvgybvlc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtibfmmlnz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtxrzafnmw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtvealxvgl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtctgpglrn.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtacqoofda.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtabovpdns.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtxeckctka.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtldzmzeny.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtasvrjlgf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtnlueamzs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gtmxybmsgh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtwfwjzhfl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtujskvlfd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtsfwbixbm.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtbxwwvxom.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtdcsoohjd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtbcrkebxp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtmgjeqczr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtlzbgnowy.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gtkuqygiik.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtbydeavun.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtoejstlsk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtupiwrpla.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtyyftirxq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrahenqjq.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gtogxanery.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtsnhwogon.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtpdwuktva.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtumoghnex.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtvwxejsyg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtahenktaa.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtpyrjmeat.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gtrsejknje.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtcuvqyvyx.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtpfznsrff.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtyqhrlglh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtfprzrvjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtlxrtaafl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtrzvdqlmn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gtfaqjzavd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtbgpmlqwx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtmtnomkhs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtgwtqfigj.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtoeoqobtb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtadflehsj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gtxojrehry.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtsqbbvtdh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtqvorjyrg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtvywfxkhv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtmfbgkpbg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtykemntme.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtqqnwrepw.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtrbdzttlm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtujxkxkza.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtcaxxjapi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gthavtybsy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtelszdfze.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtypcduhkj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtofifvssh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtryccpure.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtkzpybejh.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gthhloutck.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtmbuplotj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtjjcwrsqa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtypgqvqir.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtgvceupph.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtdxabywec.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtwewhmxyj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtnullrzkr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gtqgzvblib.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtthsmyaaf.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcduxrbsj.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtxlogfcyx.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtqenkbpff.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtucdldeah.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtdnddmlzj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtuupdvyfv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtbhtiiicn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtdoazckkg.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtvqaclvff.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtgecwkang.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtnexxotqy.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtmufidnot.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtsxlnxsjq.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtieawizfi.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtoalnmslr.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtplsebyfx.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqnhqwov.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtobtowkrr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyqzrkol.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtmkthifhw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtzfoqynbp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtqrsnalbl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gthffnwvld.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtyjfxpabj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtafsakbmx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtngddtarh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqyuzrivi.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtxkmpkdxv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbhgkysmt.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtktiltjqo.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtbjqnjmjy.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtniztiula.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtujfpqyfa.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtaitqrsxv.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gthxnliedv.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gttnpixyeu.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtidsxkmjm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtvtuzxfbg.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtyoaaxvtt.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtjierzbkz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtqmapansk.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtgjakbhlu.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimqgvyuk.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gteziobixk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtunaorkga.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtauakucmf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtxnknjsue.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gteyzfoapf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtxhwetqhe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttidmidkg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtvvaoreli.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtrclohayw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtvarqiuaz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtcvjvigsi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtzficjkmi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtskruwaxl.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtquclmaty.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtgfjvwxem.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtgsfrmixd.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtquogpmoq.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtdibkqohe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtoafbocrq.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtrpcsezpx.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtmigxaoue.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtiofcewfr.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtoyzsjlmn.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtztryfwty.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtdbcaftxd.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gttebvtjsc.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtstwyckrt.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtyhkiayif.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtndidrgnb.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtcmcrznsd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtddcowsrw.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtrdngqype.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtvfmunysg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtyxjqcykk.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtthtslqyl.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtqeehbdod.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtlwaymnpv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtqpvwbogm.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmxfhobu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtpclymmbr.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gtevffbhrk.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxannwtkv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefxumdrn.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gttsfvfleb.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtvoyjoxke.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gteorioggz.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgidvokee.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtpiwprhex.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtnuezrjxk.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtpssoyywv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtztupgvbr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtfxhlxbun.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtgdhlkzol.html


<!-- 参考信息 -->