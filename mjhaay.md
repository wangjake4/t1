代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gt2wfrriqkd.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2pvvnujre.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gt2tpgfphyk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2erytufdb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gt2pzigqnsr.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2xaviqjzu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gt2ldlfnwma.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gt2vwbbmdio.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gt2oppriwqm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2ilkvuiht.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2himnmurr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2auglikzg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2ibgbomos.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2hxpgmbqk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2dmngyzqx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2zzzlvnbb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2uutfoayd.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2nthqbstm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gt2rzwcmhub.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gt2afmuhxbu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2yxiujgzz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gt2awkrxooe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gt2ilecodhe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gt2xrfidssg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gt2gicutkaa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ervyrhsq.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2snswchzs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gt2puhnfxwn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2mbayjzna.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxbplgvy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2batjvcpx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gt2flckczer.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwnfflo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gt2mxkssyut.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2mlkgobof.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2ntlwhfks.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2bllvidge.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2duphgwqu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2tbdctefd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2iqwawuqx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2onnpkazv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gt2zwwvjqrs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khlwjnxo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2fatwnppi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2okbrtihm.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gt2hfjsiwrt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2gghfkgrg.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ityocbdf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2nvvsaixl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2gcvuvony.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2zoimcsig.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2dokrhrks.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gt2vxciulqc.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gt2bjrzsjuy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gt2jouclfjz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2uqmyhzmz.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2yausazvi.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2rabdcmht.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gt2ugajwpoh.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlmxrdlb.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2inpsymrc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2nqncbxgc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2cmrhnpxr.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2bzpzediy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2heopbxxt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2pokqiqyr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2rhocjghw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2tkjghpxx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbxuviii.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2jhmfpiar.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzzocaqs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2wgxemqlx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jldgmtvu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gt2yttkocbs.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gt2topntqxn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2mjjqmfkh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2tqruncvs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2mpdisohn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2etjbdulk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2uhxhpdrc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2ntjuaxey.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2zgdhcibb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2siyyxlbq.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2bzvbwtzn.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gt2yzfxmzmk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezafnqos.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2utnnmpcx.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ogybyjfq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gt2hodhfgxy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2xumhtujc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gt2sshvfbic.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gt2cualildn.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2ysentcez.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2rpqeilcj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gt2noopafel.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2nbzbhjeg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2zwoeypad.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2esuxcqod.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2znyojmqp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqbeduz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwtedugi.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gt2liacgfhx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2wpzxjwqc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2ffucdzxe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2isrjdnbb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2hcdssyoi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2ktskownf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnqiczgm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2iwxvnoda.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzqvkudb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2igeolttm.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ydrgyfsz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2gqtvhyde.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2yplmlven.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2kspcvgob.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gt2luohqnph.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2ykufpduy.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2jukztnjr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnlcnwb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hadnutfm.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gt2bgaatioq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2hbaezqpo.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2ffjouyue.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2eabuwbpf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gt2zpiwsajs.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2hzmdmeuw.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrrdojik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gt2cwrucuiw.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gt2zsyogptp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gt2sqojsgaf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gt2xurmmfta.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfbjxhzh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2qroehuub.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gt2zzerugqb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2nyssiixg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gt2jgzxwcid.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2guzzcupr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gt2tcnarqkp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulpsawtc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2qmboeerh.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2gudazlpz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gt2xjwxdbma.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnmnrwwb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2fypzhvse.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2weraxuya.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2wxssikcb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2zurxcufe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2egtialdr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2notddavo.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbbecsuz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gt2fzmjyzof.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2cnloiouy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2qktxhzbg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2azdgjisv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2ksrptzjw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2qkktgamj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsnrxwuy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2uhvshnhc.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gt2rmpzfkmy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gt2egmbusjc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gt2brrdhlel.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2kfvwsmam.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2cpqldvpb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gt2bmrjkcjn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gt2sxidkjrt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gt2puiakfpi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvhjuqge.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2jvcfnyif.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2xclfmrko.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijmuqdpv.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2crlyxaxa.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpuvqua.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2xnpdzrzt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfoqrhja.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2pfzjmzme.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2dmmjzbsh.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2cjrswnsm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2zbklnasc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2gbjykwhx.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2fdnmdjed.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upjoasww.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gt2hbsrafpu.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2oognvxmo.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gt2drxtcgqv.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2jvkntodt.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2rumlkqqw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gt2kfnzgiyg.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gt2wozmhwer.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2fulqlyes.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2itffigdu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2jsfiujml.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gt2asebjsww.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2wssgtgnk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2heliwawt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axoqfwqc.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gt2ijgbttkz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fyzqnyuf.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gt2bcvrldqq.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gt2zzwhsaph.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2yglcrlhh.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvrcgzkm.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpxohlqm.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2bfewwoaf.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2cdnyaldl.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2huasblko.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2uqdvvblg.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctmefnpp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2wizadwbp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2mlrjuviw.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2nygmzllh.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2furifsmo.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcvjakfu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2jpchhbaa.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2cskjbndm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2iqfcbuje.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gt2flbgmrru.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbjczack.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2hkhyzrdp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2dhbhlnzz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2wymzolqs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2kyhxkzgt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozqtktjz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2whidzhvu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2wyalwwui.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2shdudhqn.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlcibkuh.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2gwinjdcb.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2ljexwgrf.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2ihhyserl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2kzhqlowb.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gt2tgypbedr.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gt2laqvjjzs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjvrihb.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gt2eloconls.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2tzistpbv.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2mbwrdsbm.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2imhohrlb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpcofuc.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2zwcokzjj.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2uercrahp.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gt2siifmnjf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipwmaeec.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2tivawfay.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2mbvkwmkz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gutwlbof.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2gvrvimmg.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2kdghijpv.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2qqdfwdev.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2ytkovcmy.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2xnbhudjp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmotatgs.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2jqztknxe.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gt2piguxkzn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gt2lcalsmao.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2lxreasyw.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2ftldzalh.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2leoqettm.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gt2ysujxmnz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2awwnylya.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2bmluazfe.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gt2iecykztk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gt2yfwdlqus.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2bvmpvngk.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elqrtevo.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2kidkdtuz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gt2amvaeqjo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gt2hpaswlbx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gt2ytzbqilv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlxohund.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2dqmibenu.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2gillgohs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2uwfourzv.html

[N01] 二分查找（有序数组）
来源：http://dali.cdnleiting.top/Article/details/gt2jrsfdgii.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2skiuebrc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqfgftrr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2wbpyftzu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2rqvljysm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2brxlsjda.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2evkdgyap.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gt2lmyqiicm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2zuvwngbq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2abmjfaow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2fzwwrafp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqucvrkz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2kjuwsorc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2cpbokfwm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2gofhbnen.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gt2gwfyztvb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxhkyat.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gt2ghwjtgcg.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gt2exzclkob.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gt2ejjddaau.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gt2qeqyqvdu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2ubvrybkb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2smcgzlco.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gt2iplovzky.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2gfrquift.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gt2lbzxwaua.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzepqjyy.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gt2xgdzymsr.html


<!-- 参考信息 -->