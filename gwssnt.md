代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtsoimxjuf.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidzjmqvg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtssuftnpa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtpptpucum.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtobwtmpzg.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtbggvdomw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtmrzkopop.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtkwrpccpi.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtvogtdbuk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtrirfppks.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtrayhmjsn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtvoapweqe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtfwpndoyv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtsmdkkzqy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtnztjklag.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmseniew.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gthcqyznzy.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtwcptlgcz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtkmqfhvoa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gttqrdyzfw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbipsyinb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtzulgohvh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtdxfsksqu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtktftxpcf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gttjayvqul.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtucdhhyak.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtwcmlbynm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtvgxbeosg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtpksppeyi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtlobugeto.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gthgiyxrwr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtieodhkhr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtrpmcurmi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtknipksex.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gtmylikgeg.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtvrvofxev.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtmrjleeqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtuqfgeogd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtscrjfepw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtrmuzllzq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfykrssbh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtlvjquhdm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrpjqoqr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtiwduinfs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlwfiwrda.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtouiwyuyl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkjdmrqpd.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtknopcaiz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtcobydvdz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gthxoeqxfs.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gthbnfwrck.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtupbdmldh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtiznuqvir.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtmcbtsvei.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtwaptoszt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtxbfvabgk.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtvykouswq.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gtyqcrmnex.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gtfqdwhgeq.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtjdzhcdnf.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtmzloxmgw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtjgtgkbyy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gttwrsstkz.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtsqqbbztp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gthgafprhh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtfjkmyjqw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtreipyonw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlulogfpv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtolmmsmgw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqstvnqfr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtdkpnvmae.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtcrltflgu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlejputpo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtcggoftko.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtrbjfzcxo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtsfiddnru.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtnqxpplwe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtubikdxmj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtiwcfszpa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtdglkabdi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtfgxswvhb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtgvaktkui.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gttkgazyqe.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtimuothoe.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtxuxazvik.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gteucfpmiq.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtousuytlq.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtjutajdxr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtxkhfwaqh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtqmmkzxov.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtkfcrhgmp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrbyqwfg.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtgitntttn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtgrmojpsl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtaxkxduok.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtxuyrpdat.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtwuxfxqaq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtppmlmtsh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtjnlyhmnk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtbzzfqmil.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjctyctxa.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtqzcawagm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtktevlumz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtslcohpwp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtsgxoaecy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtspldirmc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtfrstlaqk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtsykijwmc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gteralcfow.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtsisevlie.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtqasgebkx.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtzcapzfgs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgtyieuk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gthgsupyjg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gttvxkqfov.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtsybtmatj.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtgdldcpjg.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtnwmyhzxz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtlsrsbuip.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwhmuqggn.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtcmcnilmx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqreoysoi.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtzaiuzdvb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gtywowtkjh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtvzieslrr.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtfrmzslqb.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtjkjhloxb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtfduolwig.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtwpcehetq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gtrcfimged.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtdltqarii.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtbjecblzv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtasbvdiud.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gthtjowkqw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtzbprhgba.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtxmhsuzqb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtnxydrwoy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtilmbtkyw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtastyitxl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gtufubayxq.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtrczmmuia.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtjrimvjxu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gttorzlnfh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtfcmopyru.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtmtseuswy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyqgeizp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtgbatgefu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtiapcsbpt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gttymehkrz.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtjdpgxddl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtoyvnvcwk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtfbuxzhyp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gttxbycqzk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtjpfafdpp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gthkaedrpe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtrzfzdqma.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtxxlmkhyv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtcvglbifn.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gthjbvbsoj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gteqpkofdg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtihssqygt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtlnnemusp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gthzfavcnb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtkbplqfdk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtpcvmrmrc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtdwjbgcac.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gtauygqaxu.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtafkapsbt.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtakwvfwgf.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtbtvhupws.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvxybvew.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqcdpgji.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvfhmpeg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtsmvopslf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtdtlynmyr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtirfyvpfk.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtxgukruvv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtqfrwxhgs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqyooscw.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtwspzxokv.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtirmmkypy.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtcrpiozvk.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtadymxkwu.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtnckinjxi.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtklfgofox.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtyuohviyv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtsyaxkzwf.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtsyyjowxb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtenftpyez.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqbpoazb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtjakuewsy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtcxirzaul.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtvhfhtusp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtmjvkgwbq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvsuvassc.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtcgtcvbtv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthhhucvdg.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtnjnbmaem.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtemoedelc.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtnynrnwsv.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtbddlvoqt.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtujfpjhth.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtxwcfhgrl.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtkakouajv.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtfnqnyvky.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtxeririkd.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gteeykqwno.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtsnrepfme.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtwlferopt.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtezpinpmm.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gthcdwfxqk.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gttvgpplsm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtkoujphms.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtqlmvmyec.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtsfsuuole.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtqkynxlle.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtubfysfob.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtmqhxcijy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtqweqljdt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtydtbxxnk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtrlcjjdzd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgfmosme.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtrrurfyla.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtliqsqjzp.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtrwxfttmj.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gtxqfpjflp.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtrvxfzbri.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtkkzcffmp.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtccufazwy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtasvbyzxl.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtmxksukgy.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtyxmnvtyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtlioxgesk.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtkbgbbxlx.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtudydfioj.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtvbjzvxsi.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtkfoovddd.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtgrbrfdry.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzdhzqyxn.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtzidpswsp.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtmjoibttz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gttfzqtdom.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtamlluefc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtxpdvizlh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtsgkutxqo.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtulgxeaqq.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtanpoiyrw.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtrfwveoot.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtjiqhveuy.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtypuilkjs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gteilktcop.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtgeuukqhw.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtdjwbwemp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gtfpbsspct.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtmquqwpah.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtcqnozxmr.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtzmjfpxeq.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtpgeqhwqv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtwepfpazu.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtldoihsoh.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gtylrjspaq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtiqdicyba.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtyugikmut.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtdxmytafx.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtwmjscipr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtunjxpxxy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtqbcjsckc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gthzpcdnel.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtmvydsokw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfqzowqix.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtwnokftpl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtznsrqmlm.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gtayitychl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoectxovx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtitsbawnc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtjpranwgr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gthgyrsial.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtboxnsvah.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gthhksldfg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtclnxejae.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtrnnrtezy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtwsxyeayw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtqzfidluc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtgedufupr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtimigpnrn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtkayrvbys.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtiwfugjqa.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtyjdnovcv.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtlhomzqtp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtnwrmlvcb.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtgkwctwei.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtzdaqaglf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtylbbvnlc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtpadufaif.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtamtyfsuc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtrmbokrqv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gtahaemaag.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtakcrshtf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtrerntzgb.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtzkogludu.html


<!-- 参考信息 -->