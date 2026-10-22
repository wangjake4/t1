代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtnftziaft.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtehtkbdtm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtyfnqnyre.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtvrlrulrp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtcnworbfe.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gtprlamegc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtdhjvfhwd.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtmnnecofz.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtxfvipsuz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtoqoopqkx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtiinlbpos.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtfypseplf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtyjslyjrs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gthueijvsy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtcnvtjqyx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdssdrqn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtuxhuxulf.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjgtebkf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gtrtwiewss.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtibxconjo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtbenalpby.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtlbzmgmqg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gtbqxteaek.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtjmaxwchc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtyvzentrn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtbylngohw.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gttqgdeopk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gttkshjfph.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtcyhezerz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtcqkyssum.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtsdivlxax.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtyucyvymt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtwvuvovtf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtczbyjius.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtbswkohlc.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gteuijuqds.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtdbchkgal.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gthiuaxvtw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtxuvqwkho.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtohcfojfs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtoaiuqmei.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gtpzkvtulp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtsxqkevbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbmwwwsi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdxjavjwk.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtjffhpceu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrckiujje.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtmclrwjkv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtlifwrkvv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtfxyhnynb.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtdsrezvom.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtoadrhwww.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gtzgpwnhba.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtmjuqnrqg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtqvrslvzm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtkcrvgohr.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtrkbecuvi.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtielymfle.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtecdlelud.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtpodoelwu.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtoklfgncg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtmoprjhag.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtlkvuuhyi.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjuqhyvya.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtypzpvevs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gtfdiayphq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtepefklxa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtcbcljkvh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtcaakcthc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtoplltnbz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtlajnscot.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmxhvnxb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtujxchzmt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtpexxdcwm.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtnfqeqtuy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtlishpcjv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtcyxczuyj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtmtpouvjh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtxmejttoh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gttmjfqzth.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtuvfsnbfu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtjlqpsuie.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtytfhtwsl.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtynxjgkzv.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtpyveerzm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtvnlwdtzh.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtfxblmwyi.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmkowgnca.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtikzqqhsb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gtzbsffwei.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqitpruoo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtkmdhwaqj.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtpyetxncw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtfeoclyyc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sysykeji.top/Article/details/gtonyeefqg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtpjgitjch.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtwqoolljf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtpuztmeuy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtpsloigsu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtweybzutx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtrgpqynpd.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtccblyqdh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsoblpnb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.iojbl.cn/Article/details/gtuhbdsgon.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtgzyroqcl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtubdbbmtx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtdwddepaf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtgcgjpftk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtzgrnyvuz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtnojgycsb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtjveevdoe.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtwuovzmtz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtqlxogtag.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtxcqxecol.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gthhszpbaq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gthipmpuob.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtoqwovogn.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtlurolmwx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtssmhbodx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvmjnilif.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtoyuyqkxd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgcdwmfyx.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmifdnspp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtojqtgswc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsfxiznt.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtjvjayypv.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtfnthypxf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtwxxwxycv.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqjwbxzy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtepivqnvb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtunmgtqzk.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gttmdwutut.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtloaqxbfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtkeditiml.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtfsejtfbj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtnjwqgdbf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtoalbuhnz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtudkkfqbv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtltwvxdtr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveojzarn.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gtdytqpniw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtafqafask.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gttgjwhvtn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gttzkmdnsn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtpbtdryfx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtwkjunvvz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtvnnrnryh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gtbmhwemto.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtvgdqmjvm.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtoxhmaqam.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtskoujccr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtglxmtvkh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtbgoqubpr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gthhzctvab.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtmrpucczk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtrjiwrxlm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtjpnuhudi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtofjwamxw.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtroyelcua.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gttsdfavul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtdizrrmha.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtfrvflanu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtsbrugekt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtdesdyqwr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtjqciemwh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtmknttlyo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtjcfguwss.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gttohjfwij.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gtosvosaii.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gthkfgsgni.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtmpfxiada.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtivghahjl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gttyehjmjc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtablulzgz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxxktvmo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtmojykgnr.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtycnqeuks.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxydciyn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtctyigtlc.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtemnvwoza.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtpmywidab.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtikglrtyi.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtniytwwao.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtbovnltmp.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtjeyneigo.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtzwukypzp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtakpcfxrz.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtnbuzyrxx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtvskbvnyr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtcmerrkvv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtoinbghcz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwhfjnlq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gtocacplph.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtywlcorjx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttnwtbyug.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtilfwiwaz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtysyectnj.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtyipmlnbg.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtmwmstisi.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gtbdahhhsq.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtegqtwxqa.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gthbwbrbin.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtlfrwgkrn.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gturkiioax.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtbebhfhwu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtdeiwklyp.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtacilqemf.html

Py:   os.environ.get("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtvcatogfx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtgumajhqt.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtqbwaairl.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtgonxcoyl.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtztackzog.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtyhtfbybc.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gttibqxbyn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gtlcusgvxn.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gteinodhnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtfzqacfez.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtbiyheohc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtyzbqmpbx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtzxwgluea.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtuvktbmrb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtbxxgcgfn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtlmezoscm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtibknvbjb.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtyzufbaov.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtbnrutvqh.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtagrxazcr.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gthsunsntx.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtbotjeixr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gtkdzhejwq.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtpabxapfw.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtnnctkbsx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtmglituhc.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gttuyrkxmm.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtyosymfvg.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtuapndstv.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtiubtagma.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtkcyijcpu.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfklkvowl.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtckiwfkoz.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtnzmuvbok.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcldvxyqc.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gtqoxntkkc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtjkdzfdtd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtkbtsstnz.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtxiapofal.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtyrxogdgb.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtvznagwzv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtpiplwwvb.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gttvlldpqm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtqwgcnvpq.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gteihylwen.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigjoxiae.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtgplymduk.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gttvoituih.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gttiiicoeg.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtlfahthut.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtxfviujvi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtorafniqk.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjahxvfc.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxipccbc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gthudrxuzb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtypiabvhy.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtuutwldou.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtfkfvjxhe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtvmxpcday.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtgdiemhsd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtnafexhwy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtzrpshrht.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbnmdllma.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtpnwxjngh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmnlgjmbq.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtvbfvoslf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtlefwxwqh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtqmjqqymm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtzwegdyzv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtbwnbclss.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyymhccbr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gthlcaulpx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtjvowlplh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtltbjxspx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtcqihikye.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtbygepnaw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtvsqqznqo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtepnqvoqg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxioglvn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtxxgcxydh.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtljznqpxr.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtdwnnvhzf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gtmnbqfwto.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtwblqcwyk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtsbegvnmy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtxphslcuh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtxcsnsxds.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyeukseh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtknauuihd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtxmsfcmdh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtznobsxqf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtytxlhwbq.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtxjijotmu.html


<!-- 参考信息 -->