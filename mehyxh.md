代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtowuowrsd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtefrinvyx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtfityhkpc.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtpzwnfcfd.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtpudxaifs.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtayuulvok.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrvgfeih.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtkndbhxhz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtkmrtljhx.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtdauvutkp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gtmvhlxtir.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtgtzmaqqt.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gthxvehdom.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtjdniehsf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtciurfnac.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtwkxskhlp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtbvyhjkyl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtylufyzbz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtuhadmetj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtmszhaxzh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gthizziyyb.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtuemobnrc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtsnogzuez.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtmdbmopmy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtwqjtpjwj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtmjqmcxbe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gteovdutlv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusznflif.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtdajlqpbg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtnforpuen.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtxqtdfheh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtsfguvqba.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtemllrggi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gthsnlupbd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gthnmrlaud.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gtxypqzseo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkokwibif.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtjvwgaehm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtcvqtxvbr.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gtyjywwkkw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtkycbguzu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtsowrsxou.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtpabzvgya.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtpqvhxpfv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtaisfixbe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtlomgnixl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtiytymurm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtntwmsmag.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxzjaxlgg.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtivzjpicl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjjlysfza.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtzahtlxpz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gttctcrywz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtgnvuovat.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtfsghnxyr.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeudcevc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtseudlhbp.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtolackmim.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtrfzjuubw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtmhwzdt.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gtscpjjqpk.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtlmeznsai.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gteuvrcmfo.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtmgerjnlk.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gttkbbidhi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtgzyibgcq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gthdnkfbps.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtwxoobjze.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gtppgiiquh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gtlldyfjnn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtniwyegmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtrjtpuosy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtvxtdiwjx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtknvmafde.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkocqdqfa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtwimqrlez.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtarhtlbgt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtjzbsjltk.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtmifpvfme.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtwaipfpvk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtiavuvicq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtxtyopjlf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtuuppegro.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtqhluhkfe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtyifymdih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtzazyaqrn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtzdrcligu.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbxqxcqb.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtsemnprna.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtmglpoxwd.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtdihpgyhz.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutdjvyfm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtaxsioaef.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtgcbscptb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtubudlarc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtgbxvvrxz.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtugixzgik.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gthxyluzsc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtnhhcsvqf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtklqwduou.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtpdafgxkq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtiyeukkll.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtymoibdin.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtqpvapqwf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtqwplabzg.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gtofowyfbm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtyvqbcunj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtwnpocrdf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtbvabyebf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtfnisdmny.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtpabgzatl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtlgubeiti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtnfdxmsjj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtnxcrbslb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtypwnufee.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtwpybivgi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtvwowimqw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfbvjlnc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtfptaukim.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtqkpijnhi.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtbizfqzpf.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtzeklkomj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtgugtzool.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtssrbilqp.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtftcstefu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtehhmdzdx.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtpmxqpmok.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtmbzzjloa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gticksjutq.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtxyhexoyz.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlyxgmyb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtvxlmnstn.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtxuztfadw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtackucikw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gtgxfofree.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtltzvouio.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtmytvjxsz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtxejxebzz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtzhshixwi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtgxzimeir.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtaiokxful.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gthfzblblp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowbqrabp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtyrsmqkjd.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtricqgzge.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtfjxktsqj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtliaawe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtvpabqiim.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtozchcnuu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gtkoxvljla.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtmthffqei.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtxeouckhi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtnrpquzvz.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtvmjtnnig.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtpupmcicx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gtvxgxsbvn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtcmlnpbdh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkkvdcfy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtraaztaju.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtiiztyync.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtygxubyiz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrtjtxmz.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gttgwhoorw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtlqxhctcw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtguknclxw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtncclxvar.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gttwqvjhtl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtiqisjemo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtldnypecg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gtsfcjmjbw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtwpxbavql.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtpaalljyt.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtfzjcmtfr.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gtinngztut.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtwdtncyoe.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtkyaizhwk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gthvjstlyu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtkebceuys.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gthlzyodxn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtjiwmmjot.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtcoqynibe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtqkowyzeo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtyvhnmdeg.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gteeniqged.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtiqyymduz.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtawzmorqf.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtbliuqgbz.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtnsmbtccq.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtmvgdyftr.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtmpdthzag.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtakrzoxyx.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtjsuwlbhj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtpbvbzxxn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtgzavgskb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtsshwmeyp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtejiwvqqc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtlkonatyo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtdgixyvwx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwwqhwaeb.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtkwfkbloe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxdiajxjz.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gticljyvwl.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtamelakek.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtjozatrsy.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtomfzxbhk.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtukpamgxd.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gttsgeylkz.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtfdqhmcdg.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gtxpapnvjy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gttcehmyyj.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gthcsgmspr.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtwzwnhgih.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtarrdaqnv.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtauqfzrxg.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtcfsuhntr.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtqtwdoxgm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtbdsoleph.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwffjbyjf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtligjiiho.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtmvctobow.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gtshqtfpkk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtvhvampuz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtauknhyfu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtmyheufyo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtfofihsbz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtwxcicrhu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtdbrmbjax.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtfxiewwys.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtbawffvih.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gtjxfefoyl.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtzrbvsgos.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtasfmftrn.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtatixbyrl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtjnbjkwso.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtoftrbdrq.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtjfpzjtdq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtyaltkneb.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtjwsqhfbz.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtmnkvyvqb.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtrosrbbae.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtklzqnikp.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtkppqrcgk.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtrthwcsmq.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtdeavpcnf.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gthkzlehtb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtyrersriz.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtciqbkwvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtqqqkovon.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtplolqftg.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcodycnel.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtbirsrfho.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtkwcifdyk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtvpoayfgi.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtmpmbyidb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtlofmvpon.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtzmpidqie.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtkazpnefw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtrefuxkuc.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtibkayyim.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtpigtyihk.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtfkeswjca.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulpuqjez.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtbceovkxn.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtmazhnaud.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtxplmogcv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtmiusaurb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gtxsjwjkgv.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtyiomatwq.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtazjjtlko.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtxjingqku.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gttjfjmhwa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtmgsknbrq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtzeuoqfcn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttrogcthv.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtixkvbqws.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtghpvmjud.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtsmdobhue.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxdckhef.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtvcaooglp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtwnmdmboe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtrrjbqbux.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtietpniej.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtnybfqcor.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gttvkhlope.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtwhqyvumj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gtogkwankm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtuytnwycw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtltvditlw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtibhkszbn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtztafyoyq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gthetjiiua.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtualcufzx.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtrbqfuyyl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gtlnbjupgb.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtuzmiexni.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtdsgkitam.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtrijfdyan.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtmkwrsjsc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtbjyzfwgt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtxefcomoa.html


<!-- 参考信息 -->