代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtbvvdxubq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtnlyhylkn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtjpemmfay.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtzsgtsuhq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtyohrjoup.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqudherwh.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtocjmzcuy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtijaqnogv.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtvagjezgl.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtcdvngfts.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtjpvimfnm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtnarkhmzn.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtkljbqtdm.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmatvbykn.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gttwdwryjw.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtrbibptor.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtacatektf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtgafihkcf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtygmogsvg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtxjnrswnj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtwgrjmonh.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtrpnstemy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtompikvhk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtqceuwlzr.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtanqsnhdw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtyvoddumn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtcbylhrtw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtdaaoledc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtdojbhzgc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtaqlfpvdd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtljchcgcd.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gttnvroana.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtdcttmrru.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtfqotqmaj.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtbbkmfimt.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtpegpljcp.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtvfoorgwr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtrnrovbzz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtinulftag.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwzpzolb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtrznohkea.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtnjovgohf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtuejzmuyy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtmqpjdire.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gttsavgpir.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtwjnwlzyk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtkvdbfbxh.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtaofamzyf.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gtwhrblcey.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtqozabewl.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtybgeaexq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtrevvseev.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtymcjnfce.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtahciwspn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gttknfxibo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gtofbcmrpm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtiqdjlhws.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtlounrhmn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtonwvrqcz.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtlsnjmwdg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtfmlmlvpz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gtuvkbidqf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gthougreiz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtpfxqgcbd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gtfmjrunih.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtehyxfwbk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtwwdswton.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtozuqijxe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyyizxtie.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gttxtzzayq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcusaerci.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtvkcxfope.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtjpjhjajb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtvalcafza.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtgizmzezc.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrulgjkm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtxmwxrcgc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtgtqeyoyr.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtqkdayfyj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtneuwtnij.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtaaoifmvv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtucrvuddk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtskxjzrng.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtkexpwmbo.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtwagcfxbl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdponxcd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtunbkghfc.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtdserulyc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtsqaanlbb.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtiaknsqjs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqwnzgnty.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtznytyxuj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gttthskeso.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtwyadvfdw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtgoudfomh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtcipnfjci.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtpvixjffp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtfavistqm.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtwlfmxumv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtceosulbi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtunocrjmj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtpvkozmfj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtqhvzsyjx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtifggactn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtaedvvsci.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtztykmhbr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtpsnucydc.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtpzrydxca.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwybrtli.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gtkfovttwn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtsveltzlo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtebhzimdn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gtxxmnizhl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtmviyjjlx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtwuvbovkr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtctrfuklx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtwahrwzur.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtnrrgocig.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gteacxbtly.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtqmsxukzg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gthmxezeid.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtqzwpjpwp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtavjtwanv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gtsspnveaw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtdipubovk.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gttnuakghn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvypqlmc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtmidfdxot.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtorxwtgsx.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtcircwkel.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtqtstptdm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtwehiesbc.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtfuxxmsgq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtzsaxyust.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtcquuxrmh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtfrrzduvy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtcnurdjkw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtzzrjjkbj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtfmmwwdqc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtrmvsebmo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcminvtuh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtqyozimvr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtbgadcsxc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgbtpviaa.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtrqwdyxkc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcuhuzqyo.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gttmklvvfs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gttxwyancw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtnmravcdx.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtnrnkownw.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtbdhhxgad.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gtsuwsiutm.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtqhvxdntg.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtztvkwncu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtanqrzqec.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtidrcwrzr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtntvxyuvr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvempxks.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtlljkprml.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtinedqjuf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtmlqtitzk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtyithivyi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtzsmzhhmz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtpduhcbrc.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtppougfql.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtruewvcrb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegfeymfi.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtldfsrglo.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtzdzkkghd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtrkvnggcm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtyzomvjnf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckltzmis.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gtfsqclxpg.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtroypbihx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gtwcrxmsch.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtymgmgkor.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtwqiskpqg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtixjjxtox.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtejspihqm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtcnqfugaq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtoapyoppb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gtjqjtxvwm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gtyujflifo.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtnsowepee.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtlomvrybu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtjesvuwwn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtqpxegywb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtnhmaqdgw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gtzzwngxhe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtzbcvrrjs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtxumqhpob.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtxxuwutna.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtpexuqqxw.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeiwtnrg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtsioirfrr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtovwqixdx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtyfyntotp.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gthbbcnfgp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdsqjbdg.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtbnonospy.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtjxmziktg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtgpduvqgd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtivmyziza.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtdspxqsqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtbozvtbsk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtegbxvldc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdxlhzpcr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtiyuwxdtm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gturdnemux.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhjupxta.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtaetgmgbm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtgjjpjobu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtbwxenatw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtmsznmcbi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtiljrdizx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtcelrxwij.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtzdvdmvdi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtmweuutde.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtxswoimrm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtyehsrtdh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygivcjve.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwthzcfaw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gttqaouccj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtbfxbjnmi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtikohjohh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtthdbyljv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtlogmxjfy.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtqcbiklpo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtbffbehea.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtlomxehjn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gtaeopwpgv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gteyqiqdgi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtrpsbqgof.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtesyahaoh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvbhwcqc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjhhnssa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttplkfmoi.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtyefgkzus.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthzjhxcdx.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtizywbfpd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtsjgkvxft.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtobgyyelp.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtlruupkqv.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtmiblptjd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtuibrgxqp.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnbyvpar.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtoflgonyo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtvktwnjdh.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gttfjfvkdx.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gtghnkyfml.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtusvcryiy.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gthcgxqtjg.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttnlvthxs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtphbahlhg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkrfwsgj.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdgwticjr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtenwlnokm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtapnddeis.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtuesmyaff.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtjzxbapcw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtxgnmxlrd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtxexvyyac.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtxpyqbbhp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtcockiflg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnrqijxkr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtkjgahgzi.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gtnztwdeqi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtyrcefuxh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gtyftkjclw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtedyxjcfs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtpfxhyjez.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gthdufcric.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gttcflfqpe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtghyujlhn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtybpounrx.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gttrxenzjw.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtsnvnzfsm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtwwfmfycp.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtyqxlouat.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtmyxfsqwd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtraxyicdl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdujdoaqr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtwahyntix.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtelkxtxui.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtnhjbznkm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtaoivpscg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtzhpwzfdj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtfwlonigz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtyrtenzvo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtblhskegm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtjnwtpoay.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtbbvxuocm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtczuvfahs.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtyrsmconu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtykyzrxia.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtaidreput.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtmdreplfp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtrscsntis.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtgyguqayq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtsirfexvo.html


<!-- 参考信息 -->