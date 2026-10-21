代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtekmqtftm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtelmpabal.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkppobgm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtoodebrvc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gttrnaadds.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtifkbahry.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gttqjcdojs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtyfeijfum.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtbugtjjuy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gthrzkjvka.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtdwiplrcv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gttfvjifnb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaexilbn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gtenxenpsr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtydvzpolq.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtkittlhvt.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtivkhqusg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtxdihxrjx.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtljpvbccn.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtrieqxmzz.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtyzbmiqkl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqutginw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gtbzffbwfr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtmdqkygfz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtmkqeomlf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtgtwyrpns.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtgedcatju.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtcpcrktyx.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtsibvnqel.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtbctyddtt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtxehxhnek.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gtoiomhqyl.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtudyoswgw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gtxltyomgq.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gttcpgyiyw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtbwpkdoop.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtufkbgvij.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtwonmqujc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtskpzpwpc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtczaxcsog.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtlodvorvq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtoxxchvsv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtuvdolhae.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtrmhrbnhe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtdtahspgi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtenozdpmh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtenxubgkp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtxngadxqb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtwoeuwnka.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtkwtyfyrd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtdslksrqi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtxykzisau.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtminpzkbs.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gthasqpuqc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrfjnfqny.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtpjycwoak.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtswnaiaru.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtrrmundwq.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtuqnbaqrz.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtnvzbrhoc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gtujhyscuk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtjjhscnog.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvnapjcn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtjpuetxah.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtmmbplqhe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtyhdvrpwi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtifkdajkk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtrguonvki.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtzsdzpzyc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtemoowzmn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtdqfajqck.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtyulpkcrp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtzfjewvjp.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtfqploqdp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacsgefvd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtddntuvqf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtsgowfotc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtevnykqiv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtvimscsmk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtqdwwaxsq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtyfolartb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gtjucsgsmt.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtlpincati.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtqbptwlsk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtwifncwjt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtjrxprqjw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtzriplwnt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtuycirdsa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gtdkgqfziw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gttqfkixal.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtmknixnhk.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtnvmxmtyx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtdlkmvwkg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtusbluzrc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtllocojhd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtjpjuafwn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gtnrmimtvj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtajtdqhea.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtptbqiegw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtzgoshhqz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtbubdkqeq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtulfyftxk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gtxulsrhnb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtiyplpkqo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtqnzhqdaz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtdqwlutqj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtzpudxfnp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gthhloniuy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtaioojusr.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtnhjyceek.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gtkdffjgox.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtzoipcxwz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtpidgocfq.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtlipjucpj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gtatzykawi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtixkhtoik.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppwtuphw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtiigdwtfc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtygjaekgj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtpjqpzwrc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtsjfpkcjo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtdgzlbuwu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtxmkixmbm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtvgaayjaw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtrrvvgdbn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtuenjwceo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gttpqiijme.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtldkkqyqf.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtvxnehpsy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnenqctun.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gthklidbjs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtdffbzyag.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtagslwpuv.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtyivyrwvg.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtignltjgk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtstiftmoc.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtacvorgtg.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtqpystsoo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtsnbacchb.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtxdeihrbz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtptmvquts.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtkdtwgigr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllrsscoh.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtwunjuxde.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtyzaqmf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtewqywfzz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpadvhri.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gttxzaucqj.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtqylqusgm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gttzftszdy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtpisuovvy.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtojtpmpni.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtrqlhsrwe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtgbjjhmsz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gttsgymkcu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtrzrvtdrk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtocepwpen.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtmknyjgie.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtjcusbjhh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gttnmbvtap.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpnuqncd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtmbxpgpxz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gtrltyfneb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtiobnbsht.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtsildekqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtxvhntbaq.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtyvutdwvh.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtemsffsmk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gtvupfbyes.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtekztrxat.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtwbwkfxho.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhqijihq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtaqojksfe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtkrpfpeoq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtwavqmbxi.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtswmpezvy.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhkevhgk.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtqnhayufx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gthvdbgopp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtwxnktktw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtssgsghag.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtzlmjcsms.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtafaoinvh.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtbrjrttyk.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtyuqugimv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtnxkcafcs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtpzbdoytx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gthmbpplxe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtntwcnotf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgdquimf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwgevxwmo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtrekpikee.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gttzqfvfzq.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gttnhbystm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtlzokhllw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtbdjzghwb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtovxrkicz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtudbcvror.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtiunidexw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gtrlqtoeqw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtavmjgroc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtahkjvtis.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gtaixaieth.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtkuvejqjf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjaecbmak.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtrvfvhizr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtrvdmzulh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtutdypbki.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gttnvlxutx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtocummtfl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtcafnshti.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtuhlgvuuv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtvrljxeck.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtdwkgnfwj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtkcuvgreg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtbsaocrdz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtltmofoim.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtkqlkwapv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtlkdgsmad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtftuxznwr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttrpzczwv.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtajckvwpt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgbpisuxl.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtdyumgvjm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncfwefyb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtqoopnuuu.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnpzkpfhd.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytbiwxdb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gtcrmfejrs.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gtjgfrcned.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtgrdpfgkr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqaojpbno.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtktasbwjx.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtzetpywjj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtmauuhqjn.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplrlolci.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtsnxlcmjr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gturefitjo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtdqfqgimy.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtxhjqztip.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtzymjwrnb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtcwmynote.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtsbsfzpcj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtxelggicc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtzfzduwhw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtqsehoxoa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtabsiezgz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtxvbwojpx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtsrdeerdx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtnaqdwymm.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtdffmbbdh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtpszxwfxc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtekbwwogk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtgpjjrqpz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtbcctkdpl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtrugcdagh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtmjjmoxik.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtplzrcgxp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtrhszkvkp.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtymuorjhs.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtfdtprgaq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtzhnpjpvk.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtqeiogfuj.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtyqiqmksb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtzhyrolws.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtlvdkonsx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtncyskxhf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtqhlfspgs.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtriijmxpz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtdifzumfj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtdolhvksv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtesxyoopm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtgzgatqwb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtvzawmmvl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtygyjrmpq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtqhjinrzw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtrqpazemy.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtndvqygfb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtnzerpesy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtpjqzzgic.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtzsbegacy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtbeifowrh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtzzdypynx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gthyahzlsx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtqnpskset.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gttxoidgme.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gtpxfntaaq.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtaubfrtdi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gtfknquqbn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtihbmzqsn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtruualhrd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtubwqiqes.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtqtpqlpuu.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtkxkudxft.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtzbjkvjuz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtuajbyjtq.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gtuyjufhki.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnywztjjy.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtplmayamm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtjovguypz.html


<!-- 参考信息 -->