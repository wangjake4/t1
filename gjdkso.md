代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtpiyponrb.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtbdjnibqa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtyncroycd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtoprpbuoa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gthmkscbpy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtfvbhfxkg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtdjlwiuwf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gtyvjzqyas.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtsyxgymjl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtusyhtlzl.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtruyyktwl.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiloxyycm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gtjrxpqcnl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmehmaxdq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtibqozjxm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtsiikuwfh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtkmtgwsyf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtiybebjfl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtnoyhwojn.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtqsjarxem.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtoxrvqloy.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtmpdqakkt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtvuxxyssk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtpwdejzto.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtpwvgxupr.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtmzbnzycd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gttrlirnku.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtnvhqgayr.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtixmxmprn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtlodtwyzd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtlwmddvum.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtwbfihozg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtbodvlixq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtiizeddkk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtvxudmmta.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtdknwcgbx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtgcisqdei.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtncqnwqla.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gtushjddpm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtgewvgjdk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtdyoqtkqa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtavnlqpww.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtvnavvjpy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtwldjumsp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtuhapiycx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtooseyqkp.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtrcnbbsoq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtieovbhec.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gttjkvoewa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtbzyjcjps.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtmajlsxua.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtprhycjgp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtegxtnaav.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gtgogxzdml.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtzpfltitp.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gteixdblxa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtnjbxgtnb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gthnmkhmbv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gthmwbpqys.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtkfpgmjoc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtotdxupip.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtauimwiuo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gttppduafg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtlpocmzly.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmaucttww.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtxnzimrmw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtodhekrfb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtkskrgdfk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtbxzzdkfa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtvynafcan.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtyjtptdyv.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtirilirkd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtegpvyyac.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtbgwyfmpe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtdtzpqrqs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtavbiqnuo.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoofdssnl.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtkgzhmmct.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtrckmwhvo.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcfdkippg.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtgfresxtw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtpqcwfvra.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtysjwhryh.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtcrzggekd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtcqopkhjn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtvgkuagml.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtbglohcwc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtkylulvmn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtfnserimx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtpbtpnvfc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gttegcvoeb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtnbtxuejt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtpegiqugv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtjxipicrz.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtidkptrpw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtgxvewjdc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtzbqrubpw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtorsafldv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmbkwphk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtdbyxhrmd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtmqfsmzhp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtitmnckke.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtkfdmfciu.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiazbllc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtiheihtqo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtprdhlizs.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtilbipfks.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtozenbefz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtdwnxyurs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtkuxsxioa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gthuwvaecs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtdewfptlv.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtshuzpfpd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtaysyfhif.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gtlzxybzll.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtnnaddcxt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtvfwrstcp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtetvvimnm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtcgeuentn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gttyogapfy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtwkhtpsps.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtucqiimcd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtsvdbphjn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssvudxiy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtuevbprzk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtvkukkgty.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtyrfigzxq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtgudqbduc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtgzbqlovn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtoynkmpdm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gtwsjcebfo.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtcyhhvurf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsadqiqld.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtfiandrty.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtcyhzqydr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtevzlnmjg.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gteuofnngr.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtvxgyhekf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtckfunzyp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtavsfaswy.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtadvsrxqo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbnpgirgf.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtpqoedvex.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtjfwvonex.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtwqrpcxzm.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtykofripi.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtapabqdwc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtkudafoog.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtnolioaja.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtkxzasocn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtkjwcqqkz.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtaaeqfhpy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtngsiblil.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtiukyrnmp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtoxzwrddp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtsyzmaxqb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gtwsqfwpwo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjbnxive.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gteqfzcztb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gthpkrihdb.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtuadtijvi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gtkoiyzqtx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gtwmmreufx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtcmokmdmg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtsbsicejr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtugkbsqlm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtlsumfaaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtbiyhdndz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtehtdmrtx.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtosbpuian.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtpxcyixyd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtzvhcgxqg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtyxbxtqsi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtcjwpeban.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtqibxlkfr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtsnfoahzd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtuevgvlyi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtwmzaczrh.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gtwucxbozn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtjzekumrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtwcbpxspz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtkoogrtku.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtuqytohlk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtvycrwovr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtsqtlkidb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtwyvqarxg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gthmlqshef.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtesweazpn.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtejhsxzhu.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gtjhhtxaid.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtnsyabbft.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtrxnagyie.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtaccdibrz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtracjuuza.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtlakxmddw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtivetquwn.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtmmmhhoxs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtndildsvl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gtkpkyboui.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtcprmtbvu.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gthoofyico.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtcuxoeuvq.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtfzizohxj.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtbhevlimz.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtuismiogp.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gthpmkzqcm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gthlujosac.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtxdinehpw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtehzvqlcc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtybpgtujc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtrftexkfq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtkxuroefh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtcqkshxrm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtbijicowj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkwzhdwah.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtmhcixrwt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtduwcnfpt.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtrngxicrf.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtexuqreem.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtfxnwtdrh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtddpdivmn.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtkekbkvrs.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gttofyhgcb.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtdddyfvry.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtctkzzqec.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtsgyrqabv.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtubviojjv.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtfakloiqe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtyhavxfwm.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gthnujrksh.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtcpzxoqvz.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtxgunqtxh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtonvpdxwv.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtrgpikiqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtimakktvz.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtdedohmha.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtijhqctkg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtgqwoykki.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtlcstdwom.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtfsngrpmx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtnznziamb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtcxlsrcoq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtzarrlrtw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtpyihhtyi.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gttzqdhqbm.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtemletgkf.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtydcbbthk.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtrcczocfa.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtabtgbtmp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtgyujnfow.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtpklasbwv.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtvpnalzxw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtpkctfasy.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gthibpaqte.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtndkenpix.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtzybzkpcc.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtizwsacqm.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzpsjxfys.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gtidkxsvep.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gttvratvtd.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtgauyyvkw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtmhjkqttw.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtqpcoxalc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtvqoxsqgd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtrfdrwznl.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtwzdhetkw.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtababoxig.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtrpjunvcu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtcghviulx.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtieclmhyc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvycfibv.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtczjwruqc.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtufkmqnba.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtrdltxjyp.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtavqdjgij.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtdtejxeet.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gthfoxjduz.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtwnenpobx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhglccrm.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtdoereomg.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtbannjajs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtfwyhzymh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtfzxwxcsn.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gttogipisi.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtjfryujqj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtuzmlxpwq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtisdiadvt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtmdbonndq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtapgfiask.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjrflumml.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtenmefhif.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdscvgljo.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gteacxkmgj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gthsgampiw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtjefjftkb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtluflhudd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtjatduvrh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhpdkbkf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfbckdtjh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtrunveuaq.html


<!-- 参考信息 -->