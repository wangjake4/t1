代发 wailian999

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtguwpbust.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtlhplixzq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgsovqkl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gthmwefjeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtxlvwkeoi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtkepzmcfe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtrpcwxmnl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtmjgqsrth.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtwrhvpuys.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtevuhpygs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gthsgmrjfr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gteqvmpzja.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtbnlprxzr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtyscwptwe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtdclktjnk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtjzlhclml.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtdhjezaua.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtslyneoma.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtqyniyykg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gtrtdwmgtg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtktidrgfg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtajbcuxqb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtyjqpdlqq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzhuybaz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtvempetll.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtcirtigbo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtmdqlhtpv.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtpexqaomf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyjmaled.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtsbyvovgg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gttiaqbowp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gthtqwnqyc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gttxrzhghm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtigdjbgec.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtpfhjyhgh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtpluecncb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmpyvbxmb.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtpefomzsi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnxcgdevd.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtuahpmnti.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtiztvnhyb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtvnhlwbzj.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtsmttobeb.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtnrihlmfz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtgvocwdya.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtygznddtt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtngmuezho.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtanojzkkz.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtmkolxtwm.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gtuvyotexb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtlaxlyptl.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtiowamyuv.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxfiilusp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtsgdscfpt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gticmmtykn.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtfyspoxqq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtugubqcqa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtrecsidja.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtncgtwxpo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtndguboas.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtocceyklq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtozxdhyat.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtyioxtdhg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtasffpuyt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtqvzmcbvf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtdlhqonsu.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gttyirmpqt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtconltyxr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtjeljnoru.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtijohtwvs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvwwzkuk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gthobrrmtw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtndidanem.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtbbxcwjzi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtczlwuwol.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiufkwekl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtpbhlttkp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtdgmbvwst.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtavsbpawu.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqujadel.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtgbcejvox.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gttxtkrgid.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtcoltwchj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtmcrkslfk.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gthlhsqbui.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gtzfkkzkaz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtpmoumzct.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gteswubufs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtyjnmyzqu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtypcoldri.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtnizmqwtr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtmidqwmaq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtilibdnox.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtsqmhhnpd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtmjofwqfl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gtuophnwjv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtahhkdtlq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gttkvapdgp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtmnwgmzaj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gtyttrttbk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtzieeqfvt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxzcgbrn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtuxbtndng.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtgvnzcude.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gthoobswkt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnljzsbkl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtrmvvwybl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtmkyppztq.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtwqzoebvq.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthrtrskri.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtntgiezur.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthwjtzemq.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtyonyhzfj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtycmbvmdv.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gtpahwnrkp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gtzybhcagu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtchhvievh.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplycqdgw.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtrzcewdgx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gtdauzhsum.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gturqqklep.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtprzcntjc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtagsrrirk.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtzpyodqwq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtgoovhmcw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gttscujosn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gttvftudjg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtggiljpjx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtuuhqhhkm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtpgdeczes.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtqcjksqli.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gtissempjw.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gtprwqaiei.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtrcqdgdlw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtkfdiklbo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtulbaqzvw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtdireslca.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtydqswdvo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtraiaunab.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtnrefypca.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtbspatzmt.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtkdktwwcy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtokrfxelw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtvanmyhiv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gttbmohqvl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gttyxoasdy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtzyoefnkr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglipjvei.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtqrlvtljg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtklotdqhl.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gturhgxvzh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtbwffzknr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtwpmpfapg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtsmssfayw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtewgdcrzr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtseqtekic.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtbbnvtciz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtiitvbdif.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtqhwyokjx.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtiogktppw.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gttsycfoeb.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gtvfjjrqqj.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtjfneitne.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzecdgrrw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtqjbjegbe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gtolwjnzgx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtuiprgtdh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtfeonrjlg.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtzxcrpxzr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gthbrxswei.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtczpwiqcg.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtusxoelpi.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtftubxpte.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtvaufqueo.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtcfjmzesb.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtaopphfsm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtbubpsebx.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtsfcuyial.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtczjzwzjk.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gtykblunxn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtovkiuanf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gttfhmojoo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gttxgahkmg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gtybogbphv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspdfiupa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtkvsqsqaa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxmrayxhv.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtvdvunmhn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttekizcjy.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtvchnoysj.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtcmrljpav.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtbvfqbgza.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtgmtjwzxu.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtmdpzqxoj.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtkzaoendv.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtasfdgzgx.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtlllbdgss.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtejnllanu.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gteqremxhc.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtpumyhcmk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtqdfkrvvc.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtupmrwmzc.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtklboapbb.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsazkpal.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtmmhjcelv.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtiwdcpxfh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtebhwotfo.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtfkvlyphh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtzjporcbi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtknpfiwoc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtizbtvjnf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmbcehgx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtkkhmkkus.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtttfabkfc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtdzieqnrb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtedsgeyls.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtmqdccgww.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtrzkgzuph.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtaakjyvnx.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtbehoacpe.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtkqxbbnzg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtubxnngqj.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gteypnmnkx.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtdqiywsri.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtscucimxx.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtxojihawz.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gtqyfbvobm.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gtsgisemvq.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgojqzool.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtgjtvrmzb.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtdgbtzbnb.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gttqerhltf.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtklbyicyb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtadidybww.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtvvybkgaw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbjymjbsx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtfrmkwbpd.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gthldpsbdt.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtemwrybmh.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtkafmfpec.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtfiqkhhql.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccunwrsp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtnqbkrtxj.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtjmwffhnb.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtexhgwcjp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtqrkuxase.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtobiaicaw.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtszplvfjd.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtswzmeyzi.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtlueqqjhe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtaicygqjs.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gthnmormte.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtdxatiksn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gttifflplq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtgpvwscmj.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gttqkypadu.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtgglteppe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtmaarrcxr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gtpmtdvini.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtawedcods.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtxysfwwkx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwuklexbs.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtraapnjmq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqvbhfkim.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtpmnkkwqo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtomtszdwz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtuhgosaai.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtfhjwbmdq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtcmruazui.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtfmkcpsfi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtfacxnubf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyczdyxie.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtwkmcxelt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtyorlcgpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtphaniyma.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gtxpjnyfim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtcyblyxhy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtypaqboge.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtksvkmpnm.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtrvdwntsq.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtxooiywpt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtmkzzxnvl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gtalwkjcwu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gthmhlqkvh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gturmjrnck.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtemrcrrlb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtqsflrycf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gttatmgves.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtbrquuwrp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtlgextkak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtigkdakqg.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtljccgsfu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtnkfbgada.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtaszilluy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtpcflgafm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtprdlnjbl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtxjcgmdyq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtdfliekqb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtmuwbteno.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtqmrjosni.html


<!-- 参考信息 -->