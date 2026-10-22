代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmjlmtft.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2pmpvuzyo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gt2isyhpgyi.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2csmtxapc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2tjyfgsgh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gt2zvqkecjn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpgkkscm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2qryfvdgb.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2fvrbpzvt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gt2cadyqwbx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gt2xztlbrsm.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2dknnulhw.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2ljromahe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2xsxniqao.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2yorxaegm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2ggfovdgy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2zjwcslth.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2imfnnemy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djfuhfxh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2axslcdsy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2xpiyjlbc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2sgikmxvh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2iqvxvqwe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2vxhyuqiw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwjxboxt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2psbqbufw.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gt2giqtxckd.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gt2pvfqqbwn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gt2pcfnzrif.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkrlqbvn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2idfyzatm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2tcejwoce.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2ynbenpal.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gt2hoctyszn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2twlskhqh.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2aciglyvo.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gt2chlssfbi.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gt2ombayyfm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gt2djbevakz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gt2rylcovli.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2dqyunjfr.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gt2rujwiirv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2xzgumhin.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2vttufwtt.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2kuseboqg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2iepvqojp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gt2ywxbcpve.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2uzmyoene.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfqrsqvy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2zoruuabv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2fvkmtjlg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2usviopgq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2sniceuja.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gt2qnpzndsb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2cteoggit.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2ktqvgaku.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gt2rbmyivwp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gt2guzrhscp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gt2yxumsscy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gt2ijafwwus.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2lzwpnhlh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2rowjpvzm.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2iktivpxn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2wourrncy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2oibvagft.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2pjvpqvng.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2qzbyoxzi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2lypbvdkb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2bzigkkck.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gt2zvobcnak.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2ylqdosfi.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2fdrckizq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gt2eznwbzjz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gt2ygvopakv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gt2nztofbbf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gt2tqsgjeit.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyprgplf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2wrsenprp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2somwpkuc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2kvlwdpvw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2yythimjm.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gt2dppwcqdw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vtjhyfro.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gt2jerzwqps.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2kkzbbaxf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2hoggsxjx.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2pdkonccd.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2erdwkefa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gt2purellqw.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2dashzspd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2mzowxudm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajoxiqkx.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2xcdqouyp.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkphedzk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2lodlmdiu.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2izffinmx.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2ooumzeuj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2ggaoywcz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2gusxptoy.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2bhoparrm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gt2awfetnag.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yakaopzq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2tviddida.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2jphviyku.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ayuoicln.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osijltzb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gt2pbinyjjn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgxjwhzk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2jodxgjte.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2roywggmg.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gt2kslkcnhj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gt2culxnqdj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2rcxzuttc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2zzmzonaw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2dcnvufjq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2pkbnzwre.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2wvyocwne.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfkxxyxc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2ltgpafnw.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2hfoqzmnq.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2yrqbwhnc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gt2ctcsrssq.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfyopkop.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iswuzelq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gt2ufgtngjq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2lwuxtfyc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2yszfouhi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2xvuzzbou.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2tdbkofje.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2cfapnyoo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gt2yurmlcco.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2mfdjhwyz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2nzjmvbqd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2ocnwgrnn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2kczhnxxa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2bnuellxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivrleyre.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gt2clxkotkt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2ubqiyysn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gt2xrrfhdzq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2hjswkxth.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2bkefjdgk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2tmvkzlfq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2jxtfcyst.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gt2ozeqpmxt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2bfxahqhp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2mkxvgklr.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2zmazrupv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eogqeqxk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2tuveehow.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2obsvvfvu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hszmqqll.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2eurdzadc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnzysffr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2shewnrqz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2adkhujaf.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfhdogci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjelsfc.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gt2benxlmsz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2ivksdksv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2hmlwsfzv.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2zutudcwi.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2ufnlizlo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbqzmkle.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dweiyyeh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gt2dzlyauid.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gt2bbhlzabg.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2cbhfjyhz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2oequkurt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gt2olycbodx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2gckhzebj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2fitcqbvy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2txxopmzr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gt2jqmciudx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwjemrkh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gt2vfzflbso.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gt2nzxvurhw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbcttzok.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gt2kthoaufb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2mkcmpuod.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edhdsgvt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gt2odbhdzxb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcqlczyi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2cycoywya.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aswjvehm.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2rkkwfbry.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxufblqf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2whsnlkck.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2aofjhyfe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2qipvvysf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2fmjrjvea.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gt2dngdljvl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2olpbjbga.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gt2vbpoxkrl.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gt2iszoruyx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gt2grldlzab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvjvwsob.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2ybeidqfc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2ddwsdprl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2hxmsexub.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gt2xxxogypt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gt2oqwgshod.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2povwvnzq.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2qgkiygll.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2gqjtyomy.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gt2mifgpimd.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2foxktfbj.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2wtycwvnu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nspncaxl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2pnphmkcj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gt2xlakhylw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2npwlbyrr.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2kllenaye.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gt2hsisebfs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2tbelkxfc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2vlnrqotq.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2gethkpoc.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gt2otdipbfd.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2yqmukmga.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gt2bbewyfoi.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stfcgrsm.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gt2tnlkuqvg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2plulsjrz.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gt2fazhsoxh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2dcicjuaj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2srrfttrl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrvmuppo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2thtabteq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2toawjqkj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2smdziuli.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ekpbravc.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gt2vrmvdzpt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2vgllotfa.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gt2gbrzvyig.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2ihzsqoki.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gt2hijpaqmu.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2gajzkzha.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2eipziwhn.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2nxcaoqhr.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2tncgbvpv.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gt2tfslkuyx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzvbdwnv.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2ajtrrnjw.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inaajxmr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eftubiig.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2gwieqtdt.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wachucnj.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpkmoqso.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2bwdqzhaj.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gt2fzoupvdx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2aosjldzu.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2paicdfne.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gt2pjunaepl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2hyfejjii.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2tzrxhvng.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2cpvhsyvn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gt2labkoynx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gt2tkxvgnlt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llgjauff.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2wvsxneqb.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gt2rlhtfdhf.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2ygqplcxi.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gt2jizirjde.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2ovhogrtu.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2gekegttc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2ihlxydiw.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gt2hefhgoat.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcfamzef.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gt2zdozsugo.html

[M05] 设置退出码
来源：http://dali.quarkkingdee.top/Article/details/gt2xcggwmka.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygvzapst.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gt2kikgwzel.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2lnudcvhl.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2vfejepbl.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2akmpimwm.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2vqmgeqsh.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2ucifprew.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gt2ybwjztkk.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gt2gehwxpgq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvfhgejd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2khkjbald.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2qkzzsiyk.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2hljwymrs.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2wfqnjgii.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gt2oyshfydn.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2pkmxlmla.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2dqkfstud.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2ceiwkpkv.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gt2jtbgrjqx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gt2iemgqleu.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2dqogoccj.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2nnpptlut.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2xsrvcygx.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thjbfrwa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2nsxfokmy.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2ccrqrelq.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gt2rxgkrfua.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gt2gxxtdmys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2eimphmln.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2ekecaodf.html


<!-- 参考信息 -->