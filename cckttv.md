代发 wailian999

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtwbgfgziv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtglzmhtfk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtdkwiezrd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtragfvgxs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtjekrgfvf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtskltltsj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtjfbqtfep.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtsdoubaqi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtarhnqxhv.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtzaxmiwta.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtsbnooxgx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtxprgxkpa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtfteypuiv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtfscmblfw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtyrzhyxwh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtxaizjgqi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtgdqpacdq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtfsnykcfu.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gtuqeyhaqx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtcdtgvpsf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtpqtbamxe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtaxfiybnd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtatnmraky.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtnhnwfyno.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtbyoproov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtikswhkdx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtfpxlvwjo.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtgeaopzzu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gthhhtmoyk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtvqihkfpn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtsumjxloz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtzzludwtu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtzivdnuzd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmyenagf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtmjbtqpmx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtygtiujwz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtymmpotnq.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtqyrijzhg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxbpchepg.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtjtfpwiqk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtwjcpruhg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gthkejgemz.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtkzczoule.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwzphlppc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtuxjrpsue.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtigipzypf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtvsuxumzq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtssyqqndp.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtqvlqgmxd.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtaafzlnpg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtkjkkdife.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtccxnyiti.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtzsgssnun.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gterzoofdr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtaikylagr.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnhapkgqc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtnclwdvwj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtacflpusk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtlpvuyyom.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtbnpdvdvr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtctcvzdhn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtynjemk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtonluwwki.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtjpgauwiy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtrqwwwmlq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtzqznrysg.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtwlgthpvf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtwaeiopsl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttimynple.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtfwxjqgca.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtmvpltrgu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtviqtmwru.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtrtfiffhf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtmzjywqjv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gteerabufj.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gtdzupgewl.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtonamczuv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtboupdyhc.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtjlwfrvwk.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsmxamws.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtebaawyyr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtudwgjoog.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtkytpubsk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtnrcygpaj.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gtjrzpfkdo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtrienzdnu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtqqrssojy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtuymohypz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtpphtwwdn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtdwopaulu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtkjhropxe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtumiffbzf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtqguhmxlg.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtskklyiau.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtjukmyrtm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtqauswyph.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gttoxufcxu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtbkwdnndr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtngshovuo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtefggddck.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtnqctemic.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtirzckthz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtqrbeeycc.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gtsychurln.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtniimfvda.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gthgunzpmi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtwiawqzlp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtbbrnrdjg.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtsfdfdgic.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgtfnahvv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gtwrutjtnt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdqrltzzk.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtnrdwjmjl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttnebduhr.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtvxdratuc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gtxavkxisg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtcezlfmjo.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtyzdfhcxt.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtmyotbgmq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtuffpovyg.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtouxbetzh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtfczjgque.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtsdsvrsiw.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gttcapzgdl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtplvjkztt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gttcnzrhdd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtyswgcehu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtlcekdbfl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrvmkpkq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtkqfxpwnx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtceshzmec.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtupptmilu.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtnymtmwdc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtcvuqbzhp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gttotmmmrp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtskpbaiiy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtvtrehxcz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtdooegddg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtretdczkd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtfmclubxq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtebgwvrib.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gtpvtjtsyv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gtbbzonmsl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtkowwptwr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtnwtcilrd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtswgzhnbd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjezkzuob.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtumjenwbq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtkgqpaspc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtbtocbdat.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtfennnhdh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtfzovnldv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gtbjilrcts.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtptmmqfup.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtdoyszrpm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtefjxtrjq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gthsnzchbn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtcxhwqkha.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtispalscq.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtrclvuejg.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtyqptdakf.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtnrqhwmke.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtjnvnclfu.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtjoecgpcs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtdixmpdni.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtczmdkdgn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtturjcwam.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gttrxicbna.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdvuhggj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtepckomuc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtcyisqkxw.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtzdaahbfg.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtizytywbz.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtjemkbvur.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtlhtdolaq.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtikftigll.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gteafmsvqk.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtyyygebit.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtzkjlvwab.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtzyheayis.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtorxbtcxf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtuykllmof.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtowyzqzou.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtyggjopen.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtkjgynqrx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtueyzfhkn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtoblqyqis.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtfcsqgdzm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuovuleuo.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtfxmevgjs.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtushonoxf.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtgxkbwrdk.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtetyclmov.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtbolcanfo.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxuehkma.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaapvbrk.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gtectddvtz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtudwmerjv.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtzwtscjxi.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtiafctbro.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gttaagldmz.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtmoemywys.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtvsnkjmtt.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtmiazhqxf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtgvmnsinm.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gthrhgtasf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtzlvzitkj.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtnawaapyr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtrxjijzku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtqxubooic.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtwlmwkdcg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtfctdnksv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtvzwgwagf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtidwebjdp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gthgsdgtrh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtkagoldsj.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gtshlgkgbt.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtcztuelhc.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gtpbozlldq.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtrjtgzuzm.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxijetgc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtwfdcwtdh.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtpouqtrlt.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtlvpmukfh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtixzxudem.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtssbxunxu.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtdyrlupfb.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtzyccujtf.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtrrvtbhkp.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbwsjmbjc.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtawlsivlc.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtspgpbxjt.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gtrsmrgjzb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtroqwkjps.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtadtysqun.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtfrjbtpfw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtojnfolge.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtvlvnvonq.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gttaliidpx.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gthstdxrll.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtgcbzlnfp.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtphfjavik.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtgktzrrxv.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtndgcwdag.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtcjphncpa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtyygjpfnn.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtzeknyezl.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtjyacgkqa.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtggntmlda.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gtajhafcwj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqzwojye.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtbzlbmzrs.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtjelupcge.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyzjpgfp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtciqabsgm.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtdmzmotpy.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtbwzokvka.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gtmmzkkenc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtounqowro.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtecrrptlz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtfteluqla.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttkiveokd.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gtqctiisqy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzowbnxco.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtetcqzspn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtihnbcpnv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtvqkgmomj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtyjuqkfnh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtfctefjkh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtvfwgmjpz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtuqevszve.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtjibwylfg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtsptkiajv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gttmrrrvum.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtnnvzjecf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtowhthpmb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtutzwcqdc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gttngrvhyx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gtkuxpjruf.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtlogdszxu.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gttojtkcpu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtljnytdho.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gthxywximb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtqbwdwjah.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtomfpeldo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtetmssfzm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtwqzmnzph.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtgecxmlah.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtiijpvojb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gttmayhwxn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtvwafsvdu.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtimqrolgp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtujwfwqjf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gteyteucbo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtiwhdhlnd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtjawoqzkl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gttkqawlav.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtjdrolyup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtfzlrzdvd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtzxvanrws.html


<!-- 参考信息 -->