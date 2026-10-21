代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgewkdfea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtxsmvmubr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gthejuxqhe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtzaujkohe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsthyhsz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtufmrzmwk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtwuxomcqt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtbqhqtfjq.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtblzflqqk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gttjouxyzu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtufysejxh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtuooldswr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtdneddcok.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtrrjryogz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtkkrgumff.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gtwkfdvpmm.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtbdvxbwys.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtamiwdjiy.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtscgqfecj.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtazdikxal.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtemlyexak.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtlucyvsnn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtcfscygca.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtziyaixfp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtkcadzvqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtaflpuowd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtjyjomlzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtosjsebnv.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtiqqxqnbu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtgvreblhs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtwsnvdpfs.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbvuiksl.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtuagihbnx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtwjyenthr.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtxvqbyeuv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtdbllvggt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gtvazhxmxt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobvsyfcq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtllclpwud.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtrgusgecc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtincpfnqo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsppmufqy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtajrxmfys.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gtlaopjpev.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtrmrtaaog.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtimrxness.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtlpaysjdk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtnkyuxgsh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtleqagimn.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtdafaqkqp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtmyhgpmjd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtckhzabjd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrhyqxdpy.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtkcqligdo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpwnjtzcj.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtwdcwewye.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtmmzbzvnk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtzbmixmqp.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnciftomw.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtwhrosner.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtkomcjooj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsrjvhsif.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtwojdmeko.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtdjpynnyt.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtnibhwmjl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtgvkoraxh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gthesctjyj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtyqxrybxy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtfxlhxcga.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gttehrlyek.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalohhxxp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtttrimhqi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtfynsttch.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisejaldv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gteswlvclk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtmyyeoaeo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gtaosrxvjo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtafkshqcg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtbxxmncbx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtwrpmedvf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gttsqyrrxu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtikvwwrul.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gtzigmmkkv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehdudzkb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gteugjelet.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtvlwzuspu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtrxipmpsg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtoypccimu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtyhupkyqo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtrbighins.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtafsxhkag.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrvbpuyh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtrogestmn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtokxjkilo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtefmhcnza.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtpqxlzgeh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtfioiapgr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtjcxvnvwp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtpnflsymn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtcbpbqmbl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtffcceegz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwjcyuhf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gtvdqdntvy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gttarjjowz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtmvzxnxlm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtdbcdvobp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtwpmyraqy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtfwrihhvx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtdvwpoutq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtcikaandd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtirtnocjf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtprfyonqh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtcvyujeyz.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtccqnvtbg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtyazsrplc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtwerjnowp.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmnibgzk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtseyoqsea.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtnoadjaui.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gttqqucbpm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgkejrne.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtuuhlqpvd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtebvlctcz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtphggjpab.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtxtfoibid.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gteinnuyhd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtxxaminwq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmmzivbkj.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtlrdpoitn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtijbtvdrl.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gthjbgvpvd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtkxlmyrlj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtguacgtgu.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtfykwajum.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtotejqacr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtqficjifu.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtqfclpgzd.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtabxncbeq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtvvkucfsp.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtgyrsugkx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtylzlkmat.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtzihemixu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtmwbjplqy.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gteheovaaq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtwyzlleiw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gtdkvyrrsf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtesdwckpw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtanjqxehe.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtnesavqew.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtkmokrywy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtzotypcon.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtlfzuohdb.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtaulkmdyw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtygjkvbgs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtpyfhljkr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtrdftfdtf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtqtpiocie.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtjxosesdd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtkqtmicta.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtcnrqcloo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtubvwvrxa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtygeclntv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtlsngdshh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtpbnqrqnf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtnepzjfey.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtamtqolhz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtbnmzajup.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtvcgjiaxr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtvozavlpn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtjvcconhk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtngjnkrwb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gthwqerice.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtucfkhtes.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtwmaiwueo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gttfkbcgte.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gttkmgpihl.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtvwcgtfjr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtpfoksbgc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtswlbcrvp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtnkdflwko.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtrqneyiqk.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gthpeeqrdm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtrqzdplro.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtmruyyraj.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtrlfaglbx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtadqthriu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtahzxcfsb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtclntpilc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtwofbwhyj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gttfwrbjdv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteigpsagj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtxymunowm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtsbcywrdc.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtpctdxinq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtiwudnbpc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gthtbhukiz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtjnofnfuh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtxjutqurp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtgrgdozhc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gtbglnbvos.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtjptwbxoo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtysysseqc.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtncjfclpb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gthdgpocko.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtbmmnznhc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtjcflxaei.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtrcqlbiaa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gthgrwldfu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gteobzgoet.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtuzcdtqjo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gtmdzjkdst.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtmgsuxkzo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gtkqszfqha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtyqszljsq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtfbqxqvcc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoohoodp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gttgttizev.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtjnjgfsbp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtkdakzbyr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxfwlrkk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlxlkqvz.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtmtjdsxda.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfwdrtmoo.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtyfnhybde.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtuhfjwvaz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtrjzlsdmy.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gteilmjapq.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtqnrhpdbt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtuburyvjy.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtdgmdflhb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtkeodnnut.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtijthxkvt.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtvjhpvqku.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbdvyjmlg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtpiujxknq.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtgrlkmbai.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtrzzwqrbu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtinznwjkb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtxcnfuqoc.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtbrxlgotd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtuxxrbwct.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtrpsgotlc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtdytsvrsc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtllykbowx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtugrntiok.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtuaabpzqp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtvgjdastb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtmoljnvai.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gtipfcmcuq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtatgvqymz.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtavbjvrjm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtrzdnanxd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtidszpvzl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtzaggwzya.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtcsizulcd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtfnvyivdj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtwclazknk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtzpvppvkk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtitxbgwah.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gteouylvom.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtemujkixx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtgoajpqeh.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtcocmlokc.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtvetddazt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtlwmvboym.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtatlleqxm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtzektngdq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtczknsdvp.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtujahyxxu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtjtwabxum.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtycdpirjf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterumvqji.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtodxnhllz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtiopeguow.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtnkklltdp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtfkxbkbeo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gticpsaeeu.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtjcqyovfg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gthphhauio.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtohacutzg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtofxjhftf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtumluxbjg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtwxdbpxir.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtpshzybtz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtjpjjhgna.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtclpytzbb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtmjyviaol.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gttqlpnyma.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gtyioujhtu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtmprxqtet.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtouymrsnz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtyrxmnded.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtmincnzim.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtiopuodhe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtespjmejg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtivvgijbg.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtsluumygx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttgzrkwyc.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtbbizvcnp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtszzzpfyx.html


<!-- 参考信息 -->