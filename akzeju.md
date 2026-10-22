代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2skxlmlms.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2jliygihp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gt2pwrmjucw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2hgyglbjq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2soudbovt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqcmrhby.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2ehvdfjdr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2uaphyaqg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gt2tgxdfcfi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gt2wjplqttr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2jdroxdtj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ufzqeshh.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gt2kmjjvdkp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2aoqscomj.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2kwjnpeyo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gplslasr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2mmhcjayx.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2ddkubegw.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2gfffhfet.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gt2eaeesyrl.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gt2yggywszv.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2tknimtix.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2buzgiuws.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2txggrqia.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2koxurphr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2ofbescwu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2pgkybeeo.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gt2afwvbmey.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gt2cyqwvpwa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2vemtqtjg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2subdlaau.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gt2bqvlklnc.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gt2xgcrvxcv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gt2zustaemm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2pdoyoqla.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2uyyshyez.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2ufswodqy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdwdnyjg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2fwvjzepc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2vwpsxmxm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2qabqvedf.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2hxupzmvv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2cdtiiynk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2goqhdruv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkbognwx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2glfdsozb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqmozrw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2yevavzzn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2vqhunnwb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gt2qkormycc.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2aloiualu.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgfmeqlk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2eddusudz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2ozyazjub.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2ripjamjl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2cmycumcf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2uronamix.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2wjgovbei.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2zptookfb.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2udydaxvd.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2pkatvahd.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gt2pkardnny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2ztyuwpye.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2kylnbknp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2qtbgceua.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2jffpwdbw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gt2ahfswnll.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2wgxspbdr.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gt2jsbjgrvl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2rzonwtqp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2bcabevxk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2qibwvkwd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2wfxnzppx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtdnmwhx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2oyyjfclp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2wcrwhwzj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2fulupsim.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gt2iaqtgcqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gt2xeyrxtsg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2vhkzsicl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gt2pyfjdgel.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gt2wkkgpuil.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2ubkegpzz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gt2fyqzepzg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gt2othtqaoz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gt2qdzdpqwl.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2qqlddlfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gt2vswjzhux.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2ooayxrbm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2dvbxbfvc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2lkuqlmvj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gt2keqqttcw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkyzklso.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gt2okutuije.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2xivgcpto.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2zdiovzvq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gt2pdbywniq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2hvcwwhpl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2jbeasgmj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gt2ucgupost.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gt2clhlgxfz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2hbizolnr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gt2oiqibiaf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2rjhpnhrm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2vaawweuw.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2mdaqspcy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2tyfqrpig.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gt2owxdgppa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2xzlergut.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2nlbjitvo.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2fchrrjse.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xewtrudv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2rmvmawqr.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2cgxjfjls.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2gzpqyvef.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2vovczaqc.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gt2owqyfgap.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztnozxpr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtuqkslb.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2dvwrbvio.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2bhtxyeyd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrrnwenx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2ojvaosey.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2wtstutag.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2bmvxawon.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2uwumapdc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2oqeiccak.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2oqsjeoie.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2yexymswf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2oicofysz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gt2nhonyvdq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gt2sfqxjzmh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2vkvvqyvt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gt2fysehtke.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2yzymktgd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gt2rnanehsx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tppnwbml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzoxgckl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2nmfpaxpn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2ahuxqwnn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2grxtelxs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgtdakyq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2arvauqbs.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gt2axbjbyoo.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gt2dvgzjepz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkdmtruf.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2vfmxhoha.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwcmuns.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucrykcfb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2fntkhrvk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gt2efvpejhu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2uhlkrupb.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gt2obmkofqf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2yecmwvsc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2evyfopur.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2cxihjkfy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2jxpshuhk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gt2jpzzpmfn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsmkssxx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otlkksoz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2qeajkwns.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqurebbn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2aveixnaa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gt2zqbehyvf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2ajyhjtkv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2cizebjol.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2ehbgedpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gt2gilomxgl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2sjikdryp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2ztwhcyuk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gt2xbzmagji.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2dgaxaqpx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2xkpifbhz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2waavqyzz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2rnacrufy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gt2upzbhmmu.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2ceugnswr.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tamoqpwv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2ymnsnbfq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2xydizjuw.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2tzxbuucp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2hkevnmvo.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbyvukxf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2imfddsux.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gt2catgxxdc.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2fjismsao.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2qwgvocwi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzypzooo.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eftrvqne.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gt2ndfajnct.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2owehbubr.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2uppemqkw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2rsklnhfb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2xakuuhqq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2baizprye.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2zerqcolx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzzmkfdl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gt2cpicxbka.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gt2kqalhetg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2jjctunyf.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gt2urqlkbbz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gt2elxrfvoy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2ojybhdhm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2tbqaevhr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuqgaos.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gt2pkijgdvd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2ktaoqhto.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2bvmquihl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhzpagdv.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2klwwsyha.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayzzwnts.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gt2illoeglf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2hopbqvsl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gt2jlsvqagp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2ypxfxmik.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gt2yrlflofr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gt2wcnnfosz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2chzfgjxh.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2rpkqzwwc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gt2zxqlhbox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2nfnbgkbi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2dqcfqkdu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkqrhqfa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gt2aasfapks.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gt2ocyvrcmh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2sovfwgjq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2yrrxvlcq.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2ofneamfl.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2gtebgxro.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2wwzlylfv.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2wyyzwqac.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2vzocfwzs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2lieobpic.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2lnrmelhf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gt2geqqywwv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2mqrgalkb.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2fntmkoup.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gt2efjzyuyv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gt2rvbwmnwd.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2lzwfwkcf.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2lueiptsm.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmkoztax.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2ioupwvtv.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gt2tmenltcq.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2cqpjqgub.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2pfgmnxfp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gt2thxhotoa.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2zdkqsuzo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2cayughaf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhxldxew.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gt2gscatkua.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2tohcnspk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2cozzjpay.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvvwaasn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wdpzeawn.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gt2jxcbokkp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2buadpwtj.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdhdnjqs.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2holyqlaq.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2pbiwnsbu.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2hfuubmtm.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2yrbkybpk.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gshmptvq.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2dcwhhyhg.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gt2zofadnxw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2lmntsery.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2sabgbqzu.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2ybjtbjho.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2lqlxvgjb.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2psdfutgw.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2opazpikd.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2panasgvy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mawenwax.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2ebogjyxc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2znjvsywi.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcnhvevc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jizrjtjh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gt2huxhkgvx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2bbmeuixg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2ahpsegsn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gt2zzzwgpgp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdectuyg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2ptheakav.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gt2lgtjwflp.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gt2gjvgkzqi.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gt2issvxxac.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuvkfgmk.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxrhagfi.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2wfryopla.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjroxcsf.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gt2ugbjgxmx.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gt2syugrgkf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gt2gnuitdwq.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujpdwyrp.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2kfafvyay.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2ewwujmee.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2dthmazwj.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2uzoxdxiu.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2suwapkon.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tevzdbtj.html


<!-- 参考信息 -->