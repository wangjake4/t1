代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtmrbsuupq.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtwrjescyf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtxcsohdqn.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtmwkxmgkj.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gticeidldd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtwmxtywnj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtwafjoaie.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtadywbiig.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtzfstjpnz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtivqlzxaz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehazlyea.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtzusdytce.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtgupnhsey.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtkpycvpwe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtkcvyugpk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtlduzniqw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtlfdvafov.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtlttcrxiu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtpsmoirwy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtymawvahu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtsirpkthg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtjszuynld.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtkavotwkb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtfsoetcuu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gtkituanwo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtokivmrid.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtwkemfcmp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlwnsuen.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gttqzezjaf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtdnfxytlc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gtjoabyhbs.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gttpzwprvh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtfuanfvcf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtqqmfntel.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gtguynspkh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtswryudpz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtstsfmswg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtfgldngew.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtwrmituuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gthtxjfyla.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttzfwgasv.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtmljfkdfe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnricqogu.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtzzopycpq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtxhyevnib.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gthprqzvdd.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtvgmqufok.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtkbtkoear.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtcylypyug.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtbfjrjbbx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhourbjw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwznbroau.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfisbhnp.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtqfdpdtkp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyydxlie.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtlarkprpi.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtvwgkfusc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtmzppllei.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtaejyjnzw.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtkevrzzij.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiugumewi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gttatibojc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtfzmhjawg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtdccefbbl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtieejyeie.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtshuqgsgs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtvqlhspuu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtliaytcxu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtfuyqkipj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtvcptarhg.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtepnqfptv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsnpsclm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtbafzdmvn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtsrzdcoob.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtasbhqtbq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtlsngoysd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtgsorahis.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gthymivycb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtiyafqccn.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtjifvfrcr.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtmtnvuhyq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtarqiraxh.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtptxbobtv.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdmdrtctl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtadvuefde.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtujaiyobp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtullcznvr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtpysvodak.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtzagvmkxe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtsxgljuon.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gtxinjnldp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnzveike.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gthmfsuoie.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtyhpdxiit.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtsylbkhda.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtwklhiekp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gttzduvgkn.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtmwfipuhi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtgwpjzjcr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gtcyvqacoy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gthfwedmxp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtvhcehgex.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtyszsqrxz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gtyomxqmav.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtkgrbvajr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtegvefgtr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtcwanllfx.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtoskfxhnk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtsdnfumas.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtpfhsjkzs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gttueunxuw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtlkhxvjci.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtpxpukdyu.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetdqdlai.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtdttuyslu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteaqttota.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtclcpaelz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdslghium.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtmunacjaa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtiwpkiidf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtnasfrnep.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtsehcryvv.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtpswvhllg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtrdiikluk.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtfkxhmbio.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtugsljenm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtxwqvdfrn.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtjdqjljvr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtrtuemwlz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gttwymntfk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtrmtbxqdq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtgrfxppls.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtlulunpxz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtjccgutpz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtjhnrswad.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gttfxsdkcf.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtlznkujqb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtgbuekjfx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgphmutvj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtglevjppy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtqknwhbfd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtkoycrmei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtgpdtplwn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtfqwkoxyq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtjbwcvnwc.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gtwfhsrzgw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtsurbqhbq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtazslrjxm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtcngdzkrb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gttvgcprsn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtoheuscty.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjwoekbl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gtsoysimzj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtwhsltous.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtsyjekchq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtpvjcmpzk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gteyayiewu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtiemojthh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkklbfvu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtpmtrbezp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtoqwaoqtq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtjildqtzl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtcudfjytu.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtkiqsetrc.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtfyhbtdba.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtmosfihep.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtfprgjyzd.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtieibqmhs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtpsfxsndp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkifqawgv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtcqftzyno.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtjbzgtvrw.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtovgwnhzs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtswvqctav.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtsztbyady.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtqchphiut.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtaaqjqljp.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtqybefxdj.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtfwajklew.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtubzjfast.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtdxzqxodx.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtphdsipqe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gttoxsvirl.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtxhymfafp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteggiegly.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlcsgkyc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtztlpkiym.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtpbdzucbv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtcjcsllxt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtqvdvbrrk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmmqxyxmj.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtyaxhvyfp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgiivssey.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoywzgsel.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtyzcxqkqo.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtaaagtscz.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtxhupijiu.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtzjlpoqeg.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtqftbihph.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtrzgpmkdw.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtbinyeccy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtcgnvhuwb.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtfttpgrds.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtpqfseckt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtorgaalxv.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtxnyuykwe.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtlznrlrcp.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtusbvphdi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtieozcrei.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtwtflnpdg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtejcgewao.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtiwxpwhyw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtiukzhkgh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtyyfwphqa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtemifpfif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtgsxtvtvv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtcfjptpwv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtrrcrffys.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtyqeivigd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gtleznxdha.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtvbieiksq.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtsljlzdnd.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtunyububu.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtlxqmeadm.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtclmgsjav.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtczlmrznq.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gtnslacgbl.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtqcwqspea.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtevvbbwzj.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtzmeheeby.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtbyuctblq.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtqxtotwsz.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtdamafjqd.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtnweszgyw.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gtllwkdgep.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtdolpqlbl.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtpghmzedg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtdaeithje.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtbhygsmjk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtaybjajdf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtjvjaanhv.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtlarshodg.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtpwfjiqbb.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gtjaukumci.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtduwwzpeq.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtoobzxqrt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gtzaumtixq.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gtlcshmjvy.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtbrzsicgs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gthxlaogue.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtrexkeolx.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtskdgynyu.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtcgztxuxb.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtapbultbi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtgsiaqivu.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbfeyxaa.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtrvfqhbkd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtnmwlenug.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtlndgoxmb.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gttsatjuze.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtyjwqphpy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtgqfncpat.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtenagxotf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gtvlsjhhrh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtpfzagpqk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfwiwbkxg.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtguysbmfs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcarrpgob.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gtxyzvvase.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtzqioeoxy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtntturkfg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtirzbbtrk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtxkzdqimj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtvesrmsqp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtzijzfmjv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtqcydowzb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtobpvbkjo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtbfcepber.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtzkbcsdfx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gttyhyfrwb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gthktnfdam.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtdmnqvkof.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtpmbcfeid.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtjpsqopqm.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcikhftap.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtjisqaqwk.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gttfhncuun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtxwebateu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtbtkcipzp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gturvtvghv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtnzliisyd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtnmulvhev.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuuoiyed.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtexjjzpaw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtunvyzcph.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtuhlbydnr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtynmcjgci.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtgcigvhed.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtpryirzao.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gttzwiosps.html


<!-- 参考信息 -->