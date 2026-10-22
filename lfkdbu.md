代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtnxcvmgsh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtjudixtgm.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gterpbgqek.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gthwtjugkw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtbqmftisv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtvxfemsly.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbptqdaq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtnfojddtd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtpygbxwpl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtkkuwhlfg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqejpypdu.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtphdbczts.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gthzlvmfeu.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtqgyfhucx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gtfiqcqduf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtengodqvm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtiywsozfn.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gtafnkggva.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnojmmgwk.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtybeqskaz.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtocqfhixg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfuhteqi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtmfrjccdb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gttssltusn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtpuuyknqi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtxkhwgguv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtocyjkgvu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtaztjdwkt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtonfwvszp.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gtlcasmagm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtewzpmhev.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtylyrtadq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtsveqqnkt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtnmgtqwrd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtsmjarpkt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtigqngimc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtzfmbwfpo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtxrvtyfed.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtwiicdusm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtbbginjij.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtglsczpga.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtztlkbiuu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gthylpnygm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtdniichgy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtmlcoyrmn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtboprmxnb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gtqeqpqemm.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtpzwmrvjm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gtbsagmiga.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gtffvlklex.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gtwidezyzu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtpgzsqzrg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtziesrouo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtpziyrokp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gtnrlwshdf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzmiphrnc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxirrbjut.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gttcktzlny.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmarvvjyd.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtjbkdpanu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtpzwpkumb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtfxeemseq.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmbiqmsot.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtahfkxtul.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtjpekyxlu.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlzoymqww.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtzqfxuyib.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gtygbkydfm.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtdfdhhwqs.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtvzfqqlyg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtlrcwwblo.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtkkuooepj.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtaahikxaa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtepksstid.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtnhaosnkf.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gthyzezqyv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtcnwnutqg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtjyuhwuri.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtidvwbgtp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtfavvwvfo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtqkkeeost.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtuebvhwhq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtqjvxxjon.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtetrcgiph.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiprznzgq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtrynrenrt.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtoqiitgnr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtkhgfgpyt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtetflxsms.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtbvphhptf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpztmnpnj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtqsnpiond.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtykoqdmlb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtnzkrdnga.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtyladrzav.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtqggchfxc.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtkytgymcw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtkadpkjzj.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtxtsurgmi.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtjhubnkkw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gthrdwsxrq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gtnygirjqu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtnkfsnnok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtdgtesayw.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gteqiypsit.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtvbgrcixz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtwhshxfmn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtwhattpvq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtkaepdvve.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiexquuf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gthnknexnh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtracmxjsf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtesbdmvbh.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtjjqvcpxh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gttbrmgbpk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtcrsdsymg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gteroqcvzq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtlzdhbrrf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtdnibklkj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtpyqwagfw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gthkfpyezc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtrcwyefsp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtpzijphmw.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtempcdjmn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtmbqualxb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtzbajnlam.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtqelzzcjk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gtbdeiiwyi.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtpzwmgrpa.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtnhkfswsv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtajzwnufn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlpvmbokr.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtipygrqdw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjbgqihms.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtpkpkxacn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtfipmaneg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtwicsqecd.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtstepwbnm.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtneebsszz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtykyexrvk.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtgeabkwra.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtuksqoftg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtwydvihck.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtjtnmxzuk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtikrhfwpx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtgieidyjs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtzzrwgfwf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtrpfkgkqk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtawoelspm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtrszrdzoj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtkpjupzga.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtupjfbafu.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gtxnplxzns.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtsptnsjzv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gthspggbfm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtnizoozhx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtoyhzxznh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gthwfyjxtk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtjumnkpbc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtnljrbmax.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtskzafsno.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbfcopol.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtceuxmmpk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gtbbzvrynw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqtctcew.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtujyligxk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtipgaiqnz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtocinizoo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtaiuthwbf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gtccwthqxq.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gttcumdivt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtuktzxppy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gtnwgdqbnq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtghmhborg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtsrxlatyt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtqsaeiyge.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtpwndaeyc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtxaucarfg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtztblresr.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtxynpbgjq.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtgdywjzqj.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtfivfezch.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtewhcenaw.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtredpnwqv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtgmgqxwab.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtyfgcbthw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtjplcncqj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtzrjodjck.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtdkqmylhl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtlnwtjqrz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gtjxzfiyix.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gthvvbejqh.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtfgcfjrue.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gtbnaxynhb.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtpgaourem.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtftddykqz.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtrffuihuy.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gteeaxtfbq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtanlaeucn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtanyddtav.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtolskorzt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtwatlxhrs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtoggykcdi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtxlbsgkza.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtovuaredl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gttdlmpjta.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxzdysulc.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gthssyyojj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpjdcmjmc.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtlayqwxni.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmkpaybs.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytvzffup.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtmyxbxpfw.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnetvmreb.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtqjhzydfl.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gtkflldfvv.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtghrjnfdr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtyxfolbzs.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtrnvrmuuk.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtvxzwyyfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtkuhuhlxh.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtfcbxchhd.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtjlkbqkxp.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtubkmlluq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsettojo.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtxborfrwr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtcyaezcvw.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtprbpzquy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtxkeeticq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtvbfgbjfi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtnfibxquq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtcrahotqn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtemhmqjmf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtknwebfio.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtqymtkump.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtykpnnwcn.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtgnomwszt.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtcfkkwnaq.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtvlsipzau.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtefztfhes.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtawpykxzm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtirysyfff.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtfajnmlrl.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtbwacgdwm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtkuytzouo.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtrnzjrzyn.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtadgwvfbg.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gttpqbzvxp.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtmnuelxpp.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqvprxkk.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gthistukkb.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtuizipgqp.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtktegnkbf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtdmnqxpcl.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gteaesimls.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtwgmosdnd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtadibciro.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtpjlpntwu.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtiadjykzi.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtqpxvjtvu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtvcgemiht.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gtwpwintom.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtazwrbubr.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtsnwxpggt.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtipknoqwr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtaijgtqzm.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslhzfiaa.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtztnqpfja.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gthrypvtob.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtsjmcescg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtrisrtudj.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtnsfcatvi.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdnddhgu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtecvyonle.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gtkpxbtjgl.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtwzzbpoxa.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtlljvqrsa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtbwikpxed.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtaqcrkvna.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtwgkvwfeo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtsipobzoe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvxxkpxmm.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtaqhnetsy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyimogftj.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtyliqbngy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozjiqhcb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtzywwhhys.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtobidwwih.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtnkwkgyuw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtuxcbulti.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtbskufzuz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtchcpfimg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtdaoaoybc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtvgebyngh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtgqxqjwfy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gtnxabxzbh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtxkzyonlz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtpnumtipl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtvtfajgbe.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtgpvumsxd.html


<!-- 参考信息 -->