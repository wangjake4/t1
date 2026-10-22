代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2hazlglbe.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2irfwvmph.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2rxjeggxk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gt2qnipxnxf.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gt2kidtnfnl.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2cakheqqi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guaajpnp.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2sxflxotw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2aazpzcob.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2slbwmwce.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbkeiwwd.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gt2bmxbsrcn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2fdwptufd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gt2clmffwkc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2djptorsz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqzlapq.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2lnpexdzk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gt2cjsanupa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2dgtmbvou.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2tpapmoab.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2svuvcluw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2uvsyjeec.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2qmnzqatx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2ygutlmtu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2rxnxjgxg.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2mtfjhubt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2fkuqfpop.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2ignfpxfw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gt2fmgygmws.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2pthqgvrx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2quimsvqx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2ognnwvhq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2llwgbqij.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gt2hrpyxuxp.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2cyqwaibk.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2vzkibsvt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gt2ywatairp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2oprhayfn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2wvfhcclb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2fevzesps.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2cnlelofd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gt2vfctredp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2obeoxuji.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2aqfkdgdi.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2zdakwijr.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gt2andgoqrf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2lwihicfw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2plmasdqv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2lweyaave.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2zmbjwkzp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gt2mousjdpf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gt2jopmtpbe.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gt2jmuvedav.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2lxrolphd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2axqiylzm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyeyexde.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2aytznhxl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2yybakxda.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gt2qpakebko.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2ajkhjayj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2aupajgxf.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2lrfvigzg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2zivvtjcp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2cmzwvoon.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gt2hmpaasjy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vebkpcxv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2wnybgbpg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2cxrobiyl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2qeejdger.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gt2jeiucite.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2muoksgqn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gt2sldfzcmc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2iodpdfvj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rysibxcq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2olkmnbcy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gt2ruypfcmn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2klcemuer.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iklutkyn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gt2xufhdlmi.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gt2zthjfnbm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2rebqxjud.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gt2wtchswpp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2bfjuwltf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2aeqvmntl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjybydck.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gt2lvehikqi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2fqhothss.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2kdvtlfmo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jojbetaf.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gt2nxpwdhhm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2txtjuvec.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2zowolzqm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2dqixczug.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2tpforfhh.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2fttbrioi.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ptfytgdq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gt2dauwovhw.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pipbjskl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmikkeqx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gt2lgddwxsz.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gt2laxsdjow.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gt2naqmkeaj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2noggknyw.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2usipgkjg.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2pmhhoour.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2psedhwgj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2cvikrkpw.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2ldewxbqi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2pxexpgik.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gt2gmktvxec.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2vggffroc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2fitlrkca.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2rgyhojui.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2pffkpnbl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2xnxuptjy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2jtxjvpvd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gt2nvgmjqri.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gt2compafyc.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2edkmmoeg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gt2trnhddhw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynhewmcj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2gurqzodp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2jrukaxwq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2rgmwveop.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2pswsfnac.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2eqbwsctj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zielhruw.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gt2deoplyqw.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2rvxyqpea.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2vtkzdddv.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2vxbtxymh.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxanhmsd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gt2hticznkc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gt2vhidjklc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2frbwbpuw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gt2vawkestm.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvbaqxev.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2nbgpsymr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gt2xqebegcm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2dgdlmrsu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2fabefqop.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuhsusxs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2iotidcgq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2klsobdxg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iabypfak.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gt2aynwsaob.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fooprzco.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gt2wggwkveu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2xrcnozgj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2qpeypctd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2utxujrbz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwmwrucm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gt2hsyfrtnk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2iohmxjdv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2arhvdims.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnvmslj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gt2pirkqyah.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2bqovxtdq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2gbjyfudz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gt2olankblp.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmiqrpdv.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2vuropxpn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2ipwwwttz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2pdblmqth.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gt2wtqlaioe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2urodstxr.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gt2mrcjqlvs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gt2btnbcett.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2rvkubzpg.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2fijntkqy.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhzhukig.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gt2hlteayvl.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oytqbyft.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gt2gmfgqtwz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gt2tiqerxhj.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2cqfypiqm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2cdlvjrbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2xdltumlz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2qiwkiwkf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2xsacbtcz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gt2iigdliwa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2fudrvnmn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gt2gwvgbafn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2esmxsxtd.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2evbmkfzk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2limopuoi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gt2slhkszea.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2nbbsepyz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2focvxexa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2hdgbntmh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2ovmxmify.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gt2nizbzwti.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhrlrrwl.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2jkyaudih.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2vevhaolo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2syzqewij.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2msiicpjn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2bxigixte.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2kpfuhcla.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gt2ouxqqvav.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gt2qgudpfiz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2kroxhxsj.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gt2wlihoqga.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqvfzotx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gt2povipnxm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2vgifiisg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2qtyfekuo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2ipgatqjd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2wshbnakt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2usylvpzl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2zrrafuez.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpssqswn.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2twocxfjy.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gt2lbncitmc.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2iwyqlmzt.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2mjcxevaa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2igrqutjv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gt2etnzkwle.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvzvfidh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2lkjtzoje.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2aciexdsx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2ksbztgiv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gt2qjcxfrsp.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2hcnawpga.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2dkgjpbug.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gt2dkzndqin.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2ltldxgjx.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2prrcaixb.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2fauxnqxh.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozvearlf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gt2jsbgvugl.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2dmnxodrv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2bxmiptqg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2lloekkiz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gt2uebixuux.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gt2yraoiyom.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gt2jrfnrsge.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2hadsujly.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xsqzqxyc.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gt2atnohdgj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fybpyyqm.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gt2znrztovb.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2cxiymwij.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2wpzxxsio.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2otpykjpe.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2qxpasyps.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egmvwxki.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2xodgsypf.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptozbkxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2yslwfizg.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2lnojqevi.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2gxfzjqav.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gt2psjmuacs.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gt2nhbatoyp.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2qrafmqgj.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2ecravzvp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2tuibgisf.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gt2fhltsvat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2aqfoygco.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2nueqtoyr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gt2kdoecvcb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gt2zibvcirl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2dyrxbeoq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2udbsyzls.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsvhmaua.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gt2egxnnruw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gt2rxlwxfvf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2lztxehqz.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gt2rnmcageo.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2bnpgsuda.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2vwovdqsh.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgdujveg.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2qzzzuzyw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gt2lfnhquso.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2vvhfbtsd.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gt2rfnzkkyd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gt2tctvfhpe.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtxcajy.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2fktyqide.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gt2rydxphfy.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqfpkcjb.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2jzvrkgfw.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2upgstyok.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gt2bjwavorm.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2vzvswzxe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2liwkqsvx.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2nkhwikct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iissncof.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2jjnoruoi.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2dlyuocjz.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2xfntbwan.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gt2apbxryds.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gt2fujthpkm.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2axfkfuoq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxmeiwcz.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gt2udbvliqu.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2aclozjxk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2uvkombty.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2vuqxxdik.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2jluchmsz.html


<!-- 参考信息 -->