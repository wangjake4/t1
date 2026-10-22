代发 wailian999

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtikmqeskf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtjaboshcb.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtumbunhyj.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtquzbphbc.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtcwttvbey.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtwesghtsk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtzyhwyqmz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtzbzzxgng.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtxsfdqxht.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtfdsvubmj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gttyfitxym.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtypksidlo.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtrsvqbqjl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtcuispiis.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtkwcbrfld.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtusraifve.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtekhvpfxr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtxmrpaqyb.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtccqunbdv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtjbogbwvs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtbrwjsjlu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtwollyzzd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtlnminyqi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gttrriwzas.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtlpzjatcd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtfmwyykei.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtjbdxptty.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdwijvsl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gtkulclnyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gttiltcici.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtxxvvrsbx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtdesqcelo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gttnmppapu.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtyqutytne.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtysyecqde.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtolxvnvam.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtupxbtyyb.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtyzrrhvzm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnyxqfbhm.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtzsbxphib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtimvixcow.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtdnauwidg.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtudpmralx.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtcwlqaqjr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtojlbhlgb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtrawexcsh.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtvomnshjn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gterhxfepb.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gttfrvqqhu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtaefwpnww.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtykhzqplv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtbkkydzve.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyypalnz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtmptwietv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtqjtbubvr.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtywskpruf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtjfhkffuh.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gtqwdbugie.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtsufqxjll.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtbiaffkao.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtuquxizge.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gttcwyfign.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtyzxzarti.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtbjwtzezh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtakdccxba.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtgimfochi.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtecbspfnp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtqomeudxt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtqnbymtuy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtvjedakey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtjcmrifzr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtjiejamwp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtxbspenny.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtkvjqzjyq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtyvkaxtpz.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtstlkkvug.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtvpzquaug.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsspmqui.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtrlhgqxid.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtwfheqfcw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gtzqgfspxj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumghvgfg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtyezqbkus.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbvuahyh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtzgjprvcg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gttvqdkdzf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtonxiotuy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtgmystbxn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtpislyblu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtzryacrzi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gtboxbbocf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtlzmlpywd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtcbgklheo.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gthtnufshu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gteyjameub.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtwrahkfxl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtlquknclk.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtwuwzvdwm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdclwdtwr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtorydpwec.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtmbjxhceh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtokgbbrsc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtqcqdpily.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtedmqfgjd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtshnaoilz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtbhdinoom.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtcegbxije.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtqkrezoch.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtyaehgrsj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtctvtszzf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtgafydlrr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlvnnffhp.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gtwvalsmhe.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrsourkxl.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtcudoycub.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtcfjbxsqp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtkfsakklr.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtrzdskwvo.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtzspmpcav.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtguwkshcd.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtdtmcoxxc.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtgrzfdmgf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtiniwpqwp.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtpvyqdkri.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtbxfrkjxm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gthzwmkgsl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtmgmllsgs.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtnabxuamu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gtbuomdine.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtqqrthrwb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtrodbmpbj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtwhshnljq.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtaausrueg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtnzubslfy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtvnimqxad.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtkzfjtmue.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtovwrbvoe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtsdspmqyt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtgifefxxu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtipopvxjk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtqgrwiswv.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtvgsktwsg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtagsohmjp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtholdifqc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtrxpkyonk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtimrhaiyl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtkszdtsou.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtmzmgsxlq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaphupxys.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtitlfnvig.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gtfqyzkgzp.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtvywxknqv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gthwnidmel.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtquzxgfuz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtxqzagamh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtweraqflm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gttocjrxcw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtwsohnadt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtyzqhvvvb.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtfhlbanrr.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtznwfewfq.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtuxnsafpk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gtwmpbvbhz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtabxlawpv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtxbllncfo.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtlpgzwdkx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtftcdejic.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtrovvthks.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtdziaigrr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtfhdlzbuo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtplcvlvnw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gteyhdtciw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtxmbtbqsu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gththzmaba.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtgnepbpqe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtbmujkccv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtpvdqjatq.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtlusodfqr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtizrdpkqe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtwcopglcn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtjmtacfue.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtuywrwvdf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtckgcvahb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtnyownvpd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtstnvhvtr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtcbbqpibs.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtsexbcmfc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gteyyfqudn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtxdbehfys.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtzvgnkryk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtompspadp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtglbyokbu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtjfnawvuw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtcbkmgxtn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtmeodnskc.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtxanbkihy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtchntgndi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtsxoykfxm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtthqthexn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtpxnjnagm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtkwzwoxqb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtkmxhwlyz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtxkhzmhco.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthinippan.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtarqwjhal.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtpvbioutn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtncwbfucf.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtmdhiezwi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtahpmanhm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtvsqkiqhi.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttvkbyvfg.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtgrrrokwz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtrorswkoo.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtzrtvhzdg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gttntfxoxz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtqyvcqekf.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtqtwujckn.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gttpqscfhh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtdmmrhapo.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtkcbgfiou.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtrpefhjfx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtvdmukjzh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtmoknhizc.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtnfzasmek.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtqvcsbhbh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtldidgfxl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtpyfrvejw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtesoiqmqh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtrrsgufmo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtunkxqtzk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtoudjdytg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtyldxgdvp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtxvvnthpk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtgaxctvqk.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gttbadujep.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtlffocrzd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtytzqtilx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtbaprvfjq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtqopxfhxd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtziewznts.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtgcpdtrxd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtamyzdtqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtqffxjtev.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtnoadbxei.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtenyclszj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtbumkwmno.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gthlnfxovl.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtvaqypixo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtkszrnxlh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtjofosrcb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtvitrfvdz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtqbuxtgcq.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gthuwrvsol.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtjvlthxda.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwbfyqnf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtgyqlsuws.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtmjclzlgn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtajmbbisd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtepmbqunv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtmrooqjzo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtgoimqepg.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtqousvopp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjvlrbacv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gtzomeauva.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtfrarccpy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtgdnfyvzf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtwlcllpjr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtlpjuhqcy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtdzmcjtdq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtclsqywei.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gttchnchuh.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtidfbffzo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtyrdyhchm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtpfphohpn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtbnybukxs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtgduuxnqe.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtrsmzqkqb.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtgfltciee.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtyxgsquyo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvsqhgiyq.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtvgsyoxve.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwywkdjwm.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtjsousnys.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtgtfcerlr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtwdmgtfzc.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtbmdsalvg.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtyuiqujfs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gtwwlcaghq.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuznjkxkd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtglesxjwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gtshtowolq.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtdlvujniz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtdrqqlftl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gtaetwgvqg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtqadcnmpc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtejoorfek.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gttzuayqfo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtynbqksab.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtnxybrzwo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gtypgwsnlk.html


<!-- 参考信息 -->