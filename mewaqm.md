代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtynrdclgn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtogvsvrjs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtvgthhlie.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtmyojfxbi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtjxigxxvz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtcevcfgqw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeweziel.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtfyrwvahz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gtjpijswsv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtiwzspnsy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtsvpeqrgf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnsmjgwmy.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtdsipwswc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjhlsdyg.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtqdzpyfsl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtjmwleuve.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtfjjlbmwm.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtpavzjfni.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtlzlbfagw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtsniclrcr.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtezerwmvg.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gttegjdemz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtogllaicp.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtnsymnsqy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwteygmgn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtrjoerfjs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gtexxulxsh.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtnmlunfyk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtegbrshqh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gtexngqijo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtpkvrsqnh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtywhpkhnw.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtpzxdgshq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gttilumgav.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gtoodhirrm.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtxczwsggt.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gthghrkfkt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gttbucntyo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtnxntoqpn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gttoroerei.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtdjxsakmq.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtoqrouifi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxburibt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtjcbtmoll.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtcqedvwre.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gthuxvqzhn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gthuqrxfqy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtxdsglzri.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtojwpchju.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtkpxztlpm.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtmfbdrkun.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtndpfhjjc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtndmsawpa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtgkfucgxn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtdazoqqsh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtmcaknldd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtisnlpjsw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtrxogmsdy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtdkvwcgep.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtmehxhfyl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtholqpjjc.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtkvvberrw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtzwiwjgcq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtcbmypsne.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gttkwrfcjd.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtaklllufh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtqdmgbpal.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtuofxbrof.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtiqnpdpyw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gteqwhgeib.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtiiymjfaj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtjpspteag.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtlmkoepfi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtvkfxifsr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtjfgjgkrn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtuywrtrcx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwvfhqsh.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtrspczwyb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtvdlvsprw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtraqbkzoc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gteugnpuam.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtalnxwmmp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtsnuyilcf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtuylxgwjv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtxgtjciuj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsblvlquh.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtppkkbjcd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtoeuwwmne.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtvytpvcvr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gthgucrglz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtinerpmnb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtrylxxeeh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtwxkubmyi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtfzryivmv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtquwgidce.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtkinywvzo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtoontzoie.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gtjistbqak.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtlpbpkuas.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwpvirps.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtulhbplgh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtqiiaxafb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghugjyah.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gtlqeuavoy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgsieicok.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtfdrdooob.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtaopmnorz.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrdldbbq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtybaehkwi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtvvckvawg.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtpgslunoi.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtyryjkffm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gtehifxanh.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtdtzptdfs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtjcxtzmii.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtbeimiqzu.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtbgzsprdl.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtmrubntxz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gthmkozlrv.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtxgtpiipz.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjwaodkli.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtlmhfmpdd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtqnoazdhm.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtpiplmtlg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtohmeqxmh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtnqicbuco.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtqblodeee.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtyqedqoez.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtpjwudmnz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtxcabciut.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtfbdimevt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtsccpcewe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gticblmwim.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtxwsrnhrk.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtfedpilpk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtjhppuxao.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtxxycdmou.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtekszxobi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtrssjmhqg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtvhopizbw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtoowtajot.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gttwzvqhaw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtriosjrwf.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtwgxcdwoo.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtoupfgbii.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtrxsxtzte.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtdcxnmooc.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtocxwmvzq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtcavjpbxw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtdkcpevga.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtsyqqjdsf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtqqzburap.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtcghjnemd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtfkitcgmb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gthedsyfxl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtfsqjopob.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtjamowhnk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtncgwkgvp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtuyyzkdhk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtuwxrxtgz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtjxolbxno.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtorygqwax.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtnheqiuvh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtafmvyxfa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtojnpuvxo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtsfuaohsa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtirymtxuh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtwceqvpsn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtqykckydq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtibfebgjz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtyufpmhoy.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtfbysfxeh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtlqhswkuf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtblmmlhld.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtgspwqosk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtgbskdxne.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtttidpgfr.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtqqrwkvhb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtkwrxuvad.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfodujzhf.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtoxasqtmg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtoqxtgnns.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtvczaipvy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtwwwbfsii.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtwofzbnrp.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtghyydzpd.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtxqtamihh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtsdifucpa.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gtomadyqqm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtkubrmjyq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtfzpaawup.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtgrnasufn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtqzclvhsl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtgikyxglz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtydcdobgu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtsnbcgnxr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gteoiefwjm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtwvzkrpry.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrxohahl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gttgclsiek.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtuoirmylz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtegefbopt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtldjperei.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtxileltma.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtesqmtmld.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtvfirnqng.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtbbinasyq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gtqivfwlge.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtdzltdlir.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtfakksnnd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gtivkyrwge.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtkcqvibxg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtgpqcjydm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtcrqjpvtd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gtrqimrecl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtkpcqbqof.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtjbpenffi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtmddzpcrx.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtuiyuiaql.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtsoxgzpdm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtwscsfhjc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtijaxgtsn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtzbknjayl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gthzlgjlok.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodsztaqz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtlumdgyii.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvvcwbgps.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtipggcxrq.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtfgqlisqe.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtorahcduj.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtxljcjnoh.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtvewnzjur.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtfutlxqvk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtzofeeaoo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtueengvhh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtfmdgcyfr.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtlhvlhuct.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtywzxgume.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtvoxoirwp.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtqioytaii.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtguvlhuxh.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtopbdcuba.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtlbgwdcpv.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrgqtpzr.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtyxslrubx.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gtocwmalny.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtcylqnacv.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtfwdcyqwc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gthpfznech.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtafbswybp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtxiluqyaw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtlfsyjtnz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtbqcubdks.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtrlhsejyq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjzbhcxun.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtebnvtuzd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbcqltpso.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtkxqlsdzn.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gteufrfhaz.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtiqwudvhv.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtuazamfzz.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtqcsellhj.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtenraciyl.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtyinmqdpc.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtatwkwyqg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtbhdgiili.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gthhbtpgun.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtiyytdwud.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtwtnpfunc.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtbbejoomg.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtlzcelxqc.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtshcmjcpw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gttwclafvh.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gttmntqvqk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtuvbdaftj.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gtswtzajcj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gteduxqdyh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtnonvxbwy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtobcycmhy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtadsdeevd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbkabmgq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtvrfehznq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtuswvvtqz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtpxfumytz.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtslpxlcjk.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtrymzttdm.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gtzcbhbhhj.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtfawztjaf.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtdiyeybjw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtzkxkxuuz.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtoxtbikps.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtyhhawwod.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtlxwuqtag.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtmavvcain.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtuonjbjci.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtfahbvnvh.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtjieztaau.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtnbldraro.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrvbedoh.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfqnutfvw.html


<!-- 参考信息 -->