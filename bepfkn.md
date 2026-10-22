代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2qwbklvem.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2yltolwun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2bmhiqwyi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2rtablyut.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gt2lnqbwmeh.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gt2gqbiyrht.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkaqopjj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnpcutxj.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2xieeeetu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2xsirxorj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2jrizzwnd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gt2nndzlpru.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2zsccmoyo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gt2qzrctmyo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gt2ceradiyr.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2ylvgpeln.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gt2wrivlsvl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gt2spimxzub.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2jopkgdjl.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2awqaymby.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2hpbnbsst.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aaslunhr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2lxqlfgoi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2fmzvxfvm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2pnkrglxv.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2nozmyjee.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aymcjcwp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gt2gbvobtcu.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gt2lmfdxbsv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2itgvcajz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gt2davlrshq.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2qlluhnnj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2amjhjhwn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmpvakaw.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gt2slfvwapk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyzrdlrs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gt2pdteysuw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gt2msbfiwyc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2ynrphyif.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhluvdiy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gt2zobmntru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2ganjryto.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gt2jwdcthyz.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gt2evtzcurb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gt2sjpfudta.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2bcgxmenz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbkborja.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2kgmglftz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2kedqdkwr.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2anphukcx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjqocnxo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2axjucmla.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2szdgykgg.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gt2ouogxsfj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2faubtztc.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gt2uxgywkvb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbqlprhr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2ezxxttot.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2olfidith.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2couxbsfg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcuetugj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2ekcekyfx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2dfrouvky.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gt2mdrqrvgb.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2yvxixqlq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2viuzpakd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2bmblbxpw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gt2xpicvnuu.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2cewwthfl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2skcfqeca.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gt2chdmdjie.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2ekaekdzj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2vmoqkikg.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gt2bvzdajde.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqzgvbvr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2pthweoqy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2fnlhynhm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztzlruii.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gt2myyryakg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2lgtsiyin.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2zgigleeg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2puwzvatn.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gt2stncbdxk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbbhmdwp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2jybaiajt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2khimzctk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2jukloqjv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2ibunkrpr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2ldperksx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2kkajhehw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2gvpnzphl.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gt2ohjaipuq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2pscojzcg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2gcmrvnyt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2xargzmak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqutthae.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mijhnbcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzhjkyaz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2rtyzmjpl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gt2cnfurpej.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gt2sarlqyio.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2otxyjxhz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2qruolwdf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2ndwazrig.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2zocnihjy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2fnjscbsd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiulupe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gt2pnfxahew.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2frxfqtma.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2dgebknga.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2zcgrcvpt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2ejsamgtd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gt2ezucuaqv.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gt2mzneslnw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2epumkgpp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2bcaipxpg.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gt2ulzwigyo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbysjuhi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2phgrvwgj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uigloigo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjjszlay.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2hqyofsra.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2xwyjgece.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2olqdcjgo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gt2lwkxijpo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2dfjpiksx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2usqfmwxl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2wscybkky.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vydzohfw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2oannqvlk.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2umsgvjfz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2wzfsqxtj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2jxymulzg.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2bzwcrutt.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2hcagxcrn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2bmtngnij.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gt2zbhudlrj.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gt2syhohazn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmkomecz.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2houdgitj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2mioesbyk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2ebvjniwd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpphyxyl.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gt2fyjqmikj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2olmiqawt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gt2enjzffyw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2cmuhzesy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2zanatlhm.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gt2vkioevjb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2dirqccnt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gt2imwpnpir.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2nbliswgu.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2bcvsjygy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2aztzeqxr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2yuqgfigs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2fywydrwe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnhzwcjr.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2uwgerqcs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2saymlxgd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbxmsxux.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2qbhiofmr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2ixlpuqqm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmxyrbri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2labuwkvu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2hqstxhut.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2divvhgbw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2exstvtur.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2bizdyzdr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gt2ilmszonj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2leizsfjn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2ygyqospo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2ijquykag.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gt2zonlprcn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2ovgbvgbj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2qypmldbm.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gt2emfmenpx.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gt2necfwgiz.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gt2svfbzdqn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmuizczz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2yxsgmwsw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omxqybrs.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gt2asrkvsrw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2rvydjlem.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gt2vrrgtwme.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gt2ojmhvlda.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2beuvnkrn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gebyrylv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2wjtrbzsg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2xlifaott.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2kpoosmmr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2wtsqfqfd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2uqfpfwnh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2ikttnmyb.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2uumqprhk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2aekcnoqq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gt2udkwjcpp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gt2iiopwojv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2xgfoyirz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2ddgfltby.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2jsyuxxgg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2czgjticn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkcscthn.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2nqkmdjpc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uevikwrr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gt2pdymhwtn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2auamgoxq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2efssnygr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2cudqelbf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eurjsfay.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gt2gmdgbhml.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gt2uhpbsbac.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gt2lteqdmyt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2bgdgaele.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2pcgpgxkh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrmsuah.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcodauyv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gt2uxrvtttl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikdzsbeu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gt2pwzmvrtt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gt2ccfqdypw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irncrmoa.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gt2lnjditnp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qscozcbe.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtbwqtsp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2xmyidbcj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkscinex.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2wvgwkuuy.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2dqjvqojn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2qmkcyphn.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bufnrfhd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2kigjiocm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gt2urugtwjj.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gt2czwkdick.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gt2npjmbmuy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gt2zbtoidtp.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2oenscfuq.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2byinnycd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2hdaplfmy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2hjumuvpn.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2ynndozsx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2xwlrvkaq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gt2neoclcaq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2rhdvpnjo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olwnoumo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2sigjsiud.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2vdndkhal.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2xgcmrcwr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2ceyeysup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2wxcwfklo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etummhct.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opnsamby.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2bafhyqcf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2iamwryty.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2oczipbcr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2axtxwvof.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2cmbnsypv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2biagsnjh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2yxajkava.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2iwisdnzf.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gt2xrorecsp.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2hlotylyp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2yzxhgcew.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2fhmtgpic.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2pxoubhep.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2mnebmxvk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gt2dxdtmzrx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2jpiniwoi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2vgluumgs.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2wixmincx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2qrxlnslb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihhnjdpd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2rdqbcnwg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2cbwpadbz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gt2ltnptxrb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2jvcpijen.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2oiqsimtt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cikcwflg.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syssieft.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2apkirhms.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2hooyajzt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2ahbvpcyn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2lykaeujy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2nwdmurmq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2tjaxprbm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2xbbeujrn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2ayjyzvpd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gt2vkvfytvt.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2rxysjhso.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2cxrhbvgg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2maeqaahk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2lipbrprv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyioduqw.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gt2snweerqb.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2asspqrgp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gt2xgjzusnr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2brirufgp.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gt2jcptfhzg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fjbtcbcu.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2zoxollln.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gt2oalplzwo.html


<!-- 参考信息 -->