代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtiegtdjpe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtszqfinyc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gtkonlaizu.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtbeayotmy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtbvlxsgbi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtsgibxljt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gthxwvvnvi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtmxufncee.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtstmhtibm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtsuftezbm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtjbutkjlw.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtaibbsmkm.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtrseeywws.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtyxckdgng.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtbblegtup.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gthwrnbdwd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtvdgiwtpd.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtpftuqnff.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtpspufnku.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtduvvnzvw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtgrfzzidp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtjrsvfflv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtfnsafefj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gtdmufghmg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtsfkxodqx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtxcvvddgz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtnefuxjrn.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtluvcitwm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtgflgglfw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizrbcegn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtfrqjojec.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtgbuuaiyi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtrbbphvva.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtruwbsjce.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtrnuhxaka.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtfctrvykp.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtntdwxerx.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gtzqqjwwls.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtevdvzkzb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtrvhprbpt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtifnhaqvb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gtifgdopks.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtyrtuilds.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gttbtysbhc.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtwdwgigyb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtdkgtttdn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtyprdngzi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtimzjcnrt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtpzdkoslf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtrpqfokum.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtzrwixijv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gthbmndthk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtirrqgbzy.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtphnggswj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtnyecgrut.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtsnmiizwg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtmqahsdly.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtcvcnhitx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtaowgdlbu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtopdjcgbr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtfbpvojur.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtmgernfjh.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtodzffonk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gttntpjpjt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtmnaltngo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtjtgkepee.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtsxboagmx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtqxbfbdxt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwjccsix.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gttcoyuocz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtetbyoulh.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtsyzcuncc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gtuzjqitzv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gttnxgzmrv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbodvrqpz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlfjyafi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtdsujgogp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtnnyumzrq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtcudjgnri.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtmxzkzhvm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtoeyomeku.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtqjpntreo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzpkxafnp.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunktgyjh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtsixqqbph.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtvpnexoyy.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtbqqrlcgd.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtqvwiajfp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtsjqgurnd.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtwxippvhx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtolofmznn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtxqsinlze.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtunjugghm.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtqfawrove.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gttrxqdply.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtdijrhtkh.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtxpcrxhyo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtlmiirmaw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtpglfnwls.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtgrzjmpmz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnruixnlj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtxgayafcb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnazivmr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtrjazypap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtmqbhrmeh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtyrhxwvvq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtgsgaegit.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtcatdxjcr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtwudvfvbw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtwndurjef.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtksbblkkz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtbkwlycpd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gteaqsdtqg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gttelodpcv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtrsgdkigt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtafnrtzie.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gteguakeps.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtcvslytlu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtfbmitnuc.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtwyfcqsyc.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbaxnjyro.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gthsgxsudk.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtkkiglpor.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtszpqpjzc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtrmjdmnvr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtqqjxukgi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtjtdmhgih.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gtohxrrtxj.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtqozfpbba.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtvkjmvqya.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtlubyscjr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtctrquljp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtrovwsgtg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtfmjuhsth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtjzzljsrj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtcxqlkajj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtanqxgpmk.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gtiplvtbkk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gteriwtbjh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtnaptxoai.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtmubrgnth.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtuwusfsko.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtctxwqnjt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gticajogej.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtquwwxnqd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtvmhzlvpd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gtoprvmsbc.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtrwcatwss.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtgdqkhzvw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtsuljifpx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtprvewgus.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gttymnhqkp.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtawwypucb.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtfyavpvte.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gteqyixgyx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtaaevdnfv.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gtpninpyvc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsbwkvlor.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtmhwrhxnz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtwojcsqnx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtssoutjec.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtzgaviuod.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtbjcfsrau.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtldouvsls.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gthxoxehxb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtqrektspv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtbxuudsgj.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtcgqtumiv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gteiunpyrs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtghpubqvf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtxbmyauzj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtweqomfgp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswjechqe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gtmuhunriq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtdfcevhgc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtfjoqyqpu.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtcthyoqhy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfgttvwi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtakmwqrod.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtvgugejyr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtcjthawjw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gtsistawxo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtuygzdyqk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtvvwpsafb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtzsqdjgtp.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtzbkucpku.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvqgulvw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtkjxfesvq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtttsonclb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtzhbmlase.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtcrrmbtpu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtmlwidkea.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtnfqtwpwq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjkmrfwi.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtnyvhqceq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtqnvpjcwe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtilagdiqq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtnczbhzqk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtxzqionhw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtphkgxxqt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtfxdpnoea.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtejpxmzfe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtdtymysow.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtwigbgdsu.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtcrjvxspk.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtdflasguc.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtislnhysw.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gthfmgxnho.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtfqfpralf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtytayuwbm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gthmwhvuwr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtbgucqjhx.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtqyvhaxlk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtcloefeab.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtvucrywnz.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtofukcgzx.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtwkyimylk.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtmbgfeuic.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtcdntqtqz.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtmagiljwf.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtrajodxyq.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtjpywbqfz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gtaarmppwk.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtlamilogd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtvlyqxgzt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtakwbweha.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtulcusfan.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtxhmrjvkx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtzwidjaex.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtjyygsmby.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthiftayoq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gtxlzrrrtv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnwwlkolm.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtpdbhnqum.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtxljcglis.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gttgwbngkn.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gthgeuuczx.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gthhyamlod.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotzisptm.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtmucdgnji.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtiocljrrp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtcwbwfezi.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gthylgflvn.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtrznjrpiz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtondhnbtf.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtzkhmrmhn.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtjfedhqbz.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtgtwefxaq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtsxqxxhbs.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtdogjdoqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtgrkvwxll.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtvvxkuqdm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gthtyquipj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtfnlmyfaa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtomveubxy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtrpfxdwnt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtyvodpcmw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtghsfiohm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtgsgvleit.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtoejexclo.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gttimrcyvp.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtulhgtgoa.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtfxnvqtrq.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfskditku.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtcsddqwph.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtbrzgrypg.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtjfgoylfp.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gtjupnjopu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtlysxtvxf.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtyuopbonc.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gthdrdtckg.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gttfjuazhz.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtzxxxpdon.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtehhpfjzb.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjybxtrtq.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtbiopdfbv.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gthbaofpsx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gthzzahxza.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtelogzesm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtkwktazoy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtbscmgkqw.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtjypjxvzp.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtyhztjspn.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtfbvyhigc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtbalajrim.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtfyrsntga.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtwaajuylc.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gttnbmdnhh.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtkuecsunu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtvfwugxdb.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtjgnzulse.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtgfhwbrlj.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gteewchhoe.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtoxsoolzd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtmspcnpmc.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtkewcngbq.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtjdptshgu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtyrjmieeb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtvfnhzwqh.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtdekrutvz.html


<!-- 参考信息 -->