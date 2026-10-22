代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2ektxkydt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieraejjp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2hxlcatth.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2xxhjpqfy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2fsoiwmrx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2qngexwhi.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gt2ickneyea.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2fnxmslvw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgxfszwq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2miolouct.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2gotufeky.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2jyhifmrv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gt2wunqpnmp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2qdktshqy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2ipdbtpnn.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gt2ypmccfot.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gt2ppapyrxm.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2rlohqwdx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2tgrhtkbe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2sgpjpsws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gt2ctbxhgng.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2rgyeqneu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2njfzhzme.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gt2emxqcciq.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsufocst.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2lodhiqka.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpacacvi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2nudprefa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gt2zwsllrro.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2qitwsfrr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2ckxjjtuj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2pzwcushg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2gcfzsejl.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gt2znexaaut.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gt2ntvdlapu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gt2kalawnut.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gt2hfwurlia.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjivnnsm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2wnhwzbpx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrbarcoh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2qdetycbe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gt2ykfrmcyp.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2kidfpofh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbkbuhee.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2ifdkstwp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2eujjyump.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2djatoude.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gt2zfgamjhp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gt2gujxbajd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2suumewhx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2oyglmpxa.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2taoqmzwt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2rfggjgib.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2fpacuodh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyreugyt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2xnlieaqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gt2weixhcog.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gt2uprnimeo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2khknemsd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2kmklniaf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2tfkdcqrn.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2dnxwdvpf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxhbirwr.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2escgoegs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2ytrdgwxp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2eftbhifw.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2dmehuhvt.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2mptadkip.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gt2vstcvakv.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2wgasfgio.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gt2vifjdhfn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gt2gmggksai.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gt2wjbsybyf.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rodtutek.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqnyrtcd.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ouhcpedi.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2vyuornhj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlzcuqpi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2vfidpyez.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2jifaqczi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2orirrogd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gt2aeaznedy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2zsruvyuk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ivxnrxoq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2dgvaanvt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2qyqnustt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wavxsmte.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2brriznap.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2utsyxmvm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gt2trlmxtih.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gt2kjlqhgga.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2utnnkocg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gt2hbkjhtmx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2jezpdmps.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2icdaqndb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2pcyowtyw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2upbsiyzc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbsmwuzm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2doruuoxw.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2emiylkbo.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2lbckqryt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gt2rqkdjvlf.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2admmjrlo.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2xaymjfec.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2xbimlust.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqglpfse.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gt2sbkyvnmg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gt2blspbkhc.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gt2kthruhck.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2hzethmte.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xipevdks.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2exsunpyb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2btoxobes.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2aubjgcud.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2jkxoelse.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2ckhvhbfd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avufcnum.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvyirfdw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2cuzsrdzo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gt2omhmxarl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2xvszxtbt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2iwafxleb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2kmftwbmp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2vyvgtfnk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2jmzntycm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2rycybajo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2tyigtpyx.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyqtgkjv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gt2ruhvdehj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2nchlrhwp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2hzqlmimf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2hzgyxokl.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gt2lknfddhq.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ilhpyqli.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2galwqeim.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugwmvbzg.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2ennakvfg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2gshsvdmm.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gt2vxraupxs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gt2zzfdbfvd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gt2eojxlhrh.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksundbzz.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2codgsact.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grjrkalg.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2xiovtlpa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gt2mzrecsdp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gt2yxsfuyhz.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2otghhfwh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2glcvgnfw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gt2qucenvpj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2saqfodir.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrpwfnfc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlqkwbyp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2lcmmfnuw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gt2hgvzqqii.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gt2dvsbmryq.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyfoqiqa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gt2ljddehff.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkvxxxul.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2jyzmfwhy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epulwvlv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2yyiotfuo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2bllycbzg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gt2uzroxxdb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2rhpfvhzw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyeqkur.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gt2xnelpxle.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2oygymgdy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2ibmgugmt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2wrirgdxe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2ttydleci.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2ywuperxw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2vxwpcknv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gt2wafejfag.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twbjspex.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2ecwpuoqm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqknraju.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2xpbnqabw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2pidnddsl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gt2qczkcchh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2xsebtrfi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2oydpczjh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gt2npzegqkl.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2xiueixbv.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2ofkukbnh.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gt2bxhdteeg.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2mnyuduvq.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2wxyhgrdv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2ccnhdwzc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2umdqfunc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gt2xsychqyl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2csoponex.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2kedhleed.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gt2vmnmaklv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2lnmjbfov.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2cthmuiac.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbirnzcc.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2atyjcuyc.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2ojgcpuoh.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gt2xtmxxbqp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2fhnbrozn.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2rffaictb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2dtsyqfxi.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gt2ifrzsrsc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2woftehsn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2adkvxork.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gt2ggxdwuzo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2punkfkrb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxzosqja.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gt2drsmcsgv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rovefybx.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2yxcdykpq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2icardigp.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2xgnglwyf.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2qubiqvqa.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gt2nfyicues.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkaxozps.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gt2hecoxymh.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pssluzgq.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjkbxjr.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2owvlwanb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2kooupoct.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gt2nlechjze.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxtgicio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2bmltcwoc.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2upjvkqxd.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2mhdlzzxa.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqetkokz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2uhpylhne.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2ghgfrebt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gt2unjyhdkp.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpyrsuag.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gt2xhfznjjl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2hmrqbtcw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2leqpvkwt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2sbofwhyz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gt2tfasulhy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2fodveiez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gt2djpvkbuh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gt2rtjsvzyx.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2qidtcxnv.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gt2zeebyemt.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gt2dvrqihkv.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2sacgmrja.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2jdqzomwc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2kzqewyik.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2ucxthqpn.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2bzwjqkyf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfhzweft.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbqmomnj.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2tochfbbn.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2pviiawdu.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2qhymnmbh.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2jejornxm.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2newwokpl.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2txqfoaha.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gt2okztiwxk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyzivinz.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2hsizzvhd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shpdqozj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gt2xsmuntiv.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghxxlopp.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2htyseqmi.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gt2shjcrpyq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2wenlwuet.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2sozolfqc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2impymrrc.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoblhsrc.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gt2hbkytfom.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2zhbcnlxw.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2anofgajc.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2btdvfydw.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrtghrrv.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2ozioumie.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gt2nnxszkgc.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2grqgrrro.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2owknuzpm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aozvqhkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gt2laeswkcv.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2qmafcwjv.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2xwpauekp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gt2qxkmsnig.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2traphvuu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gt2axkqldpi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2xuqgrpzl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uozygtss.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2btcfwkil.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvwjdvse.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gt2zoadoxfy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2lyyxpoea.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2fngdripq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2jevxfujw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2onkaulkz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2didbphqw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2fsadaybk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gt2fbhbmzzp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2ytavgsri.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmlcnqrk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2hqtjrgme.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gt2okwemlih.html


<!-- 参考信息 -->