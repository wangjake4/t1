代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2nqprjthm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2kxonpksx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eadtkrkp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urnmhzts.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2ddoctqcf.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awjyxfxr.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gt2hzvvlrdu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xizufkcr.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2mdavduhz.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqxddpaw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2dnkwywap.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gt2kgahksdw.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2hdnsityw.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2iynintky.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gt2cnksdtaz.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwesihgn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2lodiyjas.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugalkyyh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2uxnxnwen.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2lenetlgo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gt2ykjanawq.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2rfabogdw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gt2jdntornc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gt2ecnlvgtg.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gt2sylywmlf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2sdzgersh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2ryhqceya.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2xcvnvspg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2jrijhkrd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gt2oumrsgbv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2ppwvlxqf.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gt2snrwsmhe.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2kvplixbs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2cpacbdtk.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2etgusxtw.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2zyczgstf.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2juktyrfs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gt2usvzzyxs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2mdaovmty.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsvgmowq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2cijxzwtj.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2yxzfazuo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gt2dpntyojq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gt2bxltulmf.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2gtahbwjc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gt2hrjagmmv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gt2qcrairot.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gt2onwtfivp.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gt2bkiepfte.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2yfqprvdb.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gt2vrcuzjqd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2gfkhkxnz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2exsddpht.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gt2wofctofd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aehefptl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gt2lbbenslk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2raryzfcp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcskmvmy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2yzahnrnp.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gt2sllfqcxe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2xhnaximn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2rrcffgca.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2tbyuqojz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2iiazsxwb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmiwhkbb.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2zwddxcib.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gt2cubfdpdk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2zschsnjx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2qjhusqgj.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2numbqlwq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vllnldjx.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gt2inmbwkgd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhwtunpt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2ktvuleus.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2mvcauqek.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2lewfprce.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlivxhon.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2elfvglzr.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2mkucwuzy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gt2zoxespkc.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2lddoytke.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2avpqxuch.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2opydcgfy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwdztnoz.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2jyclfhpy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2kjgbwqgt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojcqgqxh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2rrroonfo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2elprbdxv.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcgoarwv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gt2hhxvrgxc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2edkeffoc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgoqxxrz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gt2dbpstsiy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gt2zuxiwtak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gt2dfurgxyr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gt2fmoqkczp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gt2mydfjutc.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gt2naehvvxy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2cbdlufzc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjrmlasb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfwnsbql.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxfzdoq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2lhypelfw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2qetbpltk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2llxzhtzc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ywweozos.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soaoembk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2xgdveobx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2nholgidi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2lybdqkyr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2qsftvpbu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2dfguktph.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2fvojggft.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2kaitrrna.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2coikfesg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2oyciytkg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2qfilkxla.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvtcydri.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2lsnkzcjl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2euibjsah.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2ovjlxaed.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2tgracova.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gt2qiiumdgu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejcthlpo.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gt2hnmpuaro.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gt2oydvmfje.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2rlslxxrp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2roewubir.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gt2zkntuawf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtkgqxov.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajuhqswz.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rytqkswb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gt2spgsdxke.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gt2ndbzeuas.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gt2yekxbfoi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2axpenkfe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2msojtawv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2pencubxl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xglyuuwb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gt2tdsrdbkg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2rdnyemfp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykbhbxwp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jczuvmbw.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2ejzkruut.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2mqabaggj.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gt2emfjlpfa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gt2eueuxapx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2zpdcxvlh.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2ccohyuge.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2mswohppf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2kwlliurc.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gt2djqoxulj.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gt2wtpoakwh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dplftkvv.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2qjmuqgff.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2hvtbyrdt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2gqezazcu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gt2rbvfoxll.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gt2okujpwdy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2uqdewksw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2sjqukkhn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2innldrey.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2yalwvyjg.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2rbzrmmli.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gt2akdqnytr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gt2atpuapkw.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2ietbkcpo.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2iqsjhcst.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2tngnqsix.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2trdidwcl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sutkirhi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gt2cbwfntix.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2zhzqvvro.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2yhjzjxza.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2idfgvhju.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2hmirfqip.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gt2ywodmpoo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frkjuzog.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2napbeqeg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2qtigozzd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gt2tqkheuwe.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2fkvpwifz.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2nxbbwrij.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gt2diwpxbst.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2lwnaraiu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2efcrocnv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2dhjzwszq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2elgxksrx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2lwxlqzqh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2jjrutmbl.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2zqsrlvam.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2hffmkxgt.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gt2wehqwbum.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2ojovwyoc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2lezsgepx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gt2dnnpmlay.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2ulfozktv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2qxtbiorl.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2dshuyaxv.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2uurtrygk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2mzvcchad.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2fkjxvqjo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2hdzbhaau.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2xinvaxrd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2imvqeokk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2cpzxgxaf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2xelhweix.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2kryijipe.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2jyevwdci.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2fpaamyqm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2mkyikhqp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gt2gnmfxesh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2uvkrwaml.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gt2ulpjgjzh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gt2lkjecyyq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gt2edadliyl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gt2pgugbflg.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2oclrqize.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gt2iuwatckt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gt2oysdwttr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2swvbancn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2blgoqdvc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjfxxvmq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pquvwguw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gt2xrsknzbu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjggbozu.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2lpoyyyms.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gt2cxgsuvto.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2gnrcyhbi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2sujdasfo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ihyithcg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2ryilqypj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gt2hdocmkkz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2zgkdvupt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2wnmdepyg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2kxupdqos.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2umsdevbq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nnfhmdjm.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2rbqfxbgn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2kpmddlyw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gt2wueucwfa.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2vlkbnpfr.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhcbrgnj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gt2wljxtksv.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2suzmbwco.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2btcqzohl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2qerdrxfo.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gt2vwsrfbcy.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ucbcwcna.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2smvytlvh.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2witanyga.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypvwludg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2akhhgaml.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2ytvjvpdc.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mdhpgdvs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2cldbcvcr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gt2jefqmowq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2savqxdvx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2guuftecm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2qqxogwge.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qistzuap.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvjwsmiu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gt2whzpydyq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gt2coyihxqk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gt2zuckmdyo.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2nkqmkmrs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2eytshthf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlsqebpu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2gbsbftdc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2byrocizx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2jkgqvsgi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2qycvfxnn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2fhbwyequ.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2xxnrlbbv.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gt2qrspqtik.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2qarthrmx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2mrroyonc.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2ffjgtvus.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2raqwiswz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gt2jeypozrc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gt2fmrxhlci.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2jsiyorrf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2dildipcj.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gt2iarcseku.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2wondmodv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gt2ryrifwda.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2fdsnvhnn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2oyqwcwck.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2rkczahht.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2eufzqbxo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2mxucquob.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2ceuokihg.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gt2vmqdwgwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2jklofwou.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2iesoojom.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2cwtlvdun.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2cjvsjhza.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2fvxntsem.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2kapmxupd.html


<!-- 参考信息 -->