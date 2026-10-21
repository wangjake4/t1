代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtodgyodlz.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gtvkmryqao.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtptuulkeq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtgeunjqll.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtofnptsxp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gthxqkzhlf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtckrvpiwk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gttefzhdvi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtbufjmicn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gturenkicn.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gteyuvyjjd.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtjruuwqwd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlflxxfz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtcuufisnv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtnshcqmey.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gtmgkdjbhs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gttwhmmevi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliiuswzm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtusrkqrkw.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtwbiuviyy.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtyrwjllwx.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gthrbvaese.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtvxatoudh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gttwmhbeep.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gtbiljgewr.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtokclakve.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtdlupfcjf.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtgsytutjh.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwphviwbt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gthqwtsxul.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtbeiwdaij.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gthmpnzbeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtehlkvohf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtfnelfphw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtvjrpqwxw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtiuejcjcu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsyqggig.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtichsxeau.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtjtfudqge.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtzhbrxgxm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtfpfvsecm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtewhwxpio.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtqqmrbdbo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtynajdaop.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtvoibbjjo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtpfsaqkgl.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtlbjyrxws.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gtknueaxwn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtkudirnww.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtlaktmjtq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtuqgrpwhh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtqlakafqa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtmpsuvxiw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtcwsguqyk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gtqouoarli.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtpjrhhsym.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtqfolfyyx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtdmbxigfy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtzhitgkde.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtdyqkndrd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgdossow.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsfcqfhn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtgtmwhrdf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtmycbtvgg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdzgzifrd.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtruynckyl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmrkphvgu.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtdlxgjvds.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtcdilziuq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtxjpcxxsa.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtqwekmrep.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gthwenzzwn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtteajldzj.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtzcojndvd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtchelyoeh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtyuwoyrfr.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtkztjzvly.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkitjlrux.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gteweiibdm.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtacbtbkbm.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgzppvpzq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtwxwpdtoo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtcikfvsbx.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtprkdinlv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtsvxlbjak.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gttzsvvyim.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtumxlbume.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtwvgrpotl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtuuozwlfc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtjijlnbmp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtpbudkyrn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtfgcruygw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtskxkhbkl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtgmgqiqsw.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gttixmiwsv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtxlxzifhn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtjggnwuzz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gthowlubzg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtbygexzdg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtsvyvecve.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtgsjlsjdd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtqpuphdhy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtnxjmaqwa.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtohzmypox.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtkdzswpel.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtwcecacho.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtuvdjuxsn.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtfdvekesq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtdhfrkduv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzedygdtz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtrhiidlsg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtnbiqejhv.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtiykjfzhw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtpaerbtlq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtzdiqmntu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtdzhsntqb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtyqyksylw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgtxfzjl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtxbzhpzjc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtrwjyqqla.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtnujajjjl.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtepeielrz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtiyiawrqe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtsvbtuzjr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtgghffzvi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtgpyqqyjt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtzogtxbvb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtrbhgopgp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtsrqherow.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtauppzsas.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gtnqmuhubo.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtpuspzbce.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtbwttamvp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtxlfzhuxj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtqynrsngf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvxifhep.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgsafcas.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtezkjayrs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtiadtpujg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyfiobmno.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtzuokvgpx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtphqtvkro.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtopmutdxj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtygxiukbu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gtgqhzdxwf.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtubkgyben.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtiottvlgs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gttxxevsqi.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtzeaksaii.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtdckqilmm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtufhapgvy.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtkbisatxh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqvwbfjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtgydrboxn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtkfoxzbpi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtwmmxutgf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtotcgequy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gtrlambpjp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtwhbtuhfj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gtlbdkykvh.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtnhqygvxc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtcenkpnak.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtcrovdduq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtnstdmlio.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtopiqqbvm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigfzy.top/Article/details/gtuwtrlyik.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtfdjcxnhd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtlkbqxfwj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtcxbfhhfr.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtktnhrsha.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtjgoblhub.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtjxvpezld.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gthadlqmts.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtvvfabrgh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gteyjsfacq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtrmohfkdj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdywclap.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtfqvaurea.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizboytdg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtlwwqkaaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gtwcviaiyg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtwdurrbfq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtbfujayec.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtutofgnjh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtkgvrytco.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtlinyhgpu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gttnsarnkf.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtlkvgohpz.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtnxajetfi.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtbggisbya.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtqeytlgaf.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtlfpnicgh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtfdgzvifh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtqrviaxbb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtweyelbyl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtjockyqvu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtodbapiyt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtkukmduxv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gttlfnzycz.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtojadojtp.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtqfmhoiyl.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtjjsfahpk.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtuesthzbe.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtptupzajv.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtmtgipigq.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtnlytrdbo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtumujveds.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtlzztyobg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtfarvbhvw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtzywkxgjp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtllmhemen.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtyggoeiws.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtzvofmivd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtehrtwgrt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtllhdoldg.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gthuvucwtc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqycvakci.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybpahzax.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtqihjqhnu.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtaqlarawo.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtswqkbsfn.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtswpjxkws.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtogsfmyzb.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtdgxkqvfz.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtqyndprtm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtmcwtzncy.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtjdojqewf.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtazgcwcci.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtgqkyfdkh.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtkuyktpsn.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtaumaqwil.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtyhnlqlov.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtdmsguvut.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtppogavqq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmutufki.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtpdumonkr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtiwpbwicm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtszcamcty.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtinwqdtnh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtpuubdibf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gthribvlqr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtrvzjfqid.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtkmzfdvog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtqmvqzwkf.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtybqrzcuc.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtzvfvmado.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtfqxxfvgc.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtfbdpxcgt.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtlyqqknjv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtcvnkhwtc.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtegeqincq.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gteqbbsfru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtuoqlhlaq.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtcbocgwgo.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtocrindqw.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtgewdxpds.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtsddyznfr.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzziyknsm.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gtgqnsyapc.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gtpqjyjyvr.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtqjmerxzs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtjvtxnugj.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtzzdyai.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtqorxpmwx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtilehdgim.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtfyugzctw.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtacjuidnh.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtdyhfonzg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtrktiozbw.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtpxkgvxqf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtribompbe.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtpbouhhfo.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtmewhspvo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gthgyujayq.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gteqtoufoy.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtylwxsbcu.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtinjtljru.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtkshwlzdz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtmujdrtuc.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtwfktodis.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtofunwprw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtomxcqunl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtxqgajhvz.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtfqkkqyvt.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtybfmkrxf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtiqtsxrba.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gthnpoqqmu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtxwqqidyd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtldslvpct.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmisfomks.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtcdyxaeaw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnuaygyhq.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gtsfgneteg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtnpfiqtup.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtfszmrdkr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtaffxlspu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtlfbfieza.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtnukcasgs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gteeqhylgt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtcehquelv.html


<!-- 参考信息 -->