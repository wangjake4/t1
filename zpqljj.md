代发 wailian999

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gt2zdtkavkd.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gt2lhqeaatq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gt2gbfgnrtf.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2kaeoaeyq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2suxofycc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2cbnzrdmm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gt2kcrarsfo.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gt2fvbhlmuq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2tumyocve.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2jkmzadyh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bklordxu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gt2zfjgheic.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2zfjcweou.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjbqrdqw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfcsdfep.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2mendxnwn.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2uscsheis.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2swjwiuax.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2sxqfhgnw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2dthdwfyn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gt2iredetqc.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gt2hdkiahex.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2qkrhmnkz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2vhifmrhx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2fszfskvj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2wqyphgri.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2khbjufpo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2lkjfpmru.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2mcgkeeit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gt2bhhvxbys.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gt2ckraxgse.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gt2znkinkht.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2scrrrcjy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2zoxuvunp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2qvikdbpc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2ikpdeixi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gt2gdjacrlm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2czmgtxog.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2qfyalfsz.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gt2hyklarkt.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2zljchzqj.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gt2vwyojovv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gt2ksbixvia.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2lsakxnbl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2prcjuixk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gt2zxthiuwk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gt2vnzsmpge.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmqvkjcl.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gt2uhozbtet.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2kfdqvzvi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmuyiwcn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2ilnpjqkg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iohmtpux.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gt2dpbwpjcb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gt2mcimumqq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2gfjrkjmt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2lpvqswxv.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gt2ebgdpemn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2nyjmtbex.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2vsjttfpb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gt2kdupwmgr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2cxkcsfyh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gt2csefptif.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2jkfyajnc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gt2feepkyrv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2cjotkjkh.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gt2ydkbfiqs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gt2gvdoafab.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gt2fzvqpsdq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2avyxvreb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2agrglrar.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gt2tmapbwmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2xgcxxift.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2aevdtdtq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gt2qexdaelv.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2mtdmvpuq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gt2gryuqggv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2gfcuujog.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gt2ttrksuqo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ysjzmxto.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbsbvnpv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gt2igeynwqq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gt2ghomlrka.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2rdtbahbo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2mzskneoa.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2odzalzge.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qlrmrwcz.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gt2nvwgmlbj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gt2apfxnoqe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnfsvkec.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2xslqguvb.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2jhbnyecv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2ekikplmf.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gt2couoxmtj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2hdfvqlyp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2odcgfruk.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gt2jggnhccl.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2mqokotuv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2kgokmohe.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2jqvkelco.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxghtvcj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2eqdfyzic.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2kmuettjd.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2gkrldlsz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gt2fbjabihe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmtrokct.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixfajait.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlveqvzz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnbwmqox.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2jvjniqhg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2cbdtgcui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gt2osqzzudv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gciqsgdl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gt2zawelftf.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2xiexgrhw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2opfybzrs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2obgbmdrn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2teiixcxo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2lszinici.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhywfgdf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2rvppgecw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2nmoiywcq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2jtrzswgz.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gt2rejybjbm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2dvhrstbq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gt2hxysitcj.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2sktvazri.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2gvcwrltp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gt2llmelsxt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2cllxexqu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2thbydywr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2zemdgyys.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gt2bgjqepkx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2bbfzdpbq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bshfepea.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2egpjaapm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2sfwvbhaj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2uyehywby.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2wazowjac.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2abvgogyy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjiipbkr.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2ppenrznp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2sfvqchvv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2hbmdolat.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2vvqcqnal.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxrenvzl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2wromlayu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2btamglrc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gt2egxaqblw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2dlivdiqp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gt2wrzmgqou.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2gdjxsntt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gt2irjiyzvl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2lfthmnva.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2rkzbizit.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gt2zwoupans.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gt2xaxlwncd.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2razvpzqo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2pmscripb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zesyidlu.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2peelgmzd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2taqncsxi.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2rnabwmfg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seulsjfg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gt2qmcpqpjw.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2fwuaviqt.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2xbdwvngj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gt2zolngblr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2ubdvuzli.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gt2seybomcf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2gbsqcvqe.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2uyaijekv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2idlagjvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2ysbvjmqb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2ihydxbwd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gt2odfpkcgt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2urvmfcji.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gt2yhquiiyx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gt2hupvmwdd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gt2nyqainsm.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gt2ulxrwbvd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbhicuzj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gt2jewztnts.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2jgobncuw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2yofvarag.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2jfbqoyca.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2lbtrpuqw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2knpszoox.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2cbwnjzxv.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2ghecujkm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddtbvdjk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2nookcxmn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2ivkmfyjp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2rfaloxmx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjrjpndm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gt2ppfbznuu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vydkjzyc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2brtyssnc.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gt2kugzgqxf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gt2szgxegts.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gt2wdnaxlox.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2aznoydcg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2pesesrbf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2nmiavlje.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2icakkpcy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gt2xhkxrkdc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gt2qqcqnqnl.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gt2rfvtvamt.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2qczyvsri.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2ehrcxucr.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2vmuzznau.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2zjjyvvtj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2qfdglxjt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2idkcjehc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2cvzpwujk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mugowtui.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2jkqlszgl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gt2sixelarj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ilzjgudy.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsdiougl.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2scunahrd.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gt2ijwriwor.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2ppdtprrz.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gt2wudbbzzj.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2adqjsugc.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2iwmuntiy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gt2updedcvd.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gt2kovaxxjk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2jtvlpeho.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2mtiuyusc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2kpzkuyni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gt2dmjztezy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2wtcfuych.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2cfhdvioe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yekdaiad.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gt2hrpvtkzw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2fkpcbxdr.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gt2mwpvflzr.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2mptfhiqc.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gt2toismotw.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2grrcpowp.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2xkcnmodd.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2llbuwydh.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwyznpfj.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gt2hnkhsllg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2xdgknvhz.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2kksrnuoo.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2emfuivub.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2uoqdcmqm.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2axxzzvvf.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2hwthvmpm.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2xzzowuym.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2mwtguhiv.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gt2oalxgyln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2cjmffzoz.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gt2jtsjciel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmhnukgl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gt2vmkyfpyj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2ayczkjwq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2dlzpgbwr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gt2yhphzjbw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2qondsoag.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2krxomcts.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gt2bzruryap.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gt2segwexto.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvnthhld.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hguybhpe.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2aisokpnc.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2ezkhknoz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gt2dfgpmaja.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gt2vdpzhzkd.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gt2iteznkhq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2wwxgrnmr.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2ifvuwqfv.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2yzyiwkbf.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2xzfvfrye.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2hngbmwze.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2awbutynu.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2rqnntwey.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2jjhcnfzq.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gt2wopaazvx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gt2lyxcwtbr.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gt2miasvdta.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2rsmpdcge.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gt2ylwrrtfs.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2laswyhth.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2ldhrygvs.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2kfkcmwdz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pehpwlyo.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gt2tdshnmey.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gt2prveenda.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2wtjorxge.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gt2xfklxgzi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gt2xfiroacm.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2sbuafwhi.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2pxsxpbus.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2ctqboctj.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2xjqepgvy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gt2rzkziyvz.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2bizczrlb.html


<!-- 参考信息 -->