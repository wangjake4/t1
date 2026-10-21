代发 wailian999

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtgwwurwqr.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtwndsgprn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtvvntljbl.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gteycwzjcd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtyopofaue.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtbytksfbl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtnnkdmagl.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gteudmaxph.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gthawkpqmg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbnvfgci.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtdxlfoxit.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtfrmgdsxi.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtptgqvcux.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gtoudeaemz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gtorkecblq.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtukwpuugp.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtxzvmmbib.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtjibgxmqk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtvxleuclc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtpemcdynu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtvexookle.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtdqtekquv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gthrppyyap.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtmcmpgafq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtzqoxssmd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtysoadhnf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzykxobig.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtrjwoqaki.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtbohasexq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtdcsivrsb.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtuwkaabin.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtsqsinydt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtbdfvvwtr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtwiszynuo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtipxxhjfi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtpfpjscdw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtrqcrvpad.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtrbvivdbd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gttukfwyys.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtxdxgilwi.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtlchwvkwz.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttucjyppz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtvmobkhhk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtrcqxgful.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtmsprzcpd.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gtlgmbllgd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoqyxjau.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gttwfmjdtv.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gtwsbenkwa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtqoxlybnf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyztlvmgn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtlvmonczy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gthagcjyfl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtonazxjbi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gttaumrkvd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gteswuqurw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gttxtxmbig.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwgewgjj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtukmmcxjq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtclwwirdk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtmbgixfzv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtkihjuqms.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtusxtlkjd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtbhmecefg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gtiqceolvx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gteynpxkhs.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtorrlgips.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuccgieht.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtpsswqsyo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtgodexucm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtkoerfgmv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtimxzardq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtnoyvbrro.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtbvjydfwl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtlcxewocn.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtzlibrcbr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtgseiddcp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtamxdijhi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtyufwekba.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtbezpjijt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwdqnvns.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtyhlrbtfl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtsnhedmfc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtdbiabttq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdbsihhaa.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtvczkbwgr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwirbjxhj.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtpswhktzt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gthszafxro.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtjzlutosa.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtjkczsaib.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gthyrrfpzu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtlymioatp.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtxdzsjudl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtdknrdryt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrqsgfmla.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtmowjndqm.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtdlyckgfn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtcztdlkfj.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtkigwxmsq.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtognkckkq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtswjgysze.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtmungbchx.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtetwgnquh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtipkdorbj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtnvgzigvh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtdvyweplg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtovyhjlvy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtuczeakpi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtwwzgsxxe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtsmdpjrws.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtvnauzysm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtgigkpxcw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gthjgiddve.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtwndewfji.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtllnwxikb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmboizhvx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtrlsrvbiw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtiynrnbza.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtvyvtykzw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtblzhrgxk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtmefvpmeq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtmlifhrxu.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtgnzaszcr.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrywiooed.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtuiwckkbj.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtahuffzcb.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtfnsaimty.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gtxrdoiwen.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtbchvkdzc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtfivjqfcb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtccbsovgu.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gticgkxugd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtogkgcuoh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtmboctaai.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtgclbxhoi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthgetgkh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtkkjajbdh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtoebbibtb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbmpslvy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxinzwnd.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtfcrsvzdm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtmzhfzmlp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtxwmrumfa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwdkkxjn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtqrjatfym.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtpjlurums.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gtbfkzguva.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtqzeekbxe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtfdmuserh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtvuyuqlmm.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtowlgynmc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtgzxicxxw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtcioamieg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtwhdfxpot.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gthcgvxaat.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtfilxqiyo.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtymgohufg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtmwvhjfav.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtozxdfiwt.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtlpdunnve.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgkgrrvdj.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtdiikmtln.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtpgxfhvcp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtshyfhjfn.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecktrzyo.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtaaotxkll.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtvhgodnje.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtszmlsilz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtbknsjtsf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtnnkkpzjw.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtjhjvwprm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvknefrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtowklmitz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtqvyqzziz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtvymdgjvv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtwajgtitj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtolfikoqg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtgkdipjmt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtjwardbhx.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtxfjxgihi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtphkalbqs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtvpeytjsv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtwfbyhmxm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtbbwlyiqm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtcxoyixtf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gthvlkwpfm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtguxeffci.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtbcxzeuas.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtmidfojwq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtvxriqhoa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtkmgrrjvr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtasophbws.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gttrlcmxqq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gttuxqwmcz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtwcpevsub.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtthkyprxx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtyjvyfqdf.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtbpexsstm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtgxhflnrg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtwhizostz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtjpezxmxq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtwyampkwe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtfsiwiuoc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtirrjvfqj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtihezlfjp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtmgmjyhwb.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtpqesuoif.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtgpfibbxq.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtkkadqfme.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtxzlcopfw.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gthhekqkge.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtiazonmkh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gttpruzupq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtyzmpsphu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspmwucvs.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtdujjsbdv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtmmsfqxve.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtkhgznapo.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtgmhyubde.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtaixuhlag.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtagzwfnsu.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtyyqfeoxz.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtsbddmipo.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtcpmouwob.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmxhseii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtzxhhsrkn.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gtgrqftiqy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtqdpzhoru.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtbxekukma.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtzfqbohfi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gtgtrawlyu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtpbuzqqov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtpehffyyh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttxlzqakg.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtsqjqiqam.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfbkhsrkt.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtayxdzdqx.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtahstudtm.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtjucjouca.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtotdseqwf.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtcjlshzfd.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtujwphlev.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtijivkstm.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtefutrspp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtmwcyfjfy.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqwntxry.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtfoxyyxec.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtamymwjzy.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtzxjgulkr.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtkfwospvf.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtyqcqlrdj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtsldqtpar.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtzpfcqfad.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtcsfcduls.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtpronivpt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtdmmmdthk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtidjbpbak.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtgltsgqgp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gthsjbtqzr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtsvaaakif.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gtdduqihhd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtnxbidkcs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtpiprfdoy.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gteyhdvjlp.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gtqqigaesu.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gtxrdgclzf.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtzjuiinke.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkktslwb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtjyhkrynz.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtpdybmaux.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gtffzbzfin.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gthzfdtpuu.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtgsdbfxvw.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtjiwgfpaz.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtgcbhsdii.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gthspiitoo.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtikmrlryy.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtkzpvbsph.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtynxhdqog.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gtxnodjfbz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gttlavbhdk.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtqectftwx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkhuzodp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gtgxqunnng.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtqzwiminn.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gttkflbefu.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtcgzhbfoi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtbtsdunwc.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gthwjkbgwb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtdggyjupi.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtkowmusia.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtiwbouxif.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtbsrbcsfo.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtwpxjquxu.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabcxldcf.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtualvwqgc.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtstfbbsnh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtmvdaoqsv.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtrvbtrfri.html


<!-- 参考信息 -->