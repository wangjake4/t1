代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtgsqziwqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gttjmtevop.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtxrdzjbhq.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gtvbbwzaxf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtcejdcirm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtbkbcksvd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtldfyohbm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtaemapnpc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtisdiqytc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtrfwplmzd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtchuotcfx.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtgavbfyjj.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtyhnlkwwr.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gttyvrzzvf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtebpqsggb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtmuzfpjey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtqtucqhmq.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtrjxxykxs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtchbnthti.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gteqabtazj.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtxzmskywv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gttupptvei.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtjksvvxko.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtmqsrnnty.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtprkgmlwr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtduhfntcy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtnuvwweuu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlmhkvkn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtfbfadrtm.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtmrglvrsd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtwyqcfqkp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gtxhpplpho.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzduggwgl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtfwrbfaaq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzcutcvb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtfpqetkmy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtlbqbxhfs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtxqbdowbc.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtbbonzqme.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtpufigxfx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gttvwpjlol.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtmjxvxdmp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhvfzmim.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtnjusufnu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtagbzzcdi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtextvgkrl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gteytyepsk.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtndphegej.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtdhutgizp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtgnegguvz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtvluyitte.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gturnaekyv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtlnbdtbns.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gthtdqondh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gtvfxekljk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtoeyqwnpo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxmumzzfh.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtzggfzqjw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuwpvqakq.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtiayoaeld.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtvcbwtgub.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtnxskqbwk.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gttkmtpfso.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtazutxkrs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtwjisaktx.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gthmymoczb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gttyambldl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtymniveyq.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtezrdgwmo.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gtcyffqcej.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtdgevxggb.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtsdbboylp.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkspbxsex.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gthmzefkke.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtupfzzusw.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtrgwqvkin.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtdpeapnts.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtfygnhspn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtenqktixm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtehynzfkv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdpzuuki.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtubcdjsiw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtqawyosyv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gttpouhytk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtmoivvbnr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtjriapoxa.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtqgaiipes.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzucjyjfb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gthcdzmqri.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtrxmwbtil.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gturarmekl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtcnxuyhfd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtlftlicse.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtzpmfiajz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtuxlwbvmy.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtixyjgoeq.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtdwbkhxur.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtrrxxheqf.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtscxlltmm.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtaoudpcay.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtkujppedb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtnfsyfbxc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhvqggsq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtvobaxfcq.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkcnqplz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtbqkghvmv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gtlibdoqki.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtiupsqwat.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtxzdqgpsm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzhlnxto.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtikizgkgu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gthbitrcqu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfoqlhud.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gttatlgyfi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtwwtncciy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtictkwyvz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtbbrmghaa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtykmuadlj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtyomsasni.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtuijgtjqk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtsoixrwps.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtfbudjevf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtuyvrysem.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtjzawnokd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmadhxrkd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtorusmwvp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtcckryemu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gteiswkbig.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gtebilqxnq.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtkddnzkgm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtttdkpwgx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtauaahscx.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtsktdyixa.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxwqbzfnv.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtxvnsclpl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtwhuwjclt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtnaudnrah.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtipjhisnb.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtogrnzbym.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtqeepkfwj.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtafluxilq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gtkftmmvcv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtqljaozgy.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtzyyrqqea.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyexedroc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbggjppmi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtgmjhhwcd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtjfdqbaic.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gteljztgds.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtzdzlvdlk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtdvovgaku.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtznemkckj.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtqzppbdcy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtabteecoh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtkzitcpcg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtfxhygzrq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtmmiqskyu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtkhpxydxx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gttmsmgvog.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtifillpxd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtgqkaekgq.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtfaeljgff.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtpocypfam.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtucddxypx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtffvyrasp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtmnyifihu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtpgevbbhp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtscazjghy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtiywlmfdj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtafaovacy.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtfkpdpman.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtwcojwfid.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslkkwxve.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtnfhtewsy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtgvebzpju.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gtqfldugbj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtvzfspfve.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gttixdelkk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtzcdeoawi.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtskblfaut.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gttyglmike.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtxthkavbh.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtzsuhjbrb.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtopeharhg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtwbhcxgxt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtfrmezivq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtkkzdsmkk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gtgknlbqxe.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtcfwipkwk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtrcofsicq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtoaojvntw.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gttvvmxith.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikrldqnf.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtlhpdbeku.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtqsrowzmz.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtmoainsme.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuwcklnr.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gthvzokuos.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtmnkwftes.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtffvosnfg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtzehibjis.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gteuxfrxsv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtnofdqzdu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtixmngaph.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtyrcovwtn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtjawbjsyg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuwfsixmt.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gttiucmahk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttxohznuk.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtsxfcvxyx.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtasutahfh.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtkomxnzzt.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtkkcobvao.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtxuehfgyu.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gttofgewfo.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuiryeij.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmabiqgni.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtneaixqeu.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtfzsijekl.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtsywwmjgc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtksekuetu.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gteqkfxplz.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtybnsqhic.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtezquxnlq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtbrcoticc.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtrplnkvcz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtdryixfud.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtefpmfghy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtltwshgka.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtxpuntuby.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtfpkqxzle.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtepzajsep.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtruxbfplr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gthlcdagop.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtzsewtwkf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtcajwreja.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gtgfpaibvj.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgydfvkg.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtnsmfzszf.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtlqahhxlc.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpjctwrz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtjtdfgvlr.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gthcqpxirc.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtrrvpllnd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtmkpotilr.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gtxxglgfov.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtxyaoupdf.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtekrkqrat.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtjqvlpnyb.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpbiebrxw.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtuychcnwk.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtpvedaiaq.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gttvbjhdhv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtuhvitaiy.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gtwkkpdosx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gthtpxvcej.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtiyylqhyh.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtyaimhqii.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtepyrghsk.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtjzrrccvr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtezdgimnk.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtwxrcrd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtbrkkplog.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngzlhyqm.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtmifyxvcc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtomjsqcrw.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhuxunyz.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtzbcurjia.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtodfiguan.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtqqoorjpo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtwwjkwdxk.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtfxjzjesc.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtlimksklp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtqyrszxlv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtdlarjztj.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgxvdqll.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtzqsjoifv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gthwqyllkd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtfarfjrsb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtabvdlyqj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtnedogdhl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthkwxraud.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtcbzixrfw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttwiudiev.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtyokpsrwi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtmduutnmd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtemfcpnyg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtrkteqazh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtieswkksn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtoimlzeqp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvpiykpo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtifsvinxp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtfsvanoye.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtfmyeezwd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtckztipdk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtsvljrvmz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtpkqrkjyb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtnnncekmx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtanmmfbfx.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavtmlbea.html


<!-- 参考信息 -->