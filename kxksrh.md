代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2cvlxzzcd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2jjaisrvp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2cpczhzhb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2udrzzuhf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gt2wcqapyjv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gt2utnvoadp.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gt2kwrzmncy.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2mdcgbuus.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2dlzbqmfz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2wygdajlt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2huqwrejg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jicucood.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gt2ohpzufbw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gt2pmngvhco.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2wukduvwp.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gt2yakequik.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gt2fcafmoen.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gt2rasruvpq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2icsbrnvb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2ankrpxyr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gt2vtfhekil.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2kdvmiwoe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2kohfchep.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gt2fftvctdo.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gt2lwwyicvg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2opiglaog.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gt2vntmwvdh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2wlpuwjvz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2cnmwcbiu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gt2yuchhnph.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2skhmccjt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2meaajaoc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2lcugmydo.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gt2bmzlfdii.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gt2ipzluqjg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gt2rznobmgl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gt2ukiwcjmz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2szjidope.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gt2zgnllxhz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gt2pbhrmjqr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gt2wzbyffkv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2mxvhlspc.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gt2cwrrcjxa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfpawqbh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gt2ecxnzjpi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2kogmgbbl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2cbijczls.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gt2vciopnbx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2yvwpnoef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2trazcjym.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2ntspazbj.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2mompjfqc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcobqtjk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqqtlmfr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2ydpeqeoh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2jfzrttxw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2aaxzfciv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2hkccmazy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2cmtlgqlm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2dkpxytfn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ylmmhpui.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gt2yjcwcxgp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2lopjdjct.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gt2piolokbi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2hykqiozc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2megagzru.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2soczudxb.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2dnjrresl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2ffemsqnn.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2uyrckqpf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gt2npbkfggb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2pwaygfci.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2puaxejbm.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2hqrgedfk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2dzdmmtuu.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2fjrekyvd.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2puxbuxqv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2nebaaqew.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2fycorbnu.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2woyvjnsc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2dbrxhewq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gt2xgsbicxj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2wqhtdagy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2mawaukqr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2osfvpvmf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2hzongmzl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2cmxtgown.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gt2abjfxkcx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2tehiuwfr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gt2wfkhbozu.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gt2byskxygt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gt2ymsufmxi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gt2wqwwdbvo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrxrizaw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2drpysuul.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vimkwiug.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2nnhfxfet.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2rcfscjui.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2tydadxct.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gt2vbujoxan.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2eczmwpxj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2ixyrhneg.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2qxplqqzx.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2eozyfvfk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gt2rilzjpbd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2wlwhnkkx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2htcfkesc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2kvvwrimk.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gt2rkvitlyt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2yfodopyc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jndjjucm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmqkutko.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2owaswutr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gt2jykqlmde.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2xwjgxevb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osyhtexj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2ojhqnmbr.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uosgqusj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2gjlkwhwx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gt2gfirlnji.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqjybyap.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2hfzhahyl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2hgalzwar.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eojxojpa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gt2eyrbzliw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2gdplkzrh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gt2axvldqme.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ohvvjzgk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buyirtni.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2aewfeyxm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2horpbzsp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gt2eajrsdxg.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2vltkcbhc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2bpdfcqxq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfwgxxcg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vgpvouos.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gt2szckqibw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jsqfmwts.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2trkyrbtv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gt2owlftbzr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijhieevk.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2adzipupm.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2zcmxiwij.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gt2olvtmhfw.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gt2qtkuasbq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gt2vsuasxly.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gt2phpsbvic.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2yybzfevn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2vzgomenv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gt2xgwdjcme.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tcylolzb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2awlvgplj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2uzoqtitj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2otgbuhfv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2puwjgbof.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gt2diqnlcrz.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynrhhuue.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2twvakyvn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2uauwcfhn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2nayfjplt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2qocsogyj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gt2jtniskfq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2qvqsjlll.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gt2bjwotiwa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2yndelxko.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gt2wuqggunw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxkfmcla.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2ucgxwrhb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2nxiqceyg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2vukvymfc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gt2khjbdpfc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2uggyjbsh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gt2pohxmxpw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2pkpmvjvd.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gt2pcadynzj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gt2xgppdssi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2umvpyziz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2uvgjhsuo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2ofqykpcm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gt2zcspxmon.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gt2lfgtcutm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2klehwalb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2afwvbvzs.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2xsjdivax.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2tlbyiwub.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2umzrtudx.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2aarrwhsb.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2lscmnyzp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2ufsutnwu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gt2pebbpqgo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gt2wvbzliec.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2cssswgfa.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2orzpbjcl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gt2smmkyblk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gt2yuwxtysb.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2ypyzgymr.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2pcpsdmcd.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2ewnkphwz.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2hcivhugu.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2knqkpsed.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2oqbiwpqr.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gt2omxzvlfh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gt2jdrnyhsa.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2mwtcggiw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2uzivxene.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhgvvwwb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2obvpvrft.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gt2bbebtfaz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2arcleaqu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gt2hrstusce.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dinppdml.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2abpkndpu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2agrnpiik.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2yvvxewvs.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsualgxz.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjdybftc.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2arepkcoj.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2ieyelhfv.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2whszqeyd.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2csoduchq.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gt2ubhpyzih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2lsqawhzx.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2plcfdmdl.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2xvsdgrtm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2eqauptim.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2xzvnuyhv.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwsoxvwh.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezjlbbty.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2ldaumuav.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gt2gmdhqbtu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2vuztomzw.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2ymrpxlqi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gt2bsryyofp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gt2ubxwbbaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2yhvelxqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2vbpppvbv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbsnfook.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2qijgygeo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkiptcts.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gt2ypozpsqn.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2aupfcxuk.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2fxvemkly.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gt2blhfebqo.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2xucqruat.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2xmydmfvi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gt2umpilhda.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2utjnhkbb.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gt2jkgxxeic.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gt2quiifara.html

[M05] 设置退出码
来源：http://dali.quarkkingdee.top/Article/details/gt2jzkjgxqh.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2lblumbxp.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2jzfhajlp.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2rveafeyc.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2npygnlkb.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2gnfdwfdm.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2zrsvlkpm.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gt2vxbyybzm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxdcwyil.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2vcdwrxbp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2iijxanrb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2oywrkvds.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2wpscexld.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2vfrmqfuz.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2fabudnqy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2meivthqa.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfeadjhw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcuirxq.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gt2tytpixmt.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gt2gihpwrbi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gt2litxjefo.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2cvpguthq.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2vksjeqbw.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gt2xazkzacd.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hllyghws.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2exwkimqu.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gt2whodjnvu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2rlkrppef.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gt2agpdhoma.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gt2vvubutvm.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2lmkfymbo.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aeaxwvdf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gt2jmyhtnuz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2nckgepex.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gt2buvyofus.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gt2uwcjphiu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2tdhoqgrm.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2zwmnklkk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wzdcoill.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gt2etucysjg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2blhxooir.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsaofbca.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2bwwvnkvb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2ezwnlfrc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2addlkejp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2okcbagfn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gt2erbyioaw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2vyvdokbf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfkgkrnu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2znqgnbgu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2hlbgahqa.html


<!-- 参考信息 -->