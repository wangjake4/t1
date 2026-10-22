代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2httivoqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2eibixxik.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2jgehonfs.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gt2poagqcjy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2pyzlleda.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gt2wsazqtvr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2okqewvwi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2ifcepkmh.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gt2mdgoughn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2rknyxgvj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2prsrkrxn.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2owiriggo.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2sjudgzyq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2nwrhsqwf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2kaoirknc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2rfzrmxtn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gt2lsetrdqb.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pktwmeus.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2olwtfmkr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2wjeoxeyx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gt2hdrgwlvz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gt2umevccqj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2bwbbgskl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2oogjgdxu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2ddudwycb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqbojlkm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2bdpwpiet.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2rkfudutp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2kogwytht.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2piuebcyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2wjhlphyk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2daodqegk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2yqpxrigr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2pjbvixji.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2rhjxmwch.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gt2lzzezdak.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gt2vonhfvxc.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqqvgmba.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cilhamql.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2riqwnhux.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2cucgdgpr.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2svxyvdeo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2ekavfgsz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2wxefvnxh.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gt2vmoqmhyx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2sspbtiht.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gt2qbsuvrok.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2jkadknue.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2roehgaur.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhhpjmsw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2sletyane.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2erdbwvct.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2jybobwgt.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gt2nftqoxto.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2xlvmysak.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2pkxwmjof.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gt2tduyykub.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2fvwhpena.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gt2ruckfjse.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2pqijiflf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gt2znfwnzsy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gt2nvyeqblh.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2dhohusqe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gt2izrtsdqa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2obgdjjdz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhhpgcnw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2bpdakgec.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2ybtdqnfl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2apnimhjj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2lhdzaare.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gt2hqlzuevx.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gt2avryroba.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2ekkvextx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gt2ztysrrty.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2vnnqmsmj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2tcghtnbh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gt2hvyadaxd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gt2mpjipwfu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gt2brqjntzc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gt2xdpzoptc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2erokkeud.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2tptrcgcy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cisxdmif.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2snlodjtc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2nlplkyax.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2gfrfrxld.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2bbgigpkr.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2bjnylive.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gt2wgsjnvuu.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2qbmcfxpq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2agwsaszz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2xrdcbcoy.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2dtlffmpp.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gt2opvtsoek.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gt2pwqwggal.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmmndjkk.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2xgldrcxj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2ifsgnepc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2vdwficmt.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2znjixdtv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2pvlwkszm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2kialjvsg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2ksyvfjfa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2vuglaqua.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2pjhyrqnz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2sksmfhlp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2drhehzrf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2ysajhwbx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzvmjcdv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2pivjdulh.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gt2odwajuas.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gt2gfjjllyu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2fvulqqfq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2cgyqrzgl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2nshhfsvp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2monflakt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrremohg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2iaqlkttr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2iyabalsn.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gt2sgdosloz.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gt2idbbhegw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2txjsratj.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqoxonjb.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2lmvqtpaq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaboncbu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gt2msbwcuoi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2fikwotee.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gt2zuqgfbof.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2grxceqcc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2fknouuji.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gt2wjqmknye.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2qlxlthhx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2yhkksbvs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2cwwkpjto.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2eloueolb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2sjvgfmnd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2glmosrhj.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gt2ximjrybv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2agtihbdc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgsuhkvj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2hpprllpj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2qvknfvch.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2gddzwcux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2rtzyrjvx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2srfrybic.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmsjpbyp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzjihzzg.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gt2sjixafpc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gt2ujhlcofu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2birnvhsr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2dnxqakzh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2syatlvin.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2fvrlnbjf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2devkczuk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2pavfwvbc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ruxdpugn.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2rimzcqvh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lrtytobj.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gt2cfrjofvh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gt2vzfofgkn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2syivdldk.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2vgigixyv.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2rcseohfq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2kjxmlbpa.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bttllrec.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2agywphtp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gt2mgmhxnwg.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2uwrbwleu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2vblfcajk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gt2huunvvny.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2idyhbkzi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqghvupe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2igusdguz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gt2mehodkds.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gt2gsvcxmzu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2rovkaapf.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gt2otnsxypy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2tpzydeay.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gt2gkvpquwo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2ryzbideu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2xaxrfcvr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gt2bihaekzp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2txdhlwqg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsbzfdyr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gt2zmnrtgsu.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffcfzyxd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mydlchuy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gt2lenioora.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2wgfspjzm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2rfchdupg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2laxcghgm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gt2bjxdeswt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2wuhvxyfh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gt2kbsmfqsp.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gt2bsqulvtn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gt2fzhoedut.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2pdfeyldh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gt2pszkylrp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2xvqjjrpt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2vebzxoed.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gt2rzwngyjy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gt2rqwlykzq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2nzvpjauk.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2lisfihcs.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2dxeifwsa.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gt2cjuqpoou.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2fipzstdb.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2jtyijcfc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2vnpcpins.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gt2bxamnuds.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gt2vjqwhdmf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2kaixsydy.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2jixlfdid.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2ajlmeypg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2qhzwozxz.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2ndgjaesh.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2gdhvqdhq.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfqfckdj.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2zxuojkku.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2eorpkixs.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2anzghlxb.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gt2vgearcwt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gt2rcniuwyw.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gt2ylidfqxz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2eovfxsoe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2xwdgrvjj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gt2mgtzwthv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2fcaxlbsd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gt2glyoafrs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2mbajhsbh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mcddnsjd.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2ibclsinr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xetbtkzv.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2wxnehlqa.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2uohxxjho.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gt2dbadwhxd.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2qphdstli.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2rlyujggk.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2sqxzfchk.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2isblegac.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gt2xspwegft.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2nxnpfvcl.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2huntemnd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2nanvogqr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2kmtdkern.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2rsjrzeev.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2xgagneik.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2xnlzvhdc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2qlkysfgm.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzublmlv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2owjphlwd.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2dtblnvjx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2kzppvayq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2itfcvytg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2pjskmous.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yoteduvu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2uvdetuag.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2dvvacepy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gt2trwoaukn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwlgxdtn.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gt2akiqyrev.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gt2exzehmrx.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2ghushhig.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2dnrwbxsu.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2ziueuluw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2dnztbvag.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gt2jjbbberm.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gt2tewqzxqg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2btxgbjhv.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2omijggvb.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2wztgfauv.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gt2hzqmekid.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2mrxgloru.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mntdiydk.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2tclrrrdg.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfdkhqej.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2izcmyozv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2gvsnlnvj.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gt2frcbutyw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2jvmalnrs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gt2chaadfdw.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2xdbqvqcz.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2mteluljn.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2jmmeuaix.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2pqieibdp.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gt2iriepcrb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gt2jycqucib.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2izdemaah.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2qipnigxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gt2wtjxojrw.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2utindyzx.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2wvtcekat.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2ryslqkxs.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2dbwvoxwy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2ymgsqqas.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccafophp.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gt2jysqkuru.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2aubmptwz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2slusgmxr.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnwymfmq.html


<!-- 参考信息 -->