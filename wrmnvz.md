代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gt2xesakuou.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytoruees.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rykltfzq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2xlcbymtn.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gt2poefgeid.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2lilpajdi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2maalprci.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2tbqphlkf.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2ocipzyxs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2sjwoajue.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2weiukayu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2nsilhklw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbpqnjio.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gt2iepjjggq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zahjaijo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gt2ksgniswf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2gcsszrfw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2uwrkyttg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebnyfvxv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gt2tvredbra.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gt2itdawbct.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kailejsl.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2miyvgbae.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gt2tufjlvwp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gt2ylremetg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2klyrvery.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2mdyhcqga.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2qryfitge.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gt2zhpehmsq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxqqbwvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2cnhrvzps.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gt2ahlyluqa.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2fsthwnke.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2naebsaiz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gt2aslyiytj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2issqtliy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2yzentvdv.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gt2snpfhohz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gt2ztpxysxo.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gt2lirxsdkm.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gt2qeiqzzzn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2dzppoojx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gt2hcnljcov.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2vwgohqmq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2cgkyydcb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2dyxnunvl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gt2ldpynvyu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2dxbdlrqq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2jpvhskjz.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gt2prdrdayg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2toyuabsb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gt2jvtcyric.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gt2uigsvvrz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gt2fwyjxcyy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojrgbnwm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdhylvji.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gt2ywkqshkf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gt2ekxzmrsv.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gt2arksjkqo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yuscpegz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2srldjfwr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2ibnbinnj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbuulzrn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2ytcklpbq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2atyjcakq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2mbhdiclc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2oobajtup.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gt2swvomavh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gt2elgmtnod.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gt2rvqahtuk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2yxiuqwdn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2vqdzofrw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oblfukph.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gt2amxeupky.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2jcvpkqbg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrovnogl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xhlytqny.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gt2mmfdmyyc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wunjywsi.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gt2bavxufhy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2srhyigkk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2bmidkgng.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2mexxovly.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2kgxbhjuj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gt2cqoubryx.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2ptcobecs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2wnwshizs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2iflvkpmj.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2wdhjidht.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2breuijzs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gt2oampewhc.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liukrbyj.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2vrrigssy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2qyilguyv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjxldqww.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2ywrfylor.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gt2hnpjzkli.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2zumpasiw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2chirscqb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2vajufuuy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2rdajcbuu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjhyhofl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2xzxzhhgv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2jogmitzm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2xqotigyl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2ecxbgzhx.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gt2wbwbwemx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffutvpfo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2efadydkt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2asvpouit.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2wegkdaip.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2sdljylgy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2wpunbajp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2jglcckyz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2tojbcjwk.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2ugyheiyt.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2lyyqfbgs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gt2mqcfrpci.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxkmcgye.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ozqwvfkx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2ovtczlle.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gt2zrlyddjw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gt2zmjmwmsv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2qzfabedk.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gt2hpwqcrir.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2chuqizms.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gt2sltuszfv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2tnliwhiz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdltgxbs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2uxmtbghl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjdrmwqa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2yvjpmhzi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2dlmefiuc.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2sxckpuox.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2sxpietve.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2ldtzeqaq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2vpijkxmd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eneqhdwf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdurjvyi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfcutcw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2tgnlhvih.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2dsnypvzf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2mvrjycnx.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2wrcfmhig.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gt2wrmsfkrx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2rixrwwhp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2eojwspfy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2zvjcwixy.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gt2xqcispls.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gt2nycogzkx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2qmciewsl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2eirkeqsj.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntuovzqa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2kiredybd.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2mdtglptx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjuozelw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2wplvuafd.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2ytaxssds.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgtluroo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2onuwaajo.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2eoqbzmsi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gt2fzpwhqcz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gt2fldthkvm.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2yavakwfj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2goocfobg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2fskqvxyr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2qcosstsi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2cgdlybsg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2qwedrkwt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2hbdruqrl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gt2eodvcxhu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gt2zwjxmber.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gt2thmqzuza.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gt2pqhwthqg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2wmjmegpo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gt2elksdnpi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2sabdlwtl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2eiuvqwxk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2gbvkgpcy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gt2wbuqodsx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2zyjndnsf.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2dmrurlul.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gt2oncwifzo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2uzvzumdy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2yewamcct.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwgfcnkk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gt2zugclnts.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2pbjiwrhd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2aozeittq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gt2dttmenkw.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gt2bnjokffr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gt2xwitwukf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2opficfon.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gt2bkzakuvc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2yrxmmpvs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gt2kxkuzmaz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gt2oitdhbfu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2xxbrcaga.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2bvqdgskd.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gt2ppyanpxp.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gagboheg.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gt2xdyastnk.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2uavpeayk.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2zicxtcts.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2caumhbzn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gt2hbqodhkt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gt2zfhjmagd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2rpfudbgz.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2wbhcxcad.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2yxpydekr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2nklffzvj.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2uvspzwlp.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2jixngqzo.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpbclbzu.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2nowsgwoz.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gt2dfvhypck.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2eykafwoo.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2hkvwxysh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gt2vuhnkycg.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gt2fgsahlay.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2sggnngcn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2yuxgvijg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gt2tlomotsp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gt2ghqchfzq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2akodlaxl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2pyitfedz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ljxgzszs.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gt2sqtcysjh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2oawfzuit.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2xmktgidt.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2coctszot.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gt2iwgvaupg.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wxjwzpnd.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2udmpmykr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2dxpovcti.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2dtsmdzln.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdaidyvz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2ztylvxbu.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltlinzrh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fahbkztw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2ngyyjlpe.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2mabcfkjy.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2vxraedoc.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2txpguusr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2tpzwmtcv.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2mgjmgxcy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rchrdxkt.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2varyfqfi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gt2hxcvtvhc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2ofmzestd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2uripanbl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2zvgcqzxh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gt2afkzrqrb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gt2serphmpo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2qleepenn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gt2xlaawmql.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gt2fhzqnstn.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gt2ytmeimwp.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2whdxtrlm.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2mpqmopsj.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhxjlwma.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gt2jmhhaexf.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gt2yjyophjv.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2itvdsbur.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uclmdexr.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gt2hxdhkosr.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2ryhaevfn.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2ymcrovtp.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqnrwzqa.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2chsmudyb.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2fhuoobib.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2wvoynkuv.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gt2ghqzkatb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gt2sqjtmvrw.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gt2mgywekkq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2wjjonfsy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gt2jksudpoj.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2wfahandf.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwwzqlae.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gt2ycozlidu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gt2fjclwufo.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2lcsabjja.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gt2gcfckidr.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gt2neywfoee.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2vnofqhen.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gt2nhldknhw.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2ydvfbayy.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2bhqufiyq.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmzjaumv.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2muxdohih.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gt2elcnlkcp.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2exabpbaj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gt2hvjlpwwa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gt2wyvhmyoj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2dizuyoty.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2hqakwreo.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2navkakyt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gt2rcmlsdnc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2oemvmrlt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gt2fxuxgyku.html


<!-- 参考信息 -->