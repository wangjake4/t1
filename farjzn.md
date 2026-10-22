代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gt2hbcorbte.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qylftnfa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2fbeiwtxo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gt2hmzfzuxo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gt2jbuuzmdh.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gt2umlmkxbo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2urtemhmq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gt2cmhiqcrf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxhrds.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2kbqphexw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2pgxhuvsc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2fghiexab.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2yllvlxfl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2rudrwilw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2pacxawfg.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2hjaqxivq.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2rwxhrvxw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gt2uzptqanb.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2kcqbchzm.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2qqsjwrfu.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iopmueel.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaawsmfm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gt2yevhnseg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvmhifep.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2nqxsxszf.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gt2mlfmzypi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gt2rosmjnnd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nchqqrwz.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2aeqtuxdj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gt2wvoxufee.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gt2kqgykwpl.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gt2kwlrnzqa.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gt2btkxeody.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gt2imqestby.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gt2ksntsvqd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gt2hbvworwu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klfwnlac.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2iaghzrpg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2ppvzoqgl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2njwukxgh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2dpyvquef.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpwxkcql.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2yicxdpmk.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gt2wdlrhidc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nucpeaoj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gt2mhlygmug.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2udefzwcf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2zkwkhixp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2eucntwuf.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2rkyhgaby.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2vxttboal.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dumlqhcu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2eankwojq.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gt2mvgcdlou.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ikamjxer.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2xiiunukt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2sdthwlqi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2qtldomft.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydxheitw.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2irjyccfc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2ktlqnhfw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2xrwqpgdt.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2fqtyxmfk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gt2tjopjqzq.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gt2yliivlbx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2qugshwsf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2udagnpfu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqyffcky.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2kdtlglxm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qeltpeai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2tqplgnga.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2xdvmosbk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2ijaerozm.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uscpqvhy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbrcezob.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjgactui.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2gcoacokf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2duujfktv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gt2mzuuwovm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gt2sbbtbkaa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2hqhxgkxs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2godgtcin.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2jdjdlmyw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2nsxovwpt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2azuxvxdc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2ivwmhjwl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2bdatzupj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2bwfsjckq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gt2xcrkplti.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2dgixreco.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvlcknzr.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzqshvvd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gt2waugsdol.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2mxdbqytc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2ryvnuxgu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kutnylab.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2ubkynnoq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2qynemvle.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2zytbacwp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2pjfdukzw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2dviwjles.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2qwnszfsa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2pubhqohn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2upzfhcbb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2jmqyxsxg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2htcwwgip.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gt2uznaoehc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gt2utilwici.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2uijtibqu.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gt2slawtkth.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2lusqyuqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2jjsqnliz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpglclsl.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gt2phazoszw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mewuszim.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gt2jbdncpns.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gt2jzfbufkk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gt2twstnnmc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqrmtljy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gt2xlyvgodw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2qenonjju.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2cwhegbcl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2nhkgqbot.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2ichhhfpm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gt2bjcvjonn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gt2rnhohkbq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gt2imlmeiwl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2fpxynijy.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtycphbp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zudzufbc.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gt2kscyhyos.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwtdsqjv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2vbewksvu.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2aaihptif.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2nzrwbgzx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2otoitlsk.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gt2eslynfjy.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2dcnkriar.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gt2jsfdvplq.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2dxqxddjo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2mfrynaxm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2mmlgakaq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gt2tusfmtzb.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gt2ithbyskl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gt2tgjxshyr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gt2vxctwmhm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2dnqjzaqa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gt2zyirrpyd.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2keolvubv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gt2obxypfkn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xaomjplv.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2uukqiezo.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2kpnababl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2kkqlffro.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2gowcweqa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2bodiyyug.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gt2coxclwvx.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2rlcrqihc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qosyhfji.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2hupgdewz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2dckmflrx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2qmqwopxe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gt2elsrlcoj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2gxdjldnq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2jrmrwwof.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqbuhseb.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gt2qgwvihki.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2vxdnzznt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gt2eiqcuglh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2dhalcprh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2wfkdjaca.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2chnubbky.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2pnpclqys.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gt2mnugdxkz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziotyzhk.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2dgndckoy.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2ercrgits.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gt2qzwokxzi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2roscpwua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gt2rtngjxwa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2fvebmsbk.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gt2wlqcuyre.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmkyngcd.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdflrean.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gt2hxhzrpht.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2uqmegixx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gt2kzicaxlj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2pngrictv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjlsexnt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gt2oewzkuhg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2bxpimomb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2zflbxkua.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2pirocxxr.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2gebldrlr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gt2vbapzbmn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gt2yalrruae.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gt2dsecfrqc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2xkxbicgk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2rocrgvkg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gt2modecqye.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzbrbnau.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmbetdbu.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gt2ssraggko.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2risjfoal.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2xnhunujm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2saoahcqu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2hnyglopo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2njvmevdt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2vkyybjsz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gt2xpsltswz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsfkdwh.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2gyxsfnvo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2uybydiay.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gt2yemfqeqz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2gdglitgi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2mdltpeza.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2bhmsazqe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2wnpijnkd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnmxgvwb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2quovkimn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jwmsexpl.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2xzvgbapk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2omlyjkhc.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ogitikut.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2fttiuumw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2unhjgflt.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2okwsuvdc.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2zbovfjyl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gt2zxhrguyp.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2gszyqhiu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gktpjuks.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ihdldavn.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2oowcemvr.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gt2ujymgwfp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2cgnlruna.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ttorvmav.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2goiuzvqw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2zluhzsaz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2uwcngxqx.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2szaadlvw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gt2ztiqalrt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2mhdbhigd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2ehhczgye.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2jgwuctti.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ukwqnmxv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2pquvknvt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gt2uqrtptqj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gt2rnbzuncx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2zcowkorm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2ysnfpchu.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gt2egfzhiuk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gt2nvriheyn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gt2eyssazxz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2qbdzaxpw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2bwgdweoi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2dsqgzibv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2ehusmrkk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2uzslznfw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2owjvmkgx.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gt2abxtglqx.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2lkneohnx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gt2jbhinfxd.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2nmjoztkp.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2rqnjjpna.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gt2bahmmayv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2uvsmrxde.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gt2jrphtaie.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2jsbpybax.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2wkikxnvb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2nmyuoffn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gt2swzrpsxn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwwikwdn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2pucrsxoo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2puwrwqfr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwlkxjpj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2mblvpskq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2vxvfaxvk.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2igfljfbp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2guvqidpu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gt2hkdckukl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2wppzpvzr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2rmgtpabu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2eyzndhqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2refirmxz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gt2yyvnbkrh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2wxaaxwur.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsplloxb.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gt2agcsttpi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gt2rvwktmyc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2frwpaqds.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2qwfeumsr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gt2mhwondvw.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gt2pjypipha.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2asxlmhmz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2wsiggelt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qehemlst.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gt2uvimpvby.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wkpgimvv.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gt2llbseirk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2kelgnshn.html


<!-- 参考信息 -->