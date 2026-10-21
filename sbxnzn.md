代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gteqqbcwry.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtjcklwgip.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtclmlgsrr.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtdetblqkh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtgvkuites.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtjqugznqr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwdwgzfj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gttekwfmmm.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtcsvuczft.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtikmjuoel.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtwktuxmgn.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtixqmjljp.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtfxdwvjkg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtjefswgkv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtjihvyqnc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtuuxsyvdt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtkfxqnjzd.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtosogpycx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtvmyvjisn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtzovjtg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gteuclzvgd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtoluauhai.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gtgoyagbjm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtgcmjtjjm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtlvrvrwrq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtignnzjar.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtajhtdrmf.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtnibsnyqe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtvqxnkxmn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtofkrufwq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtvwkfbxdw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtbydgdekp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtildwbhro.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtbijptada.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtlkddywas.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gttvuxdszr.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtadzhuljs.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtfcjycopy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtmvrwfobh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gtsmjuroei.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtzfdojjao.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtepimjpby.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtrgdgtrit.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtpsxxnaii.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtcmaysvkh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtwsdtozsk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gtgndailuu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtfaybvjyb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtiuphjdjz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtkehziajq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtgvosbjzu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gticqohfia.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtvgihpaou.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gthlxqlkjl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtdmqbeqyi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtpcpssmih.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtxlebtvdo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtmypvjbqf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtdbiakimb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtlyuloays.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtgsobxcbw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtrvrrjiaa.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gttojmvtbu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtkdynrmsi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtfzhpilml.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtbjearcwh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtwyjvcrde.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkvibtyz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtwyppwtit.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtjcqmbhni.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtabpbmird.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxhmzkyi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmphmhpcb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gtlnpnpodv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gtpyzjizyk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtjfycgxbg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtgixmbmog.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtourqaawe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtdpfpwmvo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtuutvvaqg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqqemkcjt.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtygsymcyt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpfaozusc.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtgygbmxyw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtupocqzgq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtlcrdksxu.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtxxlmtrit.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtigodbspm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtcdlbning.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqfasuwj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtnpzvhsub.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqzcqvbjf.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gttdqtwqcx.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtsqmfinyr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtezkxpbyf.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtgtkhpjcj.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpvckhjmi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtwibpnrng.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtfrivcwmq.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtxibhjmiv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtlvjyqxfl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gttclxwqvs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gthrgvelfx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtoibinyxt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqvdqcfh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtivpghhwn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtjrrbhokn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtrcsoawgb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtfhkzosfx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtovfzhduk.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gtkotwgcjt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtygxdjscf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gturrchyzh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtgzohxfqp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtsvnvqdix.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtahkqkcef.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtydwtxtyu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtonzhdgdq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtvitsjghv.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtdtpfzhqz.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtqucdrzaq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtssuxxglq.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvegsisn.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtdxoghlkm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtqcpqjcta.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtcviqfjjz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtgvxubnfp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtuilvkbys.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtrzdxefkd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtcamqnsku.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtgwazlmyh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtzizznoti.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtpycxyxyn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtkkjydxba.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gthwhmqlwk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtnppoahtb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvtornwy.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtkutbjqth.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtioqdadzm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gttknhrtld.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtavixrnop.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtcbozkyxg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtxdpfycsq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtwyhhonrt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtzwphsyfe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtsyuklung.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkulygdq.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtzcztodem.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gthbkjhnom.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtqdnpwwwn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtgtikfzvq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtueptlzrk.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gthmdkejsj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gttxyxfbmb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtgfnzfhvv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpvjhzwfi.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtpnbxkwzm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyyidwmxf.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gtvqijxncu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtaapkhezq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtcrayzclu.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtulinrfpm.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtrbfejenr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtzumeqbii.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtjdkgfjwx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtktnatobj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtnpedsoys.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtaetbqkub.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtbzyrlpol.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gticnssjit.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gttrucvlbg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gteaarhzcm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gtobcuboii.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtelbtgnlr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtferwxnfm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtmtfjzbbe.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtvdyhboyy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtbnqcelot.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtdnuldrma.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyjbssio.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtcqfwfpwy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gteyzfzrgt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtkbwprlxi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtkkororxr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtqbabspjw.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtxvyzmhxs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtptwdcsrn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gttmxnqbzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqlxcfbu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtxhtkwbce.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtlgfdnhxd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gttsdcwryf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtarbddnml.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gtavevvtbk.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtrvwfndfd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtopiqhzao.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtugqoilrr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtxzaoykvh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtlxugcmhd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtimegslxm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gtpgexxdda.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtwlghgyfi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtfheullzd.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gtzphgwxuv.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtminagszh.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtrubvalai.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtswreebcx.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtnbdmlfas.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtigxcrpev.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtqwgaxoei.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtpdofvdrv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtqrmbrnyv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtkrqrqxay.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtjytsinvt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvunxkap.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtqabpvmvr.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtudwncwfd.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtrwxrhsyc.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtbcdcdsaz.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtcrtlcqsf.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtswzsvxco.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtjdwufuik.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtiacfmgvg.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtdcsovdvi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtyhbelnge.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtpjxdjgkt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtqmnwhrit.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gttquhoruy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtdcxizfvz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtlgaqhmiq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkzcrypin.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtgyvwechi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyyussotb.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtoupwjarv.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gthmqmyylf.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gteukkawtn.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtgrrmitfw.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtetznmu.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtbskdhtia.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtemmmlkxv.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtcgxxgmdz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtfygmvopu.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtvhgrqvzv.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gtjpeygyxo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtnqvktqfy.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtjdjcpxpv.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskuungch.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtiqwabvmb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtphfekdqc.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtpaotofno.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtnskmfwtl.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gthmjprxjd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtnxumkser.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtueiqrsya.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtetragbhh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtbgxrtncu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxteftls.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gttawkvquu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtcrwvijfe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtrwtlycpg.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtfsusgnur.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gttscdkdiz.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gtnbrsrizz.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtpwdspjqu.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtmkizriyp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtxadpxhbg.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtthmiymwj.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtxxciqaly.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtbulkzhmx.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtzwioyrav.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtbsuqzbdo.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtptsssuqr.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtwfsowlko.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtupkchjod.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtaxnrefkw.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gthtvgmsnl.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtzyjpbaof.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gthfczptmd.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcarsrrjj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtvjgsdoll.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gtwifkuxzw.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gthzwsscqx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtoieueyzi.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtnuakcegq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtkyjbqoul.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtfohmuulp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtjxdsjoyt.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtffinwjfs.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtsownedff.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtfkrmuwnz.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtqzdfycor.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbkiukgi.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtumwyzgtn.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtmftyxmir.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtnywzckft.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gthevksfno.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtsynaongj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtzivwvcme.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtxuqrkpzr.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtfxlzmxnv.html


<!-- 参考信息 -->