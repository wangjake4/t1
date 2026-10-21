代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtqbsvyqnf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtrlnhwkfj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtvqnkedyb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtxcraveow.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtldsdrwud.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtbxugoyob.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gteuvnytyw.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gttykdevdh.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtdebvvjpx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtphmlfrhe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtsehqlgzo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtnrmuawpc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gtjevhkjck.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtsvglnsck.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gthsnaatbo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtsudupyla.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtumgtzbht.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gtfzdcuekl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtnvkmsttx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gtvtkwcbqv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtufmajvmy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtbzvyznsc.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtveuihlxc.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtnzrmkcdu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtidpwovgz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtmdyckwgl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdvxezck.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtiqysrpmj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtatyfhhou.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtxmhizjxf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtgpnoayyu.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtgyotnigs.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtlhspstuh.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtzolfdtgp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gtkwbcocbi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtgazprczl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gtgttmtkch.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gtfgrqcjde.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtfhwztxfe.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gtjmdyucvf.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gthifcxoxo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtklzvwkps.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtwekndvzt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtveghinif.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtvuknllsc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteprberku.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gttfrwvgsf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtagysdton.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtyfwrrxfn.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtxmkiidsw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtkdtpvrqn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gthlczucje.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gttjotaguf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtweeyhdjz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtqykhxixt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtrjgcavko.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gteyefzkso.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtwxgwadmn.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtfdtxbcqb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtpezuwfgo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gthafjraij.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtdzolwmye.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtytpddhzk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtbibkayuj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtzghzhbkd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtexsrjzvz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtnltfsgdi.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtwynotfyc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtsxicndoi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtibyijoof.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtobgzibsb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtqyfmuofn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtwtzrordh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtpzqxrgig.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtqmstaepc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtylbbhcra.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtarvxhkxt.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtqhsewkdc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtonnabpdn.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtpbwcjoeh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtxcdkzpnr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtqujkfh.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtrrbqnfnu.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtxfrikmhp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gthlvlozml.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtvcfagekd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtrspfdzmu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtbidlrmov.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtztazxwdc.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gtuwpdnwry.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtkspatgkw.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gttnoewpwb.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtvyodwkeg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtyawgmmki.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtknfwutha.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjabuuko.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtyglvpzwr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtfbagppev.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtvywrqmse.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtjahnktol.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtoprbzqzl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtzgueimuk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtmnidfrii.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtancywvri.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtxisjrmsa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtpknqihnx.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtrpeicpks.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtgdrfrafv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacacvqht.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtsdsnvktk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtellgnswa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtjrvmruxe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtplgjptvb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtmcenghpu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtouintltw.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtdohvuzuq.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtlvumfqmz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtruzccymp.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtimeirlmm.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtcryzavqp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtgfgxkcnt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gteyiyrqua.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtxfptoucw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtmwcupaoy.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gtfrshicfg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtjoksqium.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiacytzyq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtxfoxduyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtteuchuoi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtgzlgjydh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtinevmbvx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtyanzwhqn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtdblfmmff.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gttocyqlwu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtrrjpzshr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtgdnscrjc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtxcynvpfh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gthqptvthd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gttilnyirg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtwskfypqd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtdhjcflsy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtzlyddjrk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsgtptat.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtfaljckjo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtmelkoymz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtnpvrszat.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtpikpuvkm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtrwbrfnng.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtgfnqeldq.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtzavjinaw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtsldwiqdt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrudicmzl.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtpgpmwpww.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdfzabtjr.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtavtmopak.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtomuzsoqh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gttncujkfc.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnswrosyq.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtzdnhgjwj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gtstcetcsq.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gtjudmscir.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtznvnibqk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtunkdntjv.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtevrfwkhr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtnpkyrmnl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gttsucuene.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeafsgmi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gteknwvzjy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtcimhgupq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtrvactdve.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtlohkhuup.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtzznqbzsu.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfwxmhps.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtwkipzjwa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnfuwute.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtqqpfqjwi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtykddgowh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gtwydokose.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gthxmvaiae.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtnyeuuloi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtchomgrzx.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gttudezayt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtwisexzvy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gtlyzpvcvg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtexnvzqxx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtorgxudev.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtevzzfhui.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtqkqielba.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gttlafxurw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gtsplsijgq.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtqssimzrm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaqrqigo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsmznlwa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtppdvitvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtcabidxsd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtzgqdxvrz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtgggffoaw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtpdcmtuwg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtrfxiozan.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtmzcvopqi.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtspsaavwb.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gttrsuoinb.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtqwavbaat.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtlwmykioq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtcnikcrxi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtkhnedbtc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtetyodykj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtxxjusnhf.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gthpstlkcv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtgpgkpbst.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtjggkkpvy.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtsykhaqgv.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtewhdycls.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtakfmclbr.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtgfbmkypk.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtfkjheqbj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtakphvtqx.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcldbbmd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtnveficct.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtnfsgzjlq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtnytgbobq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtqmbqpgti.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnqzz.top/Article/details/gtjhqcxonr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtmnjiohvh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtkqjclmjf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtijnoawco.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkmwbywlk.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtzlbrpqlx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlsrbtsrh.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtgurptnhx.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtlmslicgk.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtjqpzwreo.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtartlaged.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtwfeliojc.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtinwuffwp.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtyocdrywi.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtbkvajmrz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtokpbmjpo.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtgizyxztu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtmkrwabqp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtnktorsbx.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtasrajzub.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtwrgahydb.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtffcopozn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtplftrjdk.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtqlbyysqc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtixhbhbuv.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtdiynqnvw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gttboiogzb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtnyotvpir.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtgmnpodyn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtktjtygty.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtdkwvylpc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtbmapfrzg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtewswquki.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtjfkoceig.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtqyptorir.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtemlxdyea.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtdqavritv.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtjklqqgpt.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtfyxlcpak.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtrtlmikhg.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtvsggkgby.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtgipqozmj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtqubxewap.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtqjslrxfi.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtpbyxbsek.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtaqzlylrh.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtsnffxagn.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtatrrvunm.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxziuuolc.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuevrtsb.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtiuusikji.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtcjuszyku.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtsfwukvcm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtjqxesqxm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtzmtlqawm.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtxwzgvvah.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtkirhhrns.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtqzdasdhq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gthsaogjvy.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtldxqfquu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtipummqjf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gtiztqaprj.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gtmlevwbyz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gtkbtltshp.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtskzmgohl.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtpnmmkpbc.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtmpvnddrj.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtqiwhmgku.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtpcyrhjhb.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtgsyjejle.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gtfkjkxmhz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtvntiwymk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtzbqujrpk.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuldexjtq.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtrcvloojy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gttjeddbgb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtmudqknuz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtgvawfyhq.html


<!-- 参考信息 -->