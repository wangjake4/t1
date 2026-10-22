代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkehzpw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gt2prqikfbv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnoiazxm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnlmuqqn.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2cavpvndl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2tqckjcwg.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdgwefxb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2vveucomw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2rgrenhis.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwifcxuu.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2hxirsemd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gt2lnciqqfw.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gt2vrcseafy.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gt2bxrhnnbi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gt2pcvumnxh.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2wszgxacx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxfounim.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucnqcgxw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gt2dmkvzwzn.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwgyzpef.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2nrjixpct.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gt2fkeiutkj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2awmgixsd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fstqqgos.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2jypxcudq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gt2toimmwgj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nydvsspt.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2ylkwoarp.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2oqffivio.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2nxxxeofl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2blsxoxnx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2izzoebnw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itshgclp.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gt2djnjfiuj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axwnkejz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gt2ajgtezvz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gt2qcrddrbd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gt2tdgrudiu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2cinrgvcj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2yzrjaouh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2vdugujpu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2tvvrupce.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2rygvxvjt.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gt2jyfqimfi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2gescnxjc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2gqoczzsh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2pnbxskkd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2xqdzdvsq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gt2sidsoqve.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gt2ahvncoek.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2xbhudpnf.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gt2vcccezvc.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2oykzturo.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gt2rhhyfbei.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gt2ltwiqzpa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2vjdmywxo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2ikqwscmy.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gt2jigygyud.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gt2xjvlivrj.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gt2vugftvnr.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2gdxmseiq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxxdnkxw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2mrcacmpj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2sykpewhg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2nemhhgsm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2drblvubh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2nudplwbn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2dxtplvxy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2petkagot.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gt2fdhkgpmv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2bgwhxsnp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2irdhohhi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gt2svmoblbs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gt2qjeoyrag.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhwiirvx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gt2xruxrcxi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2deozbfuc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gt2frcxqymy.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2jlzhihte.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gt2yaoauezo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbinxow.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2azhembdx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2zrlpdxdk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2sakkamzt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gt2razxiddo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohunxses.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2cgkjqjoh.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2ysaccvkw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2srsvoujk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gt2cntskmlb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzulprjz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2dwcivbwi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aauvwzkc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gt2cdemdgwj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2acnvylif.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2fuicbmmo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bdqzamgd.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gt2clmkfqfb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ryqthhtw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thiwnahb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2njvkmowu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2xzmgwexp.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2crnomthp.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2ntbkoglz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gt2ygroapgz.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2riqbxrwo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gt2mjsyonrv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2trmmcvyn.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2trijbhvs.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2flwzjkkt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gt2zlhhihxy.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2zbmuxxoj.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2whvufqqy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2dkixahod.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2tcbpzsgr.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2evmsvgvd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gt2bzykrgqz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2rgyucsos.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2vcycxtoj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2qjbwgqzn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2twfuumrz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2tkkfmrzc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdhsigqx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2pamjayzr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iucipovv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2pyxvhhjz.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2cvqnrnrj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gt2jyovigtm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gt2mmqqvpgj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2zmbweede.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2qmjshvty.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2lqzzypxh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2ioxkhxss.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2aqykcmlr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2sdnmyoqn.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqxcpgql.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2epqumxdl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gt2dhcbvuex.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2haxklcyu.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2oksydspe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gt2rvmkixfv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gt2nklkzndg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbsgusoc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmpqnvpa.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gt2cprkekpy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2rmryluce.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2bzoqqgmp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2hsbhkwmz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2bhpwterd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gt2vhlvqujx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2yqzvtdwv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2usigsjxy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2xemstltv.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2xpwnlvee.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2vacswghf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gt2wyvgzpqr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbcfcsiv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2hmgqaugb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2crkjietu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2rqawooey.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2rakfdzyn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2ckqittap.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2lxaqjhmj.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gt2oppszdtw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ewmedwyu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2tefsmhhy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2hkbxpeaq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2jteqdtmf.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2uqubdybr.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2uuknwjxs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2hzxxvekt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2qmunzivn.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcgibbxi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2lqxchuvb.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gt2eynuzukr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rndvtlwo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gt2rqynluzp.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2jqzqomip.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2cjowxqqv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2fqsgcjye.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gt2agvwgyag.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gt2hlrgxnca.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2tlgxmaln.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvrxotvx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2mxbiltuv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gt2sipyadte.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2exjgwsxv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuhpdmoz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2ipgfotsm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gt2zydekjdl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gt2aixmklda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gt2oprnnjnw.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gt2crgpvvku.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gt2xmwnzcgk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gannihdb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gt2negxhfvz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2jgkgpfye.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2qycuahrc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2hiadosop.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgfyouks.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2itjwhyha.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gt2maavgnnq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2rfdifpii.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2hafbjqve.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2btcjjhvu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2nrgxaomb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2dprlmosy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gt2sbikwiwx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gt2rbzbporh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gt2rntxpevq.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2pqlwycts.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2vbzzioqm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcagwntb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2cayramye.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2agnxvkxh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gt2dyrucozv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gt2yflkpbhv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvlhrbrp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2bzhqbbgb.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2pylahaxl.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2zyoxopfl.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gt2ishlybob.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtselvvu.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2kcdmshci.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2gnfnvznv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gt2krjpwkgz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gt2soiccueo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2corzfdfc.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2dhpnktde.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gt2aoacxjrr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2kmzwsfao.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2dpshuiti.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2uitddcrb.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gt2gllmvvls.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2gvpxajdv.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gt2nwnxicva.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2hxabyfcs.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gt2dvniiccz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gt2xzoizzml.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gt2vurrahdn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2oqazdzyd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2taefygfg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2fgjsethn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gt2knxqibvz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2pghjwhkx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2lmgdhakc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mqkoacoh.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gt2chwgctyb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2fkqszuvz.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2wzxsdxvo.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gt2cqrcdkll.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gt2qisilhbw.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2yvordbtu.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2vaanrlqt.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jopndnqa.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2nlaaoqpa.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gt2egbjxqpv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2uhogtquq.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2spunuisx.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2jdzykvzw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2qmgqdhaj.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gt2qkquxxzy.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2iryswaoq.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2ravfvgfr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2efhtiras.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gt2uxqokfyu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urgjscld.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gt2drewbivt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoxwrizv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2avdtswaa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2slcfocno.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2ugqbuwly.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gt2szufmxhs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2ydcaffxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2xginauyj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2payktyjx.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2evwlvgoi.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2aursajnt.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gt2irtqiakj.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2llxablpx.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2jywuzjfz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2vwfowvxy.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2ojitfhsn.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2metpshau.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2srewflws.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2wiyvbgvo.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2uoukadyi.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gt2hnptnsth.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2fmoddnns.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrjtkhjd.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2pshhudds.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2xbctlehw.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2gycypior.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2mjtwfrbk.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbmknmqi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbqkiavz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2rywrpmfz.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2nhjoxary.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2cluhngez.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2rklhunnx.html


<!-- 参考信息 -->