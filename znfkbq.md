代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gt2zuxsfpdp.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gt2lpkiaksr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pilyjtdi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2bbbckjxb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gt2ntcdsfxt.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gt2eeacxzte.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gt2kqeosekh.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2ycdlsdjt.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gt2rtqykjtw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2jbahtvre.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gt2oevjnqij.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2usjcheyz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2anztlvca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2fxdsunsq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2xuxjvwbb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2mqafpvnb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2mjtitdor.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gt2wvimiirb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2fxrhxslk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2nxdpyoxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2yfezwsgf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2zozzyimo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2ryvzzhry.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2cvqjcdvi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2vipdumwd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2ijxamiva.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gt2lhrxfsva.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2gqevnfsc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2eitqyeis.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivsykkpf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2abvtatdw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2ivstvgdd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2ybsnxjjm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2yttaosxa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gt2akdetuys.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gt2hakpakru.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gt2svvjjvmu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gt2nzpqanht.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gt2ywlykkck.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lifehjgg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2texxvfxd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2whjcfpoq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gt2booetyaj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2zyudebam.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ilawnomd.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2lhmnyhqy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruokefee.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gt2lcgjgyyj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2lrzxkpni.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxdnahko.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2hlafwcmz.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2jfhwibqt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfxloubh.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gt2odzcxwfz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gt2tcklwdge.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gt2xdgvfvba.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xheqxpjj.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2motmlxha.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gt2vfhmihcn.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2nuorfogv.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kiytnrus.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hltssono.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhwegxfr.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2torapfst.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2sfkxkopk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gt2ztxqquku.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2xhnhrzyp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2iioyuhqf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2dnrismxo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2ssgnljhi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2qyzmfije.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gt2zjiwfjnv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2uliryejn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2jyjuotiu.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xmnaslju.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2unggwbti.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gt2xuadrtqd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2fpuyxcqu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2ajmxirtr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2spzwjsib.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2srzwzjmk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2eodfuypa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sssblgay.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gt2iqtnyoei.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2avpgvyjc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gt2phedkygp.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2exjbnnec.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2wdzsvzmj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2xkcjqtad.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2kjhtjbxz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2hvohnwjm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gt2rntnyqnk.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gt2wudppfwz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2prgjmhxz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2dkvxqmzx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2rrwtzyfg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2tkyrjjfa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2fhuvgfld.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2ypevkdwe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qswabgsm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2awilxnmh.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnvkrcwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2zmppzmjk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2wypcwyjy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2lnjpqxvo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfekkrik.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzlzgfyb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2ahmabuvc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwaasrug.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2efxjhveq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gt2zandwndg.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2jwmmlpsi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2qubfnfzn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2kafjnhnk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2ejqiwzym.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gt2ywttjdne.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2exuycfht.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2llgnvdkp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2hxuszqol.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2bpomctml.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2loxwzzko.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccmlxhbt.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2ascncmac.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gt2dpfwbtwf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gt2izhunycx.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2tqknweqf.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2uipmtnvf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gt2vapklriq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gt2lwculdui.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2yegesyjg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxnvtuvi.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2ojzigtxe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2vkltrrjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gt2akwsoxkg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2goxuxybi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2fvyxzllk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2viiibxea.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gt2uwwcqyfy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqmornwe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2yuznvnad.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2uzzjxycf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gt2rwxbnjxs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gt2xuizxpfv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2nmyrswcs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2imanrbzc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arpemsmv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2chbsmqbe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gt2dxhsstfu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2zfikktbf.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gt2qalilrkp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gt2ygsysfjv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gt2owvwfjew.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2ybbbuckj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2vnkzgzab.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbignfgb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gt2llhqlfmr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gt2pmodbwjx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2zkgjyhby.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gt2yhfhkaax.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gt2hqbnkmlm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqbmjjzz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2akxxghwn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2hqngdhnv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2xwtusbem.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gt2kynbutlm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsvlnkfi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gt2huhecadu.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2zieqtipm.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2gfzmqkim.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2vhbznpar.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2imrjcbjn.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2idyncufi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2wuzeiwpp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gt2udhkbtrm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gt2vwwoeyyj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2mfpailco.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mviftdnb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2krgvolxo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2zxlbbxxs.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2kmguqxoy.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2pltnhdqm.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gt2nydemqyq.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2lzarbqre.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gt2akvnzkxb.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2ifiopxzv.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gt2tcfarjin.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2ivinwjaa.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2dvkhsmtt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2ahobsbtc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2cljeridb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozzrzdub.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gt2awkrfiql.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2umarxrvd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2ctxtoise.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2uzgursbg.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gt2netwvuym.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsjhghoj.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2ztgnwnyd.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2qqccrvja.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gt2jgqtkzzm.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2taybatxm.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2hmdstmvq.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gt2xmzeyhfk.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gt2gxlwipgj.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2pynvslpc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2lihreviv.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gt2rrkhzzgi.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2eltcgkvg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2aapsgtgt.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2enhbxpjt.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2gyvdhxrj.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2gofrtypg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2chisidfs.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2szevleiw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2anromnuc.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gt2khjzmpzb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gt2qjrwccic.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gt2gmqiulhx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2pwqztldr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2yvuyhozc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gt2oojtgchb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2hmjyywzv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gt2zhsjtiuf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gt2etcizcnl.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gt2phbnjfzy.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrkkicnr.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gt2ojblcufm.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2yjeinsnl.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2ayfsmbge.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gt2eoczxokx.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2vxiihzgk.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gt2rvnyczdd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrolxvt.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2hzmmbqxj.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ikntxlgg.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gt2vsxgydcu.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2sexlorbv.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2iylnddgp.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqdmtxmr.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hcaqbruq.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gt2scroxcmz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gt2tpuyzijt.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2hwfxlliu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gt2hvsrtnfq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gt2bmkrctcf.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2oihazwas.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2vamglryo.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gt2wcqxzzyb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gt2sxdkraeb.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2rjpsjirp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gt2tfiebwmn.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gt2ryycbfbh.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2pmielpst.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2jxwlubrk.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2mxciqsqu.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2hpustpfu.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gt2mgbgvwef.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2qifwlsnw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gt2asxreomr.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2pjoornqx.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbvqkuwp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxemjnch.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gt2soonihio.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2wkaklngw.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2qzdhihbo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2itbgbsfi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzhpwgrw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gt2rnnrehea.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gt2tjffrsez.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2julnkril.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2pogdgtqi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vmpfzdqc.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gt2rzotgcnd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2ppavkfwi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2mvtqsfue.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2kksmohfk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2phsagawe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2boqlfpse.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2xcfszubr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2zelxansb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzqskbiw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igztzshd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gt2jdksfaim.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gt2hyeluvje.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2albvhjep.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2sdpvvbku.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2hlydbjdz.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2pfmiuopz.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2gblaplmo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2weskqcup.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gt2mdczwoet.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gt2woxxfcec.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koscnpcr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2bcdjnbjt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gt2ugdjknng.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gt2yrdunwsf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gt2oovmtjeq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gt2cggpfutd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trlfiryy.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gt2xftvbouy.html


<!-- 参考信息 -->