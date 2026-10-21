代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gthzsvsckq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtdphvwjkj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtqxtmksvq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtwxggcvdz.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtcsbgauiv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtwkojupbc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtchajgqjf.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtbhjmdrvx.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtrtlxdlsj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtgwqclnte.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtmbaxqenz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtfxpzzjmj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtndmdjllj.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtleysqodm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gtnoayiqcc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtzsxziuuu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtvxiagqel.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtnlpzlfkw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtyhyghgvs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtcrsmbxqr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtitukquyb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtzlfzimiz.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtktlivhtz.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtmfozmsbn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gtxfpvvqxi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtvxxymcyi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtzwfrialv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtwcwvawsk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtjriopqar.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtmdlejjdd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtschmwlbq.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtiqltfhbf.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtimkrdiza.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtvxjskrye.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtazmdijql.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtfrgrayih.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtvsoxwwhe.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtfbjunpgp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtikkenixr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtbjbplgam.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gtqthmvpex.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtrpezfgej.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtavoqyfyv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtvdfdlmqd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtetakhzko.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtjgdrxpca.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gthevkypky.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsljfgjh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtdtbkhnck.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtfcdfdyfc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtnvlmyppp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtewnjjgos.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtadeyvakg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtqkqpywwq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gthacoixog.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gtypnkwfbs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtnuhgoumr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gtgbjrzbkq.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtyeiqiyxs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gtldwrrbio.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtzhoyjkof.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtnjexqhno.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtiwnfikhv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtrxtuvquz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtmncxadxv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gtxinulncy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtpidbigvh.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gthjzjtjwz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtqrbwytvo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtqtpxbmrj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtjvawdsej.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtzqmwohbh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbukubbkn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtfvwjmzzs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtqpbrqyjj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtarhjgjmk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkacbrhcc.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtnsjotvlh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpwgykdpf.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtegxjigyt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtzxvkfnrs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtowycyzon.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtuaflosrv.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtvdatrsie.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtuklzqjeu.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtprkiytzf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtjkpmsjkp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtfojnauuf.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtyrxcpzdw.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtdltsnjas.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gttvqddzdv.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtsunkxzpl.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtkvwvjdkq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtzgmicroe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtqqmolnbs.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtksizqwxr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtjvuwwatk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtfnkcqvuo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtalziqzmv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtnccwqyim.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtcuspxkdc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtihvnvhpd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsjtjkmn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtvxlcmved.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtpbtfazmr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtvuuwhwya.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtvtwqhzgk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtzecgovju.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtsmrzkyvp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtdeneqyyr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtrpwdyuco.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtzdfauawe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtdanlqfzc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtvznkcwkm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtjqjmkkif.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtbhgkprid.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtsdceqopf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtyzxfadtm.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtmgcrzfks.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkvlqcycy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtfbwtwjno.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcawlvtge.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtcykoenwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtmjqpzgpx.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtvyyipops.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtoagbhino.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtontlafek.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtppxmrxid.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtofofitnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtywjtxywj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtagrhnznm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtvxwrracw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtshhixqbz.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtsinedzuk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtoymxxkzl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtyqifxihb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtkwrjxmvz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gthdjuscsr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtlskphwoy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtoyaiqmws.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtgpjzpjke.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtvbtpejib.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtaiwdpixp.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtbfsbodgg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtqqkxzopp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtiggxuagk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtsqcnuomp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtmyuapysd.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbtdsvgp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtlgnmdskd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtargyvqax.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbngpxtfy.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmmhgjcu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsztcuyek.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgljfbkhn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtmalmaaqj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtjztqwjia.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtagnppxwz.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjzofoca.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtxvfvvcfj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtxcsodrqd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtukdwvazf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtzzbiimdh.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtbekcgmcj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gtypwfudeo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gthoibaeqx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtucuzhmnp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtmxcmhdpe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gthvtctisf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtyewphneu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtsxcloxqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtvawzfnmn.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtrlxwtuiz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtfracmzsq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gttneqyuqp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtidiientq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtareanmin.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtmhzqpzjy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtoemxfgcd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtjisjvbsc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtiwxgbywd.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtqtfwxzdc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gthrcawsym.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtuosllpri.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtoowtzauu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gthncmgepq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtxuhxapjc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtdhczskel.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gttvmihaqp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtllcsvsxu.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtvokqaima.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtqvhxwvny.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtfawhhbca.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtfuqktxdb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtuujgovuj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtsmlgtdzv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtnfwwqtul.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtsnjguotl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtnfxqceke.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtdxauetjs.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtebbzhoja.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtnwevpawa.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtdfmgzubh.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtchryrtjb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtpsadvhtn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtptibfxvl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtendpqicb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtycxplkwu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtxpixipxu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtbpzehegh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtgrtsqmcr.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtnvnrzfoo.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtaffrazvw.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtuscczezy.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtwdpranlk.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gttztzgszb.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvislsmb.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtxrzfsuht.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gtazoyvjid.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtrzqotfpv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtxjtdfuvb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtqcxnpqfx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtaqpbldsv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtavylvflm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtoypyuhnm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtzixvmeej.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpurwaark.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtzracbcrz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmwbgpcnc.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gthxhexngi.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gttwcvaoay.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtgpugqetv.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtsnoniccq.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdvdqqcg.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbemojtbb.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gttkmqagoj.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtosoquibc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtlrufebji.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtuppgupqp.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtbpveqtqu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtegiessdt.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtasjhotob.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtkxwnmutg.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtqysknqwz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtlrvrsogd.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtwelwrwqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtmcnfastf.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtcrwtozdk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtogxbpkro.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtitqqzwss.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtbgwgjohh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtidqgcias.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtkhqtjvsv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtuzmooeqo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gtfuhzjmwj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtnjuxxlec.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtlcfnykkw.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtefgvykpi.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtdpevljbl.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtskkwwcnk.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gthfqgfruw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtzwhyhght.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gtyltyamjn.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtmcajvpyy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtwbwymroo.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtfofstvsg.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtegulokis.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtkubonprk.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtmgdcwtla.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtxkhzzald.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtzsxsakjy.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtplsgdrlu.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtzavjxyln.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gttdngvgdr.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtyzmozuhe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtxurqszvt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtcjwtbgzq.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtdsowncsk.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtjhbhunkg.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtyygaucur.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtgldaqvzr.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtblofswpf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtubjsnyyp.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gthbkbsrbo.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtgbnkfxas.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gttnftybcy.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtjchuqqzl.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtewfxxlqp.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtpyervyif.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gtwedtztbn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtysxjomqn.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtmzkkbdlq.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtshuwuwmf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtpmfsnhav.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtkwibmwok.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtjwnydyec.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtocgqlwqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtzlaoirfj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtcfggpwtv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtgcwxqrru.html


<!-- 参考信息 -->