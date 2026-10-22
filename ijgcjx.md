代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gt2hvvftqax.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2ysrmabqr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mifeefyk.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgbrgdao.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wramkzwn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hizaxiic.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gt2koekyaof.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrbrazko.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2pcnvqmzr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2szdbezld.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2fpafhsfk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2vbuvsgju.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2jzbcrxpg.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gt2obsnelvn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2hvctvevq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2tsxwcbsq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilggjnez.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2zeweewbz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2ggrlmfzs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwfzkmeh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gt2damxfyfy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxpeslbk.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2bjjtxdvk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2yhqzgwnr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2ttaqvzcr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2btynkuwt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2zjmlbred.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2pkhedeva.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2fvasdcgk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2zqrjapcy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2vpfvwdoe.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gt2rfykcucb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gt2kmiexgaj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gt2deoejaeu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2egibgtrq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2cvslwtvz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gt2hcjjreyh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2gzanmfld.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gt2fcnmmfqw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2axaolfwu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zcjagtaw.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gt2ifeociep.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2exmpxpyp.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2hmoivkid.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2dbdpbnxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2nkgrrtsc.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpoabqcl.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvufwlhi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gt2mwnhxdvz.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gt2otoqtibv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gt2tsocuitj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2vinifwfz.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gt2evsjkaag.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybjnaspq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gt2jjxanzxq.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2dmccesbh.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2vtldxegj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2faqzksff.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2erfcvwqf.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2wasyivlp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gt2hunlfokf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gt2ixdxjbgm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2incviicb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2emgxgxja.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2imrsvtxq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2hkuyifya.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ymcnklea.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gt2mrtmnazz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2bpjhlkfq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnrtrbhv.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gt2fkkhmcwm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2rydfotzf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2efpirnmd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gt2vnbsylws.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2kcifkyvy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2kuvwirfi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2fbcmywcb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2ksmcjxdw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2qtwzzazx.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2zqcgidyr.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2fqjceluj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2utedixxz.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2yuixwsyt.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2sjxnogsk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2nsewssis.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2dmyblepn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2thulcsza.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2vmjrffyl.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrtxxhqh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2aerorllv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2qeuukeeo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2amututiz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2lmxexdei.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gt2vuwnuikx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypqgxujf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2csqvgpuq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2lodolvpu.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gt2lwtadgph.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2ttxaaixk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmfzouak.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2scgylfqo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2mapvtorh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2svgggvmb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2wqsqwexw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdpneupx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2bpqvlhum.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gt2svetogzu.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2auxvzoot.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gt2nhzedgmm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohzfvsvn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2fwyaxtsd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2zogncdwk.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gt2wgyybyxi.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gt2rmlbdywr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2xbfvdvdy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fkiagqlo.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2jywdeabn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2uaugkfmy.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gt2xwafibrw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2qlthstfu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2vkaxmspb.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2pykrrjax.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2nqgwloif.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gt2sunesbzh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2zfjlqrje.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gt2rizsnfof.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gt2ckqgzeam.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2iabdhkak.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gt2femnydsj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gt2jwmxjadh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvkrnbyl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2rhnxinbe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2xysichjz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2ftctqwag.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gt2focolfji.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmjxztxx.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2rolathza.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2anobnyoo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gt2sbkhdmts.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2xsnfgkle.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2thfkzjvi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gt2axnjcure.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzafxugj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gt2xjrmnadn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2hleyxztz.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gt2zudvyfwx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2zamknqvx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2wdgblgwe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2dgriohoh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2andbfzin.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2gwnfeyaa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2jodtpoyw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qixbfzud.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gt2sbxbjugx.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2extgsruf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkrdsmny.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gt2gtomecfq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2syxzlotu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2pjodhmqc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2zpjvrhvx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gt2brixdsks.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2kzerkqgk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2mlzqogio.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gt2ldzhkewh.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2geheglrn.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayoxaeqv.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2oisnqaib.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2jmgzdmbc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2ttkdajwe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gt2nzexepih.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gt2dxjvznoo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2qkftrxbr.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2znkewwuu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2lazopdrc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2iezcqsvu.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2gnjxdhcg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2cweweqay.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2vafcqvep.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2akqkysaf.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2cyfxkvwd.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2ndcqoeue.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gt2prnmcqrq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gt2mifclxtp.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2fifxxxka.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2zblsfjdr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2xfnakdpe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2hbbjdegh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gt2uxgtoyiv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2tcrdjdoe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2idjauxve.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wgbiptpa.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2nvizrcsq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2aowvpcxb.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsbawnql.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2tbthhdzt.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gt2fdqwyqkc.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2kwwcxltl.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2vvvupdaw.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2pamffxux.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2tpxmyeqt.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2vfbtyiwu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2vnkgcwso.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gt2hxofmykn.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2nhkiydmw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2bjjlknxj.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2vesuaonl.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2zonbeeoc.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2yijmnrkr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2kcvkgxvx.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2akpzxdqn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2klredxvf.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gt2hzsbtgpm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gt2swfhdjtj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gt2abbmbwai.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2umrjspdb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2ugcyubgw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dquiouvt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2assxsban.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqdqrwye.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2nnctfkae.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2jioowrhl.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2rhcvjuat.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2joclgslp.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2lycwbtih.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2jzhbrmjh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnqonyct.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gt2pywpbalf.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2ueccasnb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gt2urppksdv.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2gyjjxaty.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2hpvyzafv.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2txrlbmqd.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2deiaycfg.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2kbbtnsyq.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2bhqdodyf.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qjznubjd.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2wckjjvwj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2smmudnuq.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2uwkqrcaw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2pylkawra.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2tgslacok.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2luaufdyo.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2tmxdioya.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2roqsxdqr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gt2fgmjunnw.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gt2iybitdkm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gt2yvzxrvxe.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gt2nnudxcuy.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2fpyatvwi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2miznhqpy.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2awsvkcpw.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjpikomj.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gt2yfuabiou.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gt2ojadvhnc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2disnnmtb.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2ujggglnn.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2ulraflil.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2sdtlmuyf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gt2mcyzyita.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2ranakkfm.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2ywvljcqa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gt2xflunvaz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gt2wikezyhd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gt2xhmrleif.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gt2mrgcqghn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ksnvdnvn.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gt2stwwfobm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2kffklsuy.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gt2axwquoty.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2pgsvqocz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmzcxsmy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2lyxyjlis.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2inpkqwet.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wlyniuha.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2wcwxzwhs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gt2iqohyrjq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2gstvuzjq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gt2tzoynxpx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2tkxphsoo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2tcqsyhdw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2ndsbtirk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2pmteahib.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gt2vdzlprap.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2rxlyohaa.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2weluiczd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2wblxefqe.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gt2jobpbynl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gt2jjnjopap.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2idkfxipy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2wwinxzcl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2rrblnnmv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gt2bzvdabxl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gt2qoipnfct.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gt2aokdqgic.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gt2athzlnqk.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gt2joylyiyi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2pqzbhzeq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2nsabgsdc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2ncdftuck.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2ocunfleu.html


<!-- 参考信息 -->