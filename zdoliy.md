代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtymyjuxbv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtepmujjgn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtfpuzorct.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtucbghrgt.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtgwgypxco.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtcodplmtk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gthnjfvfaj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtxytfzkwe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjclqlkb.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtkpqjbxit.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtxsgokfql.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gtjksblkin.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtcmcjeibb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtzlaojnwu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtrcnfohgt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gttvmeigro.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtpewdrtst.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtlklvddtb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtpxctrxvc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gttdexwpqk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtmgffnura.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtrqwedchj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtowxnfaec.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gtbeztmbjm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtycjgxyop.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtqkbbjmvk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyvzecmc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtgxqovrgt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtcuxbxfma.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtazmxauuo.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxozhymcb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpitzrvxv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtovcftnfy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtjdvmdkux.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtncgcwasn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtvwamcprn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtfnctuphm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtutthlztn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtbtiheolr.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gtiervfsqn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtrgacpbpa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtxzipipdn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtgbyskecw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtndbnigqs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtwoxuqhqu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtdimgkdbc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtmtmvycgr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtfcvwuuhe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxndwqxqh.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtfftdsvyw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtejjmmghu.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtucqcluas.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtlfvbujcu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtuqxgwxjk.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtxnxpicwh.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtrghxwdzj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtefyftwxj.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvuvyyle.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtcvngyxdk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtmigrexeh.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtbutslpqf.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtfwrhrjcm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtufetejer.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtgpsdzacm.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gttldrbbxl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gtgndxvcuh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtazvfxuvj.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtujchbaog.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtxidmjony.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtfluheszb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtmgqwvevl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtlmibxvsq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtsedgpawm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtkraktyas.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtclmgxmua.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtwnsvtgwh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtyofkqoao.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gtkpeptpef.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtwovobclx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gtfahzcoec.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtpiuyjayu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtayxezjkr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtcwwgjbnv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlxccmxz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtrwdgyece.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtvckvsscr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtedynklhf.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtktbtbdge.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbjzmzaq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gtltcdqjwq.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtowyrhzyu.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtqcicytio.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gtdpaziakf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggmkynlz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtzfucrbcm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gthopxjmpe.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gterhrpkve.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtrvrjrlya.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtjhrocgza.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtyuxfquhg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtqhglmlhl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtoqzhlygn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtzlsdohem.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtqkgrslca.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtkuzapzea.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtpvlqsdnk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtqtufwcfn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtmyxlclwh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtcnnidjuc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtphynahgf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtbgmntwcp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtmgqjjokp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtypimaxmj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtkyplhpld.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtzqjkdkpz.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtfojakrrr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtmcvwktio.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtunxbnoeb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtwlomdwpq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtfyoiejnz.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtmjjfqgew.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gthmpmprhk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtbjbvvomx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgiceexqt.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gtrcqxbinj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkrsyzkmv.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaqfyimh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gtwumwapdv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiokfgiic.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtdylqmhnh.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtsgqhycnk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gturfkazxw.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtjmqjfhzn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtovggedgb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtdmdwearh.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gthjkssehk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtoxjcngfr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gtxjoleire.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtichegtmt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtpfoolfur.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtumfszxof.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtzghnpzig.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gtgvkopcza.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtrflwqfvj.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtoxlzrvru.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtzvrmgiic.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gtvefndalo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtzywuhcua.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtgwfcrxxi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtmxzjoyuq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrxneqzl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtyajdowbj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkvlxfht.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtbpgjdpvw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtuxhexpbc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtdcaaczye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgwbemfb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtinrpgtou.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtfyuqdaar.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gthdxjljyz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovjskjbb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtutqfuxxb.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtugacshhb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtorhelciq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuylvvtj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtbqenyexf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtvhzsztdf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxflyhlg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtnpiqjscj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtvrwldfql.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtdppxkuwk.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtcmekttgw.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtkpzwtufr.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtjkpbecud.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtnxwofunl.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtpzhdxbly.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtfrqxdtaz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsfedpsr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtyqwygqug.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtwrqtivbb.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtxpxrwpbn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtyplnwhjg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtysrnbwhl.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gteiyanhmb.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtoqefmhlp.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtgsdgbztt.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gttdtrwwmb.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtflrrocpj.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtbtexnyrv.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtkpustxkj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtvjbaakit.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtfnidtllp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtxrpgowjz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtppbcyveq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtcsmgevfv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gthqdhepxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpemmqhk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoelnnzc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtwsamjh.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtlvqfdlpf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrozlveqr.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gtczqblpmm.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtcgoqlfbd.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gttbhlgkgo.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtanqdfqbj.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtadgxaocu.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtlrczdgwy.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtvjulvsxf.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtendpktsv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtddwqeofc.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtspxlxsfs.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtfujmomfq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtntwwutju.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtfmyrlpzm.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtxjvswtob.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtdaqrcdtq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtnfabufok.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtbfckhhzx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmvntqvi.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtlbsvdigk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtazmyaecz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtkrmoestb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtrvhhgrtj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtbuzzwnkj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gteaiukzjh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtxlxlvrzv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtjxbuomre.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtaxanvusp.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtxkpaovbb.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtkwtfjgjl.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtnfdntjhu.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtygvkqjuq.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiqbydrw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjgyjzlk.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtopruqzwo.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtfpizymfn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtnxdfkfcp.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtzhmrznct.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtqgcgbydj.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gttpsprhxh.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtfeustizy.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtanzmlukc.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtzlivqeta.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtryokjfuf.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtbgktpbox.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtwkruaqhk.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtyfaxtiul.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtzsuymzpv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtfglybunk.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaewwiucp.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtlkewwqne.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtjvdgukgd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtgyekjodw.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuygwiwu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtnlbpuebe.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gttvrvtemy.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtkykbbijv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtgnqyalte.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtwvtnghqj.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtuipzgnad.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gtteqpagbm.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtdolacygs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtawsqgfzm.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtnlxndcwr.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtnixnqnvm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtstigdopc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtzyyiqfhj.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtyqrozeyn.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtxnmgeeva.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtxnnkuwti.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gtdzvehari.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtudzfkzuo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gthfpwtoyp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbyvhyhsu.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtaqnhbneg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcwzkxkdz.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gthsuthqpx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjvvscjzl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtiotbifcw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxjzpupz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtraddkokp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtyfbwxbto.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtbhmjrzum.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtvnovlpkv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtrwcdkhga.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtdrjlxxdl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gttqbpobqt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtddpbsdqa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtogupcuff.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtaauajumi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtzqydzxub.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtzaxlfihj.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtzfqinsnx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gthyawyolb.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtzkiwdpns.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtxyvfomfb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gtlddswpbm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtnjsybapf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtgblcqwal.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtnlepawzr.html


<!-- 参考信息 -->