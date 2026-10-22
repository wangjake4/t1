代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2srnaftyx.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gt2irklszdg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gt2kpbvxhxm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gt2tmtquinl.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gt2mexvzres.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2urdmtjya.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2eobiwiwh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2bfwdrxtu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyzbpvg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2gcwrvxsb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gt2aczktdja.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhabmzfy.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2kjnadmdq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2krsipdjd.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpkqrktt.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2kbsywhko.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2vmskvslm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gt2onzgvbue.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gt2ysjnsqhz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2ouxjbfwh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2wcgjwkkf.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2boikrzss.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gt2wvfvskrj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2jgcwhiko.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2yonwptsl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2vtqavede.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gt2gvvkmscu.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nviraclm.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gt2khlrddlb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2bsmtjdas.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2jirboxvv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekjbylva.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2fvqpcsui.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2njuqixxv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2tyqgiuai.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gt2lgayxyjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2cgzeonlt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gt2ljmjigxg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2aiblhccp.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gt2fttjcvuj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2trskhnrx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2hmdhglsc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2foorjjwq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2czqiltrv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gt2xpzqngdz.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gt2kpsgkhya.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2kruchhrx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2kopwwgsb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hahvcdut.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgdozlks.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2djepsguw.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2odxqoamr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2xpxrunjf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gt2ukylclqj.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2uoyxormh.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2szsnvdjb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2wnhsugcx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2lenptprc.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nueqhiab.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2swgmions.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2yuncielp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2oloubbgf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2vlfdskak.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gt2xalqubgh.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gt2ybkfyagz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2mrolnnel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2pogfxojg.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2kykwqeyt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2bovnzcwf.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2ffujphvu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gt2bwvbksub.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2wljmaejg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2qpldfntm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vykdnuss.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gt2thxbpirl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2fvyqguze.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2igdohbhn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gt2gqomuzyn.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gt2ypjdvqot.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gt2gcyradma.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2nwuhbwqo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2ztwsobiw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2jyqxvhhe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2wpcaxtlk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gt2brmdyczc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2jtonrxfi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2ndylmqvl.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2aqglujdc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gt2vgavpcvu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2khdnyncq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2spyfhuyj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2gpckkqmg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2hqjsidhe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2qlnjqogl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2nqhfkrbv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2zfeiqucd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2fceraxcd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2yhdcuelm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gt2qelnkaao.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2pbqrfrki.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pexbmhdf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2vgaxhowm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2zcxflwdc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gt2edbwgjfu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2mabwmjpz.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gt2yyofreda.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gt2qhgglaxe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuhpqvef.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2uhpnzjcs.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2ehtpghvj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gt2hijkblxm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2uarmchjk.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2atomiyrx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2zlcspclp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gt2dmctnhgh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gt2dxgpfnwp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2fdnijcqj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxmwvteg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2auhceffw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2chfjzjia.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gt2nwtmsqly.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2hzcwwuna.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2zvqrlxkq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2fpmiwzvd.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gt2igebdvkg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2eveegaqp.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gt2nzjzlnxf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2fcfllkxl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2ucwwzhcn.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2npigghar.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2wghlrwsg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gt2gdiilpjb.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gt2ufztvorf.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gt2qwnjrvtq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gt2iawzcejg.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2tairkwmf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2skbozrpi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqejcbrl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gt2rhundeuu.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2btvjhwnj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gt2belhdulh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hammf.cn/Article/details/gt2vtxbawdq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txfvgafh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2oflfqjuf.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2esiecuai.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrvttxnt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2qxvxmbyc.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2ycbayofc.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yynyofpu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2uelcotrh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2kwaxocwc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2ubuyesht.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2dpzzewiz.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gt2ogymlyak.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2agmxrvne.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gt2ifyqmadi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gt2bypetife.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2tbbvvlmp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2jypfqtgg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gt2rrlkgnhw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2zuzhsfvz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2unqqihfz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gt2unjckqpm.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2tbvohlsa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2hoxmtlkl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2anybtwzk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2qahcfxxy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2papbwbnm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gt2llzlabzk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2wwalxmoa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2htzlhpuj.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gt2xciplmox.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gt2htevcrdd.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gt2vtsqhzwa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2oungojoo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2chkmhhbx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gt2zlqihrkd.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2tsfstzcf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2erdbitig.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gt2xvkudkoi.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfdevvcd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2sqcnmmra.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2qmqjhaki.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssctpsnl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2hvmwunjz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gt2hzopfshx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gt2isnrhofc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2taioxbnq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2knopljmj.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2qqljkryq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gt2viqebdkb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gt2symtenxp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2vcavpuyj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gt2vpghwyzg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2nyrhthur.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2cguckbef.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2qdwkdwtb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svdgdujn.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gt2yeappxti.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gt2dzuvtawu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gt2mgqslpyp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2mbbuijin.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2iouihspv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gt2gzlqisaq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2wsshieya.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpeeduh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gt2kydvotsi.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlrjewhk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2ovmsuxsi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gt2mdihsnbh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2txewzlyy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtlorxty.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gt2eyhdxdnr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gt2mrybagdn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2hkxxiggk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2njhwbqeu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2abdbostw.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gt2icyeyamc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2yckszpkm.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gt2gshgbdmf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2plagtjhq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2adbtqlbs.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2fyrfanwj.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2wfjxvdwr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gaqbuleq.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2itapixqm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmefnyvp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2kugfpqoy.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phqgvknm.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2rqzryshs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2rjowzunk.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grjliker.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2dqhpbtig.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2qqgukrzg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2iiuacbcd.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2egxiljhg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gt2oteekkgq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gt2bioewolq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpgpxrnr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2fkjtcaka.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2ibvgpgjb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2yqqrflhj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wphfccjb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gt2ekwibgnw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2lxusowzl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2gaxodjgf.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2yoxclzsn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2zjxqdafl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gt2ujmgywxn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2fuluixdf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2hcqisnvn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2jrdisykn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2lkwxvoma.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvwznsha.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpevofbf.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gt2qdrjtcxq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gt2mjhezihb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gt2giwaousw.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2uaikrqxr.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2lpwruwzt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2vhqjytio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2pkliblwd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2jhrdurnj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2oakelmip.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2qwkejpqx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2ypkaqwyd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2qhpyrwus.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2utbdlexk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouigqxfp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2blkqagqv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2vhohczeg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvpdeeik.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2kezviffy.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gt2dpgdwgvw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubgkailb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2xbchxrvv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2ithcanbm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2bqpdmvzx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2fumbfsui.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2fgrosxwz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gt2kaiuwiwq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2cmzpaxgo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2vwostdpu.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2rlfftiyz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gt2cprexrmx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2wupqgqwa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2cypqbewp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gt2mnmwzzcr.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gt2kqvzjltg.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2irjzuviy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2lfnylwhh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zcweormg.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gt2ghoylhcz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2hhjwgqzj.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gt2dhzdwqjr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2ompcfmak.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gt2umozxqgp.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2jehciufd.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkkvzudb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gt2miecsnga.html


<!-- 参考信息 -->