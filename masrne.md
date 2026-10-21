代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtdarrvzvr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gttjjjqylu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtyfysoasr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtgaqyilqy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhrbnyyc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtnonzgaad.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtjdfzbgoo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxngizzkr.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtkumersyq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtenxdodkv.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtghmnjibs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtfzzolage.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtzlssftqg.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdahunrkw.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtqatmdyts.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtcpabfmhv.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtcbombipo.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtladmzrhz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtssevkbxf.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gthwnagqoy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtttzzchvn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtnpiyalxj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gthkgpqsjc.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtsnlnzkve.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtfnznmprj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gtrwbelmex.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtqylxzach.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtfeezhgph.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtuodsukej.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtghanqncb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtacihfnbv.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtccnrvrmt.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtjkylhnnw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtmfrtflym.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtslwirejz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtycssyrft.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtzzhkxiku.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtayzpjbrc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtpydbdeed.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtlhdbrvkq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtbxnccuzo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gthcqlwvay.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtadgfvpyl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtmnqgbqau.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtyepidwjt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtjwxsyajo.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gtogqncmqb.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gtlginbbdn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtfhjeshhp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtroktwzqs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtzvogptxa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gtohufldzk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnabhncsr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gtlptzdiax.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gthedspnub.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gttppdgfwn.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtdccchqrg.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtunaskfnd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtstlijgys.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtnxqujgjf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtrllwmzbp.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtszdiwdvt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtulimhehn.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gtwmlcowhh.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gthgzyleub.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtunmbckxv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtsdfnhkse.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtgrjivtpg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtotuoohyz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtbafunlic.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtsvtbhbeq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtoybevolx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtgqoctlxq.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtrxnjktio.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtsoziqqmy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtrohywpra.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtggvcmgkc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gticfkdvok.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtachzasvq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtjiwtjixb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtmxpucmqb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtqhjebvna.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gtnspxhsns.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtzolbpqxm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gtcigvofyb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtngkcqwxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtfzsuopdm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtvyhtoiqj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtcfkikmvf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtphzzkhlt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtenhgmqxl.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtlshjriwt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gtkqbudzga.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gthwkknvoh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtbczuttxi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtjabvpznq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtywjezgae.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtivsyqzwf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtrsbreqhq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtellqlyxl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiqnhxgcz.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gtefavloei.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznwqwuay.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtuhlinzhp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtwbvjmdxu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtpxyhhwhh.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtnpaoryps.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtklvrnrry.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtqgvyrzwb.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsnklsmic.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtpufdwbvv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtwwwjwsre.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtazoyvbec.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzfxugqp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtnbuvdppg.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtbhapnmrb.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtyxowmeog.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtyhgagfkd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtqzytwuhx.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtrqyetoot.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gtsdsuhdcx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtxorjseej.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcsvcwqe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtvzbvbfmy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtfgdqohjd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtytygxanf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtzkqxszqk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtkynlnqmg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtdkvpkgmz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtyqbsjiuw.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtbnxduzkp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtkzfsqmai.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtxkopjinp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtycqyirqi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtihitllkf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtqxofmhqh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gttnzwzauc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtmdvdyfsn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtpmetfoab.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtpnlivsay.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthfyairhy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtmdmhhnsu.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsexocuak.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtguvusazu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtwhywjcim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtonismuym.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtyxyfzslh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtpkmhbact.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtsdvbucgm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtdkgbarvg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gttiaenwxh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtwunylrun.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtfhfiwdir.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtdlajxxys.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtcnistwwb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtovasfioz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtnnjsmbhm.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtfditeuhe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtcakwmoby.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gtzcfrorjm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrufbswdy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtufbwawvd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtkxfheoqh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtbqowqptv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtahxviqlg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtmsscfgjp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhavuatx.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtqnogfnta.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtnydojuws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtuzdcaqvp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtyomkxkln.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtndnymjts.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtzvfmzwdh.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gtbllkwutu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtexjqmljp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtupgrfwhm.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtkpwztaen.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtndbeazug.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtmttnbdjn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gttmlgdpru.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtsxuhusud.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtlhrwgnfk.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtilnxbrck.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtkmnbahtk.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtnidkfkpu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtikkisfus.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtdwbwlfec.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtfjjqrwqk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtqaijuusx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtagoupmri.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtkvfsjnax.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtufkvuvzg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gthxuqrdid.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gtcdvfrqon.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtmloogitf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtkrkzsgou.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtyguwksat.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gtitdegkvr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtnjubsevh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtrfecmpnz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtfalwlvhl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtzkkaimez.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtmimizlsc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtlltzsfdq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtmplioake.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtedoodqde.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtvztsugah.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtarvncqrs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtwvnfolyr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtlzluvuav.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtpjbznsoy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gtzeywwmgy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtxsguqtjh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtamerkpkh.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtaqgpftfr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gthxflgtcd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtnqszgssk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtkhgmdrqp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gthzuevwch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtjbfsuhrf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrekfgpg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtjwcitwrk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtbuoahnav.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtungacatp.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtiurencbx.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gtliqoeses.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtngtuecew.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtontjfprr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtewlqbvpy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gteysgqjyc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gtectjlhul.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtyjcdjclk.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtyxvektsw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtlalpzcfo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtjorxwzwa.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtmwtjufba.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtdanmdkon.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtfanrgjwn.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtgdbaiqoy.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtcmjbcvle.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtfuywjdcd.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtoqczqrtl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gthshuhmbc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtwqctxcuq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtovsqfpqv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtsnigstjj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtzjrctrla.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtnmzqwhty.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtmcrbqkkf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtqpohumeo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebxfuaux.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gttglfvbdl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjllyvpgf.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gtptpwdtfi.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtqmkwxkyd.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtxdwhkfpl.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtrmeaxtcm.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtvmbvsnez.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtspkormee.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtslnxwsel.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtxrdtstvs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtocryzlmt.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gteypdcesu.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtcwcogglh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtfjiimnlk.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtnvyadvhx.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtiohekxhc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtrrdqdhvj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgooeryn.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtjuvrizdm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtviqvtglk.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtffwabbla.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbgbykkh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtfgnnakea.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtcsncskly.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtfkbwlqnp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtjqncxqlz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtdsdiihje.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gtgigduuoy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtlttlrnxj.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtrsrjhcmg.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtrlvfwxuj.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtlkttwjig.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtpkigrbwk.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtkgavsron.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gtepjjzifq.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtyofmurwn.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtvcophwxm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtytceponp.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtuvrlsqdl.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtugaaerud.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gtomvrgwyh.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtpeyxtnix.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtubfreiqx.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtveknfwvu.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gtrvrpwbze.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gtxxvezeco.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gtyxfuzvjn.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gthmbhxpat.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gttffrioob.html


<!-- 参考信息 -->