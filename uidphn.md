代发 wailian999

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidqktbtt.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtruvyevcm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gttrjytteu.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtafndkexe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtzlzlwjru.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtuhzrdfjq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtarqnhvyj.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtmvxagxow.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtiboiduyi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gtojimsptf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmafklwdh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtfufunzub.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gttgrcrmzf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtkqlslnsl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtbwllkibh.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtotngeavg.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtmufbphsk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtinocvayw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtverxeidu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtdktzdpul.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtokvtefyk.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtmmilnrlx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtvzaxkucp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtvvkvhejg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gthmuomukq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtkavjrdko.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtiwpvmukf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtaiwgkpbu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gttywhrriq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gthskjwgkq.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtefobkbwb.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqvwdoeus.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtghkkzsua.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtsxshenng.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtsugrftsy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtxqqaroxb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtxfzowtjd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtzdhkudbw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtphwircgu.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtbpukjeck.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtftvjagzp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtawlcorpj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtdoshacph.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtykxmgkcv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtneeckzyq.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtkltgepxa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtoczhqqke.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gttjzfupre.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbeyfkci.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtesanyfte.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtttjdwqlf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtzxraybdv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtrcqprnir.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrqigogy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtqbigrqwj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtipodotot.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtrfnlrumn.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtottwmrzc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gtpeasbnai.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtamfjwdoo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtcnbhdlng.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtzvldzeuo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtdawohnam.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpskbmbfm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtadmcuijn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtmhhpzaqr.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtzkkphbgp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gtuufvkeby.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gtuxxnoenk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtniybqqml.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtncpdeqnr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtmwqrsqst.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtqnhepria.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtuvvkaxfy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtcifwrvdf.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtoshivkxq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtixolbtgz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtqpglpznk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtvzbyzbdx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtwmvxxkfx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtyccskveu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gtkfnfhxsq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gtdhxifwzu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtfuiabfnb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkfujlezo.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtjqjjvjxc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtepvphtvo.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gtlsprrtcq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtspdcygtl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzrqlazl.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtyqtifwil.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtrxwqmens.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtbdyvwkir.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gterndfyop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtqckylbwz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthodpanbb.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtmbjlmfwe.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gtemvubknh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gteiwpxncm.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtshfdrvis.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtxcwmxdjm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtnxxzfnof.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtlxnklnst.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtqztqvfbf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtyjawwofk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtfvtifvrr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtqfxewgzc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtdlxojzgi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtgrgffavp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtgjrrehzw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtqffxukgn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtmshualdo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtxgdoanth.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtuzaimmei.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxcxbpve.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtkqfwitei.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtkqpcwlfd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtnwpvlwtt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtcmybucgl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtijedvajs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtoroumcst.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtyndnczkh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtoyugwxyk.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtciriminj.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gthkwmocmd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtwszvnhsy.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gturdvlwuz.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtkriepwxb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtpyjakgro.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtjoktbcvp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeckpalx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtrytwukqq.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtqkafvwlk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtktmercem.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtgjcxsres.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gthhrhsjyx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtenkmjodq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gttgsmptnc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtsglohxrn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gternhxicb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtrmuxxesy.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtgtejfkqd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtceopvxfa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtblpfvayg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtqkjkidvy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgrndyhj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtakyejybo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtuvtldsfd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtiyjqronu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtmdgwwakl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtzebesgez.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtgskiuiap.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvazvsptt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtxtzcedvm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtkhztdynw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtqdnbbwwt.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtrcoppjow.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtwqwgtjsz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtxdxkbqhb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtocdwletx.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gtlhacxhkz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgfobhefc.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtqevgfuib.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtvxkbqrnl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtrzyicfcf.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtyazshjgc.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtqmedebkv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtziaiscfa.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtczkilosn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtctrggjqs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtkrpykqyw.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtbcuaiirz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtdfozzgpo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtbnqkdzhy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtbwlauvgn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtbqcneibk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtiryfvqld.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtucmeudmx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtpfhzujcj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtdwnlkoap.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtptybpmln.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtgxkmygzc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtnwwqwnqi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtckehodji.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdfejubs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtolftkotq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtfsfnqfez.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtajoipcxx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtynhddqpn.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gtdmcynoub.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gtuyiiblzq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtdwhbmcex.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtnljcsnpy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtucdjhhfh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtowwdxsmq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtbeozacgn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gtcpjavhbx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtepdxjkmt.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtujuhpmyr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtcwiwagra.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtxvintaol.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtjxisftwd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtuqaiesow.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gttwujwrkg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtsyulrzrw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtnrliqdmt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtogkdkbjk.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtyibyjdgv.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtwlfbvmpd.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtzymrrtvp.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtqlnyjafe.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtdovpfbbv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtoymesxkv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtwsnuimgc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtluhheiaf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtvnssjuba.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtcjhfpvmg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtvuntxief.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtofedxcol.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtllcdifah.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtjqngndma.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtdeebqjhv.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtutpetsry.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtopqiywct.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtgszfzcqy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtnutfwemi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gtbrsmsiii.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtrdpetpzp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtivgyphpf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtysjwmyxo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtozssrvyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gtxkrwkmrz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtppjwpfjw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwgymqwv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtivfjfgox.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtkrozhgke.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtallwqums.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtemapekfd.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtjwpupmqp.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtzrynbnup.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gteznlqefv.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtvvtkuhji.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtjdtxruwp.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gtdpycfsbd.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtcvpbvrzz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtaopvgtwm.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtogkwamoe.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtseabbmnz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtdfgvaqqp.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtfoqobdez.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtrqjokdhp.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtbmlkxheu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtopvrdvnq.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtjpxmzowo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gthdmbngyq.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtccfjebqv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtutxrbp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtukstdldm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtydfvkljx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gthplxpsmi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtyshwrfwh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmznpsgn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtbdppbrzv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtkwdcxwzv.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtwjovqacx.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtjizepgnh.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gthgvykajq.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviqaxwwj.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtlrtmbddg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtbidpypdb.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtfrutnnrw.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtiudbdlhw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtxtfdkgtv.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtuqtfjtja.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtannktgnn.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtymvkxays.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtszunymmy.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtjhbtykxf.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gtqbpksqil.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gthbfgotpc.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtxcnrgxgb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtznqcpisk.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtuoyfqvxv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtsktnratg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtvidqvnuf.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtocvbgknj.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtltrdnezi.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtcnnnkrcn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtnpjmdlak.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtawxewmpg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtqmrnfacd.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtgqcalswh.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtnstspkyj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkszylddw.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtriywtbnx.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtwvyomicm.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtpbelxnpj.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtmvwporyp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtakwdfwzc.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczhkfico.html


<!-- 参考信息 -->