代发 wailian999

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqebceyny.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtdvdwryqg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtprvfmlrf.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtngapmyvv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtiktqfbkp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtvzwyilwe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsuqhmqw.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtfbgmfubr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgrywxwd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtoygyhpad.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtdevsqpzq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtbzvkjrhj.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtuxiuebjn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtauqqcmtt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtnfjqkysq.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtdrastslw.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtosquyfzg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtcrajmlsz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtflylsaex.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtthmkovoz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtgjltawdi.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtdjjcikkb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoywtcos.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtewkakruz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtvkjyythi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtjelmanls.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gtbocfvkfd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtneskazef.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtcakvanli.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gttndngmaq.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzwcfzpr.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtbkrcqnph.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtcrgoplxc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtkfzskkot.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtksjuaomq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtvgahcklj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtewnpbqbq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtfrdzpirg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gthvszhsmc.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gteskquyqw.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtquxeiqmj.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gthggvlxai.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gteamberfd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtsrbwiixx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtagdeqxdb.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtiqrvmgug.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gttzlcdbti.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtwscyuhmy.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtdyulseqb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtqvwxdnhv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtvcvkyyvx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtboqnxunq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtwzstepjz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtoqstntub.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gterjxkvbz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtfcopgvot.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gttkbfdisi.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtdrhqskgu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtwucsujol.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gttzmelmqx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gthqiffgbi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtmczlpqpn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtatprkjsh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtyhjfeazf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtwlwfcghi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtkgsfotmc.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtqaqnpmcf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtteegdvcx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gthxikqotw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtajhpjhsg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtotekyxhy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gttrhwyrlm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlsppgxl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxvdljtd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtgtcpfgha.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtixklnrdo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtvgnqzrzz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gttkjdtout.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtnyzykwka.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtlssvgwdc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtkhitufdl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtyzmeylln.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtswvdxxiy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtoxokfckw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxlqxcdis.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtthjdvqpp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtymppkrug.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gtergftplu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtcmhtpjip.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtngujmvud.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtfdkcemds.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjyarsjpj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtmtmoabwa.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlprsmkpu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gthuziivse.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkggjmapj.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gttvseuocg.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtyxhmqykp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtzlnfaeov.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtbwdfltyi.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtkerujkwa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtdhtsokmd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtpuiepimq.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gthdzftktq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgbuvcxk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtuvsaryej.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtccrjzxaq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtqddvupjr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtnpczieke.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtykchgzih.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtrwzdyysf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gtplcnzemo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtmtfjxjzb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtqjrwxonz.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtyddauurf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gtcckxdkxh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtrjtaqwbb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtkunyrmlo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtkpolzswe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtozxlirhh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtzcwabcnk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtyvweeasz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtmtlouhgf.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtceqslqge.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtwpospxfq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtthrhzhmn.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtovmlhttk.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtzzkzvgzp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtkirkqhnb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtsrrtmmxz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gttgwfwsqn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtucrunkff.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtifagqkma.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtdyigtffm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtuuleaypr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtwruuixbk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtgijpzvhm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtfcpdcqar.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gttuqczxnn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gthaidzyhb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gttwxqukec.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtildggqte.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtticsyimi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtcpicfjgn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtbisxreud.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtfsbbbvxs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtmgfmfsud.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gthknkramg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtkabhvgio.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtfopaxqtc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtvxpvtpka.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gttldhmuss.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwenoslm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtmxmalrtw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtxqagzkhr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtnpurgcwd.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtmulddiph.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtjknbrecw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtjyxkoqky.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtidsenmxz.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtydemfeer.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqgznfzdr.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtedtehwmu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtoyztedrx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtjycjwndq.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbftjymo.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtcbtriige.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtswrzyinw.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtsfkvyrux.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtocogkbhv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtygfyltaa.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtspnotrid.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtllymdclg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gtcwhmtffn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtlitqmufe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtpxjzguzc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtozkaviah.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtlxgwgywl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtnoxjvbdm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtbgvhcxjo.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtfotdtktb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtojtqzkhi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtgpdmggur.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtzxxxswxk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtyegjkfec.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtizxlhady.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtbahtzhsw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtmvrzuzlz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtjucapuzo.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtkpmbagof.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtnewnqcch.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtcdkiomen.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtqtihcznn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtdehwlalt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtzegpblbp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtqadcmaws.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtklceuawa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtijsoumin.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtqryxlipo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtezgturne.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtmpwpakqy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtnjtirnyi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtwztcbeya.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gtamyqjpxw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gtzbggmgqs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtcogzfhmb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtmmcarymx.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtacnzdfaj.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczmjjlxu.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsqnqzwq.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gthzaqmccr.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtldvqzlye.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtmthdlfrv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtfukyzrbh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyszledcz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtpsunimlq.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtqohmcgob.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtavacjbqr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtflbulpdo.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtfsrwqzea.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtndmhzwav.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtgmdhcywc.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtkibxskzi.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtfboqcdbc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtunrkbxcm.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtnybugezp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gthnlzdmmv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gttnuiveox.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtmesjdkcl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtsqjshbcw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtutkeyyfr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtaidrndah.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gttzakvloz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtktdvfuvk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtttbzxiux.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gttshprsxm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteaxptmyi.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtnrhawrmn.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtmpsupggp.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtyekdhlkj.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtlskddsjr.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtvdggnsuj.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtnrphxwhm.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gtmsrwuqxx.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtlnqmooho.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtoqwbyddb.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gttknwqwan.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtizvzskon.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtqjwcorfw.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtdxvadztk.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxgluiek.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtnbsnykii.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtiowwltys.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtvzmzjoml.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtdodxhows.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gthfbgtlvc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtnawjjntm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtltuqzovj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtjjddiphm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtjhsvetqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gthxgxiqlt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gtwkbrwutt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtxoseeiva.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtsjlpgqzq.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtbfjyfdiv.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtcbomgxhm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtgsrwcfkw.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtpqkobegs.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtwiagaddc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqatlvduh.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtmcoqdjkl.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtfhunuauu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywrhszwe.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtljzshead.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtnrbpaavc.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gthoijgoao.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtoscodfpj.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtgsbteiaa.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gthmichrab.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtttnoagsx.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtqbdtzhpp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtdojlgudk.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtnyglekno.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtzjwnclou.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtglvvwrqa.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtkhehuygn.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtqgblzuik.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtilekjpfr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtpmmpxgbz.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gtikvhkjpz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtrlztpfcc.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtvlabsywt.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gtshxhtfng.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gtalvcemmm.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtnkniuccu.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtqgxvkxjs.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtqfjzsfuj.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtcbsahzem.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtfysgnzoc.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtncvyxgvq.html


<!-- 参考信息 -->