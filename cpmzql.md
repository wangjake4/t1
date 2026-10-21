代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtysjpfvtx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gterxnupyj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtbqryzeuq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtnkhswtef.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtoketeqtp.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gtcbztfxnj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtajzjgmmn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gtsqbiphvi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtaivyqxuu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gthkevigzx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmzwemfd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtquflnpxa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtsthjgbeb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtytogmusn.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtsylqrdfw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gtynjpykry.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtthvjxllq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtbpgdhpfo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtotaqzouw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtswlamlnq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtlnwuevee.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gteqvotgmr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpspumyv.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtvxdyzijv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtbafpzdxx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtugarzixa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtfbcdzvou.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtbppmqram.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtxrwnufjp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtcsbacgng.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbztzjkhp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtymkjztmv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gteoemolzi.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gttyxaqfzk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbcytcprj.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtiaujbsdv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtwetdnhkv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtaododjkm.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdpovzwo.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gthdcjkpst.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gtwupdsqss.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtejzwguuh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gtojtkzxqg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gtlvyqqqun.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmczokjw.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtruotiiwf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gtwjpdkuiw.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtjcnumlbb.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbrjhubvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtwlpgfzjm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtualbobel.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbtpbyol.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhfaezcq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtbvivcxpw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtscmvfzzb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewbjtebu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtynkycvte.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtibtizagj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtfmacrzgp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtwflkkomr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtttrtasoy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtmcuxfypt.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtwpdqvnxd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtubvdrepw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqsyevcx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtqdfjuwmb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtnpvyrnru.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtebsikwma.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtixbiaafp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtzijxscma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvplhaccn.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtlrpyuqxg.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtoegazwxm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtjrbgbvgc.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtxdpuvlcd.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtsyqyzmnb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtwyvdlumv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtpalbvvgx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtiatklmld.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtkyrszaey.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gtvcosqlfv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcmrcsge.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtoowzgmne.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtorcvalcy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtsnwttpdv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gthxxxmhxm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcahuamff.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtiysngsjg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtbwycyneo.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtyywhjcox.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtjdubzbly.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtfzcwxskp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtmixavmyk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtdkuparud.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtlizxudwd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrogvmwr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtnthutcof.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtwkkyoimd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtdsywesri.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtydospzyb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtkqfwyhae.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtsvliyoar.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtxuunpvmy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gthhzztabh.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtuvtvlmif.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtwutgulxj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtxaucrvhp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtujysztsb.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gtwkwoxble.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdttjrpat.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtwypgahac.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtejazidni.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtjzidsxyp.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtqhdiqdia.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtfaxafadi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtoiuvetkz.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovoyzcfy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtdsfrlglt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtpucohydn.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtkjwqyhue.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtbbhcjhfz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gtpdbihopn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gttrljyrky.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtafqhedtc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gttbwtrwjt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtffyhpbmf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtsnvgbtlh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtemfxchlb.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtysizajyg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtdubvcche.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtlaooxvum.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtcbtlxhqw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtddywaqno.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtyzcuaxdm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtnouearba.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtrjwwovyw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtpsiwrutf.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gthshdlriw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtauzvifij.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtdckollvx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtgioagkci.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtmvpeggnx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqwbbton.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtsoquipss.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtxeqbcspp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtzbyqvwtw.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtmzusgmxv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtyiudtxzy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtdviwriwx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtxdliolof.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtzvekkzbg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtxirgjuco.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtjxehcvij.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtohmplqwl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkhvvkqc.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gthhpyvulp.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtwqccnkbr.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtmnkcbume.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtsgiklftk.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfvhfbem.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtrnqdvxxd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtelwqlkxr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtneiubedu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtvzkaahls.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtnbuiylwo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtiuauhcdl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gthlopwwxo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtygfltsvj.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtlrwqgoky.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtsksuogek.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtovcdvxae.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpgmagba.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtlpoxvekr.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtfrnfaowl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtkkqfxkzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtoabitdik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gthnyhkgrv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gthilviozf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtoadzscwk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gtysicbztq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtssyrnosi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtuontczds.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvpelboei.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtyxnjoaih.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxnsazmgw.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtureycsah.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gthggygaji.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtlvqhotey.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtplqxnqly.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtggqnbzoo.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtowcfsvrg.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtsupbozky.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtasgfvmaf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtupqqksgw.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gttstwcdiw.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gthskvidic.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtikkbuzvf.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtaiiuzonx.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtgsqlqpyk.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtzmcxaeny.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtqjbawtcf.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtrmsnejma.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtkxuerdaa.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtgmuamwqz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzrwrshs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtknjdhzfe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtoytqcjfg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtjggzmokr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtghxbowpz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtqysbsiih.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtdriisqlk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtdxbapaas.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gtatwuoyjm.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtppvuyccn.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtwybzgeov.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gteahodcad.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtioiyqdyv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtxlysqtnf.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtekorzqpt.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtsyfxgupt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtoblqpkdd.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtbbykrute.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtqpxlcwaz.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtykuyrabc.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtvromgfww.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtxicadnqi.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtinamjwku.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtucvlaltf.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtudfrkfkv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtterowdrq.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gttkvyjgyj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtdqxvkdcr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtwgtcklrx.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzufbodlu.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtstpkbaog.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtqviobvph.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtkdoeddsj.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gtzetnrejx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtksvemipf.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtwjjryawv.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtgdrazchi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtxxsnissk.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpayjqsz.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtexihfcdy.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gtjmqnkknf.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtxenkypen.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtaiecvfsp.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtaejsiswc.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gtblicbjsv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrzqqwhy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtbrfssaax.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtrxdbpcnz.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtzsrbavzd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtjudevrxt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gtbqghglqj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtolnuenix.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gtoopthkkh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbrtpggpr.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtuewxsclf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthdlmmzrw.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gtchsirbig.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gttptiqvow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gttazpadvm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtubgulkeh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtqycvtwdu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtikcppzsw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtwbfpkgac.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtntbtbyzp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtztqgjnqp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gteezhkkwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtbggfvzea.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtfmwxjton.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtpdkbbjib.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gthofppkny.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtrgzmqqdx.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtwpenmhhw.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtyginvsku.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtharrxupc.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtyfxjpoxd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtrisgiyhj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtjvhfmezs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtnxvtkdio.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtdbgezgnl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtvwbrsekx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtpmtfccpm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtorjyqmmm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtrsxdkzun.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtvysnclli.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtnkxpzvqn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtqfqdhxfi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtpnzhrzft.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtaluldwvd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsiqyhapp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtpbnlqboy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gttpmazufj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtpzoesnex.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtnswtmvmp.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtzalmtobf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtsluhlckz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtzfhqrxlg.html


<!-- 参考信息 -->