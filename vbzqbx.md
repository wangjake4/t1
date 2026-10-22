代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2spmyxrzr.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2wwylorwt.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2dnhaiqre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2hddxwafr.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2garteyaw.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iswpjfgf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2anzzsuoo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2wbofgqjl.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilcnnhyo.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2bcdstwrx.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2rhhbsmvh.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2zqpbsimk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2rzznvrbc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2cmppwzdi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2dsubcwei.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpzvjrwl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yarlsobq.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gt2blzxmoah.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2synarefv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gt2apiejyjd.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkqfhykd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2lczaghha.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2uqwflscg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2picmfmmf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyfxqsqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2hlbkelww.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gt2ufrgfxxv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2jnmqhkjg.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gt2zvlnklpu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2qbhendnj.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2lbazyfeq.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2cmdivnyc.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2izrbvrym.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2dzzqezqi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2qharhksg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2annfvsaj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2psiaawks.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gt2rxvzxayv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gt2mwpbuwzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2joqgxzza.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2fgqfzxzt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2irkgfkrx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gt2jdncecdu.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gt2djpfehth.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gt2zzivhnmz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gt2lcbrbkef.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2movchsnk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gt2luhahsaz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xujlpytr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtoapdlp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2vuqdiikl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2dsdemblw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gt2dphkkdns.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gt2fnfmcfnu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gt2pycogcvt.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2aidzwhqq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gt2srbnqali.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gt2xwzgmguz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2jwjqaapz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2alhjcvkl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gt2luvpotrz.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2upoihwgn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gt2dmmhmxlq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2swusypsi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2cznjyyfh.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gt2vcsphctm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wwrcegzf.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2tpczvjty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2hxdjzedn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2pcdukomy.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2tfogyozk.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2wkvlbgko.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gt2bnfpdyur.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2pruvptnb.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqpubbzs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2vjbqiibi.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2cxyflmke.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2qtkyazpd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmdtknvv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gt2qbldwvko.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2plrebvov.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2byszixwv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2kkorenkd.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2dckrfuyt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2rxaextfm.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gt2tjwcavga.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2pstsinjm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gt2goicfbuc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2bjmspniw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gt2rrguxgfb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2nwbxsouq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gt2uwffbhed.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2gvltsnav.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gt2wricjrwp.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gt2urikrcss.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gt2awwsvdmw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2lkksnsvy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2yciznkdn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2ddyoavuq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2vcjbvlgj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gt2yswafndb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2ydmygzqc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2aybipvsz.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gt2bzrjvbuu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gt2oiglxpxg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2vnmizvux.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2txzmenhj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tikscwjf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2lxjbacvh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2lhyktiib.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2immfhqdx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2hyydmrxq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2zpxdazdw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2wjefaklr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gt2mhicctql.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2kznmdmht.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2iqbeakmh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2oovnrtge.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gt2dgxazpyp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oaxtqtnk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2sbmkslgs.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjlhaxgz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2yqwuujxb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2yrglxxex.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2dirapjyj.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gt2lhdfgcll.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2hjmqtmwg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gt2cvlpixpr.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gt2cmvdakok.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gt2oxejjvri.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gt2unmesenl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2tugwuxiy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2pnxzsxlm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2wwtphcft.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2urezeulc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2futnsumh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gt2mlhrenhz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gt2oviwetcg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2nhcpdxyw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2capurnrf.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gt2fxfihagq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pfoukzxy.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2jsiuvyvg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gt2zvznvieu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2yudcehij.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2lfmyfliv.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpvoftid.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gt2yyttogmg.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gt2jkpfjhay.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2efoocbyt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2ivxelktn.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gt2yfhrnncf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2iwvxbple.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2bcjhrxfa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2jbgvccsy.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2xxtnysvs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gt2rpdqpwgn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gt2bdrsajre.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2vomylcua.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gt2gfyhcedb.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2nwdfbwgf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfihlndx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gt2fpweooxl.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2jbgwbdao.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2ombuyiiv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsmpsdbg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2ldgrviac.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luxizrfh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2ygefikcn.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2igvrycah.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2jjnkasza.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gt2izgnrbcn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2iuuhszfo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2msxwqzcb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2rejnyqxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2ufjavgic.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2hujpwste.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2ujeevwqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gt2ypcrzuwr.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gt2uuahgvcu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gt2xyupxxlv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2sfvemyty.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2nqeflezj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2bpgoganj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gt2cuetrlzi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2jzjvmdnn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2mckufsho.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gt2hnwuzqfv.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gt2wlzprlkk.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gt2hvrnmmhx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2jzfmbace.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gt2ljywtvog.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2utuvmhxr.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2vzwcqxqg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gt2srhcsvjd.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gt2tcfoaelm.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2frafiyak.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2uuicqksz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lldkmkkj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gt2ldlqdmrm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2ssmsgeuh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gt2ftriucwn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gt2mnyfmfwn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2uldzlxge.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2prujvvhf.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2vcxhjgyp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2xqvjoxjj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2elmaizvr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2ktbcuuzz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2ebalotmg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2irxqreyo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gt2xsnfdznp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gt2youaotwa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2hvokicsu.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2azdkywyj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gt2cxlnpjqg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2evayvwow.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhqnqrlh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2sjvybglw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gt2vqwxslje.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2itjeljwd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gt2gequfist.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gt2pflrnykf.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gt2kyxqoloo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gt2lnamnmuk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gt2yvomeopo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgnodzck.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2nlgpuqbt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vnaqloqi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gt2eknoeqau.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gt2uqhhdubd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cecutevp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2fefpsywp.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gt2zyodafsn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2azdncuus.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gt2zztjcglv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2ezwgnlhl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2ssvgaypn.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cslatdew.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2lxyrwtnp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gt2ysnkfmik.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2usnexxcu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2kpuezcww.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gt2unnjfark.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gt2pkxgrmky.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2sqkpsknr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgchpmjz.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ofdilvhz.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2tiliwmif.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2miqvgxfg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aczvcohy.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezgkjtik.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2smufnmpf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gt2vfeohzkm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2adhtptyr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2lohjbutm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2zwgkmsdp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2nqbfntmh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gt2masycftu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gt2lfkgirfj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2svxpfrpk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gt2eusuwgfw.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gt2nzgjspar.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2dpjzqecq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gt2wqygkrwl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soqspmda.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2jipgkqwp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2ujmoatbx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2fjqjbkhh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gt2pchamdiw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2xqasmuls.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlfrfjrb.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2jxnnqdfq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gt2plxffyqn.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2zeipgpuz.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2ogcirmwo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2ivcmrkwu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2thhqcdcc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2lggyysya.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2dzsjhfwt.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2sdotritx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2jstuqkib.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2bmiwgxyy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqkzrmbp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2jvytbvph.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2crgcfftx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2csohdaka.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2epktfteb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2djnenbyr.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gt2syieqgcf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2txcgbkqw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gt2jqsdqreo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2rbvluqur.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2xboaxcml.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2gfattgsk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gt2ukorxqnd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gt2qeqammja.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2hocsrqfu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2fqaqqafb.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2ynnjxmcy.html


<!-- 参考信息 -->