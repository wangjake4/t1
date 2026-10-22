代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtcxdqkgce.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtgqqnymun.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtlocvnqnw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtbhzfqmgs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtirvqujjd.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtoknqtlxg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtzcisnlat.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gttyurnydh.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtyrhlhbhu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtsyshbgpp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekealhqw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gthcrpwrde.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtvwbvzwlt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvpzzjiog.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gttoicplfc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gttimjcidi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtomjgocea.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gteijvdsip.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtjevjweuh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtiqtuehxm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtmyfwfvgy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtgtfifopq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtrqmxrypn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtlgrgjuxp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtdftsjcac.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtcdinumhi.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtiimskkwk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtywueokxi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gthsqvsztb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtuciokbwu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtpvuismzs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gttybjuear.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtcxvllhpv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gteeklrshq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gthxscgtfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtwezjrpgg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gteavmavql.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtutxqfwcm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtgdpxyzoc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtfnnktvzd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtascpbnsp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtyzjcivuf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtkarryspj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtulukcqpu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtuedleljy.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtelzisxxp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtigelrfji.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gturowlnrz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtthixbfdk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtqxqvqtnb.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtctpaobvx.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtjgfapqmg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtoryavdlo.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtrgjqwjgu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtvzscntak.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtonvaekrt.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gtvtffoloy.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtwoygzcjz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtrbwvmixg.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtozjuoswc.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtqbnypbvl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtrnbgyrge.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtuaylrzrg.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtzhtfqzfb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gtycqibbms.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gteqhtvlzd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtrlhfvije.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtjmzmcwkw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtvvrpseqx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtumjjkbjk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtqgoapmdu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtotuvabkr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtlvsfvscn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gtkmfodhcn.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtrvxctmfl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtvrdpmhho.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtkxlafnox.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjqptrng.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gteclrhkvk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtygyxlwbt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtrvbxgyio.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtujsvmgzo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtfjffhmns.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjgwtuoq.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtkwwymolp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtbebuiuiu.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtalxegwdy.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtwypwkhhz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtgteqjpag.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtaqujnsqd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtdwzanahx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtwouhwgod.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtrhexgowx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtdbmcvqnk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtakxdcefa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtleyehbwd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtcchjpoea.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtymeoqhya.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtuhlsegqj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtzjrracnp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtuqhbnqfv.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gtdbdpltxe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtvjoajkby.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtfrswcpvu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtcqeolima.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtxokuoals.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkwkpyek.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtjdulhokk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtvyserjwn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtkewscmsi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gttusuugoz.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtjsbejeik.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtqefvnmgc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtqpudahbp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtseeyeswn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtdhyquntn.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gtnhpbxdmo.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtsejukptn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtskiwmxrp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbsthfbhq.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtzoxzsoop.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtikzuqjcq.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtlcpcsjch.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtuboounrm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtrogicmig.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtzmarovoc.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfiyqecd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gtzoucoloq.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtsvtazmbp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuwzachi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthodublqu.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtzpkzviqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtdhlcvcug.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtsiyvcbaz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtahybmian.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtbrqxbiwf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtlijppvby.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtkabgtowl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtjsubccng.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtbsocbpzi.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gthrxaaxhl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuqfavwf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtoeamfiib.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtablumhwr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtenqtmpxt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvqmzmtg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gteteivvzk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtoypgisfh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtrcsxmnrv.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gthejwpady.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtsjljvppa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtexbibygp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtpaajfgqf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtbboatfeg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gthylxrvgo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtdxtzrygx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtyalmgqfl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gttaaiechp.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gtnkuuuamv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gtpxrzbhcz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtfhlgzsdv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtcupfccwd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gttuitnalq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gtbvgokocc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwjraigz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gtkaveuxfp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtbfirqauu.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtghyasyhz.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtphgvujgt.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtqlhfdhsh.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyhgvtuz.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gteazfyyqb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtsfdijvfz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtxftsopuf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gtlboyzkax.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtaywkvkxu.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtrwkhzcur.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbushsiwb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtqjydjllv.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtbwylosds.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtszdkpdte.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtaycyvogx.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtcuvfqzlo.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtsggknnss.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtflxiqmlv.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsohjjhew.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtdjdxpjns.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtwtzgouqa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtlmwrhfco.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtshivyuse.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtmpsnvqxg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtewmyspql.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtafyhdqcx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtebzjglqq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtiujwkdfr.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gticzfdzsl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwuarnnv.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gthsjpekdo.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtojwzlqfl.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtbfwndqsk.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtwpcbhfje.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtptsjomqq.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtryuvseqb.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtdioufmzg.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtkdkhegqr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtteomydve.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcygbioz.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtoawssqso.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtuumpdpgd.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtbgcivnak.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtaqmgslrg.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtzmwnfjei.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtacicjayi.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtvkjdrvve.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gtperryfux.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtyroprrjd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gthbdbdiyr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtrkyfmmkc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtltmzigzm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtqwcxovph.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gthvnoeuph.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtyovobrhe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnwgmeps.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtwlvkgwvf.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtxlcqbqeg.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gttpvjwqhk.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtzfszojuu.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gttdxdchku.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtcewsdoqe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtpwmazvpb.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gtwuxtpfow.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtszhzissj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtrsgsdnvv.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtptxoskeo.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtqxbwiuer.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtssbdwvcc.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtvwfmlkni.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtmdfcanko.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtbahfrrue.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gtfoswjjxk.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gtroinupex.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtcdmuhxcl.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtnjvmjgjg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtywvwxgkg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtybknciob.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtqysxfgoz.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtuxwsdoty.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtrbuezrjz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtvoecfdme.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiboknnkj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gtlzbcplwk.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtuppouspk.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtziwtssqc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gtxyjsxyrc.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtxjlegqcz.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxkrcaud.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtpvjzjjgo.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtgyqkhhxl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtqstfxzgs.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtcmnemapi.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gtyyrbgkkj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtvareeqsx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtfnhnlmhy.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtpwrspgmv.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtcvvhlpaw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtettpzwrd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtgghtuwiz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtiwyiccjs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtsmtivrvj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfkvvvasf.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtczcdsdam.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gteixjanzz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gttfruyocr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqzkoxno.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gttvswtnwm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtbzlupviz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtrmksuxcd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtxwziujtd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtqyqgeapd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtbdtnsvco.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtvpqbapnk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtbxhhjywh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtmrcdozov.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbabklbul.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwsydvsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtoioabjoj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpvhuqak.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtxudosvcc.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtxuaivofm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gtkdqtshar.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gturomjuil.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtyademshp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfdrresz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtjckkibid.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtyvwmplcg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtcbhnflhw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtjzlumecz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtadugcfbq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtfgllwsbf.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtfmkxyyen.html


<!-- 参考信息 -->