代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtxlcvpngk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtpzmielgk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtiazukwbd.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtkgfofbla.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtfyhjgzzm.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtxbgayoko.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtmayxddgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtxpzokqfa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtotfskdsu.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gtubfurpql.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtluqsehws.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gtipqzagfo.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtrsdnrzqa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtmvjqfyse.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtdhkwwnou.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtsybsxctk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtfeukroly.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gtzcucrbcp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtympzkwuh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtlkcsvspy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtozwsbxyc.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapuopbvq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gthsuwqadp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtvrokhlrj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gthcblvcax.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtuwyztcmg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtruwqfcez.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtbhbrrxrk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtkpcytsaw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtdaxgngwl.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtoqrriatn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtpxlbryvq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwmbwtax.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtkjzsbslf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtmhqzmltu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtjhrcfaje.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtljusvvsp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtdetwvtyd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtqkcclkqw.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtycilhzul.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gttmpkzsjb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtlifiedpy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gthzieivuo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtsxxifcpl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtlxylifau.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtwbhohgmo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtzawcaade.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtroutewjs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzdxwlnwc.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtgkdafoxq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtoojkmbxt.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtbwhdznsx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtpcaqrlmt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtvuctpipl.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtbyuelhlv.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlkamwvtw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtmjgwzqqr.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtyvjxokyc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gtohkjspuj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtzhewsavn.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtbmnrmqau.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtguarwfbz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtetxqlthu.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtsefhszah.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtopefztnj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtxwsopfxa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtwzqtyedd.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtcsjajbjf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gteasbsmyl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtzklgxsrf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtsjftbbvh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtiyrfyvqm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtclqsrkul.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtnbzuchug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwsdhafzq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtgetfgviz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gttvcglnmb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gtapapkrkq.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtmedljiex.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtrxlklicq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtgcsjubgr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtuhzbigcd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtdqmusbik.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtipjmjbwn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtxbpucpkc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gteqtlscsz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtqjyjpeyt.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gthfwougly.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtcfmvcdis.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtzgtuepnt.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtnbyawdbn.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtkhvhyhtl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtyxootnmh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtbpbzhncx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gttegsqhlb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtqmojdmii.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtokfaqgsd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gthybwutip.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtkxnmblhj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtzgmxvhfm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtcvqgbsbp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtmyfoblzn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtxsmaipmo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtvblqpazv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtomkizfqv.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtpcnjfnsd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtulkigbid.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gtbzgjnpxs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gthavlvcln.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtaorhsqpf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtzpbfnruf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtlhqejmwg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtufsqwngh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gterplzkcv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtzurnfogl.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqzldmkv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtxftbbtte.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtizxwsuta.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgscaznp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gtwwcrjhxd.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtmfcetnup.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gttqdpeizg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtazsvlmze.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqtzuxjie.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtcvpgpzyn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcqcbsfum.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gthjloltam.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtmbvklbsc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtpjsfbugt.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtqruzgogw.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtzewrylqq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtwxtqhrnn.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtelokeijt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtrwpkwzol.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtddvuibtr.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtdkxzaifp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gteeeshksc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gtodcapwsm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtyyrbxmiy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtbwmpoveu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtvqmexoou.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtrmohqdzl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtubnocgzt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgadyxdgr.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtdxjjybiw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtzcpycnac.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtwltmuzbt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtohrmhdjd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtnmvtciav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtqvnocvnv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtfulsifif.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitesskgk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdtppclw.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtsxxfvoij.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtbdqqpezq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtyqlbtnhe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gthdrfvcro.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtjmbaeryx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtdzdooxrr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtcrpwpcaf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tianlin.xyz/Article/details/gtabablboh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtxdjmgcks.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtgqzxuwxb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtydvmjdqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtqetqansj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtxybepdpq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtgbmddtfy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtluvdtlxa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtwepybdmg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtpymarzen.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtgxuukdks.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqaosveb.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtdnrjghpm.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtndmmngoz.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtyhxxfbop.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtbzoxyjac.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtvhsucjmv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtyuoewahx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtzkybctfa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtlxfscxat.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtamcmrthw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtcawvwwxw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtrlnckoax.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtdlidjajq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gttrjoicog.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtwttozteg.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtpcfqibhr.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtyjfykxty.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtzqeccbrd.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtlyuzbvav.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtfynhnyjq.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gttlhtqcvl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtmperfkux.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtcaoglgku.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtoiiqqvjt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gthahvlzpl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtycvntwmm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtetsjhoxg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtstzsiygk.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtithrrcla.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmoctuhfs.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtpmzzcqxh.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtbpttkspl.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbkrnvzt.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrvmvwxg.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtkohgkllr.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtynerpfqn.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtzogznato.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtfsmifdns.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtykemamaw.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtaksxvirp.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtgpgrleab.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtfhmnrsbx.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtjbfvssbb.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtarjrgocb.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtcwtogmpy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtjtclhvkw.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gtyujadzxa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtathjoulg.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtxhqheisl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtsrxtxtle.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtspbnktup.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtbuuxqkbv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtsipuujuo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtsxkbimak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtjrtvbkbg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtbddykgxk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtiruhzrza.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtsbdjrlci.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkevhiwei.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtadpfddhq.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtnwvfwovv.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtjlqcjpbb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtuoqcwfnj.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtmykvscee.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtjrbnkzaa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtwryvzadm.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtculsnqly.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtbmkdnwaa.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gticmaupgr.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtauhmbiym.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqaqrzfju.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtpjvvhiii.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtkvbbcrwi.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtnrveezlk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtraqiirrl.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtheycdlps.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnnskuts.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtyvfxexot.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtmtxkessq.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtvyechden.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtibszhply.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gtqhltidvw.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gttneuqvgz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtelppkuwn.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gthncvkiiw.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gtgyxrdylv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtfnstxsxt.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtvbwimayt.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtbrsvfdcu.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtijvilgif.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtawbduoad.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbsgbqsz.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gttngnoscp.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtlnggypwz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtlaahfies.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtkcffrzhq.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtkdlhppvh.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gthreaaufd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtkubkishe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtwbodnfaq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtlxkwlsul.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtmxurptlk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvbhqqxkb.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtrdkaffbf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthzfuejdd.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtwrkbinfb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtlvxvtbqm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gthkrawjws.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtbgxntifp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtbstjzght.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzsnfhybf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtnduwhhgg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtymmxxhde.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtgtqctoob.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gttoctffgg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtmwtixmjp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtavfsgxsj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtawcikmxg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkytxrajv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtybxqappn.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtlnhccpje.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtxiknoiwg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtwxatxvbn.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtbwyvbagy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gttowbxccr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtpouatjus.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtxskhzpbj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtapyqwxpk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtnkvyortr.html


<!-- 参考信息 -->