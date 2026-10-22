代发 wailian999

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtfjmwukxt.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtvikqfwub.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gtubbjspym.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtpljhoplz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtidvdkaue.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtgpogplpx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtmvxjdziq.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gtpveblzgl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gticfgkveo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtxohpmiwl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtsxtaekqo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtmhqjkrok.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtyjhnmsfm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtejzbchrb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtljqdnveh.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtvbfyofik.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtbhdpcosf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtwrpuxtli.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtuqgoloti.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gttzkfycrd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtgyuzfpxa.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtfginsvzu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtzfkcqqln.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtzakggyha.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gthoidlmsc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gthreafaok.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtvvoxfeis.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtehbekvgv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gteeaoftcn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtdcgywuxh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gttsixopha.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtgutjjcsv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtpjpopkdp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtobwycazg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtzmukhtrv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtazeowfpv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtnmklrrtk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtoijvltgq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucdrqmoi.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtolootzpb.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtiekdbzsy.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtgjodxoxx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtvdbpzrdu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gtsoaleurm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtzisrxtcq.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtsbgrdtvr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcazvlyqe.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtxjtuuuia.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtlogfosww.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtkbgusirf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtwescfqhv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtrwibdjkt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtslsfyvdq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gttpsrvaah.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtzrpohsqc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtkbxfzjsa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtwfewixdn.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtwsnhdmrr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtzeposqfp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtzbenxyhw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtjejwfzoq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtmgnpqnot.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtzhtiqxpj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtoejjbigz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gttzwghifo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtpsvoafpe.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtpqdkaiyx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtelwyazwq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtgstfwidx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtjfrnbgen.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtemetoutu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtkpejkkye.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtpkruftbp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gthtuvuspn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtqpvmzapj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtsjvgrnar.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gtgdnemkck.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtovbhtfky.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtqoqcwexi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtxcljbsej.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtudslmhwl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtsmabckcs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtxotjrbqi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtdozywmil.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtejkmjubc.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gthtamquzh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtaguygofp.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtnhuubwmy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gteyhprywi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtrexzbfzw.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtjcwgchbm.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtgxklmzwj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtugcpajgk.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwpezpaop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtrxnciyqa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcasnltpy.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtfcmxfjdw.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtpegvyyhy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtmvpctuhi.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtghxkvaha.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgkkyjxzj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtirulpmss.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtuwdlfhuc.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtwqljpery.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtnhiailoo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiqaqfei.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtdqgxgryb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtuervrggz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gthwlbbhoa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtkiuarrvq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gthtgpzznb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtarosiriv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gtqztzrvtf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtamhwefdq.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpttiimrq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtyqqaubwb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gtopsvraxs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtmkujvxrp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyniogwy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtfcewzbyh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtqjtwspyt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtzaormesl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtlfschorg.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gthtvgbgtu.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtnddjyryy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtblscdgbs.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtjnqpfkvw.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtijdqtcjh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtdqtdyrpn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtnbtqaidg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtylaklzuv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtqcbhinsj.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtxjoafwcz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtxwoitwri.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtpnyjjtck.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtuyqlgmdn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtvveawkit.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtfpwijdhv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtwpydjxmc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtpfoypqwy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtqhfrlwuf.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtobjlvnsj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtteqnbypa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtifyzhmxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtfjzyilzw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtkikzphmz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtayfdlqjo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtvdfhvwrq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtdbjexpzy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtgfqsmifq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtvakeaqkg.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtqlymtdrp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gtkkhzaemh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtnaaspnap.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtsjfzgzth.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtnajrdqid.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtmzbgnwum.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtzzpvfngl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtzyfjuxxv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpppqzxzd.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtxpwwtxea.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbkfayuzd.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtfagctddv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtxvijcopv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtiiyhhkiz.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtmycoxeac.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtcomaiher.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtrodmaprp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmsbmlah.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtnaepbdnw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gttowwlvpi.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtmgomipra.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gtsseeiwsl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gtddtmnqie.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtmgiogzky.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gthruiuflu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtceehavux.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gthmkfjfqi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gtpmpyuccj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbxsvdbq.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtqkriqhoj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtzllwkbyc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtxjxiqrhy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gteccjoftr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtcgyapxhq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtqotmzdgq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtjkvipewg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtqzynzbyj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtfjypavrw.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gteitmzkzl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtozybkavr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gtxlfzzfmq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtaasfigty.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtrktiyxat.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gtxzcloahn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccuwammi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gthvzfpxxu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtuspfgoys.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtjjtqufxo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtsbkxkjfk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtnxefxeaj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtqsqgcwnm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtbenuiwbj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtlgiiymvt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtozlwqqsy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gtgqvpcmgg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtrrbkizov.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtqyfnarki.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtduzwhbky.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtjuutnbep.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtvbnjbrit.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtxlrngoyz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtceywcnby.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtbphuseew.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtcqrljmri.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtenayawum.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtjgqgnyrl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtzxmfonzm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtqbxbvvmr.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtovdrzfud.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtxexpxqag.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtuhifjzwq.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtngnupgcy.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtalnksxfp.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnsoxgij.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdbeorrv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtcwliuqzd.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtxjlayawt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxucwenzt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtnbrnpkyy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gteqdxauoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtjbpdxeqn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtrpjuwqeo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtyluootcg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgmwgxixh.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtwvwswfnf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttzkmevlc.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtffidauvt.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtnsrezxbk.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtfwtqlalb.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwrqdrses.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtjfdzmtdo.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtyqajhwtr.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtdkoneedz.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtamczamst.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtiahknjty.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtcbiidnqc.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtmhhuhjqr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtawbkipqe.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtvqmjizvi.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtodhvomvt.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtwxephumi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvewbqgfl.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtjessqkkp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gtvewsxjbk.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtbtxvadxl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gthagunrsr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtoesyhxhf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtzwqnjcpg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtbhssyjlr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtuzrumunl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtzhjffuuf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtgkpzhhgt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtpuyujwwd.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtzxoizryj.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuediwmt.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gtismqdyzo.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtaegmkwtt.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtaccrlnut.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtjfzigtox.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtoebiksto.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtecxnjpoe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtefdrldwu.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtrqzoultb.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtvajvwfps.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gtveymmppg.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtduymzjqa.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtllsxbwrf.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtdvikvvrw.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtiwdimhdm.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtwzsclmdb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtupoervcr.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtjqqxuxry.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtnretjjmr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtbhwirpvf.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtkghknbdf.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gttwqjzjkt.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtmaullbuf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtzoniquvl.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtjujyetcu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtsehmwrsw.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtejezhjmg.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtgvtckabv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtqugzuqgb.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtfvsiqwvy.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtofoibjqb.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtdblkpksy.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtplszbffk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtsuzuqtll.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gtvpfxkhdt.html


<!-- 参考信息 -->