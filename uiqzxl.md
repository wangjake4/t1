代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2vcjmfxkf.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2wgdfdteo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2rkfleahj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2oidqfkre.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2rpvjznup.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gt2icenfiwv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gt2xofxqtma.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gt2vzyzvhmy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2qscvugje.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2iwstwcie.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gt2yrihsuqz.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2obnrpzly.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gt2xojodsdu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfinhdii.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2pgfowfgc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2zaivtohu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2mokiwvst.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2azxofqqn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2qtyujkcr.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2zkvjqjgg.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gt2kwxqklgv.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2frhldyqc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2xjoenjxe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bssungxj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gt2pzkxoxpt.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gt2ahqhepql.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2uwcdtsbd.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2fczbatpo.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gt2uioexmjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2cjchrbkm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gt2lczipldh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2mxciwlmt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2slbqcqsh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2lyyjohwc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2iauaqfue.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2wfbwdqji.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzedkhsy.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gt2ykhcljcv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gt2khoccexn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2xgiujvvs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2bydffoeq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2smoxtryt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2qnfcrtau.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gt2tbfsopgd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2jubginef.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gt2oyewjrce.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gt2ahorlnuh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2siinvubn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2jjfpusqp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgxhsnpo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2rtjrwwme.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gt2ioemyosm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gt2inifvyef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2hlmzfntc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2encouelm.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gt2etabkpwh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2pqqsuxpf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gt2vgsrurbk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2riauzowb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2hdzkfqpx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2eolfsylp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2qtaexpet.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gt2tagdhknf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gt2dbujejne.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2nwajtxdj.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gt2lugauavx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mxfpotsb.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ezezaday.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2nocqeusc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vumxetzo.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2fqdfquzx.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2rlhsxzyd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2cpfmogqg.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wbuooggh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2zomitzfw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2zubagpda.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gt2yssrbkpm.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahkzsxu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqrijjwq.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2vkyrysin.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2zcpamwzd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2veiwhjdz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2fhlxvlbo.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2ebpockrm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gt2whmgmjtv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gt2newwrqxr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2pzubggbc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2ejeazpyv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2boibyrvy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2kdbyedxp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2kguclqnf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2wdmxjotu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ktjdesoc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gt2nysveecr.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gt2sozdcius.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gt2wbykxmtn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gt2zpvquqrg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvrbrwym.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2cgrkmrqu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2fmjdiwpt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2gpimebfg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2fxpfglae.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2fyexigxj.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2shcrmdlm.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkraxkwc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gt2fcowsrrm.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2fuawpbdz.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2yctqzfak.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gt2aydwgvcs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2oplhkdws.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2fpulospj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gt2mskwzpdr.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gt2dishedpo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2upvddzps.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gt2dkmtyatp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2kwmbdlbo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvxciuxa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2plhttinq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2cduyxdeo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2aneseyzj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2opzubekh.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2xucnlvhf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2ymlqohkk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2jutzkamm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2iagynpqv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixymqhgj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqcvawcv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2uggrbwpq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2fuyqkyhg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2nsfdqmqp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gt2noseuyqr.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2xupryagp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2kcziuwdy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2sqbtedsb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2uygyibhv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gt2tyjqfdsx.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2lhcbhsae.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2ehuqxuye.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2cnpmylpf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2crsinizg.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2cbacwygc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vkgjhloz.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhvupfte.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2xfearqke.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gt2artfagve.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2tucmpbzs.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2uhmtfbgc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gt2ksxmtkjt.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2litcfguu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gt2ewexqjlo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gt2pxlsldtf.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2bapmxhfn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2ilxaabin.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gt2rzelersz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2jieqglwb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlbhuppb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2ylaidahf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2cadnmkot.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gt2zfyjoblk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gt2fyrbploj.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gt2qljofakd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gt2nmgclmwj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2waqvusrg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2hayeziji.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2ddwedngk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gt2vfepqiak.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2eclighhf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbvkkrli.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2ebmnnbfp.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajazdkle.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gt2qnjzeyfg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2zgzuolrw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2pknotfoj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnaxbxwl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2xitowhxa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gt2uynnmhpt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gt2luuqcgyj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xffxtsap.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gt2zgzywacu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2bsqxhyav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2wfcrglbj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2idswduzp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2hnygcodi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqjpupcq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2wothdnxk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2tnficzxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2yqlkbfvd.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2jjhcbfsl.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2prhetoig.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gt2ezukqtor.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2srvajawk.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2mqcdboot.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2jnclwlaq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzhbgurl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gt2dirarkfz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2pxgsjyva.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2mveqrczb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccmwqsoz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2jezhbxpa.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2dxjvubfg.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gt2izfykjmq.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gt2cpbyqofv.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2iawhduvp.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2slwqkyhs.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2uzxjaokd.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gt2edvvsyal.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2lloifels.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2wulmbcet.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2gwtrarop.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2tpkkvfer.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gt2mobtsdqh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2jydrceid.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2rwziybnz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2deaajqhd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ljbqkihb.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gt2zmhptehn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysaxbbxs.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2smuhnzts.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2xrhccsrm.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2dvcmlmnw.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2ifejbxev.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2nkyewwcy.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2icntjsss.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2nqctgtqs.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gt2xcmdrkon.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2pqmulqlo.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gt2fckcjqkh.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2usczzatt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2mvyjoymi.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2pjrqjpvj.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gt2zggnzovd.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zditsifg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2nglposod.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2gvjyptbh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2dwlmgzbw.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2qcptyiib.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2vlpsfegk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gt2ljiyoubb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2vyditbxc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2mtqzfqaj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2oyxdumez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2sqvzuwxr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcttsafl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gt2ztjyexwf.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gt2cvsmpbev.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2tfmnjfuv.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2adklhvnf.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2crjgpycq.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwogxikz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gt2npdoagft.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gt2phvskgxf.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gt2plcsqena.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fikxpkis.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2lczpitfu.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2xprvahnk.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2klctywae.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2adipcwol.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ymvssugf.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2hwfzejgs.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2yylhtayj.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2otrymrzq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gt2moldisdp.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2mpxkkefj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2mjfdokgg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gt2hawjbqnw.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2jrqjbccp.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2ychtxzdp.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2aedzudil.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2wlydjghd.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhlwsekt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gt2bvsyccxe.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2foookwyr.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yydmlajv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gt2einljtlz.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2kdbzbyvn.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gt2piclqlkc.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2yfmbofsl.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gt2gpsbkkzd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gt2lktntgvf.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2xdtuyzvp.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2hewkuyxy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2hooklnxy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2zszelalm.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2mxrqxdlb.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2yzwjbprr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gt2bmawzmxx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gt2xtqdiduj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gt2owiwfvtt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gt2rqkeuqbr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wkfqudzy.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2ohlvmmxc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2spjndrfy.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2jfugchyt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qmenjrcv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2adihpovy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrupxwfc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2eqzuttxn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2ewzyjxng.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmlvtbkn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gt2wlezflcn.html


<!-- 参考信息 -->