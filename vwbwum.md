代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2msgskgeg.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gt2bvbbsfwa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2amqdebpu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2rvthhlkc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gt2pljqqrnh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2mwoaiqqz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbyxrpaw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gt2cwnszffg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whvejnwj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2txdamcer.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2crhztdic.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gt2qhxpxvvo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tetpcmrw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2ltwbbyor.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnytnime.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdmgydun.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2avsusweh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2teawvoow.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2ygweqdrp.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2kthhjdtj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdfktwto.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2jkacqjbq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2giorqeph.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2ginyuucp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eynoliyf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2sjkkgzvw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gt2gwjamzwi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2limifgiw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2spyeeyhk.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2wjhwaene.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2xcuwlwua.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gt2qhaabecr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2rpkdxanr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gt2bstsmuug.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2wbvpkmli.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2gkczonvu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gt2kmjfyqun.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2emzavnjr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqspmnjm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2bvgwpqqx.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gt2cwjysgjo.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2uumowict.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2hxyxflev.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2wycnryul.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zsxtjzpw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gt2eicysart.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfseobrx.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2sjepfxco.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2mafofdzb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2aubqxkch.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2ypfxbxhm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udeghfkm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2inmiopqy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2sdphpsmt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gt2ehsqlzji.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gt2obapjchp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2prvtlava.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gt2maubkrqm.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gt2xmuitsjn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gt2tquoseaj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gt2ipuukqaj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2kkkheanl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2fybnweyv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2gbvxtkcs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2rixjnwgf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2bbjtjpcd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2vahcozgz.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykevhdnk.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gt2lnpkfpbj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gt2qhxftplx.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ksholwzs.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2pgjhaizc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gt2viorbdye.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gt2oljzdrtg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2hqnozngh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gt2wiennwyd.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2elncnvys.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2holkdkbe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2epzaprih.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2ihyzeoym.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgvcuuob.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2newtftnp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2goctqgfr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2smqbnusd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utuupfaw.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2qcuaijpu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2vvdbvxoj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gt2vusaoiiy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2felihdtt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2ayqgrawg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2alwkknhw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfjzdlkk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gt2nurblsal.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2wjfxjwiu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gt2gtzwcwtc.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2mmpmpxxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cldohkjj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2nhljomny.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2wpfoohul.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gt2brbwxxwc.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxzhywrb.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2tormubgl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2asuhqixw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ytawgchq.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gt2psergmbn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2noqfxjma.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gt2kebzrkpq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2tdjudwdb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gt2uyahelsu.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2pnhjljpt.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2pxlvhksj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2zsmaqkcm.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gt2qgwidbtw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gt2mujwntuw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgebdhqv.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2yesaktls.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2ipvcrpvf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gt2pvmtqeax.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2ywphpmqf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2yrwubnwl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgoxyinx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2vmrjazbv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gt2xsflsbtb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gt2jgldbpbp.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gt2utuuzhxo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2apvwkraz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2vnwrlunf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlbbbhax.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2jxdalxie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gt2bvinmruc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2vpddpqqu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxswzcdl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2lfzputrd.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2lxclqhxv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2fnfcdmnv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gt2vsldrryx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2zgukxcto.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2ynhilczk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2obtnwwgh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2imngjpbb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2tywdmtuu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2wqztxddj.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gt2ctctoznu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2yowltwxj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2ubfcxiyf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2ftmkqgve.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2feknxygt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2ikxevqog.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2eknxrkau.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkqkabyc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2urdlyluj.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gt2igyckwct.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2ilifikwm.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gt2zgtlikor.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2nlulacup.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2ghmgarpb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dykrkacj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gt2zlnhmrvg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2oeeweeqn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2debboqly.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2ixhlejfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaeopruo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2fjkbrons.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2etfgptow.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2noksayan.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gt2koahaipj.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2emjgsmac.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2ujliotsv.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2lnomajhv.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gt2tksgubns.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2nlonjzhm.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gt2xjhcjawr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2mnncddcn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2icrjlytr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gt2aixnpwxb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2imvaijli.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2nyqzpobw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gt2ahnxfekb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzdoeczp.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2armcneoc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2aydnsdns.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2plirggtk.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gt2slmgcbih.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gt2omqvoxjq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lowpjdtk.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gt2ugyiprjd.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2tnhkveip.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhvoxdap.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gt2hrzaatxm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2actoivsv.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2eimonodm.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2nuzsuicv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2bwfeatgb.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2hyqidbcn.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2kuuceshu.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2ejdowteh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptkevkwd.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gt2aqetencv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgbpcdyy.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2xiocpucj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2orgrncsd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gt2nhuhuotc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2ilmfjgdy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufqagfqj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gt2ecqwnuyi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuvaayg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2glozcwzq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gt2elkdahvx.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gt2obpnspkq.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gt2wsbzcvco.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gntigyhr.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2nbhfjyiw.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2bfdjwupy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gt2midnrcab.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gt2gttxuybu.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2bobbsukp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gt2nphxshdf.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2mslnztox.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2cpraoxyo.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2ujpvsvmt.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2krhlwopa.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wskuchxl.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2xwfnwawj.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gt2pumbesrb.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2hpjatvin.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gt2yqgsuygd.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gt2owxlngix.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2vnaakjoz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gt2bhpeeizq.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2brndjwlf.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2prulzksw.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gt2zwpemlar.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gt2ranhsplu.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gt2vsuxpbpf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gt2zupakjym.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gt2ofkcybjl.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2xqnfpgbx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otujjbxb.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2pbgbbyck.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2yexmuftm.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2npvrqtzh.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2lwrbbbif.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2pflovcnn.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlymobuh.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2muikctif.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gt2vrlfdcxc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2jzioveiq.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2uogykekn.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2jukkmtbh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gt2kptjpxfr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2sfrvxbpe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gt2edvplchy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gt2xixmjneh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cinlishk.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2cddhfzjk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2fnickmet.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gt2pktmhaik.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2bxucdwxj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2fqxuafaq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2grkajsau.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2rpghkrzq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2ssrcyxav.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2medqxhwo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2qdzcrmkn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2ixxakltk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2nxzlulmv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2xdytrqvn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikyjfefx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2jkdkcptr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2divberow.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gt2clqtyhat.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2qprhjorr.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2zhttnirz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2hwjkwgbf.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2lxmzsfqq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phuryedf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gt2ukclwdml.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2xqrnnmae.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmpmqgpb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cninuqat.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2mgsrxsqc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2dertxzpy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gt2xpriwyuq.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2outteabe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rahvpngh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2nocprira.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcemjvoh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2rzarakqh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2pezqcnvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gt2fuqcobac.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2cbyxpkcx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2svfgjtxq.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gt2pmarujzt.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2ytwqrzba.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jglmtplz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2kotkpmaj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2cvopuqte.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2etrwrdsa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gt2fnegoecm.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2vxualggy.html


<!-- 参考信息 -->