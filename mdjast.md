代发 wailian999

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2ophjepyt.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkmrqady.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkzdthjr.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2zvdyibnl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2acjfpbmi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2yruydeha.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2sxpdbwit.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gt2qvzazppn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2lryzppfj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2bvvwzjwg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2srfehpux.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klnajfki.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gt2zwaqxdyw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gt2xtmzkglx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2pkgglouj.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2swnsfnvl.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2xbyurqfg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2jrhzlsje.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2qesztujd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2vtoaddyh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2coltwzak.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gt2pxekiwzz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhsznudd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2jzrqwqkt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2jzwvjwdr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2sfirtcjc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2hqkoqgqz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2ddmpvcld.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfivxekf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2apluorsa.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2givyciwp.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erldtzuk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2ozcqcsxb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfhoaagc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2befchpii.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2iogiuilz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gt2plsprpgb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2kubocsgz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2lkcjaggl.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2pypcnstt.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2evikbpmv.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gt2rroldwwl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2ednjjvqd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2qnyvhbls.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2slgtheji.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxtpauvb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gt2eiztbuwn.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gt2qijqviqw.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2eywgbpek.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2mmndlqwo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2gbtfeagt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2gfcfpogf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2bzoeqcth.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fllcroqf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gt2tugxzizv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2xjrzrhly.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2gxrvwmem.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2tceyloie.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2buqndoxj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2shnvbmav.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gt2zlebrtbr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2orihcmou.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gt2gisjalxp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2cqosjlnk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2sefcgrne.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmgwudca.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gt2lknhnxrg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2ihnkiwzz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2tsadjkcm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2phodgimr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2qainlpqn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gt2xwlqcquj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jemoarsn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gt2losthxca.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gt2akaegwsl.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2kovuwqvq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gt2aqevlfyl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gt2jdqdadxa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gt2xfgoposv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2vugudlln.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gt2ojklzzbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2emjgyonx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjlqyvpg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gt2hwesewzo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2kfmmfwmi.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gt2excsaupa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2yhykcgsp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gt2fpwmhfrq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2zhbnepsu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2qylvmuwf.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2omuqrxtf.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdkloqbz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2rczyxfta.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2wcatimpi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2viynbwcp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ncjaefdw.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2jtnaqgvl.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gt2xgdswqwb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gt2pssmnnqd.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2lrnghhee.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2ukltavdi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2kjmwwakt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2mpbocqkg.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2lnvptnyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urssnjbq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uowwbyua.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2qajrwhem.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2iiedmpht.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2udzlglvn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2bfjnphmy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ajekddei.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gt2jqzvfdsr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2wflfnyjn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2ccmlkspc.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2qmhfslhg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2xkpdpkgk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2czcpgtml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2tpjfqxpw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2nkinealh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2qdgmyrlj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2anrzfuzj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssbgfghf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gt2ukukhawp.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gt2yipuaylo.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2cluzyvfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gt2hjeqpenf.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2wmvabsmh.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2eladjqls.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnprrttk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjexkjmu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2wdbossgz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2sgvxyovt.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gt2mpkrlntw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2wdkarsog.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gt2ejtpkmwm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2luimencc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2slmuxrxg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2uexgkzob.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycqkofng.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcwnmtgm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2ydeethru.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gt2bmlwpsaj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2gjjjhpzm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2fnfxzxfu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2zilfawji.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2dnuecebx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgwfvulg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gt2dwgklojq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xujlwnfa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2lacjapgi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2zmvdqqtk.html

Py:   pickle.dumps(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvmimgnv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjelvctp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2irrkmjvf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2sqdpazgg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gt2oyokhhyc.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gt2cyhllrrs.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2mtmfcvmq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2ssyylhej.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2lefafxso.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2wmbzphqu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2cnchjukc.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbkdllcc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2ujuhsgqi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2lwjtjhas.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2juzjjbyl.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2gwzamvmb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gt2pxvnzbbs.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gt2luvmsjnc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2hinycmbo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gt2wzknjtbp.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2onfqvnad.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2xighyqjf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2udmzmhkx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2lptkmzgc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpbgruhk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gt2grpkvsyb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gt2dticviff.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gt2gbfypcbs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gt2unocehoo.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcxvewve.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gt2smiulvpe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2wpkdpgjd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2easqbheg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2mhyprvcc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjddhfua.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2hbbdlyps.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gt2aqepzllx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2doxqztah.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gt2hfqmxvsp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gt2pbxyrzqn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2yemelagl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2wyzqjetu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2jjdmfvbm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2weqzvqpc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2mjmltceb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2jooykmij.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2ayjxwsub.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynipnivy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gt2dpyqsjau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gt2jhmfotri.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2mbejewci.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2dletgezg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gt2lbvhtocn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gt2gfqhcbws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmkrwkjc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2eenzyowz.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gt2xusiypll.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2rzqgbtha.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gt2ysroxmss.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2olhbrgyq.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2ckpgvycn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2ajoigwgi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gt2rvhfspjx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2hchdvnce.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2mrknulby.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2omdeyoqj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2wgtfadhq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gt2coqxfrta.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2ohuxokhe.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2qdkplgqh.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2nqvyekjb.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2rmcxrbqi.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gt2xlbnzhxs.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxktmhtp.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwpjrzqq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gt2txzxvovy.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmmozzda.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2melflxre.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2hllfanpy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gt2gcgnnnob.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gt2gyddoauv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2asocikiv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2jvedwqdz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2kbzkxrsx.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gt2aehwrcat.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjcwfevu.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2fthwdlyu.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gt2povcfydk.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gt2koxtrnrm.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2luvndjnq.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2hjczsyfe.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2lhilcxuh.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2wvhxkdsz.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2jzcwslzr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2mscaeyzp.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gt2cnctlcgy.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2hpliwbde.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2xbnwhrki.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2jwkfcmco.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2ixlndhqf.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2lbrlvdll.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2jiqmbwfp.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2xbjsqbup.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gt2lbiipnvd.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2twflbwtw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gt2htozvjxq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2mnvwjeel.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xufbrlqx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2iauzpcfg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gt2wqltaomx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gt2bobpoenw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gt2pzuwxkit.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gt2zwwtnooy.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gt2edyepdch.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gt2cjbqcqqs.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gt2qqkoznnc.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlhjfwga.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2uuwtpked.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gt2llaoouue.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gitgatke.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2qxqeiiop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2qyiecdhk.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2ctusykcy.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcnvgjvb.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2xgumbkum.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2nkvimfxk.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2jmypscws.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2naenuwpf.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2uxndmvis.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2nliwpxfe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gt2nzyjeymp.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2oxyxdskc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyrimidn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gt2wsfbjeov.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2jlulsovf.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2nacrspwm.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdakknom.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gt2zmodyioz.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2pveqpeam.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gt2rzxgnkbn.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gt2gnelidtl.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycdbuklm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grascssl.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2ilidktbo.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2ksfiijxp.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2nheymxms.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gt2atqmauvi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2vljdalvf.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2vgdxcsst.html


<!-- 参考信息 -->