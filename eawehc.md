代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtyduzvpxv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtnwidopvm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtucroqgie.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtooxtsizf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtaiilbmfy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtmdushaik.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gtfcpnipnn.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gttgtckbal.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gttirbpdyp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtiisiloid.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtgszqyltt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtkovgvvxd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtrftawgeb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtstirlkdh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtooxtcfhy.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gthrainhss.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubrkyyah.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtfuukdlvp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtrpcdyurt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtqoezrkmx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtbutfolum.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtfbgsului.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtmhlmbure.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxnarnkh.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gthexgvlzc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtbjkkrrur.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtybwxisrn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtsyqpwwjq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtlljseuyc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtcqiukohp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtdjwprlsm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtlrettnox.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtbpilpdov.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtozrtbyvs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtrmjpmmqd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtmarrrnng.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtwbiejcan.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtullqmbxb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gtmqathrbw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtnxhmqqos.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtoozshste.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtjloefsji.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gtyiklcenv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gtywokkugu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtmvjekeaa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtdkmtkeog.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtpauumvzv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtefvjlfiu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtnvuhodck.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbbumwlx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gthwcdtrzi.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtfyhqzbpi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtqblbipjf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtyyoisaax.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gtrerrzynh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtsdvjrwyo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtevjjqisx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gthactoavx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtakuiqnlj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtdqrizfjx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrvrnkjzw.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlekszaqw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtudxgnkmp.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gttmvmdolu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtgrspgcvh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtwdtjwgvk.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtjbteylpm.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtwxpakorr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscuikebl.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtiniidnlp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtiyavqzal.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtwfdmrien.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtynhwefno.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrohnjlm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtmfklqzfc.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdpcqfpa.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtqpidhjji.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtlgadboxs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gttaxzpwmv.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtgdkdssnm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gtowjdzalk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtfagehouv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtbeebtfwp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtbrhxzjrj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtccjvmona.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtsahozjti.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtffnajspf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtuehbumwn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtninomlad.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcjgkxft.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtvwwkkape.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtxmrijaon.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtepfxyipd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtyuktupek.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtnabyriha.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtcatsengq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtdpqragmd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtuwsrexgy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtrxdpyahk.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtaazlpdhl.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtasrcholh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtnqowtjvv.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrdlnaeeo.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtvjrwqesl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtasrtjzrr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtewblqhbm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gthwuognep.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtzpmddtem.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtocqbzevj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtjctunmwx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtugczjdxq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtlhpmbiqb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtnhmyefia.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtowmasrmd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtsikfzaso.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggvskfvj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtfmjfyhtx.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtpmlsppuq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtnwnvtmyc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gtzbcezlhb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtpoznsfie.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtnserrlte.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtzwxokxkz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtdjjjdjki.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gtcellkvmu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtrbotayvr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtgxyjlmnk.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtzomijoxt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gtuhtholec.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtokgsbgfs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzinfxgi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gtldpzoqol.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnyggcen.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gttmywueci.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtyedkfjlg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdojvkrmg.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtsigbyxjf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpqwljsoi.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtptijfzzp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtcpjkuxqn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtaqephswf.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtaeczybbx.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtjanqgcyz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtlhfvzijn.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtdfcezbli.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtlczjqzbr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtotkukhus.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtbskelvfh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtofanvkxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gttredkucb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gthsvrcjxt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtkiiddxga.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shuidangran.top/Article/details/gtoytcagry.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtvmzxnmlp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtecxthzwn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtwynpepjj.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gthywgqwau.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtynjibbwf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtwnimnxfv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhbjaxlk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtwuuizykx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gtlnbayagt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtsselkdee.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gthygbvcgy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtoucviyvf.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtetbipbzu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtchbsraax.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtpvltktgw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtegdiiwtj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtiuojrktu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtsubgfhdv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtfrzshpoa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gttobhgbov.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwryurky.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtivrqyosf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gtstfrwydj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtekucvweu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtqsbyqlib.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtwmytnjby.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtabvljsdo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtaxhsslyx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtqjgxpfzb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtkcmxxetz.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtypndjxrt.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtplqdankw.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtxngidrsu.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtckytfmpm.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtuujvfipm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtcmzeqqas.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtctoqqfud.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtnmknsttc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtsdquzgzr.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtbsnnhvmn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturijckks.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtuatzecox.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtsfhjopox.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtvzfdidhx.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gtjhezmfbi.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwowthhdf.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtqybtymmb.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljfmdyey.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gterumeegd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtngqroxql.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtnmcrdbfq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gthadvybcm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzkgpysf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtblbljztk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtbytzndtk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtguolqtfw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtthjrprxa.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkdzumaua.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtenvgress.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmusgltvf.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtjykufpwj.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gtobmvmdry.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtogkvlovg.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjpdedbsb.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixixrxts.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtcfvdbhqh.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtrfmisrwn.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gttkslwcog.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtjvbpxskj.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtnpylffiv.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtdtdpkkzj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtjnhtbhdr.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtzhendirv.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gttrbpcrzl.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gttykzdquk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtsztoyguf.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtczqncikq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtyuezupqx.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtueybgkoq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtbpngsvpe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtvvdqobua.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gttbhlhwjk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtwcjcslxe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtbusnypft.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtcbdazjuf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtrcscnwvi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtouxfanoz.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gteseugqjo.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gtmirmxlop.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtzqsttadb.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtxczftevr.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtghvrqkfj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtxvtldtde.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtcnbyrkki.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtqdchzzge.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtrgfqosyi.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gtlopxdaxa.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtplrprdkk.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjijohufl.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkdawgqdy.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtfgsxmwco.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtzyxuabmj.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtcxmkbftc.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtggdiudrd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtggcvuuvc.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtsvclzpad.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtdgiyuzil.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtcjiofnmt.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtkjdgzbfz.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtxsimqboi.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtmdnvepjo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtipihkrqk.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtrhcikhln.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtibgjqfzf.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtfgmujhxs.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtldlfattr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gtoufrjjbz.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtdeefylyg.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtpcwqihmm.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtdwqyegml.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqsitsnj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtwjwcuprc.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqplwmeq.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtbzgxypvf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtgneysufa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtscbmuhvh.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gttrewjbji.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtsuszwysy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtkuavivva.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtnrbvmipe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gthwnuxfxh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtcxxeczpk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpyswjuzh.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtohjjrgqk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtivcnmqxa.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtnitxyllo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsqzdhgr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtcwpnthhy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtnjwodyig.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gthueygmlo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtdazdvjof.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtsvteilet.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtnxwcvxuf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtwunmkkcy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtfmtdwmbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtwvyjgxpe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtyerylqzy.html


<!-- 参考信息 -->