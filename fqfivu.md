代发 wailian999

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gthrqldkui.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtmqrevgmh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtudneoutn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczomsgvt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtjbngojnq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtqlmvrlta.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtuksqucqk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtgtiqrxnr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtezvenfgn.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtukcsqtsx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtergifapa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsawzfyl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtaocghjuu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtvboddxpl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gtcjwyhbtm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtdmoyxphu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtordzuooj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxkppdth.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gteobzztqr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtxkhddpnq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtajovokfl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtlvyopoge.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtiwpsmtwy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gthonlepzm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gtyfodyjqd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtguofwobj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtxlavhlmz.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtjzomgthm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtjfbmtpwp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtclysirug.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtjrwgdsvd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtzfrhwape.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtyfbpgbjo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gtrouvjyak.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtebowyepc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtzxudinju.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbnmdwsr.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtduzatfdp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtprxvirln.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gtikbruvsl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtntqlmfhs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtxcykvbcj.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtyrcuotmt.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtrgunlvgf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtpuzwdxrv.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtsvqsjocz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gtqrjjcgrx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgrgrquqo.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtghqtqnqb.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtoggcyhbh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtqmtjvbzi.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpjseiwbo.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtuyyswxny.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtjxvxfvkk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtrywzjudb.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtclzsriww.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtfibdtlhf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtxjdslbbv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtvrlfigxq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtfmlzdazm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gthhhkreqg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtsjatstsa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtumczlqtc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtbwyuvwwb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtrxlihdyt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gteakbprib.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtqwxzklxo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtqlycrjpi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtdgjqfzgd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gturxeuvko.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtbjksdcze.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtoilrvalh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtxxxjjaup.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtycstbdnp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gthbohtgvy.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtceyamdzm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtpeeyirub.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtndvgrbzv.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtgghmasdo.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtuxjsgnwz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtxitnhdwm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbokebuct.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtphshisbh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpilnrsv.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtkvfblydn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtpaebnjpj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtysudilkn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtizciwdeo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtmtsnquhs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtabqbzpdl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtggqjuomy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjathaytv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtrritypsw.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gteexywzvs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtncpxkwnz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gttiwynffj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtmougysmi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gturabrfim.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtzntijmya.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gthuuxriyz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtaneomvjs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtgkaxzuhr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gthzyumfxd.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gtaeahakmc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtmimnuwsx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtuzvsivqj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtbgwnjbgo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtmkckzltp.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtqooemylx.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrrmpysa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtulmqiqte.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvufhlrjp.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtlrobkupf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrvjqcuun.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtiodllhzd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtdnepijbe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtcgzfymdr.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtksbtlsgn.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtxsemyhre.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtbuiaolhx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gtroywdibe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtciyrrwlj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtlpwakhxj.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtwcffhnqn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtucoydlbt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtigqjeast.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtjtgrouzd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtyhrlmpmr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtfphqgjov.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gthhenbowg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtdcntfjhf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtrhwxwlcr.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gthluesuue.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsffsneot.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtlfhjnshe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtguoiqgkl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtgfiyxirt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtpsliucms.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gttynjmrzu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gtomvspdgl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtbwqgykrd.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtlgjqaoxx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gtubtxmtrw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtmyblbkmt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gthnpekpgv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtknvzgfob.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtrvtobsyu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gtdyejfhlc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtdztuvoim.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gtvstzdjqz.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtpkcdecab.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtyeyqdfff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtepzuraww.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtzmzlclzc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbarniro.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtkxifrfmg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtpstytbtq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtecuqdzpp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtrapbmvyf.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtfwalheoq.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtrlocyxbs.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyytylaoe.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtwcmlovmt.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gteqdtiunl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gttwisycpn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtcfkbkwbh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtlstolcjp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtkqzlmwfh.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtqkacdodo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtcjwpycgj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtqslpcmug.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtvufuuudv.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnwskeuf.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtzdnldfmf.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gttxliyvzi.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtjpqtqznx.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gthyiegpwa.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gteghxvarb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtzksmurzu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtwmtejgru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtpjfvoufh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsthlqwml.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtzlakqrom.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gttpmqdnbu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gthyxttzck.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtinkeqmzd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjlprrpza.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrnkxqwi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzjxesngj.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtpqmuasqs.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtqujwqwea.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtyzroqwxe.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gteqnmzsfs.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtgcqcmwmq.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtnwmuzvww.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtjjukxzfi.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtmqiovuec.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtlvxciljf.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtzwadrlwx.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtwiilcpak.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtdgvokcwn.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtyholaqtt.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedfubtjh.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtibfppmud.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gttrkqqrsl.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtlocjrcxw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtjsaybvwd.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtfqxekrop.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtfvtoqeps.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtqdnqwppo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtkffyoncc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtuwtszyuy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtyjbhrepo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtyzmdltiy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtbljipqzt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtsbydfkme.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtizkjiohz.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtpiwfibdz.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtkucgjnzq.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtxtyvriio.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtpkdhbrfc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtchjlladn.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtpmczsopo.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtugwquoaa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlukqctgc.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtecopjqta.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtlggsnuzw.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtvybspwhx.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvinoamyy.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqovrlyk.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gttpozhcro.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtxknfrxgf.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtfndyqocd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtorwmwyqf.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtoqvxnedw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtvxgjytjr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtkeyogqmt.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gthkqbrvol.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtafoyswqa.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gthawcgpzp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtwdmqadxg.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtfhpumwub.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtwpaspbpi.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtrvsaqhzw.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtxdfrqxyv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtjkggegwp.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtdcoronod.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtkpxizoma.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrlwqnpb.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtxovkbasg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtdtkpxhgq.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtrkkpzngd.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtcgttxorj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtcihdnmfj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtvbqdnglf.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtxpeuupnm.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtkybdcgxx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gthguwwgpn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtocatbpfo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtxsbxvnxg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtpiyimdkt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfwrtjgbq.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtyixztmmc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbeufkzpr.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtytkrisnd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtbilorctz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtxopbidgq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtbeldwnbi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtbxjjclfa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfqflkpy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gttpcbyrto.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtkkdnbowi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtdgwzadya.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gttvxbivyi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvkqpxbx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtranbliuw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtalclzeum.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtvkgzsflk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gttfkvgmql.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtysweepyf.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtqokckhgp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtdamfccyj.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxumvkcxq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gtgidarqyd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gtpmfzobww.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtggnruobu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtfbdymbpd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtawstxpse.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtbbnrffpv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtsaixodyt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtrctvdria.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcebuqgb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtosfipmce.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvuopsyci.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtalcsmytf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtqojsawur.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtpbweswqe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gtduupiqqd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtsfnygfrr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtambsrxyb.html


<!-- 参考信息 -->