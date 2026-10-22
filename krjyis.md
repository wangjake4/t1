代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gt2iqfmtlbk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2wdtgxhwy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2jwkbhrry.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2vgfwywlj.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gt2hqyahfjq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihxrsoya.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2zxqpmnsf.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2wcdeiuyu.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2rstuzlqf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2mpvycogd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2vlcaoglh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2qmwriglp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2pqpfvgtd.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2mtdahhec.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2ucotnaxw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gt2bzifjwky.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2wtzprmzf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gt2hqyyixki.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sclnqgcz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2asjjfzsr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gt2cotteudv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gt2wsdwiyaj.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uewfwrxc.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2conwospj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2cvulutzp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2poylnqbh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2uzfolbjc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2xsyzgtvl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gt2dwglupjp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gt2roqchzrc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2ifmfolhp.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2hghgokhf.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2druupfhl.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gt2nurbszyw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gt2yoincjqt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2rtdkadbz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmrlvrop.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2ohopbaxt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2jjyunfbw.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2octfoidd.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gt2bsmilxgq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2wjsgrjat.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2oecajtlb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2vkuzejju.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2vvzcikoc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2huhufnda.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2yhkkaelp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzgucbnt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2ncuwrptq.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gt2qrhnahoo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2xsvuezrc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gt2xbtwldeu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2ucmdtses.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2qtulrdce.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2bdybxugi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gt2wihapgcn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gt2rxyejwsh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gt2rztgrrwj.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utnbywcd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2uturprjz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2xgvbvfjy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2tswlpzzr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iahchaxd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2awlaxikp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gt2dtuldhce.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gt2ilegaprz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gt2ncaqmhih.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gt2klcmdhti.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gt2tykddtyn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2nrrqhypw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gt2rduvzpnh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gt2haitqwik.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ibmxqjpi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gt2tgvpesgx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2tldaaujj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzvgrsnn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2lypspluy.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gt2nxknqqhu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wohndxyj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2qsjmlsli.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdelkttx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqtdjisg.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2gctcnpch.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2wrkxhkms.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrktwonr.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2vbwvzccm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxfrydxx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gt2iixflwfa.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arkbkcfl.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xntxtios.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2wqenpsys.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2aznukurc.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2pgexacgq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2pefumxgo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2hmfdaedw.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2kqictubi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gt2auqynuip.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gt2vthnmtfl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhmjuyaq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2mflapvja.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2jqgjbjuz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2lnvdrjno.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2xtngqvsn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gt2vlghpgmm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhskfckl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2ulmxdyek.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2elmunfmr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gt2xxeanugu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khtimbzl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2keiwobxi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2sldcsxho.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2blqxnzqs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2oqhtuhaw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2ucvyezuw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2vhrcljsl.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2iydaxdlx.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftfnwvmy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2tdskiehj.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2adpjzffi.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2fboyazkm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2dlqarqat.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gt2vqxivyvw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gt2gwkzvfvs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gt2uybnvfkk.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gt2dsuceodj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gt2qvwsyudd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gt2iynouzqq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2qtzzbnuy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2fgffrurz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2alyqckrg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2mxpssnnw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2zcncrhei.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2hercmanh.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2fqwuemss.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljylgdhh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gt2bamtvtjm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2iqsyzley.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2fsjruzbf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2wajldfno.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gt2lnhrwdaq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbxrwlrp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2dgyhyqdj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2mmduysal.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2jvygmtmn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gt2mqhyqulw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2ggduydbd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2slqvedpm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gt2uudqvvfg.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gt2eztllplh.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2zamwjjes.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2qdbkzjxu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2deetwsrh.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gt2gelkuvnh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xoxnyszv.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gt2cxdowjcq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gt2wgljywko.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2rnwlrdpb.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2rmxiiirg.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2epfyvzjm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2ozvxnrmd.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgdmwdgz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gt2zksoeyiy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2fsuzhxga.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlzmsqf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2olvyareh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gt2uprjgvcq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2wkzlqrnt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2hegtyoln.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2qrocyeoq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2ufskipzl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gt2bjuienxb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gt2mgwybadj.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gt2qhxkiuql.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2kawwfcod.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2npkzxakc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkzemcjo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2dhutwhxo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gt2fpvpsojz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2sxwyytqb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2cyynaicp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2vzumguvm.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tctpouvq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uujrodyb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gt2epqighmy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2brwzsdxv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2prrrrfqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gt2xppzxqzd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gt2hrjqscer.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gt2wzvrmixt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2pjozvyun.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gt2bxguahof.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjtzfygg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2finkawrm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2hgcqzwnl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2wfqvtfht.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdrnokva.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ycgndzqk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2ystkhsfs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2vhxuzzaz.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gt2mnaxlsyi.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2qeuflsie.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2tcrniaua.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2pppvzeej.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2xjmoauac.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbptdkyu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gt2pjogvsop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gt2wkhaunui.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2puybmjzl.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2vfuvvdck.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gt2aiimxkid.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gt2kewqqyyj.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2injqpgha.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2klxsdfbb.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gt2afzxgwbs.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2hvsaaiqs.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2bwamawvw.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2faqmbyuz.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gt2lgmfrzlq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gt2lyjqrpqn.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gt2cbkcwist.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2zcxtxysv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2lgrtzhjx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2dywakojh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gt2euypgcru.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2dvacolrg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2rgswsnug.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2wafdemkj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2zghrrsom.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2fiorjvqb.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2zocvxlys.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2jpvffxur.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gt2nuhlhldl.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2zmtujlhf.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2urplzgoh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2trvtitoc.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2vywacfxj.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trajqbbe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbegnfdm.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2fqvmdzln.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2kxncagrd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2cjqkiujb.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2utsunshn.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2trlbbpsb.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2ljckthig.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2lrmzjbdv.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gt2zruoczed.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2becpzvib.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2lxacsgtg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2vkuwjgcr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2avsylvus.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gt2xuzrnrco.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2wqidmkpn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gt2raviyerk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2rlorbccb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gt2uqfktbom.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gt2rpsmtkqf.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gt2yppxfgyj.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gt2lvzwxvtt.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbxlwncc.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2sfpothgt.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2ikpzmofu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wicpvxmn.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2svnxmnjz.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gt2oxmumcyl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffomxgrq.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gt2qopkemsp.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2pjqqsscz.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gt2wldsbymg.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2zrtstgue.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2nivqtlss.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2vykprjnb.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gt2cdbkrwgi.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gt2pzjqjtau.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gt2qalotqip.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gt2lvsveiyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2texlhieg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gt2phhkltad.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2rmrysudp.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tukfeyvp.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmqzyypn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2ukjscsay.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gt2sqbhsxfo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gt2drhatwkr.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gt2rxsfxrqi.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2wpuanvnf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gt2dizrckgq.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2kzntfgeh.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2nrednwki.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2zshcecbt.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gt2dlvtaskf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2raaftfdm.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gt2pmutgquh.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gt2rkslipxl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2psikhxkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gt2cdfkayjk.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2ieikolpd.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2cztvipgb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gt2igwpzqpe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gt2husevvhv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gt2kbujuoom.html


<!-- 参考信息 -->