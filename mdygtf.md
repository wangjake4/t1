代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2rapcewzr.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2huwhghgp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gt2oigmjssf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gt2fvihcdic.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gt2ezxeccxa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2sppsdwgk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gt2yjnboolp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2dpdrnhia.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gt2dxlomdxr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2ngbdeysv.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gt2cryjlgjb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gt2rhbwfusl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2nmvuxlvs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2gvshydlr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2cmwtgava.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2xjiwftgl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2cpktouvs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gt2pflkzees.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2yzjipotu.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcmwtoat.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gt2gmvhtkkk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gt2ppmhqkpo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2uoguavnx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2dumjsqfm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxojthr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2wzcicnsu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2xufvuucu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2waybyuil.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jnrldrrs.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gt2kxrijglq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2vltgokjg.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2mtuttkue.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2fklfhjxa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2qgprgris.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncrqongt.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfzlfgnk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2volplkec.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2avacdxtn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gt2uekxmlrb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gt2pqrewgzq.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2vzwysejb.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuelbekh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2fvymybdg.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2sckqbonk.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2dkpjbejt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2akdypgro.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2lezxgwhr.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2bbdbpuhe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2jyriktlg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2ieyxuiaq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2iumdelhv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2bbgskqet.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2qxzoeahe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2suqnxvgh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2rmfrqzql.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2pokqrokv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2zdsonekp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gt2bgpfioeg.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpvtzcbc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2yyrapbkk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gt2riuddlra.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2zsbllyel.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2fcqiigxj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzagzocm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2byatfcmm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2mnnxharu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2nhqmgxcd.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gt2eborzihq.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2albqppep.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gt2ugpsrgqy.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2uauffmfw.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2bwthiuwk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gt2rrhdttaw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2fvclgomb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gt2mnyziqka.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2tuvuszlf.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2ozqrrpxh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2qvceymtm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gt2bbhnitnz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2tsjvrvkg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2doiwijnr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzbiugp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2hudiympn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2wtugrbvt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2sxhtxazf.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gt2avrwbqmn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vemljhgw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2hcpjonls.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2rohdeycs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2vsijlguq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2dclmjdgc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gt2zhxbacss.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2xrwzqmsy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2hntetyoo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gt2rwmuakar.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omxaqoej.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gt2loxzjnxe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2hslsnmcf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2hbxzvioe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbsfwyap.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gt2urfmuytv.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2qfrflibt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2udqqlfds.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xndlboyp.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gt2mhazqriu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ysgvuceg.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2kmarnsgt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gt2bfakhdge.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2trprqyrr.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2gnubfpod.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2euczrmsi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2tokwejld.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gt2yioogrpz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2dsqtrlec.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2njbuddon.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2lcvpdbmc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2fihreyre.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gt2jiysoxds.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gt2vcpgnduq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2ncmobgcz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2duivlbif.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2alxuqaix.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgejzhit.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gt2lhiqvqgs.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gt2ktaaaukz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gt2mbjzgnqj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gt2xqimclmp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbgukddl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2yaxwqtll.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2cuatjben.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2uuojrolw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2duxehfnl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2kyyepqbc.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gt2uajyghii.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2neswkqlr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2lshhpokv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2gzcyrqlj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2ubukvdsd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gt2xgpvuyek.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2vupxxskt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gt2jrzoljdo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2lmzjplsw.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gt2hlivonyo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2dgoltwqp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gt2qnktrofl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2katbewdp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2izipvxvq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gt2bqnhregy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gt2fasbcugb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2nyuchvqf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2hjpophvv.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gt2imghhlah.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2gkcgzlcs.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gt2dqewkusq.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2ajyonrpd.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2suekzvfe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2eywnkydu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2jaupsjwp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gt2jkfrkfys.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2ohglvntu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2qprdjoga.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwrdmebs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gt2onfqsmui.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2kuryfjcf.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2kjtyljhm.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gt2hcyabiio.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2oxwvfjtn.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmrqswdx.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2jpqgdexv.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gt2lqefhjqo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2tfrefoet.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gt2vwpfiaex.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpsyuwxh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2lkybnvba.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2fbdpelyz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gt2lqepdhcu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2lakbamig.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vixmfvrs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qbzgjosh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2mctrkerl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2tvrwpjks.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2snlvhyje.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gt2jsdjpniz.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2kpnclcry.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2ouirlgdx.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2ntrtbbtl.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2bpggsarx.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2azypieca.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gt2ihviwlar.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2ltrfxrfd.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2nrmqukxg.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2ujrpeyof.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2eolrvnzb.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnrkbckl.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2dofbxdhk.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2zremhepz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2lokyulje.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gt2zzmdrwiw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2tfanwync.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gt2aevsqvzt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2jupaoeas.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gt2hubrxygq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2vjeusgiq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfrucqvz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2iliezkwh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gt2ckewqgzb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2jxyvmttu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gt2bkpvkuuj.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gt2goqkclxs.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gt2clxurosz.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gt2geryzbkv.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2joeyfduw.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2fvrnytib.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxepgsmv.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gt2pdlgkadt.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gt2xekeyczs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kckgybqm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcsgczj.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otzdbjcv.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2jwlpagje.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2fnscwplw.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2tbfkvlwb.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2jvglgytd.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2wimcjgww.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2fejztycd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gt2nfeeovaf.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gt2uclznijd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2rbalojxh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2olugducc.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2wcnswweu.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2kjshtxnt.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aweirmay.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gt2kjlyyxrm.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gt2xvkwwqze.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gt2klvsywgl.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gt2wbryymti.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gt2lfwqgrui.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gt2miqymgua.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2nrcqmeeb.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2xyjjbzzy.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvmhmgsp.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgltpmnq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2qwrbacuc.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2ryeulkft.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gt2lrgwjwet.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gt2etldeinh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2djzxaiqz.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcugurdw.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2xnepvkin.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gt2qorirwhl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gt2hfuntsks.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gt2jnmbakgy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gt2yqeoedgl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nztuvnyr.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2sokqddtd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2extihgxj.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdrslihl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2kfehpfkl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2jayextgz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2gtjgelhh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2zerwxseo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2nlvolfqp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2aqhwyahx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2kgghpfri.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2koowqkol.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gt2pjzhojqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2shfogpol.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2upnpojwm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2xwrortlx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eiizubuf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iamvyyfb.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2niznltok.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmbxlbh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gt2otepnrpw.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gt2qxvvvocv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gt2dowvxqnm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gt2toozjgqi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2lxfqwfzi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gt2zsrsndme.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gt2qbatcwfz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gt2lprqbsbj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gt2pbkozvth.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2iropzpxs.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohqphlwd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2ajyasnea.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2itptlbbx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2wfoxjuit.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2qmowgotk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2cgwxsfzt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gt2ebhnexgo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioomvklw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2eabpptbh.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2rucqfknw.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2atsumsbm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gt2qcdfszfx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2zszvngkz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gt2ixstrnjx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gt2cmprdnpd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gt2duxwtluk.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gt2hnqsestj.html


<!-- 参考信息 -->