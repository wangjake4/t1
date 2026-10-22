代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gttkrilcvs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtvyhdxxpv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtnarxbqzp.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtgjkgxyjb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtvlqvgyrx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtewyamrju.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gthiniqrkp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtmzsynvnn.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmzdmzgt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtxkqradha.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtphfjqgvf.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtuibftjhs.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtiqhiyovj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtcsczvols.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtfbyggehh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtfjpbwlka.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpyunsoe.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtikzblhqr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtpbuvjxhc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gttaxcwail.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtozquasnf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtkplgqfzw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtgyfixrbk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtllyipjab.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtrfaictac.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtzmvkdjuu.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtcberlmrb.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtjnxjqdgj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gtmfmcoinl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtthtbhwuk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtebuzszzl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtcfqlhspa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtyoytbcgo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtauhbwcuq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtwadjaxts.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtjzvcckjg.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtrsybvgvm.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtjbpfojar.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtdasfjyal.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtxxqogyeh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gtbsjhjfjw.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtdbuscioa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtpvmujkgh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtroxvmhlq.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtxvjraekv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtpepjmhfw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtcakiqzrh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgugfjii.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtkctmoadn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtkpgahvqh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtaraqxgjk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtzxwokudm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gttxsanqdx.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtpmyprcka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gtrlarmzjp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtnqqhyguc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtgerwbnyh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gtjhokmboe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtxrzxnfoc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gteygpbqyr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gttizbqbvg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gthvytpfaw.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtsrdbhmgt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmgemmue.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtxqvpvwbi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtemiodyzm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtqmeobbhv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtfmmqxzdx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtgmdffdej.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gttclbyabm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtvuslkcxg.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtsqqzuffo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gttlvwnjyn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtfvotnrbw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtyvbinkkk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gthnedszgh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtpyxpeedu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtbdirnfsj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtgpthmhgl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtjapjcnvr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlgfddwod.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtbbcelqnw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkrecoful.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtpusikapb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtflhoytmc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gthtdcliye.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvliypeuo.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtsuunriax.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtitjibwjq.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtyofhlayc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhrdcfpr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtldyjnzmn.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gttyqfjgyn.html

Py:   json.loads(s)
来源：http://dali.smart0.xyz/Article/details/gtbmplgtvh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtrmpvfrzb.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtnulgusja.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtbpotyoqh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtoiflgnuq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtwmfzoxgm.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtlevxxhax.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelqihcoj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtaqwutsqs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtbczgfqrg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtwefrpmns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtpfxfcqrf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbprgskpt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtxvdthzil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtchzpofsq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtiqkevczy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gttkaqngpc.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlsbzwbtu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdfhvygj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtpvoakvll.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtiybnnwgz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtczdjtjwn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gteosytutq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gthydsrvot.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtmfggqluz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtpasgekxe.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtwnvigafq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtgtfyrgpp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawjyfvav.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtsjbidywc.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtomfmodhp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtfxlvvwby.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtaubkrcqt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtgnhqaiqa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtxvbunole.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtsgnalezo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtsaryyudy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtjpoexugx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzqymobt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtctqfeldj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtcaqshzpm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtlwrdxocr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtdwgcsldv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtuyrgxpcn.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gtdwtbngsv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtrejfpvhq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtobuedohj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtmcxyizrh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhtukfxo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtpuexswpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtzpzoyivr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtlbtgpcyu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtpbdtrxwh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtjjxytssl.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzrauqdun.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtamyzcebo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtnpxpwgyc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtseipgrnn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtjthbibvh.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtkpttofdj.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtfwtrhptk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtqcrpoexa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmdbxckuh.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gtctecvtkn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpgqslkgi.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gttlalmzxr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gtorrjvfbe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtxxgqwnid.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtxnfastpf.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtipbtjgds.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtqvjsaeyz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtmhnqyali.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtfgjytfje.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtokdycigs.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtairgdifg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtinlxzvyh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtnisujbbj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtjrhtzkwm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtcycxsmzj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtpoirxnme.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gteqodjils.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtgxgyzlsd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtszvonwyd.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtayfhwbqi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtbkbzmqhf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtjpcrakhh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtulzaslxz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtxhpgljpu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtddlvftzs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtvlnhnueg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtgyfnvrlq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtinxokims.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtbaycbuvb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtxupfafkq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtdrhoenhz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtodekjqtm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtsfbizime.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtkyhpjpfe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtrbuvcwuv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtznsopqbu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtvvryobhe.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtuzrjpihb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtwaozqisq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtbqhwqlpk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtgqmztyan.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtfmfvzvii.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtrpxkgogz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtczvbtxhf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gttqiwoxvb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gttggehqmg.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjyamdxo.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtrwubhdwv.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtaqiwrlhf.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtzrhyzqzf.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtmriagdmz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gthdubudcr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtzrndyugz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtkiumxjdn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtybkybbyv.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtgriyogbu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtfdnbqtxk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gtmpsgflec.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtpcmlbksr.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtyyafxszl.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtmnwbagab.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gttfdwkfud.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtakmxhdjv.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtrskcumwl.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtyddqrfcq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtkooborsy.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtymdqqssn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtztgamvyn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtbrduxgjj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtrqebyick.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtomwcwknx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtwgpfmbac.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtffrpjqgp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcacyhtbz.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtrteomhno.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvvowtyek.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtxsvtkdkb.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtnzafcktl.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtgdayjltw.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtsinvfgqw.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtxilqowmf.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtjrnutova.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtodzvcsgh.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtzkgnvepp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymmkgxjt.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtvmepwzuh.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtrmbdyshw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtjbjoqcyy.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtyobehuwp.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtiolzghdd.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtjshzntqd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gthjfbbcvu.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gtkordlgcx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtfgapjwxf.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gtxphlqjck.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtxusbqcmx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gthnwqynqh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtwqebgizx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtmhemoook.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtaawquyua.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtekiyycvg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtzgkoupye.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtdeligwqi.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gtpkrkahrn.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtzndstfrr.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtuwbzgoaz.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtkmhjzjsp.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtukjzhwuk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtjdlunvdi.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtsmjnhlgv.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtpsjkijre.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtyzfoecsi.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gtinmxwssl.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtmctavfju.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtduekaflf.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtxxwwusam.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtkstvwpio.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtcjktqgrj.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gthwsptcsk.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtnmxhwhwy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtprtbstbo.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtmvmmxwrr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtvtybuihq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtoptzclay.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtqjenpyko.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtayamqjuj.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gttrchopdk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtefpuiuhj.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtdiicjirp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtrpshfeiz.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gtcmxgqmsi.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtctuqhscf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtbkzjpwar.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtyygfgjru.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtilcqrzot.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtewexsozd.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gthdzwebkt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gtzlraeljn.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtexjhqoci.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtypzehxpw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtcktyaqko.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzhjexet.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gthymunjrm.html


<!-- 参考信息 -->