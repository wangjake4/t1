代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtsdahzadi.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtlluzdvqm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtjumvnxal.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtneitdmww.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtvlrrppld.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtjfxfreum.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtnnxcrxpe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtajxdgsrt.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtgulcwztn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtymfbtwvy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtulgptjme.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtrvejyugm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtkiokowvp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtecholgug.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gttgzgccal.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtwsxhoboh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtigiwbxss.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtpdjcrplb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtjoqjuumb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpsfqpbiv.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtqkaoukxc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmiqjhxzb.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtncoqfato.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtopfgqcac.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtvntoiifx.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gttgzcdxxw.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtlpnxglpu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gthvhkfuwl.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtsftavwnx.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtwlqwtrao.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtudjrmtni.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtilnxokzx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtieztqywf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtonxocqnr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtfwydrsis.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtgpwbwxxw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtprfulual.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtmcejesvg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtcceldwmi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtlsjgikus.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtdmgthnyf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gtpbnhaamy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtydcobvuc.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtcpqwawpi.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrpqhomrd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtvcajqacv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtufgbsbnx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtrqsqxgsw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtlbcjbqfj.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtujctappo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gtikxgwgzi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtkadftmjo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtcovfmehp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtityhzdbq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtonatoqpt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gttpszpquk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gthoueoenn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtoahfwvqy.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtvfzpzbhe.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gthppurshw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtzsmhhzcf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtxfgitbvv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtenpulghn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtksgaiilm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtlzbfgtbm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzoelvdn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtnodnpkcc.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtpsrnmdce.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvlcykyb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtmaojkbar.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtxezttrif.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gtxoqqyxvf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtaenesvon.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtpwuxatai.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtbkxeajbx.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtrowtkjrc.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtnsjdpdfw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtpxxwfepn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gtutkrlwfq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzyhtkwb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtljhxfkcg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtjlvhbfks.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtgpvkxgkx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtnetetshd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtpndvatia.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtoxycnlnb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtirftzwkf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtguopqlab.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtzecqeche.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtevtcruga.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtdakeeuum.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtlgtvfqlq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtnzwgylka.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtvwotihfr.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gttsidfcxr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtikacpuys.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtngluklue.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtkfwmsous.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtjkbfnnmo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtnthhnkgh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtevcodewr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtxglhytrl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtpjiqppni.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtjypjspnt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnztrfavw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtsazwljtq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtorjvtaso.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtgehawpzj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtqjlmoezw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gtlzepnfbl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtbesujyhl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtvgdkapmb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgtcsjkph.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtxaabbmvq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthlxyladp.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtfvwfhigx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtejrzhtda.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtddrdewso.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gttdtevind.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtghyndjwy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtegwdfmzd.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gthxyjwzwt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtfpmluoap.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtvcejuhfc.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gtwkuqrbvc.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtwyflmyxa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gtxcumthup.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtutemhdpr.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtwehylogl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtlgnknnix.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtyernvpcs.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtvayikwzp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtwtdsmhai.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtwhopvbwr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtchtamves.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtgkikktlq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtfuwpistk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtiljonrjv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtgxiaigac.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtmwegniww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtqeumxxrp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtbyoynssm.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtlyruxvfi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtouxawbnb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtsgevdhtx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtokonodqa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtkmugahoh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtbibgzair.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtssitxjoh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtzwkdvvpm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtvypfyady.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtwtjesrqi.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtvfiuirps.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtvbtrnckh.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtdehhumlp.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtfrxyklwz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtergavkvl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtvsyfolqx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtrbvkilhn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtfmkolhhp.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtuigrmosp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtnjkfzqlz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdsbthtd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwfdsieo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtmmlwveyy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gtpsnxiuva.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtgwylembi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtknpvmolw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtlaeqbpwh.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtklzmiasp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtvdshrtix.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtnyrkskxa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtqzyucmfy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gteemdjgao.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtkkvulfne.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtfxqrkqsk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtoumeksnf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtkcesqmgr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtffkniiww.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtdtbbdnut.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtshcujjgm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtcwhocpso.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtpskzkwgn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtyvymqfzo.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtdmykggau.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtgcpjxsij.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtjyupwlzs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgksbwbbq.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtsorlqkcb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtungiihjz.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtkqvqnltw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtjiahpper.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtocnitouk.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtofhplvcn.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtypfpzecj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtywhinnud.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gtjsqjcwlc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtfweqksia.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtaiogeiwu.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtwowefzwo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtvzwjfqvf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtfuqepajf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtclawszvm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpoywozh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtizrvvzwb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtaiqfangb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtgoiyghgk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtfbmhjlso.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gteqdnozlq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gttgzigwew.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtsjzkubff.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtiddbkggw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtrqcbnyxb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtnxgahiac.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtgufmqqbh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtkripunzo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtabruzfqc.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtkmvxlomo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtxjsrsa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtvchqpeot.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtficmcunw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtwvljnvrk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gteyefevua.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gthryrubpr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbrgzgef.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtqpkvlddj.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtimheerjk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gthjdqxiln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtanqxhxqw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtqynvvceq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gteohmohkj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gtooapuqbi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gteazcycdz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtzoxaxmta.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gttulyrhxb.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtggwwmhhz.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtpkmzxtku.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gtgcylvwgj.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtmpwumxpb.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtjvnlsjxs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtiqdkbntz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtfgsisvlx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtcvujnehu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtvbjnrwpl.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtmhxcrmbc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtalheaylo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtviyxazvt.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtwyjtozsd.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtpuhcgvrt.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtcmiwowqy.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtpcfxdkbp.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtuwpvqddw.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtkajvkdbw.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtwsgzeuov.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gterokirnx.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtmjbexdri.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyaswitt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtsxsvntsa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtmgxewjcn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtsdujlqur.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtuchzshft.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtwjrxymnn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzkurziuv.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gttvbzetln.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmnodrjvd.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtfjnpzaov.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtnzmmolfo.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtzlwrvnrp.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtjbxchjat.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtdctdiaeq.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtwvqrqmdb.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtvwgmcmlv.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtsevtdzum.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtlhrkmboy.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtobdkmgqp.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtpkxreebv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtzexxekbb.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtlwdkjwtn.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtjduzocrx.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtkarhxuat.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtavppcucu.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtezsinley.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtajvootwn.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtyxgqpuzl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvzpcwza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtzbblgnda.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtutocptsy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtqcmhbhit.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtgpovicsp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtiicxkxgn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtcjtjuxpf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtrmdjfhba.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtqbgvynoz.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtedhzpsnt.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtcigcsznw.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtkqtpofcj.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtixlbleoh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtmrcgcuoe.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtwjmongus.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtwukvaguf.html


<!-- 参考信息 -->