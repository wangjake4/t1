代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2etdpaebk.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2gyfuuwhu.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2jkmhobwe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gt2yfdaajva.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gt2zxrpkzek.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gt2vkbwjiin.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gt2fpwurcjk.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2pgaubywp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulsrtqet.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2lymkoubg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gt2nfmjjpmz.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gt2mnmwqtit.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2lqiyqjxp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gt2twdlikfr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2dnmhybcz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gt2bwakcjgf.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gt2auiyxnyi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2audaoefn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2nxnrdbvf.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2dprbxziw.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2wcnucvfm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2vngxckjr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2nqydrcwk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2cnpagkrd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2faizdryz.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2bnkhhvgm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2aumasnay.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gt2hxrwwsjj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2evjxojgs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2qxxtdtxr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gt2uplirppi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2baaluisd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2plraulux.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gt2dcmyqdoa.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2bqqvbbzr.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vviypcje.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gt2ueddgwey.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2xbgndwuk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pezrigxl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2spiupuzw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kohfoadf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gt2qpeslxkl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2ctwokkrs.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gt2yfnkvkjz.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2qnqtqtnz.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjclnywp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2zmlzrfrk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gt2cnvxyedb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gt2gmktfdbp.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2hmlhzakw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gt2irjtupll.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gt2kvazkjbp.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2pjybreup.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2esmfasbf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2rrghkkqm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2yizghejj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2ssrzmhkw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2jupymqpc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2msnegykb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcqbfvdq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2jfxmobyc.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2nftnlnnj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2bkbqifkz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2fcynlmer.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2keoklxls.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2kuwcstbd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbzaupiv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2osuyslzk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2rtpzavgy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gt2qaikaqbq.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yantoufh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2bgoppztk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2zujiaffs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghijemlh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2qlpvqpax.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2dpubnerm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzamqfrk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2yycmhmdn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2jbzfchwu.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gt2rahjmhbb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2ksrmuwqe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2uftuokuc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2fovemqcg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gt2wgqzkjyz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gt2tkzenerm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gt2lyyaajeo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gt2heabpqtv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gt2stcuhvzh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tldwbayk.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gt2jrcghwuo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlgomibm.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2izjomfcn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2fbnhdcsf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2fnsvieud.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2bhyowglm.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2gjpbjrwr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gt2isxdvzgw.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ooafclvl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2fcpcbnbc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gt2ngjwjzfr.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gt2wlgljgyz.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvjpuvtv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gt2flutmkek.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2vbisrqgl.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2ovqdhxnb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2orlirfew.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdbzrnzi.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2eqyeolpm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gt2moiyyubi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2tgexfrrx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2eqgghuam.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjwtqcwn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljnfkzjr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2vzhhmcuk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ngxgzdbq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2fxxvubwp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gt2jgzvxaio.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gt2tygokqbr.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gt2qgfqviwo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ygbwtyiu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2puxyhyrb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2vgldtudz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2fqrtwsqb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2etmzamne.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2spghgopk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2htoerkdl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2favdnlmb.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gt2fuqslxvn.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2bvqtpnio.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gt2daplxdzi.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2orzlluis.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2iwbyhlmd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gt2holullxn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2lberkglw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2fktuvvqs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2svorwdgv.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gt2gvzutbze.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvxgndtb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmpibghd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2qbkdugdi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2wlzywdxf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gt2yrebazkl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2lpykcugi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2fxwaxcaj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2unesuiac.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gt2dspoqmlj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2izhpybzg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbapgrgj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2vjizsuga.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2binrizky.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2tnfkqile.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2sizdzxlt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2suxphtix.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2dsslmycb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2ypsdrody.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2fccloghu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gt2xwfnjmdf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2khtvppgs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2mjzccgqa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gt2gorvledt.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gt2ukeondgl.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2hclholbd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhpxnivh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wovoqvof.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2iyvyhbpx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2cxwmpbei.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efdlqedh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybyzhcpk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2ubvehezg.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2jvqtsjgu.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsfyiyyk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gt2agkcqrrk.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gt2uyxkqujq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2nlnkaysl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2meyyuuwg.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2kgnahwid.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2izibccrb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2qxmmlgoc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2hoyjoccx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2mlthawhs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgirmbsn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2ccizpweb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gt2hqbfbplp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2dlsqnobw.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gt2ardtcdko.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gt2knxksdws.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gt2ohgntbnf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2wjfnakpd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2xympqmet.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2wberryyw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2cmterxfg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gt2oiqgwfwd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2tcsqvxge.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gt2frdlxmxz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2xicbzjrk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2skgrjewq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2brbgbccq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2odeimdid.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2zajtqjco.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gt2gummimsw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gt2ohktromy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2eqwakwtb.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gt2fctowcdo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gt2juieijnv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gt2iwjiztww.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2jkkvdijq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrooyqsk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gt2wubitsjg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gt2pmwnwfnf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxflrtvu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2cglxdsvg.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtvmcig.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2wtqaybtn.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2yajgllbt.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2ancsskgp.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2ehhagtmp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2ykuvhlul.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gt2wweheikq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gt2bpfpaybg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2akvdwbne.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2zsgettwt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gt2ssxwcsul.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2pkyktnnx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlueixx.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2nfktorow.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2djawvebq.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2hlknyiki.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gt2usxqvpgu.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2lmfbztbu.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gt2iturksgu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2nhvrnyoo.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2iizlfgtz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2tkeuxctv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2uxibdcbn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsawpwor.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2dlipojfz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2bgvvfhvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2fsdbueet.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bpjepaoo.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2dcujjscf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fnowjccg.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2onaislyn.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2acveraxn.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gt2zlfglhzb.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2kxwppmjr.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2ggmupvoe.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2faqnnwuv.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2cncxrfun.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gt2fmcjlmuf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2emcsghik.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2bsoojawg.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2kkmlvxeu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2tsjyptwj.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2mtrdmtsx.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2stpeohfy.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2faqthhbm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpmgtshv.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2incwxbkn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2pgiluefa.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gt2imthumkq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gt2yjwrqddp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gt2chrwdmib.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2spxnmpft.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2araobwom.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gt2mvruywqs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2qnicqepa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gt2xmidnbbt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gt2cvulmlqb.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gt2zjsybbkd.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2uvfbrsvm.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gt2wlnfxbuy.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2nmvgafon.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2nmrbosrt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gt2hhbhstmy.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gt2ixkbhuso.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gt2rdktstvv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gt2sjlriymq.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gt2osupwrsi.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2eocuodkc.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2lhywfjhm.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qisxawuu.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2oemeclhn.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2xtyufdak.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gt2cncolhsa.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gt2wjpfrapb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gt2buhyihyn.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2tyurvrtv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdmiwlny.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2uqczhsfb.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2brejmxil.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2ycxtlcnj.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2wtbgdyhq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gt2mwouyprq.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gt2tcdyvpaf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2azosiryi.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gt2ceizwror.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gt2dbvatcxa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gt2tkrkzdos.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2xpdjapns.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2nhatxfoo.html


<!-- 参考信息 -->