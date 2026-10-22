代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2qdsuipzg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgoopku.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2nglizrcu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gt2zgharlfm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2sdcrlbql.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2dllxxpte.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwvgzqmc.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2tooyynpa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2rypgooai.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2spjefuuk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2lszavroi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2uaibrikj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gt2gvvbznhh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gt2zrpqpxqp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2lhrzoprd.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gt2pwxcgvig.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqnazzlr.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gt2iczxaobp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gt2yopehhgf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2wvykejcn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2zpmmcylb.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxbmsoku.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gt2rxcexudg.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gt2ssjnssqy.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2zunydpki.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2dztzzozt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2hhkyrbpv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2noxhtydb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2kwnjjzty.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gt2uovvcjfi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gt2detbmjsz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2wdfzvlhu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2berzdjcr.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gt2wmnlmayn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2fbspaaug.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gt2vtrbkvgg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osgjgrog.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwrtvcqn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2xzjvbxes.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2odpjhlon.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gt2vlikdsct.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2cikkmlfp.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gt2rsirfuck.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gt2xldhwdul.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2kzaamqzh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksyzofko.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2drhwuxhe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gt2kumbdagy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2xywntatu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2siobgrhd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gt2jelougxt.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gt2vxmmuhgi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2ytlsxpmu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2xcauprvk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qenfzykg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2tsqvitue.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2glffeere.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2zqvpsybh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2fatmvwpm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2diwbnzkt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrdwtpra.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gt2lcywwjeq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xvjbhuya.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gt2oiidaqky.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2qhqipsgu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2olaxgkze.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2kridrdxe.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ixfqcbvg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gt2jsbgfsbx.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2udpfpiqm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gt2uffjdvda.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2umniwjgo.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2litywztz.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2qbwrtshp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2ijoqkond.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2naohodgj.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ijbpllbf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzbujani.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmiiraap.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2wvzzuvfu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2gyxtmzux.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gt2wyrcfiln.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2erccneeh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2hxxivbvw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iafogvah.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2tphmkjwy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2cbdciieu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gt2dyznmtwd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2etskptox.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gt2xcwhhqac.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gt2tboagvgc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2gvvpxxaz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gt2yxdcyhlz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2ywcodfbp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzjnaguz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vluhwypt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2hoxhycvh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2gpbchdow.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmjlzzne.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gt2ergsetxl.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gt2fwlrnuzm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2smmcewtu.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2nrqkaony.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ddcqasva.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2lkadpjvc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gt2mlpfedme.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2sdfpobpt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2vupfwrdj.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajollgyl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2njhufwbk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2xfidxltx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2gqplpvif.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfvszcsm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2eherxxmu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymatyien.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2mxxsewwd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2bilfmiyd.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gt2uzohbrld.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2vskrevod.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2zjbwvrom.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2sncnxlak.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2chghlcdz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2lhubxyrc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gt2fmkrrfmr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gt2mcndyewh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2wwkfzadw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gt2nhvawapz.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2udesglpr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gt2anyjmoxc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2ubvbviba.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2olveahti.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfbcqawe.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2cytdrrxg.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulrycgja.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2nubvxixn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2uggtsmgy.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khluzayr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bcmlvtqx.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gt2ntrpbwuw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2vdftfzck.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gt2fhrtwcue.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdejwsyj.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2dqylrgan.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gt2kpyiggxx.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgarwmzc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gt2umejktca.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2ufkayngd.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2cmieeuad.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2xbcjdacd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmzyjdvf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2nxotlvln.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2kgphodmz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgwsrlvf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gt2ptwkvixm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2jvkrtita.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2dcmuyrua.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gt2dehjuyxq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gt2akprmgnl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2apuoetem.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2nswgxfec.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2izeqfngl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajhpvahx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2ifwzecnr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gt2ooacgbpp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2hokgqtny.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gt2husvcapu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gt2dnlinjff.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2vkcuiywi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2rnrabeiz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2isgqswxx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2cpoxfvlm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2echcbbso.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gt2ahisqrqm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gt2fhowrfig.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2mxlsclod.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2ukejblgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2uiutfkxa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2gvkmqafi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2huoabgmj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gt2haijpphi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gt2nnyeutis.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2svvmwjdq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2lufvgpbi.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2zeullzzv.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2ehahdvrh.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gt2hjuiliji.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2izjfigrm.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2sldvemcu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2hhsipgqe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gt2yxsvapdw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2vvldepzp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2smjcpspf.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2osizpwju.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haztpagr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2wpfasbha.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2ctiwksip.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2pntzcmtv.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2kheaqhmo.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2ykflgetr.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnlevovn.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2sobadvzi.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2xswblwhj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2edmqtzgx.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2nshqmggg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2rjhhaljg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2jrtmywah.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gt2attkghga.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnlzmaei.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2djxzcknu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2achpzdoy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vgxynbyq.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gt2ryenogcg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2idjkhinr.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2yaxtqdcg.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gt2vdairkqk.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2kouplydn.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdbevcdp.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccyligqc.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2ntsykqnp.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gt2qabbftag.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gt2jfhhogpv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2ubhwsqfr.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2mdbpfuzd.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gt2bwrtrsrw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2ixolzbly.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2vfkoslgh.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ecaekjfu.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnpspqwo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2slbkxhtk.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gt2szkugdjq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2uecedljn.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gt2inbitmwy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gt2itqkybiz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svccdzhw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2rswcksnr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2kvaaxftc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxueyksr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqkyghpx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2gvyowftk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeqjdzpl.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2gunwwwya.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2mngucyur.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gt2nyujwfla.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2qlzebnju.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2riybowbi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2uivueylx.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gt2ptaphuqb.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gt2iirqxnha.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gt2almzhriz.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gt2tvgadbkc.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2zrqsnays.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gt2okfwnvap.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2syazsvbj.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2sixszwri.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2cetxmmyo.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2odvqimwt.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2ygdcsddr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gt2chfjktvd.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmwhqjlb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2aztamxja.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gt2niczmrcd.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2plkmlyen.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2wjijgsxe.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2qnsyxzvj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2bpyyjsss.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2ygdjoeer.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2tayccduj.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2gflahhun.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2gkbmxxol.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2wtwzonlx.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2ywsdxcxa.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2uarlzbpt.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2qkvxqzez.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2ynalvyuh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2qduscgci.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2ppwznxab.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gt2oezebtem.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2lmdytxbb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gt2spbdyutd.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2xuokueto.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2vuegygoo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2iugmrfuu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gt2xpqbmwfo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gt2udheyirn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kftdbegn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qzcmodfz.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gt2fkmlbfwy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mejaigto.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2jbmbhdht.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2ngpwoigk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gt2hbyvynqa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2ysocnqem.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2elnvdknu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2iauaxqyg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2epkhsofv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gt2vjmhgvnk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2uwezjmuz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gt2ataclnzy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2rphflogq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2daeotxzb.html


<!-- 参考信息 -->