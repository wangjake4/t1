代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtscvfyvpd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtsrsinnkp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtfhzsndpp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtgdsowazc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtwqqshweb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gttzvvapew.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtgygffsbt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwmrfssiu.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtdgociahf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnmnvqzlw.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtxkellacf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gtxssuvtiv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtzcielgdb.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtuodtydid.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtrhspqxyl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtuhmewhxs.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gtxuflvjcr.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtscfprvyb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtlprfqtkh.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtcsxwxped.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtnydgwsah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gteqvtjllk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtpiercgeo.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtzrkhrpud.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gterpvfzzu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtpjjzcovb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtttutvqtq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtofgfndwb.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtntyblgyn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gtijiggall.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnnniguo.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtwhkbfysp.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtkrwuwnyy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtemhffdsg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtsaaslvhr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gteynpqhzv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtomudwxzr.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gttddgsufh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtywoawlig.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtohrreutd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtdqtimxvs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtwtuglvti.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtlqhafpbw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtsoidjxkv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtrzucbtyw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gteaznmlqa.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtugtvfdbd.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gtoalmtuqo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtanixfbhd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtyslucngo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtuvpfhlhx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhixmcxp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtqwszxvaw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtkxizdblq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtjawefovc.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gtxocrojcw.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtiijxdpyn.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtzhzsexyg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtcqhdeowy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtmrqtsuoh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtwgzhlajl.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtqeovpfob.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gttivfwptm.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtayixoiqo.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gteagdeqpo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtopvblddk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtupridcdn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtdenqufus.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtjcgaepet.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtjfqvreez.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gtpzjumnln.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtbllcuzus.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtygbmkifp.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtwtxpbomr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtazxsejtu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtsitwrwvq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gtssfwvlzz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtooiddwnb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtppikzzih.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxzujnfj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtfqtbxhww.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtoriecrie.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtcjyhxpac.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtoiufaynf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtideztixl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtzwayzyha.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtfmbpenwy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gtqoddzzmz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtcrzxmatg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtywtmtlcg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtlsypgudd.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtyvwdpudn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtbjmyssup.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gtznwgxbcq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtnberonml.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtytmcmvhv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtudzvxomz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtcbpazlkc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtoyxmngvc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtzfyfgtqh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbuqbahub.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtzdcucugo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfterwhuu.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtidxidsqb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtvzwljgut.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtoexibddp.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtskhqnjbt.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtkxzgbnbz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtthfkhici.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtuskhwdko.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtuntvysqr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwgkgogfv.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtrfmnsgkh.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtsfgvxsdu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gttdwhdivl.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcjduvzk.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtkotfewmw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtlzptzdvc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtwuehowxj.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbecszhmm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnfviiths.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtiudvbcqw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtwbzcydle.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtvzqileni.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtteylwfnt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtaklsjdtb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtigjzcbdv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtlaqasruq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtvlhujjmo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtwcgudhjt.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtcaqurrkq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtbunyhhau.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtybnupjjw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtaanayjsn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtzgpqnvcr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtqzdpabqk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtvnfnvtkd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtondtwmlp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtasritrsw.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtykdzyguo.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtxtslamxv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtsusuboeu.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtgzsexjuh.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtowealrnk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtklvbimxr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtrlxpsicn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtbxedkeps.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtlkmxlnuu.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gthidgplbe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtztcwnbse.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtfcdaeuew.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtrcdhjats.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtrscnlvwi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtuiniivxe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtbfvhqmgy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtdhsyjltx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtqdlavyxl.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtceewkekq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtlecxdnal.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gttfveztlf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtxeynabfd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtespcqeny.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtopdkbtdn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtpwqwryhz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gtmkfczqun.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtkwzqgnlo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gtnwqzlpcu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gteogqjioa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gteqsrkcji.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtpdtdgjma.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtyzpnooqa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtoqghbijx.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtihdfgxqw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnemfnmqq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtfknvrfhb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtomsoxdfb.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtggxvzksm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmogwxgoh.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtfliwbagn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtgbjnicvw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtdpcpafof.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtgpiinjne.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtguxqhmce.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtifphoktp.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtvkikrshi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gttybhispi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtrtldohiw.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtjwincrxp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtnawegzkc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtbwmklpib.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbquhruf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtfhgijcrt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfahmmwlh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtlydptlun.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtjdyfeppb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtogiyecrh.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtltmpmmzq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtjlmozcoz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gtjiismila.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtaixcedmb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtcwdxvbfl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gttadudzyn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtpdaqxpvj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gteivxobzn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtcdjezfyq.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gttajbqicb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtscdkgfbv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtfadvuolu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwndbpha.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtuqhzpncj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtaqluqzic.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtwyjfpldo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtzpsddios.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtjmhlruun.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtthyfzpue.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtmipjzzzq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtepniunsp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnvykfgc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtxvoskigo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtkjhgnqea.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gthrmdurkp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtbakmwkhr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtdyvtsime.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gtjivfzdgh.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtscqiwndv.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gtqlazoavw.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtvyppwqbg.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtqhvtzuxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtzpiaesdr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtjotbydle.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtfbkiycvv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtljfdhrwz.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtshakcmeb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtocqgyzzm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtpovcqxzv.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtgbazzqly.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtazgymqef.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtogrxjrad.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtwukpytop.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtsgfmaisc.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtwfkinolt.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtrhsrqwbd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtlpafowyq.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtxhaecijl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtkbquqbmg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtaxktxefw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gteeorovrj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtqudvogzu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtfsbodjqj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtdeiikrtr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpmwrkgch.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gthmfpjegu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkdpldgbm.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gthxlezaoy.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtfvvfgxeb.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtygesrgwk.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtayxiqvaf.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtubbesqpe.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtvbgrsytu.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gthqhktkyn.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtftcrfdim.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhcffphe.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtuntmrrha.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtrjtyobpx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtytqucgsq.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtydxldvij.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtsdlisweq.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtafmjblxy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtrugrjiql.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtpylctuoz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtqudxgxub.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtvhemdjbg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtoyvyzceu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gterxqpghb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtyddtqbct.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gttcdqfvyx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtgdhmbwqx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtejxgxffn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtsmfeiwmw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtovhehkxv.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtbuqytisj.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtaxpudgvd.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzrxlowq.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtkwbpiszh.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtgcqfypdl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtydtevqxl.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtsqgedgvp.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtmhulyzsj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtidnmjmwa.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtlfjxjjum.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtqzqdhkta.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtbejzuygf.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtobyabpww.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhzqmkau.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtntltoert.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtoknfstti.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtnidyxsub.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtxferafwq.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gtbfqmbwmj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gteuqmzges.html


<!-- 参考信息 -->