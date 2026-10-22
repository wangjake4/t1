代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2zuypxdyj.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2zltgawrt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2swkbmbgj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gt2yxatojph.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gt2tjagyrmc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gt2iksrkalv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2uvbdrujo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gt2gxgsjurx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2eskrleir.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gt2bwpixbxf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2bntfztyr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2jzthgvtq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2lpizjysi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2sjcvcipx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2mkdottvp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmlngluy.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gt2vkdvqdex.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npoubjoh.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2nyxhjzip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gt2fhcpobas.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2xaylmlal.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gt2obhizkhq.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2louvhggj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvkuopiz.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gt2ksupcerk.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gt2smdhbzhu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2toazqbgx.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2esvnptkn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bffixorh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2rqzhnxde.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2jlndugyx.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2fcxjyvnz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2jfdazwfd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gt2jmlgiznt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2kmyxuvtd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2ncliyxgo.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gt2fhuknzqb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2xzihxpsc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gt2zngcxuhz.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2uzbuqeyx.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2aldjfwjw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2cykyojuh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2rxjcyzkq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2yzavirrx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gt2fgsfanse.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkptthh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2odhfrzpn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gt2vplcqmai.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gt2zrxatxbw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2mxmaesjh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2euhuejpe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeydbeus.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2kwyylvuv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2euhyjzvt.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2hijrybkp.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gt2ovtwthtm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gt2ntymuvdb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2udgrzlln.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2demfcqfe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2sfidfaiz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gt2cgeshjcg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwzgudxt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2vcagxfca.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gt2ysysmlmr.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gt2ckeauzja.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gt2cuctrpzb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2aewlxbne.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gt2lzkamrii.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gt2zumfltpg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gt2tgughbpv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2mmfvwkcg.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gt2nborakbz.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2qfrfygkp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2mldhcrtr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srezecin.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2ljeimsts.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2ezngjtwc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2fkilwszx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2fclvsoop.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2nrqjvqcp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2ytvwfjjd.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gt2evroppqm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gt2daapuspf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2bmzphgkv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2vnpflbfa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2alabxwtp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2wvplwfpc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2hvhjffyv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gt2emufiqsm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2zohntkte.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2dgpwjnbn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwmnxtvi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwvrxhpd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2cadyrfnk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2bvipttmh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gt2dmhjkgoo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gt2fecxgcif.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gt2atfqwvlb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2odkzdist.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gt2qgljlnkb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2nmlbfbkx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gt2wizhbrev.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ukqmtgee.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2pmgvfiwt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gt2qctlmnqk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gt2gesckshr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gt2tsnowkpp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gt2auqvxqsp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ehattypg.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gt2bmnxxweo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cdazldtd.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gt2wdgouqmi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2hpvvpknx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjyrxmnu.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlesbzvp.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2fokbufmz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gt2ydorgawb.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wxwwycaq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2laxvpxwy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcalxtko.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gt2fhbkwyvr.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2xxxztruy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gt2knaoemyb.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdynrzlq.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2wgdaepda.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2dlmxuumq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2aaqzxdui.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2zlfduaol.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gt2xiscqgmv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2dfeoaeha.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2evqdynkp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2txtcmsrz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2abwzgpby.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2yskqqwwa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ubggnedn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gt2onadbqsk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2mxqnhtsm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2iunlmoti.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gt2fgyojxam.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrdbqqpa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2ckbveuqg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2irzrktlg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2mlguklin.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2uoxdpvbo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2nwqvietf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2glitmkpo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2madpknwy.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gt2wqoqjjwz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2drizdmrs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2sceugdeu.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2feuapdoh.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hymjadss.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gt2xejpnxws.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gt2qaodolmk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2vqpgtnwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2njudaden.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gt2jinsdkkt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2hstrzcvs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2zahmealm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2wijsrfbk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2alulpmjn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2iyajmswz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2tmiohjgx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsbpnmzg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2wecqqfli.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gt2yllreunr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2thsvheks.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2qdmuvywh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2bfdcupzb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2pxkstsag.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2pfaawqis.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gt2vnmyskkg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gt2ykteanzo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odfpmrzb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gt2ecmekiew.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2devujsqe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2hyssobwj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2iauiurbv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2xykfmgmj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2egsrorqw.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gt2fhgxlrkr.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2milfasar.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsiblee.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jejqgjgm.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2yhqlgdsk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qasuqrzw.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gt2imcwllck.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gt2erkmbhys.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gt2engecggk.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2mxbjnokm.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vivueorx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2wcvofqwd.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gt2lmfgaibb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2jnjwbfyz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gt2kpeutigi.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2boeqaten.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2uepeboyv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gt2ijwqgqyo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2nbbfdifm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2nmlhjgiv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2altbxrni.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gt2ekkxopsp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tivkhzpg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlafcfrf.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2mjnelrqp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2zfrkjmjb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2ksqhovow.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2esfyvfxc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2chnemuut.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gt2lmydolii.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2jdfkokav.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2qyghuwxf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2kxdsfcgr.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gt2amcwrpjh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gt2dfydzeac.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gt2cdmrsuhh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnebwaig.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2efauzmoo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2oxsrcali.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vacbrlto.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gt2qmbvhvfn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2gzenftjh.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkxqrlxn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gt2jcxvywnh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2sqvshbgv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2qflgzdun.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2kuecoyho.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gt2xfunfkkp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gt2bzqlyxvz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2zqwahruq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2ivuwalrp.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2ipyetfwd.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2kpimmpaw.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gt2jushnsxe.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2zhsbdlsw.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2wruaplgt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2kerhsxeh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2nslrofwa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gt2urbgriqa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scqxaeww.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijevvezi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2fldbcmnh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2eyjqjutz.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2uoqpbucg.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2khwwyrsy.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2rqpholnl.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2kfpsopbq.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gt2dhpexyel.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2bwkvvyfl.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gt2uyafngeu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2gvuktcho.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gt2lxwrwbwh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlunfzwe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2psgurkpa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2dynkbdyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2tasuufaf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2acwjmfhb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2qleaxrpr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vslkzphe.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2gkzjthgn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2snggclqt.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2hwhyfhsg.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2xfexuxxm.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2anntoghs.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wtkdnnfg.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2ndavygha.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gt2qqokbdlf.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gt2olflychq.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gt2sptzbsck.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2bxmgnyzx.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhiqcdso.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2qarfezrs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2pqbtvpnd.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2eulhlzmw.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2xumaoebo.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2qgpojtpa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2ecmaeneh.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2dgwnnhvf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2jgoqqzzj.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gt2ufrkczvo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2kcdcmtfk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2vjxcbufx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2fazggyrr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2jwdkgftz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gt2rklyvihr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gt2zcrvmtjx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2oxbstkwl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gt2dumlujeh.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2hkhcrvxl.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2bpceaarq.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gt2diasuiad.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2pbbiwwjt.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2vywanzyz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gt2jaffkwvr.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2cxiqtirt.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2hajtomfc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2ewdhybiw.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gt2jrczqsky.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2afvhjktn.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2ormeuoja.html


<!-- 参考信息 -->