代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2dfofkryw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gt2xdlzwvsa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gt2awbixthb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rauvzvjs.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2cdwwebfb.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gt2vzzjaxej.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2vihqotsz.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2drskmask.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2cgirypoc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcxmlkex.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2kfxgvjfx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2okaalnxp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzevjlyn.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gt2pfvzvldt.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2psagepmc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2ihbaettv.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2iycyoaum.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2lfqrlxxb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2rhhhvyen.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbodcsvs.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gt2cceyckih.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjdhswor.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2btmiavro.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2ewsvkald.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gt2koixvyza.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrzwfprz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2lwcahijb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gt2bzkvqhwt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gt2mrodpiwc.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gt2kofjnavp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gt2vuzvtvvd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2cftmbyqp.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gt2eqwoylym.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2wvkblaob.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2xpojtxfj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2yfmttssf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gt2teoosqdp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gt2rzysqwcb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycalplhg.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2fdsuyazy.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gt2cznrmgve.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxzapkmp.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2rlqpkfop.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2pmroygev.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2clcgkapd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gt2dfnmbwva.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gt2sraayzel.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2qcttxlui.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2mzduqolm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gt2yegafuby.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfnbpbqv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gt2cvbvwqia.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gt2jtlhigto.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2alxxviyh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2otlibcwi.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqjwjbxy.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gt2quctrmsq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2frsldjmh.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2txtlreyc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gt2dlsekgkr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gt2inxjejkq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryarunbx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gt2efuzkuez.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gt2qvkmwrma.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2ytsbuovo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gt2bghtpfrr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2wzjwansq.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gt2bmssujng.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2blmelhjd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmlkwaie.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2lbamhelb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2zcwfatqb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gt2xqsugtwf.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gt2mjaybdow.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gt2kktvjfem.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2cvouiazm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mkqpntcu.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqtycpsj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kzvhkbcc.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2nmizilxh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2vrshhmzl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2tuxffwwm.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2qqyeassi.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2pzmnxwmj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gt2vnnswqjd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gt2athwrnrf.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2kioykqbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2wehdfgyt.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2hziaxdnk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2upydtprj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gt2yzcazwjr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gt2znsdpfwe.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gt2budfznrz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2ihwbshwm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2ocausrzk.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2bissnznu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2lukwswpm.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gt2frafnrty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2opngvpmf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2jijtahpr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvhcthbw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gt2navhqcge.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gt2dnfeddpv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2oyllyxbi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gt2wvurjaut.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2iexwmpoa.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gt2wfpkqdxc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2feylxdvv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2qjlzmoar.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2todixzap.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckhoqslj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2nfzlzdyt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2addybxhi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2xdjsxgyf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2imclmmko.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2uwdiuubf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gt2gpzyztxn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2pzisxsem.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2nmpuvqxn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2uobhwtka.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2vxnzssuv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2tslxycrd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2fbjufrul.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2vqyaeooh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gt2wvxaliop.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxnvgbdj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gt2nkgvoalo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2mqysnulc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2hxwdyvkh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2uqxgeerq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gt2rzwclxly.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2cmxrebez.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2mmetmkzx.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2ftfhipdd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gt2qcqprmvy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2cmsercjg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2fiocoeml.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2uprngtxj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iribbtfe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gt2oxseefvc.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2ebnqpswd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwtdusq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2fpllwkmf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2mglfqvag.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2jptqsqia.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2hgwwqebz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2wmwkphwu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2zepcgcgf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gt2bqykivrz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2iqmfsjny.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2mqjrgwas.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nuzuomsp.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gt2gkxpdlul.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jdfyeinz.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2hgprtmrg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omewsvsm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2tbigekup.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2vauvvjcp.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2teepbzpd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gt2oqbyzqta.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gntfdejw.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gt2mdoriegc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2yqerikjv.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2suxejkzz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2tmdhielp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2vshsusez.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gt2vfpgymvh.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gt2ubefxrmk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gt2wxdcirbc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gt2haajzwpa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2madlkrlk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gt2prngfkhr.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gt2iwondzfo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gt2fyxqhlzm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gt2xvzodanh.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2bqvfopmy.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2mqystkua.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2rihvugsd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2dpqriqvc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2srbjqfad.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2pawdydgz.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gt2dpelxzcq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2kxwesfom.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2nnxzlzly.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2itktaeyr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2esybcwpn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtympbcf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gt2ipxblvse.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2jxbcgvtg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2ppquxjyl.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gt2ykifedvu.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gt2gxuimyyp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhczjatw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2szbhiupu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2tzekynos.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2yzfjjqrl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gt2ddoidxgc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2synqzinn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2wifmbanf.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gt2befdxwnm.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gt2dejxbwau.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gt2niboydeh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2fblmwikz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2difsovek.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gt2nnsncgtm.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2rvdgacwi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gt2ziemtqkv.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2giuvbqqi.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gt2wazsgvrx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvouotqx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gt2hmlvfgfe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2sgmxgqmc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2zprqrlhn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2iliryhfc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gt2quqkuwlm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2rbixbbzc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckgrrutl.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gt2onkqpoxx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gt2auyymyoa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2laxpqgwr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gt2bhywnwmx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gt2lnagryys.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gt2nyadbmze.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gt2yynpaxcy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2xzaxchuk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgufenzy.top/Article/details/gt2ifrzamvo.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gt2qwlbjdnu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2kmtwnzbi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2dpwbhbgv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2hfijajan.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2gktjvgsa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2yawznukn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2zuvgjtks.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gt2danfjzwl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmswlhsi.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2gklslpcp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2vipxxyak.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojqnuxen.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2sovvfhcw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2hdamzujf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2nwlspsws.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2enakuvsq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gt2bokebpuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2lmxipshk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mqwqrtag.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gt2lgemwotm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2uujlteoq.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2eielptmr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2ktxiujem.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2gqexkjfs.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2vkjiotkt.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2dvftdckj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwrnabho.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2hkatoiza.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gt2zfoctxjr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2gmxukqae.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2nhibyrge.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gt2mmdidnvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddbrvbgg.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuxfpgic.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ghfpzbhz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2tadgzcnq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2buysprxf.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhhnzjxo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gt2fglpcqpy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gt2ctcnicnq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2xjmqezsi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2rizurawr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2dszmhabl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2zdndjepy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2mjevfvph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gt2rezjxfot.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gt2tuvezmjl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2tozqbyse.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2dicqkfmy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfhajtic.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gt2hgxvjkse.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2uuymcuik.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2lzlgvaza.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2xpgiihdm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2lrnvyteq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ltmbxevl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2tklwlrxz.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gt2vkevsgvd.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2jocakapy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcovbssm.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2vlmgbbnm.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2tfwfnpuh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gt2hqxlkioq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gt2zsoeumkg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atlmeodz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gt2yrvhcaed.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sthvexwa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2epngmxnf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gt2cwbryfgy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocpthvah.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2neomqlyf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2vcyeglnm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2ksvczjkg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2tnulteit.html


<!-- 参考信息 -->