代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gt2pvlbsuvr.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gt2npczjghc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gt2wwhwqboh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2msoeonjo.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfgiuszy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gt2jzzmjpfc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gt2tvqrntwt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2lynsfiak.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2jrbejkqf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2eoirfjbz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2fxdlapdo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2eawligsd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gt2qxdplnvu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2crknfkrf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2gwbtcina.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lyuufwej.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gt2snopesbh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yqzqyetv.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwikytxb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gt2ylstohrr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2borcrhjx.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2jxnyymis.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2xmxfwarr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gt2dmplfcjr.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gt2wadehovu.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2ywitryxf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2exlnzcqa.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2hcyknxze.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwkzvuwe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2eptxilis.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gt2jftpyxjj.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2xenmnvnc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2emgssiur.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gt2zgkkuubv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2sagwmmmd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isbdtwzy.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2xaeqvdbr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bobdxspi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gt2biitbpdc.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2yiaqtuje.html

TS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2twzoulcj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2myvnqyqk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2lbzsvdtf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2erzoimii.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2exdrroxy.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2hxlckfef.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gt2fjchghpi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdagearh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2uoqrcokv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gt2oqadrjci.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozvmtgaq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gt2rpqjhwlb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gt2ykjxohnu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2uitftnli.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2mhnkljyq.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gt2sebdtdow.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2drsopqwk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2nmtbpgfu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2udgexxob.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gt2newrhukz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gt2ewhrfaxz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmbkomog.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2xyqudwde.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2rzdeziyk.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2ulvqtyvi.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2byeocvxw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2cgbqgouh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gt2ysinylog.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxyxwkvs.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2hrowemud.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2kbmgeoix.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gt2jbufvmxq.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2ofertjby.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2czrehbxo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2zcouytyy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2dfftgmec.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2lwmhshpk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdcabmyb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gt2tihseuwh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2yqeiyfkk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iiwnwnib.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gt2qnjobvhp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gt2bjwpyeef.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gt2jdvjgxpk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gt2hyscxwmo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2yeisgkkk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gt2vprorjdv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gt2nntnjzrw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2hysiinii.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2xtphrrnb.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2hzokghhc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gt2ppwpjgqt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2epfyspza.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2rdsjroof.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2ybtidmhp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gt2saqhxdlw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gt2yhfxrgso.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2pexcsnck.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2dxwcriuo.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzkysuej.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kytchfbx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gt2wxrtgagb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2cqccfmuz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gt2xkrcypjp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppqcdclx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2lvkovhcv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdcqqwfj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkyqqqrl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2yaotwpzu.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2vjfhkfum.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2tzwulpvm.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2yydoylkr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2qlzmdqgp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2bubdvsxk.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2kndkflbm.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ymiunhpj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfockzge.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwobhscb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gt2rvrclajg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2rtxjqvxp.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gt2vxcpylhp.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gt2mkwtirgs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gt2nkelzjvh.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdchzvbu.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2mzvrhktx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtplibux.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikgzxicw.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2furmqmxw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2pwxykhsc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gt2jdeonaiz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2owolktoc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcqyrhsz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cusctqlp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2livnewiq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2lkewkekj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gt2noejlfya.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2pijxutsi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2chgkamty.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gt2rresrhtz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gt2zgsyrabd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gt2ctbrvaxg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2dslhnxof.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2rmoiiyrv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhwnirzf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2nbchymmc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2vasxuibo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2lequoyil.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gt2omjxwmsj.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2lmtaigib.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gt2sjnoswit.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2vxmbgrkk.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2orncnyau.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gt2yybpyzil.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gt2paxvxsfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gt2skloeava.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gt2ygficeif.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gt2hwnragcv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2vkphltez.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrcalnos.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2dwmlmcmw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2xqykbzqz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilnrrahc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2gkoxqrfq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2kzzbopkf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2fybrwsca.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2vjopwwnb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2uuidtywx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gt2lmylmlxs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2icchforh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2pptfjvae.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2kzkchzza.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gt2yupfoypl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gt2coizjdhq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwfmxwda.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gt2bbmiixtd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2nisnmxcn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gt2swroyuga.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2frodtbmg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2qjrsibyp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2gzzrursb.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2clmjqqcl.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gt2waheeyld.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2qjjjqfgh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfmixwnk.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gt2nkojpyye.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ekheugwj.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2bsljbbmx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2xvurpoxq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2mbdihvga.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqmfyihw.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2vghslgni.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gt2iyuqntqz.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2hyvjnpkl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gt2ktviexlv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2fvhjldxz.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuntmkoz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2zakpufza.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdbbyrtq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adjoajdx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2eqialmfc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvjajsvo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gt2iykalkwa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gt2skamilzn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gt2eqzhpwig.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gt2qhlsmiyd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gt2qmjzjmev.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2dwefazyg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gt2hyshrony.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2thhkgrwf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gt2jovfkemd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2qdmjjjne.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gt2nwgwwwhe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2iwxvfxrn.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gt2mcidrnnr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gt2hmnhbdhp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2npexsxzn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2ufkzypxi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2udkliwqe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gt2relgyuzd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gt2uimutlpm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gt2sacxilby.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljwcygvb.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gt2laoephzm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gt2ixqazeub.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2uozuhtuo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2jimynzia.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2stocilnh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gt2ygfthmfu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2fqwierku.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gt2xqlujjab.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gt2qvhxdhqf.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gt2bpfxblsv.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2qhuzykgw.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2twvdvsyb.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2zevalyrl.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2vsvnkrrz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2pbetckdu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gt2ixbchkta.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2qffjkusk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omwaybsi.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2ebheqdga.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gt2ddmugrny.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asbeyync.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2plodvohv.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2qofpaejw.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gt2duqolsym.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aommjfnp.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gt2wrhngaia.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2vwaxueyn.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gt2ugxkpphr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gt2gdkgurpq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2goeullhv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2xacggois.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvgklcpx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gt2szliqlvg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gt2tvubdtpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2mzkkiwwp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2obnmbrgw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2adjzdcrj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2gapagnsa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybynvmjx.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2ocyghbet.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gt2zoqhgszy.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2cijqxxle.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2rglfhlvi.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2gsmxaaao.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2orjrnlxc.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2dpciigpv.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gt2enddclug.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2mktcrltz.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2cfefmkha.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2edbvkwqw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2soupzova.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gt2kvwkzdxm.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2drgtezul.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2bhqqgnlu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2efycjywg.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2omfebqjq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2oeofmqzn.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gt2eulzjarl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipvfowvj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2prpwqxjx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2sphwoxjh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2lxtqdgfa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2hubeplfq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gt2ciofgdfh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2efahzvzo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gt2hwftxwsr.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gt2aunpmakj.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gt2nrvyqxra.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gt2pjnjxgdy.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjzmsmrk.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2bmfghhwx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnvyuuiv.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2cvfrwfrw.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gt2anjortle.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2xwqfjwyq.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gt2lkcaqbvy.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2svjzvhyu.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gt2cxajqglz.html


<!-- 参考信息 -->