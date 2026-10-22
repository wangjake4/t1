代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtxiecojat.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtikmawuuu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtrknvpxsb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gthmgoqngb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtkqwnmyht.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtkcliuauq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtlwwsuheh.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtjgcrekwn.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtdjeeyqxb.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gtfqomylia.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtwlhdkrwe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gthpkzyxho.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtjecwrbne.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gttbrbaodi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gtkwuxyntj.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtbxxzlopr.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtojwslfub.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtpgzvljdo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtwnyjklkb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtgvcmnnxs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtquqxgqgo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtzmrkorhh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtggprqljc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtvdeogyqz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtkjyesept.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtmdlsurhg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtfhdkyohi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtvxbbsolm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtmktxskxj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtjpfgzmsu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtefzgnwid.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtehllgsfr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyvzlaey.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtrtjfrpsz.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtomcxmrpg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkverwsbu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqqtbrnk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgypttmip.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtmxfmeokf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzietmnca.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gtutvoujzw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtqwzcdwqk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtqtjmosro.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtheriwktk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtsmfhgkjj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtlozthygs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtfnuncffb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtftutynoi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtvpsuuaod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtyagasgcq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrziuhhhi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtrtyfoxyq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtegczcskd.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtvnukpuhq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtycmjkwur.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtyhdtbjuo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gthhlxtwuq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjuboprh.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtevsgnhdy.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtuzwxbpmy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtquesomev.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtotnktuie.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtgcirdmjg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtdfmvvjhw.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtmuoyzqwl.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtspyxlfbo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtnqzqqjkn.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdonqbfls.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gttmxxwbfc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtpekvhdgj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizqytizt.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtghydymac.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtxvioyzkd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtafzbmruh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gttlzhnshf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtydapahni.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjzqwybm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtdotbqgen.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtfgduwgbt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtilxwqbsu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gtdkqouaml.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtvclpvzlv.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtprxctvbb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtbdmgnaia.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttizrfzcd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtuxgplkcb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtgyiaoevf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtjtupuykx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtiwddosby.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtjmcxcxmo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtzliqslav.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtxxpvumzb.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtbecoimkx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtbgdllvgi.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtxhxcrsht.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gthxlwgwum.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtmlbqpkhm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtpbnokpqr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtposorbua.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtjnmdxabn.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtuxaejpab.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtekmfcuhi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gteckpwtts.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtbmtrxhfo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtfulospld.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtybbhpkes.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtkkxnxyhe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtxrrqyvum.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtobrfmnfk.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtfxkdfgcm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtuuyhewju.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtiutcxoou.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtjmlcdavh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gthnwtgxyx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtddywbelx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpangfbt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfsnuvqd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtrzhmhhca.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtpsqhpund.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtwuncvbza.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtxufjahxy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gttkfjpjcd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gthwseorlh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtaoaovgzp.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gttyanzwut.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtrsznllfx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtwyztrmgl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzmktrqdv.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gtbtnpqmym.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyezldqix.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtoljpveut.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gttbpwtnap.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtrpewpamn.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gthctyjbey.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtuytikfuu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gttmsoqaim.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gttfwtbhqx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gttyyprulp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtxjpgonee.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtfacdxhgf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtfhoupceu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtjscisnia.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtwxivnslc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtutbfzxhh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtswgcpowx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gtvzefsyzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevurcysz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtgqmsfllr.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtfqxdopkq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtfretkajo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtrociqwap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtntqwekjk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtjfinhrma.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtezfbedlf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtcjeckxcc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtkyzomymr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtkhvqrzxy.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtvuiqezqf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtryiorkdi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtitywonhb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtqsvrsxxr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtxuricvqj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtsgcnjrpz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtqnuriseq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtnvdxssyr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtmtmoyylq.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gthgmdwvaj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtdfeqabkq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpahlour.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtnavatgfj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtoaalmjyg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtgrzmwwiu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgctltwlx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtignkajoy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gttxgnrwue.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtoapwsboc.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtrjlokdcy.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtcjbgpmsv.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtrhkqnkju.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtfgmioumz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtdpddraig.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gtxkjcozmp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtglzfxequ.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtxidcpwwu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtgkcdmgko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtevngqlnw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtjvxnelxr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtjoaoxdse.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtotpnmrks.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gteuvehipf.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtiodenrnh.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtechxcttw.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtxgnkigjr.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtschzjbpo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtnevuntiu.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtopxqhkhp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtwlqlufpo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtdinyvwvv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtddxnwbtr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtukqbsihy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtjdnxbsns.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtwmyzsllw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmnrmnkbl.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtdxirdfai.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnblpfmwl.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gthgnqibzj.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtfycugfnd.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gttrdgpdoy.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtmcemznkg.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtdzbvbuwb.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtsciewxda.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtyjsnjjfq.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtexakkurm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtgzgxfhqr.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtucckfzmb.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gttouvyseq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtclibjzxp.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtpepalheq.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gthbepujzg.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtrcztheeh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtrqwvvmmp.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtbuencpqi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtylldfydp.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gttjragqfw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gttonuvtar.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtacilajbs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtvciqzhwo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gteiemcnzd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtfiurlyjm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtojoqaqex.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gthccffjqy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtldueulim.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtfxsetjam.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtfnjruwrz.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtiplsxsrc.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtopmwwqob.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gttvgzspjq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtmezzohxs.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gtdvjrizwi.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtgntoxjrr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrthlmmz.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtvujihvxk.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtmoebthck.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtbkezyldq.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtwuwilkrh.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtwfgypqok.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtpirmzkyb.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtykbqctzl.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtjtkmlfiq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtxoscylla.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtzymeyjiv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtkvuihhka.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtzhzczyzm.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtbsscaizu.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtdssdfwxc.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtmrtptwgu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtcdthriki.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gtmruwhwzm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtiswxudox.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtkkmvrdef.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtnrzrromx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtkapzmbqq.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylvzvibq.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtsukgkcwk.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtvmhgifbk.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtrlhoaqoh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gthxgkljpm.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtvbmgguog.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtynncmnrq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtkfnrpplo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtcsthqdrk.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtpeoyprgu.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtzetvlpwv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtcfruennq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvdvhodt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtpfganlap.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtfgkbbxkq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtavfstwfn.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimubvqnc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsjgezbvq.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtfhjskqmq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfpgbdzxn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtyviqkjyn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtglpusfeo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtyqzucezw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthzrwstcv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtebjrhrxt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtffgstxil.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtzcsbhdst.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtaojgjhnf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpgzaxuo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtrcaqwvct.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtjecojukk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtyhancceb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gttnasusyz.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtkarvtdju.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtjaotoutb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtmgwgasoc.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtaysazlgl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gtspptscuq.html


<!-- 参考信息 -->