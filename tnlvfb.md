代发 wailian999

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gthtdmishe.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gteimdtcbd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtmfasjiod.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtupdjxzql.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtntxsugwj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtwkeohjga.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gtjdnrxsfl.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtxubcvrfz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtnlenxaoj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtivmhdkxe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtmfzavcch.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtftpifocm.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtgacqikrh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtcvskbkrm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtwyqfwgqp.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtjtzssuwh.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtppnnplqq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtnznwtkby.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtnjrejldf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtimcgeatu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtksnspvwr.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtrhvazovz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrevnksb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gthyfmdlwf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtkyloandt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtiexaezdm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtoxblpzlt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtsloqguol.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtbropwbxs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtwntsllmw.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyefrlqg.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtlubwvfqk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshdfamin.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtkivztzcs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtummthygl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gthohaexvh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gtraxhsyph.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtbrftmrko.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtlqwcqrgd.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtjkroyvyu.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtrkjmnaug.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtmjtomvrj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtymraqtjz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gtynwtikud.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtavbsjlrs.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtyyeeskyv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtoeumexvu.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtpxebbtju.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtrpmijxkw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtqbilrcra.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gtxjhnmrkc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtdzlhbtoz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtzzmsymhn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtclwsolad.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcmhcduv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtqsdtmbop.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtmfozxbqq.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtabwwwedv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtqmmadqge.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtrudmwzzr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gtklhptxfx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtjzvfaouc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtgcdqmlst.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtvgojnfvq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtiktmhllm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gtusumwaom.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtzutcwmuh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtcvfhwuxn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtcnenthwb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtixelgjyi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtfpivsifu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gthdqlmpri.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gtqbtwurxr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gturkzsqtz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtwjhlohvp.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gtwcytkwcv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtguetyxnq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtamqyibrd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gtcmudsbuo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtrlahpfjp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtvlxntvkc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtjwbyzoyd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtenrwsfny.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtuyzrikbk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmznnjihy.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gtehupnecg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwbircbgp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtdhxkdrnr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gthkoavaxo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtjgmbekey.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbezjxex.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtjtubgxwh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gthxyesuve.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtpvvcmsjm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtteiyblxr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtvlgiktht.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtsmpvdepd.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtxortjqnj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtnfcfmztm.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtlyionuzk.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtvdfedfsv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtyzhclwea.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtqummpxyo.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtcqpcmwwv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gttopdyujm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtynojwbco.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtxtxrbuwj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtkoxsllcn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtepgfzxbj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtmdjggqnm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtreycbtdt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtwexdeiqy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtjpherhog.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtgmxmxjss.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrosiifls.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnptbvlls.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gtjwbaeahv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtuctetpph.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtklfxmbut.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtnyjlyfxk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gthzzxyhsl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtlphdgxue.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtjqvaysaf.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtrsevfqfy.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzgvyasuk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtofcbvfxg.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtkjmlehbb.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtlurindki.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtgbtnknqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gtwumytlcv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtkqjyvvsv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtgiitgzmo.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtshtyyhxt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtxdojgymh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gthelnbvlh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtmdysfzue.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtsppflrfj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtiqjtcycd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtkwdcisas.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtdlvpzupb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtucvgowsu.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtzyvvxvnc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwxhorbp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtlqhymrzj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtjzqrpyju.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtjzzcvdcp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtbsvqwyco.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtwtqrfhti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtylstywfd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtbgzmdyla.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtzddftsox.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gtppdzuydh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gtajezbexb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtfrzoaivb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxsgncng.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtnvulhmlq.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtzmqrjrwt.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtwdhpehol.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtnzryslex.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtizalksgf.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtnwtgpbkf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxgrydavc.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtcjkwjiui.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtbclvisxe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtluwwgsdy.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gthvmmefkt.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtqjbrsctz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtpzcyyuyc.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtjcbsyehi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtullgsziw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqptlnub.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtbxdrffsw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtgsbpuibe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gthidfuvgz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtfmbqrncr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtlengkmii.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtlltdpkpo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtmqzamtgv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmuuhvad.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthehbjnpa.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtfpfunxqd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtvueyiyjd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtdrkjtovv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtfszhaacz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtyxbjcqcc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gthwdhdsfj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtcvbyzebf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtjloohtal.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtbwoplfdq.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtlijfsbep.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtnxwcdodf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtbgxrxinq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gthcdsbaid.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtpzbblfvf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtomgbrobv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtpwcdbmwl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gtsfyecgwc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtjudukehe.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtmxqkbfwa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtvmsionpa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtvpvmuhzk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtzyydjczg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtnyozapkj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtwrjqoqye.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtymvlehrf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtudsdsvdp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtesrooihr.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gtiannjmbb.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtoawmfzrg.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gteuftpedh.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gteakapcbg.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gttsekmfwj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtwpaqlzfc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtvqvrjwql.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gtnlpgnrsg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtamxvbpja.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtcurbzblj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gtrlkratcp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gtvrxjgoeb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguljkrnu.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtwnchuvwe.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtkklvkdfx.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtjrsdoser.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gthzjserqw.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtjcsejkgi.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtoiqrzvul.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtvtroghfq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtxmbuvdeh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtgfzlozap.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtmkllftil.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtxpbwbeia.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtrfkbxjfj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtopxyzprk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtayuocwvv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtiiztsrgt.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtlrywefva.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtplbgglcq.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtylrsvgzm.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtqubcdqqj.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmuhoyzg.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtykworomj.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gttulqhfxx.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtpnbsmamr.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtqornorfc.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtoildwefr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtrryduafg.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtmcgbideb.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtyheqcvsq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtscagiuih.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtblfergcr.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtkhbmrczc.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gteijobkka.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtccretord.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtfqthiuxk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtrwwgzxde.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtxmgrixzf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gterermkbk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtguoufspy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtedvwkwgt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtzighgegw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtfkagjbmt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtvydmclsj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtscovrwdw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtitaujfro.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtoygvvsra.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gtczehrowp.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtbmkaqrjd.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gthgumbruz.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtjmtlpnsk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gturbybbcw.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtqqxawpyf.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtpdglfpow.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoircldhm.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtzodmfgcm.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtblbyclzj.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtnhftwoxe.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gthfizqlek.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtyuesmjey.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdbenxldn.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtaenqdhaz.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtzpzhqfrz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtvwbchlsx.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtwjufcroz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdajdufwv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gteabqpilz.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxquxjlso.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtsrboliim.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gtksoultxa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkupuptu.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtszamtjun.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtemhoixxc.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtutmhcjvv.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlfqzufz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwszxrxb.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtisfccixq.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtyaknomgo.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtpyslnhmx.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtiuypywbm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtoyhbxgqn.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtzjvpyuut.html


<!-- 参考信息 -->