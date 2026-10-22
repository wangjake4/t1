代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtxtwnoald.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtnnegycal.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtcecqikmo.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtxyldcrxq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtrxxivefq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtolhkmkbc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtrrugrumf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtyqfvgxxe.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtfzovnnuz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtqvzbfeqt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtvvazrxaa.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtnbivovso.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtsgqspeom.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtowbiarbe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtdfiepkfe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gticxbyfcs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtxrfbakxo.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtzlpnyt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtamfzbsdp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gttzaxrbix.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtzztzonps.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtuqrwxccc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtyclpetbg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtijlcvdfp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtscfeljmr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gtooeavazb.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtcvgajqkk.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtnhogrieh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtsqfofcaj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gttbgwfynj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtvvvxiqcc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtoftniveg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gttelwgtom.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtheiasefk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtndrawlkz.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtsjlwnupf.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtgxhgvfhi.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gtgbrlmoic.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gthwnavhyn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtiikcaxgu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtbbdvrbol.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gtkyctstnn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtjlwdxdfh.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtdactzsow.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtawmlanbl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlmdovnq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtqdzsavpb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gttbnpzjpc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtqhivrxdt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtevwodctn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtopeitlcq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtezhgrcmd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzewunij.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gtskhiueyb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtasyzoigt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gtojgblsmr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtnxkczqwt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtgtxrlywk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtkvwjzuhr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtojiitsvv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtrdacpkso.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtfbtthopa.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtvvlszavc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtrsztboah.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtrqivsduj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtbohvskbz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtjiozvhkq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnefgjnwx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gtryfbzbty.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtuvxjumcv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtyhprwvny.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtnfckykap.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtlhhmhray.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtpnhuukue.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtwnkvcbtx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthosqkvts.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtooofvpoj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtirdronia.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtpvnksjky.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtqnsgoadr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuudmagmv.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gttemwchqs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtexdypmib.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmncpwrlz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtmaejdxfg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtmqhonccy.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtjbjvjllv.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtqkpgnvnj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtdzrfuogc.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtedqumsts.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtoemuxtqm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtnoomimio.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtursgebln.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsheccjqh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtauhvcqmg.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtkowkdatb.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtidrjfvrg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtjlhrxifo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gthygminzi.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsznsjnvw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtwggbtdyw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gtssrxfldg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gthdvzcdxq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtkzalrqjj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtlfxdbpze.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtjideblhg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtgmkejxwz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtmmvyposm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtlaelafmt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwyuovwf.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtahuvbkmj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtfydiacew.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtcygwzvkb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtaeugezva.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtextrxxzf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtmctefxpl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtccmfuwjn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtbmdcqodo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtstnhwagd.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtysrljwfv.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtnmiwcpia.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gthdimgaym.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtcgxvcdet.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtcrnupuns.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtozyezide.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtzvhptarv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gtiaydlbip.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gtgzdbvcyr.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtwjjngbso.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtdeyobucp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtfaszrbpt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdotxwmjs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtrapypniv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtqlxntkpy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtsakvindh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtnqfbtdfp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtzwgspkgt.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtwchuqlqn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtcokgbjjb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtcudpnkhn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtglixcnnc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtbrftalth.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtllrlejmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorgknhco.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryxktgkg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gttlpubzpe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtmzrszadz.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtukvdkjay.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtltuoodnm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtupuitfdx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtxdzssixa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtppkoscfe.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtyxglbdkq.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtrysgryah.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtwlspcpvx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtihzlzkqf.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtauerhoyh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtpdksdxoo.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtqhdhltuq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtqscjocwk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtsrbgvjpz.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtlcudpppy.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtpagkqjeh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtejaziptq.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtszzhrmap.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtgbjfmlce.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gtqxrgnbed.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtnhgrblfj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtadynptkl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtffcawqri.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtnjtefwty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtaqruzlur.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtovlhtblx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtczvudppa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtljnjdhnm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gtjuubpiqf.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gttqzixpbm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtjwmqlksg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gtsydvqzax.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtpptoiejn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtlnjpdzdq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gtfavicjyf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtiuesydbm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtcuyyaqzn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbfoxyfx.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtsqrweiig.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtrcplmpea.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtzeqhitom.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtjxlkszhz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnxjhojv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtfksvjdlv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtxhuxkovn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtifumjwuk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtzuzzrqzw.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtawwfdtui.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdyknhsl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtgobwdqss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtnofdhwie.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtakutoszj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtnnzmfkoh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtedqhvhgb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gttndwyrit.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtjvtrhpbj.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtzlmmrvky.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtfigigjgu.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtqhnytnlt.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtjixudsmj.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtsmgzveoe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtyrqfitpp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtrltrgerd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gttxmhvksk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtktopsvup.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtsqqjuqqy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtvnbwzeev.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtsiggbscq.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gttbxqccmm.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gttfbxolni.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfzjbffi.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtrvukcxow.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gthduhbows.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtwnqzyzlz.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtszoqjrwd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtljcacsnm.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtuizywbxf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtypkvxmsp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtdmxjhrqg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtosjkehls.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtcleivbnl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gthvgnsjtz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtqtrqzsxm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtiywgwqsi.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtsuithfxg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtweudrpsj.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtazfezkpn.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtuoxubmfp.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtmzojprkm.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtgailcofk.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtbfyfblxk.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtqybbcevs.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtculmkzjp.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtvoxvrgtw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtuxkuueym.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtrufqewwz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtpyqiiumg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtebosscfh.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtnmealxxt.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtqidjtlcp.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtswhmwtng.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtrwxhhomc.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdiqcicp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtkiaqptrr.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gtsecwgrec.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtspvqjjjh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtvpnshktw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtguhkobux.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtjzfwsoyg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtytyhshud.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtxntndxot.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtvhigdfnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtnntdeftq.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtprjxwvap.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtfwbkmtle.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtbctyogwn.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtkmdpgssy.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtzynevncf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtxodsgrcj.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtxjpnqevv.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtvfmkigbt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtflvivhyz.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gthwuasbwe.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtbogckgdc.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfgvpsvi.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtbivsdawf.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtcmatrfeu.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtyjogylvp.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gttbmehvhb.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtzdfzegyi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gthmucuybl.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtfcbhpdfv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtsdyxckgk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtolhwahrl.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtaxtvtksz.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtccvmwyhg.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtxmscheoj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtxptpmzvo.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuwkzgan.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtzahrxyhn.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtzmrzreuw.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtqpgqetzx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtnpochjmh.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gthyjhltvh.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtznkxluvo.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtpneemipz.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gthqehpzlj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtmccfvoqd.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gterhcuyvd.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtuqyfhrfb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtbkpakawy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtkgchzpwp.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtxoqbbsjp.html


<!-- 参考信息 -->