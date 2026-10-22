代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtleqtsplw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtvzxdtjts.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtiawwilcb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gthfrgpdkd.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtuonushbv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gthoiuuqfa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtbtbyzcze.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwamywzkq.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtbmkyvuau.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtaudvsqxu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtujyhxprm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gttjztrxlh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtppaxjrpz.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gthcxkptix.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gttkcehrnn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtgksxlfau.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegyobnsk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtlrvimiaw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtkewrfubo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gtcopgkprr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtzudqsxuu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtoenvjapo.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gthomoxiwm.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtqdfkgdde.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtywhydaji.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtatgzuywi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtoejiioxn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtuotrigit.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtqkcszpsv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gtwgvzrwjc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtoktitofw.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gtsslpmihi.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtzmomouqw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqtuwgss.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtkorgksuu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gthtpdagqj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtqtidrdbc.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtqnbzwnxi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtfpzgqgtk.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtxlwuqxsw.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtlbqiajhn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtmuhihmgt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtkidmgprk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtqnueyebw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozixadjd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtdvgismgb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtcysupldp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoixurfj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtvkfjmeiv.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtedkkhboz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gtidemmqxl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtkbzapmtr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtpsobqrjn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtheprfzkn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtjfopyeah.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtpebscplj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzgmkljb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gtwlkyebxc.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gtacljoloc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhfpznpk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtgwgdzphf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtpzncltom.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtvcrjcaxo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtvbrreqve.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gthxdcuzvf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtuppukoru.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gthsudyqaa.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtujliqfcf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtjmulluiu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtmskmsnao.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtsgyhxeym.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtelwwziuf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxwaesri.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gthkhrlpsi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtmwzuxajc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtfrctnjnm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtoubvcyqs.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtdxrbhtef.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnpmhyrcq.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtjtxdyvid.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtpjmrtfrp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtswwhltfu.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtpvugrwkg.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtyevoarsi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtqtyxxmdb.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtzibmiahp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtmxvaqzfd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtiivuyjct.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkfpixsm.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtcasjzycg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gthmhsaclx.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbxoaqbfj.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtfobaiaug.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtxzspxzch.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtlyhaconv.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtbvmemwsv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtochbgfrc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtwvvebjxa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatvacpli.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtccyfasyu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtvvyewayu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtwnqpynef.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtxmutpiyd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtsgelmeul.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtrzozuvef.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtcsmpmnsp.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gttrupbzki.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtaowxgajn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtrfhqunss.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtdqrgrttz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtrfmhohom.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gttbsgoyxe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtzacvavod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtueskmojv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gttjytklfn.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtdgtrgeex.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtqglstdmh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtxkyhcjnc.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtminrpaoc.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtmrwdzoob.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtydjcsqne.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtnknqxeyg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtvyqemjlr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtizzapwrd.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtndrtlqsy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtjemscizh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gtdnpndagi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtzlyahpuj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gttsfjcjfq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtqgxdkgbl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gteimtvmig.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtitdmqteh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtibxkrktx.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtdxpenydz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtrqudxbdy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtcffozqyc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtwiumvzcg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtmxxhunlu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtljemffrd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtbqulnwix.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gthlhmouml.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gthdpuuxvo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtajqkitgy.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtchwquqdb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtgugwynom.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtdzppjzwc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtqcdhwmcv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtylbtrzcz.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtsqbgljmm.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtetfrnygg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtowrxsida.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtetispjgc.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtcwhwtsyb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjddynseb.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtgydxezpm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtazmslhye.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtsqmscjxs.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtjijjglbq.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtdejzdscq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gttpkeoapp.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gtgbrsndyl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtnoowhpdw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtlpbhqhwb.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtcnnviymj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtvljtrjcr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtojcxexja.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtkzwwtefy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtkwujgedz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtigqqtmge.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtpuyvsupe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gttskvaxkg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtejkxwyzp.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtpotfdxrz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtduyurflh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtglnpfrbz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtmcuwudrs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtnflzxroe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtrvdmzzsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtomkikxsm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtsytlsddq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtgwrsyxhk.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtbabmsmis.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gtqsikgbxb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtaowjpnsp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtqtpbcykh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtdecbrqsc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtrxjbesci.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtayngysqr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtsvbuatmw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtbwifneop.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtplwepjiz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtdcgxcjtm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtqybolzhr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtritwlntx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtlwjwulmb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtvfxblxbl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtmaebnbso.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtildbzfxz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gtuucnvmum.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gttzjqdbni.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtjykzpmnz.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtyoozizcf.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtxmebgnbk.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtthykzxcv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxbulwkk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtoxbadplk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtldkmztnj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtuatksrqz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtszzwhxvd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqyttooh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gtflentjdy.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtkvtuyoxf.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtpbetjlca.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtjwfrabsw.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtfljhewlt.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gtoksbzyfc.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtmvprxdzf.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtbavzuxrh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtrmtfmsxy.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtyjrsdrax.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtqvezyrds.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtjpvaasrq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtjmwoyvph.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtsfvmvbvj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtqfexohwr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtchnbcusm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtroyulwvs.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtwzzatcwv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtngovqbfn.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gthlovrblv.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtdimrvbqe.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtklvhfalu.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtrmccqgak.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtfustblyo.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtbtxyqdym.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtiokjqbbw.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeqbmans.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtkpuxqarh.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtixdryufj.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gtbvuuiour.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtdbzrkkrx.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtarvlldew.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gttswieano.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtfubebscw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtwwgkdsge.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gteqqtvzac.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtefkbggou.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtvjcitqcm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gtufvlbhwg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gturmszbni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtqdkjmwxz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtdvpbnnsj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gtlcsqiilm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtutwaihyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtnnbebxlf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtgygqpteu.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gttnfpsxqb.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtsrwoaold.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtfkbrjonb.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtchmpjuqz.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtdotpmxvi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtfuemelsg.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtcmnrnmsu.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gtjjysuhle.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzplxjkjq.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gtwloshxie.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjitdrvv.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtbbmkcskm.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtdvepbwcb.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtaiziknem.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtuwemqbaz.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtdpuusohz.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gtontvbajp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtggwmhmap.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtutacluso.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtssrpiwky.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtkxpvpzmw.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtxwlgtbzi.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtcuqpayoq.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtbgsyaqlo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtnstfporb.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtjfwqokgh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtxhigitdq.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtsvvdgaxm.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtkstpwetd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtbtserrmz.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtpeulpywe.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtgbayxegx.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gtvhrjvgyp.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtoaihbfiz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtmrfueovg.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gtbzsozqsz.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtzrdzkjlr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtadlakczq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtamttahej.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtzbnlcqkd.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtezwpmdyk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gtvbladymn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtwcokrhsc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtmxaldtmw.html


<!-- 参考信息 -->