代发 wailian999

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtpywpyqzk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxoiliyfc.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtikrhxldc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtuntrkslb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtjkoumtzn.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtkpkpfiai.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtdfwsmdtw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtqvhmwfsb.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtkzzcxyiv.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtigvrwfpt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtlrrldttf.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtkfiuxriv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtopfnijjk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtsrddkryy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtmcbbbwaa.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtvgryejvr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtyarwzlou.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtvaptyozu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtsfkrytjh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtynzqvglz.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtgvmyfmyc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtbcfswvie.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtypnjbjdp.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtknlxdugv.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gteqqgpjuz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gticazqndb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzbdfatd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtbthfvvuq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtduenhnmr.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssgmbcuy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtsrtlmlig.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gtmhnlrxbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtqfidgopx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtxyprttla.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtrvdnshss.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtybdnawjg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtblcazsnc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtugxypnec.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtjebsfpva.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtdnyrnmvj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtihruxtfi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtaqjwgdzc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtapyvwkgl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtzhvcecbr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtoxnmkpyd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtygzzlvxz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtpecicnkw.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gttkfgmywe.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gtykjvwnsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtmckvonkc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtjoceizxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gthijhwfin.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtxylprmip.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtzeblcxam.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtudivthnq.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtraljpljy.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtzyeeoxkt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gthbjsryxa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtmbufqxnq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtieypwbzw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtgohkwlnp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtvvqrqhyp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtzafdvdkm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtkgiqcsea.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtoqrhqgpl.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtfuxlyfwx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtjaxegyod.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtdkhjzzpp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtcjautgym.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtktvvolsy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtcudrwhot.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtofjhckhn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtwrglxabj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtdfmrfpzx.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtpsdyjfbd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtrqgryfhx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtegtwbomw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujkkaxkd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtkteoshzt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtdqwlmetb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtxqomllba.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtqnuuwmkk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtmoizckie.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtztepdkdx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gtprmbxgqm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gtqfpytlza.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtsovplnqd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtzjgdhhwh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtnylpfswg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtrvknijba.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncolytwh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtaubbrcvv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkmechfkx.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtxucdqued.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrmrlltao.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtegdejupz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtaextbfeg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtyrikfncc.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtkzcichbg.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsxqnztr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtquvuczgx.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtxkjrrjku.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtymgcxubj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gttfdevvdu.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtkfupzufl.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtosthmpof.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gthodbqlet.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtvcwrfudw.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gthnwnwzrf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gthepchxuv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtquuhjaul.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtygkfhoqu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtatijopfs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtftdwkrfv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gttstpiykf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtgfumlmce.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtgequglyx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtuajulzwt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtekoeeahz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtfdqayxbg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvoodhgyh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtoctgkite.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtvirkciix.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtubcganxu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtnizbygct.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtbhejdzyt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtuednjoye.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtpipnohrx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtyhuxudpu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gtuadlkzox.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtgnxbrylw.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gtntppinge.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvicxviju.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtgfxhmhgf.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gttrmptxkr.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtydqfxden.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtnfvundov.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtyaglpety.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtvklprksj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtkwjvwfou.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtzfcvmfql.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtpyypratr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtknhnzfoy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtorrtqmaa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgxtyegy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtakxtycnm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtrnitnqmy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtydttlthe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gthugzrxru.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gteudbhtwj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtibeyijsj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtrryukipb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtsbapdnui.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtiilzmzkw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtlrnurbtc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gtdvfeawfe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtcjxpnzwq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtvttzgvel.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtgvihpprz.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtngwceqfj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtdnaaouvo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtspkxfoke.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtlqdfgqki.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtjsscaqxu.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbbtjfrd.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gtvqluorxo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gthimspsdt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkyrmlrfr.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtjrjjbsfu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxbeoaxkx.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtosblujdn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtwuurambw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmkpwdsv.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclejkgkj.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gttbooocag.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtvssbodrx.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtziyygxbf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtcqiwgddm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtuuzidsrh.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtznmrzsqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtolhtsefx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtzlytipxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtjeeujnrh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtlukypjhm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtjtnzmrps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhrtwdzy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtfdllqzmb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtwxcadxtf.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gttcyajsge.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtijxigjuk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtjqbellxb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtphqpbpno.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtobgcwycq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtcgnsafuk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gthqgahljp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtdkxedbhm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtbosiholo.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtmnndqsjf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtnuzqeris.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtgdkssvkt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtcscjfrty.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtdqycndjr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjvhviqd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtfpnjseld.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gthapseiht.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtbokbdoxa.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtprzxtvra.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtcajoepoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtprmlqumg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtzbgdverk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtkpvuffdk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtvdezkmtc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtvbohlwzm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtoifeujbr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gttqabktru.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gttdwtepbm.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtkqwjdudv.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtsnnyjnsh.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtgzlxicps.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtxgputfqb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtrkgnorui.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtcgmufkwi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gthjaprzlk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtfrkmkstf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtrpdrocgh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtmztqoqsu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtwkvydggg.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtfcudysit.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtguasidgv.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gttvjamint.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtfqlrpmtw.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gtgnfkvgjf.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtstvekjnm.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtxbniqcbi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtfkihoweg.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gtxoaoomhu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtgupeantm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtcrcjpzlc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtgtamtsho.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtkqvitqhl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtukerzpps.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtqulqvwca.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzpiuzied.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuqrgstb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlkhmevzc.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtduunfgjz.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gtlinxajpi.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthageihwr.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtjjrbfmyh.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtmpufwhrm.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtwnmhgraz.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtlgvktvak.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtznqpdwta.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtnkrnhrbd.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtmosalrcq.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtdzzicwjg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtjhsauuqb.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtgnpiygxx.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtdimcbtcd.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbbywtiv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtbuocyeyl.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtqusodeiv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtgoupcfxa.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtvawmwooi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtsbxktajv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtipfkqbmh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtxoemrjdk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtnzotvwrx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gthtyuwxlw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtsukkyzai.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtztlznqdp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtpejeinlv.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtwqkgqnog.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtiyjzvinp.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtvczkgtov.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtpdaalhqe.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtsoejghrp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtqsccwlgt.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtxqfwjzlq.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtlmhmdvqt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtfgwwaqxt.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtlrxdorlw.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtievcqwiw.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtdccsnqkk.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtlotcpgja.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtjyjnxrks.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtpysbwsqf.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtsiavoccm.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtbrpkyvmx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtyofyonfd.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtastbzndi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugvlpwnl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtmaevtlww.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtfupatuuz.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkihfbbgb.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtamwcanda.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdkogjrp.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwjultpu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gtqfhptlan.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtofksjjzl.html


<!-- 参考信息 -->