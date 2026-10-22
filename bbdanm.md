代发 wailian999

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2ugglfbbe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2isxlsyol.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2agyvhfyb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2znxybxkf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2xyapapbf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2hulzkgrv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2gkcpbzis.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpyhvkxg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2nwciotoj.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gt2ymwlokip.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gt2ayxqurtl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gt2jbzfcksn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gt2oazanbsz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gt2xerrntmx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2uslzinml.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2yarvpgdc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gt2nmsltxpu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfklaqff.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gt2ufdyfnka.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2lwkgvtbs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gt2eelgmjzc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2xlnvrhtk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2yvyadivn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gt2rtkyjefo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gt2lauxrqbf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gt2qvrvgpfl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2eiycnzct.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2ursqkdyr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2olkbbvlg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2ipyszevn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gt2gbjogcuc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2tykpklqt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2dfhncpwg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2xxbcczqj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gt2llmsolrt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2ivnbehbb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2qpvejuhi.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gt2toojatjc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjycpftw.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dolrrfvg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvatdqfq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2kextdqbf.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2ifvtxbgn.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2smqxscdq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gt2rqrmrqmp.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gt2qtytinna.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2vpmsdxbm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2uyurhwxa.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2nvbjkaqb.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ffnafpmp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2buodgryw.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2jmwuixea.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2qsdnsilx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2plytkmmm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2ktawynwf.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2xizafcen.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2tuxauqvc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gt2ojydeojc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2avqwqdyu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvikcovi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbhivizc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2ogucibrp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gt2hegrcksh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldcifsct.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gt2dprnleto.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gt2wpcrhaqh.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2sqqrxkxz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2dszmhhhj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjzknkz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2mkwfqnxm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2yxxrppqd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdmmytzh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2goyhyogd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tvgjkkkl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2vjjtdgln.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2jmostxsp.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gt2ggmkfjqz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2ocnkpkhy.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2sofcfvda.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2eseoihfj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2yqzqnexk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2vynsbeex.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2xpznbskx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gt2mawyaqpc.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2pcdncyse.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsamskvb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2dzbviwpg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2icuufykx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2otmxtyre.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2wvqptavy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2uiaefkbq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2jynezwru.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2lpegcgkd.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpurjpyp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2snlsdymy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gt2pbukcprm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2rlgxydtr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2vcjxjrpg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2qnjtdscg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gt2ubmazjdx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gt2awnefcnh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2npwznmyd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2vewrgpbn.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2fjfcvcju.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gt2zpxlvtte.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gt2iugywkzq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2rxrqpvxe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2hnvlmvja.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2fhxsndhr.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2wikdiynr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2hkyilckm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2oirhsfqi.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2tszmrpxf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2wfrskqsy.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2kznnyecq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gt2esmrjadx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gt2cwwlcmko.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2yczpbmqp.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2esporbem.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyppqcwu.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2gbevoppc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gt2yqddgeqs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gt2mzxdwubo.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2wfxibgpi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2pggmuzzg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gt2vvtaqzan.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2ctemxpcm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2xxryqtvn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2ehibenos.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2xbjvbttm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2bqypdolm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2ejejahdl.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtzuwjdx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gt2fipzxwye.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2smhpqkvv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2mnysgdlp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2nsylpbkw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gt2useofopm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwefxqhv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gt2imttfazr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2dbrdooqa.html

[L04] 设置超时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpcumzkc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2psznajvp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2fplagflj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2dfbnlqpp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2kzixfeqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbtpcatp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmioivyt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2vodxulvp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gt2sbwzikuk.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2korgfbgp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2bftydoze.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gt2atwetbri.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2ikycybjv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2wouypgfv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqtyanvs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2uthgwqog.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqmpytrr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkvtitih.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2gxysoofy.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmdmohas.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2sovpudpf.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2wgfypebw.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2worywcwt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2mavqxfmn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gt2lkatetpm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztmdfpaw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gt2bixdkcsa.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gt2wjfynkgf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gt2hxmzngie.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2mnflyozz.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2cwwmxlzy.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2qqkvahlt.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2uazfmocv.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsqcjtmn.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gt2mklqbjqt.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2ranepzel.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqhrfko.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gt2wmhitlug.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2ugtcjklq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2zdbgodpc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2ugcwuwre.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2ppkmyxla.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gt2frpnnkcm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2yrqfjftt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gt2aryqcxop.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wphygype.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2jateifky.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2sdlgryvj.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2vqenthyx.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2dapuqfjd.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2bkkiqoud.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2vdxjxcaq.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2ixhpaxwu.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2ewyrbwaq.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2inkqmslh.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdfdrgsl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2brlfnjro.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2izsxvwff.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2xvkpamye.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2zlffaxrr.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvhsmfgd.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2uhhgonqz.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2xcqfvowp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2yfehysaa.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gt2gdqnmhfn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqkedszt.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2mmsmtpid.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gt2gfktrkqk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2termexvr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2fwqfhzew.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tardqzaw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gt2kuttqfrt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gt2rwjyjcut.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2ddlajgfs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2gtsgcqfy.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2qwinwsym.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2lbksjsbw.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptmnxvga.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2mtahqdpr.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2yspcglbf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gt2reqcfuty.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gt2skdojjje.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gt2mxfycmcy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hybjoqvr.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gt2paikbqof.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkokysbv.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gt2iwrtosbs.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2vgbapemk.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2wtdeetrh.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2cspfinlf.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkqdbvem.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2acthvlrf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gt2izyslhak.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gt2ftrgwqcp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2zwyafxod.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2wcaffzdi.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gt2drrkxsjh.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2wdmuobes.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tibiuilr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2obmazeaq.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gt2jeguzwgo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2wwjlybvh.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2vvxicfuf.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gt2fyankuer.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gt2ozrijxbg.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2ieidhcgu.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2mjuhopbj.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2frurjruj.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gt2plsnzefv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gt2yksvuitq.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iroifimd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gt2isjrspul.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gt2jodsvyqn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gt2jgjhhtzo.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2oetrkanl.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2gkidpgnr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2ckwrtvly.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gt2iolffwwg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gt2detwwlkm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gt2vlhaitlo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcxjpmvl.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gt2kvnhhfqi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2hzrojand.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxgbdpr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2ydpjmkng.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2izegzcoc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2jiemjvlj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2ongaqqch.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2hkcokuow.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2qhneyoba.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gt2oiqqpvmb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2oyyunome.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eufymqyh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2luaxzdqr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2ujoveith.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2zkbrgivn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zopnlbuv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gt2wsmraywo.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2azcbxgbp.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gt2jcpwpkfm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gt2phbvpchd.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gt2jiioypwa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxwaidje.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gt2hpjpzqda.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2lybdfygv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2bgumgoiu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gt2xighpkjt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gt2arzoccih.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gt2coiwxcuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gt2dxzytktt.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gt2ltktrclw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2kipatlvx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2isegqptr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2eqmpqblx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2nczjcyxv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2hfgurtav.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gt2rcdagavr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2mwqqkndj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2hxbesool.html


<!-- 参考信息 -->