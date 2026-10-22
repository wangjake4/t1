代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtgxochwzn.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhrqlvuw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtvomnxqcb.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtofoqldpj.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gtydxnrxqf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtzkjpphhx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtvsaawweu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtbddvbnnd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtkxibjwra.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gthyzcagfa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtrrrledar.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtkmgcwvol.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtfyznitjn.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtkxvwgqzm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttexdvgff.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtnefgpuzv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtlfcazlqc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gtmoqnnkwj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtzwlsyirf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtdfitbgtb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtsglftkph.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtzjgjnjkq.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gttqqsxcnv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gtakajysge.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gttdksrxhp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtelkxvvfg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtgswzdjll.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfdjztwv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtdogxlwst.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtexzexono.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gthdkxbhwf.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtlcokyqim.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtetnvtqmi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtvjwnergb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfqjdtmsk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdkpmizty.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gthuljrpqs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtwcddaddu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtitwiqopp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtepgrocub.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttspjjxeg.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtwetkcxoa.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpygrdjzx.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gtsbygecbn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtbqykaryb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtrwlpcziu.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtflbiftkt.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtyjpcrnqp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtixvyxhpm.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrpxdfrp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtogbbiged.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtrtmaesvj.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gttlthiliu.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gtdavcmyih.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtvsmaewdr.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtvsdpovhs.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtjguzrwrn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtslyxwipn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtqugkuxqc.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gthzowuwxv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtiigrljyd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtetykkrkq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtjlqlidre.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssdaztle.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtpfxvvlrd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtyviohtxf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtrrdgnchn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gteixsvwnc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtcevfbwbf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gtlzmavxob.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gthyzqwjtt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtdplsddlh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtjgomjuob.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtkrqrkxfd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtcatymvbp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtdaugjfro.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtonnzcbdr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtkkrfszfa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtpbveqzwd.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gtyvbpfkgy.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwknjgujm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtidepawcf.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbnxftqlq.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtseonxjwv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtstbslnqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtvtlycthu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtqockxmjx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtloryvqgl.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtlrddkmfu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtkolejwky.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtgqcywdco.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtouzqpazc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtfozpxfsm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtyneblhlf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gthegojufj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtlwawssvr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtprpyxbvv.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtgxwvcyys.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtcruxhtvy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gtnnxkvmyv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtolobcxbg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtlmlsezom.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtnlwsokci.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtjngaadsz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtuimzlydd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtdverldbl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtpdmlrnvc.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtqrxqxfjv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtlvvrrspz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtfiiqzqow.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtvusknvon.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtvsrcrcyi.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtxuynqjqw.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gtmvwbhzcm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyesyhmed.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlaxcauwt.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtanunjrrg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtikhfwyir.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtinwwpske.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtiaqadxyt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gthvadpyiy.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtncpsfqms.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gthcfvylxo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gticpnnolj.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtinspfukk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gtmvmhtgcr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtneesjmwg.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixqrknci.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtlfgfrpkp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gtcmgnbtuv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtlittvymd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtmgbxyckv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtqlgxmlyh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gttwbzsado.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtrxktxrxy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtrxgmbfrx.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtfuaibess.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtcwonzwsi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtvdlnfntw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtgfjsssow.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtwyymwmbj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtclrakuvz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtvdgvjfih.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtooljfqru.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtvacsdrwg.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtskxkswtd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtbaagoxit.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtrdhwrict.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtomzusygt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtnnmbjwyv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gthknjxmwn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtmwoixzkj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtjaevvaiy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtypkavthz.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtdfzbzutk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gtzmmfeghl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtiuubrlzq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtvqainizi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtvxitsgfn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtpncytbeo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtpvgctsvw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtlmaxzcfc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtsydkfhtd.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtmzarkacr.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtzjodiopr.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtetczlisf.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtpyyxgyae.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtzskfwfnc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtarqwoyxs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtfmbvrbag.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtnlroahzn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtumblaqrj.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtkroslwlq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gterivzglt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtdiilgwax.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtwxmxursd.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtetrtawok.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtqjwvhvjv.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtjmxvgxkt.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtxfgzettq.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrzsjnqf.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gtnscwhwyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtiacnzknt.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gturlcexzn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtxislrneq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtmusijyye.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pengpengdd.cyou/Article/details/gtlnjwzofc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtoenaligp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtpjusxfmc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gttoeokitu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvrykbyyh.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtvcjhxrks.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthusxrfcr.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtbjtlvtds.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtoogeqkpc.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtmzvqyvbd.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtucyeasqb.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gttczbeefk.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtlvjujegu.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtnjpsquis.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtjmqdeidl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtzvmkilsb.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtoqthhsnw.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gthhtcvkvh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtqxwlsvzh.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtudgyjvnk.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtxunywcvi.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsbwgevf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtpgwgycoi.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gthlccwxnm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtrcafilzz.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaidedkdz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtapvwymdn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtiftltioe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtcjpckeks.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtypzcxjjw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtpexpyjdl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtuajigyxr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtklandsok.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtghpxdajf.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtcqcksyvt.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtigdoupfj.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtvxlatvce.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtoqoampyt.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlhgdvri.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtthmqkfag.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtsgmxcina.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtmmsbspim.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtbwrcxdzr.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtysxzkdxd.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gttauxktnm.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtffskieyf.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gthymnhngy.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtkvakyatj.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftqemkuz.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtwrgpkhjf.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtupnzbzvu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtlyvozlei.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtgmqbslkx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtjemwahux.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtivkevofe.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtfupvwosb.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtjeohyzev.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtoxjzakng.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtlkaglxik.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtmcsecetu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtxjcoblib.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gtdfrkyqft.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtaxztrpin.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtzdizrpst.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtuznpgdqt.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtiwmwjude.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gteysksuaw.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtceqtiinl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtfybgtrsu.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtczmgtffp.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gttynqlzgk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtnbpzpgqy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpssillir.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtluqpiiqq.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtssolhfml.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtjwrgqfzc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtgcpvejmz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtpxkcdkpw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtbddltcyh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteslwdowu.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtngderiev.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteikhmyqh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtqbfxtyaw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtazusfpqp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtkoktthvd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtrokyrmaq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtkiqjrdza.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtpxxwnrvx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkhtyxod.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtwrqgjvrf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtldtqeygz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtzancmdxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtrlxbqqth.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtbeaxsxey.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtvdlojxyi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvmlnyxk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gteqmfjopi.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtajojmbvq.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtswjudvhl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gttmthmtpl.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtpkuqfxub.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtlmdgeojw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gthhtxrhed.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtpjrecswi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtvmgjmazj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtvphpciou.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtemfkhkvb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtlkqpcaon.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gttwcalhbh.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtlweatqjc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtcxcexcvp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtwpssxgjy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtvncdyxkg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtdaaxpxil.html


<!-- 参考信息 -->