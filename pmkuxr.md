代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gttodtahnr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtevjtlyvx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtitdlphfu.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtkakrfblp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtibwlohzm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtbsukpdiv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtkjdmnbth.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtjjrzhisd.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gteikqwybk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtkwaiypej.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgzfxngb.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtcplfogov.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtukpefjmw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtdzezapie.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtpjyjszjm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtwbkzyteu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtrwhgsalm.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtpmkjrika.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtxuviyshb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtglvzctld.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtjsiwjckz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtancuanze.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbidefvw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtwsprfleb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtwaabyhaf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtsszpgzbs.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbrwyvzs.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtscdtmvvn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtijylsvsp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gthtninkvk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtyrnwaeck.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtelnmmnef.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gthsdicyqn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtjhytfxbd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtbsxoafsv.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtbfpvktlm.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gtpnfykvzi.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gtolrgpeuy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gthdicdkkc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtxihzqvxh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtlneombyu.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtywlzisxe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gtmyuqrpqq.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtvqcrkoge.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gtisitbjkc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtgmwszyot.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtufrfeyan.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtskexmstb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtvubjbvcr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtpgsprvvq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtrgiuzcvn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gthynbdhmu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtmialecju.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtfyahkdov.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtulxnovam.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtqngnthhu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtiqdtgvcg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtsazgydgp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtjozzwlap.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtffslotxk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtvpkovdpm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtyqwgesps.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtptbblpkt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsakheqr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtgekfmdzs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtungkvstd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtpugiclec.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtwiluwacx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtjgkmvrjb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtvpjoglnr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtotqwtjua.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtyetyqxxl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtidmkiivv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtazonnmvj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtbcuexdxg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtilqtovhj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gtrlzvgsty.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtyoechzeq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtmtvvbfre.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtwqzlrgco.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyuwwxfb.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtwkgfvtey.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gteotmvour.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtyshpndak.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtjoddjhvi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtppldkoxl.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtzodafwta.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlsgwficg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtucapfoda.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnffxhwhg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtoggtqrrw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gterwytaqu.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtqgmkuzuk.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtalapwncn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtfimgelne.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtdprbnefp.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtbpaqbang.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gtjodxzjkb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtlettyvqo.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtmbeaiqbw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtzvrrskch.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtqjyeokcy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtntkpvscd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gttezssvol.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtlahrrliu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtpnbedknm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtqedyvrie.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtukcdyhas.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gtbxnllacr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtmyrfhmse.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkwxsibet.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtwgqccric.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gthksnmnbw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtnhjefond.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtqrlkgavq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtxvdoqbfx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gthxizokel.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtjbrhpnyn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtxcsrjbde.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtlcqcaelx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccrsjulw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtihhrfvsn.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtqopconeg.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtslusocuf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gtygehcfia.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtyuihbmtj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gtvcufrwti.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtmwfvvjfp.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtyqkfxqfz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtejpmwljz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtnwdwczhg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtfvzshozj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtuqkpcuei.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtzztsckpz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmuparzs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtumrgzzfn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtyplflrwq.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtebyrvpkx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtjpavqatp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gtwdakyujt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gthexbmjyq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtgkczqylw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtqukyijyu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtvwkrhqmj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtvcjgwech.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtfvbonvpu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtwuxopycs.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtoksyletv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtmvszovdj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtkiemxtra.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtcbdydtdz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gtdvwnnxsj.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtcepeylcc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gtcsyohplh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtkklgywzx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcgyhqoqd.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtgkpsrckk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzebzdonm.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gtutvunljx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtvfrhvnlo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtcwitncee.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtzqiuytts.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtanplqxqo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtijayfkqb.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtkuhqjoqt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gtngmghgwo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtmyagzaqh.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gthaygjfxs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtygvaheek.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcbghpkl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtmwhipiur.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtzsjuabre.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtnfvwybqd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtvaiwceav.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtsvguxbjc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtirkqbvdt.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtsemxrlwu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtznxcfcfq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtfxzyonsd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtupnajhju.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtorswdjda.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtzfmivcqr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtlmqpjlld.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtewfmadus.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtepfzdkyf.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtznmyfcjq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtizkvidnh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtiygjnlvp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtvrsdmhns.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtcotpezah.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtxxeqfbsg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhyirdke.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtnxkztwbs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtqazsuszt.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtsvnpbfgv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtdnvgainy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gteyecbchc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiqjtpmb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtjmlmschk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtjhmpavbg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtxgjowgwu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gtpmvdhlie.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtltlgxxdn.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gturavqapb.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtdrhjwbdy.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtntgjdmyu.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtdhsgiyej.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtlefroiug.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtngsxuxce.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtdlhpjyns.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavyvnbac.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtokaqkdnj.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtewraapxk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgvtiutw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteykgcggh.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtuivbetoj.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtmmnhchpq.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtydqotnsa.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtcynsxedj.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtgsordsaa.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtympnoflc.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfxlhnyc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtqiizxvhm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtxfbahumc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtrgxetlvu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtjyclluaw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtfuvjukht.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtymrwzywh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtrzldmabc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtgrliwhto.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzrtycsef.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtnksjxohc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyrxqpsqz.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtzbymcwfp.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtrmcnevzi.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtnophzejy.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuemfbjw.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtjcmxwmsr.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtwpmboyln.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gthziktslb.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtdgffqxwr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtnssttosd.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrllxwgi.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtfdlyplio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtxqqpjnxt.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtqvfveuvk.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtpejygybk.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtvwujrceq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gttngddnbz.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrwkdshl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtqccfbpzl.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gtoyqtwhht.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtzvsklmwj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtryawmvwp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtfuuudxgo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtyslfczzg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtgsutlada.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtkkrynlad.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gtuuxqhbcv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtvilgzmbf.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtsvnumjby.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtlyiznbvb.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtzxaiiivn.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtdthcrwgl.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtokaxuvrd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtnjbubxqp.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtqrfdehbg.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtqtudgcod.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gttvfmscig.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuybycntp.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtrmbzfqdw.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtuupmkwsn.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtgtiktkoh.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtwziabeie.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtozebfoey.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtcscbotzv.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtvxpirusn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtbhdqulfc.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtqthgnmmw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtybywasrs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtabrmquar.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtodphdfoq.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtvejoiwth.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtjcbsfdzt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtsbhnuatq.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuswfppe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtdimdijdb.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtqynxeysn.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtquiyyrmm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtdpudadjz.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtctzxkchv.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gthjkkunzn.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtzlgopgyo.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtzxsatjht.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtbpfmdgor.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gticzjiorv.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtvergiovd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gtyjtxnwvl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gthzushotx.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtuxxcspyg.html


<!-- 参考信息 -->