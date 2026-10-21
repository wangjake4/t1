代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtpucacpyc.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtyhhnayob.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtkgtzsdte.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtzevsdudq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtwhnpqoeq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtgzvrfnva.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtxmifjfpj.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtypypsuzv.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gthqzlwfcv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtmbhzldad.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtchuwhrfe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtaxyonkpm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdczacqps.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtefigjyfd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtxtcnwwjj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgmgeqxs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtfpllutya.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtacevrayx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtbvucumkr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtiygcqkls.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtvzeqxgft.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gtopjcvtrs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtlqrlmfkz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtdcrdqryd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtydwkamep.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtcqwbpter.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtuzbivcaz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtwtrixubj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtrzdlqlmh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtpotxlrsw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtxwxpvvmy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtbeoshavi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtpjimlfzf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtiehhocbn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gtbqbcuwaa.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gtjjjwlllr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gthbqashvt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gthnsjhrzd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtvmykiyen.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtkzdnsoty.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtrclckiox.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyptvznt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gtaykpefbq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtdmgshxli.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbbbxkwbo.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtvvwswbax.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsafenuin.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtjgcgfwet.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gteebcuslb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbalpprb.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtnqoqhrui.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gttzqqqtdn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtkojjwqpu.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gttfwpwgmo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gthktyyuek.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtknwwkslv.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtctauiqac.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtyddpbnzy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gttabdbfxb.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtpclvsqpq.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtfotpgfev.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtcaohuafr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtflfylnxj.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtkkffdfsi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtotjhsqxn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyxpdkdq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtfvltziba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtqvrwcjag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtxzstdzim.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtskzqvlwr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtzguynfzb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtfajbbbmd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gtdxizaqat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtqyqqyibn.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtpqjedpyf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gthglhapxm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtqvmfnuli.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtvyadigby.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gthllnznhr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtmtksyfmh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtfvpnkhqt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtyzcpebqw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gthsskzfmw.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtvevdvatv.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzbdcabbq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gttixeryzm.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtrgftsufn.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtpwrankui.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gteuuoidso.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gtfuxlclhg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtvjdeerik.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwibdahi.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gtjdvmbxlv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtcinwomqj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtgfsjfvoy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtumsnxkum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtwmsscjfh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtoikjlsbc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtxfrtdtoh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtaobixsyx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtiuvzebre.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtbseefurj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtsdswcjaz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtrxjvfjnb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtwtutrfzh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtvghxpvmw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtxeuratgu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtfpnvwhgn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtfpsbfuef.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtcvmoifae.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gthmgfxcnm.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtvlojlbny.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtylkpxvgc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtutogduqs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtddyyvyun.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtsbaytffr.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gtnxrtxahg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxevejtfl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gttlchtqhj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfavtxoa.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtvrwmpjda.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqxgvsgkx.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gtiifbarfm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtxxehafbc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtvjazravp.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gthghsavvv.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtgakthptn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gtalpsrner.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtnqxlhzzt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtmjgmfson.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gttyerlkln.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtfuahpiaj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtpegtrbvu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmiydllk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtejtakhcs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtbzmhcprs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtmprnuejp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtvoaqowob.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtiniuusdy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtfmcatntf.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtwqcclhsg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtljapbsnx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtuumuffxn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtqlgxywvs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtawzeplnj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtnveilgkf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtmxruynlh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtgikkoezi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gthbdltfai.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gtetrtolqi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtonxwlfwb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtdtadkjam.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gttlbelwdh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtqwvmvoop.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtcbcslcmi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtaboscsbi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtruxqdpcm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtujihmoeb.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtlelxkvdz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtbxkrrdco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtortmahga.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtqoxsnjdb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtcivxtckf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gthkadfgar.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtxxrpdaxn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtquhqpkrz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtaxsjkbak.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gtrkcpszoh.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtqwrxcoze.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtzyfcfoid.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtnxtticuk.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtafpvdozh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtttzenijf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtvzydzowx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtmxphtlrb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtwbrjupyc.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtjfnrmgur.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtqureklkt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtlvcszqrk.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtokbwklar.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtjmgiiixl.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtmekndmpo.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gthqujgyce.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtajdhipka.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxbjhfpj.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtleukejeg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtyddvnffc.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtwmglexhk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtkfetjjzv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtmfmgganl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtatqpptqd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtkxbdoaig.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtcsjemxii.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtscnyajlu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxxiwafpe.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtuyyuwpvp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbxuozquo.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtucvcfbyh.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtvzgnxxpj.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtizmgckrk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtodwzhinp.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtbphqxtnw.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtlzucbwuh.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtbdsqwwju.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtbakuqmyl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtwtmjwggr.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtshekrkps.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtozzczrzy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtdikxuefb.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtoohijwbz.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtlsmdujrj.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtdnfoikpn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtbfkgkfhx.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtwuwuvkya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtvhtlyuok.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtlssgysqn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtsecldbyq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtngwxjehu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtukecrjup.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtmimgqpvj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gttyeftnxi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gttdieawrg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtiaudxdrx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtvdkjdcsk.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtjrpuavhu.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtbboklphh.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtgctholtt.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtebxodlzd.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtdhxjkdgb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtjahzfdvp.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtdhqqehiy.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gtxsdaguxs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtiorzgvjt.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtamfbnogf.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gttvgaierz.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtbtvhdfdr.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtvtzgllos.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtrbkgdncd.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gtoezkkfgs.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngrrimix.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtezmndcfd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtyizrkjfq.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtjqbsiudb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtdrwtbzwc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtpfxnzohi.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtjtrjysgn.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtzyenzjgx.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gtjuvsdwdq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtbjynlvnd.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtqluzsxtr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtkqidcbxl.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtmbmudoek.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtucwsknui.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtrqjdyutf.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtbbibgrjk.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtyydbifrm.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtnniyftdz.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gtadjlmizn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gtfqbasynn.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwjyetat.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtgdvglyrp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gttartxfqu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtlzdukrbn.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtxuisjeol.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtubxjcddh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtnsskjzee.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gtopfgbsso.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtziunicpt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtchifdrin.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfnorrimv.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gteijbqgvh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtogbxevkv.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtngsnvzdw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtuzqddbre.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtrhjtgykj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtpskxiila.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtkrehdmcu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtxwxieunc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gthlkxytup.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gtsywjugiw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtnlttkmks.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtnlgnokhc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtgpzxterm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gttrgjstss.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtqqrijncr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtqubwkuhx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtucbhusjx.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtobiaqasm.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtliaouuuc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtsvugvrij.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmliikbo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtlhvkefaw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtwlgobzjy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtahhzocgk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtheowsjhq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtmmdzeiiw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtxomnejhn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaoapopp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtngrvdgwb.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtrgipypgs.html


<!-- 参考信息 -->