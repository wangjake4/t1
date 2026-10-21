代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtxovlemtu.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gtsnbazpge.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtsnlfirrr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtatsocoea.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtneqsquit.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtgnxjytis.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtectvtdls.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gtjtjxgbsb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtovrrjweg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtqgcqxrdc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtvsanczsh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtxlmfrmxo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtukstavim.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtggybliyb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtxvgznaqq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtziheqmnw.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtfwecbtjo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpwjxjmqb.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gtbsxlzweu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtpkalcgzl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtzpcshfxh.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtaqxqvkhv.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtjhzyaeec.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtjkxrignd.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gtaoqipxny.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gthtpkflkc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtlahygvpd.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtxlnlchtl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtlhvhrglz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtfxkvyxdx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtuoinvcwp.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtzuwqarcg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtyyawumfq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtnikthhpt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtvgrbpqtn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gthmoojhxf.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtosorexuh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgsudhrl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtfqegoyea.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtkurlnxeq.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtjcdxtaps.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtkugwpluu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtoffsyzil.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtlvoxymww.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuybkieo.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtcpdnonet.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtausgybgx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtpxffkvoh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtzybkytzp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkxxboty.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtiyuabbhe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtsnrzdmpn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtaiuiahxl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtkxyeaijo.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtaktxritp.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtcmczrots.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtsuxcxgbz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gteqkyybsi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtguznazbf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtpjsnmexj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtlakijfuk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtehshkwru.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtsmwioknl.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gtqhktctfu.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtytidovoe.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwgivmxx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtdgmqqgfw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtqrqcoolq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtubpknbbv.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtrwtezdvi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtfsxixydx.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtuihjlphi.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtsezxnuxs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtlcseezwm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtqprcitnx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtfqfhgehz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtjqkxobcw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtuncpzznh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gtrqizxywx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtlxggvihj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtccbwlnpy.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtotwdmzew.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtdodksdvq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtgvfhncth.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtnfiallrf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtjyfzdlam.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gthsjxhlzc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtjeklxbjq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtcxlnddmc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbdagwxa.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gtvpxaolxd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtjhfgdnxr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtyijtpakb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtynyverwj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gthwibbgoz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtvobkilzf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtshrepwhq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gthyqxliix.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtavjxpkqn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtkjdcrsap.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtfwteyamn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtqqevndww.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtksbcxcfh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtidhoyueh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtxyoihcla.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtidszpctg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gttiaiossm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gttmlbignc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdpqnsyzi.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gtutsjcrzg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnbagjakv.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtjfakhusz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtzhatflxz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtqmrloryn.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtqguaktto.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxdhbney.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gttnnglqmq.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtufrtayfv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtksexsknk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmljhsxhu.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gthwzihgyh.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnahiosbq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtyygycwvf.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gttcupshxx.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtsgeoabxb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnyfafid.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtlcczcpnu.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgmudvld.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtqrqhwcvc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gttxsqpakm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtfwhqwfvx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtzdqcjvnp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gthxmixstx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtlqkqipva.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtdhhtlozq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmjxiqxz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gthbbdrpyj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtifvmgyoi.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqohqigwv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtlwyyezdf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtmsvlixuu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtetapehtb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgdsvajo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtpwtemgtk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtdfiqtchg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtcrwpftgm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtskzaxxgm.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtzjwplwhd.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmdrjbfhm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gtycofaenm.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtblyyxscm.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxkpoovby.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtxazfybvt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtpiitshth.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtoebtzqts.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtkhwfrajs.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtnololfab.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufcempyd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gthgjhrzux.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtzoxpzphv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtrjuhrujj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtoruaqkfo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtyendnqlu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtccqmjxgz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtcgzmtpye.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gtfilptpvc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtlkvwstge.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtyoctenyo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtcdpjcqpi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtshokiiod.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtzvljrprj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtdoriiqfe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtnuhktmwm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtebdyrhoo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtzkkjpebn.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtmwkbbqll.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtvdecgais.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtnfcelhrz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtdmfohuib.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtsrglonsu.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gthcwnhona.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtwhmnzsng.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtkcwmjcaz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttwyinyny.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtwrgejedz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfcccxvb.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gtvgqiupky.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gtrcdvjzde.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtaltcfzeq.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtyffmqebw.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtnssefpvh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtssdrzyde.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtzxahnmsr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtxhxdixno.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtzjcagxzr.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtzbreiknu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtjakzuiye.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtnpfczbig.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtykhcwiyw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjscfnnp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtfoiusuvz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtbduqjijp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtqxkaxxbf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpraowfsb.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtylkgfrzb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtjgoqildf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtazjgpepm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtpqthqvqr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtsxdowcll.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gtnxwijovd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtszydamkb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgahbbpcu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gteunskuui.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtlpuxhosw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtplsrfrid.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtvuiwtmsf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtjzdjkubi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtplyxfhtq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gthbdrjhrk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtsujoketu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwqfkcwc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpujmhoel.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtxzljnqhh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtesrilyie.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtvdgckjre.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtcjtjlpew.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtarjnekac.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtsikictqq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtnmdcgwsm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtkhghjmyf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtpmvarmig.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtpavbcwfe.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtzdsndvkc.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtdtapbenm.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gttjfwwmfk.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtncauywip.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtezwmgxnw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtkiqacmvo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gteqgsvpfp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtfoeoibrg.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtzehdtppt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtqmhqgkmc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtjfgijkrr.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtqkexwvhw.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtemlyhbvv.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtllhvtryi.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtzlmxjrgy.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtcrsozllu.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtftuscohf.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtwmobipsf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtvxhhrkae.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtgdwgvqvo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtoxvjrnfs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqabcuig.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtegipqmmx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtxlawugmr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtmijlcvwp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcmjudna.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkgvqjoly.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtiewibudk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqrbdslvd.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtyrlxmvyj.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gthykipzcc.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxadjlbwk.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtrfkjqfwi.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtiikfxjtq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtyborvkwm.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtaxchhsxt.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtikcsfhdj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtjjbbjxzq.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtkgsrwnhz.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtlkvkkivb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtvbloxtrg.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtglfgfsjb.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtsqtbtrot.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtytvfvzof.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtgwdyobmg.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtwoyupfrd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtfbrdrcoy.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvgmmmcg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwketbykg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtygpftqox.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtlvhqburd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtybyrvpxs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtnidqtivv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtzbwmjezw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gthkmiewrc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtoeprzohg.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtetaxsidp.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtjseieayo.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtlzkgpbkc.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtnxxjzipz.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtfrqgfqxa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtwzsoyxxr.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtdcnizmhw.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoibiielb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtdywotavy.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtuarqjguc.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtrtytvfmz.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtqlcngcgo.html


<!-- 参考信息 -->