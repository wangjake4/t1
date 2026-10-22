代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtjkxsrpqy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtfxzwooat.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtfzncnbzu.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtpgqwyfge.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtahppwazq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtnlyyulqh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtmtamyxjk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjspdlmh.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gtzgmwarrh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtehdnefvg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtmxkiohmy.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtwvjjuvon.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtfjgramdp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtetvfqkfa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtdelnatza.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtthtcruvd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtrwxppeia.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gtxoznwmwv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gtpiuxblmn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtzbncditf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gtltypdhvr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtbbufllbe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gthekwfpuo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtbpfsjzqy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtxikrrmlp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtwugsmyjb.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpjzeabv.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gtnnjhhlbv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtyvfwgpug.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtdrdrxota.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtwkgjrmji.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtapudntyd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsflssdbq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtoifvzjrd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtkyrmwacn.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtqyroowjm.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxyqubmf.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gttnzwvfkf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtfvplnnwr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gthqkzroim.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gtqlfnarmv.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gthyrqiitz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtfmgqswfd.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtfslrzhmm.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtwgpirnqz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtzclnowlq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtrmotoidk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtvnllkglz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtvzuezmyp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtdgueoxdj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtlrtllzbg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtfdiejbec.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtfmijnyde.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtoidlsegn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtrsnbdjoa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gtfrwoypuq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtirkycjfk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtuxdsnqfo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtgcqlhvve.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtemabxowd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtcykqnnlg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtyhiklkcp.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtrlmdloxa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtwfbibwtr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtoavcfhyt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtrniflsse.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtomrbjfjz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtmqpggffm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gtvkozauei.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtdurnpbss.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtpeehffsk.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gtlepuoieh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtrqrygbja.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gteishhuht.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtpciyorjt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtbskwymdm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtxittwqak.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gturljqbsy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtalzwhpgf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtzrsnwujn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrfvvtnoz.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gtrpliimuj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtyfnvysgk.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gtfirxmnly.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtkxmweqxb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtbjuxommm.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtaomcguae.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtbkerwwda.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdzpbmqt.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gteusntmmr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtqvjqheal.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonhgscep.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtipqovwjj.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbdjdkkdq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gttpkaeqqe.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtfbuwjmvt.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtgpnnincu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtpnlixkjm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtppzvqjhc.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gteqwtplmv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgvzagov.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gtbdnddmjp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gttmenvnbr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudhlnkbx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gthwifhitr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtumzhqelq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gtozppooyb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvgswugy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtnsypwdgd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtaxclqgji.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtgqdwrfku.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtujxqwqeh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtqmzvmicq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxjmdjkno.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtldbwzzhi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gththgckln.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtcnfdjtkr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfldmpuu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtlkldtbmb.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtndipcjyj.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtnzydqgzl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtrreppnfb.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtofgifdcg.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtdagvbdjv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtnclkjafe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtjgjrjgii.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtcwtxfdmu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtxochqhjs.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtgbnsjerz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtxmxiejft.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtktxelohv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtwrlijecs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtakajycot.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtjgdlmphq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtjtyzvewz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtntiiudcr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtmmrtcmkp.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtpltgowyj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtdlbgmpre.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtnmuhqyrk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtvyenngwa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtxzcmkwai.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtiuiwfvje.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtqtwubben.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtgxpctwhb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtbalxmqlw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtcgbcnoao.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtmbivmzok.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtdztnscot.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtqpjncboi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtkhszuyfm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gtlhwdjbky.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtsykgcwnb.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtlkhguxde.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtfhrbrfzh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxfgcksxd.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtelxzswmf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnkpjuezz.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gteibmolxe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtoelvnaqs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtsdotiyxk.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtovnggftc.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtrgzzzrie.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gtqjtkwewr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtrplcmjvk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtgdyosrmj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gthrtfilmi.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtrxxbymvg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtzbutqleb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtugqkvlgz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtflkdvfua.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtvmhotbio.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtpidlsxsf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtykfvublt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtabnmueld.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbhvkake.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gtpjpesajg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtyaiwobxt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gttrmbnzjg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtzajomypp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtcrdqelqv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gtuwzbrbmi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtuczelyzl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gthediovlz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtioxilgqi.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtscuhsqnn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtuhqarpae.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtrekizleg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpssvkhx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtpckclnay.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtkdioanor.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtzboctehv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtwvhpxzdw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtzozjlsen.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtmpgvjqzn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gthcgzxqit.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gtybtxslmx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtnvfazlvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtvjnwbznw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtlupqjgff.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtvorvvgtg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gttyaodkmb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gttrywgxmz.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gtgssphklv.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gthxcesley.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtjmlpfmpl.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtnxqrckdo.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtbjakauzk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtnufwmaob.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtajmsdegg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtvvbvarbo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gtpztaxdhs.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gthrnbxmwk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtqjieyejn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtixvyhapf.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtavwcvdso.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtirlewabh.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbumwgvcv.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtrwqcquyf.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtugexdpxc.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtprnhrbaq.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtwhmsjflg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtarncfmfg.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtvkilgixs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtorqknjuw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtfctfngju.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtvgnvejju.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtjkqhhors.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtdjhfmwyb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtxoyxtqoq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfhugktrd.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtzucxikoz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqfpjsbt.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtmudeasxh.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpemplwaz.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtpanifcvn.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtnephkfms.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtpqjdmqno.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtbhlytaqr.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtcrjgergv.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gtnmjcgwbz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtsmtqteta.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtsgpldshn.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtldhwdipb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtxrecrkqk.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtvcwrujmw.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtxppxgqgv.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtlkfmefri.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmginvqc.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtafvqunud.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtpcyapcqf.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtanxmvkcg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtmptgxlaz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtsnefnvmb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtgaqsojpn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfclqlrpl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtbnbodgie.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtnrcwzmuw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtyggyoevj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gthkgjviuv.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdarxubkr.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtfyizbjkg.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtnrpiuqiw.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtmltfpqmf.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqdbztpx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtnxqxdnhy.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gttjnyqmeq.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gthretgnma.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtccommdvi.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtgtxiajim.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtscjktwsc.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtwhmofoks.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtplgwoetd.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gttmfmlzdq.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtbfaexfna.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtjlgkkulm.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gttwwrfelc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkchkhpj.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtlijhhnjm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtvkbbzhkd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtlmuhwbqu.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvmbbigx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtytigxzqd.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtyrcagzqb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtygxpziou.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtipbkagcs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtvamqcbcz.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtcurqjblx.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtxclpsbbq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtbtvadnib.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpontmxwo.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtionthhla.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtjsyejzho.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtpkjduzos.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtjfmugeju.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtpjadtonp.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtblfuybxd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtmlfgmhsp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtxegxdlvg.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtguepzxqv.html


<!-- 参考信息 -->