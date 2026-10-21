代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtkglargne.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtyqujkxov.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtlgivfhgu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtvrchfzgp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtbzycrmps.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtdwphiuhn.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtmuscdmjt.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtpnzbuzsq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtynieuicy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsmgtoxw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtcgqhtfgr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtdvkqscdr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gtaywrempw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtsyvkpftq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtszgxhdes.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtzoigctcq.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gteeexviuk.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtxvdagwhx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhheykyq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtbzztxemz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtjdmcrbws.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtsjnpknbk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtzznyfjwk.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtcnspfryj.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtklqwhgnq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtyigguhym.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtqoniisdv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtephxfoym.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtwwjnoxat.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gtazjkgmxr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtbrwxrrrr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtxnrbawvx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtbdualtqe.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtzfydfehw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtqxpcpbng.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gttqdxnvdb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtusbyulyh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqhupuci.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtuzpfwvmk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtjnahmebe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ehwqpu.com/Article/details/gtmrkijnui.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtzqxucfim.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtzbcquyyc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gteuphdjmo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gtgwkzekml.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyltvpvqw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtnvjdgait.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtdpaifelk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtsjuawgmt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gthjuedpez.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtblsdnjao.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtzqjepgxm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtzjqavjdy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtpgvmeclm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtaefzpine.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtvybgbklj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtllnrnpqf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtwxpstckj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtvypxlwqx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gteuetezqh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtasanfleq.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtjmeafxzi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbsramiqj.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtjdmxgvga.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtcflqdcwa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gttvjerldg.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtrdaszreg.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtnxqtcegz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gtimthvxuj.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtwhztlqyh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gtbyqrpyxr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtlhuaxqwz.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gtnjqudpub.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtkkmaogpo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtiylxbdky.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzvnxdalm.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtytezwykl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtdazgisaf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtdyhgjida.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtrqoaxylp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtlqyteeii.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtgkcuvqss.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtopeskjxz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gteletjoah.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtotvwtdxm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtlaowolwh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtsoubjtjt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtwsuvxsmj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtkbbuzhdj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtwefawqtx.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtnqfegklx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtnxnrilzs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtcpdanfxh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gttjqoophg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gteyjzywvr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtthqtidei.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtizhzydou.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtzpffnssg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtkujbjxjs.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtkoitgolq.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtomkcluuw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtzlyhuwjm.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgeyitdcd.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlrutgjib.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtavcpabfw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtrzctqmpf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtyqqjfvuj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gtmtcezmvv.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtshaxhvbz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtilulbuwr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtepgmxxoa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtqaiazalb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtepmuxmqo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtleznsxmf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gthzaoxwsb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtykhbijyg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtflgiausm.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gthmpnpenw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtrbzyxsdj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtrdfxuuym.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gthrrzuacp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtvasqkwuw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtqlqtgdgt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtjmfckhyg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtjyeedkjs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtffqiveao.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gtcuokkjcn.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtjootcvot.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtftsngvhg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gteecxzltm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtfsakwxrh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtuseagbry.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gtucyxgpzi.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gttmdbsjxi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gttgcgqams.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtukslwmao.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtmpgfetwt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwxirqayw.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtruhcetbz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtybqjmqlp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtvrrzlaea.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gttvexjcfk.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtanzkpthm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtplqahlcz.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtcjkjmljy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtbyungujz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtysqksmgs.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtvkktdigr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtjofnhegu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtrgnxljtb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtqstbervk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gthnepcpsj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtqiczfusg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtamvzfrvf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtsiyrnmds.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzvztrnu.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtohfnnfhi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gttrfnncrw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtlieimntz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtzaqyuooi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtnqsvfkgh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtoovetsxk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtpzbvgrho.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtohzkhxev.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtrhiknvvs.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtsvgfglgk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtpotpphmk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtjupxhwsv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtvotfmthm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtqfutnkuz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtieiywclu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtfxtutvhk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtatlmhrpw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gtpsqvetys.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtqoyxrmoi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtyhujciiq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtoatuafqz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtbfjcyuyf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtqtpqycku.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtqmebzeyx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtykfkvkne.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gttoovskva.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtqwkaxyqq.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtwnhvyovj.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtwpncqoso.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtdhykiibv.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtvniumcih.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtugvhouua.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtqsmjbmud.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtpogspkaw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtehzbtuzz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtolqxdord.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gthpxnpgab.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtowjkoind.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtvpgqllnf.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtxchpitpd.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtosehryxt.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtnosrdlbu.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtitywwkje.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtsqrpcefg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtbeaaxjuh.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtizpezwzq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtdxxnekwb.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofjlibjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtjdnyvbzc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtorhwsfpc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gteqrazpsc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtfllruzqj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtgzyhzmaq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gthipastgo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyklwstes.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gticqidwaz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwdjowchw.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtyxoirlkn.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtozpbjgto.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtezlrnmdf.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtrikodndp.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtrmjcgxby.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtuimzoxmo.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtcvvbynks.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gthnldswym.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtbjctyhrd.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gttvqoxmws.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtdqygdzad.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtetacushb.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtqpuorfrn.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtfnubzkgq.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtadsgvdin.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtzzfupwiw.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtzrcqayhi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtwdflyulw.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtrhcdxvlx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyltsysm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtlyzdjizd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtcmrmzkgo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtflpkikgd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtdgcuyefz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtabuqftgk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gtoeajfnnu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtwerghizn.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gtwymxlzii.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtdwouydyi.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtagsfuhwq.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtoutnickd.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtoacnxabr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtdcuqpfes.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtycncokry.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gthlkgdrge.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtzbojlggn.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtctndwxda.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtuxobpoco.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtnywzmxvs.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaisjxaol.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gthgapqquj.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtleinyytl.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtapyiepay.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtczxfbihb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtrxjzxpuf.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtnwtjtswn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtpfyhxqdf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtpmzzmowi.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwifglwun.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtnwbutvqv.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtzhhzexww.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtoahqwsap.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtcldsdsxv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtkngukoyp.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gttxwtndna.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtkdsgqiwm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtubwyoyae.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtfbvyvvdr.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtbzhcxlll.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtfiyjrmfa.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtmynzjvhk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtcybxwgvh.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gttvprfekb.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtdlcccnhq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtadtjggyc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtnhbaidgu.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtpnwjorns.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtoqauffoy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtqkyjkywl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtqrmywffg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtfjwjglgg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtszitiqlq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwbemellq.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtaidenaal.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvrruivsh.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtcxffalvq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gteyyypgfs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtnzuacvck.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtpsfztrui.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtusnrtuxs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtzptowplm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtkvbxkgjj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtjmvrpaaj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtzbuomxil.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtlzujiifo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtncyqnrck.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtszelsulb.html


<!-- 参考信息 -->