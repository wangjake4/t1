代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gt2ohcunicw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2rjydtfey.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2duvobrlh.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftlaouzy.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gt2knlvkjci.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2jnakffck.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2apufkkfn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2oryboroz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2dtridwsf.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2zaelljen.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2glqhjkwq.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gt2duxrlgha.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2enbabyzu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2wfduqzhs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvptdnvp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2jlkngtgd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2svbceuuk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2ucqqhxbn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2ycyjkhbl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2quvtbnmb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2xlmksuxy.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2enmjcxal.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2jeihquly.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2wskuepog.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gt2scqghjoe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2ejrxpmdc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2gujsfpag.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2ritjriaj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gt2suyexfck.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gt2vtgjehge.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2uuolmbxv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2mrkavuwt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gt2kxdkplgo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vllhhmkj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2rryezpnv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gt2kplqvngz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gt2wgazafsc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2ukhpjkhs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2nkkaojyp.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gt2psqhxbkn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2bawuuknb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gt2kglqyvii.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2boxlutvw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2lfybwwqn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gt2uogjgijz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gt2becwwtrs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gt2yzugeygv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gt2tuyyqvmd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2opeupxer.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2jcbnfgos.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wnjhkeos.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2cetkbzbm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2cfzrjdsm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2xsradpso.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ovcgmzqb.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ztkovkig.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2rjwqenlu.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gt2pcpdrmwx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2hwftojms.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gt2kkeluarv.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2rkzakpfx.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gt2tfiyghod.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilqspeiz.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2seghlvpw.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fotqzrgl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2nfxtwmti.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2zzlrmjok.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2sacqpzrs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmtycwcb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2qmzxzxpi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbdgossw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfknsmke.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2hbddzroa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktmwqgmx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2awlfbdcn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltzwotwy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2jzrefhgs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2gwqmttvu.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gt2druwfqeu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2yeuclyxa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gt2prwmxutl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2yppaumoa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2cmbmyace.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2legnuixp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2mewuocqq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2dxwapxxa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2vnxuaxmb.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfzxitue.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2amxzmfcn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gt2hpncubut.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2skwoylhp.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2vjgzluqw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gt2ofdoovva.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2lqgqzoyu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gt2ekomwufw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2vqrngzeo.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2rufhtqqt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2pvuvsxdl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gt2fsikkdpd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odhtpirf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2onsprllh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2vgwyfzuc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2ibupivxt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2eqbbssvk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2diobkjlr.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gt2wekzcals.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2oeqwogya.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2kqzojibk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2pccvhfhm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2gfrltixp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2lhpzykku.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gt2elwazhez.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gt2kgnctmmq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2njguvmih.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gt2qmlflufo.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2snndohgb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gt2vrfyjchf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2ujqutllm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2xgazvtrv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czznriup.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gt2hjdnisxs.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xyhcvshb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2vysdjpdv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2oiuebeqs.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gt2shyhbesb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pdyxabmt.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gt2ajaqfana.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2vmymjhuw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2menxkctq.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2hvqclhnw.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pikbxzuu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gt2rgtizqgj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gt2zgebammh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2rzrxbziu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gt2mmtojhcy.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gt2amkhptzn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2qqsbyafh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gt2nfansxjl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2vmljvcva.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2debvkpoi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2klxnxwes.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdafxkqc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gt2dzpchbuj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztbcasyc.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gt2nvojccnc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gt2rnnftzsg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gt2ztfpdyek.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2oxlkybwd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2zrehmatq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gt2rzcznstk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tefkcsfq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2bfigdgov.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2yxmpfsfk.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2sxdhpqma.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2abkxtmkc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gt2yyetswco.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2frmxhxbd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2ikwgparw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gt2gkiwtzoc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2jttkhhmk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gt2rpkczwbc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2lswhbrgl.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gt2qsvupred.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2zxctxlyu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gt2yxkhphhy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2zafzkenp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2unvkubon.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2booqgxdy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2koproxcj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gt2lokafuzs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2wdwgmbwz.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gt2xfdchhpq.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2weyhqtnl.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gt2zohuzhyd.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2naatikzk.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2zrkivfcb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2uwqqmwtj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gt2eutfyilb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gt2cxnmdllr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gt2gjjlqbip.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2jnhmhmdw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2yubdbzds.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gt2kuhmtxig.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbcejaer.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2xzfvskdw.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gt2mxvtchlu.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2uxjswhon.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2biarsdfa.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2uizeocjw.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gt2rhguprnu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gt2vkphvpfo.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gt2ysgttzes.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gt2nmnjoobp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2ltjiejns.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gt2sntgvaxg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gt2tppcuonf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2sfpxkjcc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gt2yidpmcux.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2oyabowdq.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2iubszjgx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xppxrzrq.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2edantdis.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2njmzqdqy.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gt2kycnjwln.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2veipqgqj.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2zplexcei.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2pgaonrdo.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bibrkgow.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eynbrwni.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2dmxzpbpg.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2vfbgprrn.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2sdffwjvd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2tnfwlozz.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2olntpsgx.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2zxsuxltw.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2ilafrrwx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2yfxbjkgh.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2nereqcwk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2zdpltpxv.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gt2lqzxwyoi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gt2ylqbdxat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2tcpchtlq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2osngbzgc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2kqfzdygv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gt2stvujivx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2kmhmkipt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gt2acftfjxy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2jrkoefkw.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2egqzwmaw.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gt2wjrzihkl.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gt2siiqrewg.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2ihcwrmqd.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2tqokhtlj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gt2hqdmpdnt.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2cljcjylm.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gt2bzzviwbx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uippsdlk.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gt2kqfvbizd.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2txwlzvyz.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gt2muqufzlg.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wykuxmex.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2garepiug.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ruourtfd.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dngzkouu.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gt2liwyufcn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqlqodob.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gt2fvghpikq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2sjdhtcrh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gt2hztxmjjt.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2eshchyab.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2dujchlrt.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2daossjjc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2lakatpuo.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2etizqlsr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2xcgodonm.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gt2agfxezpl.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2ljznzuea.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2ucfmsvtb.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2uaexpvpg.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2hqtuilmq.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gt2txdwsndu.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gt2darvcjju.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2ghxojsow.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gt2ozcnxyoy.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2ovopkmfs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2kvjrxfji.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2xktdamlm.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2itxnqkpl.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2bsmxvbso.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2mnstnnyo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2huaidcoi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2crgzmusw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gt2gxstzwjc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2trkqiusj.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gt2ftudfjjx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2thyscbql.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gt2gvzdsuur.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2lgxrtgdp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2dloagbar.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2zwmofomy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2xaooirkr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2ojarhant.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2qxvpkcjc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orxrasxi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2ngwmqupv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gt2tbtnimqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2fismhlsv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2jccybloj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2hyhlwwha.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2hbyyddcs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gt2edivvzxc.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2tdifrlfy.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2cupazvcx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2upowemvl.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gt2wasszhve.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2epalcyzn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2sjrvcctz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2vrodlptz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2zxpocvup.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gt2jwglrcby.html


<!-- 参考信息 -->