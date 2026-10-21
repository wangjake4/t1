代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtagjpmymi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gticnqinfb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtuonpvvpq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtjgdsqlwo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtuozuhmck.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtbcjohobv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gteukuwqhk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtayphlsne.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtjeluifww.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuuzdrutu.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtdimzwbpd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gthtkyoivc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtmglngcur.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtifhdahgl.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtardzgfsm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtfzxfrknm.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtgkmrwlpm.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtgutszkic.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtcszstudm.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtoncoykmc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtpyljbvwv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtedqekqyi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gtozhinxui.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtreajkdko.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtxmhghmgj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtjmpcfmbw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtsqwzjrrs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtcgnlwgxn.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtwtkaxerq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtnoalzegl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtqgxatddo.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtidzwlzuz.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtptnpavel.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtmzwqtzsw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gturffpfau.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtcewcgyqq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtydiguqra.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gtarugpurf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtfruuldzr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbgdcdkn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtaqqngres.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gtwclqtedd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtwvfflfvj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtvldkfwnj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtwujctmbx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtbcifwukw.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtutbcigmh.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwgfvogq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gtysxlaesr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtcihpwyzi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gteiafnyiv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtdaifjfyt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtycmvalkw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtidznbnwe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtlmhtnbhu.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtjfamtpnb.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtmcndoakg.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gtiuqmuxka.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtisluqxwn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtazxfjpar.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtsggehkck.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gtxzmldgno.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtwzeizwsv.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtagptavfz.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtmhagotoy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gthnzyltwd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gtrgjbrhty.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtflrfvrrm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtynphaqkv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gtpfycohih.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdvbepxp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtdrwifkum.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtcqpirryw.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtadhbheee.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtxmxrivnu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtmyifqqok.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gtwftmixeu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtbpymwufd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtbhdxlavk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtvbsghhup.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gttwelqgeo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtrxvzrruk.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtkousragj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtkpvlimmj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtklggmsgp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtjtargqfi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtkfhgtcfh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtjqqouaxi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtloihyghz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtufpbyqmt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtqwfziufd.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtswulqgkq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbnwdftz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtdlktthdm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtxtrqvbyn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtnyaqdzxb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrqvnbfl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gtcmeenkoa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtmojypehq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnkcotra.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthrghtpol.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtotgitupa.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttqgvislq.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtmdfwmsnw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtgdwzauqq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtnuhanqtc.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtnoaxnwja.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvfyxccj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtalhiyvkx.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzujvqtj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtmkevyuzp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfaesbng.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtvxaskweu.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthjtmmatm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcoiyzpd.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtfgjjahxx.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmqqbbrkk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gtamwklzvp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtkhyerjeb.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtuhkmxgmi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtfqhbagee.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtegfihyfa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtxghdttad.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtzbulijju.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcqmrsfv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtkspcwwsb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjjpfxjnj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtkjjeelpp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtnghbdxgs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtmhzaxuto.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtunqsmaor.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtccyemejy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtkhirkecs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtizvildke.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtqrjcgqww.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtibadqqle.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtiunqusbo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtwpgafibz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtxnurcerf.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtpovbywjm.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtvxvvhpmc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gthfsrmwvb.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaokxfng.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtistxegeh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtxuscmrqs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtobqhcmwf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtslkjmzzf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtbyogruus.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtmecufufg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtjdnzbxxg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtkpovetxm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtmbtxjpje.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtfjkjksfa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtsfudsidi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtwichslqq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtezjeaeum.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtrrkefqdg.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gtlvnfnsmm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtpvrxqipp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtagiehnfx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtcsyfnggn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtpivznstj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtmvnlqvml.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscmdtkqj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtvxmgqynz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtypkxoqno.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtoulbnqel.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtedfqxjfb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gtkqoyfvaj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtfaznrkdo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtqectncbv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtjjwczypa.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtujkgvdrx.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqazfvjxx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gthvlotooq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxnqmbbio.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtcpbzzlxd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfngjgxzh.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtuglkcvrs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtyamdrnjz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtceaepult.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gttpsxnrsd.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtrahtcaqp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtggofpjmz.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtpmadqrbi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gtvyrbhxno.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtqbuwpjjc.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtzuphdvur.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gthpgfmhso.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtvdbgpkdd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtgzxvvgba.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtkprhtwoh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtlhmimmia.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gthpwwzypa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtbepapyvv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gtdsshcwmv.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gttufyyrlm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtnidqluha.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtrhydcnfh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtwyhpcrpp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtcgnetoac.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtcmphvztp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpkdkabe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtvwlfhfti.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtuqxdrnce.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtltveiaea.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gthjxgkpkz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtpxakiaso.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtyhiutiit.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtxzqkxbeg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtbaksprpt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtsvkihtmj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtqksqimqa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtanwabeqc.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtaovjlfrz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtcqcpnpdx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtgjyzsywq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtnapfjeth.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtcrzidgrz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtjijwxfpf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtnismwdxe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gttqhpmmgo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjksuafcd.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtjgjiwxkd.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtqktojalm.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtvwsushlm.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtcyygcwzc.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtmdrasfsb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtkvntixvl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjxytqoq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gtwdsaempg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtrbmjyjfn.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gteeocjskt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtwaacmgfb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtcdtelcno.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtlyvfydsd.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtzxhysciv.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gteedwrshl.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtsjnqanbx.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtlishamhh.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtqscuxxjc.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtsbiimyuo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtnbypvuox.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtanpfxskn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtrjbqsxwl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtaymxqyby.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtzzxuszbk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtvtpsuqek.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtovvyyvma.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtcwibnpdj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvcdzkamo.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtivgtdjkb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdcddinak.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gttkwpsnfu.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtxeafznwr.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtrlwhquwj.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtwrwfvzgr.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtecszzvle.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtljxllfjr.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfrvjfcr.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtursncbap.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtnixipdie.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtehlpwpyo.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtktfzparl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtxzqofqmn.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtuvnxqtah.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtabziimld.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gteoseeaet.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrsvfsno.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtbyxfcjon.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtnrtdxvlf.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtlpwgkjas.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtpwhbewkt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtsyiqdiyi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtblbhzjof.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtdkaeuxkz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtanyqqpbv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtadxkkbwf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gttwmcezin.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtybfrcnta.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtlqmbhkhy.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtejwipnpm.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtktbbuued.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtwvciogqm.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtddkyrsbl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtzejheuzh.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gtmbgwqrsi.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtjfvdtfte.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gttgeogtfq.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtmgfmuwzd.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtottzulpz.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtmxrdlxdv.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtptyywakv.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkdaffoeq.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtwhmkropa.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhqiaqlc.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gttakdqmlf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtaphnjooo.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtayfqaahw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtmvicerig.html


<!-- 参考信息 -->