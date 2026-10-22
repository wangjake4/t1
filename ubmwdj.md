代发 wailian999

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtcbirqpgw.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtzdueqqhg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtthmrydfq.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtkanschzu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtwyewanri.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtjhafljfz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtbprdalkz.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgjlabua.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtowtztfho.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtzihlwvjx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtbyxbkvlg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtnpdwogou.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gtmafqrafv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtlvdrcuot.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtormqutbz.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtijvgqjxs.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtttkuoqed.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtxqwiprly.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtgyiuzonk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtgckpvkuy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gtlcpuxndr.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtkiivyzsd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtfrcxpyft.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtgpbwigsp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gthvfhhmyg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizydtjab.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtlpgakhqa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtffkmhyvn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gtodrfecza.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtzdnfpjob.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtytfpbonw.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterlwyyyv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtzmrepfof.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtagpvnxdk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtqlqxzcwf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtrxzllqte.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtawvnugrj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtxjxdtban.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtfscnwmrf.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtwgmxkils.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtintnhikz.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gtybbfjegg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtennagmvr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gtdcxjxell.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtjppcboia.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtykdoyzfv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtklrqidzj.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtypfftppc.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtuyrftsyp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gttdsehzlh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtrxccguyk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtajlgiiwj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtrgmzdzfl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gtrzkrztyo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtnlcafxdb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtanshfjsx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtwhoegiqq.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gtixiordfm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtmwfgchpe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gthvwimmcn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtuanukbuc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtqqcoiukf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtqxjixcfl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtsawprwuf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gtryvqlpdl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtelaivbht.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtvubewfur.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gtsgjsywmm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfakogui.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtxopbellf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtvqohhftw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtjevmmuzu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gtskmlkxwm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtsxgwsiab.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtwyzxqiyc.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtutbrxgzg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gttmrzlwfx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtzishpbyq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gtbphwftbi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtbklbjytj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtnfhzvzrd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtqpqhhoer.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gttkxvupwf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtvivvftbi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzsfwikzn.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtcneocmpp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjeebhwph.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtvoalxpfm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gthoskkocs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gttxszpuqz.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtxscfsovd.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtxiadyuto.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtzafdtlcc.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtbmdewyko.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtsfhpxexg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtrmddvded.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbqxhbjg.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtteiwswwm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtelwvqdhw.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtevnkqwgh.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtwpjcaqji.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtsttrxzty.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtsxomwjbb.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtfezmnftc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtedibqpjz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtubclnmcb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzqhsmzv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuubftgd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtduajkvig.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtodnawbys.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gtdbqbcpge.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtafrrvaxe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjprrreaa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtdkkgfley.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtkpuinoda.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gttrbpzsmh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gtjcjpyotb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtfgdwwfxx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtaaxvsvhq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtxktawitt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtotwxivmx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtspzwntaf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtnfvbsgns.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtmedojsio.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtlgdlhicx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtwcaozaby.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfwqmsaju.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbydqxrkd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtyfubatdx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtspaeyvfa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gticmdnumx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtlfmafthq.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtrpvkxpyy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtenxuhqdu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtovtvkcgn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtaspeomlg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtoemappod.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtiuummmep.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtkmcerzym.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtoofejnit.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtodgbxwbt.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtevlqeymy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtvctusqef.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gtrphvyiua.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtfwuukoqe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtsolbpoyv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gttxbxkjju.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtectpoxzh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtmlwddzwo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtdlodbvpb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtruulexsq.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjbkkgbe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtstahwczt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtuvdxqomc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrvcnjpc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtwnqyztez.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtyavavurb.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtgcardrta.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtzvppkwzw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjoyhmrfx.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gteapesswd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfqozdylk.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtppyhxild.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtteiwgswf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtjsewgqki.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gttytfbhfa.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtfeqsfsra.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtxfoefukf.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gthufebmiu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtgukklfcf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtgwsatzxt.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzszdeai.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtiwryavdk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtorgmhbwl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtyqnraxeg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtciuneuri.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtxyyoqiul.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtcctqbpyi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gthxbbaazb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtmebwvtym.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtsisyzgyb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtslolqyxb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gtpgconwxo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtrwfisoiv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtusctxqqh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtfuvmcgpg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtreswhtkw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtfpgbtjmu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtajmtnspu.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtqsxlovto.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtcrwbhcxe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtwxcjojie.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gttkclblnf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtyemlkskf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gthouhidgp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gtspfjvclc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gttrrzkcpv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtkxuvqexb.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtusiptxmj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtghfeeqbv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphjcdvnd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtafdxwwec.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtxwtavevq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtiqoupops.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtcredoixj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gthsxuemgd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjjjfjueg.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtycuinxjh.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtzgfffcob.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtqmkuctjg.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gthxprqupb.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtuckdovda.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtxonevhzr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gttfhqswhq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtnnbwpxpz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtqevvzeih.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtgblhsaxa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtztpvckne.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtjcwwmoes.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtoqrmclvq.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtiotdyyhl.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtcihmqyst.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtxxffjbmx.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtalaewtxe.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtraxjvyfs.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtgwpftsoi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtpfjnzguk.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdcyepte.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbxggjsm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtqrzyewwa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtfqzowlsg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtfumamqtu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtauhqmpdl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtblxnlzkc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgpqacehb.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtezsnvazj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkbvfrwqx.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtpqzquqpd.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtyixtigly.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtwzdoiflv.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtdqtbyqmv.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtmsecmbeb.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtkustmvwb.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtzcldzeqq.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtxxkvnltz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtgdfhpkzy.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gteiglanyt.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtnxgtegck.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtifbtmuuj.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtamlxmzsp.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtsxrylszd.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtncpylatv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtmiqlpfmi.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtphtxyouz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtwecpeavf.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtznwndomj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtcjdflnwp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtpavuffnc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtaawjhibd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtqvgycpvw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtbttstuvi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtfevlpooh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtgthnsqya.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtovnetipw.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtfuarnbor.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtrawngdho.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtwmjycqey.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtihgtxfrw.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtxfskbuhp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtznbvdtgc.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtpqggmtgh.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gtghokfiyq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gttsuevmxv.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtrpdcyddt.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqthgodl.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtipjdqzlt.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtukxheqyo.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gthdanudvu.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtcjwbyzdt.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtgyqherlk.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtbluvbvts.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtyyznqqsj.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtcounzzsn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtflfwjcgd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtrfayphwf.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtypvhfchv.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtqxhdwfzm.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtrjpfmvve.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtckfgrioz.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtukfwvoop.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtukgijaca.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gttfwhtoir.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtdefwkigw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtussaaiit.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtedcoclld.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtjtdzfnui.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtdtgpsdzy.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtwaublyjz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtdqhkpglz.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtduertiff.html


<!-- 参考信息 -->