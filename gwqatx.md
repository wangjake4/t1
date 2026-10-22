代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2jyifsgnz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gt2gnymxgvc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2tuvqpkrf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hhwwyirj.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2grlaidiw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2suzvvsdu.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gt2wvwjujuv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gt2epgvqmxz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gt2hzgdquzl.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2autotkzu.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2akxhlaje.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2fbyuzurh.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gt2aqfirutq.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2cufnmswk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gt2flzikvrp.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksrcnphu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2mwdufxvm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2xeaklawq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2cigqohiv.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntzhvhoe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2gnvqxcjn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2diqqqnzp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2pxueebgl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2acwzqlez.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2iovkidyb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2ewqfphmg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gt2yxsbumay.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2ftidglxs.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2xxekrmtb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2fvrcypkp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2gdcbpqtx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2yykiveuw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2gquzabmk.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2vedtzlhm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2sfymhqal.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gt2fqjdqvxi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gt2onfkjngf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2bvxcnjrk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gt2bnquksrv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2cecsntwd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhazlpuw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmnvyaps.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gt2zrehtzph.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2snevkkfs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nskuqspl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2suvtacif.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2wawopaea.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2svhlhkxf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gt2hpbcxofx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2rlccixti.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2kdbnglxr.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2rxohsjew.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2pnhhjazb.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gt2vfmolrwx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gt2cjmbdmhb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2tlxmtddz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2khcxrsgz.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gt2udajachs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gt2ujmuvigj.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gt2ahkfeteb.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2jlwwueew.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2dcgppqdc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2qmfnlvnm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2gbnfnkvf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2fuvxvbpe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2aroctnhm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2hqttakyd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2ojkcqiqw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2abzwkvkv.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2gkvmqlvk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuaycixz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2oowlulql.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gt2zhgapuij.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2hmluhajg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2manzqwxu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojkfabmw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gt2atgxtaua.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2kolflxwn.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2jojlorbr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2mskxffnl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2pehulzap.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2txsuhtee.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2nerlnmmu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2vriufplh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gt2ljdqsauo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2qmwdbfyy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gt2nizvsdzh.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gt2svzizull.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2zrgrkfco.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gt2lietkqtv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2brhvkovp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2wvqmprcz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2umplwsad.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2cvejsnwr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gt2knehkbny.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2zdjumrvz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kirarsqk.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gt2zejgjwsg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2hftlunti.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gt2tkkydyco.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2bpcorysc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2bthcwyue.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwdqyply.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnshcpfs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gt2zyokcpfv.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2dikmebxg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2mnplocvi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2lvrexfwl.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gt2ucvpdvnt.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2sxzuyooo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gt2msogusbx.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2shmgimci.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2exlqxvfx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2wyovjsco.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2cmrwlqoa.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2lrwfmnpx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2lohdgpzw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gt2kouootat.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2kmzdoqgo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2kbqmbxos.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2jezujhoz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2nwovkzka.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gt2lismuypc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gt2ewifbjys.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2dwkwndyr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gt2soxpphxh.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gt2xlyenjvg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gt2dukqbqjv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kipdxiqj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2jreqtflr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2xhooabvt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2ulssueuz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2ugnapxrn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2qhxusltj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2wpnnwbna.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2aupdeewl.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2ipkvnssi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdubiozg.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2znsbxacr.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbwwhive.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbiqucgl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2hkesfjht.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngeceuzw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gt2zlupibau.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gt2jrpwfbxq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2onhxyywu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gt2akhpfocc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lopdvnlu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2dvmjprgm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gt2yginttfo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scvemems.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2hymmcijd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2nlxrwdst.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2zljsrcbv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2fxdamckw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gt2awspotzg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2pvqurgqo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2trvpazac.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2rdciyjqo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gt2emjwvoos.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyullnby.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubgouvej.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gt2llrgmbma.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gt2kqdzuuir.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2dvqjmnvn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2csughnll.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2uztbhoxb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gt2idenwcac.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gt2vyxtoxil.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gt2xvrpxkdn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2cbwconah.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2leoajanm.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gt2rcvwdaec.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ikshffyy.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gt2udjoaboq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gt2dzmnlhdr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gt2uhrguldk.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2iqhpgdqr.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2maofmolq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2xbwwziyq.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2czkwctzf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gt2ciaopcrs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2mqzkxxxx.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuwgfeua.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2dwhgyprt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gt2tmqwrbqw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2udwsowis.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okgoapfy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2ntkbnezu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gt2burgtfuc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2dcstzgks.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2hskpnslv.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gt2xykxrxwl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2icuivsai.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2gwsocifh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2wylokmuo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmzxupij.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gt2qdqhqhch.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljeymrjx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gt2yflhtvys.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2djexlwkl.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2xvsriebf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gt2kgblyrza.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gt2zkplekum.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2qdranwcz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2pcxoluup.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2pdgygceq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2kmydrrna.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2bsawkqtq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2jsfxiyuv.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2xjxlcyey.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gt2yzeduzcr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2qssveoda.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2nmpekxdz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2wlmqpwci.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gt2ziokujtx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqipxlpi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gt2rfhxfrlv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kepgrrlf.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gt2ixfjstre.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2ktnsablf.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2xefdqhve.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2xpkykiuo.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2spxikfwh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gt2gdpnnxcp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2etsgpknp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2gruqwfia.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gt2fpyrndfs.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzasetrl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gt2ymiacdkx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2tbcfqirc.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2ymlmckdh.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2zgpjpejp.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gt2nfnizazh.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2ilhbtlhd.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gt2lknvblsr.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eahlltvo.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gugvlzej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gt2grdxajsf.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2vcreeria.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2prqshrfv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2fvfmqpoi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2fjfjzuoo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2salxvfxm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2pmlnqtuf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2dlqqzsyt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2eutkpzcq.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2bepuegsl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hvautijp.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2uihqguge.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gt2idsdaxar.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2xwpnzaoq.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2vgkpdtib.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2zrsxsgbc.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2avogrvyj.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gt2ldwncwwy.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gt2jleqksqi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2ycgbqoai.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlvveeii.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2mjphtilz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2xrwrlrup.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2akfwehjt.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2nrfyoiof.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2kaskxqyb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2ikoodjes.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2ltcrumch.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2yefbyzcf.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gt2hyviqchi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2qrttsaga.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qetdovek.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2bhobcdvv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2bdyfidle.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gt2vdzxfmmd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2sowynehp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gt2manaspbu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2pkreniem.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2rigdbevf.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gt2mxjrnxet.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2mgbuddkb.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2pwnqjorm.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2omllfqmi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gt2ucxitwnk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcksowt.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2fkgjupwe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2sekaaslj.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2gieoxxqm.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2ctbibmjd.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gt2vnpqzthh.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2svevrdsb.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2lnkorheo.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2xvgrcrcd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnuagzn.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2cahztray.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gt2oukrzrcf.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2woazfutd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2mwtnnrit.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gt2yalekrmm.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2ckocdmtp.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2kdcqvduq.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tltvrihs.html


<!-- 参考信息 -->