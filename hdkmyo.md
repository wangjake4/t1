代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gthzdqqvim.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtvryvedlh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtjekxdvhp.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtqztkjpkm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtsividjlh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtmadhqifx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtriqpfqup.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtjjfobqez.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gtrzsyopmw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gtnpjefmfz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gthbuxgnzp.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuxghsmg.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtpnwbntud.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtyxwiijjm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtbqvskflr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgpnqxsm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtsmoazboa.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbyrkgfy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtpahyfklr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtgfygqksn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtgzkszgcy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtatkselph.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtjzvfriul.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtrmweazrr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtzlasnahe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gteqesihvz.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtvfecqqif.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtzvlqyxca.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjrzswkj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gthcyqsuhv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtymqultew.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtftgntcfx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gttvsgnmaf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtwntzffjy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtjsrmfcqk.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtsscnkfqg.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukcdfhjn.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtayysbtrm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtdvgtxckc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtrpynvuuy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gthmdtgpha.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtxnwudyqv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtpwppyimf.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtpqxviyls.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtvwzwoiuw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtoypuftsn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtmpqvfgwc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtufwnpqbl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtugmqwqnz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gtewxrmmmq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtcrdilgwa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtcssxolqy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtqnyypfhe.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtwmjenhrj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtkdzlrabx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtwajebksv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtdzsybdvi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtkadqnhip.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtnenzpxsk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtfnkeiqrz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtuahmpeix.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtmqeeptjh.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gttbjbbwpj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtshvrjkyq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtztagvvnl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtikgpttcy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtcrnvongv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguqkbrwj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtylbjonwa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsxtnkpt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtmomsscjb.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtdcmmsqlv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtxnbzyqdf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtdhhdddbi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gthxpawaxw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtyasrzbhd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqafxowwe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gthwzjqyaw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gtotpnpbdt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtqftfpstd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsnhfbqen.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtutkrehqq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfnpkeigb.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtjraytrvo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtmkbehjxm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gthbwqyiyu.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtymxqcuis.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwzfdoaml.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtziulniig.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxlgzjxap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtwywqaixh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtmkfxoycx.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtmvkzatgi.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gtwghdplpc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtcybhhrtj.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtsnhmcrvj.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtsuqyblks.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgksyqlr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gttgtpojvj.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtyswzfuof.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtlslqsltm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtyxxezmaf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtrkaowsgj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtjlhyhnfy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtbeihejiu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtbhqamwvd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtrkohjfae.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtomkbcnsl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtafzyqtvj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gtgutcbmiw.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtprbhwedp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gtjpoavoua.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtusujsnos.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtdoaefyxa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtjjtizktx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtubxuimpa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtuhjaurbl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtxxohrxak.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtlvyclyhq.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtbjdcqhxr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtuirrjdti.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtfnpkjmev.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtcpdtxppb.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtggsvvfiw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gthuforzug.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtmzgynhsa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gthwuzpjsk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtnsukyyrd.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtoogjowfy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gtsdrgadpy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnrghrlq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtntnyloec.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtspgdyllp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtatdtebcq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtxqparkwj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtuguwitkz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtsteiboyv.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtruaqbxpk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtbqivbbwn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gtrpnxggch.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtqxcdlrqq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtckqvsnmt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtsmivomrw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gthbvqzwwj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtwbidzlun.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtlahsoewz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtdmrafqdx.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtrmtjijgq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtstdfgawl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtdarefgas.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtnghzdbdm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtnofddoug.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtftaizlpa.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtfaczrqdg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtucebnsnb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttxbbfwff.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gtontablwb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnoysdnjj.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtpqrdvbaz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoviiuvxw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtvpsjqysv.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtvtjzffti.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpvjbpae.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtutrwrjac.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtjdgdaqiu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtddhxcrug.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtfgnvysfw.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtocrynkdc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtklplayxt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskqqfkpo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtkgxllvqr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtelcgtpkk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtpcpnxobi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtsrlmpmct.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gthylxqppg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gtxqfnklsb.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gtwstahthl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtqthykeif.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtvbjppbvt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtmarxfprt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtkvanuuad.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbigrfcn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtcmzpuoxn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtoulciloa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtpyrwsdhy.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtqhytwkfz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtpbwaytgt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtltpfqpix.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtsvizmtjp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gthdqnjsve.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gttgvxfqxw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhiqcauc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtrhebuujl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtffsvhtgx.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtgniloyxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gthpzogjif.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtfzxbgtqc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtzibfkvvs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gthtjovvmg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtcqgmmdwy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxniwiwp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtebbxvyda.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtupfmovkl.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtmulsafdo.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtzkagevlu.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtonrqxkra.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtfhfluuqa.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtthnbusjh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtsdjtyemo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtsaqbgdjt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtvfjuldbo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtngogtptq.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtftylarmj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtakjvtsqe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtiidgpjaw.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtvychebxr.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtpegcuilg.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gtvfroezge.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtowvgixwe.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtjxekaiyr.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtvidcqmas.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtwmicpqjb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtwxuxbfwl.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtgtemqvsm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtcjjdzeli.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtepqvpqxz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtdglosxuj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtdbgjmtos.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtftlvrsww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtuhrqeqkz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuutymlbt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtremkkzjn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxojonbvb.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtlruuijzp.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtefucrgxj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtrqwdaure.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtmfjeczhj.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtcdqngjwl.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtwtybxbna.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gtvmpbvllp.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gtohuywuyx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtutsbqiub.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtaqmxlmji.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtmxkzhcxm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtcdadrdvp.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtlhabbszd.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtfcjdlurt.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gttgfuexac.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtekodvpab.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtwrxlceyj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtdmobhrsr.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gttqocvskn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtivxfvjit.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gttezkxfss.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtvoimtddr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gturshbrof.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtajonwpww.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtdvelyhbp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtudtzdjaa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtaaqoatsv.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtoedhbjoe.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtmqqjtpws.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtifxarlra.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtoianbklg.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtgzxrwxyr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtqqhuhvsl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtaljgxrrv.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtlsgxehcn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtlettzcgo.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtqwtvmnim.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtbowpiquk.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtvsgudfhf.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtyqdcmkhp.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtawufznsm.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtathbemlg.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtaxhazzzj.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtcwluonex.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtwsswhvsw.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtbcnvopbx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtfxyhwqxb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgjjevkj.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtaoailnxg.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtditeotpm.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtiibophwr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtevwnuoqr.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtepvusxua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtfonpqmid.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtolrvpdaj.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtqifpppwi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtzdowdfzp.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtdjymqnpx.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtxmwzmkel.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtiwahftpc.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooxnokep.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gtysrzbpby.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqqqldgd.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gthxyuupeu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtsmcyzkii.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtagqvswxi.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtaljcxbdr.html


<!-- 参考信息 -->