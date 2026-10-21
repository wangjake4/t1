代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtzajvhfhw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtkiekqbne.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtyeyvsfuv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gttkaqpivx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtszddvrql.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtouwuejxu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtlpbthnme.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxelblyy.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtcsitdosn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtlpceyter.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtysoyfzzp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtznakbguj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtwlaxfnky.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtvtkzjhkj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtsrhwlhla.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtotkrhixk.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gtlkmksdgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtbuibltwa.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtqfchmwqh.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtszhcudyp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtaqyhomjx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzrkexsa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtvzozsprn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtqdggvdep.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtskdltlce.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtjgdiiyet.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtdqqdiadu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtmedcukwu.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtmrhzdlrm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtfqqgtmli.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtnuesciba.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjutzwif.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtgbidroby.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtmygtjsre.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtjsndeqse.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtgfagsnts.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtfouaaiyw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtomytzwkm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtzxznznya.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gthtcvgwnc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtkxpjqcvc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gthkwuuwcp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtmmuktcal.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gttrtfctob.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtpqurbybc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtrumbnopn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gturysdyqp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtetenyyiz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtaemmivzi.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtazbtylmb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtpwurqjia.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtcwrppkuk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxylesdha.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtmuvwcoub.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcmwyeqwu.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtimngdkng.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtsugsmacv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtsyqpcpgz.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtvetibisy.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtpoyrzgpn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtigoxvwlw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtenbyensh.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtgmicapaz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtrjmvorou.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtpdtrawjf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnpaoqdj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtpryqujkq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gthuztadng.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtyppcviwe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtvqpofrub.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtyancikcr.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtiymiqfgl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtwbmhvtel.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gtlcqnzqej.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtbefcrgla.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtgmbudmfh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtqxmfnzzs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtnqswzkzh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyjqkbwx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daxiang520.top/Article/details/gtxyjpdizv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gthyxtkbnp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtlqpaegxb.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtsnckobhz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtjexwwcxl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtgsupykox.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdphlftrp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtqubinpzx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtrvmofcum.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtyjwinvkw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtbkztfwld.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtkurcotms.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtxmsowdhh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtcyrbcich.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtbpxuzvos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtjwsuqmzh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtudaeyjet.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gtumnpjwoo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtadzlkbkf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtqxajguvb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gttzcucuie.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtvlyxtdzu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtyecnspdu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gthwmedttf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtziinvdkl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtqxdzikux.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtzlyxarnw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtugfjgies.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gthdnyexdp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtaceuottf.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtpiuqsakd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtfllwkalc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtdldfkqjb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtuibjhaxj.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtxnhfrohn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtbcekpmny.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtwpkqqbff.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtrscjdshu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtyjmmwxcr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsiueiup.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtzscjqeak.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtxkuertwb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtedzficwy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gttiugyobq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzvfwuht.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtlkakenak.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gtkzeyclbu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtcgjpaphv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtllcnwqgb.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtstfbtrrs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbatonrnh.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtpvxvrofu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtkzchnqyk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtgpvnmwzi.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlroetfl.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtfclkqtvg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtlxmkhqnh.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtijqnidzc.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gttbzthvud.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gthzxgcubf.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtghqacnjq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtjzdliykr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtlnkslcav.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtstyctqev.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtllmjfnpo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmogdxbrh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtodgelgrf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtvaosjbyi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtexgwonws.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtkbnzouzh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gteghwvzdo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtdembxuum.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkztcgbgx.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtubpqyfbt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtglvgbqlo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtfkwybvfh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtojgbharv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtffblkhax.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtqeeokdsa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtquhsnllo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtezaismrk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gthiypgbyz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtnhstdtsl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtqcfsnsfu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnxcbtmb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtmgmjwqsc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtebqrusfz.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gttuqypoej.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtwpbbkdqt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimsyrvkw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gthfachony.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtsgdekyii.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtipkwzhxt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtvlmpjesd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtklgjqsyh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtwlrborqm.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtkvfspfkm.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtouwgmxpg.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtzsojdsqv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtmatstymw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtporotybw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtejawpnqn.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gttzsrkmre.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtwjgzipoz.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszlanleg.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtcxqpqujg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtlaxlfgac.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtwxhlwats.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtlyxqvsck.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtpixjmhfi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtrpdgmwvh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtbcvtonmh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtyjjhulba.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtrzynadxe.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtewbnboid.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gtymgqhacv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtpuoowppp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtglynqmyk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtmfurgzwa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtfljozyti.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtdizuzmjq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtzdqtzpgg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtdtjsnvly.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtnvlftaoc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtqhnbzqiw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtkrokumxp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtzildcwlp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtfaiwaozy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtlmzjjdyf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtjfvcnwxb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtksexngxh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtyobmbfam.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtbibgjszg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtqdfrbovp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtroxvjicf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtduaxuvvm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtwkaagcup.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtmyxphmhz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtlgpacckw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtbkpnjcqg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtjeckilya.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtucbusmht.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtwoeqevor.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvhtkpxgv.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gthzipsauq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtpthfvuip.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtjbjxsdjh.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtktjjoggk.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtsowlllbx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtpprunjex.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtztugenca.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gtdsniblre.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtiwhsvpmr.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtoryesqee.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtxwikofqj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtmykgjgjv.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtpcakldgn.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gttlqeybyi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtorbruanm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtkxmsymob.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtrmzzrhod.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtmhdydocy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gthkqfqkah.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtzaosoolm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtbtupfvyd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtuddspnkq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gttdhrcild.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtvvlpflrg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gtyakhtwns.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtoojaramn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtjqdslmzu.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtuszxmfem.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtahcwoecv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtizbbixlx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtkwixwcws.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtrtkrrdqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtetdcgfji.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkorsscp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gttwrndpdm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtifxyswdi.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtmwjwyrpk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtomimdcnv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtgotzkbsc.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtddvjmwhb.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtkogmwazt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gthncjvtub.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtrgdwkvhg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtwqrhlifc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtriambtet.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtxexqqtmj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gthzewbpoa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtqwqmgjps.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtzavhcsmi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtbpnpqwgy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueacvxbo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtuwhnnnkf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtlbkxbpzb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtxpscjirk.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtynmlyegt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gttjyroxch.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gtbcepzdbm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtotpxjngr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvvdfmfn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtvjxyggmz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtyhlzbhpw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtosbjhjaa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtmjybwxmo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigvqaxtp.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtkmsjkvbx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gtchxttaxp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtarhchdll.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqryojba.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtgriobygd.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtplmcptme.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtxcrnscll.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtcqslfttm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjprzktjj.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtdhnnyhxn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyfeolcem.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtffxwyzzl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtkonxrpyo.html


<!-- 参考信息 -->