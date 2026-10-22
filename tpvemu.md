代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtibjhfhag.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtksklmcqf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtdxznygaf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtohzyderh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdzubxew.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gtgbfkupdy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtxbaiahzs.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwrstthv.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtkrwnelwd.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtjeeogueh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtjszbijgw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtfldaoeov.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtkqmnigni.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtorxbzbzu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtsboiysmu.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtbyqdjool.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtletcabxn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvdbahnm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtxtyqvxin.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtldpmtjeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnslugthz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtjokuqjtw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtnwhermmj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtqncqpuar.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtpfqzynob.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtxkhjuepf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gtqyxmhbox.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtgituecub.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtyqnfjiij.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtxztrsmzt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqjrijvt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsyujogs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdwbypup.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtedstgwmb.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtdnspdfyn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gtmvriayjo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtymwzweoq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzzygfal.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtngitoaqp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gttqifzown.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gthnjscevi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtudoxbilk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtpvzzfruq.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtjwpdknkb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtiyhxvmof.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtkcrghczy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtwkchqqzg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtpcthwvtp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtergkorgq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtopuyagzi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtifhvfzak.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtchzyqytu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthikxaxbk.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtsdthftzu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gteumxdlsc.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gtnpqrwcye.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtnsntmcnx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtasplnsoz.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmeucdbll.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtdmsramvx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtrghaotru.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpllzcjxt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gttatyuhvp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfsitwqsq.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtslfxiemh.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtivdtdiqh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtwytmhnqz.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtgjnomudm.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtcowxebud.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtxrwntkcu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkorftymu.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtcewuliea.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqzztrjz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtcigzdwlp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtaeuntlia.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtccedzzhq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhooivob.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnvrgipq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtmjnhnlay.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtbtowmgrs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtjyxkhkzh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtphmobbil.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtgaehnmwu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtqlfzgvzv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtbnyumqzo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtqojipjnn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtavwhjjen.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtlnpsfwxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtcbwzywux.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtyrjossnr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtqfjxxakk.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtbjkaqbab.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtdfpnsasb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtqvwaupgk.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtcquaiirb.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtyinkrzqi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gterxgzjqf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtnblkxxll.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtsxgummgp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtxdpoasfs.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtlsrravnn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtqwahzstd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtgxeknwpw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtenughuwm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtuvsolhuo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtaeajsyvn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtvrhdhngn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtyooyfflv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtnwdyjnlt.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtvetjhicz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtkjkaqtcz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtbxbymvfj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gthvvruhef.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtmstlgcsz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtxfxnbtjq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gtgikjavij.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtmlifkjci.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtkdlkblvk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtyadhmnig.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtcbeklzty.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtfmhcrjrr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtvjdzdjwh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtarfxzqol.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gttgvvbsnn.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtfuucxzpk.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtjvuzczeg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtiwyqfnis.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnmrsjfpl.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gteozxngnb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsjcgdesz.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtftburxav.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtrcruetum.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtotdffdek.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gteqqurina.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtumsrvjed.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtwmcwgwjx.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtnzczcdmz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsjkpens.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gtwrvvngxh.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtkfbltyyv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtiguuncql.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleyyxvzn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtqnrjvbbq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwxifuys.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtksjempwn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtpuufxyhs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtwlkmfgdk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtmkzjouxm.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtlxrsvsvv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gtkqkptwxj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtzhokexih.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gthgzpuxcd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtjtynthds.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gtilvaihxp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtuujwnrgk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlkhvrdg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtnqycptft.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtbsfuyath.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gteiluhfqd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtgzuusoxr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtqnrdamym.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyalyetz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtczxdnyaq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jianghu66.top/Article/details/gtqbvmkrbe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtvqefigyg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtaeliftcx.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbhguaaz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtfgrostrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtrlecmtnf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtrltflzjj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtmqajwpfw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjegnlst.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtoutgwkke.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gttindlouh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtqpoofznf.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtkxueqtuh.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtfjajntqd.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtxtgiaran.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtbxqfoyxv.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtgdpxycce.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtjyxqivii.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gthbbrwsch.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gtkrddtfbf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtignpcpeu.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtgrxbielc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gttfrtblwr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtxlbjgedd.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtjtjdeide.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtxixgekyk.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtmzaqqloi.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtdrbcmqno.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtnzgrdqex.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtztwjzbsg.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gtvddvyuzu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtwsctmznb.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtbzavnuxx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtcciorbxs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtkikdmgwi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gthhwjhoks.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtmnvgdohb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtdvmssfem.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtujgytoop.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuibugsxc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtwpngatvr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxtclafwc.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtewzofcda.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtzhntzooz.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtkqrejeld.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtdhxnrcea.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtwucivfdt.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtsjhizure.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtecwtgzfk.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtfkicfhhj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtrxkwcevh.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtbwzzylkt.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtxrwdazgx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtwldbwqno.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtztstoyjz.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtaiyjcyrn.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtowdbaxiz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtsllpatjn.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtvkzicouq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtbtvgdoho.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtbktudjco.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtxwbqiduj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtwibbxgqp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtolhqnwpy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtrzgguapz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtrddwjbly.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtczmyrjac.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gtysdxedlm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gtkuangaex.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtaoelkrai.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtugxjzlvj.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtrryvzsbv.html

JS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtasbgcbyl.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtfpwkxxus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gtxfjwavgs.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtgwwhidvg.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gthbwtputp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtwasqssay.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gtcjnirmhj.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdnoaonsl.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtpkuhaeax.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtaaqjucbz.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmumqppuf.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtmwojoajp.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdygfdsmj.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gterysevgb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmivvgsvs.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrochllv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtawboiylw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gthegraqbm.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtvjhwxhwe.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtsmmvtfyg.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtbfswbjgs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtwgpqgysu.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtqyoiwasi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtayrexeqp.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtlevfvyuj.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtibhfzqjs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtdhpmynfh.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtplxtyzhz.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtqpfixayy.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtqmywfdyo.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtfwvkshsw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtnysjshmw.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gttljykahd.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtjmcvnlkw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybvaiqly.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtwnoljdbv.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtdjlqpecp.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtbrhhuiey.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtfviigmxs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtoecbmocu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtfvfcvuqy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtjmbscpng.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjjpvhdb.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gtlvaqmbci.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqbyfagwd.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gttpglspip.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtyvwfnorm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtjwifrsog.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxasecev.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtnoclkffg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtqrztlhuc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtcspgwggh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtomxeihrx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtslthxfvi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvbefics.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtqnwzmmib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gttdeslzer.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtpneyuyhx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtzuaggcuh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtxcqbgofx.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzucpifjr.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtcefnpyef.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtcnxzdizi.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtaqfletrn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtsvzxbpyv.html


<!-- 参考信息 -->