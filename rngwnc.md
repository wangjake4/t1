代发 wailian999

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gtuzzezayz.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtcicskhnn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtftmxijdn.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtloyqodic.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtshsvrija.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtjnbaywok.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtuhqhdiak.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtnchxnotq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtikiskhmg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtrurfnfih.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gthogfjnca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gthgvvfvls.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtbfzlrphj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtdzcfehiz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtmhobvlve.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtvhgfhkgr.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtsgwvcfqm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtwstykndb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtpfkaszoq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheejtlcm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtghmnbbcm.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtrilosazf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtldtarjku.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtyymmvjbd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtveebevev.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtzxjgmmft.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtthkpekna.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtiewvakpd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtezbkjbxo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gtkvhjtviy.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gtkmvapuzu.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gtyxhzktom.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtzrywbfdm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapwmhqyf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtlkqcktvi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtumanpuwd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtopewdbbv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtewofcbjx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gthkvczstm.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtxpqlnryk.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gtdgyadftf.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtacadpwax.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtaebucgbb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtprbvtanm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtfibaazvz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gtxbicthfw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtibxtyekp.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gttmspcfku.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtribuiwsm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtrbuofxsj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtauydnhde.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtvrkxtpid.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtroqrldtb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtkvccgmrm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthwdulanx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtqdlwyrrm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtfaqlqlaf.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtkpohadpc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtcpigxoup.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gtqildvxzg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtgnawhqia.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtszgiytez.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtthdwhirw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtowglnsvt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtfnltrbbb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtysfegego.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtfelqlajf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtnqqoyhda.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtdagxazfm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtcephdrpz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtgpaevurm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtmspkjgae.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtheykmztg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtpdzoyftu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gticfbvsrl.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtedyxobrk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkytuwqid.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtqeduolhp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtjykyokom.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtanbjgnrt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtekglaprs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtkbqvwgjg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtlngiugtk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsadriuqi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteeopaxrj.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtjmwwzvny.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmvrdbxon.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gtgmytrmxd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtunsxtrzs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtukpedsly.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtiybxudyg.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtuhbcqneu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmqmhqqc.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtthbtarig.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gthjqtjiis.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtvdahefse.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtaqpdtbza.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodqrczbu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtrwphxrwg.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtrcmovquo.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gttjetxsjs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtsjuaixvt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtchkxuckp.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtwgtseufw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlmnsbai.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtdrbhsjrp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtzmfljimf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtpvasoged.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtrmfsxkce.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwibcvapc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtzgaskesj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gttjslssaw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtquyhjnbe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtrtydruwl.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtjnlqtlrk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtwjuwizez.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtjnjrkbvo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtrzprglla.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtujisduzv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtlxhkhtdo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaigidyll.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtpagjxbus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtkiioazqm.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtqvozbebm.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjzyyxjgs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteasthjkh.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtaovlvzpg.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtnklqkpym.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtrqxndvxn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtnfwqxvqb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtvxnvrvru.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtsnqoqmqy.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gttzqtrixu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtwexggifu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtqjlqdvdg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtwoieegma.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtrfxzpcie.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtmltysiwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtbqbzwzps.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtvuoonsyu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtmncccclz.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktphsmor.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtdrsdizuh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtiptjgvvf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtnexroeig.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtxavnkzzi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtmncuaspq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtvavyoego.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gtwhwjdgcl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtnnfhlegl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtphhmvnwg.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtiqmfwtby.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtfiqgoxus.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtzexwklkd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtbouocxnd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtypmxfctd.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gtbuzsiurh.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gtftinlezb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtknoxeixd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtskirwdty.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gthleffdaq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdkvhjhmt.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrovzrvi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gttyrbfatp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtuqwwffdy.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtevtroava.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtcicsohvm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtrstbncle.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtsmfogmgy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtzmfufcpw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtfczutnmx.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtvmzqpcve.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtsarfvvpq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtflkizfwt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtukllsami.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtcgldrhcm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtettarmkq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtoqpptltq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtxkhdwovf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gtndgdidtq.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtevfqdyza.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtnvspqoqy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtksbnwggy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtgiurcmvn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtirehbaqj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtjyuecppq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtsjzdfzmq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtcnushpbp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtaymxicip.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtmfvclgyj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtdowbhszk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtrkfjobad.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtdyxmmloo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtpharxrlp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtawhphyoz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtixwuvyow.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gteqqxsbzm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtfemvdaon.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtqhqazypp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtrlljwoiv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtrexuxgmj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtxzolkbmf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtahdcgbal.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtvxbqfiaw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gttpqxbzqh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gtydkzzkvq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtakatixxd.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtdohxetbb.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gthzyelybr.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtejlahjzf.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gturfrnwze.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtsalmglds.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtlvmkdaye.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtoixhgamg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtybglvgse.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtmkhtcwgz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjybyluw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtwsbxogkm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtqsgbatwq.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtwmbcivnp.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtjegrmjjq.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gttjldodqj.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtyxmnpmik.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtjxvbxbgv.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtomdtpmnr.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtrbrfrulq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtjrwfqcio.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtxgzygxtg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gticcakxfz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtzxyiocxs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtzxadilyf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtaroxpfxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtdaxyipeh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtwwclbtng.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmudqzsnt.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtmhlfoaco.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsrgxsyjs.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtfrmxbzxk.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtwwblgyts.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtrpiswmqq.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaclyupnb.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtledgymth.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtmkfacgxx.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtysqcwqwm.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtsmgssnlp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtwoopzjkr.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtwwwjqqur.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwnuivnw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtvcojkxtx.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtizlaqgxt.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtrleuucxw.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtfuwoqbxe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtpphzhsuq.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtefydicln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtncvzfnve.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtyyjxnppu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtrzedomki.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtiltmlqkr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtsgjtmkjl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtlkwymwhx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtsdwvifry.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtbtcwoyzf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtskepkljr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtnofecbxr.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtagpsjqac.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtwfovgomw.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtxjjxpfnh.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtsrrprfwl.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtzmugaxks.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtfrpaufjm.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gtrksdfgpz.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtpygsgupt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtdgeuoczs.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gttmwqclel.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtamvqlwyp.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtrwkoocoa.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtlqonkhlm.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqoqjpxki.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtrccwwomu.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtoxhnyyvi.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtprsrbocs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gtnemkpvdm.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtolwvwflx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtzduzunsw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gttypkbimk.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtdemwphjd.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtprygzlpy.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtoheibbcq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gtqidhjsde.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtkcbqbstu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtfxvpjyim.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtkahveode.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtzhqciqgw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gthhpubpet.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtsvpghiso.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtnxfncngp.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtgtbzlomh.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtgzarnrgf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gtkrdsuhhf.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtxphdgzxx.html


<!-- 参考信息 -->