代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtiigwuupp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtatgkxinz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtlfykjabz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtufvxxzgp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtsddsnvmk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtbxykucuv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gthtpaluwh.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtuiixastx.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtftcvpkxl.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtlvwtsfqb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcrurqvk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtthffickf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtkdsgibsq.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtqfcsdczm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtqqfmobuq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gttgsobtau.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gtopxyehlj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtqjadrucy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyshemff.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gttiqljdxn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtyeugourf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtxupocuwi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtawsxaopq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gteortuqoj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtmkrowvsy.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtdeecdnlt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gthianyjcx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtrsvlcmcg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtoaylfugf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtxmgxplec.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gtygcdklsb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtbmyhnsic.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtwcbwakwp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtmvujesxr.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtonyhpgbd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtvojgsrgt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtwqmqxeyb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtrpsesynx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtvagtgqxh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gtbcqahdig.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtufxqukyp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtzmusgnoo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyrqwxuj.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtfegnrgdg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtpypsqfgq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmjzyisg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtwpqdltzr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtxcydiunb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtzcdzldie.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtykbdrayj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtkelienqn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gtzjgneebp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthzizxoef.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtoajkatxp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsgrardib.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtlkrchfgi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxufifog.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gteoeipnsd.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtfqslthbb.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtwdurfouq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtsoltdmxu.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtqbuxvhtj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtdnmsitrh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtgsuouhgv.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gttviifugs.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuxlsdgfn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtuavnjjkk.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtojbqosbj.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtvoalbxuu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtiyjuoyig.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjprymxb.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtsvaencio.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gttddjallp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtqrxsgrtr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtqriigqtm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtpshlpigr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtimzwrhpj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtsllzpbpm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtshpttbji.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtiglaiwja.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtulgfetqi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gtrclvwxee.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtkcbfjtzx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtwwovlulw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gthjwhlanr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtlpwragxk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtjqfbknec.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqdmpbcz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtzfpxpnte.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtqpjihaig.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtjrrciwyj.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gtsiwcuagv.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtsgtvgrmh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaphavic.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtmasasxdz.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtmfumjpyy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gtajmendsf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtgqwpilss.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtkokphbiu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gterdzqdnk.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtodpehcew.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtjloafpnp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gteqehubmd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtmvhttfap.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtjiaqslwm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtarqvwddy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtkywmccic.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpjtmppw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtizstrzem.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtyappyfnu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauvdhysp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtkcxvpgau.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtmiglefzw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtidstcrmc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtealexetr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtxdarmccl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtgrxmzxvr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtjrneztaf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtunpuvfjp.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtppjtfdyv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtdbmrhvbk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtertkflcy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtvrkufiaz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtvlojuaeh.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtadwxtfzo.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtnimsmymn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrevzolh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcnnkzkxk.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtusiuurns.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaxsrphgh.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtreuzdkkq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtjkcmekpf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtrzdkbftw.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gthtehpeiw.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtwrnpiryw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtmtyioatk.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtrakxwvvu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gtgruqbfmx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gthpgcalpy.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtechtewcd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtqiegtyrq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gtpbqwfabp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtojhjgwaz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtspwdnemb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtjeqacjyb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gtyeulbaol.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtrdvmgvmb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtyfrulueu.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtnewjbifa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gtiizpljem.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtdcjvdaiu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gthmlbmdlr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtzcigoqtw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gtidvxyrrz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtunhjrptj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gthcdpqyyi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtaxlvexts.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gttspzrdqy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtezpihzhj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gtxfdnitcn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtkwsspfgm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtharzwbov.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtawtujvah.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtrzbidyea.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtkelgcfgt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtoqnoaccb.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtlugfygmr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gttyixfvql.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtrtkvkvme.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtixeylwle.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtwtqbbpay.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtzzrolocl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtzoznpzww.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtijzkohzi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtuuvkkxrn.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtowajfaxu.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtrxdmabyp.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtlxxrbmue.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtwhuyrnob.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtgbnrwlky.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtusrjtnfv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtcmfnneqj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtefnpurgz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtpqzuvavf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtuafzckid.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtimjlackv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtapaxhqat.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtmhvcgbcn.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtqkchjshs.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtsqzzysig.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtlpnifecy.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtjgwbwpbv.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtedhwjval.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtwoukvzgb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtlyjvqwyz.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtlytnrgqy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtkxxyypha.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhhwybux.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtlwivnrjs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gthwkzqnbv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtxlxswixn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtbcgcthxa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlminsudr.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gtvivnlumj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlgzlmbuy.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhwfzvor.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtzivrjssb.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtdnoylhus.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtukuljupc.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtdvjyzdqg.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtvmobleeu.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtlkkzhctu.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtmyjetgny.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtmgiqfhak.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtqdoosbca.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gttpbjlthq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtfpbnpjjq.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gttyvexjkb.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtxjrnhsbk.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtwotofqkd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtiuxrstnt.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtvabmqvdj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtsvzrjpbl.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gttotvmqkm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtejndyxhc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtfohargxr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtggmqzrbt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtmtsbfpim.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtnhbmngay.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtwsowspnk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtnbqgdviq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtmclgalmw.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtvkxadzex.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtjyhgitfr.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gtqzitsvax.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtmkmkgjbw.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtqrqtjdzt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtphsewhsq.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtrechiqny.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtcfjopyzo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gtaxmxavme.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtprkhyjbr.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtxzazvhru.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtnpiwdstw.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkuswhyqr.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtavsdgxsx.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtxjjmdljp.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtityvswex.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtomsdhfwg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtqdllzect.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtkxsskliq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gttlxdjwew.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtkxhftlge.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtdkgocghv.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gthmrnzmcu.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtpbdejfad.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gthemouwqf.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtxcstwddq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtknkxhnso.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gtlxwuccrb.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtbmvlhoac.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gtmvrkljfm.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtbiccqoiv.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtqimoiebu.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtgduxyhcr.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtwczzaikc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtxeqqeffe.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtrotmwdfy.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtjjlculql.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbukcrlcw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gtbjlmeiqx.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtfnbywmmu.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjogqbexy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwcxvuwm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtrmqhflne.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtdsvwpvde.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtdchukrjo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtghgfffsp.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtsdeveiog.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzjmfdxjb.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtilxszicc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtqqmofatx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gttgefiynd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtwfogfcoz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtwlorlbmw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtcbvwqcch.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtermfkhtu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtbcotusmz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtwpizngrn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtwcwxmuzd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtxdgckwbw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtnisklrqr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtqeigeofz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtsrlhnrcp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtvgcihkvb.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtnvqoctme.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtbmtaomtn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtaljfaeqw.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtthjlkamu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gtllhtaepm.html


<!-- 参考信息 -->