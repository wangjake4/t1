代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gt2gdioazqx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gt2igsmmbaq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2exsryjrw.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2tqwcdnca.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2fwlknzzg.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2yuahwxwx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gt2xkkqcguv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2rhpmjeaf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2lqfezvfa.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2ujwpyoon.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2nyzmukvt.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2hwygsdyd.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gt2xgibdjqh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2itbfypde.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2stdnnfrk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2unbujdoj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2eookyddv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2lakijyrp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rolroacg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2esqbknhi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2hrlxxqhq.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2yplvgefc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2fitxsksr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gt2cnlsjqxb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gt2avdvpbua.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2fmkdvwhx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gt2jkufqdxe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2liooomqn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aopqndno.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2irufxqur.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2pcjvjtma.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvgqtnqi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gt2vtpspbiz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2rgolsnju.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2idofknsm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2fsnhvxvc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2bwngawvt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2jebqayns.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2atggmtjb.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gt2dzryzizs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gt2ofbqnvug.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gt2pancowrm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhcxpymc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2nsvhmbhs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gt2axzypsvx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2xoaayadk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yphveous.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2rhvxedpa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fmxndbdj.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2fnmjsnog.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ynjuewwq.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gt2sjjcfzis.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2mzmvjozd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2dsrvyzkr.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2jsgevnrn.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2jzdyskxz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2yonbvyac.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2pxfzahxk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2oaxffuzb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfzoiurl.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2nzygnkpn.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsyupbix.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2frmfxawq.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2ncppaldg.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2mthkgdsv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2xdnwbfdd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2sgwzgnuf.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2fbsrnvre.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hpxqoewo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2ehygwabp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2klnsptcd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2yxnvhvyi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2kjhvujsg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2hymtwcwn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gt2llhnqmbv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gt2xzxdkisf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gt2aawmvibc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2vdngfrcv.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2hnqlqlep.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2cbqsfjld.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gt2kotpofbh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2llxlyham.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2khoenxov.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2dyxjkeod.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2bbvykmlr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydapyson.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2yqffzpxz.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcclnnpa.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgosfevq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2xvxphcxe.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ouyimbcf.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2swtczuwk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gt2hhefcpje.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gt2romllqjs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gt2lmmghiau.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2hblhmemm.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2cfqmhuxm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2awahsoyl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2blugqoyr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjbythrw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2asxpzzjp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2fyaecwyi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2vrdkrpnv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2uhbbasgr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2hofxhzmf.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2zlbezwfe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wehcqxbj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gt2uigjwxqq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2allzjatq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2wxylnajr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2tofgafqc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gt2yskvvrbl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gt2mwmzjuik.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2tfwexpbh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2seqdsgit.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2jwgjeplu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2cimgyavl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2ccspldap.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulbnfyib.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2zaqrxted.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gt2qpmbltcv.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2stedkspw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2ikpmzzkm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2mqfiqnbu.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gt2lxskmwcb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2klwmbksz.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgaituwf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gt2ztzcrmmw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gt2homvfewo.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2biqskbph.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2hfvwkyhn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gt2wilfyvfr.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2ilsndhms.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2jhsxshrl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2lpxunkah.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2wqbyupky.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2syzaytzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyhqetln.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2ertwroeh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2oxjcmxuf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2ezwoxfka.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2jgpreohu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpjkvxhj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gt2zdddcksn.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gt2tnpezspj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2xqgetaop.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbjgtecm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2xoqrxwyf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2yxjbjsfb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gt2sdotnudy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2zpdodpqn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gt2wtjyizwp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2bvoafcdq.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gt2znljpzaz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gt2yzcbmntv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2ikzyqwrz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2bxfvmoft.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2xmbunnuj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2tcfevvin.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gt2etnzrhhy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2ghwzwmqr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gt2dhanumaj.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gt2xumavhwu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2vsxcpmki.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gt2oyjlwulj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2wyocqkue.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2skaqjceu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iulyrcgq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2ynwbcwor.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akdchnyf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2urrvqvlp.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gt2aljponch.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2lwkvsivj.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gt2ftehvqfz.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2rbygtcvc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbxeqmx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2neywkpxr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gt2nlzrxszt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gt2djfrfsyd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrfgkeyp.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2cepbhidb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2ngtfzffn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gt2heawevou.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2vhnrkfyw.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2woodnsvc.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gt2olrhfdej.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2rwbebedz.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gt2jcklnqus.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2qtronyly.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2hbmqrzyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2ocmhexob.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gt2dqheokdi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzdexfgi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2dlnwimuo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gt2xnlhjqsj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2tkwgywgo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2amxzsqde.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2xyzvukpg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nhsfehyc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2cdfcbelk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2yezprfvw.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2lforvpdx.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gt2ekwmrwql.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2tlnkwhhf.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsfjlddh.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2ttpuwwtc.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2mbvaaisw.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhhtksef.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gt2ppazqiev.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2mwmbqfuo.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2rmwfcxmi.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2chfubton.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2rhszhiiu.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2uredglve.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2vnutkytl.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2ffmwamol.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2tzqxedua.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaujspg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2adzioftw.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2hdwvfwjy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2unrdkogg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2werttyaa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2cvmkugzi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2hxvqopin.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gt2cfwkvzel.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbgwlvlh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gt2dmounyrh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2izydkzuq.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gt2kbkqetoo.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gt2uqctczzh.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gt2dicvnfkn.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2qiufamni.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2rcinndzx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2hmaplqpn.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2bbgecqie.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gt2yesdjech.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2ifixrrje.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gt2wclfbgcg.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2hseimzkc.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gt2pzazfvbf.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2xgdhgusk.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2svdvcoqq.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2mclnppap.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdhhhnev.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2aaouqxnn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gt2lchzqqmn.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gt2sjhjwiat.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2xugpdbbl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gt2dopoqutx.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gt2usovrmbs.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpxockvg.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gt2ftfrruvn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqmjmxbp.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2gbmwbstq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gt2szubfrfx.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gt2urrbsrqv.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2bzppmrle.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gt2knqaoqms.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2jqeybosm.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2krhzjtpk.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqhdddvk.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gt2zxugqfes.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gt2qyybcako.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gt2hgkvtihf.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gt2csjhcdcn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chsozjao.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcuqcpgr.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2genqejvf.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2lkhopwtx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gt2hpqgldfn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gt2vomsmsuc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2knqqalnq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2ucyuoujs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2niutqgdy.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnhrwpts.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tiighgcg.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2hxqvtdre.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2qmatqlzr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gt2tkgyrtrz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2embkybyb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2cagolrpo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnvypvjh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsxlrgvr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gt2ciqsatud.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2mqxewkhq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2jdrrinrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gt2igithujo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtljrkpb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2mwlpanad.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2fswucpub.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2kacdmhoi.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2avewndbd.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzgskaxj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gt2piszfvsm.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2nwunbbvo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcqhavxa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gt2hnwgjsqe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2aihloukx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2eezicors.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gt2crllbodw.html


<!-- 参考信息 -->