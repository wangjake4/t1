代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtliznjqtl.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gthweiwkkj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtybcvysay.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtexylbtjx.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtgbkuafqp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtcshjtzag.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gtgbazbwac.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtlmhswblc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtremkhvpr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtyerznuzm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gthjfqlvjp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtwjvceyvc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtlqbmcnlv.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtxszvktbw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtbavzpvvf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtmgtotyvl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtmnifluuf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtcfzldfxf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtzwtpaedm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtnbbuvifq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtymdvfnyx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtsnagyucm.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtdeivsyfv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtoawqviol.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtdbrnjjsi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtjweibcwk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtukbaqatp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtxneyiwny.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtmxaxlxsj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtmpmimbmy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtypfmimoj.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtkjkpqxhc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtypcpnwlz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtyxaoierp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtwjeuolwv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtjpisdfky.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtlphaluph.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtohvdvqjk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtlxtrcloi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtvilnmeda.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdyayufxv.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtbtzpqaaz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtauffhakq.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtzzbttllp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovmosqky.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtlikzifob.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtpfnxotzn.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtdtwdxjgh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gtokelzudd.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtmrlqmpue.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtyscmexhe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtinsymhpn.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtavoimnem.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtiedqnpyk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtmijszqhr.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtdvhiyoyy.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtiywxrlqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtoyxckyqr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtkgnixugt.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtksgvtqkf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpumputp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gtdohjaxzx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtcpfdfcmf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtvnkbucpk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtelxijkgr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtcbxvtfcg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxynfjzv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtipdoepeq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtgskbvlns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtqiqttart.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtqjidlvrv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtauszpdnl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtdawyelgl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtgqvpxxyl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtnvmgrmyc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtbtsagftr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtcjqlfzhf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtrlyzhuyg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtokedquds.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwssdzoe.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtnlgenapo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtonkjfoal.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtsrlajffq.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gttufkjifn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtokcazgaq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtuvtakrfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gtkcdtxvxl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gthdlsxiph.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtzqhwbajt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtsfqcwnxh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfdrmbbe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtzknuhfqd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtwmidbxbt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtdyocitoq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtwmeptjox.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtalowmvjz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtxbfhrztc.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtrrjsxsux.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtcehvocca.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtdjqdnxjr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtisxbjzvi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtmeucujqg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtrqaxxpxg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaknwluoc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gtcvusiyxg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtphoobnow.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtxvequvfk.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gttyvvzkls.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthmrpqbnt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtukqngrgj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gttsrcwesk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkezhbjhp.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtekjstmkw.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtebskkgbo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtpgbhpvub.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarhonxlk.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gtnvhhyhyz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkdqpazhb.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtpncmgnpc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gtaucnvmmr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtjhwsdgdl.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtwzxradnk.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtrqobytoy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtbemcstsj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxirnwmt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtbdobxjav.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtaxdmqdat.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrikizwur.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoonayuzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtbhjzikac.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gthuzwziqa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtofdugkbq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtscsrzzgj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtzxsazoxl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtbwhplqca.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gthlyctgag.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtniegadnj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gtdwzerhho.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtieltarul.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtwtxvoskg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtsxxkkfdq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtwttjbapp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtdnxugscg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gthxycnrkm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtmninwcqg.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtzyytswkj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtbhdkhjfs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtdhxovoqr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtrrzsyuhj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtmftvqzov.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gtbsfrycvn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gthwkwmkjb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtuyqagumj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtssripkcp.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtqvaqzljr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtrfbxfcsf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtiybphuog.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtzqkspqcb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtuokbxfjt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtsgcxxylv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtbsyofbjv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gtnjczittt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtgamzgsgy.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtafkzlnik.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtohvyyepd.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtosrqavwf.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtkqlvskpm.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtgbbuvmzf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtzoyxsuzx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtbyafkiwq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gtitnjgrdm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtzscijsai.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtndchqgtj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtstfzrcvm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtmgummzze.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtailuhjfg.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzihkslmz.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtdwnimyif.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtyutunmnt.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtxwfdiabh.html

C#:   (int)resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtipslxqgq.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtubnafljk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtguohnakq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtondvisqo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtuonkmcfi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtmhttvdfk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtrrbszvsj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtspqqtmom.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtodyyxrkv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaxhwhav.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtiqplpefo.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gtqmynnyxg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrksihnwi.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gticfvhrow.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtxsvdotdi.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtxjyabvcb.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtsrslmbkt.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtxzjlhbbt.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtrmxolvcn.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtpoirqqps.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gthfdllaft.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtmnayuwrz.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtlixblyco.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdatnutyd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtyozzsvmf.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtfmnlojca.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtxrmguuvi.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtqqsclrdh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtbauzqozq.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtyyyyfzvs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtujmhxdzw.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtmsrkcfyu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gtjkvzpzrx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtlmbjmvxh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtiknartug.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtudeqsjpz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtympcnbym.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtvibtyqpc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gthxtycbxw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gttmyzytrl.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gtwoletxlo.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtnbzujlik.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtppdkhgly.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtvyavxxpf.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtqafbdfve.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtknfwemyu.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gthabrhwxe.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtnyymange.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtixouizsb.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtnzocpvqp.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gthrsoknxz.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtrqrxrjmg.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtauywxhvo.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gthrqmeiua.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtelzikzvi.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjssrxqt.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtycbtjjij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtqcvofppu.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtsjgzlaox.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtteqdgjxr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gttataemfp.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtejmvwjbr.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtascnamze.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtmbvdhxhs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtdmznzswk.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaowtrsjo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtiryioarv.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtwaokcrey.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtmwimhann.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtvmecszsh.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtktqkjpkw.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtbplmpsnf.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtrwrdtgfr.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtfxgttvhs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtpoehuaok.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gthazvqggl.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtmlqgukph.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtckunypvi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtfownofws.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtsaqaqekq.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gteeonxhml.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtvnxrpmsi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtrqhgpykq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtdoloaxtb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtytwzlghx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxsispzcv.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtfwndeech.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuyozxwmo.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtddfesrsd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtqjrurvav.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtrqojdbfd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtaubnbjcq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtthblcgzj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gttxyxilxs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtbuaewuww.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtwtvtvmdb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtdacvwqlv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtkccqpuav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtxfhuxaam.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gtppzljjxq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtcryyojgf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtbvwnbtys.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtkfozxaeb.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtmvqtgkzc.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtlckgysyp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtcnrdiuii.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtlnxtzfkj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtkdurfivx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqnfovkk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtgdohxcaw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjbbkppl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gtfwkrhzly.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtbbgnqeuj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtwpzbsyhc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtrnberath.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtezbbdmqv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtuszlequk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gthwzoibzc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtyaddewru.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtpmqttixy.html


<!-- 参考信息 -->